# OpenAgent Tools (OATs)

- A repo for those trying to power up small-to-large models with a tool-calling prompt index we're calling the [OpenAgent Tools Protocol (OATs)](https://openagent.tools). Using OATs lets developer and security teams curate supported tools with easy-to-edit json and markdown files.

- We wanted to share how to compile a dataset with a tool-calling segmentation approach.

- OATs is a self-hosted tool-calling approach for agents and humans to align on approved tools.

- The initial use case is moderating multi-agentic tool discovery, guidance, resolution and usage on a filesystem containing 20600+ git repos using over 2.1 TB disk space.

![OpenAgent Tools - Architecture - Intro Tool Calling Pipeline for Powering Up Small AI Models](https://raw.githubusercontent.com/district-solutions/open-agent-tools/refs/heads/main/docs/open-agent-tools-intro-tool-calling-pipeline-for-powering-up-small-ai-models.jpg)

## The Problem

Large language models (LLMs) require expensive GPU infrastructure. This project explores how we enabled **small tool-calling models** like Google's **FunctionGemma (functiongemma-270m-it)** to accurately determine the correct tool, source code, function, and API across many repositories — without needing large GPUs.

## The Idea: A Prompt Index for Small Function-Calling Models

By data-mining leading AI repositories, we started preprocessing the source code across multiple passes. Each pass continues to extract, learn, and compress the source code into structured, indices that a small model can semantically use to match with "similar" prompts to the "best" tools and the underlying source code.

The result is a **fast, high-quality tool-calling approach that hopefully runs on constrained hardware with many plug-and-play tools**.

- We also publish a parquet file to the [OpenAgent Tools dataset on Huggingface](https://huggingface.co/datasets/open-agent-tools/open-tools) that complements the json files in the root repo directory.

- There are over **111,000** tool-calling ready-to-use rows in the [OATs 20260504 parquet collected from 158 leading ai-centric/ai-adjacent github repos](https://huggingface.co/datasets/open-agent-tools/open-tools/blob/main/dataset.open-agent-tools.ai-repos.repo-uses.20260504.parquet).

- Reach out if you want to add a new repo!!

### Validated Models

- [google/functiongemma-270m-it](https://huggingface.co/google/functiongemma-270m-it)

### Inference Harness Component Inspiration

- [Google Colab - Full function calling sequence with FunctionGemma](https://colab.research.google.com/github/google-gemma/cookbook/blob/main/docs/functiongemma/full-function-calling-sequence-with-functiongemma.ipynb)
- [HuggingFace Transformers Apply Chat Template with Include Tools](https://github.com/huggingface/transformers/blob/53b92b94ed7e48ff5db11b88a271cb8941c2df9e/src/transformers/processing_utils.py#L1671)
- [HuggingFace FunctionGemma Basic Usage](https://huggingface.co/google/functiongemma-270m-it#basic-usage)
- [HuggingFace Function Calling](https://huggingface.co/docs/hugs/guides/function-calling)
- [HuggingFace Tool Use](https://huggingface.co/docs/transformers/chat_extras)
- [HuggingFace Tool Calling Server](https://github.com/huggingface/transformers/blob/53b92b94ed7e48ff5db11b88a271cb8941c2df9e/docs/source/en/serve-cli/serving.md#tool-calling)
- [HuggingFace Tiny Agent Server](https://github.com/huggingface/transformers/blob/53b92b94ed7e48ff5db11b88a271cb8941c2df9e/docs/source/en/serve-cli/tiny_agents.md)
- [HuggingFace Chat Templating](https://github.com/huggingface/transformers/blob/53b92b94ed7e48ff5db11b88a271cb8941c2df9e/docs/source/en/chat_templating.md)
- [HuggingFace Transformers AutoProcessor](https://github.com/huggingface/transformers/blob/53b92b94ed7e48ff5db11b88a271cb8941c2df9e/src/transformers/models/auto/processing_auto.py#L219)
- [Unsloth FunctionGemma Tutorial](https://unsloth.ai/docs/models/tutorials/functiongemma)
- [Open WebUI Tool Calling](https://docs.openwebui.com/features/extensibility/plugin/tools/)
- [Open WebUI Function Calling](https://docs.openwebui.com/features/extensibility/plugin/functions/)
- [Open WebUI Skills](https://docs.openwebui.com/features/open-terminal/use-cases/advanced-workflows/#what-are-skills)
- [Open WebUI Tool Servers](https://github.com/open-webui/openapi-servers/)
- [LiteLLM Tool Calling](https://docs.litellm.ai/docs/completion/function_call)
- [LiteLLM Completion Function API](https://docs.litellm.ai/completion/input)
- [vLLM Tool Calling SDK](https://docs.vllm.ai/en/stable/features/tool_calling/)
- [vLLM Tool Calling with OpenAI Completion Protocol](https://docs.vllm.ai/en/stable/examples/online_serving/openai_chat_completion_client_with_tools/)
- [vLLM Function Gemma Tool Call Parser](https://docs.vllm.ai/en/stable/features/tool_calling/?h=functiongemma#functiongemma-models-functiongemma)

---

## Architecture Overview

The system has three main components that work together in a pipeline:

Source Repos → CodeWalker (crawl + annotate) → Protocol Compiler (aggregate) creates Index → Setup Tool Calling Pipeline to Use Index → FunctionGemma (infer)

## The Full Pipeline

### Artifacts - Tool Indices

We run this pipeline to manage 3 types of artifacts for the Protocol Index JSON file:

1) per python file aka the ``.py.AGENT.python.tools.json`` file for detailed chunks.
2) per directory aka the ``dir`` file for a detailed summary.
3) per repo aka the ``repo_uses`` file for a reference to the top tool uses and tool prompts for each python file.

### Workflow

1) Crawl & Annotate

    ```
    tool.py -d /path/to/repo
    ```

    → Generates ``.AGENT.python.tools.json`` breadcrumbs for all source

2) Compile Protocol into an Index JSON file

    ```
    compile_protocol_for_dir.py -d /path/to/repo
    ```

    → Aggregates breadcrumbs + AST data into CoderToolManifest
    store the ``AGENT.repo_uses.python.tools.json`` file in a repo base dir: ``.ai/AGENT.repo_uses.python.tools.json`` or in other warm storage options: redis, s3, postgres.

3) Setup Tool Calling Harness to Use Index and Infer with Small Model

    Focused on a fast, cheap, quality harness that can keep all models in memory without downtime. we integrated a lightweight model to "determine the best tool" using BM25. cross-encoder validation supported is available but was not needed at the moment because of the high quality results.

    → BM25 retrieval → sorted results containing the initial list of source files and uses the tool-calling model should try next.

4) Infer with Small Model using similarities how we think about python source code

    ```
    start_harness.py -p "get utc"
    ```

    → BM25 retrieval → FunctionGemma tool selection → tool execution -> done

## Why This Matters

AI Reasons

- **No large GPUs needed:** FunctionGemma 270M runs on consumer hardware.
- **Simple user prompts work:** A query like ``get utc`` matches across all relevant source code spanning hundreds of repositories.
- **Prompt index replaces brute-force search:** Preprocessed semantic breadcrumbs let the model match on compressed, highly-qualified text chunks instead of scanning raw source code.
- **Scalable across repos:** The crawl → compile → infer pipeline works on any python repository.

Human Reasons

- We have 1000s of pre-ai, home-grown command line tools this approach already works with and we wanted to share.
- We wanted to help others build similar solutions.
- We want to hear ways we can make this better.
- Reduce the large cloud models dependencies by recording and curating how self-hosted long-running tool calling chains perform. Capturing this data enables your team to train and finetune your own internal models on preferred tool chain pathways (tool graph efficiency optimization).


---

## Using the Dataset on Hugging Face

We are releasing the index tool calling files and the [open-agent-tools dataset](https://huggingface.co/datasets/open-agent-tools/open-tools) on Hugging Face. You can use the Hugging Face model [google/functiongemma-270m-it](https://huggingface.co/google/functiongemma-270m-it) with the repo-level, directory-level, or source code file in these repos.

The protocol allows you to leverage the small model with:

1. **Repo-level:** Full repository contexts compiled into manifests.
2. **Directory-level:** Specific subdirectories and their associated tools.
3. **File-level:** Individual source code files and their semantic breadcrumbs.

This enables flexible, lightweight function calling without requiring large-scale GPU resources.
