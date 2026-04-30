# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/integrations/opik/opik.py

Prompts

```
['create an OpikLogger instance to log LLM events to an Opik server with project name, API key, and workspace', 'build trace and span payloads from LLM kwargs and response objects for Opik logging', 'test the async_log_success_event method that queues LLM success events for asynchronous flushing to Opik', 'review the log_success_event method that logs LLM success events synchronously to Opik via native client or HTTP', 'summarize the async_send_batch method that splits queued events into traces and spans and submits them to Opik', 'create a UUID v7 string from the current timestamp and random bytes', 'create a usage dictionary from a token usage object with completion, prompt, and total tokens', 'get an opik configuration variable with priority over user value, env var, config file, and default', 'separate traces and spans from a payload list by checking for the type field', 'build a config reader that loads opik settings from ~/.opik.config, environment variables, and defaults']
```

Usage

```
{'create_OpikLogger': 'create an OpikLogger instance to log LLM events to an Opik server with project name, API key, and workspace', 'build_opik_payload': 'build trace and span payloads from LLM kwargs and response objects for Opik logging', 'test_async_log_success_event': 'test the async_log_success_event method that queues LLM success events for asynchronous flushing to Opik', 'review_log_success_event': 'review the log_success_event method that logs LLM success events synchronously to Opik via native client or HTTP', 'summarize_async_send_batch': 'summarize the async_send_batch method that splits queued events into traces and spans and submits them to Opik'}
```

## File: berriai_litellm/litellm/integrations/opik/utils.py

Prompts

```
['create an OpikLogger instance to log LLM events to an Opik server with project name, API key, and workspace', 'build trace and span payloads from LLM kwargs and response objects for Opik logging', 'test the async_log_success_event method that queues LLM success events for asynchronous flushing to Opik', 'review the log_success_event method that logs LLM success events synchronously to Opik via native client or HTTP', 'summarize the async_send_batch method that splits queued events into traces and spans and submits them to Opik', 'create a UUID v7 string from the current timestamp and random bytes', 'create a usage dictionary from a token usage object with completion, prompt, and total tokens', 'get an opik configuration variable with priority over user value, env var, config file, and default', 'separate traces and spans from a payload list by checking for the type field', 'build a config reader that loads opik settings from ~/.opik.config, environment variables, and defaults']
```

Usage

```
{'create_uuid7': 'create a UUID v7 string from the current timestamp and random bytes', 'create_usage_object': 'create a usage dictionary from a token usage object with completion, prompt, and total tokens', 'get_opik_config_variable': 'get an opik configuration variable with priority over user value, env var, config file, and default', 'get_traces_and_spans_from_payload': 'separate traces and spans from a payload list by checking for the type field', 'build_opik_config_reader': 'build a config reader that loads opik settings from ~/.opik.config, environment variables, and defaults'}
```

