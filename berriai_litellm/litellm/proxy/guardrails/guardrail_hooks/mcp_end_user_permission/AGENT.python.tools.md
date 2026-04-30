# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/mcp_end_user_permission/mcp_end_user_permission.py

Prompts

```
['apply the MCPEndUserPermissionGuardrail to filter MCP tools an end user cannot access', "check request tools and filter out those from MCP servers not in the end user's allowed list", "resolve the end user's object permission via cached auth lookup for MCP access control", 'get allowed MCP servers from direct permissions and access group memberships', 'get the config model for the MCPEndUserPermissionGuardrail to expose it in the UI']
```

Usage

```
{'apply_guardrail_mcp_tools': 'apply the MCPEndUserPermissionGuardrail to filter MCP tools an end user cannot access', 'check_request_tools_filtered': "check request tools and filter out those from MCP servers not in the end user's allowed list", 'resolve_end_user_object_permission': "resolve the end user's object permission via cached auth lookup for MCP access control", 'get_allowed_mcp_servers': 'get allowed MCP servers from direct permissions and access group memberships', 'get_config_model_guardrail': 'get the config model for the MCPEndUserPermissionGuardrail to expose it in the UI'}
```

