# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/end-to-end-use-cases/benchmarks/inference/on_prem/vllm/chat_vllm_benchmark.py

Prompts

```
['run the vLLM chat benchmark across concurrent request levels and save metrics to CSV', 'run evaluate_performance with a given number of concurrent requests to measure latency and throughput', 'run generate_text to send a single chat completion request to a vLLM endpoint with round-robin dispatch', 'run analyze_prompt to check a text input against Azure content safety and measure round-trip latency', 'review evaluate_performance to understand how P50/P99 latency, RPS, and tokens per second are calculated', 'create a random prompt with a specified number of tokens using the model tokenizer vocabulary', 'send a text prompt to Azure Content Safety API for safety analysis and filtering', 'evaluate vLLM endpoint performance by sending concurrent requests and measuring P50, P99 latency and throughput', 'send a chat completion request to a vLLM endpoint using round-robin load balancing across multiple endpoints']
```

Usage

```
{'run_vllm_benchmark': 'run the vLLM chat benchmark across concurrent request levels and save metrics to CSV', 'run_evaluate_performance': 'run evaluate_performance with a given number of concurrent requests to measure latency and throughput', 'run_generate_text': 'run generate_text to send a single chat completion request to a vLLM endpoint with round-robin dispatch', 'run_analyze_prompt': 'run analyze_prompt to check a text input against Azure content safety and measure round-trip latency', 'review_evaluate_performance': 'review evaluate_performance to understand how P50/P99 latency, RPS, and tokens per second are calculated'}
```

## File: facebookresearch_llama-recipes/end-to-end-use-cases/benchmarks/inference/on_prem/vllm/pretrained_vllm_benchmark.py

Prompts

```
['run the vLLM chat benchmark across concurrent request levels and save metrics to CSV', 'run evaluate_performance with a given number of concurrent requests to measure latency and throughput', 'run generate_text to send a single chat completion request to a vLLM endpoint with round-robin dispatch', 'run analyze_prompt to check a text input against Azure content safety and measure round-trip latency', 'review evaluate_performance to understand how P50/P99 latency, RPS, and tokens per second are calculated', 'create a random prompt with a specified number of tokens using the model tokenizer vocabulary', 'send a text prompt to Azure Content Safety API for safety analysis and filtering', 'evaluate vLLM endpoint performance by sending concurrent requests and measuring P50, P99 latency and throughput', 'send a chat completion request to a vLLM endpoint using round-robin load balancing across multiple endpoints']
```

Usage

```
{'run_vllm_benchmark': 'run a vLLM inference benchmark measuring latency, RPS, and tokens per second across concurrent request levels', 'generate_random_prompt': 'create a random prompt with a specified number of tokens using the model tokenizer vocabulary', 'analyze_prompt_safety': 'send a text prompt to Azure Content Safety API for safety analysis and filtering', 'evaluate_concurrent_performance': 'evaluate vLLM endpoint performance by sending concurrent requests and measuring P50, P99 latency and throughput', 'generate_text_from_endpoint': 'send a chat completion request to a vLLM endpoint using round-robin load balancing across multiple endpoints'}
```

