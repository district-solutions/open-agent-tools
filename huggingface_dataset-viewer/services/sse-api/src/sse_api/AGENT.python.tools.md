# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/sse-api/src/sse_api/app.py

Prompts

```
['create a Starlette app with SSE hub-cache, healthcheck, and metrics routes using create_app', 'create a Starlette app from an AppConfig instance with MongoDB cache watching and CORS middleware', 'run the SSE API server with uvicorn using environment-based UvicornConfig via the start function', 'configure a HubCacheWatcher to monitor MongoDB cache changes for the SSE hub-cache endpoint', 'setup CORS and Prometheus middleware on the Starlette app for SSE streaming support', 'create an AppConfig instance by loading all sub-configs from environment variables', 'create an AppConfig instance using default values for all sub-configs', 'access the ApiConfig sub-config from an AppConfig instance to get API settings', 'access the CacheConfig sub-config from an AppConfig instance to get cache settings', 'access the QueueConfig sub-config from an AppConfig instance to get queue settings', 'create a HubCacheWatcher instance with a MongoDB client to watch dataset-hub-cache entries', 'start watching for dataset-hub-cache changes by calling start_watching on the HubCacheWatcher', 'subscribe to hub cache change notifications and receive a UUID and event object', 'unsubscribe from hub cache change notifications using the UUID returned by subscribe', 'await a HubCacheChangedEvent to receive the latest dataset hub cache change value']
```

Usage

```
{'create_starlette_app': 'create a Starlette app with SSE hub-cache, healthcheck, and metrics routes using create_app', 'create_app_with_config': 'create a Starlette app from an AppConfig instance with MongoDB cache watching and CORS middleware', 'run_sse_server': 'run the SSE API server with uvicorn using environment-based UvicornConfig via the start function', 'configure_hub_cache_watcher': 'configure a HubCacheWatcher to monitor MongoDB cache changes for the SSE hub-cache endpoint', 'setup_sse_middleware': 'setup CORS and Prometheus middleware on the Starlette app for SSE streaming support'}
```

## File: huggingface_dataset-viewer/services/sse-api/src/sse_api/config.py

Prompts

```
['create a Starlette app with SSE hub-cache, healthcheck, and metrics routes using create_app', 'create a Starlette app from an AppConfig instance with MongoDB cache watching and CORS middleware', 'run the SSE API server with uvicorn using environment-based UvicornConfig via the start function', 'configure a HubCacheWatcher to monitor MongoDB cache changes for the SSE hub-cache endpoint', 'setup CORS and Prometheus middleware on the Starlette app for SSE streaming support', 'create an AppConfig instance by loading all sub-configs from environment variables', 'create an AppConfig instance using default values for all sub-configs', 'access the ApiConfig sub-config from an AppConfig instance to get API settings', 'access the CacheConfig sub-config from an AppConfig instance to get cache settings', 'access the QueueConfig sub-config from an AppConfig instance to get queue settings', 'create a HubCacheWatcher instance with a MongoDB client to watch dataset-hub-cache entries', 'start watching for dataset-hub-cache changes by calling start_watching on the HubCacheWatcher', 'subscribe to hub cache change notifications and receive a UUID and event object', 'unsubscribe from hub cache change notifications using the UUID returned by subscribe', 'await a HubCacheChangedEvent to receive the latest dataset hub cache change value']
```

Usage

```
{'create_appconfig_from_env': 'create an AppConfig instance by loading all sub-configs from environment variables', 'create_appconfig_with_defaults': 'create an AppConfig instance using default values for all sub-configs', 'access_api_config': 'access the ApiConfig sub-config from an AppConfig instance to get API settings', 'access_cache_config': 'access the CacheConfig sub-config from an AppConfig instance to get cache settings', 'access_queue_config': 'access the QueueConfig sub-config from an AppConfig instance to get queue settings'}
```

## File: huggingface_dataset-viewer/services/sse-api/src/sse_api/watcher.py

Prompts

```
['create a Starlette app with SSE hub-cache, healthcheck, and metrics routes using create_app', 'create a Starlette app from an AppConfig instance with MongoDB cache watching and CORS middleware', 'run the SSE API server with uvicorn using environment-based UvicornConfig via the start function', 'configure a HubCacheWatcher to monitor MongoDB cache changes for the SSE hub-cache endpoint', 'setup CORS and Prometheus middleware on the Starlette app for SSE streaming support', 'create an AppConfig instance by loading all sub-configs from environment variables', 'create an AppConfig instance using default values for all sub-configs', 'access the ApiConfig sub-config from an AppConfig instance to get API settings', 'access the CacheConfig sub-config from an AppConfig instance to get cache settings', 'access the QueueConfig sub-config from an AppConfig instance to get queue settings', 'create a HubCacheWatcher instance with a MongoDB client to watch dataset-hub-cache entries', 'start watching for dataset-hub-cache changes by calling start_watching on the HubCacheWatcher', 'subscribe to hub cache change notifications and receive a UUID and event object', 'unsubscribe from hub cache change notifications using the UUID returned by subscribe', 'await a HubCacheChangedEvent to receive the latest dataset hub cache change value']
```

Usage

```
{'create_HubCacheWatcher': 'create a HubCacheWatcher instance with a MongoDB client to watch dataset-hub-cache entries', 'start_watching_HubCacheWatcher': 'start watching for dataset-hub-cache changes by calling start_watching on the HubCacheWatcher', 'subscribe_HubCacheWatcher': 'subscribe to hub cache change notifications and receive a UUID and event object', 'unsubscribe_HubCacheWatcher': 'unsubscribe from hub cache change notifications using the UUID returned by subscribe', 'wait_value_HubCacheChangedEvent': 'await a HubCacheChangedEvent to receive the latest dataset hub cache change value'}
```

