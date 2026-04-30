# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/akto/akto.py

Prompts

```
['create an AktoGuardrail instance with base URL, API key, account ID, and fail-closed fallback', 'build an Akto mirroring payload from guardrail inputs and request data with double-encoded JSON bodies', 'apply the Akto guardrail hook to validate pre_call requests or ingest post_call responses', 'parse an Akto HTTP response and return whether the request is allowed and the reason', 'handle Akto service unavailability by returning inputs on fail-open or raising 503 on fail-closed']
```

Usage

```
{'create_akto_guardrail': 'create an AktoGuardrail instance with base URL, API key, account ID, and fail-closed fallback', 'build_akto_payload': 'build an Akto mirroring payload from guardrail inputs and request data with double-encoded JSON bodies', 'apply_guardrail': 'apply the Akto guardrail hook to validate pre_call requests or ingest post_call responses', 'handle_guardrail_response': 'parse an Akto HTTP response and return whether the request is allowed and the reason', 'handle_unreachable': 'handle Akto service unavailability by returning inputs on fail-open or raising 503 on fail-closed'}
```

