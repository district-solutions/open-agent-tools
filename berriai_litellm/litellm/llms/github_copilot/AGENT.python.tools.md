# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/github_copilot/authenticator.py

Prompts

```
['test the Authenticator.get_access_token method to retrieve a GitHub access token', 'create a call to Authenticator.get_api_key to retrieve or refresh a Copilot API key', 'build a call to Authenticator.get_api_base to get the Copilot API endpoint from stored token data', 'refactor the Authenticator._refresh_api_key method to handle API key refresh with retry logic', 'run the Authenticator._login method to perform the GitHub Copilot device code OAuth flow', 'build default GitHub Copilot API headers with an API key for authenticated requests', 'create a GitHub Copilot error with status code, message, and optional request/response context', 'create a device code authentication error for GitHub Copilot OAuth flow', 'create an expired API key error when GitHub Copilot token has expired', 'create a refresh API key error when token refresh fails for GitHub Copilot']
```

Usage

```
{'test_get_access_token': 'test the Authenticator.get_access_token method to retrieve a GitHub access token', 'create_get_api_key': 'create a call to Authenticator.get_api_key to retrieve or refresh a Copilot API key', 'build_get_api_base': 'build a call to Authenticator.get_api_base to get the Copilot API endpoint from stored token data', 'refactor_refresh_api_key': 'refactor the Authenticator._refresh_api_key method to handle API key refresh with retry logic', 'run_login_flow': 'run the Authenticator._login method to perform the GitHub Copilot device code OAuth flow'}
```

## File: berriai_litellm/litellm/llms/github_copilot/common_utils.py

Prompts

```
['test the Authenticator.get_access_token method to retrieve a GitHub access token', 'create a call to Authenticator.get_api_key to retrieve or refresh a Copilot API key', 'build a call to Authenticator.get_api_base to get the Copilot API endpoint from stored token data', 'refactor the Authenticator._refresh_api_key method to handle API key refresh with retry logic', 'run the Authenticator._login method to perform the GitHub Copilot device code OAuth flow', 'build default GitHub Copilot API headers with an API key for authenticated requests', 'create a GitHub Copilot error with status code, message, and optional request/response context', 'create a device code authentication error for GitHub Copilot OAuth flow', 'create an expired API key error when GitHub Copilot token has expired', 'create a refresh API key error when token refresh fails for GitHub Copilot']
```

Usage

```
{'build_copilot_headers': 'build default GitHub Copilot API headers with an API key for authenticated requests', 'create_github_copilot_error': 'create a GitHub Copilot error with status code, message, and optional request/response context', 'create_get_device_code_error': 'create a device code authentication error for GitHub Copilot OAuth flow', 'create_api_key_expired_error': 'create an expired API key error when GitHub Copilot token has expired', 'create_refresh_api_key_error': 'create a refresh API key error when token refresh fails for GitHub Copilot'}
```

