# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/serve/cache/api_router.py

Prompts

```
['reset the local prefix cache optionally including external connector-managed cache via query parameters', 'reset the multi-modal cache used by the vLLM engine for multimodal inputs', 'reset the encoder cache used by the vLLM engine for encoder-based models', 'attach the cache reset API router to a FastAPI app when dev mode is enabled', 'retrieve the EngineClient from the FastAPI request app state for cache operations']
```

Usage

```
{'reset_prefix_cache': 'reset the local prefix cache optionally including external connector-managed cache via query parameters', 'reset_mm_cache': 'reset the multi-modal cache used by the vLLM engine for multimodal inputs', 'reset_encoder_cache': 'reset the encoder cache used by the vLLM engine for encoder-based models', 'attach_router': 'attach the cache reset API router to a FastAPI app when dev mode is enabled', 'engine_client': 'retrieve the EngineClient from the FastAPI request app state for cache operations'}
```

