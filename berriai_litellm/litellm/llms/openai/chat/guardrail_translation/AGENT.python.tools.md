# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/openai/chat/guardrail_translation/handler.py

Prompts

```
['apply guardrails to input messages by extracting text, images, and tool calls then mapping responses back', 'extract tool names from OpenAI chat completions request tools and functions arrays', 'apply guardrails to output response text content and tool calls in batch then map responses back', 'combine streaming chunks into complete text per choice and apply guardrails in batch', 'concatenate all delta content across streaming chunks into complete text per choice and content index']
```

Usage

```
{'process_input_messages': 'apply guardrails to input messages by extracting text, images, and tool calls then mapping responses back', 'extract_request_tool_names': 'extract tool names from OpenAI chat completions request tools and functions arrays', 'process_output_response': 'apply guardrails to output response text content and tool calls in batch then map responses back', 'process_output_streaming_response': 'combine streaming chunks into complete text per choice and apply guardrails in batch', 'combine_streaming_texts': 'concatenate all delta content across streaming chunks into complete text per choice and content index'}
```

