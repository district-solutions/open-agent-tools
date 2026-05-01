# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/enterprise/litellm_enterprise/enterprise_callbacks/callback_controls.py

Prompts

```
['check if a litellm callback is dynamically disabled via request headers or dynamic params', 'get the list of disabled callback names from request headers or request body params', 'review the premium user and admin toggle check that gates dynamic callback disabling', 'refactor the EnterpriseCallbackControls class to support additional callback disabling mechanisms', 'test the is_callback_disabled_dynamically method with string and CustomLogger callback types', 'initialize a LlamaGuard content moderation instance with a custom model name and unsafe content categories file', 'register a LlamaGuard prompt template with litellm to check conversation messages for unsafe content', 'run an async moderation hook that calls LlamaGuard to reject requests violating the content safety policy', 'debug print a statement using the verbose proxy logger when litellm verbose mode is enabled', 'review the _ENTERPRISE_LlamaGuard class to understand how it extends CustomLogger for content moderation', 'build a python module to run an LLM Guard content moderation check on prompts before sending to the LLM', 'create a pre-call hook that formats prompts and sends them to LLM Guard for safety validation', 'test the moderation_check method by sending text to the LLM Guard analyze endpoint and validating the response', 'refactor the should_proceed method to support additional llm_guard_mode options beyond key-specific, all, and request-specific', 'review the async_post_call_streaming_hook method that moderates streaming responses after LLM generation', 'scan a message string for secrets using detect-secrets and return detected secret types and values', 'configure the detect-secrets plugins list to include custom detectors like AWS keys or private keys', 'run the pre-call hook to automatically detect and redact secrets in LLM messages before sending', 'check if the hide_secrets guardrail should run based on user API key permissions', 'initialize the SecretDetection guardrail with a custom detect-secrets config for LLM proxy calls']
```

Usage

```
{'check_callback_disabled': 'check if a litellm callback is dynamically disabled via request headers or dynamic params', 'get_disabled_callbacks': 'get the list of disabled callback names from request headers or request body params', 'review_premium_check': 'review the premium user and admin toggle check that gates dynamic callback disabling', 'refactor_callback_controls': 'refactor the EnterpriseCallbackControls class to support additional callback disabling mechanisms', 'test_is_callback_disabled_dynamically': 'test the is_callback_disabled_dynamically method with string and CustomLogger callback types'}
```

## File: berriai_litellm/enterprise/litellm_enterprise/enterprise_callbacks/llama_guard.py

Prompts

```
['check if a litellm callback is dynamically disabled via request headers or dynamic params', 'get the list of disabled callback names from request headers or request body params', 'review the premium user and admin toggle check that gates dynamic callback disabling', 'refactor the EnterpriseCallbackControls class to support additional callback disabling mechanisms', 'test the is_callback_disabled_dynamically method with string and CustomLogger callback types', 'initialize a LlamaGuard content moderation instance with a custom model name and unsafe content categories file', 'register a LlamaGuard prompt template with litellm to check conversation messages for unsafe content', 'run an async moderation hook that calls LlamaGuard to reject requests violating the content safety policy', 'debug print a statement using the verbose proxy logger when litellm verbose mode is enabled', 'review the _ENTERPRISE_LlamaGuard class to understand how it extends CustomLogger for content moderation', 'build a python module to run an LLM Guard content moderation check on prompts before sending to the LLM', 'create a pre-call hook that formats prompts and sends them to LLM Guard for safety validation', 'test the moderation_check method by sending text to the LLM Guard analyze endpoint and validating the response', 'refactor the should_proceed method to support additional llm_guard_mode options beyond key-specific, all, and request-specific', 'review the async_post_call_streaming_hook method that moderates streaming responses after LLM generation', 'scan a message string for secrets using detect-secrets and return detected secret types and values', 'configure the detect-secrets plugins list to include custom detectors like AWS keys or private keys', 'run the pre-call hook to automatically detect and redact secrets in LLM messages before sending', 'check if the hide_secrets guardrail should run based on user API key permissions', 'initialize the SecretDetection guardrail with a custom detect-secrets config for LLM proxy calls']
```

Usage

```
{'init_llamaguard': 'initialize a LlamaGuard content moderation instance with a custom model name and unsafe content categories file', 'set_custom_prompt_template': 'register a LlamaGuard prompt template with litellm to check conversation messages for unsafe content', 'async_moderation_hook': 'run an async moderation hook that calls LlamaGuard to reject requests violating the content safety policy', 'print_verbose': 'debug print a statement using the verbose proxy logger when litellm verbose mode is enabled', 'review_llamaguard_class': 'review the _ENTERPRISE_LlamaGuard class to understand how it extends CustomLogger for content moderation'}
```

## File: berriai_litellm/enterprise/litellm_enterprise/enterprise_callbacks/llm_guard.py

Prompts

```
['check if a litellm callback is dynamically disabled via request headers or dynamic params', 'get the list of disabled callback names from request headers or request body params', 'review the premium user and admin toggle check that gates dynamic callback disabling', 'refactor the EnterpriseCallbackControls class to support additional callback disabling mechanisms', 'test the is_callback_disabled_dynamically method with string and CustomLogger callback types', 'initialize a LlamaGuard content moderation instance with a custom model name and unsafe content categories file', 'register a LlamaGuard prompt template with litellm to check conversation messages for unsafe content', 'run an async moderation hook that calls LlamaGuard to reject requests violating the content safety policy', 'debug print a statement using the verbose proxy logger when litellm verbose mode is enabled', 'review the _ENTERPRISE_LlamaGuard class to understand how it extends CustomLogger for content moderation', 'build a python module to run an LLM Guard content moderation check on prompts before sending to the LLM', 'create a pre-call hook that formats prompts and sends them to LLM Guard for safety validation', 'test the moderation_check method by sending text to the LLM Guard analyze endpoint and validating the response', 'refactor the should_proceed method to support additional llm_guard_mode options beyond key-specific, all, and request-specific', 'review the async_post_call_streaming_hook method that moderates streaming responses after LLM generation', 'scan a message string for secrets using detect-secrets and return detected secret types and values', 'configure the detect-secrets plugins list to include custom detectors like AWS keys or private keys', 'run the pre-call hook to automatically detect and redact secrets in LLM messages before sending', 'check if the hide_secrets guardrail should run based on user API key permissions', 'initialize the SecretDetection guardrail with a custom detect-secrets config for LLM proxy calls']
```

Usage

```
{'build_llm_guard_moderation': 'build a python module to run an LLM Guard content moderation check on prompts before sending to the LLM', 'create_moderation_hook': 'create a pre-call hook that formats prompts and sends them to LLM Guard for safety validation', 'test_moderation_check': 'test the moderation_check method by sending text to the LLM Guard analyze endpoint and validating the response', 'refactor_should_proceed': 'refactor the should_proceed method to support additional llm_guard_mode options beyond key-specific, all, and request-specific', 'review_post_call_streaming': 'review the async_post_call_streaming_hook method that moderates streaming responses after LLM generation'}
```

## File: berriai_litellm/enterprise/litellm_enterprise/enterprise_callbacks/secret_detection.py

Prompts

```
['check if a litellm callback is dynamically disabled via request headers or dynamic params', 'get the list of disabled callback names from request headers or request body params', 'review the premium user and admin toggle check that gates dynamic callback disabling', 'refactor the EnterpriseCallbackControls class to support additional callback disabling mechanisms', 'test the is_callback_disabled_dynamically method with string and CustomLogger callback types', 'initialize a LlamaGuard content moderation instance with a custom model name and unsafe content categories file', 'register a LlamaGuard prompt template with litellm to check conversation messages for unsafe content', 'run an async moderation hook that calls LlamaGuard to reject requests violating the content safety policy', 'debug print a statement using the verbose proxy logger when litellm verbose mode is enabled', 'review the _ENTERPRISE_LlamaGuard class to understand how it extends CustomLogger for content moderation', 'build a python module to run an LLM Guard content moderation check on prompts before sending to the LLM', 'create a pre-call hook that formats prompts and sends them to LLM Guard for safety validation', 'test the moderation_check method by sending text to the LLM Guard analyze endpoint and validating the response', 'refactor the should_proceed method to support additional llm_guard_mode options beyond key-specific, all, and request-specific', 'review the async_post_call_streaming_hook method that moderates streaming responses after LLM generation', 'scan a message string for secrets using detect-secrets and return detected secret types and values', 'configure the detect-secrets plugins list to include custom detectors like AWS keys or private keys', 'run the pre-call hook to automatically detect and redact secrets in LLM messages before sending', 'check if the hide_secrets guardrail should run based on user API key permissions', 'initialize the SecretDetection guardrail with a custom detect-secrets config for LLM proxy calls']
```

Usage

```
{'scan_message_for_secrets': 'scan a message string for secrets using detect-secrets and return detected secret types and values', 'configure_detect_secrets_plugins': 'configure the detect-secrets plugins list to include custom detectors like AWS keys or private keys', 'async_pre_call_hook_redact': 'run the pre-call hook to automatically detect and redact secrets in LLM messages before sending', 'should_run_check_guardrail': 'check if the hide_secrets guardrail should run based on user API key permissions', 'initialize_secret_detection_guardrail': 'initialize the SecretDetection guardrail with a custom detect-secrets config for LLM proxy calls'}
```

