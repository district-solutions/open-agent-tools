# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/a2a_protocol/litellm_completion_bridge/transformation.py

Prompts

```
['transform an A2A message with role and parts into OpenAI message format', 'transform a LiteLLM ModelResponse into A2A SendMessageResponse JSON-RPC format', 'create an initial A2A task event with status submitted and context tracking', 'create an A2A status update event with working or completed state', 'create an A2A artifact update event with text content parts']
```

Usage

```
{'transform_a2a_message_to_openai': 'transform an A2A message with role and parts into OpenAI message format', 'transform_openai_response_to_a2a': 'transform a LiteLLM ModelResponse into A2A SendMessageResponse JSON-RPC format', 'create_a2a_task_event': 'create an initial A2A task event with status submitted and context tracking', 'create_a2a_status_update': 'create an A2A status update event with working or completed state', 'create_a2a_artifact_update': 'create an A2A artifact update event with text content parts'}
```

