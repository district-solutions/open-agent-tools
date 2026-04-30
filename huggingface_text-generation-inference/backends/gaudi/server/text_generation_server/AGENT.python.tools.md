# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/backends/gaudi/server/text_generation_server/cache.py

Prompts

```
['create a Cache instance to store and manage Batch entries keyed by batch_id', 'pop a Batch entry from the Cache by its batch_id and return it', "set a Batch entry in the Cache using the entry's batch_id as the key", 'delete a Batch by batch_id from the Cache and clear CUDA memory if available', 'clear all entries from the Cache and free CUDA memory for each deleted batch', 'run the text generation inference server with a specified model id and optional quantization settings', 'download model weights from the huggingface hub for a given model id and revision', 'quantize a model using GPTQ 4-bit quantization and save the output to a directory', 'review the serve command to understand sharded deployment and LoRA adapter configuration options', 'review the Quantization, Dtype, and KVCacheDtype enums to understand supported quantization and precision options', 'start a gRPC text generation inference server on Intel Gaudi HPU with model loading and LoRA adapter support', 'implement a gRPC servicer class with async methods for Info, Health, ServiceDiscovery, ClearCache, FilterBatch, Warmup, Prefill, and Decode', 'create a SignalHandler class that catches SIGINT and SIGTERM signals to stop the server loop gracefully', 'run model warmup with paged attention to determine max supported total tokens and max input tokens', 'process prefill and decode batches through the model generate_token method and cache resulting batches', 'setup OpenTelemetry tracing with an OTLP exporter and batch span processor for a named service', 'create a UDSOpenTelemetryAioServerInterceptor instance to intercept gRPC calls over Unix domain sockets with tracing', 'start a tracing span for a gRPC server handler call with unix transport attributes', 'review the UDSOpenTelemetryAioServerInterceptor class and its _start_span method for unix socket gRPC tracing support', 'refactor the setup_tracing function to support secure OTLP endpoints or additional span processors']
```

Usage

```
{'create_cache_instance': 'create a Cache instance to store and manage Batch entries keyed by batch_id', 'pop_batch_from_cache': 'pop a Batch entry from the Cache by its batch_id and return it', 'set_batch_in_cache': "set a Batch entry in the Cache using the entry's batch_id as the key", 'delete_batch_and_clear_gpu': 'delete a Batch by batch_id from the Cache and clear CUDA memory if available', 'clear_all_cache_entries': 'clear all entries from the Cache and free CUDA memory for each deleted batch'}
```

## File: huggingface_text-generation-inference/backends/gaudi/server/text_generation_server/cli.py

Prompts

```
['create a Cache instance to store and manage Batch entries keyed by batch_id', 'pop a Batch entry from the Cache by its batch_id and return it', "set a Batch entry in the Cache using the entry's batch_id as the key", 'delete a Batch by batch_id from the Cache and clear CUDA memory if available', 'clear all entries from the Cache and free CUDA memory for each deleted batch', 'run the text generation inference server with a specified model id and optional quantization settings', 'download model weights from the huggingface hub for a given model id and revision', 'quantize a model using GPTQ 4-bit quantization and save the output to a directory', 'review the serve command to understand sharded deployment and LoRA adapter configuration options', 'review the Quantization, Dtype, and KVCacheDtype enums to understand supported quantization and precision options', 'start a gRPC text generation inference server on Intel Gaudi HPU with model loading and LoRA adapter support', 'implement a gRPC servicer class with async methods for Info, Health, ServiceDiscovery, ClearCache, FilterBatch, Warmup, Prefill, and Decode', 'create a SignalHandler class that catches SIGINT and SIGTERM signals to stop the server loop gracefully', 'run model warmup with paged attention to determine max supported total tokens and max input tokens', 'process prefill and decode batches through the model generate_token method and cache resulting batches', 'setup OpenTelemetry tracing with an OTLP exporter and batch span processor for a named service', 'create a UDSOpenTelemetryAioServerInterceptor instance to intercept gRPC calls over Unix domain sockets with tracing', 'start a tracing span for a gRPC server handler call with unix transport attributes', 'review the UDSOpenTelemetryAioServerInterceptor class and its _start_span method for unix socket gRPC tracing support', 'refactor the setup_tracing function to support secure OTLP endpoints or additional span processors']
```

Usage

```
{'serve_text_generation_model': 'run the text generation inference server with a specified model id and optional quantization settings', 'download_model_weights': 'download model weights from the huggingface hub for a given model id and revision', 'quantize_model_gptq': 'quantize a model using GPTQ 4-bit quantization and save the output to a directory', 'review_serve_command': 'review the serve command to understand sharded deployment and LoRA adapter configuration options', 'review_quantization_enums': 'review the Quantization, Dtype, and KVCacheDtype enums to understand supported quantization and precision options'}
```

## File: huggingface_text-generation-inference/backends/gaudi/server/text_generation_server/server.py

Prompts

```
['create a Cache instance to store and manage Batch entries keyed by batch_id', 'pop a Batch entry from the Cache by its batch_id and return it', "set a Batch entry in the Cache using the entry's batch_id as the key", 'delete a Batch by batch_id from the Cache and clear CUDA memory if available', 'clear all entries from the Cache and free CUDA memory for each deleted batch', 'run the text generation inference server with a specified model id and optional quantization settings', 'download model weights from the huggingface hub for a given model id and revision', 'quantize a model using GPTQ 4-bit quantization and save the output to a directory', 'review the serve command to understand sharded deployment and LoRA adapter configuration options', 'review the Quantization, Dtype, and KVCacheDtype enums to understand supported quantization and precision options', 'start a gRPC text generation inference server on Intel Gaudi HPU with model loading and LoRA adapter support', 'implement a gRPC servicer class with async methods for Info, Health, ServiceDiscovery, ClearCache, FilterBatch, Warmup, Prefill, and Decode', 'create a SignalHandler class that catches SIGINT and SIGTERM signals to stop the server loop gracefully', 'run model warmup with paged attention to determine max supported total tokens and max input tokens', 'process prefill and decode batches through the model generate_token method and cache resulting batches', 'setup OpenTelemetry tracing with an OTLP exporter and batch span processor for a named service', 'create a UDSOpenTelemetryAioServerInterceptor instance to intercept gRPC calls over Unix domain sockets with tracing', 'start a tracing span for a gRPC server handler call with unix transport attributes', 'review the UDSOpenTelemetryAioServerInterceptor class and its _start_span method for unix socket gRPC tracing support', 'refactor the setup_tracing function to support secure OTLP endpoints or additional span processors']
```

Usage

```
{'serve_text_generation_server': 'start a gRPC text generation inference server on Intel Gaudi HPU with model loading and LoRA adapter support', 'implement_text_generation_service': 'implement a gRPC servicer class with async methods for Info, Health, ServiceDiscovery, ClearCache, FilterBatch, Warmup, Prefill, and Decode', 'handle_graceful_shutdown': 'create a SignalHandler class that catches SIGINT and SIGTERM signals to stop the server loop gracefully', 'run_warmup_with_paged_attention': 'run model warmup with paged attention to determine max supported total tokens and max input tokens', 'process_prefill_and_decode_batches': 'process prefill and decode batches through the model generate_token method and cache resulting batches'}
```

## File: huggingface_text-generation-inference/backends/gaudi/server/text_generation_server/tracing.py

Prompts

```
['create a Cache instance to store and manage Batch entries keyed by batch_id', 'pop a Batch entry from the Cache by its batch_id and return it', "set a Batch entry in the Cache using the entry's batch_id as the key", 'delete a Batch by batch_id from the Cache and clear CUDA memory if available', 'clear all entries from the Cache and free CUDA memory for each deleted batch', 'run the text generation inference server with a specified model id and optional quantization settings', 'download model weights from the huggingface hub for a given model id and revision', 'quantize a model using GPTQ 4-bit quantization and save the output to a directory', 'review the serve command to understand sharded deployment and LoRA adapter configuration options', 'review the Quantization, Dtype, and KVCacheDtype enums to understand supported quantization and precision options', 'start a gRPC text generation inference server on Intel Gaudi HPU with model loading and LoRA adapter support', 'implement a gRPC servicer class with async methods for Info, Health, ServiceDiscovery, ClearCache, FilterBatch, Warmup, Prefill, and Decode', 'create a SignalHandler class that catches SIGINT and SIGTERM signals to stop the server loop gracefully', 'run model warmup with paged attention to determine max supported total tokens and max input tokens', 'process prefill and decode batches through the model generate_token method and cache resulting batches', 'setup OpenTelemetry tracing with an OTLP exporter and batch span processor for a named service', 'create a UDSOpenTelemetryAioServerInterceptor instance to intercept gRPC calls over Unix domain sockets with tracing', 'start a tracing span for a gRPC server handler call with unix transport attributes', 'review the UDSOpenTelemetryAioServerInterceptor class and its _start_span method for unix socket gRPC tracing support', 'refactor the setup_tracing function to support secure OTLP endpoints or additional span processors']
```

Usage

```
{'setup_tracing': 'setup OpenTelemetry tracing with an OTLP exporter and batch span processor for a named service', 'create_UDSOpenTelemetryAioServerInterceptor': 'create a UDSOpenTelemetryAioServerInterceptor instance to intercept gRPC calls over Unix domain sockets with tracing', 'start_span_with_UDS_interceptor': 'start a tracing span for a gRPC server handler call with unix transport attributes', 'review_UDSOpenTelemetryAioServerInterceptor': 'review the UDSOpenTelemetryAioServerInterceptor class and its _start_span method for unix socket gRPC tracing support', 'refactor_setup_tracing': 'refactor the setup_tracing function to support secure OTLP endpoints or additional span processors'}
```

