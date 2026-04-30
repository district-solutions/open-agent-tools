# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/jwt_auth/auth.py

Prompts

```
['review the TokenAuthenticationPhaseout class that phases out legacy token auth and logs usage', 'test the TokenAuthenticationPhaseout.authenticate method with a mock request and feature flag', 'review the JWTAuthScheme OpenAPI extension class that documents token authentication', 'summarize the TokenAuthenticationPhaseout.authenticate method behavior and side effects', 'refactor the TokenAuthenticationPhaseout class to extract the legacy token check into a separate method', 'create an organization-specific JWT settings model instance with API token TTL and enable flags', 'encode a JWT payload into a truncated token string with header and payload only, no signature', 'encode a JWT payload into a complete token string with header, payload, and signature', 'create a long-lived LSAPIToken refresh token with organization-specific lifetime and truncated storage', 'initialize a TruncatedLSAPIToken from a header-payload-only JWT string with a dummy signature appended', 'create an LSA API token serializer that returns the full JWT string via SerializerMethodField', 'list LSA API tokens returning only the header/payload portion of each token', 'blacklist an LSA API token using TruncatedLSAPIToken as the token class', 'rotate an LSA API token by validating a refresh token and returning a new refresh token', 'retrieve JWT settings for the currently active organization using the JWTSettingsAPI view', 'update JWT settings for the currently active organization via POST to JWTSettingsAPI', 'list all non-expired non-blacklisted API tokens for the current user using LSAPITokenView', 'create a new API token for the current user via LSAPITokenView, rejecting if one already exists', 'refresh a JWT access token using a refresh token via DecoratedTokenRefreshView']
```

Usage

```
{'review_TokenAuthenticationPhaseout': 'review the TokenAuthenticationPhaseout class that phases out legacy token auth and logs usage', 'test_TokenAuthenticationPhaseout_authenticate': 'test the TokenAuthenticationPhaseout.authenticate method with a mock request and feature flag', 'review_JWTAuthScheme': 'review the JWTAuthScheme OpenAPI extension class that documents token authentication', 'summarize_TokenAuthenticationPhaseout_authenticate': 'summarize the TokenAuthenticationPhaseout.authenticate method behavior and side effects', 'refactor_TokenAuthenticationPhaseout': 'refactor the TokenAuthenticationPhaseout class to extract the legacy token check into a separate method'}
```

## File: HumanSignal_label-studio/label_studio/jwt_auth/models.py

Prompts

```
['review the TokenAuthenticationPhaseout class that phases out legacy token auth and logs usage', 'test the TokenAuthenticationPhaseout.authenticate method with a mock request and feature flag', 'review the JWTAuthScheme OpenAPI extension class that documents token authentication', 'summarize the TokenAuthenticationPhaseout.authenticate method behavior and side effects', 'refactor the TokenAuthenticationPhaseout class to extract the legacy token check into a separate method', 'create an organization-specific JWT settings model instance with API token TTL and enable flags', 'encode a JWT payload into a truncated token string with header and payload only, no signature', 'encode a JWT payload into a complete token string with header, payload, and signature', 'create a long-lived LSAPIToken refresh token with organization-specific lifetime and truncated storage', 'initialize a TruncatedLSAPIToken from a header-payload-only JWT string with a dummy signature appended', 'create an LSA API token serializer that returns the full JWT string via SerializerMethodField', 'list LSA API tokens returning only the header/payload portion of each token', 'blacklist an LSA API token using TruncatedLSAPIToken as the token class', 'rotate an LSA API token by validating a refresh token and returning a new refresh token', 'retrieve JWT settings for the currently active organization using the JWTSettingsAPI view', 'update JWT settings for the currently active organization via POST to JWTSettingsAPI', 'list all non-expired non-blacklisted API tokens for the current user using LSAPITokenView', 'create a new API token for the current user via LSAPITokenView, rejecting if one already exists', 'refresh a JWT access token using a refresh token via DecoratedTokenRefreshView']
```

Usage

```
{'create_jwt_settings': 'create an organization-specific JWT settings model instance with API token TTL and enable flags', 'encode_truncated_jwt': 'encode a JWT payload into a truncated token string with header and payload only, no signature', 'encode_full_jwt': 'encode a JWT payload into a complete token string with header, payload, and signature', 'create_lsapi_token': 'create a long-lived LSAPIToken refresh token with organization-specific lifetime and truncated storage', 'create_truncated_token': 'initialize a TruncatedLSAPIToken from a header-payload-only JWT string with a dummy signature appended'}
```

## File: HumanSignal_label-studio/label_studio/jwt_auth/serializers.py

Prompts

```
['review the TokenAuthenticationPhaseout class that phases out legacy token auth and logs usage', 'test the TokenAuthenticationPhaseout.authenticate method with a mock request and feature flag', 'review the JWTAuthScheme OpenAPI extension class that documents token authentication', 'summarize the TokenAuthenticationPhaseout.authenticate method behavior and side effects', 'refactor the TokenAuthenticationPhaseout class to extract the legacy token check into a separate method', 'create an organization-specific JWT settings model instance with API token TTL and enable flags', 'encode a JWT payload into a truncated token string with header and payload only, no signature', 'encode a JWT payload into a complete token string with header, payload, and signature', 'create a long-lived LSAPIToken refresh token with organization-specific lifetime and truncated storage', 'initialize a TruncatedLSAPIToken from a header-payload-only JWT string with a dummy signature appended', 'create an LSA API token serializer that returns the full JWT string via SerializerMethodField', 'list LSA API tokens returning only the header/payload portion of each token', 'blacklist an LSA API token using TruncatedLSAPIToken as the token class', 'rotate an LSA API token by validating a refresh token and returning a new refresh token', 'retrieve JWT settings for the currently active organization using the JWTSettingsAPI view', 'update JWT settings for the currently active organization via POST to JWTSettingsAPI', 'list all non-expired non-blacklisted API tokens for the current user using LSAPITokenView', 'create a new API token for the current user via LSAPITokenView, rejecting if one already exists', 'refresh a JWT access token using a refresh token via DecoratedTokenRefreshView']
```

Usage

```
{'create_jwt_settings': 'create a JWT settings serializer to manage api_tokens_enabled and legacy_api_tokens_enabled flags', 'create_lsa_token': 'create an LSA API token serializer that returns the full JWT string via SerializerMethodField', 'list_lsa_tokens': 'list LSA API tokens returning only the header/payload portion of each token', 'blacklist_lsa_token': 'blacklist an LSA API token using TruncatedLSAPIToken as the token class', 'rotate_lsa_token': 'rotate an LSA API token by validating a refresh token and returning a new refresh token'}
```

## File: HumanSignal_label-studio/label_studio/jwt_auth/views.py

Prompts

```
['review the TokenAuthenticationPhaseout class that phases out legacy token auth and logs usage', 'test the TokenAuthenticationPhaseout.authenticate method with a mock request and feature flag', 'review the JWTAuthScheme OpenAPI extension class that documents token authentication', 'summarize the TokenAuthenticationPhaseout.authenticate method behavior and side effects', 'refactor the TokenAuthenticationPhaseout class to extract the legacy token check into a separate method', 'create an organization-specific JWT settings model instance with API token TTL and enable flags', 'encode a JWT payload into a truncated token string with header and payload only, no signature', 'encode a JWT payload into a complete token string with header, payload, and signature', 'create a long-lived LSAPIToken refresh token with organization-specific lifetime and truncated storage', 'initialize a TruncatedLSAPIToken from a header-payload-only JWT string with a dummy signature appended', 'create an LSA API token serializer that returns the full JWT string via SerializerMethodField', 'list LSA API tokens returning only the header/payload portion of each token', 'blacklist an LSA API token using TruncatedLSAPIToken as the token class', 'rotate an LSA API token by validating a refresh token and returning a new refresh token', 'retrieve JWT settings for the currently active organization using the JWTSettingsAPI view', 'update JWT settings for the currently active organization via POST to JWTSettingsAPI', 'list all non-expired non-blacklisted API tokens for the current user using LSAPITokenView', 'create a new API token for the current user via LSAPITokenView, rejecting if one already exists', 'refresh a JWT access token using a refresh token via DecoratedTokenRefreshView']
```

Usage

```
{'retrieve_jwt_settings': 'retrieve JWT settings for the currently active organization using the JWTSettingsAPI view', 'update_jwt_settings': 'update JWT settings for the currently active organization via POST to JWTSettingsAPI', 'list_api_tokens': 'list all non-expired non-blacklisted API tokens for the current user using LSAPITokenView', 'create_api_token': 'create a new API token for the current user via LSAPITokenView, rejecting if one already exists', 'refresh_jwt_token': 'refresh a JWT access token using a refresh token via DecoratedTokenRefreshView'}
```

