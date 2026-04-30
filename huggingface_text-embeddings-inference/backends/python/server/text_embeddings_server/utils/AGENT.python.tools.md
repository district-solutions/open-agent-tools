# Agent Python Tools

- repo: huggingface/text-embeddings-inference
- repo_uri: https://github.com/huggingface/text-embeddings-inference

## File: huggingface_text-embeddings-inference/backends/python/server/text_embeddings_server/utils/device.py

Prompts

```
['get the best available torch device auto detecting cuda hpu xpu or cpu', 'check if a habana gaudi hpu is available on the current system', 'check if running on an amd rocm gpu with torch built with hip', 'check if intel extension for pytorch should be used based on env and availability', 'check if reduced precision fp16 bf16 is allowed via the allow reduced precision env var', 'run the attention function to dispatch variable-length attention based on detected hardware backend', 'run the rocm_attn function to compute scaled dot product attention on ROCm GPUs', 'run the hpu_attn function to compute fused scaled dot product attention on Habana HPU devices', 'review the module-level code that detects hardware and selects flash attention v1 or v2', 'refactor the attention dispatcher to support a new hardware backend like TPU', 'setup OpenTelemetry tracing with an OTLP endpoint and service name for distributed tracing', 'create a UDSOpenTelemetryAioServerInterceptor instance to intercept gRPC calls over Unix domain sockets', 'start a tracing span with gRPC method attributes and Unix transport for a handler call', 'configure an OTLPSpanExporter with BatchSpanProcessor to export spans to an OTLP endpoint', 'review the setup_tracing function and UDSOpenTelemetryAioServerInterceptor class for OpenTelemetry gRPC tracing configuration']
```

Usage

```
{'get_device_auto_detect': 'get the best available torch device auto detecting cuda hpu xpu or cpu', 'check_is_hpu': 'check if a habana gaudi hpu is available on the current system', 'check_is_rocm': 'check if running on an amd rocm gpu with torch built with hip', 'check_use_ipex': 'check if intel extension for pytorch should be used based on env and availability', 'check_allow_reduced_precision': 'check if reduced precision fp16 bf16 is allowed via the allow reduced precision env var'}
```

## File: huggingface_text-embeddings-inference/backends/python/server/text_embeddings_server/utils/flash_attn.py

Prompts

```
['get the best available torch device auto detecting cuda hpu xpu or cpu', 'check if a habana gaudi hpu is available on the current system', 'check if running on an amd rocm gpu with torch built with hip', 'check if intel extension for pytorch should be used based on env and availability', 'check if reduced precision fp16 bf16 is allowed via the allow reduced precision env var', 'run the attention function to dispatch variable-length attention based on detected hardware backend', 'run the rocm_attn function to compute scaled dot product attention on ROCm GPUs', 'run the hpu_attn function to compute fused scaled dot product attention on Habana HPU devices', 'review the module-level code that detects hardware and selects flash attention v1 or v2', 'refactor the attention dispatcher to support a new hardware backend like TPU', 'setup OpenTelemetry tracing with an OTLP endpoint and service name for distributed tracing', 'create a UDSOpenTelemetryAioServerInterceptor instance to intercept gRPC calls over Unix domain sockets', 'start a tracing span with gRPC method attributes and Unix transport for a handler call', 'configure an OTLPSpanExporter with BatchSpanProcessor to export spans to an OTLP endpoint', 'review the setup_tracing function and UDSOpenTelemetryAioServerInterceptor class for OpenTelemetry gRPC tracing configuration']
```

Usage

```
{'run_attention_dispatch': 'run the attention function to dispatch variable-length attention based on detected hardware backend', 'run_rocm_attn': 'run the rocm_attn function to compute scaled dot product attention on ROCm GPUs', 'run_hpu_attn': 'run the hpu_attn function to compute fused scaled dot product attention on Habana HPU devices', 'review_attention_backend_detection': 'review the module-level code that detects hardware and selects flash attention v1 or v2', 'refactor_attention_for_new_backend': 'refactor the attention dispatcher to support a new hardware backend like TPU'}
```

## File: huggingface_text-embeddings-inference/backends/python/server/text_embeddings_server/utils/tracing.py

Prompts

```
['get the best available torch device auto detecting cuda hpu xpu or cpu', 'check if a habana gaudi hpu is available on the current system', 'check if running on an amd rocm gpu with torch built with hip', 'check if intel extension for pytorch should be used based on env and availability', 'check if reduced precision fp16 bf16 is allowed via the allow reduced precision env var', 'run the attention function to dispatch variable-length attention based on detected hardware backend', 'run the rocm_attn function to compute scaled dot product attention on ROCm GPUs', 'run the hpu_attn function to compute fused scaled dot product attention on Habana HPU devices', 'review the module-level code that detects hardware and selects flash attention v1 or v2', 'refactor the attention dispatcher to support a new hardware backend like TPU', 'setup OpenTelemetry tracing with an OTLP endpoint and service name for distributed tracing', 'create a UDSOpenTelemetryAioServerInterceptor instance to intercept gRPC calls over Unix domain sockets', 'start a tracing span with gRPC method attributes and Unix transport for a handler call', 'configure an OTLPSpanExporter with BatchSpanProcessor to export spans to an OTLP endpoint', 'review the setup_tracing function and UDSOpenTelemetryAioServerInterceptor class for OpenTelemetry gRPC tracing configuration']
```

Usage

```
{'setup_opentelemetry_tracing': 'setup OpenTelemetry tracing with an OTLP endpoint and service name for distributed tracing', 'create_uds_grpc_interceptor': 'create a UDSOpenTelemetryAioServerInterceptor instance to intercept gRPC calls over Unix domain sockets', 'start_tracing_span': 'start a tracing span with gRPC method attributes and Unix transport for a handler call', 'configure_span_exporter': 'configure an OTLPSpanExporter with BatchSpanProcessor to export spans to an OTLP endpoint', 'review_tracing_setup': 'review the setup_tracing function and UDSOpenTelemetryAioServerInterceptor class for OpenTelemetry gRPC tracing configuration'}
```

