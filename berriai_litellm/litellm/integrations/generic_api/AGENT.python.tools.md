# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/integrations/generic_api/generic_api_callback.py

Prompts

```
['create a GenericAPILogger instance to log LLM API events to a custom endpoint with configurable headers and batch flushing', 'run async_log_success_event to queue and send a successful LLM API call log to the generic endpoint', 'run async_log_failure_event to queue and send a failed LLM API call log to the generic endpoint', 'run async_send_batch to flush the log queue to the endpoint in json_array, ndjson, or single format', 'build a string with substituted environment variables by replacing {{environment_variables.VAR_NAME}} patterns']
```

Usage

```
{'create_GenericAPILogger': 'create a GenericAPILogger instance to log LLM API events to a custom endpoint with configurable headers and batch flushing', 'run_async_log_success_event': 'run async_log_success_event to queue and send a successful LLM API call log to the generic endpoint', 'run_async_log_failure_event': 'run async_log_failure_event to queue and send a failed LLM API call log to the generic endpoint', 'run_async_send_batch': 'run async_send_batch to flush the log queue to the endpoint in json_array, ndjson, or single format', 'build_substitute_env_variables': 'build a string with substituted environment variables by replacing {{environment_variables.VAR_NAME}} patterns'}
```

