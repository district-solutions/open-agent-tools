# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/tracing/otel.py

Prompts

```
['create an OpenTelemetry tracer provider with OTLP endpoint and extra resource attributes', 'build a worker-process OpenTelemetry tracer inheriting trace context from the main process', 'run a function that returns an OTLP span exporter configured with grpc or http/protobuf protocol', 'test extracting W3C trace context from HTTP headers for distributed tracing', 'refactor a sync or async function to wrap it in an OpenTelemetry span with code attributes', 'check if a headers dictionary contains W3C trace context headers like traceparent or tracestate', 'extract only trace-related headers from a larger header dictionary for logging or context propagation', 'use SpanAttributes constants for OpenTelemetry-compatible span attribute names in tracing', 'use LoadingSpanAttributes constants for code-level tracing with file, function, and line number attributes', 'log a one-time warning when a request contains trace context but tracing is disabled']
```

Usage

```
{'create_init_otel_tracer': 'create an OpenTelemetry tracer provider with OTLP endpoint and extra resource attributes', 'build_init_otel_worker_tracer': 'build a worker-process OpenTelemetry tracer inheriting trace context from the main process', 'run_get_span_exporter': 'run a function that returns an OTLP span exporter configured with grpc or http/protobuf protocol', 'test_extract_trace_context': 'test extracting W3C trace context from HTTP headers for distributed tracing', 'refactor_instrument_otel': 'refactor a sync or async function to wrap it in an OpenTelemetry span with code attributes'}
```

## File: vllm-project_vllm/vllm/tracing/utils.py

Prompts

```
['create an OpenTelemetry tracer provider with OTLP endpoint and extra resource attributes', 'build a worker-process OpenTelemetry tracer inheriting trace context from the main process', 'run a function that returns an OTLP span exporter configured with grpc or http/protobuf protocol', 'test extracting W3C trace context from HTTP headers for distributed tracing', 'refactor a sync or async function to wrap it in an OpenTelemetry span with code attributes', 'check if a headers dictionary contains W3C trace context headers like traceparent or tracestate', 'extract only trace-related headers from a larger header dictionary for logging or context propagation', 'use SpanAttributes constants for OpenTelemetry-compatible span attribute names in tracing', 'use LoadingSpanAttributes constants for code-level tracing with file, function, and line number attributes', 'log a one-time warning when a request contains trace context but tracing is disabled']
```

Usage

```
{'check_contains_trace_headers': 'check if a headers dictionary contains W3C trace context headers like traceparent or tracestate', 'extract_trace_headers': 'extract only trace-related headers from a larger header dictionary for logging or context propagation', 'use_SpanAttributes_constants': 'use SpanAttributes constants for OpenTelemetry-compatible span attribute names in tracing', 'use_LoadingSpanAttributes_constants': 'use LoadingSpanAttributes constants for code-level tracing with file, function, and line number attributes', 'log_tracing_disabled_warning': 'log a one-time warning when a request contains trace context but tracing is disabled'}
```

