# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/pillar/pillar.py

Prompts

```
['initialize a PillarGuardrail instance with API key, timeout, and on_flagged_action settings', 'scan input messages for security threats before sending to LLM using async_pre_call_hook', 'scan LLM responses for security threats after generation using async_post_call_success_hook', 'scan request content in parallel with LLM processing using async_moderation_hook', 'build URL-safe Pillar response headers from metadata store with truncation support', 'get the Pydantic configuration model class for PillarGuardrail setup']
```

Usage

```
{'init_PillarGuardrail': 'initialize a PillarGuardrail instance with API key, timeout, and on_flagged_action settings', 'run_pre_call_scan': 'scan input messages for security threats before sending to LLM using async_pre_call_hook', 'run_post_call_scan': 'scan LLM responses for security threats after generation using async_post_call_success_hook', 'run_moderation_scan': 'scan request content in parallel with LLM processing using async_moderation_hook', 'build_response_headers': 'build URL-safe Pillar response headers from metadata store with truncation support', 'get_config_model': 'get the Pydantic configuration model class for PillarGuardrail setup'}
```

