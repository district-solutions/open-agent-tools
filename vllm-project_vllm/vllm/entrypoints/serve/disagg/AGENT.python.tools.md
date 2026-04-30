# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/serve/disagg/api_router.py

Prompts

```
['build a fastapi API router that provides a POST /inference/v1/generate endpoint for disaggregated vLLM inference', 'create a POST endpoint that accepts GenerateRequest and returns streaming or JSON GenerateResponse', 'test the abort_requests endpoint that cancels one or more inference requests by request_ids', 'refactor the attach_router function to conditionally register abort_requests when tokens_only is enabled', 'summarize the engine_client dependency that retrieves EngineClient from FastAPI app state', 'encode a MultiModalKwargsItem to a base64 string for JSON/HTTP transmission', 'decode a base64 string back to a MultiModalKwargsItem from JSON/HTTP data', 'create a MsgpackEncoder instance with a large size threshold to force all tensors inline', 'create a MsgpackDecoder instance parameterized with MultiModalKwargsItem type', 'test encoding and decoding roundtrip of a MultiModalKwargsItem through base64 serialization', 'create a PlaceholderRangeInfo model with offset and length for multi-modal placeholder token locations', 'create a MultiModalFeatures model with per-modality hashes, placeholder ranges, and serialized tensor data', 'create a GenerateRequest model with token ids, sampling params, and optional multimodal features for disaggregated serving', 'build TokenizeParams from a GenerateRequest using its build_tok_params method with a ModelConfig', 'create a GenerateResponse model with request id, choices, prompt logprobs, and kv transfer params for disaggregated serving']
```

Usage

```
{'build_fastapi_disagg_router': 'build a fastapi API router that provides a POST /inference/v1/generate endpoint for disaggregated vLLM inference', 'create_generate_endpoint': 'create a POST endpoint that accepts GenerateRequest and returns streaming or JSON GenerateResponse', 'test_abort_requests': 'test the abort_requests endpoint that cancels one or more inference requests by request_ids', 'refactor_attach_router': 'refactor the attach_router function to conditionally register abort_requests when tokens_only is enabled', 'summarize_engine_client_dep': 'summarize the engine_client dependency that retrieves EngineClient from FastAPI app state'}
```

## File: vllm-project_vllm/vllm/entrypoints/serve/disagg/mm_serde.py

Prompts

```
['build a fastapi API router that provides a POST /inference/v1/generate endpoint for disaggregated vLLM inference', 'create a POST endpoint that accepts GenerateRequest and returns streaming or JSON GenerateResponse', 'test the abort_requests endpoint that cancels one or more inference requests by request_ids', 'refactor the attach_router function to conditionally register abort_requests when tokens_only is enabled', 'summarize the engine_client dependency that retrieves EngineClient from FastAPI app state', 'encode a MultiModalKwargsItem to a base64 string for JSON/HTTP transmission', 'decode a base64 string back to a MultiModalKwargsItem from JSON/HTTP data', 'create a MsgpackEncoder instance with a large size threshold to force all tensors inline', 'create a MsgpackDecoder instance parameterized with MultiModalKwargsItem type', 'test encoding and decoding roundtrip of a MultiModalKwargsItem through base64 serialization', 'create a PlaceholderRangeInfo model with offset and length for multi-modal placeholder token locations', 'create a MultiModalFeatures model with per-modality hashes, placeholder ranges, and serialized tensor data', 'create a GenerateRequest model with token ids, sampling params, and optional multimodal features for disaggregated serving', 'build TokenizeParams from a GenerateRequest using its build_tok_params method with a ModelConfig', 'create a GenerateResponse model with request id, choices, prompt logprobs, and kv transfer params for disaggregated serving']
```

Usage

```
{'encode_mm_kwargs_item': 'encode a MultiModalKwargsItem to a base64 string for JSON/HTTP transmission', 'decode_mm_kwargs_item': 'decode a base64 string back to a MultiModalKwargsItem from JSON/HTTP data', 'create_encoder': 'create a MsgpackEncoder instance with a large size threshold to force all tensors inline', 'create_decoder': 'create a MsgpackDecoder instance parameterized with MultiModalKwargsItem type', 'test_mm_serde': 'test encoding and decoding roundtrip of a MultiModalKwargsItem through base64 serialization'}
```

## File: vllm-project_vllm/vllm/entrypoints/serve/disagg/protocol.py

Prompts

```
['build a fastapi API router that provides a POST /inference/v1/generate endpoint for disaggregated vLLM inference', 'create a POST endpoint that accepts GenerateRequest and returns streaming or JSON GenerateResponse', 'test the abort_requests endpoint that cancels one or more inference requests by request_ids', 'refactor the attach_router function to conditionally register abort_requests when tokens_only is enabled', 'summarize the engine_client dependency that retrieves EngineClient from FastAPI app state', 'encode a MultiModalKwargsItem to a base64 string for JSON/HTTP transmission', 'decode a base64 string back to a MultiModalKwargsItem from JSON/HTTP data', 'create a MsgpackEncoder instance with a large size threshold to force all tensors inline', 'create a MsgpackDecoder instance parameterized with MultiModalKwargsItem type', 'test encoding and decoding roundtrip of a MultiModalKwargsItem through base64 serialization', 'create a PlaceholderRangeInfo model with offset and length for multi-modal placeholder token locations', 'create a MultiModalFeatures model with per-modality hashes, placeholder ranges, and serialized tensor data', 'create a GenerateRequest model with token ids, sampling params, and optional multimodal features for disaggregated serving', 'build TokenizeParams from a GenerateRequest using its build_tok_params method with a ModelConfig', 'create a GenerateResponse model with request id, choices, prompt logprobs, and kv transfer params for disaggregated serving']
```

Usage

```
{'create_PlaceholderRangeInfo': 'create a PlaceholderRangeInfo model with offset and length for multi-modal placeholder token locations', 'create_MultiModalFeatures': 'create a MultiModalFeatures model with per-modality hashes, placeholder ranges, and serialized tensor data', 'create_GenerateRequest': 'create a GenerateRequest model with token ids, sampling params, and optional multimodal features for disaggregated serving', 'build_GenerateRequest_tok_params': 'build TokenizeParams from a GenerateRequest using its build_tok_params method with a ModelConfig', 'create_GenerateResponse': 'create a GenerateResponse model with request id, choices, prompt logprobs, and kv transfer params for disaggregated serving'}
```

