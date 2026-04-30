# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/completion_extras/litellm_responses_transformation/handler.py

Prompts

```
['create a handler that transforms OpenAI /chat/completions requests into litellm.responses API calls', 'validate input kwargs for a chat completion request including model, messages, and provider parameters', 'run a synchronous chat completion that bridges /chat/completions to the Responses API with streaming support', 'run an asynchronous chat completion that bridges /chat/completions to the Responses API with streaming support', 'apply provider-specific post-stream processing to a CustomStreamWrapper after iteration completes', 'transform chat completion messages into a litellm responses API request with instructions and optional params', 'convert a responses API response into chat completion choices with reasoning and tool calls', 'translate a responses API streaming chunk to OpenAI chat completion streaming format', 'convert chat completion message content strings and lists to responses API input format', 'map reasoning effort string values to responses API reasoning configuration with optional auto-summary']
```

Usage

```
{'create_responses_to_completion_bridge': 'create a handler that transforms OpenAI /chat/completions requests into litellm.responses API calls', 'validate_chat_completion_kwargs': 'validate input kwargs for a chat completion request including model, messages, and provider parameters', 'run_sync_completion': 'run a synchronous chat completion that bridges /chat/completions to the Responses API with streaming support', 'run_async_completion': 'run an asynchronous chat completion that bridges /chat/completions to the Responses API with streaming support', 'apply_post_stream_processing': 'apply provider-specific post-stream processing to a CustomStreamWrapper after iteration completes'}
```

## File: berriai_litellm/litellm/completion_extras/litellm_responses_transformation/transformation.py

Prompts

```
['create a handler that transforms OpenAI /chat/completions requests into litellm.responses API calls', 'validate input kwargs for a chat completion request including model, messages, and provider parameters', 'run a synchronous chat completion that bridges /chat/completions to the Responses API with streaming support', 'run an asynchronous chat completion that bridges /chat/completions to the Responses API with streaming support', 'apply provider-specific post-stream processing to a CustomStreamWrapper after iteration completes', 'transform chat completion messages into a litellm responses API request with instructions and optional params', 'convert a responses API response into chat completion choices with reasoning and tool calls', 'translate a responses API streaming chunk to OpenAI chat completion streaming format', 'convert chat completion message content strings and lists to responses API input format', 'map reasoning effort string values to responses API reasoning configuration with optional auto-summary']
```

Usage

```
{'transform_chat_completion_to_responses_request': 'transform chat completion messages into a litellm responses API request with instructions and optional params', 'convert_responses_api_response_to_choices': 'convert a responses API response into chat completion choices with reasoning and tool calls', 'translate_responses_streaming_chunk': 'translate a responses API streaming chunk to OpenAI chat completion streaming format', 'convert_chat_completion_content_to_responses_format': 'convert chat completion message content strings and lists to responses API input format', 'map_reasoning_effort_to_responses_reasoning': 'map reasoning effort string values to responses API reasoning configuration with optional auto-summary'}
```

