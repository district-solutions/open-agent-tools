# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/examples/generate/batched_chat_completions_online.py

Prompts

```
['run the batched chat completions examples against a vLLM server via the OpenAI-compatible API', 'send a batch of conversations to the vLLM chat completions batch endpoint and return JSON responses', 'send multiple plain text conversations in a single batched request to the vLLM model', 'send a batched chat request with a regex structured output constraint to force yes or no answers', 'send a batched chat request with a JSON schema response format to extract structured data from text', 'run the qwen 1m offline example to generate text with a 600k token prompt using vLLM', 'initialize a vLLM engine with the Qwen2.5-7B-Instruct-1M model and 1M context length', 'create sampling parameters with temperature, top_p, top_k, and repetition penalty for text generation', 'process a list of prompts through the LLM and print generated text with prompt length', 'load a test prompt from a remote URL for long context testing']
```

Usage

```
{'run_batched_chat_completions': 'run the batched chat completions examples against a vLLM server via the OpenAI-compatible API', 'post_batch_endpoint': 'send a batch of conversations to the vLLM chat completions batch endpoint and return JSON responses', 'batch_plain_text_conversations': 'send multiple plain text conversations in a single batched request to the vLLM model', 'batch_with_regex_constraint': 'send a batched chat request with a regex structured output constraint to force yes or no answers', 'batch_with_json_schema': 'send a batched chat request with a JSON schema response format to extract structured data from text'}
```

## File: vllm-project_vllm/examples/generate/qwen_1m_offline.py

Prompts

```
['run the batched chat completions examples against a vLLM server via the OpenAI-compatible API', 'send a batch of conversations to the vLLM chat completions batch endpoint and return JSON responses', 'send multiple plain text conversations in a single batched request to the vLLM model', 'send a batched chat request with a regex structured output constraint to force yes or no answers', 'send a batched chat request with a JSON schema response format to extract structured data from text', 'run the qwen 1m offline example to generate text with a 600k token prompt using vLLM', 'initialize a vLLM engine with the Qwen2.5-7B-Instruct-1M model and 1M context length', 'create sampling parameters with temperature, top_p, top_k, and repetition penalty for text generation', 'process a list of prompts through the LLM and print generated text with prompt length', 'load a test prompt from a remote URL for long context testing']
```

Usage

```
{'run_qwen_1m_offline': 'run the qwen 1m offline example to generate text with a 600k token prompt using vLLM', 'initialize_llm_engine': 'initialize a vLLM engine with the Qwen2.5-7B-Instruct-1M model and 1M context length', 'create_sampling_params': 'create sampling parameters with temperature, top_p, top_k, and repetition penalty for text generation', 'process_llm_requests': 'process a list of prompts through the LLM and print generated text with prompt length', 'load_prompt_from_url': 'load a test prompt from a remote URL for long context testing'}
```

