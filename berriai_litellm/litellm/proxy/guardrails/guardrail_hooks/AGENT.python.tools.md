# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/bedrock_guardrails.py

Prompts

```
['run Bedrock Guardrail pre-call hook to validate LLM input messages before the API call', 'run Bedrock Guardrail post-call hook to validate LLM response after the API call', 'apply Bedrock guardrail to a batch of texts for testing without making actual LLM calls', 'create a BedrockGuardrail instance with guardrail identifier, version, and AWS credentials', 'redact PII matches and sensitive information from Bedrock guardrail assessment responses', 'create a Presidio PII masking guardrail instance with analyzer and anonymizer API bases and PII entity config', 'check a text string for PII entities using the Presidio analyzer and anonymizer endpoints', 'unmask PII tokens in a string by replacing numbered tokens with their original text values', 'process a ModelResponse to unmask or mask PII in content, tool calls, and function arguments', 'apply the Presidio guardrail to a list of input texts, masking or unmasking based on input type', 'create a ToolPermissionGuardrail instance with rules, default_action, and on_disallowed_action settings', 'check if a tool name and type is allowed based on configured permission rules', 'run the async_pre_call_hook to validate tool permissions before an LLM call', 'run the async_post_call_success_hook to check tool usage permissions after an LLM response', 'run the async_post_call_streaming_iterator_hook to check tool permissions in streamed LLM responses']
```

Usage

```
{'run_bedrock_guardrail_pre_call': 'run Bedrock Guardrail pre-call hook to validate LLM input messages before the API call', 'run_bedrock_guardrail_post_call': 'run Bedrock Guardrail post-call hook to validate LLM response after the API call', 'apply_bedrock_guardrail_text': 'apply Bedrock guardrail to a batch of texts for testing without making actual LLM calls', 'create_bedrock_guardrail_instance': 'create a BedrockGuardrail instance with guardrail identifier, version, and AWS credentials', 'redact_pii_in_guardrail_response': 'redact PII matches and sensitive information from Bedrock guardrail assessment responses'}
```

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/presidio.py

Prompts

```
['run Bedrock Guardrail pre-call hook to validate LLM input messages before the API call', 'run Bedrock Guardrail post-call hook to validate LLM response after the API call', 'apply Bedrock guardrail to a batch of texts for testing without making actual LLM calls', 'create a BedrockGuardrail instance with guardrail identifier, version, and AWS credentials', 'redact PII matches and sensitive information from Bedrock guardrail assessment responses', 'create a Presidio PII masking guardrail instance with analyzer and anonymizer API bases and PII entity config', 'check a text string for PII entities using the Presidio analyzer and anonymizer endpoints', 'unmask PII tokens in a string by replacing numbered tokens with their original text values', 'process a ModelResponse to unmask or mask PII in content, tool calls, and function arguments', 'apply the Presidio guardrail to a list of input texts, masking or unmasking based on input type', 'create a ToolPermissionGuardrail instance with rules, default_action, and on_disallowed_action settings', 'check if a tool name and type is allowed based on configured permission rules', 'run the async_pre_call_hook to validate tool permissions before an LLM call', 'run the async_post_call_success_hook to check tool usage permissions after an LLM response', 'run the async_post_call_streaming_iterator_hook to check tool permissions in streamed LLM responses']
```

Usage

```
{'create_presidio_guardrail': 'create a Presidio PII masking guardrail instance with analyzer and anonymizer API bases and PII entity config', 'check_pii_text': 'check a text string for PII entities using the Presidio analyzer and anonymizer endpoints', 'unmask_pii_tokens': 'unmask PII tokens in a string by replacing numbered tokens with their original text values', 'process_response_for_pii': 'process a ModelResponse to unmask or mask PII in content, tool calls, and function arguments', 'apply_guardrail_text': 'apply the Presidio guardrail to a list of input texts, masking or unmasking based on input type'}
```

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/tool_permission.py

Prompts

```
['run Bedrock Guardrail pre-call hook to validate LLM input messages before the API call', 'run Bedrock Guardrail post-call hook to validate LLM response after the API call', 'apply Bedrock guardrail to a batch of texts for testing without making actual LLM calls', 'create a BedrockGuardrail instance with guardrail identifier, version, and AWS credentials', 'redact PII matches and sensitive information from Bedrock guardrail assessment responses', 'create a Presidio PII masking guardrail instance with analyzer and anonymizer API bases and PII entity config', 'check a text string for PII entities using the Presidio analyzer and anonymizer endpoints', 'unmask PII tokens in a string by replacing numbered tokens with their original text values', 'process a ModelResponse to unmask or mask PII in content, tool calls, and function arguments', 'apply the Presidio guardrail to a list of input texts, masking or unmasking based on input type', 'create a ToolPermissionGuardrail instance with rules, default_action, and on_disallowed_action settings', 'check if a tool name and type is allowed based on configured permission rules', 'run the async_pre_call_hook to validate tool permissions before an LLM call', 'run the async_post_call_success_hook to check tool usage permissions after an LLM response', 'run the async_post_call_streaming_iterator_hook to check tool permissions in streamed LLM responses']
```

Usage

```
{'create_tool_permission_guardrail': 'create a ToolPermissionGuardrail instance with rules, default_action, and on_disallowed_action settings', 'check_tool_permission': 'check if a tool name and type is allowed based on configured permission rules', 'run_pre_call_hook': 'run the async_pre_call_hook to validate tool permissions before an LLM call', 'run_post_call_hook': 'run the async_post_call_success_hook to check tool usage permissions after an LLM response', 'run_streaming_hook': 'run the async_post_call_streaming_iterator_hook to check tool permissions in streamed LLM responses'}
```

