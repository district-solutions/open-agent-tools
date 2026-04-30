# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/serve/render/api_router.py

Prompts

```
['build a FastAPI router with endpoints for chat completions and completions render APIs', 'attach the render API router to a FastAPI application instance', 'render chat completions via POST /v1/chat/completions/render endpoint', 'render text completions via POST /v1/completions/render endpoint', 'retrieve the OpenAIServingRender handler from a FastAPI request state', 'build an OpenAIServingRender instance with model config, renderer, and model registry for GPU-less render server', 'render a chat completion request into a GenerateRequest with token IDs, sampling params, and multimodal features', 'render a completion request into a list of GenerateRequests with token IDs and sampling parameters', 'extract multimodal features including hashes, placeholders, and kwargs from a rendered engine input', 'build Harmony (GPT-OSS) messages and engine prompt from a chat completion request']
```

Usage

```
{'build_fastapi_router': 'build a FastAPI router with endpoints for chat completions and completions render APIs', 'attach_router_to_app': 'attach the render API router to a FastAPI application instance', 'render_chat_completion': 'render chat completions via POST /v1/chat/completions/render endpoint', 'render_completion': 'render text completions via POST /v1/completions/render endpoint', 'retrieve_render_handler': 'retrieve the OpenAIServingRender handler from a FastAPI request state'}
```

## File: vllm-project_vllm/vllm/entrypoints/serve/render/serving.py

Prompts

```
['build a FastAPI router with endpoints for chat completions and completions render APIs', 'attach the render API router to a FastAPI application instance', 'render chat completions via POST /v1/chat/completions/render endpoint', 'render text completions via POST /v1/completions/render endpoint', 'retrieve the OpenAIServingRender handler from a FastAPI request state', 'build an OpenAIServingRender instance with model config, renderer, and model registry for GPU-less render server', 'render a chat completion request into a GenerateRequest with token IDs, sampling params, and multimodal features', 'render a completion request into a list of GenerateRequests with token IDs and sampling parameters', 'extract multimodal features including hashes, placeholders, and kwargs from a rendered engine input', 'build Harmony (GPT-OSS) messages and engine prompt from a chat completion request']
```

Usage

```
{'build_OpenAIServingRender': 'build an OpenAIServingRender instance with model config, renderer, and model registry for GPU-less render server', 'render_chat_request': 'render a chat completion request into a GenerateRequest with token IDs, sampling params, and multimodal features', 'render_completion_request': 'render a completion request into a list of GenerateRequests with token IDs and sampling parameters', 'extract_mm_features': 'extract multimodal features including hashes, placeholders, and kwargs from a rendered engine input', 'make_request_with_harmony': 'build Harmony (GPT-OSS) messages and engine prompt from a chat completion request'}
```

