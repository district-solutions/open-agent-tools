# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/moonshot/chat/transformation.py

Prompts

```
['build a MoonshotChatConfig instance to translate OpenAI chat completions to Moonshot AI API format', 'transform chat messages by flattening content lists to strings for Moonshot text-only models', 'get the complete Moonshot AI chat completions endpoint URL with default base', 'get the list of supported OpenAI parameters excluding Moonshot-specific limitations', 'map OpenAI parameters to Moonshot parameters with temperature clamping for n>1', 'fill missing reasoning_content on assistant messages with tool_calls for Moonshot reasoning models', 'transform the full request including tool_choice handling and reasoning_content injection']
```

Usage

```
{'build_moonshot_chat_config': 'build a MoonshotChatConfig instance to translate OpenAI chat completions to Moonshot AI API format', 'transform_messages_content': 'transform chat messages by flattening content lists to strings for Moonshot text-only models', 'get_complete_url_moonshot': 'get the complete Moonshot AI chat completions endpoint URL with default base', 'get_supported_openai_params': 'get the list of supported OpenAI parameters excluding Moonshot-specific limitations', 'map_openai_params_temperature': 'map OpenAI parameters to Moonshot parameters with temperature clamping for n>1', 'fill_reasoning_content': 'fill missing reasoning_content on assistant messages with tool_calls for Moonshot reasoning models', 'transform_request_moonshot': 'transform the full request including tool_choice handling and reasoning_content injection'}
```

