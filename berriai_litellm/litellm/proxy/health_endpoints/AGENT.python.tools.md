# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/health_endpoints/_health_endpoints.py

Prompts

```
['test the health of a specific integration service like slack, datadog, or langfuse via the /health/services endpoint', 'test a direct connection to a specific LLM model with custom litellm params and mode via /health/test_connection endpoint', 'check if the proxy worker is ready to receive requests by hitting /health/readiness for db, cache, and callback status', 'retrieve historical health check records for models with optional filtering by model name, status, limit, and offset', 'get a list of all active litellm callbacks including success, failure, and input callbacks from /settings endpoint', 'build a FastAPI application that serves LiteLLM health check endpoints for proxy monitoring', 'test the proxy server health by calling the /health endpoint to verify all configured models are reachable', 'check the status of external services like slack, langfuse, openmeter, and webhooks via /health/services', 'get the current count of in-flight requests to monitor proxy load via /health/in_flight_requests']
```

Usage

```
{'test_health_services': 'test the health of a specific integration service like slack, datadog, or langfuse via the /health/services endpoint', 'test_model_connection': 'test a direct connection to a specific LLM model with custom litellm params and mode via /health/test_connection endpoint', 'check_health_readiness': 'check if the proxy worker is ready to receive requests by hitting /health/readiness for db, cache, and callback status', 'get_health_check_history': 'retrieve historical health check records for models with optional filtering by model name, status, limit, and offset', 'get_active_callbacks': 'get a list of all active litellm callbacks including success, failure, and input callbacks from /settings endpoint'}
```

## File: berriai_litellm/litellm/proxy/health_endpoints/health_app_factory.py

Prompts

```
['test the health of a specific integration service like slack, datadog, or langfuse via the /health/services endpoint', 'test a direct connection to a specific LLM model with custom litellm params and mode via /health/test_connection endpoint', 'check if the proxy worker is ready to receive requests by hitting /health/readiness for db, cache, and callback status', 'retrieve historical health check records for models with optional filtering by model name, status, limit, and offset', 'get a list of all active litellm callbacks including success, failure, and input callbacks from /settings endpoint', 'build a FastAPI application that serves LiteLLM health check endpoints for proxy monitoring', 'test the proxy server health by calling the /health endpoint to verify all configured models are reachable', 'check the status of external services like slack, langfuse, openmeter, and webhooks via /health/services', 'get the current count of in-flight requests to monitor proxy load via /health/in_flight_requests']
```

Usage

```
{'build_health_app': 'build a FastAPI application that serves LiteLLM health check endpoints for proxy monitoring', 'test_health_endpoint': 'test the proxy server health by calling the /health endpoint to verify all configured models are reachable', 'test_model_connection': 'test a direct connection to a specific model using the /health/test_connection POST endpoint', 'check_health_services': 'check the status of external services like slack, langfuse, openmeter, and webhooks via /health/services', 'get_in_flight_requests': 'get the current count of in-flight requests to monitor proxy load via /health/in_flight_requests'}
```

