# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/webhook/src/webhook/app.py

Prompts

```
['create a Starlette app with CORS, gzip, and Prometheus middleware for the webhook service', 'create a Starlette app from an AppConfig with MongoDB resources and webhook routes', 'run the webhook service as a uvicorn server on a configured host and port', 'review the create_app_with_config function to understand how storage clients and MongoDB resources are initialized', 'refactor the webhook route configuration to add new endpoints or modify existing ones', 'build an AppConfig instance by loading all sub-configs from environment variables', 'create an AppConfig with all sub-configs using their default factory values', 'review the AppConfig dataclass fields and their default factory initializers', 'summarize how AppConfig.from_env aggregates CommonConfig, ApiConfig, and other sub-configs', 'test that AppConfig.from_env correctly loads all sub-configs from environment variables']
```

Usage

```
{'create_starlette_app': 'create a Starlette app with CORS, gzip, and Prometheus middleware for the webhook service', 'create_app_with_config': 'create a Starlette app from an AppConfig with MongoDB resources and webhook routes', 'run_webhook_server': 'run the webhook service as a uvicorn server on a configured host and port', 'review_create_app_with_config': 'review the create_app_with_config function to understand how storage clients and MongoDB resources are initialized', 'refactor_webhook_routes': 'refactor the webhook route configuration to add new endpoints or modify existing ones'}
```

## File: huggingface_dataset-viewer/services/webhook/src/webhook/config.py

Prompts

```
['create a Starlette app with CORS, gzip, and Prometheus middleware for the webhook service', 'create a Starlette app from an AppConfig with MongoDB resources and webhook routes', 'run the webhook service as a uvicorn server on a configured host and port', 'review the create_app_with_config function to understand how storage clients and MongoDB resources are initialized', 'refactor the webhook route configuration to add new endpoints or modify existing ones', 'build an AppConfig instance by loading all sub-configs from environment variables', 'create an AppConfig with all sub-configs using their default factory values', 'review the AppConfig dataclass fields and their default factory initializers', 'summarize how AppConfig.from_env aggregates CommonConfig, ApiConfig, and other sub-configs', 'test that AppConfig.from_env correctly loads all sub-configs from environment variables']
```

Usage

```
{'build_appconfig_from_env': 'build an AppConfig instance by loading all sub-configs from environment variables', 'create_appconfig_with_defaults': 'create an AppConfig with all sub-configs using their default factory values', 'review_appconfig_structure': 'review the AppConfig dataclass fields and their default factory initializers', 'summarize_appconfig_from_env': 'summarize how AppConfig.from_env aggregates CommonConfig, ApiConfig, and other sub-configs', 'test_appconfig_from_env': 'test that AppConfig.from_env correctly loads all sub-configs from environment variables'}
```

