# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/openai_like/chat/handler.py

Prompts

```
['run an async OpenAI-like chat completion with streaming support via make_call', 'run a synchronous OpenAI-like chat completion with streaming support via make_sync_call', 'create an OpenAILikeChatHandler instance to dispatch chat completions to OpenAI-compatible APIs', 'test the async streaming chat completion function with a custom streaming decoder', 'review the synchronous completion method that routes to async or sync handlers based on acompletion flag', 'build an OpenAILikeChatConfig instance to transform OpenAI-compatible chat completion responses', 'transform an httpx chat completion response into a ModelResponse with sanitized usage and json mode handling', 'sanitize a response usage dict by replacing None token values with 0 for OpenAI compatibility', 'convert an assistant message with tool_calls into a plain content message when json_mode is enabled', 'map non-default OpenAI params to provider-compatible params, replacing max_completion_tokens with max_tokens']
```

Usage

```
{'run_async_chat_completion': 'run an async OpenAI-like chat completion with streaming support via make_call', 'run_sync_chat_completion': 'run a synchronous OpenAI-like chat completion with streaming support via make_sync_call', 'create_chat_handler': 'create an OpenAILikeChatHandler instance to dispatch chat completions to OpenAI-compatible APIs', 'test_acompletion_stream_function': 'test the async streaming chat completion function with a custom streaming decoder', 'review_completion_method': 'review the synchronous completion method that routes to async or sync handlers based on acompletion flag'}
```

## File: berriai_litellm/litellm/llms/openai_like/chat/transformation.py

Prompts

```
['run an async OpenAI-like chat completion with streaming support via make_call', 'run a synchronous OpenAI-like chat completion with streaming support via make_sync_call', 'create an OpenAILikeChatHandler instance to dispatch chat completions to OpenAI-compatible APIs', 'test the async streaming chat completion function with a custom streaming decoder', 'review the synchronous completion method that routes to async or sync handlers based on acompletion flag', 'build an OpenAILikeChatConfig instance to transform OpenAI-compatible chat completion responses', 'transform an httpx chat completion response into a ModelResponse with sanitized usage and json mode handling', 'sanitize a response usage dict by replacing None token values with 0 for OpenAI compatibility', 'convert an assistant message with tool_calls into a plain content message when json_mode is enabled', 'map non-default OpenAI params to provider-compatible params, replacing max_completion_tokens with max_tokens']
```

Usage

```
{'build_openai_like_chat_config': 'build an OpenAILikeChatConfig instance to transform OpenAI-compatible chat completion responses', 'transform_response_chat': 'transform an httpx chat completion response into a ModelResponse with sanitized usage and json mode handling', 'sanitize_usage_object': 'sanitize a response usage dict by replacing None token values with 0 for OpenAI compatibility', 'convert_tool_response_to_message': 'convert an assistant message with tool_calls into a plain content message when json_mode is enabled', 'map_openai_params': 'map non-default OpenAI params to provider-compatible params, replacing max_completion_tokens with max_tokens'}
```

