# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/anthropic/experimental_pass_through/responses_adapters/handler.py

Prompts

```
['build a kwargs dict for litellm.responses() by translating Anthropic messages request parameters', 'async call litellm.aresponses() with Anthropic-style parameters and return translated Anthropic response', 'call litellm.responses() with Anthropic-style parameters and return translated Anthropic response or stream', 'translate an AnthropicMessagesRequest into OpenAI Responses API kwargs', 'translate an OpenAI ResponsesAPIResponse back into AnthropicMessagesResponse format', 'translate a list of Anthropic user and assistant messages to OpenAI Responses API input items', 'translate Anthropic tool definitions to OpenAI Responses API function tool format', 'translate Anthropic tool_choice to OpenAI Responses API tool_choice format']
```

Usage

```
{'build_responses_kwargs': 'build a kwargs dict for litellm.responses() by translating Anthropic messages request parameters', 'async_anthropic_messages_handler': 'async call litellm.aresponses() with Anthropic-style parameters and return translated Anthropic response', 'anthropic_messages_handler': 'call litellm.responses() with Anthropic-style parameters and return translated Anthropic response or stream', 'translate_request': 'translate an AnthropicMessagesRequest into OpenAI Responses API kwargs', 'translate_response': 'translate an OpenAI ResponsesAPIResponse back into AnthropicMessagesResponse format'}
```

## File: berriai_litellm/litellm/llms/anthropic/experimental_pass_through/responses_adapters/transformation.py

Prompts

```
['build a kwargs dict for litellm.responses() by translating Anthropic messages request parameters', 'async call litellm.aresponses() with Anthropic-style parameters and return translated Anthropic response', 'call litellm.responses() with Anthropic-style parameters and return translated Anthropic response or stream', 'translate an AnthropicMessagesRequest into OpenAI Responses API kwargs', 'translate an OpenAI ResponsesAPIResponse back into AnthropicMessagesResponse format', 'translate a list of Anthropic user and assistant messages to OpenAI Responses API input items', 'translate Anthropic tool definitions to OpenAI Responses API function tool format', 'translate Anthropic tool_choice to OpenAI Responses API tool_choice format']
```

Usage

```
{'translate_messages_to_responses_input': 'translate a list of Anthropic user and assistant messages to OpenAI Responses API input items', 'translate_tools_to_responses_api': 'translate Anthropic tool definitions to OpenAI Responses API function tool format', 'translate_tool_choice_to_responses_api': 'translate Anthropic tool_choice to OpenAI Responses API tool_choice format', 'translate_request': 'translate a full Anthropic /v1/messages request dict to OpenAI Responses API kwargs', 'translate_response': 'translate an OpenAI Responses API response back to Anthropic /v1/messages response format'}
```

