# Agent Python Tools

- repo: huggingface/text-embeddings-inference
- repo_uri: https://github.com/huggingface/text-embeddings-inference

## File: huggingface_text-embeddings-inference/backends/python/server/text_embeddings_server/cli.py

Prompts

```
['run the text embeddings inference server with a given model path and dtype', 'start the text embeddings server with OpenTelemetry tracing enabled via an OTLP endpoint', 'run the text embeddings server with JSON-formatted log output to stdout', 'review the Dtype enum that defines float32, float16, and bfloat16 data type options', 'refactor the serve CLI command to support additional model configuration options', 'run the gRPC embedding service server on a Unix domain socket with a loaded model', 'create an EmbeddingService instance that wraps a Model and forces PyTorch inference mode', 'test the EmbeddingService Embed method to generate embeddings from a gRPC request batch', 'test the EmbeddingService Predict method to generate prediction scores from a gRPC request batch', 'review the EmbeddingService Health method that validates CUDA device availability before responding']
```

Usage

```
{'run_text_embeddings_server': 'run the text embeddings inference server with a given model path and dtype', 'serve_with_tracing': 'start the text embeddings server with OpenTelemetry tracing enabled via an OTLP endpoint', 'serve_json_logging': 'run the text embeddings server with JSON-formatted log output to stdout', 'review_dtype_enum': 'review the Dtype enum that defines float32, float16, and bfloat16 data type options', 'refactor_serve_command': 'refactor the serve CLI command to support additional model configuration options'}
```

## File: huggingface_text-embeddings-inference/backends/python/server/text_embeddings_server/server.py

Prompts

```
['run the text embeddings inference server with a given model path and dtype', 'start the text embeddings server with OpenTelemetry tracing enabled via an OTLP endpoint', 'run the text embeddings server with JSON-formatted log output to stdout', 'review the Dtype enum that defines float32, float16, and bfloat16 data type options', 'refactor the serve CLI command to support additional model configuration options', 'run the gRPC embedding service server on a Unix domain socket with a loaded model', 'create an EmbeddingService instance that wraps a Model and forces PyTorch inference mode', 'test the EmbeddingService Embed method to generate embeddings from a gRPC request batch', 'test the EmbeddingService Predict method to generate prediction scores from a gRPC request batch', 'review the EmbeddingService Health method that validates CUDA device availability before responding']
```

Usage

```
{'run_embedding_service_server': 'run the gRPC embedding service server on a Unix domain socket with a loaded model', 'create_embedding_service': 'create an EmbeddingService instance that wraps a Model and forces PyTorch inference mode', 'test_embed_method': 'test the EmbeddingService Embed method to generate embeddings from a gRPC request batch', 'test_predict_method': 'test the EmbeddingService Predict method to generate prediction scores from a gRPC request batch', 'review_health_check': 'review the EmbeddingService Health method that validates CUDA device availability before responding'}
```

