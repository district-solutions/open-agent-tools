# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/api/tests/conftest.py

Prompts

```
['create pytest fixtures to configure test environment variables and MongoDB resources for API tests', 'create a session-scoped fixture that loads AppConfig from environment variables for testing', 'create a fixture that defines processing step names by input type and endpoint for tests', 'create an autouse fixture that manages CacheMongoResource lifecycle and cleans the cache database after each test', 'create an autouse fixture that manages QueueMongoResource lifecycle and cleans the queue database after each test', 'test the CORS preflight request handling for the dataset viewer API endpoints', 'test the healthcheck endpoint returns a 200 status code and ok response', 'test the dataset endpoint returns 422 when the dataset parameter is missing or empty', 'test the dataset endpoint returns 422 when the dataset parameter is None or empty string', 'test the split endpoint returns 422 when dataset, config, or split parameters are missing']
```

Usage

```
{'setup_pytest_fixtures_for_api_tests': 'create pytest fixtures to configure test environment variables and MongoDB resources for API tests', 'configure_app_config_fixture': 'create a session-scoped fixture that loads AppConfig from environment variables for testing', 'configure_endpoint_config_fixture': 'create a fixture that defines processing step names by input type and endpoint for tests', 'setup_mongo_cache_resource_fixture': 'create an autouse fixture that manages CacheMongoResource lifecycle and cleans the cache database after each test', 'setup_mongo_queue_resource_fixture': 'create an autouse fixture that manages QueueMongoResource lifecycle and cleans the queue database after each test'}
```

## File: huggingface_dataset-viewer/services/api/tests/test_app.py

Prompts

```
['create pytest fixtures to configure test environment variables and MongoDB resources for API tests', 'create a session-scoped fixture that loads AppConfig from environment variables for testing', 'create a fixture that defines processing step names by input type and endpoint for tests', 'create an autouse fixture that manages CacheMongoResource lifecycle and cleans the cache database after each test', 'create an autouse fixture that manages QueueMongoResource lifecycle and cleans the queue database after each test', 'test the CORS preflight request handling for the dataset viewer API endpoints', 'test the healthcheck endpoint returns a 200 status code and ok response', 'test the dataset endpoint returns 422 when the dataset parameter is missing or empty', 'test the dataset endpoint returns 422 when the dataset parameter is None or empty string', 'test the split endpoint returns 422 when dataset, config, or split parameters are missing']
```

Usage

```
{'test_cors': 'test the CORS preflight request handling for the dataset viewer API endpoints', 'test_get_healthcheck': 'test the healthcheck endpoint returns a 200 status code and ok response', 'test_get_endpoint': 'test the dataset endpoint returns 422 when the dataset parameter is missing or empty', 'test_get_dataset_missing_parameter': 'test the dataset endpoint returns 422 when the dataset parameter is None or empty string', 'test_get_split_missing_parameter': 'test the split endpoint returns 422 when dataset, config, or split parameters are missing'}
```

