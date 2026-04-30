# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/interactions/litellm_responses_transformation/handler.py

Prompts

```
['build an Interactions API handler that bridges to litellm.responses with sync or async support', 'test the async Interactions API handler that calls litellm.aresponses and returns transformed responses', 'refactor the request transformer that converts Interactions API requests to litellm.responses format', 'review the response transformer that converts litellm.responses output to Interactions API response format', 'create a streaming iterator wrapper that adapts BaseResponsesAPIStreamingIterator to Interactions API streaming responses', 'transform an Interactions API request to a Responses API request with model, input, and generation config', 'transform a Responses API response to an Interactions API response with extracted text outputs and usage', 'transform Interactions API input (string or Turn[]) to Responses API input format', 'transform Interactions API content array items into Responses API text-formatted content dicts', 'build a Responses API request from Interactions API params including temperature, top_p, and max_output_tokens']
```

Usage

```
{'build_interactions_api_handler': 'build an Interactions API handler that bridges to litellm.responses with sync or async support', 'test_async_interactions_api_handler': 'test the async Interactions API handler that calls litellm.aresponses and returns transformed responses', 'refactor_transform_interactions_request': 'refactor the request transformer that converts Interactions API requests to litellm.responses format', 'review_transform_responses_response': 'review the response transformer that converts litellm.responses output to Interactions API response format', 'create_interactions_streaming_iterator': 'create a streaming iterator wrapper that adapts BaseResponsesAPIStreamingIterator to Interactions API streaming responses'}
```

## File: berriai_litellm/litellm/interactions/litellm_responses_transformation/transformation.py

Prompts

```
['build an Interactions API handler that bridges to litellm.responses with sync or async support', 'test the async Interactions API handler that calls litellm.aresponses and returns transformed responses', 'refactor the request transformer that converts Interactions API requests to litellm.responses format', 'review the response transformer that converts litellm.responses output to Interactions API response format', 'create a streaming iterator wrapper that adapts BaseResponsesAPIStreamingIterator to Interactions API streaming responses', 'transform an Interactions API request to a Responses API request with model, input, and generation config', 'transform a Responses API response to an Interactions API response with extracted text outputs and usage', 'transform Interactions API input (string or Turn[]) to Responses API input format', 'transform Interactions API content array items into Responses API text-formatted content dicts', 'build a Responses API request from Interactions API params including temperature, top_p, and max_output_tokens']
```

Usage

```
{'transform_interactions_request_to_responses_request': 'transform an Interactions API request to a Responses API request with model, input, and generation config', 'transform_responses_response_to_interactions_response': 'transform a Responses API response to an Interactions API response with extracted text outputs and usage', 'transform_interactions_input_to_responses_input': 'transform Interactions API input (string or Turn[]) to Responses API input format', 'transform_content_array': 'transform Interactions API content array items into Responses API text-formatted content dicts', 'build_responses_request_with_generation_config': 'build a Responses API request from Interactions API params including temperature, top_p, and max_output_tokens'}
```

