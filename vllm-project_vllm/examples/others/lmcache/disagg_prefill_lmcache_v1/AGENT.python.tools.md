# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/examples/others/lmcache/disagg_prefill_lmcache_v1/disagg_proxy_server.py

Prompts

```
['run a FastAPI proxy server that routes prefill to one service and streaming decode to another', 'parse command-line arguments for proxy host, port, prefiller host and port, and decoder host and port', 'send a request to a prefill or decode service with a persistent httpx client and override max_tokens to 1', 'stream response chunks from a prefill or decode service endpoint asynchronously', 'compute and log average, median, and 99th percentile prefill node TTFT stats every 5 seconds']
```

Usage

```
{'run_disagg_proxy_server': 'run a FastAPI proxy server that routes prefill to one service and streaming decode to another', 'parse_proxy_arguments': 'parse command-line arguments for proxy host, port, prefiller host and port, and decoder host and port', 'send_request_to_service': 'send a request to a prefill or decode service with a persistent httpx client and override max_tokens to 1', 'stream_service_response': 'stream response chunks from a prefill or decode service endpoint asynchronously', 'compute_latency_stats': 'compute and log average, median, and 99th percentile prefill node TTFT stats every 5 seconds'}
```

