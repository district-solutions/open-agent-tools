# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/noma/noma.py

Prompts

```
['create a NomaGuardrail instance to integrate Noma Security AI-DR API for LLM content moderation', 'check user messages against Noma Security guardrail policies before sending to the LLM', 'check LLM responses against Noma Security guardrail policies after generation', 'anonymize sensitive data in user messages and LLM responses detected by Noma guardrail', 'process streaming LLM response chunks with Noma guardrail safety checks', 'create a NomaV2Guardrail instance with api_key, api_base, application_id, monitor_mode, and block_failures parameters', 'run the NomaV2Guardrail apply_guardrail method to scan request or response inputs against the Noma Security API', 'build a scan payload dict with inputs, request_data, input_type, monitor_mode, and optional application_id for the Noma API', 'test the _resolve_action_from_response method to parse BLOCKED, NONE, or GUARDRAIL_INTERVENED actions from Noma API responses', 'review the NomaV2Guardrail class and its supported event hooks for pre_call, during_call, post_call, pre_mcp_call, and during_mcp_call']
```

Usage

```
{'create_noma_guardrail': 'create a NomaGuardrail instance to integrate Noma Security AI-DR API for LLM content moderation', 'check_user_message': 'check user messages against Noma Security guardrail policies before sending to the LLM', 'check_llm_response': 'check LLM responses against Noma Security guardrail policies after generation', 'anonymize_sensitive_content': 'anonymize sensitive data in user messages and LLM responses detected by Noma guardrail', 'process_streaming_response': 'process streaming LLM response chunks with Noma guardrail safety checks'}
```

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/noma/noma_v2.py

Prompts

```
['create a NomaGuardrail instance to integrate Noma Security AI-DR API for LLM content moderation', 'check user messages against Noma Security guardrail policies before sending to the LLM', 'check LLM responses against Noma Security guardrail policies after generation', 'anonymize sensitive data in user messages and LLM responses detected by Noma guardrail', 'process streaming LLM response chunks with Noma guardrail safety checks', 'create a NomaV2Guardrail instance with api_key, api_base, application_id, monitor_mode, and block_failures parameters', 'run the NomaV2Guardrail apply_guardrail method to scan request or response inputs against the Noma Security API', 'build a scan payload dict with inputs, request_data, input_type, monitor_mode, and optional application_id for the Noma API', 'test the _resolve_action_from_response method to parse BLOCKED, NONE, or GUARDRAIL_INTERVENED actions from Noma API responses', 'review the NomaV2Guardrail class and its supported event hooks for pre_call, during_call, post_call, pre_mcp_call, and during_mcp_call']
```

Usage

```
{'create_noma_v2_guardrail': 'create a NomaV2Guardrail instance with api_key, api_base, application_id, monitor_mode, and block_failures parameters', 'run_noma_v2_scan': 'run the NomaV2Guardrail apply_guardrail method to scan request or response inputs against the Noma Security API', 'build_noma_scan_payload': 'build a scan payload dict with inputs, request_data, input_type, monitor_mode, and optional application_id for the Noma API', 'test_noma_action_resolution': 'test the _resolve_action_from_response method to parse BLOCKED, NONE, or GUARDRAIL_INTERVENED actions from Noma API responses', 'review_noma_v2_guardrail': 'review the NomaV2Guardrail class and its supported event hooks for pre_call, during_call, post_call, pre_mcp_call, and during_mcp_call'}
```

