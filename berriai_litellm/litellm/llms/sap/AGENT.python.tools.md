# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/sap/credentials.py

Prompts

```
['fetch SAP AI Core credentials from config, env vars, service keys, or VCAP with first-source-wins resolution', 'create a cached OAuth2 bearer token callable that auto-refreshes before expiry using resolved SAP credentials', 'validate SAP AI Core credentials for completeness and ensure exactly one auth method is provided', 'load SAP AI Core config JSON from AICORE_CONFIG env var, AICORE_HOME, or profile-based config files', 'resolve credentials from a list of named sources returning the first source that provides any values']
```

Usage

```
{'fetch_credentials': 'fetch SAP AI Core credentials from config, env vars, service keys, or VCAP with first-source-wins resolution', 'get_token_creator': 'create a cached OAuth2 bearer token callable that auto-refreshes before expiry using resolved SAP credentials', 'validate_credentials': 'validate SAP AI Core credentials for completeness and ensure exactly one auth method is provided', 'init_conf': 'load SAP AI Core config JSON from AICORE_CONFIG env var, AICORE_HOME, or profile-based config files', 'resolve_credentials': 'resolve credentials from a list of named sources returning the first source that provides any values'}
```

