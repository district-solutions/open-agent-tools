# Agent Python Tools

- repo: facebookresearch/llm-speedrunner
- repo_uri: https://github.com/facebookresearch/llm-speedrunner

## File: facebookresearch_llm-speedrunner/serve_vllm.py

Prompts

```
['run a vLLM server for the DeepSeek-R1-Distill-Qwen-32B model with tensor parallelism and prefix caching', 'submit a vLLM server job to a SLURM cluster using submitit with 2 GPUs and 70GB memory', 'configure a submitit AutoExecutor with timeout, GPU, CPU, and memory parameters for SLURM job submission', 'run the DeepSeek-R1-Distill-Qwen-32B model via vLLM with 90% GPU memory utilization and 2-way tensor parallelism', 'submit an LLM serving job to SLURM under the ram account with dev QoS using submitit', 'run a flask server that proxies OpenAI chat completions to AWS Bedrock Claude models', 'create an AWS Bedrock runtime client by assuming the BedrockReadOnly IAM role via STS', 'count the number of tokens in a text string using tiktoken with gpt-4 encoding', 'truncate a conversation body to keep only the most recent messages within a token limit', 'generate a streaming SSE response from Bedrock Claude that mimics OpenAI chat completion chunks']
```

Usage

```
{'run_vllm_server': 'run a vLLM server for the DeepSeek-R1-Distill-Qwen-32B model with tensor parallelism and prefix caching', 'submit_vllm_job': 'submit a vLLM server job to a SLURM cluster using submitit with 2 GPUs and 70GB memory', 'configure_submitit_executor': 'configure a submitit AutoExecutor with timeout, GPU, CPU, and memory parameters for SLURM job submission', 'run_deepseek_inference': 'run the DeepSeek-R1-Distill-Qwen-32B model via vLLM with 90% GPU memory utilization and 2-way tensor parallelism', 'submit_slurm_llm_job': 'submit an LLM serving job to SLURM under the ram account with dev QoS using submitit'}
```

## File: facebookresearch_llm-speedrunner/setup_claude_openai_compatible_api.py

Prompts

```
['run a vLLM server for the DeepSeek-R1-Distill-Qwen-32B model with tensor parallelism and prefix caching', 'submit a vLLM server job to a SLURM cluster using submitit with 2 GPUs and 70GB memory', 'configure a submitit AutoExecutor with timeout, GPU, CPU, and memory parameters for SLURM job submission', 'run the DeepSeek-R1-Distill-Qwen-32B model via vLLM with 90% GPU memory utilization and 2-way tensor parallelism', 'submit an LLM serving job to SLURM under the ram account with dev QoS using submitit', 'run a flask server that proxies OpenAI chat completions to AWS Bedrock Claude models', 'create an AWS Bedrock runtime client by assuming the BedrockReadOnly IAM role via STS', 'count the number of tokens in a text string using tiktoken with gpt-4 encoding', 'truncate a conversation body to keep only the most recent messages within a token limit', 'generate a streaming SSE response from Bedrock Claude that mimics OpenAI chat completion chunks']
```

Usage

```
{'run_claude_proxy_server': 'run a flask server that proxies OpenAI chat completions to AWS Bedrock Claude models', 'create_bedrock_client': 'create an AWS Bedrock runtime client by assuming the BedrockReadOnly IAM role via STS', 'count_tokens_text': 'count the number of tokens in a text string using tiktoken with gpt-4 encoding', 'truncate_conversation_tokens': 'truncate a conversation body to keep only the most recent messages within a token limit', 'generate_streaming_response': 'generate a streaming SSE response from Bedrock Claude that mimics OpenAI chat completion chunks'}
```

