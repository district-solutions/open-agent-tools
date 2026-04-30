# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/anthropic/api_router.py

Prompts

```
['create messages by posting to the /v1/messages endpoint with an AnthropicMessagesRequest', 'count tokens by posting to the /v1/messages/count_tokens endpoint with an AnthropicCountTokensRequest', 'attach the anthropic API router to a FastAPI application instance', 'translate an OpenAI ErrorResponse into an Anthropic-compatible JSON error response', 'create streaming messages via SSE response from the /v1/messages endpoint', 'create an Anthropic Messages API request model with model, messages, max_tokens, and optional streaming parameters', 'create an Anthropic Messages API response model with content blocks, stop reason, and token usage', 'create an Anthropic tool definition with name, description, and JSON input schema', 'create an Anthropic content block with type, text, or tool use input fields', 'create an Anthropic count tokens request model with model, messages, and optional tools', 'create an Anthropic Messages API handler that converts requests to OpenAI format and serves completions', 'convert an Anthropic messages request into an OpenAI ChatCompletionRequest for internal processing', 'convert an OpenAI chat completion stream into an Anthropic-compatible streaming SSE response', 'convert an Anthropic image source (base64 or URL) into an OpenAI-compatible data URI', 'count tokens in an Anthropic message request by rendering it through the OpenAI engine']
```

Usage

```
{'create_messages': 'create messages by posting to the /v1/messages endpoint with an AnthropicMessagesRequest', 'count_tokens': 'count tokens by posting to the /v1/messages/count_tokens endpoint with an AnthropicCountTokensRequest', 'attach_router': 'attach the anthropic API router to a FastAPI application instance', 'translate_error_response': 'translate an OpenAI ErrorResponse into an Anthropic-compatible JSON error response', 'create_streaming_messages': 'create streaming messages via SSE response from the /v1/messages endpoint'}
```

## File: vllm-project_vllm/vllm/entrypoints/anthropic/protocol.py

Prompts

```
['create messages by posting to the /v1/messages endpoint with an AnthropicMessagesRequest', 'count tokens by posting to the /v1/messages/count_tokens endpoint with an AnthropicCountTokensRequest', 'attach the anthropic API router to a FastAPI application instance', 'translate an OpenAI ErrorResponse into an Anthropic-compatible JSON error response', 'create streaming messages via SSE response from the /v1/messages endpoint', 'create an Anthropic Messages API request model with model, messages, max_tokens, and optional streaming parameters', 'create an Anthropic Messages API response model with content blocks, stop reason, and token usage', 'create an Anthropic tool definition with name, description, and JSON input schema', 'create an Anthropic content block with type, text, or tool use input fields', 'create an Anthropic count tokens request model with model, messages, and optional tools', 'create an Anthropic Messages API handler that converts requests to OpenAI format and serves completions', 'convert an Anthropic messages request into an OpenAI ChatCompletionRequest for internal processing', 'convert an OpenAI chat completion stream into an Anthropic-compatible streaming SSE response', 'convert an Anthropic image source (base64 or URL) into an OpenAI-compatible data URI', 'count tokens in an Anthropic message request by rendering it through the OpenAI engine']
```

Usage

```
{'create_anthropic_messages_request': 'create an Anthropic Messages API request model with model, messages, max_tokens, and optional streaming parameters', 'create_anthropic_messages_response': 'create an Anthropic Messages API response model with content blocks, stop reason, and token usage', 'create_anthropic_tool': 'create an Anthropic tool definition with name, description, and JSON input schema', 'create_anthropic_content_block': 'create an Anthropic content block with type, text, or tool use input fields', 'create_anthropic_count_tokens_request': 'create an Anthropic count tokens request model with model, messages, and optional tools'}
```

## File: vllm-project_vllm/vllm/entrypoints/anthropic/serving.py

Prompts

```
['create messages by posting to the /v1/messages endpoint with an AnthropicMessagesRequest', 'count tokens by posting to the /v1/messages/count_tokens endpoint with an AnthropicCountTokensRequest', 'attach the anthropic API router to a FastAPI application instance', 'translate an OpenAI ErrorResponse into an Anthropic-compatible JSON error response', 'create streaming messages via SSE response from the /v1/messages endpoint', 'create an Anthropic Messages API request model with model, messages, max_tokens, and optional streaming parameters', 'create an Anthropic Messages API response model with content blocks, stop reason, and token usage', 'create an Anthropic tool definition with name, description, and JSON input schema', 'create an Anthropic content block with type, text, or tool use input fields', 'create an Anthropic count tokens request model with model, messages, and optional tools', 'create an Anthropic Messages API handler that converts requests to OpenAI format and serves completions', 'convert an Anthropic messages request into an OpenAI ChatCompletionRequest for internal processing', 'convert an OpenAI chat completion stream into an Anthropic-compatible streaming SSE response', 'convert an Anthropic image source (base64 or URL) into an OpenAI-compatible data URI', 'count tokens in an Anthropic message request by rendering it through the OpenAI engine']
```

Usage

```
{'create_anthropic_messages': 'create an Anthropic Messages API handler that converts requests to OpenAI format and serves completions', 'convert_anthropic_to_openai_request': 'convert an Anthropic messages request into an OpenAI ChatCompletionRequest for internal processing', 'create_anthropic_stream_converter': 'convert an OpenAI chat completion stream into an Anthropic-compatible streaming SSE response', 'convert_anthropic_image_source': 'convert an Anthropic image source (base64 or URL) into an OpenAI-compatible data URI', 'count_anthropic_tokens': 'count tokens in an Anthropic message request by rendering it through the OpenAI engine'}
```

