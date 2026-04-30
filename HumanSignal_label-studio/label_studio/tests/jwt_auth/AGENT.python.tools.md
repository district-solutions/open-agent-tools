# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/tests/jwt_auth/test_auth.py

Prompts

```
['test legacy token authentication logging when legacy_api_tokens_enabled is true', 'test that no basic auth logging occurs when legacy token auth is disabled', 'test that users with legacy token auth disabled receive 401 unauthorized', 'create a user with configurable api_tokens_enabled and legacy_api_tokens_enabled settings', 'test LSAPIToken.for_user to generate JWT access tokens for a user', 'test that requests without an auth header return HTTP 401 unauthorized', 'test that a valid JWT bearer token authenticates the user and returns HTTP 200', 'test that a user with JWT auth disabled cannot authenticate with a JWT token', 'test that a user with both JWT and legacy token auth enabled can use either method', 'test that a JWT token becomes invalid after the associated user is deleted', 'test LSTokenBackend.encode returns a partial JWT with only header and payload, no signature', 'test LSTokenBackend.encode_full returns a complete JWT with header, payload, and signature', 'test LSAPIToken.for_user creates a token stored as truncated format without signature in the database', 'test LSAPIToken.blacklist blacklists a token and LSAPIToken.check_blacklist raises TokenError', 'test LSAPIToken.get_full_jwt returns the complete three-part JWT including the signature', 'test the blacklist view endpoint returns 404 for already blacklisted tokens and 204 for valid tokens', 'test the create token endpoint returns 201 for first token and 409 when a valid token already exists', 'test the rotate token endpoint successfully rotates refresh tokens and rejects expired or reused ones', 'test the LSAPIToken blacklist method and check_blacklist validation for JWT refresh tokens', 'test the create_user_with_token_settings utility for enabling API token authentication', 'refactor the create_user_with_token_settings function to accept a single boolean or dict for token settings']
```

Usage

```
{'test_legacy_token_auth_logging': 'test legacy token authentication logging when legacy_api_tokens_enabled is true', 'test_jwt_no_logging': 'test that no basic auth logging occurs when legacy token auth is disabled', 'test_legacy_token_rejected': 'test that users with legacy token auth disabled receive 401 unauthorized', 'create_user_with_token_settings': 'create a user with configurable api_tokens_enabled and legacy_api_tokens_enabled settings', 'test_lsa_token_for_user': 'test LSAPIToken.for_user to generate JWT access tokens for a user'}
```

## File: HumanSignal_label-studio/label_studio/tests/jwt_auth/test_middleware.py

Prompts

```
['test legacy token authentication logging when legacy_api_tokens_enabled is true', 'test that no basic auth logging occurs when legacy token auth is disabled', 'test that users with legacy token auth disabled receive 401 unauthorized', 'create a user with configurable api_tokens_enabled and legacy_api_tokens_enabled settings', 'test LSAPIToken.for_user to generate JWT access tokens for a user', 'test that requests without an auth header return HTTP 401 unauthorized', 'test that a valid JWT bearer token authenticates the user and returns HTTP 200', 'test that a user with JWT auth disabled cannot authenticate with a JWT token', 'test that a user with both JWT and legacy token auth enabled can use either method', 'test that a JWT token becomes invalid after the associated user is deleted', 'test LSTokenBackend.encode returns a partial JWT with only header and payload, no signature', 'test LSTokenBackend.encode_full returns a complete JWT with header, payload, and signature', 'test LSAPIToken.for_user creates a token stored as truncated format without signature in the database', 'test LSAPIToken.blacklist blacklists a token and LSAPIToken.check_blacklist raises TokenError', 'test LSAPIToken.get_full_jwt returns the complete three-part JWT including the signature', 'test the blacklist view endpoint returns 404 for already blacklisted tokens and 204 for valid tokens', 'test the create token endpoint returns 201 for first token and 409 when a valid token already exists', 'test the rotate token endpoint successfully rotates refresh tokens and rejects expired or reused ones', 'test the LSAPIToken blacklist method and check_blacklist validation for JWT refresh tokens', 'test the create_user_with_token_settings utility for enabling API token authentication', 'refactor the create_user_with_token_settings function to accept a single boolean or dict for token settings']
```

Usage

```
{'test_request_without_auth_header_returns_401': 'test that requests without an auth header return HTTP 401 unauthorized', 'test_request_with_valid_token_returns_authenticated_user': 'test that a valid JWT bearer token authenticates the user and returns HTTP 200', 'test_jwt_token_auth_disabled_user_cannot_use_jwt_token': 'test that a user with JWT auth disabled cannot authenticate with a JWT token', 'test_user_with_both_auth_enabled_can_use_both_methods': 'test that a user with both JWT and legacy token auth enabled can use either method', 'test_jwt_token_invalid_after_user_deleted': 'test that a JWT token becomes invalid after the associated user is deleted'}
```

## File: HumanSignal_label-studio/label_studio/tests/jwt_auth/test_models.py

Prompts

```
['test legacy token authentication logging when legacy_api_tokens_enabled is true', 'test that no basic auth logging occurs when legacy token auth is disabled', 'test that users with legacy token auth disabled receive 401 unauthorized', 'create a user with configurable api_tokens_enabled and legacy_api_tokens_enabled settings', 'test LSAPIToken.for_user to generate JWT access tokens for a user', 'test that requests without an auth header return HTTP 401 unauthorized', 'test that a valid JWT bearer token authenticates the user and returns HTTP 200', 'test that a user with JWT auth disabled cannot authenticate with a JWT token', 'test that a user with both JWT and legacy token auth enabled can use either method', 'test that a JWT token becomes invalid after the associated user is deleted', 'test LSTokenBackend.encode returns a partial JWT with only header and payload, no signature', 'test LSTokenBackend.encode_full returns a complete JWT with header, payload, and signature', 'test LSAPIToken.for_user creates a token stored as truncated format without signature in the database', 'test LSAPIToken.blacklist blacklists a token and LSAPIToken.check_blacklist raises TokenError', 'test LSAPIToken.get_full_jwt returns the complete three-part JWT including the signature', 'test the blacklist view endpoint returns 404 for already blacklisted tokens and 204 for valid tokens', 'test the create token endpoint returns 201 for first token and 409 when a valid token already exists', 'test the rotate token endpoint successfully rotates refresh tokens and rejects expired or reused ones', 'test the LSAPIToken blacklist method and check_blacklist validation for JWT refresh tokens', 'test the create_user_with_token_settings utility for enabling API token authentication', 'refactor the create_user_with_token_settings function to accept a single boolean or dict for token settings']
```

Usage

```
{'test_LSTokenBackend_encode': 'test LSTokenBackend.encode returns a partial JWT with only header and payload, no signature', 'test_LSTokenBackend_encode_full': 'test LSTokenBackend.encode_full returns a complete JWT with header, payload, and signature', 'test_LSAPIToken_for_user': 'test LSAPIToken.for_user creates a token stored as truncated format without signature in the database', 'test_LSAPIToken_blacklist': 'test LSAPIToken.blacklist blacklists a token and LSAPIToken.check_blacklist raises TokenError', 'test_LSAPIToken_get_full_jwt': 'test LSAPIToken.get_full_jwt returns the complete three-part JWT including the signature'}
```

## File: HumanSignal_label-studio/label_studio/tests/jwt_auth/test_views.py

Prompts

```
['test legacy token authentication logging when legacy_api_tokens_enabled is true', 'test that no basic auth logging occurs when legacy token auth is disabled', 'test that users with legacy token auth disabled receive 401 unauthorized', 'create a user with configurable api_tokens_enabled and legacy_api_tokens_enabled settings', 'test LSAPIToken.for_user to generate JWT access tokens for a user', 'test that requests without an auth header return HTTP 401 unauthorized', 'test that a valid JWT bearer token authenticates the user and returns HTTP 200', 'test that a user with JWT auth disabled cannot authenticate with a JWT token', 'test that a user with both JWT and legacy token auth enabled can use either method', 'test that a JWT token becomes invalid after the associated user is deleted', 'test LSTokenBackend.encode returns a partial JWT with only header and payload, no signature', 'test LSTokenBackend.encode_full returns a complete JWT with header, payload, and signature', 'test LSAPIToken.for_user creates a token stored as truncated format without signature in the database', 'test LSAPIToken.blacklist blacklists a token and LSAPIToken.check_blacklist raises TokenError', 'test LSAPIToken.get_full_jwt returns the complete three-part JWT including the signature', 'test the blacklist view endpoint returns 404 for already blacklisted tokens and 204 for valid tokens', 'test the create token endpoint returns 201 for first token and 409 when a valid token already exists', 'test the rotate token endpoint successfully rotates refresh tokens and rejects expired or reused ones', 'test the LSAPIToken blacklist method and check_blacklist validation for JWT refresh tokens', 'test the create_user_with_token_settings utility for enabling API token authentication', 'refactor the create_user_with_token_settings function to accept a single boolean or dict for token settings']
```

Usage

```
{'test_blacklist_view': 'test the blacklist view endpoint returns 404 for already blacklisted tokens and 204 for valid tokens', 'test_create_token': 'test the create token endpoint returns 201 for first token and 409 when a valid token already exists', 'test_rotate_token': 'test the rotate token endpoint successfully rotates refresh tokens and rejects expired or reused ones', 'test_blacklist_token_model': 'test the LSAPIToken blacklist method and check_blacklist validation for JWT refresh tokens', 'test_create_user_with_token_settings': 'test the create_user_with_token_settings utility for enabling API token authentication'}
```

## File: HumanSignal_label-studio/label_studio/tests/jwt_auth/utils.py

Prompts

```
['test legacy token authentication logging when legacy_api_tokens_enabled is true', 'test that no basic auth logging occurs when legacy token auth is disabled', 'test that users with legacy token auth disabled receive 401 unauthorized', 'create a user with configurable api_tokens_enabled and legacy_api_tokens_enabled settings', 'test LSAPIToken.for_user to generate JWT access tokens for a user', 'test that requests without an auth header return HTTP 401 unauthorized', 'test that a valid JWT bearer token authenticates the user and returns HTTP 200', 'test that a user with JWT auth disabled cannot authenticate with a JWT token', 'test that a user with both JWT and legacy token auth enabled can use either method', 'test that a JWT token becomes invalid after the associated user is deleted', 'test LSTokenBackend.encode returns a partial JWT with only header and payload, no signature', 'test LSTokenBackend.encode_full returns a complete JWT with header, payload, and signature', 'test LSAPIToken.for_user creates a token stored as truncated format without signature in the database', 'test LSAPIToken.blacklist blacklists a token and LSAPIToken.check_blacklist raises TokenError', 'test LSAPIToken.get_full_jwt returns the complete three-part JWT including the signature', 'test the blacklist view endpoint returns 404 for already blacklisted tokens and 204 for valid tokens', 'test the create token endpoint returns 201 for first token and 409 when a valid token already exists', 'test the rotate token endpoint successfully rotates refresh tokens and rejects expired or reused ones', 'test the LSAPIToken blacklist method and check_blacklist validation for JWT refresh tokens', 'test the create_user_with_token_settings utility for enabling API token authentication', 'refactor the create_user_with_token_settings function to accept a single boolean or dict for token settings']
```

Usage

```
{'create_user_with_token_settings': "create a test user with specified JWT api token and legacy api token settings for the user's organization", 'test_create_user_with_token_settings': 'test the create_user_with_token_settings function with api_tokens_enabled=True and legacy_api_tokens_enabled=False', 'refactor_create_user_with_token_settings': 'refactor the create_user_with_token_settings function to accept a single boolean or dict for token settings'}
```

