# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/bedrock/messages/invoke_transformations/anthropic_claude3_transformation.py

Prompts

```
['transform an Anthropic messages request into a Bedrock-compatible format by removing unsupported fields and auto-injecting beta headers', 'get an async streaming response iterator that converts Bedrock invoke events to SSE format for Anthropic clients', 'wrap a Bedrock completion stream to produce SSE-formatted chunks with consistent usage data across message_delta events', 'promote cache usage fields from message_stop onto message_delta to ensure consistent logging and cost calculation', 'parse Bedrock chunk data into Anthropic /messages format by converting camelCase invocation metrics to snake_case usage keys']
```

Usage

```
{'transform_anthropic_messages_request': 'transform an Anthropic messages request into a Bedrock-compatible format by removing unsupported fields and auto-injecting beta headers', 'get_async_streaming_response_iterator': 'get an async streaming response iterator that converts Bedrock invoke events to SSE format for Anthropic clients', 'bedrock_sse_wrapper': 'wrap a Bedrock completion stream to produce SSE-formatted chunks with consistent usage data across message_delta events', '_promote_message_stop_usage': 'promote cache usage fields from message_stop onto message_delta to ensure consistent logging and cost calculation', '_chunk_parser': 'parse Bedrock chunk data into Anthropic /messages format by converting camelCase invocation metrics to snake_case usage keys'}
```

