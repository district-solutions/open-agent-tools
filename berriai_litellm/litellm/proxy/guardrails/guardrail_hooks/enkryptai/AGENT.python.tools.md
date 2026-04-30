# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/enkryptai/enkryptai.py

Prompts

```
['create an EnkryptAIGuardrails instance with api_key, api_base, and policy_name for LLM call protection', 'run EnkryptAI pre-call hook to detect policy violations, PII, and injection attacks before LLM API call', 'run EnkryptAI post-call hook to check LLM response text for policy violations and toxic content', 'run EnkryptAI during-call moderation hook to reject input messages with detected attacks', 'apply EnkryptAI guardrail to a batch of texts and raise ValueError if any attacks are detected']
```

Usage

```
{'create_enkryptai_guardrail': 'create an EnkryptAIGuardrails instance with api_key, api_base, and policy_name for LLM call protection', 'run_pre_call_guardrail': 'run EnkryptAI pre-call hook to detect policy violations, PII, and injection attacks before LLM API call', 'run_post_call_guardrail': 'run EnkryptAI post-call hook to check LLM response text for policy violations and toxic content', 'run_during_call_moderation': 'run EnkryptAI during-call moderation hook to reject input messages with detected attacks', 'apply_guardrail_batch': 'apply EnkryptAI guardrail to a batch of texts and raise ValueError if any attacks are detected'}
```

