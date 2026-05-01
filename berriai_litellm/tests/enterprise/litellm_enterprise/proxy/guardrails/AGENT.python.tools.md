# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/tests/enterprise/litellm_enterprise/proxy/guardrails/test_bedrock_apply_guardrail.py

Prompts

```
['test the BedrockGuardrail apply_guardrail method returns allowed text from a mocked Bedrock API response', 'test the BedrockGuardrail apply_guardrail method propagates HTTPException when content is blocked by the guardrail policy', 'test the BedrockGuardrail apply_guardrail method returns masked redacted content from the Bedrock API response', 'test the BedrockGuardrail apply_guardrail method raises an exception when the Bedrock API connection fails', 'test the apply_guardrail endpoint integration with BedrockGuardrail using a mocked guardrail registry and API response']
```

Usage

```
{'test_bedrock_apply_guardrail_success': 'test the BedrockGuardrail apply_guardrail method returns allowed text from a mocked Bedrock API response', 'test_bedrock_apply_guardrail_blocked': 'test the BedrockGuardrail apply_guardrail method propagates HTTPException when content is blocked by the guardrail policy', 'test_bedrock_apply_guardrail_with_masking': 'test the BedrockGuardrail apply_guardrail method returns masked redacted content from the Bedrock API response', 'test_bedrock_apply_guardrail_api_failure': 'test the BedrockGuardrail apply_guardrail method raises an exception when the Bedrock API connection fails', 'test_bedrock_apply_guardrail_endpoint_integration': 'test the apply_guardrail endpoint integration with BedrockGuardrail using a mocked guardrail registry and API response'}
```

