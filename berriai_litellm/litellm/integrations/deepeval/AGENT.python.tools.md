# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/integrations/deepeval/api.py

Prompts

```
['send_request the Api class to send a synchronous POST request to DeepEval API endpoints', 'a_send_request the Api class to send an asynchronous POST request to DeepEval API endpoints', 'build an Api client with a confidential AI API key and optional custom base URL', 'test the Endpoints enum to list all supported DeepEval API endpoint paths', 'review the HttpMethods enum and Api class for supported HTTP methods and request handling', "create a DeepEvalLogger instance to log LiteLLM traces to DeepEval's platform via CONFIDENT_API_KEY", 'log a successful LLM call event to DeepEval with kwargs, response object, and timing information', 'log a failed LLM call event to DeepEval with kwargs, response object, and timing information', 'build a trace API body dict from kwargs, response, and timing using _prepare_trace_api for DeepEval ingestion', 'create a BaseApiSpan object representing an LLM span with input, output, token counts, and status', 'convert a datetime object to a Zod-compatible ISO 8601 string with milliseconds and Z timezone', 'validate an environment string against the allowed Environment enum values: production, development, staging', 'test the to_zod_compatible_iso function with a naive datetime and a timezone-aware datetime', 'test the validate_environment function with valid and invalid environment strings', 'refactor the to_zod_compatible_iso function to handle None inputs gracefully']
```

Usage

```
{'send_request_send_api_call': 'send_request the Api class to send a synchronous POST request to DeepEval API endpoints', 'send_request_async_api_call': 'a_send_request the Api class to send an asynchronous POST request to DeepEval API endpoints', 'build_api_client': 'build an Api client with a confidential AI API key and optional custom base URL', 'test_endpoints_enum': 'test the Endpoints enum to list all supported DeepEval API endpoint paths', 'review_api_http_methods': 'review the HttpMethods enum and Api class for supported HTTP methods and request handling'}
```

## File: berriai_litellm/litellm/integrations/deepeval/deepeval.py

Prompts

```
['send_request the Api class to send a synchronous POST request to DeepEval API endpoints', 'a_send_request the Api class to send an asynchronous POST request to DeepEval API endpoints', 'build an Api client with a confidential AI API key and optional custom base URL', 'test the Endpoints enum to list all supported DeepEval API endpoint paths', 'review the HttpMethods enum and Api class for supported HTTP methods and request handling', "create a DeepEvalLogger instance to log LiteLLM traces to DeepEval's platform via CONFIDENT_API_KEY", 'log a successful LLM call event to DeepEval with kwargs, response object, and timing information', 'log a failed LLM call event to DeepEval with kwargs, response object, and timing information', 'build a trace API body dict from kwargs, response, and timing using _prepare_trace_api for DeepEval ingestion', 'create a BaseApiSpan object representing an LLM span with input, output, token counts, and status', 'convert a datetime object to a Zod-compatible ISO 8601 string with milliseconds and Z timezone', 'validate an environment string against the allowed Environment enum values: production, development, staging', 'test the to_zod_compatible_iso function with a naive datetime and a timezone-aware datetime', 'test the validate_environment function with valid and invalid environment strings', 'refactor the to_zod_compatible_iso function to handle None inputs gracefully']
```

Usage

```
{'create_deepeval_logger': "create a DeepEvalLogger instance to log LiteLLM traces to DeepEval's platform via CONFIDENT_API_KEY", 'log_success_event': 'log a successful LLM call event to DeepEval with kwargs, response object, and timing information', 'log_failure_event': 'log a failed LLM call event to DeepEval with kwargs, response object, and timing information', 'build_trace_api_body': 'build a trace API body dict from kwargs, response, and timing using _prepare_trace_api for DeepEval ingestion', 'create_base_api_span': 'create a BaseApiSpan object representing an LLM span with input, output, token counts, and status'}
```

## File: berriai_litellm/litellm/integrations/deepeval/utils.py

Prompts

```
['send_request the Api class to send a synchronous POST request to DeepEval API endpoints', 'a_send_request the Api class to send an asynchronous POST request to DeepEval API endpoints', 'build an Api client with a confidential AI API key and optional custom base URL', 'test the Endpoints enum to list all supported DeepEval API endpoint paths', 'review the HttpMethods enum and Api class for supported HTTP methods and request handling', "create a DeepEvalLogger instance to log LiteLLM traces to DeepEval's platform via CONFIDENT_API_KEY", 'log a successful LLM call event to DeepEval with kwargs, response object, and timing information', 'log a failed LLM call event to DeepEval with kwargs, response object, and timing information', 'build a trace API body dict from kwargs, response, and timing using _prepare_trace_api for DeepEval ingestion', 'create a BaseApiSpan object representing an LLM span with input, output, token counts, and status', 'convert a datetime object to a Zod-compatible ISO 8601 string with milliseconds and Z timezone', 'validate an environment string against the allowed Environment enum values: production, development, staging', 'test the to_zod_compatible_iso function with a naive datetime and a timezone-aware datetime', 'test the validate_environment function with valid and invalid environment strings', 'refactor the to_zod_compatible_iso function to handle None inputs gracefully']
```

Usage

```
{'convert_datetime_to_zod_iso': 'convert a datetime object to a Zod-compatible ISO 8601 string with milliseconds and Z timezone', 'validate_environment_value': 'validate an environment string against the allowed Environment enum values: production, development, staging', 'test_to_zod_compatible_iso': 'test the to_zod_compatible_iso function with a naive datetime and a timezone-aware datetime', 'test_validate_environment': 'test the validate_environment function with valid and invalid environment strings', 'refactor_to_zod_compatible_iso': 'refactor the to_zod_compatible_iso function to handle None inputs gracefully'}
```

