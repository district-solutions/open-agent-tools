# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/pl_coordinator/tests/test_bolt_graphapi_client.py

Prompts

```
['create a BoltGraphAPIClient instance with config dict and optional custom GraphAPI domain and version', 'create a private lift or attribution study instance via the GraphAPI using BoltPLGraphAPICreateInstanceArgs or BoltPAGraphAPICreateInstanceArgs', 'run the next stage or cancel the current stage of a Bolt study instance by instance ID', 'update a Bolt instance state and check whether a specific PCSFeature is enabled on the instance', 'get study data, attribution dataset info, or existing PA instances from the Facebook GraphAPI', 'test the TokenValidator to validate all common token rules including expiry, type, and scopes', 'test the TokenValidator validate_rule method against individual TokenValidationRule cases like TOKEN_EXPIRY and TOKEN_PERMISSIONS', 'test token validation rules for TOKEN_EXPIRY, TOKEN_DATA_ACCESS_EXPIRY, TOKEN_USER_TYPE, TOKEN_VALID, and TOKEN_PERMISSIONS', 'test that GraphAPITokenValidationError is raised when a token fails validation and trace logging is triggered', 'test the TokenValidator using mocked Graph API responses with custom debug token data and scopes']
```

Usage

```
{'create_bolt_graphapi_client': 'create a BoltGraphAPIClient instance with config dict and optional custom GraphAPI domain and version', 'create_instance_lift_or_attribution': 'create a private lift or attribution study instance via the GraphAPI using BoltPLGraphAPICreateInstanceArgs or BoltPAGraphAPICreateInstanceArgs', 'run_and_cancel_stage': 'run the next stage or cancel the current stage of a Bolt study instance by instance ID', 'update_instance_and_check_features': 'update a Bolt instance state and check whether a specific PCSFeature is enabled on the instance', 'get_study_and_dataset_data': 'get study data, attribution dataset info, or existing PA instances from the Facebook GraphAPI'}
```

## File: facebookresearch_fbpcs/fbpcs/pl_coordinator/tests/test_token_validator.py

Prompts

```
['create a BoltGraphAPIClient instance with config dict and optional custom GraphAPI domain and version', 'create a private lift or attribution study instance via the GraphAPI using BoltPLGraphAPICreateInstanceArgs or BoltPAGraphAPICreateInstanceArgs', 'run the next stage or cancel the current stage of a Bolt study instance by instance ID', 'update a Bolt instance state and check whether a specific PCSFeature is enabled on the instance', 'get study data, attribution dataset info, or existing PA instances from the Facebook GraphAPI', 'test the TokenValidator to validate all common token rules including expiry, type, and scopes', 'test the TokenValidator validate_rule method against individual TokenValidationRule cases like TOKEN_EXPIRY and TOKEN_PERMISSIONS', 'test token validation rules for TOKEN_EXPIRY, TOKEN_DATA_ACCESS_EXPIRY, TOKEN_USER_TYPE, TOKEN_VALID, and TOKEN_PERMISSIONS', 'test that GraphAPITokenValidationError is raised when a token fails validation and trace logging is triggered', 'test the TokenValidator using mocked Graph API responses with custom debug token data and scopes']
```

Usage

```
{'test_token_common_rules': 'test the TokenValidator to validate all common token rules including expiry, type, and scopes', 'test_token_single_common_rule': 'test the TokenValidator validate_rule method against individual TokenValidationRule cases like TOKEN_EXPIRY and TOKEN_PERMISSIONS', 'test_token_validation_rules': 'test token validation rules for TOKEN_EXPIRY, TOKEN_DATA_ACCESS_EXPIRY, TOKEN_USER_TYPE, TOKEN_VALID, and TOKEN_PERMISSIONS', 'test_graph_api_token_validation_error': 'test that GraphAPITokenValidationError is raised when a token fails validation and trace logging is triggered', 'test_mock_graph_api_response': 'test the TokenValidator using mocked Graph API responses with custom debug token data and scopes'}
```

