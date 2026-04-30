# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/setfit/app/main.py

Prompts

```
['run the Starlette app with gzip middleware and optional CORS for inference pipeline routing', 'get the cached inference pipeline instance for the TASK environment variable and model ID', 'get the model ID from the MODEL_ID env var or resolve the cached revision path offline', 'configure the ALLOWED_TASKS dictionary to map task names to Pipeline class types', 'setup the async startup event to configure logging and eagerly initialize the pipeline']
```

Usage

```
{'run_starlette_app': 'run the Starlette app with gzip middleware and optional CORS for inference pipeline routing', 'get_pipeline': 'get the cached inference pipeline instance for the TASK environment variable and model ID', 'get_model_id': 'get the model ID from the MODEL_ID env var or resolve the cached revision path offline', 'configure_allowed_tasks': 'configure the ALLOWED_TASKS dictionary to map task names to Pipeline class types', 'setup_startup_event': 'setup the async startup event to configure logging and eagerly initialize the pipeline'}
```

