# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/replicate/chat/handler.py

Prompts

```
['create a Replicate chat completion call with messages, model, and streaming support via litellm', 'run an async Replicate chat completion with polling and non-streaming response handling', 'summarize the synchronous prediction streaming handler that polls Replicate for incremental output chunks', 'review the async prediction streaming handler that yields incremental output from Replicate predictions', 'test the ReplicateError handling for failed predictions and invalid response parsing', 'build a Replicate API request by transforming OpenAI-format messages and parameters into Replicate-compatible input', 'transform a Replicate prediction response into a standardized ModelResponse with usage statistics', 'map OpenAI chat completion parameters to Replicate-specific parameters like max_new_tokens and stop_sequences', 'get the complete Replicate API URL for a model prediction endpoint including version ID resolution', 'validate and build authenticated request headers with Token authorization and Content-Type for Replicate API']
```

Usage

```
{'create_replicate_chat_completion': 'create a Replicate chat completion call with messages, model, and streaming support via litellm', 'run_async_replicate_completion': 'run an async Replicate chat completion with polling and non-streaming response handling', 'summarize_prediction_streaming': 'summarize the synchronous prediction streaming handler that polls Replicate for incremental output chunks', 'review_async_prediction_streaming': 'review the async prediction streaming handler that yields incremental output from Replicate predictions', 'test_replicate_error_handling': 'test the ReplicateError handling for failed predictions and invalid response parsing'}
```

## File: berriai_litellm/litellm/llms/replicate/chat/transformation.py

Prompts

```
['create a Replicate chat completion call with messages, model, and streaming support via litellm', 'run an async Replicate chat completion with polling and non-streaming response handling', 'summarize the synchronous prediction streaming handler that polls Replicate for incremental output chunks', 'review the async prediction streaming handler that yields incremental output from Replicate predictions', 'test the ReplicateError handling for failed predictions and invalid response parsing', 'build a Replicate API request by transforming OpenAI-format messages and parameters into Replicate-compatible input', 'transform a Replicate prediction response into a standardized ModelResponse with usage statistics', 'map OpenAI chat completion parameters to Replicate-specific parameters like max_new_tokens and stop_sequences', 'get the complete Replicate API URL for a model prediction endpoint including version ID resolution', 'validate and build authenticated request headers with Token authorization and Content-Type for Replicate API']
```

Usage

```
{'build_replicate_request': 'build a Replicate API request by transforming OpenAI-format messages and parameters into Replicate-compatible input', 'transform_replicate_response': 'transform a Replicate prediction response into a standardized ModelResponse with usage statistics', 'map_openai_params': 'map OpenAI chat completion parameters to Replicate-specific parameters like max_new_tokens and stop_sequences', 'get_complete_url': 'get the complete Replicate API URL for a model prediction endpoint including version ID resolution', 'validate_environment': 'validate and build authenticated request headers with Token authorization and Content-Type for Replicate API'}
```

