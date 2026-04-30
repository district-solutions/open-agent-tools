# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/aporia_ai/aporia_ai.py

Prompts

```
['create an AporiaGuardrail instance with optional api_key and api_base for LLM call moderation', "transform chat messages to supported roles (system, user, assistant) and remap unsupported roles to 'other'", 'prepare an Aporia API request body with messages, response, and auto-set validation target based on available inputs', "send a validated request to the Aporia AI API and block execution if the response action is 'block'", 'run during-call moderation on incoming messages via the Aporia AI guardrail hook']
```

Usage

```
{'create_aporia_guardrail': 'create an AporiaGuardrail instance with optional api_key and api_base for LLM call moderation', 'transform_messages': "transform chat messages to supported roles (system, user, assistant) and remap unsupported roles to 'other'", 'prepare_aporia_request': 'prepare an Aporia API request body with messages, response, and auto-set validation target based on available inputs', 'make_aporia_api_request': "send a validated request to the Aporia AI API and block execution if the response action is 'block'", 'run_async_moderation_hook': 'run during-call moderation on incoming messages via the Aporia AI guardrail hook'}
```

