# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/ibm_guardrails/ibm_detector.py

Prompts

```
['create an IBMGuardrailDetector instance to protect LLM calls with IBM FMS Guardrails detection', 'run the async_pre_call_hook to check input messages for violations before LLM API calls', 'run the async_post_call_success_hook to check LLM response content for guardrail violations', 'run the async_moderation_hook to moderate input messages in parallel to LLM API calls', 'filter guardrail detections by score threshold to only surface violations above the configured level']
```

Usage

```
{'create_ibm_guardrail_detector': 'create an IBMGuardrailDetector instance to protect LLM calls with IBM FMS Guardrails detection', 'run_pre_call_guardrail_hook': 'run the async_pre_call_hook to check input messages for violations before LLM API calls', 'run_post_call_guardrail_hook': 'run the async_post_call_success_hook to check LLM response content for guardrail violations', 'run_during_call_moderation_hook': 'run the async_moderation_hook to moderate input messages in parallel to LLM API calls', 'filter_detections_by_threshold': 'filter guardrail detections by score threshold to only surface violations above the configured level'}
```

