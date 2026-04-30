# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/aim/aim.py

Prompts

```
['create an AimGuardrail instance to protect LLM calls with Aim security policies', 'run the async_pre_call_hook to analyze input messages before sending to an LLM', 'run the async_moderation_hook to moderate LLM responses after they are generated', 'anonymize LLM output by detecting sensitive data and redacting it via call_aim_guardrail_on_output', 'stream LLM output through async_post_call_streaming_iterator_hook for real-time guardrail analysis']
```

Usage

```
{'create_aim_guardrail': 'create an AimGuardrail instance to protect LLM calls with Aim security policies', 'run_pre_call_hook': 'run the async_pre_call_hook to analyze input messages before sending to an LLM', 'run_moderation_hook': 'run the async_moderation_hook to moderate LLM responses after they are generated', 'anonymize_output': 'anonymize LLM output by detecting sensitive data and redacting it via call_aim_guardrail_on_output', 'stream_output_guardrail': 'stream LLM output through async_post_call_streaming_iterator_hook for real-time guardrail analysis'}
```

