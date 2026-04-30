# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/mistral/chat/transformation.py

Prompts

```
['transform OpenAI chat completion request parameters to Mistral API format for a given model', 'transform raw Mistral API response into standardized ModelResponse object with content normalization', 'transform a list of OpenAI-format messages to Mistral-compatible message format handling content and tool calls', 'get a streaming response iterator that parses Mistral chat completion chunks with thinking block support', 'clean tool schemas by removing $id, $schema, additionalProperties and strict fields incompatible with Mistral API']
```

Usage

```
{'transform_request_mistral_chat': 'transform OpenAI chat completion request parameters to Mistral API format for a given model', 'transform_response_mistral_api': 'transform raw Mistral API response into standardized ModelResponse object with content normalization', 'transform_messages_openai_to_mistral': 'transform a list of OpenAI-format messages to Mistral-compatible message format handling content and tool calls', 'get_model_response_iterator_streaming': 'get a streaming response iterator that parses Mistral chat completion chunks with thinking block support', 'clean_tool_schema_for_mistral': 'clean tool schemas by removing $id, $schema, additionalProperties and strict fields incompatible with Mistral API'}
```

