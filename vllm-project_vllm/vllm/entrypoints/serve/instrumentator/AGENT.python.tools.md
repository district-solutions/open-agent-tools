# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/serve/instrumentator/basic.py

Prompts

```
['get server load metrics from the vLLM instrumentation router at /load endpoint', 'show the vLLM version string from the instrumentation router at /version endpoint', 'create a function that returns an OpenAIServing instance from the request state', 'create a function that returns an OpenAIServingTokenization instance from the request state', 'create a function that returns an EngineClient instance from the request state', 'test the health check endpoint that returns 200 on success and 503 on EngineDeadError', 'review the health endpoint function that checks engine client health status', 'review the engine_client helper that extracts EngineClient from request app state', 'review the FastAPI router with /health GET endpoint for vLLM engine health checks', 'summarize the health check module that provides a /health endpoint for vLLM engine status', 'attach prometheus metrics router to a FastAPI app with excluded handlers and correct content-type response', 'create a custom FastAPI Response class with Prometheus content-type header for metrics endpoints', 'instrument a FastAPI app with prometheus-fastapi-instrumentator excluding health and ping handlers', 'mount a Prometheus ASGI metrics route on a FastAPI app with path regex workaround for redirects', 'get the global prometheus registry from vllm metrics module for use with instrumentation', 'attach offline swagger UI documentation to a FastAPI app for air-gapped environments', 'mount static swagger UI assets (JS and CSS) from a vendored directory onto a FastAPI app', 'enable offline documentation by setting enable_offline_docs to True on app state args', 'configure OAuth2 redirect endpoint for swagger UI authentication flows', 'serve a custom Swagger UI HTML page with offline-bundled JavaScript and CSS']
```

Usage

```
{'get_server_load_metrics': 'get server load metrics from the vLLM instrumentation router at /load endpoint', 'show_version': 'show the vLLM version string from the instrumentation router at /version endpoint', 'create_function_base': 'create a function that returns an OpenAIServing instance from the request state', 'create_function_tokenization': 'create a function that returns an OpenAIServingTokenization instance from the request state', 'create_function_engine_client': 'create a function that returns an EngineClient instance from the request state'}
```

## File: vllm-project_vllm/vllm/entrypoints/serve/instrumentator/health.py

Prompts

```
['get server load metrics from the vLLM instrumentation router at /load endpoint', 'show the vLLM version string from the instrumentation router at /version endpoint', 'create a function that returns an OpenAIServing instance from the request state', 'create a function that returns an OpenAIServingTokenization instance from the request state', 'create a function that returns an EngineClient instance from the request state', 'test the health check endpoint that returns 200 on success and 503 on EngineDeadError', 'review the health endpoint function that checks engine client health status', 'review the engine_client helper that extracts EngineClient from request app state', 'review the FastAPI router with /health GET endpoint for vLLM engine health checks', 'summarize the health check module that provides a /health endpoint for vLLM engine status', 'attach prometheus metrics router to a FastAPI app with excluded handlers and correct content-type response', 'create a custom FastAPI Response class with Prometheus content-type header for metrics endpoints', 'instrument a FastAPI app with prometheus-fastapi-instrumentator excluding health and ping handlers', 'mount a Prometheus ASGI metrics route on a FastAPI app with path regex workaround for redirects', 'get the global prometheus registry from vllm metrics module for use with instrumentation', 'attach offline swagger UI documentation to a FastAPI app for air-gapped environments', 'mount static swagger UI assets (JS and CSS) from a vendored directory onto a FastAPI app', 'enable offline documentation by setting enable_offline_docs to True on app state args', 'configure OAuth2 redirect endpoint for swagger UI authentication flows', 'serve a custom Swagger UI HTML page with offline-bundled JavaScript and CSS']
```

Usage

```
{'test_health_endpoint': 'test the health check endpoint that returns 200 on success and 503 on EngineDeadError', 'review_health_function': 'review the health endpoint function that checks engine client health status', 'review_engine_client_function': 'review the engine_client helper that extracts EngineClient from request app state', 'review_health_router': 'review the FastAPI router with /health GET endpoint for vLLM engine health checks', 'summarize_health_module': 'summarize the health check module that provides a /health endpoint for vLLM engine status'}
```

## File: vllm-project_vllm/vllm/entrypoints/serve/instrumentator/metrics.py

Prompts

```
['get server load metrics from the vLLM instrumentation router at /load endpoint', 'show the vLLM version string from the instrumentation router at /version endpoint', 'create a function that returns an OpenAIServing instance from the request state', 'create a function that returns an OpenAIServingTokenization instance from the request state', 'create a function that returns an EngineClient instance from the request state', 'test the health check endpoint that returns 200 on success and 503 on EngineDeadError', 'review the health endpoint function that checks engine client health status', 'review the engine_client helper that extracts EngineClient from request app state', 'review the FastAPI router with /health GET endpoint for vLLM engine health checks', 'summarize the health check module that provides a /health endpoint for vLLM engine status', 'attach prometheus metrics router to a FastAPI app with excluded handlers and correct content-type response', 'create a custom FastAPI Response class with Prometheus content-type header for metrics endpoints', 'instrument a FastAPI app with prometheus-fastapi-instrumentator excluding health and ping handlers', 'mount a Prometheus ASGI metrics route on a FastAPI app with path regex workaround for redirects', 'get the global prometheus registry from vllm metrics module for use with instrumentation', 'attach offline swagger UI documentation to a FastAPI app for air-gapped environments', 'mount static swagger UI assets (JS and CSS) from a vendored directory onto a FastAPI app', 'enable offline documentation by setting enable_offline_docs to True on app state args', 'configure OAuth2 redirect endpoint for swagger UI authentication flows', 'serve a custom Swagger UI HTML page with offline-bundled JavaScript and CSS']
```

Usage

```
{'attach_router_fastapi': 'attach prometheus metrics router to a FastAPI app with excluded handlers and correct content-type response', 'create_PrometheusResponse': 'create a custom FastAPI Response class with Prometheus content-type header for metrics endpoints', 'instrument_FastAPI_app': 'instrument a FastAPI app with prometheus-fastapi-instrumentator excluding health and ping handlers', 'mount_metrics_route': 'mount a Prometheus ASGI metrics route on a FastAPI app with path regex workaround for redirects', 'get_prometheus_registry': 'get the global prometheus registry from vllm metrics module for use with instrumentation'}
```

## File: vllm-project_vllm/vllm/entrypoints/serve/instrumentator/offline_docs.py

Prompts

```
['get server load metrics from the vLLM instrumentation router at /load endpoint', 'show the vLLM version string from the instrumentation router at /version endpoint', 'create a function that returns an OpenAIServing instance from the request state', 'create a function that returns an OpenAIServingTokenization instance from the request state', 'create a function that returns an EngineClient instance from the request state', 'test the health check endpoint that returns 200 on success and 503 on EngineDeadError', 'review the health endpoint function that checks engine client health status', 'review the engine_client helper that extracts EngineClient from request app state', 'review the FastAPI router with /health GET endpoint for vLLM engine health checks', 'summarize the health check module that provides a /health endpoint for vLLM engine status', 'attach prometheus metrics router to a FastAPI app with excluded handlers and correct content-type response', 'create a custom FastAPI Response class with Prometheus content-type header for metrics endpoints', 'instrument a FastAPI app with prometheus-fastapi-instrumentator excluding health and ping handlers', 'mount a Prometheus ASGI metrics route on a FastAPI app with path regex workaround for redirects', 'get the global prometheus registry from vllm metrics module for use with instrumentation', 'attach offline swagger UI documentation to a FastAPI app for air-gapped environments', 'mount static swagger UI assets (JS and CSS) from a vendored directory onto a FastAPI app', 'enable offline documentation by setting enable_offline_docs to True on app state args', 'configure OAuth2 redirect endpoint for swagger UI authentication flows', 'serve a custom Swagger UI HTML page with offline-bundled JavaScript and CSS']
```

Usage

```
{'attach_router_offline_docs': 'attach offline swagger UI documentation to a FastAPI app for air-gapped environments', 'mount_static_assets_docs': 'mount static swagger UI assets (JS and CSS) from a vendored directory onto a FastAPI app', 'enable_offline_docs_flag': 'enable offline documentation by setting enable_offline_docs to True on app state args', 'configure_swagger_redirect': 'configure OAuth2 redirect endpoint for swagger UI authentication flows', 'serve_custom_swagger_html': 'serve a custom Swagger UI HTML page with offline-bundled JavaScript and CSS'}
```

