# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/panw_prisma_airs/panw_prisma_airs.py

Prompts

```
['create a PanwPrismaAirsHandler instance to scan prompts and responses using PANW Prisma AIRS API for threat detection', 'scan user prompts before sending to LLM using async_pre_call_hook and block malicious content', 'scan LLM responses after generation using async_post_call_success_hook and apply content masking', 'scan and process streaming response chunks using async_post_call_streaming_iterator_hook with assembled response masking', 'apply the unified apply_guardrail method to scan texts, tool calls, and MCP tool invocations with masking support']
```

Usage

```
{'create_panw_prisma_airs_handler': 'create a PanwPrismaAirsHandler instance to scan prompts and responses using PANW Prisma AIRS API for threat detection', 'scan_prompts_pre_call_hook': 'scan user prompts before sending to LLM using async_pre_call_hook and block malicious content', 'scan_responses_post_call_hook': 'scan LLM responses after generation using async_post_call_success_hook and apply content masking', 'scan_streaming_responses': 'scan and process streaming response chunks using async_post_call_streaming_iterator_hook with assembled response masking', 'apply_unified_guardrail': 'apply the unified apply_guardrail method to scan texts, tool calls, and MCP tool invocations with masking support'}
```

