# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/tests/enterprise/litellm_enterprise/proxy/auth/test_route_checks.py

Prompts

```
['test that should_call_route raises HTTPException when management routes are disabled for a given route', 'test that should_call_route raises HTTPException when LLM API routes are disabled for a given route', 'test that management route check takes priority when both management and LLM API routes are disabled', 'test that /models and /v1/models routes are exempt from DISABLE_LLM_API_ENDPOINTS restrictions', 'test that MCP management routes remain reachable when LLM API endpoints are disabled but blocked when admin endpoints are disabled']
```

Usage

```
{'test_should_call_route_management_disabled': 'test that should_call_route raises HTTPException when management routes are disabled for a given route', 'test_should_call_route_llm_api_disabled': 'test that should_call_route raises HTTPException when LLM API routes are disabled for a given route', 'test_should_call_route_both_disabled_management_priority': 'test that management route check takes priority when both management and LLM API routes are disabled', 'test_models_route_exemption': 'test that /models and /v1/models routes are exempt from DISABLE_LLM_API_ENDPOINTS restrictions', 'test_mcp_management_routes': 'test that MCP management routes remain reachable when LLM API endpoints are disabled but blocked when admin endpoints are disabled'}
```

