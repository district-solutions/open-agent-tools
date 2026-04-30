# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/speechbrain/app/common.py

Prompts

```
['get the SpeechBrain model type for a HuggingFace model by reading its config', 'get the vocoder model ID associated with a SpeechBrain model from its config', 'list all available SpeechBrain model types like ENCODERASR, WHISPERASR, and TACOTRON2', 'review the ModelType enum to understand SpeechBrain model categories like ASR and TTS', 'refactor get_type to cache HfApi model_info calls and reduce redundant API requests', 'run the Starlette app that serves audio and speech inference pipelines via HTTP routes', 'get a cached Pipeline instance by reading TASK and MODEL_ID environment variables', 'configure the ALLOWED_TASKS dict to map task names to SpeechBrain pipeline classes', 'setup CORS middleware on the Starlette app when DEBUG environment variable is set to 1', 'run the async startup event that configures uvicorn logging and initializes the pipeline']
```

Usage

```
{'get_model_type': 'get the SpeechBrain model type for a HuggingFace model by reading its config', 'get_vocoder_model_id': 'get the vocoder model ID associated with a SpeechBrain model from its config', 'list_model_types': 'list all available SpeechBrain model types like ENCODERASR, WHISPERASR, and TACOTRON2', 'review_ModelType': 'review the ModelType enum to understand SpeechBrain model categories like ASR and TTS', 'refactor_get_type': 'refactor get_type to cache HfApi model_info calls and reduce redundant API requests'}
```

## File: huggingface_api-inference-community/docker_images/speechbrain/app/main.py

Prompts

```
['get the SpeechBrain model type for a HuggingFace model by reading its config', 'get the vocoder model ID associated with a SpeechBrain model from its config', 'list all available SpeechBrain model types like ENCODERASR, WHISPERASR, and TACOTRON2', 'review the ModelType enum to understand SpeechBrain model categories like ASR and TTS', 'refactor get_type to cache HfApi model_info calls and reduce redundant API requests', 'run the Starlette app that serves audio and speech inference pipelines via HTTP routes', 'get a cached Pipeline instance by reading TASK and MODEL_ID environment variables', 'configure the ALLOWED_TASKS dict to map task names to SpeechBrain pipeline classes', 'setup CORS middleware on the Starlette app when DEBUG environment variable is set to 1', 'run the async startup event that configures uvicorn logging and initializes the pipeline']
```

Usage

```
{'run_starlette_app': 'run the Starlette app that serves audio and speech inference pipelines via HTTP routes', 'get_pipeline': 'get a cached Pipeline instance by reading TASK and MODEL_ID environment variables', 'configure_allowed_tasks': 'configure the ALLOWED_TASKS dict to map task names to SpeechBrain pipeline classes', 'setup_cors_middleware': 'setup CORS middleware on the Starlette app when DEBUG environment variable is set to 1', 'startup_event': 'run the async startup event that configures uvicorn logging and initializes the pipeline'}
```

