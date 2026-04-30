# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/examples/runtime/engine/custom_server.py

Prompts

```
['run the Sanic server with SGLang engine initialized on 0.0.0.0:8000', 'generate text completion from a prompt using the /generate POST endpoint', 'generate streaming text completion from a prompt using the /generate_stream POST endpoint', 'create an SGLang engine instance with a specified model path for text generation', 'async generate text from a prompt with optional streaming mode enabled', 'run a FastAPI server with SGLang engine for text generation using model path and tensor parallelism size', 'run the /generate POST endpoint to generate text from a prompt with configurable max tokens and temperature', 'run the uvicorn server as a subprocess with automatic health check polling on the /docs endpoint', 'run batch text generation by sending multiple prompts to the server with a list of prompts and sampling parameters', 'run the SGLang engine with FastAPI lifespan manager for automatic initialization and shutdown', 'create an SGLang engine with Qwen2.5-7B-Instruct-1M model and 1M context length', 'run batch text generation from prompts using the SGLang engine with sampling parameters', 'test loading a prompt text from a remote URL into the SGLang offline inference pipeline', 'summarize the SGLang engine initialization configuration including attention backend and memory settings', 'refactor the main entry point to support multiple prompts and configurable model parameters']
```

Usage

```
{'run_server_custom_server': 'run the Sanic server with SGLang engine initialized on 0.0.0.0:8000', 'generate_text_completion': 'generate text completion from a prompt using the /generate POST endpoint', 'generate_streaming_completion': 'generate streaming text completion from a prompt using the /generate_stream POST endpoint', 'create_sgl_engine': 'create an SGLang engine instance with a specified model path for text generation', 'async_generate_prompt': 'async generate text from a prompt with optional streaming mode enabled'}
```

## File: sgl-project_sglang/examples/runtime/engine/fastapi_engine_inference.py

Prompts

```
['run the Sanic server with SGLang engine initialized on 0.0.0.0:8000', 'generate text completion from a prompt using the /generate POST endpoint', 'generate streaming text completion from a prompt using the /generate_stream POST endpoint', 'create an SGLang engine instance with a specified model path for text generation', 'async generate text from a prompt with optional streaming mode enabled', 'run a FastAPI server with SGLang engine for text generation using model path and tensor parallelism size', 'run the /generate POST endpoint to generate text from a prompt with configurable max tokens and temperature', 'run the uvicorn server as a subprocess with automatic health check polling on the /docs endpoint', 'run batch text generation by sending multiple prompts to the server with a list of prompts and sampling parameters', 'run the SGLang engine with FastAPI lifespan manager for automatic initialization and shutdown', 'create an SGLang engine with Qwen2.5-7B-Instruct-1M model and 1M context length', 'run batch text generation from prompts using the SGLang engine with sampling parameters', 'test loading a prompt text from a remote URL into the SGLang offline inference pipeline', 'summarize the SGLang engine initialization configuration including attention backend and memory settings', 'refactor the main entry point to support multiple prompts and configurable model parameters']
```

Usage

```
{'run_fastapi_engine_server': 'run a FastAPI server with SGLang engine for text generation using model path and tensor parallelism size', 'run_text_generation_endpoint': 'run the /generate POST endpoint to generate text from a prompt with configurable max tokens and temperature', 'run_server_with_health_check': 'run the uvicorn server as a subprocess with automatic health check polling on the /docs endpoint', 'run_batch_text_generation': 'run batch text generation by sending multiple prompts to the server with a list of prompts and sampling parameters', 'run_engine_with_lifespan_cleanup': 'run the SGLang engine with FastAPI lifespan manager for automatic initialization and shutdown'}
```

## File: sgl-project_sglang/examples/runtime/engine/offline_batch_inference_qwen_1m.py

Prompts

```
['run the Sanic server with SGLang engine initialized on 0.0.0.0:8000', 'generate text completion from a prompt using the /generate POST endpoint', 'generate streaming text completion from a prompt using the /generate_stream POST endpoint', 'create an SGLang engine instance with a specified model path for text generation', 'async generate text from a prompt with optional streaming mode enabled', 'run a FastAPI server with SGLang engine for text generation using model path and tensor parallelism size', 'run the /generate POST endpoint to generate text from a prompt with configurable max tokens and temperature', 'run the uvicorn server as a subprocess with automatic health check polling on the /docs endpoint', 'run batch text generation by sending multiple prompts to the server with a list of prompts and sampling parameters', 'run the SGLang engine with FastAPI lifespan manager for automatic initialization and shutdown', 'create an SGLang engine with Qwen2.5-7B-Instruct-1M model and 1M context length', 'run batch text generation from prompts using the SGLang engine with sampling parameters', 'test loading a prompt text from a remote URL into the SGLang offline inference pipeline', 'summarize the SGLang engine initialization configuration including attention backend and memory settings', 'refactor the main entry point to support multiple prompts and configurable model parameters']
```

Usage

```
{'create_ENGINE': 'create an SGLang engine with Qwen2.5-7B-Instruct-1M model and 1M context length', 'run_process_requests': 'run batch text generation from prompts using the SGLang engine with sampling parameters', 'test_load_prompt': 'test loading a prompt text from a remote URL into the SGLang offline inference pipeline', 'summarize_initialize_engine': 'summarize the SGLang engine initialization configuration including attention backend and memory settings', 'refactor_main': 'refactor the main entry point to support multiple prompts and configurable model parameters'}
```

