# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/huggingface/embedding/handler.py

Prompts

```
['create embeddings from text input using the HuggingFaceEmbedding class embedding method', 'async generate embeddings from text input using the HuggingFaceEmbedding class aembedding method', 'transform input text for HuggingFace embedding models based on pipeline tag like sentence-similarity or rerank', 'get the HuggingFace pipeline task type for a model from the HuggingFace Hub API', 'process raw HuggingFace embedding response into a standardized EmbeddingResponse object', 'transform litellm chat request into HuggingFace API payload with proper task routing and prompt formatting', 'transform HuggingFace API response into litellm ModelResponse with token usage and logprobs', 'build a HuggingFaceEmbeddingConfig with generation parameters like temperature, max_new_tokens, and top_p', 'get the HuggingFace API base URL from model name, api_base parameter, or environment variables', 'convert raw HuggingFace completion response into a litellm ModelResponse with choices and usage']
```

Usage

```
{'create_huggingface_embedding': 'create embeddings from text input using the HuggingFaceEmbedding class embedding method', 'async_get_embedding': 'async generate embeddings from text input using the HuggingFaceEmbedding class aembedding method', 'transform_hf_input': 'transform input text for HuggingFace embedding models based on pipeline tag like sentence-similarity or rerank', 'get_hf_task_embedding': 'get the HuggingFace pipeline task type for a model from the HuggingFace Hub API', 'process_embedding_response': 'process raw HuggingFace embedding response into a standardized EmbeddingResponse object'}
```

## File: berriai_litellm/litellm/llms/huggingface/embedding/transformation.py

Prompts

```
['create embeddings from text input using the HuggingFaceEmbedding class embedding method', 'async generate embeddings from text input using the HuggingFaceEmbedding class aembedding method', 'transform input text for HuggingFace embedding models based on pipeline tag like sentence-similarity or rerank', 'get the HuggingFace pipeline task type for a model from the HuggingFace Hub API', 'process raw HuggingFace embedding response into a standardized EmbeddingResponse object', 'transform litellm chat request into HuggingFace API payload with proper task routing and prompt formatting', 'transform HuggingFace API response into litellm ModelResponse with token usage and logprobs', 'build a HuggingFaceEmbeddingConfig with generation parameters like temperature, max_new_tokens, and top_p', 'get the HuggingFace API base URL from model name, api_base parameter, or environment variables', 'convert raw HuggingFace completion response into a litellm ModelResponse with choices and usage']
```

Usage

```
{'transform_request': 'transform litellm chat request into HuggingFace API payload with proper task routing and prompt formatting', 'transform_response': 'transform HuggingFace API response into litellm ModelResponse with token usage and logprobs', 'build_huggingface_config': 'build a HuggingFaceEmbeddingConfig with generation parameters like temperature, max_new_tokens, and top_p', 'get_api_base': 'get the HuggingFace API base URL from model name, api_base parameter, or environment variables', 'convert_to_model_response_object': 'convert raw HuggingFace completion response into a litellm ModelResponse with choices and usage'}
```

