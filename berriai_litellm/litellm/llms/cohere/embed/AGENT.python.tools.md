# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/cohere/embed/handler.py

Prompts

```
['validate environment headers and api key for Cohere embedding API requests', 'create a CohereError exception with status code and message for Cohere API errors', 'run async embedding request to Cohere API with model, input texts, and optional parameters', 'run synchronous or async embedding request to Cohere API with model and input texts', 'test the Cohere embedding handler with model, input, timeout, and logging parameters', "transform an OpenAI-format embedding request into Cohere's v2 embed request format", 'transform a raw Cohere API response into a standardized OpenAI-format embedding response', 'map OpenAI embedding params like encoding_format and dimensions to Cohere equivalents', 'calculate token usage from Cohere response metadata including billed text and image tokens', 'validate and build request headers with Content-Type and Bearer Authorization for Cohere API', 'transform a Cohere embedding request with model, input texts, and inference parameters into a CohereEmbeddingRequestWithModel', 'transform a Cohere API response into an EmbeddingResponse with embeddings, model, and usage metadata', 'calculate token usage from input texts and response metadata including billed units for text and image tokens', 'map OpenAI encoding_format parameter to Cohere embedding_types in optional params', 'get the list of supported OpenAI parameters for Cohere embedding configuration']
```

Usage

```
{'validate_environment': 'validate environment headers and api key for Cohere embedding API requests', 'create_cohere_error': 'create a CohereError exception with status code and message for Cohere API errors', 'run_async_embedding': 'run async embedding request to Cohere API with model, input texts, and optional parameters', 'run_embedding': 'run synchronous or async embedding request to Cohere API with model and input texts', 'test_embedding': 'test the Cohere embedding handler with model, input, timeout, and logging parameters'}
```

## File: berriai_litellm/litellm/llms/cohere/embed/transformation.py

Prompts

```
['validate environment headers and api key for Cohere embedding API requests', 'create a CohereError exception with status code and message for Cohere API errors', 'run async embedding request to Cohere API with model, input texts, and optional parameters', 'run synchronous or async embedding request to Cohere API with model and input texts', 'test the Cohere embedding handler with model, input, timeout, and logging parameters', "transform an OpenAI-format embedding request into Cohere's v2 embed request format", 'transform a raw Cohere API response into a standardized OpenAI-format embedding response', 'map OpenAI embedding params like encoding_format and dimensions to Cohere equivalents', 'calculate token usage from Cohere response metadata including billed text and image tokens', 'validate and build request headers with Content-Type and Bearer Authorization for Cohere API', 'transform a Cohere embedding request with model, input texts, and inference parameters into a CohereEmbeddingRequestWithModel', 'transform a Cohere API response into an EmbeddingResponse with embeddings, model, and usage metadata', 'calculate token usage from input texts and response metadata including billed units for text and image tokens', 'map OpenAI encoding_format parameter to Cohere embedding_types in optional params', 'get the list of supported OpenAI parameters for Cohere embedding configuration']
```

Usage

```
{'transform_CohereEmbeddingRequest': "transform an OpenAI-format embedding request into Cohere's v2 embed request format", 'transform_CohereEmbeddingResponse': 'transform a raw Cohere API response into a standardized OpenAI-format embedding response', 'map_openai_params_CohereEmbeddingConfig': 'map OpenAI embedding params like encoding_format and dimensions to Cohere equivalents', 'calculate_usage_CohereEmbeddingConfig': 'calculate token usage from Cohere response metadata including billed text and image tokens', 'validate_environment_CohereEmbeddingConfig': 'validate and build request headers with Content-Type and Bearer Authorization for Cohere API'}
```

## File: berriai_litellm/litellm/llms/cohere/embed/v1_transformation.py

Prompts

```
['validate environment headers and api key for Cohere embedding API requests', 'create a CohereError exception with status code and message for Cohere API errors', 'run async embedding request to Cohere API with model, input texts, and optional parameters', 'run synchronous or async embedding request to Cohere API with model and input texts', 'test the Cohere embedding handler with model, input, timeout, and logging parameters', "transform an OpenAI-format embedding request into Cohere's v2 embed request format", 'transform a raw Cohere API response into a standardized OpenAI-format embedding response', 'map OpenAI embedding params like encoding_format and dimensions to Cohere equivalents', 'calculate token usage from Cohere response metadata including billed text and image tokens', 'validate and build request headers with Content-Type and Bearer Authorization for Cohere API', 'transform a Cohere embedding request with model, input texts, and inference parameters into a CohereEmbeddingRequestWithModel', 'transform a Cohere API response into an EmbeddingResponse with embeddings, model, and usage metadata', 'calculate token usage from input texts and response metadata including billed units for text and image tokens', 'map OpenAI encoding_format parameter to Cohere embedding_types in optional params', 'get the list of supported OpenAI parameters for Cohere embedding configuration']
```

Usage

```
{'transform_CohereEmbeddingConfig_request': 'transform a Cohere embedding request with model, input texts, and inference parameters into a CohereEmbeddingRequestWithModel', 'transform_CohereEmbeddingConfig_response': 'transform a Cohere API response into an EmbeddingResponse with embeddings, model, and usage metadata', 'calculate_CohereEmbeddingConfig_usage': 'calculate token usage from input texts and response metadata including billed units for text and image tokens', 'map_CohereEmbeddingConfig_openai_params': 'map OpenAI encoding_format parameter to Cohere embedding_types in optional params', 'get_CohereEmbeddingConfig_supported_params': 'get the list of supported OpenAI parameters for Cohere embedding configuration'}
```

