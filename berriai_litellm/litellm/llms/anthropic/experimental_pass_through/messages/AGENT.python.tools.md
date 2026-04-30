# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/anthropic/experimental_pass_through/messages/handler.py

Prompts

```
['run an async Anthropic /messages API call with streaming and non-streaming support', 'build an Anthropic messages handler that routes to the correct backend API', 'test the metadata validator that filters only allowed Anthropic API metadata fields', 'run pre-request hooks to let custom loggers modify request parameters before the API call', 'run a web search short-circuit that bypasses the backend LLM for web-search-only requests', 'test the BaseAnthropicMessagesStreamingIterator class for streaming response handling and logging', 'create an async SSE wrapper that converts streaming chunks to SSE format and handles logging', 'build a streaming response iterator from an httpx response using the PassThroughStreamingHandler', 'test the async_sse_wrapper method that wraps completion streams and yields encoded SSE chunks', 'review the _convert_chunk_to_sse_format method that converts dict chunks to Server-Sent Events format', 'transform an Anthropic /v1/messages request with model, messages, and optional params into a validated request dict', 'transform an httpx raw response into an AnthropicMessagesResponse object', 'get an async streaming response iterator for Anthropic SSE responses', 'validate and build headers with auth, api-version, content-type, and beta headers for an Anthropic messages call', 'build the complete Anthropic /v1/messages API URL from an optional api_base', 'filter a parameters dictionary to only include valid AnthropicMessagesRequestOptionalParams keys', 'test the mock_response function returns a valid AnthropicMessagesResponse with default text', 'test the mock_response function raises InternalServerError when mock_response equals litellm.InternalServerError', 'test the mock_response function raises RateLimitError when mock_response equals litellm.RateLimitError', 'test the mock_response function raises ContextWindowExceededError when mock_response equals litellm.ContextWindowExceededError']
```

Usage

```
{'run_anthropic_messages': 'run an async Anthropic /messages API call with streaming and non-streaming support', 'build_anthropic_messages_handler': 'build an Anthropic messages handler that routes to the correct backend API', 'test_validate_anthropic_api_metadata': 'test the metadata validator that filters only allowed Anthropic API metadata fields', 'run_execute_pre_request_hooks': 'run pre-request hooks to let custom loggers modify request parameters before the API call', 'run_websearch_short_circuit': 'run a web search short-circuit that bypasses the backend LLM for web-search-only requests'}
```

## File: berriai_litellm/litellm/llms/anthropic/experimental_pass_through/messages/streaming_iterator.py

Prompts

```
['run an async Anthropic /messages API call with streaming and non-streaming support', 'build an Anthropic messages handler that routes to the correct backend API', 'test the metadata validator that filters only allowed Anthropic API metadata fields', 'run pre-request hooks to let custom loggers modify request parameters before the API call', 'run a web search short-circuit that bypasses the backend LLM for web-search-only requests', 'test the BaseAnthropicMessagesStreamingIterator class for streaming response handling and logging', 'create an async SSE wrapper that converts streaming chunks to SSE format and handles logging', 'build a streaming response iterator from an httpx response using the PassThroughStreamingHandler', 'test the async_sse_wrapper method that wraps completion streams and yields encoded SSE chunks', 'review the _convert_chunk_to_sse_format method that converts dict chunks to Server-Sent Events format', 'transform an Anthropic /v1/messages request with model, messages, and optional params into a validated request dict', 'transform an httpx raw response into an AnthropicMessagesResponse object', 'get an async streaming response iterator for Anthropic SSE responses', 'validate and build headers with auth, api-version, content-type, and beta headers for an Anthropic messages call', 'build the complete Anthropic /v1/messages API URL from an optional api_base', 'filter a parameters dictionary to only include valid AnthropicMessagesRequestOptionalParams keys', 'test the mock_response function returns a valid AnthropicMessagesResponse with default text', 'test the mock_response function raises InternalServerError when mock_response equals litellm.InternalServerError', 'test the mock_response function raises RateLimitError when mock_response equals litellm.RateLimitError', 'test the mock_response function raises ContextWindowExceededError when mock_response equals litellm.ContextWindowExceededError']
```

Usage

```
{'test_BaseAnthropicMessagesStreamingIterator': 'test the BaseAnthropicMessagesStreamingIterator class for streaming response handling and logging', 'create_async_sse_wrapper': 'create an async SSE wrapper that converts streaming chunks to SSE format and handles logging', 'build_get_async_streaming_response_iterator': 'build a streaming response iterator from an httpx response using the PassThroughStreamingHandler', 'test_async_sse_wrapper': 'test the async_sse_wrapper method that wraps completion streams and yields encoded SSE chunks', 'review_convert_chunk_to_sse_format': 'review the _convert_chunk_to_sse_format method that converts dict chunks to Server-Sent Events format'}
```

## File: berriai_litellm/litellm/llms/anthropic/experimental_pass_through/messages/transformation.py

Prompts

```
['run an async Anthropic /messages API call with streaming and non-streaming support', 'build an Anthropic messages handler that routes to the correct backend API', 'test the metadata validator that filters only allowed Anthropic API metadata fields', 'run pre-request hooks to let custom loggers modify request parameters before the API call', 'run a web search short-circuit that bypasses the backend LLM for web-search-only requests', 'test the BaseAnthropicMessagesStreamingIterator class for streaming response handling and logging', 'create an async SSE wrapper that converts streaming chunks to SSE format and handles logging', 'build a streaming response iterator from an httpx response using the PassThroughStreamingHandler', 'test the async_sse_wrapper method that wraps completion streams and yields encoded SSE chunks', 'review the _convert_chunk_to_sse_format method that converts dict chunks to Server-Sent Events format', 'transform an Anthropic /v1/messages request with model, messages, and optional params into a validated request dict', 'transform an httpx raw response into an AnthropicMessagesResponse object', 'get an async streaming response iterator for Anthropic SSE responses', 'validate and build headers with auth, api-version, content-type, and beta headers for an Anthropic messages call', 'build the complete Anthropic /v1/messages API URL from an optional api_base', 'filter a parameters dictionary to only include valid AnthropicMessagesRequestOptionalParams keys', 'test the mock_response function returns a valid AnthropicMessagesResponse with default text', 'test the mock_response function raises InternalServerError when mock_response equals litellm.InternalServerError', 'test the mock_response function raises RateLimitError when mock_response equals litellm.RateLimitError', 'test the mock_response function raises ContextWindowExceededError when mock_response equals litellm.ContextWindowExceededError']
```

Usage

```
{'transform_anthropic_messages_request': 'transform an Anthropic /v1/messages request with model, messages, and optional params into a validated request dict', 'transform_anthropic_messages_response': 'transform an httpx raw response into an AnthropicMessagesResponse object', 'get_async_streaming_response_iterator': 'get an async streaming response iterator for Anthropic SSE responses', 'validate_anthropic_messages_environment': 'validate and build headers with auth, api-version, content-type, and beta headers for an Anthropic messages call', 'get_complete_url': 'build the complete Anthropic /v1/messages API URL from an optional api_base'}
```

## File: berriai_litellm/litellm/llms/anthropic/experimental_pass_through/messages/utils.py

Prompts

```
['run an async Anthropic /messages API call with streaming and non-streaming support', 'build an Anthropic messages handler that routes to the correct backend API', 'test the metadata validator that filters only allowed Anthropic API metadata fields', 'run pre-request hooks to let custom loggers modify request parameters before the API call', 'run a web search short-circuit that bypasses the backend LLM for web-search-only requests', 'test the BaseAnthropicMessagesStreamingIterator class for streaming response handling and logging', 'create an async SSE wrapper that converts streaming chunks to SSE format and handles logging', 'build a streaming response iterator from an httpx response using the PassThroughStreamingHandler', 'test the async_sse_wrapper method that wraps completion streams and yields encoded SSE chunks', 'review the _convert_chunk_to_sse_format method that converts dict chunks to Server-Sent Events format', 'transform an Anthropic /v1/messages request with model, messages, and optional params into a validated request dict', 'transform an httpx raw response into an AnthropicMessagesResponse object', 'get an async streaming response iterator for Anthropic SSE responses', 'validate and build headers with auth, api-version, content-type, and beta headers for an Anthropic messages call', 'build the complete Anthropic /v1/messages API URL from an optional api_base', 'filter a parameters dictionary to only include valid AnthropicMessagesRequestOptionalParams keys', 'test the mock_response function returns a valid AnthropicMessagesResponse with default text', 'test the mock_response function raises InternalServerError when mock_response equals litellm.InternalServerError', 'test the mock_response function raises RateLimitError when mock_response equals litellm.RateLimitError', 'test the mock_response function raises ContextWindowExceededError when mock_response equals litellm.ContextWindowExceededError']
```

Usage

```
{'filter_anthropic_params': 'filter a parameters dictionary to only include valid AnthropicMessagesRequestOptionalParams keys', 'test_mock_response_success': 'test the mock_response function returns a valid AnthropicMessagesResponse with default text', 'test_mock_response_error': 'test the mock_response function raises InternalServerError when mock_response equals litellm.InternalServerError', 'test_mock_response_rate_limit': 'test the mock_response function raises RateLimitError when mock_response equals litellm.RateLimitError', 'test_mock_response_context_error': 'test the mock_response function raises ContextWindowExceededError when mock_response equals litellm.ContextWindowExceededError'}
```

