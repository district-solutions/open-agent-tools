# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/integrations/datadog/datadog.py

Prompts

```
['create a DataDogLogger instance configured with DD_API_KEY and DD_SITE environment variables', 'async_log_success_event sends LLM completion logs to DataDog in a batched non-blocking manner', 'async_post_call_failure_hook logs proxy-level failures like auth errors and DB connection errors to DataDog', 'async_service_failure_hook logs adjacent system failures from Redis or Postgres as WARNING level events', 'async_health_check sends a test log to DataDog and returns healthy or unhealthy status', 'build a list of Datadog tags from a standard logging payload with env, service, and team metadata', 'get the Datadog source name from the DD_SOURCE environment variable or default to litellm', 'get the Datadog service name from the DD_SERVICE environment variable or default to litellm-server', 'get the Datadog base URL override from the DD_BASE_URL environment variable for custom endpoints', 'get Datadog tags including request tags and team alias from a standard logging payload object', "create a DataDogLLMObsLogger instance to log LLM traces to Datadog's LLM Observability Service", 'create an LLMObsPayload from a standard logging payload with model, tokens, and timing metrics for Datadog ingestion', 'send a batch of queued LLM observation payloads to the Datadog LLM Observability intake API', 'get the appropriate Datadog span kind (llm, tool, task, embedding, retrieval) from a liteLLM call type', 'extract tool call information from input messages and response into key-value pairs for Datadog metadata']
```

Usage

```
{'create_datadog_logger': 'create a DataDogLogger instance configured with DD_API_KEY and DD_SITE environment variables', 'log_success_event_async': 'async_log_success_event sends LLM completion logs to DataDog in a batched non-blocking manner', 'log_failure_hook': 'async_post_call_failure_hook logs proxy-level failures like auth errors and DB connection errors to DataDog', 'log_service_failure': 'async_service_failure_hook logs adjacent system failures from Redis or Postgres as WARNING level events', 'test_health_check': 'async_health_check sends a test log to DataDog and returns healthy or unhealthy status'}
```

## File: berriai_litellm/litellm/integrations/datadog/datadog_handler.py

Prompts

```
['create a DataDogLogger instance configured with DD_API_KEY and DD_SITE environment variables', 'async_log_success_event sends LLM completion logs to DataDog in a batched non-blocking manner', 'async_post_call_failure_hook logs proxy-level failures like auth errors and DB connection errors to DataDog', 'async_service_failure_hook logs adjacent system failures from Redis or Postgres as WARNING level events', 'async_health_check sends a test log to DataDog and returns healthy or unhealthy status', 'build a list of Datadog tags from a standard logging payload with env, service, and team metadata', 'get the Datadog source name from the DD_SOURCE environment variable or default to litellm', 'get the Datadog service name from the DD_SERVICE environment variable or default to litellm-server', 'get the Datadog base URL override from the DD_BASE_URL environment variable for custom endpoints', 'get Datadog tags including request tags and team alias from a standard logging payload object', "create a DataDogLLMObsLogger instance to log LLM traces to Datadog's LLM Observability Service", 'create an LLMObsPayload from a standard logging payload with model, tokens, and timing metrics for Datadog ingestion', 'send a batch of queued LLM observation payloads to the Datadog LLM Observability intake API', 'get the appropriate Datadog span kind (llm, tool, task, embedding, retrieval) from a liteLLM call type', 'extract tool call information from input messages and response into key-value pairs for Datadog metadata']
```

Usage

```
{'build_datadog_tags': 'build a list of Datadog tags from a standard logging payload with env, service, and team metadata', 'get_datadog_source': 'get the Datadog source name from the DD_SOURCE environment variable or default to litellm', 'get_datadog_service': 'get the Datadog service name from the DD_SERVICE environment variable or default to litellm-server', 'get_datadog_base_url_from_env': 'get the Datadog base URL override from the DD_BASE_URL environment variable for custom endpoints', 'get_datadog_tags_with_metadata': 'get Datadog tags including request tags and team alias from a standard logging payload object'}
```

## File: berriai_litellm/litellm/integrations/datadog/datadog_llm_obs.py

Prompts

```
['create a DataDogLogger instance configured with DD_API_KEY and DD_SITE environment variables', 'async_log_success_event sends LLM completion logs to DataDog in a batched non-blocking manner', 'async_post_call_failure_hook logs proxy-level failures like auth errors and DB connection errors to DataDog', 'async_service_failure_hook logs adjacent system failures from Redis or Postgres as WARNING level events', 'async_health_check sends a test log to DataDog and returns healthy or unhealthy status', 'build a list of Datadog tags from a standard logging payload with env, service, and team metadata', 'get the Datadog source name from the DD_SOURCE environment variable or default to litellm', 'get the Datadog service name from the DD_SERVICE environment variable or default to litellm-server', 'get the Datadog base URL override from the DD_BASE_URL environment variable for custom endpoints', 'get Datadog tags including request tags and team alias from a standard logging payload object', "create a DataDogLLMObsLogger instance to log LLM traces to Datadog's LLM Observability Service", 'create an LLMObsPayload from a standard logging payload with model, tokens, and timing metrics for Datadog ingestion', 'send a batch of queued LLM observation payloads to the Datadog LLM Observability intake API', 'get the appropriate Datadog span kind (llm, tool, task, embedding, retrieval) from a liteLLM call type', 'extract tool call information from input messages and response into key-value pairs for Datadog metadata']
```

Usage

```
{'create_datadog_llm_obs_logger': "create a DataDogLLMObsLogger instance to log LLM traces to Datadog's LLM Observability Service", 'create_llm_obs_payload': 'create an LLMObsPayload from a standard logging payload with model, tokens, and timing metrics for Datadog ingestion', 'async_send_batch': 'send a batch of queued LLM observation payloads to the Datadog LLM Observability intake API', 'get_datadog_span_kind': 'get the appropriate Datadog span kind (llm, tool, task, embedding, retrieval) from a liteLLM call type', 'extract_tool_call_metadata': 'extract tool call information from input messages and response into key-value pairs for Datadog metadata'}
```

