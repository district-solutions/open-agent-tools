# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/asteroid/app/main.py

Prompts

```
['run the starlette app that serves audio source separation and audio to audio inference endpoints', 'create a pipeline instance by setting the TASK and MODEL_ID environment variables and calling get_pipeline', 'add a new audio task to the ALLOWED_TASKS dictionary mapping task names to pipeline classes', 'configure the starlette app to enable CORS middleware by setting the DEBUG environment variable to 1', 'review the startup_event function that configures uvicorn logging and initializes the pipeline on app startup']
```

Usage

```
{'run_starlette_audio_inference_app': 'run the starlette app that serves audio source separation and audio to audio inference endpoints', 'create_pipeline_for_task': 'create a pipeline instance by setting the TASK and MODEL_ID environment variables and calling get_pipeline', 'add_allowed_audio_task': 'add a new audio task to the ALLOWED_TASKS dictionary mapping task names to pipeline classes', 'configure_cors_middleware': 'configure the starlette app to enable CORS middleware by setting the DEBUG environment variable to 1', 'review_startup_event': 'review the startup_event function that configures uvicorn logging and initializes the pipeline on app startup'}
```

