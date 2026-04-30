# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/search/tests/conftest.py

Prompts

```
['review the pytest conftest fixtures for the dataset viewer search service test suite', 'summarize the test configuration fixtures including mongo resources and environment patching', 'test the cache mongo resource fixture that provides and cleans the cache database', 'test the queue mongo resource fixture that provides and cleans the queue database', 'review the app_config fixture that loads AppConfig from environment variables', 'test the search service CORS preflight response headers for origin, method, and credentials', 'test the search service healthcheck endpoint returns 200 status and ok response text', 'test the search endpoint returns 422 status when required parameters are missing', 'test the search endpoint returns 422 for various combinations of missing dataset, config, split, or query parameters', 'test the metrics endpoint returns prometheus metrics including starlette requests and processing time']
```

Usage

```
{'review_pytest_fixtures': 'review the pytest conftest fixtures for the dataset viewer search service test suite', 'summarize_test_config': 'summarize the test configuration fixtures including mongo resources and environment patching', 'test_cache_mongo_resource': 'test the cache mongo resource fixture that provides and cleans the cache database', 'test_queue_mongo_resource': 'test the queue mongo resource fixture that provides and cleans the queue database', 'review_app_config_fixture': 'review the app_config fixture that loads AppConfig from environment variables'}
```

## File: huggingface_dataset-viewer/services/search/tests/test_app.py

Prompts

```
['review the pytest conftest fixtures for the dataset viewer search service test suite', 'summarize the test configuration fixtures including mongo resources and environment patching', 'test the cache mongo resource fixture that provides and cleans the cache database', 'test the queue mongo resource fixture that provides and cleans the queue database', 'review the app_config fixture that loads AppConfig from environment variables', 'test the search service CORS preflight response headers for origin, method, and credentials', 'test the search service healthcheck endpoint returns 200 status and ok response text', 'test the search endpoint returns 422 status when required parameters are missing', 'test the search endpoint returns 422 for various combinations of missing dataset, config, split, or query parameters', 'test the metrics endpoint returns prometheus metrics including starlette requests and processing time']
```

Usage

```
{'test_cors': 'test the search service CORS preflight response headers for origin, method, and credentials', 'test_healthcheck': 'test the search service healthcheck endpoint returns 200 status and ok response text', 'test_search_validation': 'test the search endpoint returns 422 status when required parameters are missing', 'test_parametrized_search': 'test the search endpoint returns 422 for various combinations of missing dataset, config, split, or query parameters', 'test_metrics': 'test the metrics endpoint returns prometheus metrics including starlette requests and processing time'}
```

