# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy_auth/credentials.py

Prompts

```
['create an AzureAD credential wrapper that obtains OAuth2 tokens via DefaultAzureCredential or a specific azure-identity credential', 'create a generic OAuth2 credential provider using client credentials flow with token caching for any OAuth2 identity provider', 'create a proxy auth handler that manages token lifecycle and injects Bearer Authorization headers into HTTP requests', 'test AzureADCredential get_token method returns an AccessToken with a valid JWT and expiration timestamp', 'test GenericOAuth2Credential get_token method obtains a token via OAuth2 client credentials POST and caches it with a 60-second refresh buffer']
```

Usage

```
{'create_AzureADCredential': 'create an AzureAD credential wrapper that obtains OAuth2 tokens via DefaultAzureCredential or a specific azure-identity credential', 'create_GenericOAuth2Credential': 'create a generic OAuth2 credential provider using client credentials flow with token caching for any OAuth2 identity provider', 'create_ProxyAuthHandler': 'create a proxy auth handler that manages token lifecycle and injects Bearer Authorization headers into HTTP requests', 'test_AzureADCredential_get_token': 'test AzureADCredential get_token method returns an AccessToken with a valid JWT and expiration timestamp', 'test_GenericOAuth2Credential_get_token': 'test GenericOAuth2Credential get_token method obtains a token via OAuth2 client credentials POST and caches it with a 60-second refresh buffer'}
```

