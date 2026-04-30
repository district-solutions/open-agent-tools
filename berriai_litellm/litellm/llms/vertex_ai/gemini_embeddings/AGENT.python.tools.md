# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/vertex_ai/gemini_embeddings/batch_embed_content_handler.py

Prompts

```
['create a GoogleBatchEmbeddings instance to generate embeddings via Vertex AI or Gemini batch endpoints', 'run batch embeddings on text input using sync HTTP handler for Gemini or Vertex AI models', 'run async batch embeddings on text input using async HTTP handler for Gemini or Vertex AI models', 'resolve Gemini file references in embedding input to retrieve mime_type and uri via API calls', 'resolve Gemini file references in embedding input asynchronously via HTTP GET requests', 'transform OpenAI embedding input to Gemini embedContent format for text-only inputs', 'transform OpenAI embedding input to Gemini multimodal embedContent format with data URIs, GCS URLs, and file references', 'process a single Gemini embedContent response into OpenAI-compatible embedding response format', 'process a batch Gemini embedContent response into OpenAI-compatible embedding response with usage tokens', 'parse a data URL to extract media type and base64-encoded content for multimodal embeddings']
```

Usage

```
{'create_GoogleBatchEmbeddings': 'create a GoogleBatchEmbeddings instance to generate embeddings via Vertex AI or Gemini batch endpoints', 'run_batch_embeddings': 'run batch embeddings on text input using sync HTTP handler for Gemini or Vertex AI models', 'run_async_batch_embeddings': 'run async batch embeddings on text input using async HTTP handler for Gemini or Vertex AI models', 'resolve_file_references': 'resolve Gemini file references in embedding input to retrieve mime_type and uri via API calls', 'run_async_resolve_file_references': 'resolve Gemini file references in embedding input asynchronously via HTTP GET requests'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/gemini_embeddings/batch_embed_content_transformation.py

Prompts

```
['create a GoogleBatchEmbeddings instance to generate embeddings via Vertex AI or Gemini batch endpoints', 'run batch embeddings on text input using sync HTTP handler for Gemini or Vertex AI models', 'run async batch embeddings on text input using async HTTP handler for Gemini or Vertex AI models', 'resolve Gemini file references in embedding input to retrieve mime_type and uri via API calls', 'resolve Gemini file references in embedding input asynchronously via HTTP GET requests', 'transform OpenAI embedding input to Gemini embedContent format for text-only inputs', 'transform OpenAI embedding input to Gemini multimodal embedContent format with data URIs, GCS URLs, and file references', 'process a single Gemini embedContent response into OpenAI-compatible embedding response format', 'process a batch Gemini embedContent response into OpenAI-compatible embedding response with usage tokens', 'parse a data URL to extract media type and base64-encoded content for multimodal embeddings']
```

Usage

```
{'transform_openai_input_gemini_content': 'transform OpenAI embedding input to Gemini embedContent format for text-only inputs', 'transform_openai_input_gemini_embed_content': 'transform OpenAI embedding input to Gemini multimodal embedContent format with data URIs, GCS URLs, and file references', 'process_embed_content_response': 'process a single Gemini embedContent response into OpenAI-compatible embedding response format', 'process_response': 'process a batch Gemini embedContent response into OpenAI-compatible embedding response with usage tokens', '_parse_data_url': 'parse a data URL to extract media type and base64-encoded content for multimodal embeddings'}
```

