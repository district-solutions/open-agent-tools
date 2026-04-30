# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/server/text_generation_server/cache.py

Prompts

```
['create a Cache instance to store and manage Batch entries by batch_id', 'set a Batch entry in the Cache using its batch_id as the key', 'pop and retrieve a Batch entry from the Cache by its batch_id', 'delete a Batch entry from the Cache and free CUDA memory if available', 'clear all entries from the Cache and free CUDA memory for each removed entry', 'run the text generation server with a model id and optional quantization settings', 'download model weights from the Hugging Face hub for a given model id', 'quantize a model using GPTQ 4-bit quantization and save to an output directory', 'review the serve function that starts the text generation server with sharding and LoRA support', 'review the Quantization enum that defines supported quantization methods like GPTQ, AWQ, and bitsandbytes', 'run the gRPC text generation inference server with a specified model and optional LoRA adapters', 'start a TextGenerationService gRPC servicer with a model, cache, and server URLs', 'handle prefill and decode batch requests for token generation via the TextGenerationService', 'warmup the model with a batch to compute max supported total tokens and allocate quantization buffers', 'handle SIGINT and SIGTERM signals with the SignalHandler class for graceful server shutdown', 'setup OpenTelemetry tracing with an OTLP endpoint and service name for distributed tracing', 'create a UDSOpenTelemetryAioServerInterceptor instance to intercept gRPC calls over Unix domain sockets', 'review the _start_span method that parses gRPC service and method names into span attributes', 'refactor the UDSOpenTelemetryAioServerInterceptor to add custom attributes to gRPC spans', 'run setup_tracing to configure a TracerProvider with a BatchSpanProcessor and OTLP exporter']
```

Usage

```
{'create_cache_instance': 'create a Cache instance to store and manage Batch entries by batch_id', 'set_cache_entry': 'set a Batch entry in the Cache using its batch_id as the key', 'pop_cache_entry': 'pop and retrieve a Batch entry from the Cache by its batch_id', 'delete_cache_entry': 'delete a Batch entry from the Cache and free CUDA memory if available', 'clear_all_cache': 'clear all entries from the Cache and free CUDA memory for each removed entry'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/cli.py

Prompts

```
['create a Cache instance to store and manage Batch entries by batch_id', 'set a Batch entry in the Cache using its batch_id as the key', 'pop and retrieve a Batch entry from the Cache by its batch_id', 'delete a Batch entry from the Cache and free CUDA memory if available', 'clear all entries from the Cache and free CUDA memory for each removed entry', 'run the text generation server with a model id and optional quantization settings', 'download model weights from the Hugging Face hub for a given model id', 'quantize a model using GPTQ 4-bit quantization and save to an output directory', 'review the serve function that starts the text generation server with sharding and LoRA support', 'review the Quantization enum that defines supported quantization methods like GPTQ, AWQ, and bitsandbytes', 'run the gRPC text generation inference server with a specified model and optional LoRA adapters', 'start a TextGenerationService gRPC servicer with a model, cache, and server URLs', 'handle prefill and decode batch requests for token generation via the TextGenerationService', 'warmup the model with a batch to compute max supported total tokens and allocate quantization buffers', 'handle SIGINT and SIGTERM signals with the SignalHandler class for graceful server shutdown', 'setup OpenTelemetry tracing with an OTLP endpoint and service name for distributed tracing', 'create a UDSOpenTelemetryAioServerInterceptor instance to intercept gRPC calls over Unix domain sockets', 'review the _start_span method that parses gRPC service and method names into span attributes', 'refactor the UDSOpenTelemetryAioServerInterceptor to add custom attributes to gRPC spans', 'run setup_tracing to configure a TracerProvider with a BatchSpanProcessor and OTLP exporter']
```

Usage

```
{'run_serve_command': 'run the text generation server with a model id and optional quantization settings', 'run_download_weights_command': 'download model weights from the Hugging Face hub for a given model id', 'run_quantize_command': 'quantize a model using GPTQ 4-bit quantization and save to an output directory', 'review_serve_function': 'review the serve function that starts the text generation server with sharding and LoRA support', 'review_quantization_enum': 'review the Quantization enum that defines supported quantization methods like GPTQ, AWQ, and bitsandbytes'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/server.py

Prompts

```
['create a Cache instance to store and manage Batch entries by batch_id', 'set a Batch entry in the Cache using its batch_id as the key', 'pop and retrieve a Batch entry from the Cache by its batch_id', 'delete a Batch entry from the Cache and free CUDA memory if available', 'clear all entries from the Cache and free CUDA memory for each removed entry', 'run the text generation server with a model id and optional quantization settings', 'download model weights from the Hugging Face hub for a given model id', 'quantize a model using GPTQ 4-bit quantization and save to an output directory', 'review the serve function that starts the text generation server with sharding and LoRA support', 'review the Quantization enum that defines supported quantization methods like GPTQ, AWQ, and bitsandbytes', 'run the gRPC text generation inference server with a specified model and optional LoRA adapters', 'start a TextGenerationService gRPC servicer with a model, cache, and server URLs', 'handle prefill and decode batch requests for token generation via the TextGenerationService', 'warmup the model with a batch to compute max supported total tokens and allocate quantization buffers', 'handle SIGINT and SIGTERM signals with the SignalHandler class for graceful server shutdown', 'setup OpenTelemetry tracing with an OTLP endpoint and service name for distributed tracing', 'create a UDSOpenTelemetryAioServerInterceptor instance to intercept gRPC calls over Unix domain sockets', 'review the _start_span method that parses gRPC service and method names into span attributes', 'refactor the UDSOpenTelemetryAioServerInterceptor to add custom attributes to gRPC spans', 'run setup_tracing to configure a TracerProvider with a BatchSpanProcessor and OTLP exporter']
```

Usage

```
{'run_text_generation_server': 'run the gRPC text generation inference server with a specified model and optional LoRA adapters', 'start_TextGenerationService': 'start a TextGenerationService gRPC servicer with a model, cache, and server URLs', 'handle_prefill_decode': 'handle prefill and decode batch requests for token generation via the TextGenerationService', 'warmup_model': 'warmup the model with a batch to compute max supported total tokens and allocate quantization buffers', 'handle_signals': 'handle SIGINT and SIGTERM signals with the SignalHandler class for graceful server shutdown'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/tracing.py

Prompts

```
['create a Cache instance to store and manage Batch entries by batch_id', 'set a Batch entry in the Cache using its batch_id as the key', 'pop and retrieve a Batch entry from the Cache by its batch_id', 'delete a Batch entry from the Cache and free CUDA memory if available', 'clear all entries from the Cache and free CUDA memory for each removed entry', 'run the text generation server with a model id and optional quantization settings', 'download model weights from the Hugging Face hub for a given model id', 'quantize a model using GPTQ 4-bit quantization and save to an output directory', 'review the serve function that starts the text generation server with sharding and LoRA support', 'review the Quantization enum that defines supported quantization methods like GPTQ, AWQ, and bitsandbytes', 'run the gRPC text generation inference server with a specified model and optional LoRA adapters', 'start a TextGenerationService gRPC servicer with a model, cache, and server URLs', 'handle prefill and decode batch requests for token generation via the TextGenerationService', 'warmup the model with a batch to compute max supported total tokens and allocate quantization buffers', 'handle SIGINT and SIGTERM signals with the SignalHandler class for graceful server shutdown', 'setup OpenTelemetry tracing with an OTLP endpoint and service name for distributed tracing', 'create a UDSOpenTelemetryAioServerInterceptor instance to intercept gRPC calls over Unix domain sockets', 'review the _start_span method that parses gRPC service and method names into span attributes', 'refactor the UDSOpenTelemetryAioServerInterceptor to add custom attributes to gRPC spans', 'run setup_tracing to configure a TracerProvider with a BatchSpanProcessor and OTLP exporter']
```

Usage

```
{'setup_tracing': 'setup OpenTelemetry tracing with an OTLP endpoint and service name for distributed tracing', 'create_UDSOpenTelemetryAioServerInterceptor': 'create a UDSOpenTelemetryAioServerInterceptor instance to intercept gRPC calls over Unix domain sockets', 'review_UDSOpenTelemetryAioServerInterceptor_start_span': 'review the _start_span method that parses gRPC service and method names into span attributes', 'refactor_UDSOpenTelemetryAioServerInterceptor': 'refactor the UDSOpenTelemetryAioServerInterceptor to add custom attributes to gRPC spans', 'run_setup_tracing': 'run setup_tracing to configure a TracerProvider with a BatchSpanProcessor and OTLP exporter'}
```

