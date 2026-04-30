# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/integrations/gcs_bucket/gcs_bucket_base.py

Prompts

```
['download an object from a GCS bucket using async HTTP requests and Vertex AI authentication', 'delete an object from a GCS bucket using async HTTP requests and Vertex AI authentication', 'construct request headers with Bearer token authentication for GCS API calls', 'log JSON data to a GCS bucket by posting payloads via async HTTP upload', 'retrieve GCS logging configuration with bucket name, credentials, and vertex instance', 'test the GCS bucket mock client by enabling mock mode via GCS_MOCK env var for integration testing', 'test the GCS bucket mock client with custom latency via GCS_MOCK_LATENCY_MS environment variable', 'test the GCS mock HTTP handler that intercepts GET and DELETE calls to storage.googleapis.com', 'test the Vertex AI auth mock that patches ensure_access_token to return fake tokens', 'test the create_mock_gcs_client function that monkey-patches AsyncHTTPHandler for GCS mock mode']
```

Usage

```
{'download_gcs_object': 'download an object from a GCS bucket using async HTTP requests and Vertex AI authentication', 'delete_gcs_object': 'delete an object from a GCS bucket using async HTTP requests and Vertex AI authentication', 'construct_request_headers': 'construct request headers with Bearer token authentication for GCS API calls', 'log_json_data_on_gcs': 'log JSON data to a GCS bucket by posting payloads via async HTTP upload', 'get_gcs_logging_config': 'retrieve GCS logging configuration with bucket name, credentials, and vertex instance'}
```

## File: berriai_litellm/litellm/integrations/gcs_bucket/gcs_bucket_mock_client.py

Prompts

```
['download an object from a GCS bucket using async HTTP requests and Vertex AI authentication', 'delete an object from a GCS bucket using async HTTP requests and Vertex AI authentication', 'construct request headers with Bearer token authentication for GCS API calls', 'log JSON data to a GCS bucket by posting payloads via async HTTP upload', 'retrieve GCS logging configuration with bucket name, credentials, and vertex instance', 'test the GCS bucket mock client by enabling mock mode via GCS_MOCK env var for integration testing', 'test the GCS bucket mock client with custom latency via GCS_MOCK_LATENCY_MS environment variable', 'test the GCS mock HTTP handler that intercepts GET and DELETE calls to storage.googleapis.com', 'test the Vertex AI auth mock that patches ensure_access_token to return fake tokens', 'test the create_mock_gcs_client function that monkey-patches AsyncHTTPHandler for GCS mock mode']
```

Usage

```
{'test_gcs_bucket_mock': 'test the GCS bucket mock client by enabling mock mode via GCS_MOCK env var for integration testing', 'test_gcs_bucket_mock_latency': 'test the GCS bucket mock client with custom latency via GCS_MOCK_LATENCY_MS environment variable', 'test_gcs_http_intercept': 'test the GCS mock HTTP handler that intercepts GET and DELETE calls to storage.googleapis.com', 'test_vertex_auth_mock': 'test the Vertex AI auth mock that patches ensure_access_token to return fake tokens', 'test_gcs_client_init': 'test the create_mock_gcs_client function that monkey-patches AsyncHTTPHandler for GCS mock mode'}
```

