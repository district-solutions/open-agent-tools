# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/serve/elastic_ep/api_router.py

Prompts

```
['build a fastapi endpoint that scales elastic vLLM engines to a specified data parallel size with a drain timeout', 'test the scale_elastic_ep endpoint with valid new_data_parallel_size and drain_timeout parameters', 'refactor the scale_elastic_ep function to support custom validation for new_data_parallel_size and drain_timeout', 'review the attach_router function that mounts the elastic_ep APIRouter onto a FastAPI application', 'summarize the is_scaling_elastic_ep endpoint that returns the current scaling status of elastic vLLM engines', 'create a function to retrieve the current global scaling state of the elastic endpoint', 'create a function to set the global scaling state of the elastic endpoint to a boolean value', 'build a starlette ASGI middleware class that returns 503 responses when the model is scaling', 'test the ScalingMiddleware class returns 503 when scaling is active and passes requests when inactive', 'review the ScalingMiddleware.__call__ method that intercepts HTTP requests based on global scaling state']
```

Usage

```
{'build_scale_elastic_ep': 'build a fastapi endpoint that scales elastic vLLM engines to a specified data parallel size with a drain timeout', 'test_scale_elastic_ep': 'test the scale_elastic_ep endpoint with valid new_data_parallel_size and drain_timeout parameters', 'refactor_scale_elastic_ep': 'refactor the scale_elastic_ep function to support custom validation for new_data_parallel_size and drain_timeout', 'review_attach_router': 'review the attach_router function that mounts the elastic_ep APIRouter onto a FastAPI application', 'summarize_is_scaling_elastic_ep': 'summarize the is_scaling_elastic_ep endpoint that returns the current scaling status of elastic vLLM engines'}
```

## File: vllm-project_vllm/vllm/entrypoints/serve/elastic_ep/middleware.py

Prompts

```
['build a fastapi endpoint that scales elastic vLLM engines to a specified data parallel size with a drain timeout', 'test the scale_elastic_ep endpoint with valid new_data_parallel_size and drain_timeout parameters', 'refactor the scale_elastic_ep function to support custom validation for new_data_parallel_size and drain_timeout', 'review the attach_router function that mounts the elastic_ep APIRouter onto a FastAPI application', 'summarize the is_scaling_elastic_ep endpoint that returns the current scaling status of elastic vLLM engines', 'create a function to retrieve the current global scaling state of the elastic endpoint', 'create a function to set the global scaling state of the elastic endpoint to a boolean value', 'build a starlette ASGI middleware class that returns 503 responses when the model is scaling', 'test the ScalingMiddleware class returns 503 when scaling is active and passes requests when inactive', 'review the ScalingMiddleware.__call__ method that intercepts HTTP requests based on global scaling state']
```

Usage

```
{'create_function_get_scaling_elastic_ep': 'create a function to retrieve the current global scaling state of the elastic endpoint', 'create_function_set_scaling_elastic_ep': 'create a function to set the global scaling state of the elastic endpoint to a boolean value', 'build_class_scaling_middleware': 'build a starlette ASGI middleware class that returns 503 responses when the model is scaling', 'test_scaling_middleware': 'test the ScalingMiddleware class returns 503 when scaling is active and passes requests when inactive', 'review_scaling_middleware_call': 'review the ScalingMiddleware.__call__ method that intercepts HTTP requests based on global scaling state'}
```

