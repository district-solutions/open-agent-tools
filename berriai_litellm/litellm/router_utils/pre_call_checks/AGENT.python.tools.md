# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/router_utils/pre_call_checks/deployment_affinity_check.py

Prompts

```
['create a DeploymentAffinityCheck instance with a cache, TTL, and affinity flags for router deployment stickiness', 'run async_filter_deployments to filter healthy deployments by previous_response_id, session affinity, or user key affinity', 'run async_pre_call_deployment_hook to persist user key or session ID to deployment mapping in the affinity cache', 'build a deployment affinity cache key from a model group and user key using the DeploymentAffinityCheck class method', 'build a session affinity cache key from a model group and session ID using the DeploymentAffinityCheck class method', 'create a ModelRateLimitingCheck instance with a DualCache to enforce TPM/RPM rate limits on model deployments', 'test the ModelRateLimitingCheck.pre_call_check method to verify it raises RateLimitError when TPM or RPM limits are exceeded', 'run the ModelRateLimitingCheck.async_pre_call_check method to enforce rate limits asynchronously before model requests', 'review the ModelRateLimitingCheck.async_log_success_event method that tracks token usage after successful model requests', 'summarize the ModelRateLimitingCheck._get_deployment_limits method that extracts TPM and RPM limits from deployment configurations']
```

Usage

```
{'create_DeploymentAffinityCheck': 'create a DeploymentAffinityCheck instance with a cache, TTL, and affinity flags for router deployment stickiness', 'run_async_filter_deployments': 'run async_filter_deployments to filter healthy deployments by previous_response_id, session affinity, or user key affinity', 'run_async_pre_call_deployment_hook': 'run async_pre_call_deployment_hook to persist user key or session ID to deployment mapping in the affinity cache', 'build_get_affinity_cache_key': 'build a deployment affinity cache key from a model group and user key using the DeploymentAffinityCheck class method', 'build_get_session_affinity_cache_key': 'build a session affinity cache key from a model group and session ID using the DeploymentAffinityCheck class method'}
```

## File: berriai_litellm/litellm/router_utils/pre_call_checks/model_rate_limit_check.py

Prompts

```
['create a DeploymentAffinityCheck instance with a cache, TTL, and affinity flags for router deployment stickiness', 'run async_filter_deployments to filter healthy deployments by previous_response_id, session affinity, or user key affinity', 'run async_pre_call_deployment_hook to persist user key or session ID to deployment mapping in the affinity cache', 'build a deployment affinity cache key from a model group and user key using the DeploymentAffinityCheck class method', 'build a session affinity cache key from a model group and session ID using the DeploymentAffinityCheck class method', 'create a ModelRateLimitingCheck instance with a DualCache to enforce TPM/RPM rate limits on model deployments', 'test the ModelRateLimitingCheck.pre_call_check method to verify it raises RateLimitError when TPM or RPM limits are exceeded', 'run the ModelRateLimitingCheck.async_pre_call_check method to enforce rate limits asynchronously before model requests', 'review the ModelRateLimitingCheck.async_log_success_event method that tracks token usage after successful model requests', 'summarize the ModelRateLimitingCheck._get_deployment_limits method that extracts TPM and RPM limits from deployment configurations']
```

Usage

```
{'create_ModelRateLimitingCheck': 'create a ModelRateLimitingCheck instance with a DualCache to enforce TPM/RPM rate limits on model deployments', 'test_pre_call_check': 'test the ModelRateLimitingCheck.pre_call_check method to verify it raises RateLimitError when TPM or RPM limits are exceeded', 'run_async_pre_call_check': 'run the ModelRateLimitingCheck.async_pre_call_check method to enforce rate limits asynchronously before model requests', 'review_async_log_success_event': 'review the ModelRateLimitingCheck.async_log_success_event method that tracks token usage after successful model requests', 'summarize_get_deployment_limits': 'summarize the ModelRateLimitingCheck._get_deployment_limits method that extracts TPM and RPM limits from deployment configurations'}
```

