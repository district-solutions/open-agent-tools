# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/webhook/tests/conftest.py

Prompts

```
['run pytest tests for the webhook service using the conftest fixtures for mongo resources', 'review the app_config fixture that loads AppConfig from environment variables and validates test databases', 'test the autouse cache_mongo_resource fixture that provides and cleans the cache MongoDB database', 'test the autouse queue_mongo_resource fixture that provides and cleans the queue MongoDB database', 'review the session-scoped monkeypatch fixture that sets environment variables for assets, mongo, and uvicorn config', 'test the webhook CORS preflight OPTIONS response for allowed origin, headers, and methods', 'test the healthcheck endpoint returns a 200 status code and the text ok', 'test the metrics endpoint returns prometheus metrics with positive request and processing time values', 'review the test_cors function to verify CORS headers are validated correctly', 'refactor the test_metrics function to parse and assert additional prometheus metric names', 'test that posting to the webhook endpoint without a secret header returns a 400 status code', 'test that posting to the webhook endpoint with a valid x-webhook-secret header returns a 200 status code', 'run the module-scoped pytest fixture that sets environment variables for cache, queue, and HuggingFace endpoint configuration', 'run the module-scoped pytest fixture that creates a TestClient instance from the webhook app', 'run the module-scoped pytest fixture that loads AppConfig from environment and validates test database and production hub settings']
```

Usage

```
{'run_pytest_webhook_tests': 'run pytest tests for the webhook service using the conftest fixtures for mongo resources', 'review_app_config_fixture': 'review the app_config fixture that loads AppConfig from environment variables and validates test databases', 'test_cache_mongo_resource_fixture': 'test the autouse cache_mongo_resource fixture that provides and cleans the cache MongoDB database', 'test_queue_mongo_resource_fixture': 'test the autouse queue_mongo_resource fixture that provides and cleans the queue MongoDB database', 'review_monkeypatch_session_fixture': 'review the session-scoped monkeypatch fixture that sets environment variables for assets, mongo, and uvicorn config'}
```

## File: huggingface_dataset-viewer/services/webhook/tests/test_app.py

Prompts

```
['run pytest tests for the webhook service using the conftest fixtures for mongo resources', 'review the app_config fixture that loads AppConfig from environment variables and validates test databases', 'test the autouse cache_mongo_resource fixture that provides and cleans the cache MongoDB database', 'test the autouse queue_mongo_resource fixture that provides and cleans the queue MongoDB database', 'review the session-scoped monkeypatch fixture that sets environment variables for assets, mongo, and uvicorn config', 'test the webhook CORS preflight OPTIONS response for allowed origin, headers, and methods', 'test the healthcheck endpoint returns a 200 status code and the text ok', 'test the metrics endpoint returns prometheus metrics with positive request and processing time values', 'review the test_cors function to verify CORS headers are validated correctly', 'refactor the test_metrics function to parse and assert additional prometheus metric names', 'test that posting to the webhook endpoint without a secret header returns a 400 status code', 'test that posting to the webhook endpoint with a valid x-webhook-secret header returns a 200 status code', 'run the module-scoped pytest fixture that sets environment variables for cache, queue, and HuggingFace endpoint configuration', 'run the module-scoped pytest fixture that creates a TestClient instance from the webhook app', 'run the module-scoped pytest fixture that loads AppConfig from environment and validates test database and production hub settings']
```

Usage

```
{'test_cors': 'test the webhook CORS preflight OPTIONS response for allowed origin, headers, and methods', 'test_get_healthcheck': 'test the healthcheck endpoint returns a 200 status code and the text ok', 'test_metrics': 'test the metrics endpoint returns prometheus metrics with positive request and processing time values', 'review_test_cors': 'review the test_cors function to verify CORS headers are validated correctly', 'refactor_test_metrics': 'refactor the test_metrics function to parse and assert additional prometheus metric names'}
```

## File: huggingface_dataset-viewer/services/webhook/tests/test_app_real.py

Prompts

```
['run pytest tests for the webhook service using the conftest fixtures for mongo resources', 'review the app_config fixture that loads AppConfig from environment variables and validates test databases', 'test the autouse cache_mongo_resource fixture that provides and cleans the cache MongoDB database', 'test the autouse queue_mongo_resource fixture that provides and cleans the queue MongoDB database', 'review the session-scoped monkeypatch fixture that sets environment variables for assets, mongo, and uvicorn config', 'test the webhook CORS preflight OPTIONS response for allowed origin, headers, and methods', 'test the healthcheck endpoint returns a 200 status code and the text ok', 'test the metrics endpoint returns prometheus metrics with positive request and processing time values', 'review the test_cors function to verify CORS headers are validated correctly', 'refactor the test_metrics function to parse and assert additional prometheus metric names', 'test that posting to the webhook endpoint without a secret header returns a 400 status code', 'test that posting to the webhook endpoint with a valid x-webhook-secret header returns a 200 status code', 'run the module-scoped pytest fixture that sets environment variables for cache, queue, and HuggingFace endpoint configuration', 'run the module-scoped pytest fixture that creates a TestClient instance from the webhook app', 'run the module-scoped pytest fixture that loads AppConfig from environment and validates test database and production hub settings']
```

Usage

```
{'test_webhook_untrusted': 'test that posting to the webhook endpoint without a secret header returns a 400 status code', 'test_webhook_trusted': 'test that posting to the webhook endpoint with a valid x-webhook-secret header returns a 200 status code', 'run_real_monkeypatch_fixture': 'run the module-scoped pytest fixture that sets environment variables for cache, queue, and HuggingFace endpoint configuration', 'run_real_client_fixture': 'run the module-scoped pytest fixture that creates a TestClient instance from the webhook app', 'run_real_app_config_fixture': 'run the module-scoped pytest fixture that loads AppConfig from environment and validates test database and production hub settings'}
```

