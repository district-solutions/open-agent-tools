# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/enterprise/litellm_enterprise/proxy/auth/route_checks.py

Prompts

```
['check if LLM API endpoints are disabled using the DISABLE_LLM_API_ENDPOINTS environment variable', 'check if admin management routes are disabled using the DISABLE_ADMIN_ENDPOINTS environment variable', 'validate whether a given route should be callable or raise a 403 forbidden exception', 'review the LLM_API_EXEMPT_ROUTES constant to see which routes remain accessible when LLM APIs are disabled', 'refactor the EnterpriseRouteChecks class to add custom route exemption logic for specific endpoints']
```

Usage

```
{'check_llm_api_disabled': 'check if LLM API endpoints are disabled using the DISABLE_LLM_API_ENDPOINTS environment variable', 'check_management_routes_disabled': 'check if admin management routes are disabled using the DISABLE_ADMIN_ENDPOINTS environment variable', 'validate_route_access': 'validate whether a given route should be callable or raise a 403 forbidden exception', 'review_exempt_routes': 'review the LLM_API_EXEMPT_ROUTES constant to see which routes remain accessible when LLM APIs are disabled', 'refactor_route_checks': 'refactor the EnterpriseRouteChecks class to add custom route exemption logic for specific endpoints'}
```

