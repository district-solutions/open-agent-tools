# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/azure/base.py

Prompts

```
['create an AzureContent Safety guardrail with api_key, api_base, and optional api_version', 'test splitting text into word-boundary chunks under a maximum character length', 'summarize extracting the last consecutive block of user messages from a chat message list', 'review posting a JSON request body to an Azure Content Safety endpoint with auth headers', 'build an AzureGuardrailBase instance with api_key, api_base, and async httpx client', 'create an AzureContentSafetyPromptShieldGuardrail instance with api_key, api_base, and guardrail_name', 'run the async_pre_call_hook to scan user prompts before sending to the LLM', 'run async_make_request to send a user prompt to Azure Prompt Shield for attack detection', 'get the guardrail config model class via get_config_model static method', 'test that async_make_request raises HTTPException when Azure Prompt Shield detects an attack', 'create an AzureContentSafetyTextModerationGuardrail instance with api_key, api_base, and optional severity thresholds', 'test checking if an Azure Text Moderation response crosses configured severity thresholds per category', 'run the pre-call hook to scan user prompts before sending them to an LLM', 'run the post-call hook to scan successful LLM responses for policy violations', 'run the streaming hook to scan incremental LLM streaming output for policy violations']
```

Usage

```
{'create_azure_guardrail': 'create an AzureContent Safety guardrail with api_key, api_base, and optional api_version', 'test_split_text_by_words': 'test splitting text into word-boundary chunks under a maximum character length', 'summarize_get_user_prompt': 'summarize extracting the last consecutive block of user messages from a chat message list', 'review_post_to_content_safety': 'review posting a JSON request body to an Azure Content Safety endpoint with auth headers', 'build_azure_guardrail_init': 'build an AzureGuardrailBase instance with api_key, api_base, and async httpx client'}
```

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/azure/prompt_shield.py

Prompts

```
['create an AzureContent Safety guardrail with api_key, api_base, and optional api_version', 'test splitting text into word-boundary chunks under a maximum character length', 'summarize extracting the last consecutive block of user messages from a chat message list', 'review posting a JSON request body to an Azure Content Safety endpoint with auth headers', 'build an AzureGuardrailBase instance with api_key, api_base, and async httpx client', 'create an AzureContentSafetyPromptShieldGuardrail instance with api_key, api_base, and guardrail_name', 'run the async_pre_call_hook to scan user prompts before sending to the LLM', 'run async_make_request to send a user prompt to Azure Prompt Shield for attack detection', 'get the guardrail config model class via get_config_model static method', 'test that async_make_request raises HTTPException when Azure Prompt Shield detects an attack', 'create an AzureContentSafetyTextModerationGuardrail instance with api_key, api_base, and optional severity thresholds', 'test checking if an Azure Text Moderation response crosses configured severity thresholds per category', 'run the pre-call hook to scan user prompts before sending them to an LLM', 'run the post-call hook to scan successful LLM responses for policy violations', 'run the streaming hook to scan incremental LLM streaming output for policy violations']
```

Usage

```
{'create_azure_prompt_shield_guardrail': 'create an AzureContentSafetyPromptShieldGuardrail instance with api_key, api_base, and guardrail_name', 'run_pre_call_hook_scan': 'run the async_pre_call_hook to scan user prompts before sending to the LLM', 'run_async_make_request': 'run async_make_request to send a user prompt to Azure Prompt Shield for attack detection', 'get_guardrail_config_model': 'get the guardrail config model class via get_config_model static method', 'test_attack_detection_blocking': 'test that async_make_request raises HTTPException when Azure Prompt Shield detects an attack'}
```

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/azure/text_moderation.py

Prompts

```
['create an AzureContent Safety guardrail with api_key, api_base, and optional api_version', 'test splitting text into word-boundary chunks under a maximum character length', 'summarize extracting the last consecutive block of user messages from a chat message list', 'review posting a JSON request body to an Azure Content Safety endpoint with auth headers', 'build an AzureGuardrailBase instance with api_key, api_base, and async httpx client', 'create an AzureContentSafetyPromptShieldGuardrail instance with api_key, api_base, and guardrail_name', 'run the async_pre_call_hook to scan user prompts before sending to the LLM', 'run async_make_request to send a user prompt to Azure Prompt Shield for attack detection', 'get the guardrail config model class via get_config_model static method', 'test that async_make_request raises HTTPException when Azure Prompt Shield detects an attack', 'create an AzureContentSafetyTextModerationGuardrail instance with api_key, api_base, and optional severity thresholds', 'test checking if an Azure Text Moderation response crosses configured severity thresholds per category', 'run the pre-call hook to scan user prompts before sending them to an LLM', 'run the post-call hook to scan successful LLM responses for policy violations', 'run the streaming hook to scan incremental LLM streaming output for policy violations']
```

Usage

```
{'create_azure_text_moderation_guardrail': 'create an AzureContentSafetyTextModerationGuardrail instance with api_key, api_base, and optional severity thresholds', 'test_check_severity_threshold': 'test checking if an Azure Text Moderation response crosses configured severity thresholds per category', 'run_async_pre_call_hook': 'run the pre-call hook to scan user prompts before sending them to an LLM', 'run_async_post_call_success_hook': 'run the post-call hook to scan successful LLM responses for policy violations', 'run_async_post_call_streaming_hook': 'run the streaming hook to scan incremental LLM streaming output for policy violations'}
```

