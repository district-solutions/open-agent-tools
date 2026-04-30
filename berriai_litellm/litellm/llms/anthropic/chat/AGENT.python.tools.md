# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/anthropic/chat/handler.py

Prompts

```
['create an Anthropic chat completion call via the /v1/messages endpoint with streaming support', 'build a streaming iterator that parses Anthropic SSE chunks into OpenAI-compatible ModelResponseStream objects', 'test the async HTTP call to Anthropic API with streaming response and error handling', 'refactor the chunk_parser method to translate Anthropic streaming events into OpenAI-format streaming chunks', 'review the synchronous HTTP call function for Anthropic API with SSE streaming and JSON mode support', 'transform OpenAI-format chat request to Anthropic API format with tools and system messages', 'transform Anthropic API response to OpenAI-compatible ModelResponse with usage and tool calls', 'map OpenAI response_format JSON schema to Anthropic output_format with filtered constraints', 'map OpenAI web_search_options to Anthropic hosted web search tool with user location', 'convert Anthropic tool_use content block to OpenAI ChatCompletionToolCallChunk format']
```

Usage

```
{'create_anthropic_chat_completion': 'create an Anthropic chat completion call via the /v1/messages endpoint with streaming support', 'build_anthropic_streaming_iterator': 'build a streaming iterator that parses Anthropic SSE chunks into OpenAI-compatible ModelResponseStream objects', 'test_make_async_call': 'test the async HTTP call to Anthropic API with streaming response and error handling', 'refactor_chunk_parser': 'refactor the chunk_parser method to translate Anthropic streaming events into OpenAI-format streaming chunks', 'review_make_sync_call': 'review the synchronous HTTP call function for Anthropic API with SSE streaming and JSON mode support'}
```

## File: berriai_litellm/litellm/llms/anthropic/chat/transformation.py

Prompts

```
['create an Anthropic chat completion call via the /v1/messages endpoint with streaming support', 'build a streaming iterator that parses Anthropic SSE chunks into OpenAI-compatible ModelResponseStream objects', 'test the async HTTP call to Anthropic API with streaming response and error handling', 'refactor the chunk_parser method to translate Anthropic streaming events into OpenAI-format streaming chunks', 'review the synchronous HTTP call function for Anthropic API with SSE streaming and JSON mode support', 'transform OpenAI-format chat request to Anthropic API format with tools and system messages', 'transform Anthropic API response to OpenAI-compatible ModelResponse with usage and tool calls', 'map OpenAI response_format JSON schema to Anthropic output_format with filtered constraints', 'map OpenAI web_search_options to Anthropic hosted web search tool with user location', 'convert Anthropic tool_use content block to OpenAI ChatCompletionToolCallChunk format']
```

Usage

```
{'transform_request_anthropic_chat': 'transform OpenAI-format chat request to Anthropic API format with tools and system messages', 'transform_response_anthropic': 'transform Anthropic API response to OpenAI-compatible ModelResponse with usage and tool calls', 'map_response_format_to_anthropic_output_format': 'map OpenAI response_format JSON schema to Anthropic output_format with filtered constraints', 'map_web_search_tool_openai_to_anthropic': 'map OpenAI web_search_options to Anthropic hosted web search tool with user location', 'convert_tool_use_to_openai_format': 'convert Anthropic tool_use content block to OpenAI ChatCompletionToolCallChunk format'}
```

