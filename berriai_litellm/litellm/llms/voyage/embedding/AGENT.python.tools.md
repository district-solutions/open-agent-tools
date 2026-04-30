# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/voyage/embedding/transformation.py

Prompts

```
['build a VoyageEmbeddingConfig instance to handle Voyage AI embedding API transformations', 'test the map_openai_params method to convert OpenAI encoding_format and dimensions to Voyage output_dimension', 'run validate_environment to retrieve the Voyage API key from environment secrets and build Authorization header', 'create a transformed embedding request dict with input, model, and optional params for the Voyage API', 'review the transform_embedding_response method that parses Voyage API JSON into an EmbeddingResponse with usage', 'build a VoyageContextualEmbeddingConfig instance to transform request and response for the Voyage contextualized embeddings API', 'test the transform_embedding_response method to parse raw Voyage API response into an EmbeddingResponse object', 'review the map_openai_params method to map OpenAI encoding_format and dimensions to Voyage output_dimension param', "summarize the is_contextualized_embeddings static method that checks if a model name contains 'context'"]
```

Usage

```
{'build_voyage_embedding_config': 'build a VoyageEmbeddingConfig instance to handle Voyage AI embedding API transformations', 'test_map_openai_params': 'test the map_openai_params method to convert OpenAI encoding_format and dimensions to Voyage output_dimension', 'run_validate_environment': 'run validate_environment to retrieve the Voyage API key from environment secrets and build Authorization header', 'create_transform_embedding_request': 'create a transformed embedding request dict with input, model, and optional params for the Voyage API', 'review_transform_embedding_response': 'review the transform_embedding_response method that parses Voyage API JSON into an EmbeddingResponse with usage'}
```

## File: berriai_litellm/litellm/llms/voyage/embedding/transformation_contextual.py

Prompts

```
['build a VoyageEmbeddingConfig instance to handle Voyage AI embedding API transformations', 'test the map_openai_params method to convert OpenAI encoding_format and dimensions to Voyage output_dimension', 'run validate_environment to retrieve the Voyage API key from environment secrets and build Authorization header', 'create a transformed embedding request dict with input, model, and optional params for the Voyage API', 'review the transform_embedding_response method that parses Voyage API JSON into an EmbeddingResponse with usage', 'build a VoyageContextualEmbeddingConfig instance to transform request and response for the Voyage contextualized embeddings API', 'test the transform_embedding_response method to parse raw Voyage API response into an EmbeddingResponse object', 'review the map_openai_params method to map OpenAI encoding_format and dimensions to Voyage output_dimension param', "summarize the is_contextualized_embeddings static method that checks if a model name contains 'context'"]
```

Usage

```
{'build_voyage_contextual_embedding_config': 'build a VoyageContextualEmbeddingConfig instance to transform request and response for the Voyage contextualized embeddings API', 'create_transform_embedding_request': 'create a transformed embedding request dict with inputs, model name, and optional params for the Voyage API', 'test_transform_embedding_response': 'test the transform_embedding_response method to parse raw Voyage API response into an EmbeddingResponse object', 'review_map_openai_params': 'review the map_openai_params method to map OpenAI encoding_format and dimensions to Voyage output_dimension param', 'summarize_is_contextualized_embeddings': "summarize the is_contextualized_embeddings static method that checks if a model name contains 'context'"}
```

