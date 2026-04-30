# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/examples/online_serving/disaggregated_serving/disagg_proxy_demo.py

Prompts

```
['run a disaggregated prefilling proxy server with vLLM prefill and decode instances', 'create a Proxy instance with prefill and decode node lists and a scheduling policy', 'build a RoundRobinSchedulingPolicy to distribute requests across prefill and decode instances', 'test the ProxyServer.validate_instances method to verify host:port format and port range', 'review the add_instance_endpoint API to dynamically add prefill or decode nodes at runtime', 'run a fastapi proxy server for disaggregated prefill decode with bidirectional KV cache transfer across multi-turn conversations', 'create a per-conversation KV block cache with TTL-based eviction for storing decode node transfer parameters between turns', 'send a non-streaming prefill request to the prefill node with cached KV transfer params from the previous decode turn', 'stream the completion response from the decode node while capturing KV transfer params for the next conversation turn', 'handle a chat or completion request by routing through prefill then decode nodes with cross-turn KV cache reuse', 'run the disaggregated multimodal serving example that renders and generates with a test image', 'create a base64 data URL from a PIL image for use in multimodal API requests', 'test the v1/chat/completions/render endpoint to preprocess a multimodal chat request into token IDs', 'test the inference/v1/generate endpoint to run inference on preprocessed tokens with sampling params', 'summarize the main function that orchestrates the render-then-generate disaggregated serving flow', 'start service discovery for MoRIIO disaggregated serving on a given hostname and port', 'run the MoRIIO toy proxy server that routes requests between prefill and decode instances', 'send a request to a prefill instance with remote decode parameters for disaggregated serving', 'stream decode responses from a decode instance as byte chunks over HTTP', 'handle incoming completions or chat completions requests via the proxy server routes']
```

Usage

```
{'run_disagg_proxy_server': 'run a disaggregated prefilling proxy server with vLLM prefill and decode instances', 'create_proxy_instances': 'create a Proxy instance with prefill and decode node lists and a scheduling policy', 'build_round_robin_scheduler': 'build a RoundRobinSchedulingPolicy to distribute requests across prefill and decode instances', 'test_validate_instances': 'test the ProxyServer.validate_instances method to verify host:port format and port range', 'review_add_instance_endpoint': 'review the add_instance_endpoint API to dynamically add prefill or decode nodes at runtime'}
```

## File: vllm-project_vllm/examples/online_serving/disaggregated_serving/disagg_proxy_multiturn.py

Prompts

```
['run a disaggregated prefilling proxy server with vLLM prefill and decode instances', 'create a Proxy instance with prefill and decode node lists and a scheduling policy', 'build a RoundRobinSchedulingPolicy to distribute requests across prefill and decode instances', 'test the ProxyServer.validate_instances method to verify host:port format and port range', 'review the add_instance_endpoint API to dynamically add prefill or decode nodes at runtime', 'run a fastapi proxy server for disaggregated prefill decode with bidirectional KV cache transfer across multi-turn conversations', 'create a per-conversation KV block cache with TTL-based eviction for storing decode node transfer parameters between turns', 'send a non-streaming prefill request to the prefill node with cached KV transfer params from the previous decode turn', 'stream the completion response from the decode node while capturing KV transfer params for the next conversation turn', 'handle a chat or completion request by routing through prefill then decode nodes with cross-turn KV cache reuse', 'run the disaggregated multimodal serving example that renders and generates with a test image', 'create a base64 data URL from a PIL image for use in multimodal API requests', 'test the v1/chat/completions/render endpoint to preprocess a multimodal chat request into token IDs', 'test the inference/v1/generate endpoint to run inference on preprocessed tokens with sampling params', 'summarize the main function that orchestrates the render-then-generate disaggregated serving flow', 'start service discovery for MoRIIO disaggregated serving on a given hostname and port', 'run the MoRIIO toy proxy server that routes requests between prefill and decode instances', 'send a request to a prefill instance with remote decode parameters for disaggregated serving', 'stream decode responses from a decode instance as byte chunks over HTTP', 'handle incoming completions or chat completions requests via the proxy server routes']
```

Usage

```
{'run_disagg_proxy_multiturn': 'run a fastapi proxy server for disaggregated prefill decode with bidirectional KV cache transfer across multi-turn conversations', 'create_conversation_kv_cache': 'create a per-conversation KV block cache with TTL-based eviction for storing decode node transfer parameters between turns', 'send_to_prefill': 'send a non-streaming prefill request to the prefill node with cached KV transfer params from the previous decode turn', 'stream_from_decode': 'stream the completion response from the decode node while capturing KV transfer params for the next conversation turn', 'handle_multiturn_request': 'handle a chat or completion request by routing through prefill then decode nodes with cross-turn KV cache reuse'}
```

## File: vllm-project_vllm/examples/online_serving/disaggregated_serving/example_mm_serve.py

Prompts

```
['run a disaggregated prefilling proxy server with vLLM prefill and decode instances', 'create a Proxy instance with prefill and decode node lists and a scheduling policy', 'build a RoundRobinSchedulingPolicy to distribute requests across prefill and decode instances', 'test the ProxyServer.validate_instances method to verify host:port format and port range', 'review the add_instance_endpoint API to dynamically add prefill or decode nodes at runtime', 'run a fastapi proxy server for disaggregated prefill decode with bidirectional KV cache transfer across multi-turn conversations', 'create a per-conversation KV block cache with TTL-based eviction for storing decode node transfer parameters between turns', 'send a non-streaming prefill request to the prefill node with cached KV transfer params from the previous decode turn', 'stream the completion response from the decode node while capturing KV transfer params for the next conversation turn', 'handle a chat or completion request by routing through prefill then decode nodes with cross-turn KV cache reuse', 'run the disaggregated multimodal serving example that renders and generates with a test image', 'create a base64 data URL from a PIL image for use in multimodal API requests', 'test the v1/chat/completions/render endpoint to preprocess a multimodal chat request into token IDs', 'test the inference/v1/generate endpoint to run inference on preprocessed tokens with sampling params', 'summarize the main function that orchestrates the render-then-generate disaggregated serving flow', 'start service discovery for MoRIIO disaggregated serving on a given hostname and port', 'run the MoRIIO toy proxy server that routes requests between prefill and decode instances', 'send a request to a prefill instance with remote decode parameters for disaggregated serving', 'stream decode responses from a decode instance as byte chunks over HTTP', 'handle incoming completions or chat completions requests via the proxy server routes']
```

Usage

```
{'run_example_mm_serve': 'run the disaggregated multimodal serving example that renders and generates with a test image', 'create_make_data_url': 'create a base64 data URL from a PIL image for use in multimodal API requests', 'test_render_endpoint': 'test the v1/chat/completions/render endpoint to preprocess a multimodal chat request into token IDs', 'test_generate_endpoint': 'test the inference/v1/generate endpoint to run inference on preprocessed tokens with sampling params', 'summarize_main': 'summarize the main function that orchestrates the render-then-generate disaggregated serving flow'}
```

## File: vllm-project_vllm/examples/online_serving/disaggregated_serving/moriio_toy_proxy_server.py

Prompts

```
['run a disaggregated prefilling proxy server with vLLM prefill and decode instances', 'create a Proxy instance with prefill and decode node lists and a scheduling policy', 'build a RoundRobinSchedulingPolicy to distribute requests across prefill and decode instances', 'test the ProxyServer.validate_instances method to verify host:port format and port range', 'review the add_instance_endpoint API to dynamically add prefill or decode nodes at runtime', 'run a fastapi proxy server for disaggregated prefill decode with bidirectional KV cache transfer across multi-turn conversations', 'create a per-conversation KV block cache with TTL-based eviction for storing decode node transfer parameters between turns', 'send a non-streaming prefill request to the prefill node with cached KV transfer params from the previous decode turn', 'stream the completion response from the decode node while capturing KV transfer params for the next conversation turn', 'handle a chat or completion request by routing through prefill then decode nodes with cross-turn KV cache reuse', 'run the disaggregated multimodal serving example that renders and generates with a test image', 'create a base64 data URL from a PIL image for use in multimodal API requests', 'test the v1/chat/completions/render endpoint to preprocess a multimodal chat request into token IDs', 'test the inference/v1/generate endpoint to run inference on preprocessed tokens with sampling params', 'summarize the main function that orchestrates the render-then-generate disaggregated serving flow', 'start service discovery for MoRIIO disaggregated serving on a given hostname and port', 'run the MoRIIO toy proxy server that routes requests between prefill and decode instances', 'send a request to a prefill instance with remote decode parameters for disaggregated serving', 'stream decode responses from a decode instance as byte chunks over HTTP', 'handle incoming completions or chat completions requests via the proxy server routes']
```

Usage

```
{'start_service_discovery': 'start service discovery for MoRIIO disaggregated serving on a given hostname and port', 'run_proxy_server': 'run the MoRIIO toy proxy server that routes requests between prefill and decode instances', 'send_request_to_prefill': 'send a request to a prefill instance with remote decode parameters for disaggregated serving', 'stream_decode_response': 'stream decode responses from a decode instance as byte chunks over HTTP', 'handle_request': 'handle incoming completions or chat completions requests via the proxy server routes'}
```

