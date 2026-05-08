# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/3p-integrations/crusoe/vllm-fp8/benchmarks/backend_request_func.py

Prompts

```
['run an async streaming request to an OpenAI completions API endpoint and measure latency', 'run an async streaming request to an OpenAI chat completions API and collect token latencies', 'run an async streaming request to a Text Generation Inference server and measure TTFT', 'run an async streaming request to a TensorRT-LLM server and collect inter-token latencies', 'run an async non-streaming request to a DeepSpeed-MII server and measure response latency', 'run a serving throughput benchmark against a vLLM or TGI backend using sharegpt, sonnet, or random datasets', 'sample and tokenize requests from a ShareGPT JSON dataset for serving benchmark workloads', 'sample requests from a sonnet poem dataset with configurable input, output, and prefix token lengths', 'generate random token-based requests with configurable input and output length ranges for benchmarking', 'calculate serving benchmark metrics including TTFT, TPOT, ITL, and throughput from benchmark outputs']
```

Usage

```
{'run_async_request_openai_completions': 'run an async streaming request to an OpenAI completions API endpoint and measure latency', 'run_async_request_openai_chat_completions': 'run an async streaming request to an OpenAI chat completions API and collect token latencies', 'run_async_request_tgi': 'run an async streaming request to a Text Generation Inference server and measure TTFT', 'run_async_request_trt_llm': 'run an async streaming request to a TensorRT-LLM server and collect inter-token latencies', 'run_async_request_deepspeed_mii': 'run an async non-streaming request to a DeepSpeed-MII server and measure response latency'}
```

## File: facebookresearch_llama-recipes/3p-integrations/crusoe/vllm-fp8/benchmarks/benchmark_serving.py

Prompts

```
['run an async streaming request to an OpenAI completions API endpoint and measure latency', 'run an async streaming request to an OpenAI chat completions API and collect token latencies', 'run an async streaming request to a Text Generation Inference server and measure TTFT', 'run an async streaming request to a TensorRT-LLM server and collect inter-token latencies', 'run an async non-streaming request to a DeepSpeed-MII server and measure response latency', 'run a serving throughput benchmark against a vLLM or TGI backend using sharegpt, sonnet, or random datasets', 'sample and tokenize requests from a ShareGPT JSON dataset for serving benchmark workloads', 'sample requests from a sonnet poem dataset with configurable input, output, and prefix token lengths', 'generate random token-based requests with configurable input and output length ranges for benchmarking', 'calculate serving benchmark metrics including TTFT, TPOT, ITL, and throughput from benchmark outputs']
```

Usage

```
{'run_benchmark_serving': 'run a serving throughput benchmark against a vLLM or TGI backend using sharegpt, sonnet, or random datasets', 'sample_sharegpt_requests': 'sample and tokenize requests from a ShareGPT JSON dataset for serving benchmark workloads', 'sample_sonnet_requests': 'sample requests from a sonnet poem dataset with configurable input, output, and prefix token lengths', 'sample_random_requests': 'generate random token-based requests with configurable input and output length ranges for benchmarking', 'calculate_metrics': 'calculate serving benchmark metrics including TTFT, TPOT, ITL, and throughput from benchmark outputs'}
```

