# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/search/src/search/app.py

Prompts

```
['create a Starlette app for the dataset search service reading config from environment variables', 'create a Starlette app with a given AppConfig setting up middleware resources and routes', 'start the uvicorn ASGI server running the search service on the configured host and port', 'review the create_app_with_config function and its middleware resource and route setup', 'refactor the search and filter route creation to reduce duplicated endpoint parameters', 'create a DuckDbIndexConfig instance from environment variables using the from_env class method', 'create an AppConfig instance from environment variables using the from_env class method', 'review the DuckDbIndexConfig default values for cache directory, clean cache probability, and expiration interval', 'review the AppConfig dataclass and its eleven sub-config fields including api, cache, queue, and s3', 'refactor the DuckDbIndexConfig from_env method to use a different environment variable prefix']
```

Usage

```
{'create_starlette_app': 'create a Starlette app for the dataset search service reading config from environment variables', 'create_app_with_config': 'create a Starlette app with a given AppConfig setting up middleware resources and routes', 'start_uvicorn_server': 'start the uvicorn ASGI server running the search service on the configured host and port', 'review_create_app_with_config': 'review the create_app_with_config function and its middleware resource and route setup', 'refactor_search_routes': 'refactor the search and filter route creation to reduce duplicated endpoint parameters'}
```

## File: huggingface_dataset-viewer/services/search/src/search/config.py

Prompts

```
['create a Starlette app for the dataset search service reading config from environment variables', 'create a Starlette app with a given AppConfig setting up middleware resources and routes', 'start the uvicorn ASGI server running the search service on the configured host and port', 'review the create_app_with_config function and its middleware resource and route setup', 'refactor the search and filter route creation to reduce duplicated endpoint parameters', 'create a DuckDbIndexConfig instance from environment variables using the from_env class method', 'create an AppConfig instance from environment variables using the from_env class method', 'review the DuckDbIndexConfig default values for cache directory, clean cache probability, and expiration interval', 'review the AppConfig dataclass and its eleven sub-config fields including api, cache, queue, and s3', 'refactor the DuckDbIndexConfig from_env method to use a different environment variable prefix']
```

Usage

```
{'create_DuckDbIndexConfig_from_env': 'create a DuckDbIndexConfig instance from environment variables using the from_env class method', 'create_AppConfig_from_env': 'create an AppConfig instance from environment variables using the from_env class method', 'review_DuckDbIndexConfig_defaults': 'review the DuckDbIndexConfig default values for cache directory, clean cache probability, and expiration interval', 'review_AppConfig_subconfigs': 'review the AppConfig dataclass and its eleven sub-config fields including api, cache, queue, and s3', 'refactor_DuckDbIndexConfig_env_prefix': 'refactor the DuckDbIndexConfig from_env method to use a different environment variable prefix'}
```

