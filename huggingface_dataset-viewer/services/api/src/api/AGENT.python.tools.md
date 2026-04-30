# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/api/src/api/app.py

Prompts

```
['run the starlette app by calling start to launch uvicorn on the configured host and port', 'create a starlette app by calling create_app to load config from environment variables', 'create a starlette app with explicit app and endpoint config objects including middleware and routes', 'review the create_app_with_config function to understand how middleware storage clients and routes are wired together', 'refactor the create_app function to accept custom config classes instead of reading from environment variables', 'create an AppConfig instance from environment variables using AppConfig.from_env()', 'create an EndpointConfig instance from environment variables using EndpointConfig.from_env()', 'review the AppConfig dataclass and its frozen fields for configuration management', 'review the EndpointConfig default mapping of endpoints to processing step names', 'summarize the ProcessingStepNameByInputType and ProcessingStepNameByInputTypeAndEndpoint type aliases']
```

Usage

```
{'run_starlette_app': 'run the starlette app by calling start to launch uvicorn on the configured host and port', 'create_app_from_env': 'create a starlette app by calling create_app to load config from environment variables', 'create_app_with_config': 'create a starlette app with explicit app and endpoint config objects including middleware and routes', 'review_create_app_with_config': 'review the create_app_with_config function to understand how middleware storage clients and routes are wired together', 'refactor_create_app': 'refactor the create_app function to accept custom config classes instead of reading from environment variables'}
```

## File: huggingface_dataset-viewer/services/api/src/api/config.py

Prompts

```
['run the starlette app by calling start to launch uvicorn on the configured host and port', 'create a starlette app by calling create_app to load config from environment variables', 'create a starlette app with explicit app and endpoint config objects including middleware and routes', 'review the create_app_with_config function to understand how middleware storage clients and routes are wired together', 'refactor the create_app function to accept custom config classes instead of reading from environment variables', 'create an AppConfig instance from environment variables using AppConfig.from_env()', 'create an EndpointConfig instance from environment variables using EndpointConfig.from_env()', 'review the AppConfig dataclass and its frozen fields for configuration management', 'review the EndpointConfig default mapping of endpoints to processing step names', 'summarize the ProcessingStepNameByInputType and ProcessingStepNameByInputTypeAndEndpoint type aliases']
```

Usage

```
{'create_appconfig_from_env': 'create an AppConfig instance from environment variables using AppConfig.from_env()', 'create_endpointconfig_from_env': 'create an EndpointConfig instance from environment variables using EndpointConfig.from_env()', 'review_appconfig_dataclass': 'review the AppConfig dataclass and its frozen fields for configuration management', 'review_endpointconfig_mapping': 'review the EndpointConfig default mapping of endpoints to processing step names', 'summarize_processing_step_types': 'summarize the ProcessingStepNameByInputType and ProcessingStepNameByInputTypeAndEndpoint type aliases'}
```

