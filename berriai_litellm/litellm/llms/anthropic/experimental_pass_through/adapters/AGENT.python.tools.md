# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/anthropic/experimental_pass_through/adapters/handler.py

Prompts

```
['run async_anthropic_messages_handler to call non-Anthropic models and get Anthropic-format responses', 'run anthropic_messages_handler to call non-Anthropic models and get Anthropic-format responses', 'build completion kwargs by translating Anthropic input params to OpenAI format with tool name mapping', 'route OpenAI thinking requests to the Responses API for reasoning content blocks', 'test anthropic_messages_handler with model, messages, and streaming parameters', 'create an AnthropicStreamWrapper to translate OpenAI streaming chunks into Anthropic /v1/messages format', 'run the anthropic_sse_wrapper to convert streaming dict chunks into Server-Sent Events format', 'run the async_anthropic_sse_wrapper to asynchronously convert streaming chunks into SSE format', 'test the _should_start_new_content_block method to detect when a new content block should begin', 'summarize the _increment_content_block_index method that advances the content block index counter', 'build a translator that converts Anthropic Messages API requests to OpenAI ChatCompletion format', "create a mapping of truncated tool names back to original names for tools exceeding OpenAI's 64-character limit", 'translate an OpenAI ModelResponse back to Anthropic Messages API response format', 'translate OpenAI streaming chunks into Anthropic SSE-compatible content block deltas', 'translate Anthropic user and assistant messages with tool calls and thinking blocks to OpenAI format']
```

Usage

```
{'run_async_anthropic_messages_handler': 'run async_anthropic_messages_handler to call non-Anthropic models and get Anthropic-format responses', 'run_anthropic_messages_handler': 'run anthropic_messages_handler to call non-Anthropic models and get Anthropic-format responses', 'build_completion_kwargs': 'build completion kwargs by translating Anthropic input params to OpenAI format with tool name mapping', 'route_openai_thinking_to_responses_api': 'route OpenAI thinking requests to the Responses API for reasoning content blocks', 'test_anthropic_messages_handler': 'test anthropic_messages_handler with model, messages, and streaming parameters'}
```

## File: berriai_litellm/litellm/llms/anthropic/experimental_pass_through/adapters/streaming_iterator.py

Prompts

```
['run async_anthropic_messages_handler to call non-Anthropic models and get Anthropic-format responses', 'run anthropic_messages_handler to call non-Anthropic models and get Anthropic-format responses', 'build completion kwargs by translating Anthropic input params to OpenAI format with tool name mapping', 'route OpenAI thinking requests to the Responses API for reasoning content blocks', 'test anthropic_messages_handler with model, messages, and streaming parameters', 'create an AnthropicStreamWrapper to translate OpenAI streaming chunks into Anthropic /v1/messages format', 'run the anthropic_sse_wrapper to convert streaming dict chunks into Server-Sent Events format', 'run the async_anthropic_sse_wrapper to asynchronously convert streaming chunks into SSE format', 'test the _should_start_new_content_block method to detect when a new content block should begin', 'summarize the _increment_content_block_index method that advances the content block index counter', 'build a translator that converts Anthropic Messages API requests to OpenAI ChatCompletion format', "create a mapping of truncated tool names back to original names for tools exceeding OpenAI's 64-character limit", 'translate an OpenAI ModelResponse back to Anthropic Messages API response format', 'translate OpenAI streaming chunks into Anthropic SSE-compatible content block deltas', 'translate Anthropic user and assistant messages with tool calls and thinking blocks to OpenAI format']
```

Usage

```
{'create_anthropic_stream_wrapper': 'create an AnthropicStreamWrapper to translate OpenAI streaming chunks into Anthropic /v1/messages format', 'run_anthropic_sse_wrapper': 'run the anthropic_sse_wrapper to convert streaming dict chunks into Server-Sent Events format', 'run_async_anthropic_sse_wrapper': 'run the async_anthropic_sse_wrapper to asynchronously convert streaming chunks into SSE format', 'test_should_start_new_content_block': 'test the _should_start_new_content_block method to detect when a new content block should begin', 'summarize_increment_content_block_index': 'summarize the _increment_content_block_index method that advances the content block index counter'}
```

## File: berriai_litellm/litellm/llms/anthropic/experimental_pass_through/adapters/transformation.py

Prompts

```
['run async_anthropic_messages_handler to call non-Anthropic models and get Anthropic-format responses', 'run anthropic_messages_handler to call non-Anthropic models and get Anthropic-format responses', 'build completion kwargs by translating Anthropic input params to OpenAI format with tool name mapping', 'route OpenAI thinking requests to the Responses API for reasoning content blocks', 'test anthropic_messages_handler with model, messages, and streaming parameters', 'create an AnthropicStreamWrapper to translate OpenAI streaming chunks into Anthropic /v1/messages format', 'run the anthropic_sse_wrapper to convert streaming dict chunks into Server-Sent Events format', 'run the async_anthropic_sse_wrapper to asynchronously convert streaming chunks into SSE format', 'test the _should_start_new_content_block method to detect when a new content block should begin', 'summarize the _increment_content_block_index method that advances the content block index counter', 'build a translator that converts Anthropic Messages API requests to OpenAI ChatCompletion format', "create a mapping of truncated tool names back to original names for tools exceeding OpenAI's 64-character limit", 'translate an OpenAI ModelResponse back to Anthropic Messages API response format', 'translate OpenAI streaming chunks into Anthropic SSE-compatible content block deltas', 'translate Anthropic user and assistant messages with tool calls and thinking blocks to OpenAI format']
```

Usage

```
{'build_translate_anthropic_to_openai': 'build a translator that converts Anthropic Messages API requests to OpenAI ChatCompletion format', 'create_tool_name_mapping': "create a mapping of truncated tool names back to original names for tools exceeding OpenAI's 64-character limit", 'translate_openai_response_to_anthropic': 'translate an OpenAI ModelResponse back to Anthropic Messages API response format', 'translate_streaming_openai_response_to_anthropic': 'translate OpenAI streaming chunks into Anthropic SSE-compatible content block deltas', 'translate_anthropic_messages_to_openai': 'translate Anthropic user and assistant messages with tool calls and thinking blocks to OpenAI format'}
```

