# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/openai/models/api_router.py

Prompts

```
['build a FastAPI router that exposes an endpoint listing available vLLM models', 'create an async endpoint that returns available vLLM models as JSON', 'test the show_available_models endpoint returns a JSON response with model listings', 'refactor the attach_router function to mount the APIRouter onto a FastAPI app instance', 'review the models helper function that retrieves OpenAIServingModels from request app state', 'build an OpenAIModelRegistry to provide a read-only view of loaded base models without engine dependency', 'check if a model name exists in the OpenAI model registry and return an error response if not found', 'list all available base models with their max model length and root paths', 'load a LoRA adapter into the vLLM engine with a given name, path, and base model', 'resolve and load a LoRA adapter using available resolvers by name without explicit path']
```

Usage

```
{'build_fastapi_router': 'build a FastAPI router that exposes an endpoint listing available vLLM models', 'create_show_available_models': 'create an async endpoint that returns available vLLM models as JSON', 'test_show_available_models': 'test the show_available_models endpoint returns a JSON response with model listings', 'refactor_attach_router': 'refactor the attach_router function to mount the APIRouter onto a FastAPI app instance', 'review_models_helper': 'review the models helper function that retrieves OpenAIServingModels from request app state'}
```

## File: vllm-project_vllm/vllm/entrypoints/openai/models/serving.py

Prompts

```
['build a FastAPI router that exposes an endpoint listing available vLLM models', 'create an async endpoint that returns available vLLM models as JSON', 'test the show_available_models endpoint returns a JSON response with model listings', 'refactor the attach_router function to mount the APIRouter onto a FastAPI app instance', 'review the models helper function that retrieves OpenAIServingModels from request app state', 'build an OpenAIModelRegistry to provide a read-only view of loaded base models without engine dependency', 'check if a model name exists in the OpenAI model registry and return an error response if not found', 'list all available base models with their max model length and root paths', 'load a LoRA adapter into the vLLM engine with a given name, path, and base model', 'resolve and load a LoRA adapter using available resolvers by name without explicit path']
```

Usage

```
{'build_openai_model_registry': 'build an OpenAIModelRegistry to provide a read-only view of loaded base models without engine dependency', 'check_model_exists': 'check if a model name exists in the OpenAI model registry and return an error response if not found', 'list_available_models': 'list all available base models with their max model length and root paths', 'load_lora_adapter': 'load a LoRA adapter into the vLLM engine with a given name, path, and base model', 'resolve_lora_adapter': 'resolve and load a LoRA adapter using available resolvers by name without explicit path'}
```

