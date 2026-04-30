# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/admin/tests/test_app.py

Prompts

```
['test the admin service CORS preflight request handling for origin, method, and header validation', 'test the admin service healthcheck endpoint returns 200 with ok response text', 'test the admin service metrics endpoint records and returns starlette request total metrics', 'test the admin service pending jobs endpoint returns waiting and started jobs for each processing step', 'test the admin service blocked datasets endpoint returns an empty list of blocked datasets', 'test the force-refresh admin endpoint for a dataset using the processing graph', 'create a pytest fixture that sets environment variables for cache and queue mongo databases', 'create a pytest fixture that returns a TestClient for the admin app', 'create a pytest fixture that loads and validates the AppConfig from environment variables', 'run the real dataset integration tests marked with the real_dataset marker', 'test that auth_check returns True when called with no arguments', 'test that auth_check raises RuntimeError when the external auth service is unreachable', 'test auth_check behavior for HTTP status codes 200, 401, 403, 404, and 429', 'test auth_check with different organization names and expected error responses', 'create a Starlette Request object from a mapping of header key-value pairs', 'test the request_callback function to verify it returns 404 when an authorization header is present', 'test the request_callback function to verify it returns 200 when no authorization header is present', 'review the request_callback mock function used for testing auth_check service token passing behavior', 'refactor the request_callback function to support additional HTTP status codes for different auth scenarios', 'summarize the request_callback function that returns mock httpx responses based on the presence of an authorization header']
```

Usage

```
{'test_cors': 'test the admin service CORS preflight request handling for origin, method, and header validation', 'test_get_healthcheck': 'test the admin service healthcheck endpoint returns 200 with ok response text', 'test_metrics': 'test the admin service metrics endpoint records and returns starlette request total metrics', 'test_pending_jobs': 'test the admin service pending jobs endpoint returns waiting and started jobs for each processing step', 'test_blocked_datasets': 'test the admin service blocked datasets endpoint returns an empty list of blocked datasets'}
```

## File: huggingface_dataset-viewer/services/admin/tests/test_app_real.py

Prompts

```
['test the admin service CORS preflight request handling for origin, method, and header validation', 'test the admin service healthcheck endpoint returns 200 with ok response text', 'test the admin service metrics endpoint records and returns starlette request total metrics', 'test the admin service pending jobs endpoint returns waiting and started jobs for each processing step', 'test the admin service blocked datasets endpoint returns an empty list of blocked datasets', 'test the force-refresh admin endpoint for a dataset using the processing graph', 'create a pytest fixture that sets environment variables for cache and queue mongo databases', 'create a pytest fixture that returns a TestClient for the admin app', 'create a pytest fixture that loads and validates the AppConfig from environment variables', 'run the real dataset integration tests marked with the real_dataset marker', 'test that auth_check returns True when called with no arguments', 'test that auth_check raises RuntimeError when the external auth service is unreachable', 'test auth_check behavior for HTTP status codes 200, 401, 403, 404, and 429', 'test auth_check with different organization names and expected error responses', 'create a Starlette Request object from a mapping of header key-value pairs', 'test the request_callback function to verify it returns 404 when an authorization header is present', 'test the request_callback function to verify it returns 200 when no authorization header is present', 'review the request_callback mock function used for testing auth_check service token passing behavior', 'refactor the request_callback function to support additional HTTP status codes for different auth scenarios', 'summarize the request_callback function that returns mock httpx responses based on the presence of an authorization header']
```

Usage

```
{'test_force_refresh': 'test the force-refresh admin endpoint for a dataset using the processing graph', 'create_real_monkeypatch_fixture': 'create a pytest fixture that sets environment variables for cache and queue mongo databases', 'create_real_client_fixture': 'create a pytest fixture that returns a TestClient for the admin app', 'create_real_app_config_fixture': 'create a pytest fixture that loads and validates the AppConfig from environment variables', 'run_real_dataset_tests': 'run the real dataset integration tests marked with the real_dataset marker'}
```

## File: huggingface_dataset-viewer/services/admin/tests/test_authentication.py

Prompts

```
['test the admin service CORS preflight request handling for origin, method, and header validation', 'test the admin service healthcheck endpoint returns 200 with ok response text', 'test the admin service metrics endpoint records and returns starlette request total metrics', 'test the admin service pending jobs endpoint returns waiting and started jobs for each processing step', 'test the admin service blocked datasets endpoint returns an empty list of blocked datasets', 'test the force-refresh admin endpoint for a dataset using the processing graph', 'create a pytest fixture that sets environment variables for cache and queue mongo databases', 'create a pytest fixture that returns a TestClient for the admin app', 'create a pytest fixture that loads and validates the AppConfig from environment variables', 'run the real dataset integration tests marked with the real_dataset marker', 'test that auth_check returns True when called with no arguments', 'test that auth_check raises RuntimeError when the external auth service is unreachable', 'test auth_check behavior for HTTP status codes 200, 401, 403, 404, and 429', 'test auth_check with different organization names and expected error responses', 'create a Starlette Request object from a mapping of header key-value pairs', 'test the request_callback function to verify it returns 404 when an authorization header is present', 'test the request_callback function to verify it returns 200 when no authorization header is present', 'review the request_callback mock function used for testing auth_check service token passing behavior', 'refactor the request_callback function to support additional HTTP status codes for different auth scenarios', 'summarize the request_callback function that returns mock httpx responses based on the presence of an authorization header']
```

Usage

```
{'test_auth_check_no_args': 'test that auth_check returns True when called with no arguments', 'test_auth_check_unreachable_service': 'test that auth_check raises RuntimeError when the external auth service is unreachable', 'test_auth_check_http_status_codes': 'test auth_check behavior for HTTP status codes 200, 401, 403, 404, and 429', 'test_auth_check_organization': 'test auth_check with different organization names and expected error responses', 'create_request_helper': 'create a Starlette Request object from a mapping of header key-value pairs'}
```

## File: huggingface_dataset-viewer/services/admin/tests/utils.py

Prompts

```
['test the admin service CORS preflight request handling for origin, method, and header validation', 'test the admin service healthcheck endpoint returns 200 with ok response text', 'test the admin service metrics endpoint records and returns starlette request total metrics', 'test the admin service pending jobs endpoint returns waiting and started jobs for each processing step', 'test the admin service blocked datasets endpoint returns an empty list of blocked datasets', 'test the force-refresh admin endpoint for a dataset using the processing graph', 'create a pytest fixture that sets environment variables for cache and queue mongo databases', 'create a pytest fixture that returns a TestClient for the admin app', 'create a pytest fixture that loads and validates the AppConfig from environment variables', 'run the real dataset integration tests marked with the real_dataset marker', 'test that auth_check returns True when called with no arguments', 'test that auth_check raises RuntimeError when the external auth service is unreachable', 'test auth_check behavior for HTTP status codes 200, 401, 403, 404, and 429', 'test auth_check with different organization names and expected error responses', 'create a Starlette Request object from a mapping of header key-value pairs', 'test the request_callback function to verify it returns 404 when an authorization header is present', 'test the request_callback function to verify it returns 200 when no authorization header is present', 'review the request_callback mock function used for testing auth_check service token passing behavior', 'refactor the request_callback function to support additional HTTP status codes for different auth scenarios', 'summarize the request_callback function that returns mock httpx responses based on the presence of an authorization header']
```

Usage

```
{'test_request_callback_auth': 'test the request_callback function to verify it returns 404 when an authorization header is present', 'test_request_callback_no_auth': 'test the request_callback function to verify it returns 200 when no authorization header is present', 'review_request_callback': 'review the request_callback mock function used for testing auth_check service token passing behavior', 'refactor_request_callback': 'refactor the request_callback function to support additional HTTP status codes for different auth scenarios', 'summarize_request_callback': 'summarize the request_callback function that returns mock httpx responses based on the presence of an authorization header'}
```

