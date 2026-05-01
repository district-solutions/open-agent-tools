# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/tests/litellm/litellm_core_utils/test_json_schema_validation.py

Prompts

```
['test that per-request enable_json_schema_validation overrides the global litellm flag for thread-safe concurrent usage', 'test post_call_processing validates response content against a strict JSON schema with required fields', 'test creating a ModelResponse with JSON string content for post_call_processing validation', 'test that per-request enable_json_schema_validation flag takes precedence over the global litellm setting', 'test that enable_json_schema_validation is registered in all_litellm_params to prevent leaking to provider APIs']
```

Usage

```
{'test_per_request_json_schema_validation': 'test that per-request enable_json_schema_validation overrides the global litellm flag for thread-safe concurrent usage', 'test_post_call_processing_with_schema': 'test post_call_processing validates response content against a strict JSON schema with required fields', 'test_model_response_creation': 'test creating a ModelResponse with JSON string content for post_call_processing validation', 'test_global_flag_override_behavior': 'test that per-request enable_json_schema_validation flag takes precedence over the global litellm setting', 'test_all_litellm_params_registration': 'test that enable_json_schema_validation is registered in all_litellm_params to prevent leaking to provider APIs'}
```

