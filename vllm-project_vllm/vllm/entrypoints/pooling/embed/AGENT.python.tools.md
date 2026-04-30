# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/pooling/embed/api_router.py

Prompts

```
['create embeddings via the OpenAI-compatible /v1/embeddings endpoint with EmbeddingRequest', 'create embeddings via the Cohere-compatible /v2/embed endpoint with CohereEmbedRequest', 'get the ServingEmbedding handler from the request app state for embedding inference', 'validate incoming JSON requests before processing embedding endpoints', 'create a FastAPI router with /v1/embeddings and /v2/embed POST endpoints for embedding generation', 'create an EmbedIOProcessor instance to handle text and image embedding requests for a vLLM pooling model', 'preprocess Cohere embedding requests with text, images, or mixed inputs into engine prompts via chat templates', 'chunk long text prompts beyond max_model_len and aggregate chunked embeddings using weighted mean pooling', 'resolve and validate Cohere truncation settings with max_tokens enforcement for embedding inputs', 'preprocess Jina ranking requests by concatenating documents before query for bi-encoder ranking models', 'build float embeddings into multiple Cohere embedding types including float, binary, ubinary, and base64', 'create an OpenAI-style embedding completion request with pooling and tokenization parameters', 'create an OpenAI-style embedding chat request with pooling and tokenization parameters', 'create an OpenAI-style embedding response with per-embedding data and usage info', 'create a Cohere v2 embedding request supporting texts, images, and typed outputs', 'build a ServingEmbedding class that supports both OpenAI and Cohere embedding API formats', 'create an OpenAI-format JSON response with float or base64-encoded embedding outputs', 'create an OpenAI-format streaming response with binary-encoded embedding outputs', 'build a Cohere-format embedding response with typed embeddings and billed unit metadata', 'test the ServingEmbedding class for both OpenAI and Cohere embedding request formats']
```

Usage

```
{'create_embedding_v1': 'create embeddings via the OpenAI-compatible /v1/embeddings endpoint with EmbeddingRequest', 'create_cohere_embedding_v2': 'create embeddings via the Cohere-compatible /v2/embed endpoint with CohereEmbedRequest', 'get_serving_embedding': 'get the ServingEmbedding handler from the request app state for embedding inference', 'validate_json_request': 'validate incoming JSON requests before processing embedding endpoints', 'create_embedding_router': 'create a FastAPI router with /v1/embeddings and /v2/embed POST endpoints for embedding generation'}
```

## File: vllm-project_vllm/vllm/entrypoints/pooling/embed/io_processor.py

Prompts

```
['create embeddings via the OpenAI-compatible /v1/embeddings endpoint with EmbeddingRequest', 'create embeddings via the Cohere-compatible /v2/embed endpoint with CohereEmbedRequest', 'get the ServingEmbedding handler from the request app state for embedding inference', 'validate incoming JSON requests before processing embedding endpoints', 'create a FastAPI router with /v1/embeddings and /v2/embed POST endpoints for embedding generation', 'create an EmbedIOProcessor instance to handle text and image embedding requests for a vLLM pooling model', 'preprocess Cohere embedding requests with text, images, or mixed inputs into engine prompts via chat templates', 'chunk long text prompts beyond max_model_len and aggregate chunked embeddings using weighted mean pooling', 'resolve and validate Cohere truncation settings with max_tokens enforcement for embedding inputs', 'preprocess Jina ranking requests by concatenating documents before query for bi-encoder ranking models', 'build float embeddings into multiple Cohere embedding types including float, binary, ubinary, and base64', 'create an OpenAI-style embedding completion request with pooling and tokenization parameters', 'create an OpenAI-style embedding chat request with pooling and tokenization parameters', 'create an OpenAI-style embedding response with per-embedding data and usage info', 'create a Cohere v2 embedding request supporting texts, images, and typed outputs', 'build a ServingEmbedding class that supports both OpenAI and Cohere embedding API formats', 'create an OpenAI-format JSON response with float or base64-encoded embedding outputs', 'create an OpenAI-format streaming response with binary-encoded embedding outputs', 'build a Cohere-format embedding response with typed embeddings and billed unit metadata', 'test the ServingEmbedding class for both OpenAI and Cohere embedding request formats']
```

Usage

```
{'create_embedding_processor': 'create an EmbedIOProcessor instance to handle text and image embedding requests for a vLLM pooling model', 'preprocess_cohere_embeddings': 'preprocess Cohere embedding requests with text, images, or mixed inputs into engine prompts via chat templates', 'chunk_long_text_embeddings': 'chunk long text prompts beyond max_model_len and aggregate chunked embeddings using weighted mean pooling', 'validate_cohere_truncation': 'resolve and validate Cohere truncation settings with max_tokens enforcement for embedding inputs', 'process_jina_ranking_prompts': 'preprocess Jina ranking requests by concatenating documents before query for bi-encoder ranking models'}
```

## File: vllm-project_vllm/vllm/entrypoints/pooling/embed/protocol.py

Prompts

```
['create embeddings via the OpenAI-compatible /v1/embeddings endpoint with EmbeddingRequest', 'create embeddings via the Cohere-compatible /v2/embed endpoint with CohereEmbedRequest', 'get the ServingEmbedding handler from the request app state for embedding inference', 'validate incoming JSON requests before processing embedding endpoints', 'create a FastAPI router with /v1/embeddings and /v2/embed POST endpoints for embedding generation', 'create an EmbedIOProcessor instance to handle text and image embedding requests for a vLLM pooling model', 'preprocess Cohere embedding requests with text, images, or mixed inputs into engine prompts via chat templates', 'chunk long text prompts beyond max_model_len and aggregate chunked embeddings using weighted mean pooling', 'resolve and validate Cohere truncation settings with max_tokens enforcement for embedding inputs', 'preprocess Jina ranking requests by concatenating documents before query for bi-encoder ranking models', 'build float embeddings into multiple Cohere embedding types including float, binary, ubinary, and base64', 'create an OpenAI-style embedding completion request with pooling and tokenization parameters', 'create an OpenAI-style embedding chat request with pooling and tokenization parameters', 'create an OpenAI-style embedding response with per-embedding data and usage info', 'create a Cohere v2 embedding request supporting texts, images, and typed outputs', 'build a ServingEmbedding class that supports both OpenAI and Cohere embedding API formats', 'create an OpenAI-format JSON response with float or base64-encoded embedding outputs', 'create an OpenAI-format streaming response with binary-encoded embedding outputs', 'build a Cohere-format embedding response with typed embeddings and billed unit metadata', 'test the ServingEmbedding class for both OpenAI and Cohere embedding request formats']
```

Usage

```
{'build_typed_embeddings': 'build float embeddings into multiple Cohere embedding types including float, binary, ubinary, and base64', 'create_EmbeddingCompletionRequest': 'create an OpenAI-style embedding completion request with pooling and tokenization parameters', 'create_EmbeddingChatRequest': 'create an OpenAI-style embedding chat request with pooling and tokenization parameters', 'create_EmbeddingResponse': 'create an OpenAI-style embedding response with per-embedding data and usage info', 'create_CohereEmbedRequest': 'create a Cohere v2 embedding request supporting texts, images, and typed outputs'}
```

## File: vllm-project_vllm/vllm/entrypoints/pooling/embed/serving.py

Prompts

```
['create embeddings via the OpenAI-compatible /v1/embeddings endpoint with EmbeddingRequest', 'create embeddings via the Cohere-compatible /v2/embed endpoint with CohereEmbedRequest', 'get the ServingEmbedding handler from the request app state for embedding inference', 'validate incoming JSON requests before processing embedding endpoints', 'create a FastAPI router with /v1/embeddings and /v2/embed POST endpoints for embedding generation', 'create an EmbedIOProcessor instance to handle text and image embedding requests for a vLLM pooling model', 'preprocess Cohere embedding requests with text, images, or mixed inputs into engine prompts via chat templates', 'chunk long text prompts beyond max_model_len and aggregate chunked embeddings using weighted mean pooling', 'resolve and validate Cohere truncation settings with max_tokens enforcement for embedding inputs', 'preprocess Jina ranking requests by concatenating documents before query for bi-encoder ranking models', 'build float embeddings into multiple Cohere embedding types including float, binary, ubinary, and base64', 'create an OpenAI-style embedding completion request with pooling and tokenization parameters', 'create an OpenAI-style embedding chat request with pooling and tokenization parameters', 'create an OpenAI-style embedding response with per-embedding data and usage info', 'create a Cohere v2 embedding request supporting texts, images, and typed outputs', 'build a ServingEmbedding class that supports both OpenAI and Cohere embedding API formats', 'create an OpenAI-format JSON response with float or base64-encoded embedding outputs', 'create an OpenAI-format streaming response with binary-encoded embedding outputs', 'build a Cohere-format embedding response with typed embeddings and billed unit metadata', 'test the ServingEmbedding class for both OpenAI and Cohere embedding request formats']
```

Usage

```
{'build_servingembedding_class': 'build a ServingEmbedding class that supports both OpenAI and Cohere embedding API formats', 'create_openai_json_response': 'create an OpenAI-format JSON response with float or base64-encoded embedding outputs', 'create_openai_bytes_response': 'create an OpenAI-format streaming response with binary-encoded embedding outputs', 'build_cohere_response': 'build a Cohere-format embedding response with typed embeddings and billed unit metadata', 'test_servingembedding': 'test the ServingEmbedding class for both OpenAI and Cohere embedding request formats'}
```

