# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/rows/src/rows/app.py

Prompts

```
['run the rows service by calling start which launches uvicorn with the create_app factory', 'create a Starlette app with CORS, GZip, and Prometheus middleware using create_app', 'create a Starlette app from an AppConfig instance using create_app_with_config', 'setup the /rows endpoint with storage clients, JWT auth, and parquet metadata support', 'configure cached and raw asset StorageClient instances with S3 config and URL preparation', 'create an AppConfig instance with all default sub-config values using the dataclass constructor', 'create an AppConfig instance by loading all sub-configs from environment variables using from_env', 'access individual sub-configs like api, cache, queue, s3, and rows_index on an AppConfig instance', 'review the AppConfig frozen dataclass and its eleven sub-config fields and their default factories', 'refactor AppConfig to add or remove sub-config fields or change how from_env initializes them']
```

Usage

```
{'run_rows_service': 'run the rows service by calling start which launches uvicorn with the create_app factory', 'create_starlette_app': 'create a Starlette app with CORS, GZip, and Prometheus middleware using create_app', 'create_app_with_config': 'create a Starlette app from an AppConfig instance using create_app_with_config', 'setup_rows_endpoint': 'setup the /rows endpoint with storage clients, JWT auth, and parquet metadata support', 'configure_storage_clients': 'configure cached and raw asset StorageClient instances with S3 config and URL preparation'}
```

## File: huggingface_dataset-viewer/services/rows/src/rows/config.py

Prompts

```
['run the rows service by calling start which launches uvicorn with the create_app factory', 'create a Starlette app with CORS, GZip, and Prometheus middleware using create_app', 'create a Starlette app from an AppConfig instance using create_app_with_config', 'setup the /rows endpoint with storage clients, JWT auth, and parquet metadata support', 'configure cached and raw asset StorageClient instances with S3 config and URL preparation', 'create an AppConfig instance with all default sub-config values using the dataclass constructor', 'create an AppConfig instance by loading all sub-configs from environment variables using from_env', 'access individual sub-configs like api, cache, queue, s3, and rows_index on an AppConfig instance', 'review the AppConfig frozen dataclass and its eleven sub-config fields and their default factories', 'refactor AppConfig to add or remove sub-config fields or change how from_env initializes them']
```

Usage

```
{'create_appconfig_with_defaults': 'create an AppConfig instance with all default sub-config values using the dataclass constructor', 'create_appconfig_from_env': 'create an AppConfig instance by loading all sub-configs from environment variables using from_env', 'access_appconfig_subconfigs': 'access individual sub-configs like api, cache, queue, s3, and rows_index on an AppConfig instance', 'review_appconfig_structure': 'review the AppConfig frozen dataclass and its eleven sub-config fields and their default factories', 'refactor_appconfig_composition': 'refactor AppConfig to add or remove sub-config fields or change how from_env initializes them'}
```

