# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/model_armor/model_armor.py

Prompts

```
['create a Google Cloud Model Armor guardrail instance with template_id, project_id, and location for LiteLLM', 'sanitize a user prompt using Model Armor API to detect RAI, malicious URIs, and sensitive data before LLM call', 'sanitize a model response using Model Armor API to filter harmful or sensitive content after LLM call', 'sanitize a file (PDF, Word, Excel, CSV) by encoding it as base64 and sending to Model Armor for content filtering', 'check Model Armor response to determine if content should be blocked based on RAI, SDP, or virus scan filter results']
```

Usage

```
{'create_model_armor_guardrail': 'create a Google Cloud Model Armor guardrail instance with template_id, project_id, and location for LiteLLM', 'sanitize_user_prompt': 'sanitize a user prompt using Model Armor API to detect RAI, malicious URIs, and sensitive data before LLM call', 'sanitize_model_response': 'sanitize a model response using Model Armor API to filter harmful or sensitive content after LLM call', 'sanitize_file_prompt': 'sanitize a file (PDF, Word, Excel, CSV) by encoding it as base64 and sending to Model Armor for content filtering', 'block_content_if_unsafe': 'check Model Armor response to determine if content should be blocked based on RAI, SDP, or virus scan filter results'}
```

