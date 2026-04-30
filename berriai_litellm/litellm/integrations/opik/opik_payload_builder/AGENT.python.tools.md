# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/integrations/opik/opik_payload_builder/api.py

Prompts

```
['build Opik trace and span payloads from LiteLLM completion data with trace and span identifiers', 'extract and merge Opik metadata from litellm and standard logging metadata dictionaries', 'extract trace_id and parent_span_id from current span data for trace attachment or creation', 'apply proxy server header overrides for project name, tags, and thread_id configuration', 'build an Opik trace payload with project name, input/output data, metadata, tags, and thread_id', 'build a function that normalizes LiteLLM provider names to standardized Opik provider names', 'create a function that extracts and merges Opik metadata from litellm and standard logging metadata', 'build a function that extracts trace_id and parent_span_id from current span data dict or object', 'create a function that builds a list of tags from Opik metadata and custom LLM provider name', 'build a function that applies project name, thread id, and tags overrides from proxy request headers', 'build a complete span payload with trace id, parent span id, model info, usage, provider, and cost', 'create a uuid7 span id for opik span identification within a trace', 'test the build_trace_payload function with mock response object and datetime arguments', 'review the build_span_payload function to verify model, object, and created fields are extracted correctly']
```

Usage

```
{'build_opik_payload': 'build Opik trace and span payloads from LiteLLM completion data with trace and span identifiers', 'extract_opik_metadata': 'extract and merge Opik metadata from litellm and standard logging metadata dictionaries', 'extract_span_identifiers': 'extract trace_id and parent_span_id from current span data for trace attachment or creation', 'apply_proxy_header_overrides': 'apply proxy server header overrides for project name, tags, and thread_id configuration', 'build_trace_payload': 'build an Opik trace payload with project name, input/output data, metadata, tags, and thread_id'}
```

## File: berriai_litellm/litellm/integrations/opik/opik_payload_builder/extractors.py

Prompts

```
['build Opik trace and span payloads from LiteLLM completion data with trace and span identifiers', 'extract and merge Opik metadata from litellm and standard logging metadata dictionaries', 'extract trace_id and parent_span_id from current span data for trace attachment or creation', 'apply proxy server header overrides for project name, tags, and thread_id configuration', 'build an Opik trace payload with project name, input/output data, metadata, tags, and thread_id', 'build a function that normalizes LiteLLM provider names to standardized Opik provider names', 'create a function that extracts and merges Opik metadata from litellm and standard logging metadata', 'build a function that extracts trace_id and parent_span_id from current span data dict or object', 'create a function that builds a list of tags from Opik metadata and custom LLM provider name', 'build a function that applies project name, thread id, and tags overrides from proxy request headers', 'build a complete span payload with trace id, parent span id, model info, usage, provider, and cost', 'create a uuid7 span id for opik span identification within a trace', 'test the build_trace_payload function with mock response object and datetime arguments', 'review the build_span_payload function to verify model, object, and created fields are extracted correctly']
```

Usage

```
{'build_normalize_provider_name': 'build a function that normalizes LiteLLM provider names to standardized Opik provider names', 'create_extract_opik_metadata': 'create a function that extracts and merges Opik metadata from litellm and standard logging metadata', 'build_extract_span_identifiers': 'build a function that extracts trace_id and parent_span_id from current span data dict or object', 'create_extract_tags': 'create a function that builds a list of tags from Opik metadata and custom LLM provider name', 'build_apply_proxy_header_overrides': 'build a function that applies project name, thread id, and tags overrides from proxy request headers'}
```

## File: berriai_litellm/litellm/integrations/opik/opik_payload_builder/payload_builders.py

Prompts

```
['build Opik trace and span payloads from LiteLLM completion data with trace and span identifiers', 'extract and merge Opik metadata from litellm and standard logging metadata dictionaries', 'extract trace_id and parent_span_id from current span data for trace attachment or creation', 'apply proxy server header overrides for project name, tags, and thread_id configuration', 'build an Opik trace payload with project name, input/output data, metadata, tags, and thread_id', 'build a function that normalizes LiteLLM provider names to standardized Opik provider names', 'create a function that extracts and merges Opik metadata from litellm and standard logging metadata', 'build a function that extracts trace_id and parent_span_id from current span data dict or object', 'create a function that builds a list of tags from Opik metadata and custom LLM provider name', 'build a function that applies project name, thread id, and tags overrides from proxy request headers', 'build a complete span payload with trace id, parent span id, model info, usage, provider, and cost', 'create a uuid7 span id for opik span identification within a trace', 'test the build_trace_payload function with mock response object and datetime arguments', 'review the build_span_payload function to verify model, object, and created fields are extracted correctly']
```

Usage

```
{'build_trace_payload': 'build a complete trace payload with project name, trace id, input output data, metadata, and tags', 'build_span_payload': 'build a complete span payload with trace id, parent span id, model info, usage, provider, and cost', 'create_uuid7_span_id': 'create a uuid7 span id for opik span identification within a trace', 'test_build_trace_payload': 'test the build_trace_payload function with mock response object and datetime arguments', 'review_build_span_payload': 'review the build_span_payload function to verify model, object, and created fields are extracted correctly'}
```

