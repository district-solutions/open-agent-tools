# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/hiddenlayer/hiddenlayer.py

Prompts

```
['create a HiddenlayerGuardrail instance with api_id, api_key, and api_base for LLM safety validation', 'create a HiddenlayerGuardrailV2 instance with api_id, api_key, and api_base for v2 LLM safety validation', 'run apply_guardrail on a HiddenlayerGuardrail instance to validate or redact request text before LLM calls', 'run apply_guardrail on a HiddenlayerGuardrail instance to validate or redact response text after LLM calls', 'run _call_hiddenlayer on a HiddenlayerGuardrail instance to send payloads to HiddenLayer detection API']
```

Usage

```
{'create_hiddenlayer_guardrail': 'create a HiddenlayerGuardrail instance with api_id, api_key, and api_base for LLM safety validation', 'create_hiddenlayer_guardrail_v2': 'create a HiddenlayerGuardrailV2 instance with api_id, api_key, and api_base for v2 LLM safety validation', 'run_apply_guardrail_request': 'run apply_guardrail on a HiddenlayerGuardrail instance to validate or redact request text before LLM calls', 'run_apply_guardrail_response': 'run apply_guardrail on a HiddenlayerGuardrail instance to validate or redact response text after LLM calls', 'run_call_hiddenlayer': 'run _call_hiddenlayer on a HiddenlayerGuardrail instance to send payloads to HiddenLayer detection API'}
```

