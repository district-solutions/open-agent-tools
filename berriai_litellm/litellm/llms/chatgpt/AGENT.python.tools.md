# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/chatgpt/authenticator.py

Prompts

```
['create an Authenticator instance to manage ChatGPT OAuth access and refresh tokens', 'build an access token by reading cached auth, refreshing expired tokens, or initiating device code login', 'test the get_account_id method to retrieve or derive the ChatGPT account ID from stored tokens', 'run the device code login flow to obtain new access and refresh tokens via OAuth 2.0 device authorization', 'refactor the refresh_tokens method to renew expired access tokens using a valid refresh token', 'get default ChatGPT API headers with access token, account id, and optional session id', 'get a ChatGPT user agent string built from originator, litellm version, OS info, and terminal detection', 'extract a session id from litellm params checking session_id, litellm_session_id, and metadata fields', 'ensure a ChatGPT session id exists by extracting from params or generating a new uuid', 'get the default ChatGPT Codex system instructions with optional environment variable override']
```

Usage

```
{'create_authenticator': 'create an Authenticator instance to manage ChatGPT OAuth access and refresh tokens', 'build_get_access_token': 'build an access token by reading cached auth, refreshing expired tokens, or initiating device code login', 'test_get_account_id': 'test the get_account_id method to retrieve or derive the ChatGPT account ID from stored tokens', 'run_login_device_code': 'run the device code login flow to obtain new access and refresh tokens via OAuth 2.0 device authorization', 'refactor_refresh_tokens': 'refactor the refresh_tokens method to renew expired access tokens using a valid refresh token'}
```

## File: berriai_litellm/litellm/llms/chatgpt/common_utils.py

Prompts

```
['create an Authenticator instance to manage ChatGPT OAuth access and refresh tokens', 'build an access token by reading cached auth, refreshing expired tokens, or initiating device code login', 'test the get_account_id method to retrieve or derive the ChatGPT account ID from stored tokens', 'run the device code login flow to obtain new access and refresh tokens via OAuth 2.0 device authorization', 'refactor the refresh_tokens method to renew expired access tokens using a valid refresh token', 'get default ChatGPT API headers with access token, account id, and optional session id', 'get a ChatGPT user agent string built from originator, litellm version, OS info, and terminal detection', 'extract a session id from litellm params checking session_id, litellm_session_id, and metadata fields', 'ensure a ChatGPT session id exists by extracting from params or generating a new uuid', 'get the default ChatGPT Codex system instructions with optional environment variable override']
```

Usage

```
{'get_chatgpt_default_headers': 'get default ChatGPT API headers with access token, account id, and optional session id', 'get_chatgpt_user_agent': 'get a ChatGPT user agent string built from originator, litellm version, OS info, and terminal detection', 'get_chatgpt_session_id': 'extract a session id from litellm params checking session_id, litellm_session_id, and metadata fields', 'ensure_chatgpt_session_id': 'ensure a ChatGPT session id exists by extracting from params or generating a new uuid', 'get_chatgpt_default_instructions': 'get the default ChatGPT Codex system instructions with optional environment variable override'}
```

