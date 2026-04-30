# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/mcp_jwt_signer/mcp_jwt_signer.py

Prompts

```
['create an MCPJWTSigner instance to sign outbound MCP requests with RS256 JWTs', 'get the active MCPJWTSigner singleton instance for JWKS discovery', 'get the JWKS containing the RSA public key for MCP server token verification', 'verify incoming bearer tokens and sign outbound JWTs as Authorization headers for MCP tool calls', 'build JWT scope strings for tool-level access control in MCP requests']
```

Usage

```
{'create_mcp_jwt_signer': 'create an MCPJWTSigner instance to sign outbound MCP requests with RS256 JWTs', 'get_mcp_jwt_signer': 'get the active MCPJWTSigner singleton instance for JWKS discovery', 'get_jwks': 'get the JWKS containing the RSA public key for MCP server token verification', 'async_pre_call_hook': 'verify incoming bearer tokens and sign outbound JWTs as Authorization headers for MCP tool calls', 'build_scope': 'build JWT scope strings for tool-level access control in MCP requests'}
```

