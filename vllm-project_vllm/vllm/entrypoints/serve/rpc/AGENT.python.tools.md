# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/serve/rpc/api_router.py

Prompts

```
['build a FastAPI endpoint that dispatches RPC calls to vLLM engine workers via /collective_rpc POST route', 'create a router attachment function that conditionally registers the RPC router on a FastAPI app in dev mode', 'test the collective_rpc endpoint with JSON body containing method, args, kwargs, and optional timeout fields', 'refactor the engine_client helper to extract EngineClient from FastAPI request app state', 'review the attach_router function for conditional router inclusion based on VLLM_SERVER_DEV_MODE environment variable']
```

Usage

```
{'build_collective_rpc_endpoint': 'build a FastAPI endpoint that dispatches RPC calls to vLLM engine workers via /collective_rpc POST route', 'create_attach_router': 'create a router attachment function that conditionally registers the RPC router on a FastAPI app in dev mode', 'test_collective_rpc': 'test the collective_rpc endpoint with JSON body containing method, args, kwargs, and optional timeout fields', 'refactor_engine_client': 'refactor the engine_client helper to extract EngineClient from FastAPI request app state', 'review_attach_router': 'review the attach_router function for conditional router inclusion based on VLLM_SERVER_DEV_MODE environment variable'}
```

