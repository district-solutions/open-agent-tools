# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/common/app/main.py

Prompts

```
['add a new pipeline class to the ALLOWED_TASKS dictionary for a supported task', 'call get_pipeline to instantiate and cache the pipeline for the current TASK and MODEL_ID environment variables', 'modify the routes list to add custom endpoints alongside the existing status_ok and pipeline_route handlers', 'set the DEBUG environment variable to 1 to enable CORS middleware on the Starlette app', 'extend the startup_event async function to add custom initialization logic before the pipeline loads']
```

Usage

```
{'register_pipeline_task': 'add a new pipeline class to the ALLOWED_TASKS dictionary for a supported task', 'get_pipeline': 'call get_pipeline to instantiate and cache the pipeline for the current TASK and MODEL_ID environment variables', 'configure_starlette_routes': 'modify the routes list to add custom endpoints alongside the existing status_ok and pipeline_route handlers', 'enable_cors_middleware': 'set the DEBUG environment variable to 1 to enable CORS middleware on the Starlette app', 'customize_startup_event': 'extend the startup_event async function to add custom initialization logic before the pipeline loads'}
```

