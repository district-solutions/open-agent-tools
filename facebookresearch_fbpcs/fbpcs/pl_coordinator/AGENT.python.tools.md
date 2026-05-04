# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/pl_coordinator/bolt_graphapi_client.py

Prompts

```
['create a BoltGraphAPIClient instance with config dict and optional graphapi version and domain', 'create a private lift or attribution study instance via GraphAPI and return the instance id', 'run the next stage for a given study instance id using the GraphAPI client', 'update and retrieve the current BoltState including status, server IPs, and TLS certificates for an instance', 'get study data fields from the GraphAPI endpoint for a given study id', 'create a decorator that catches exceptions and exits with proper exit codes', 'create an enum defining custom exit codes for the one command runner', 'raise a base exception with message, cause, remediation, and exit code', 'raise a Graph API token validation error using make_error with a validation rule', 'raise an incorrect version error using make_error with instance id and tier info', 'run a private lift study with config, study_id, objective_ids, and input_paths', 'run a private lift study asynchronously with optional dry_run and stage_timeout_override', 'run BoltJobs in parallel using BoltRunner with publisher and partner clients', 'get a list of runnable MPC objective IDs for a given study', 'validate that objective_ids and input_paths have no duplicates and match in length', 'run all TokenValidationRule checkers against a DebugTokenData instance to validate a Facebook token', 'create a DebugTokenData dataclass instance with type, is_valid, expires_at, scopes, and data_access_expires_at fields', "test the user_type_checker function to validate a token's user type is USER or SYSTEM_USER", 'test the permission_checker function to verify a token has all required Facebook API scopes', 'review the TokenValidationRule enum and its five COMMON rule types for token validation', 'create a TokenValidator and call validate_common_rules to check all common token validation rules', 'create a TokenValidator and call validate_rule with a specific TokenValidationRule to validate one rule', 'use TokenValidator _load_data method to fetch and parse debug token data from the Graph API client', 'review the TokenValidator class and its token validation logic for Graph API tokens', 'refactor the TokenValidator validate_rule method to improve error handling and trace logging']
```

Usage

```
{'create_graphapi_client': 'create a BoltGraphAPIClient instance with config dict and optional graphapi version and domain', 'create_instance_pl_pa': 'create a private lift or attribution study instance via GraphAPI and return the instance id', 'run_stage_instance': 'run the next stage for a given study instance id using the GraphAPI client', 'update_instance_status': 'update and retrieve the current BoltState including status, server IPs, and TLS certificates for an instance', 'get_study_data': 'get study data fields from the GraphAPI endpoint for a given study id'}
```

## File: facebookresearch_fbpcs/fbpcs/pl_coordinator/exceptions.py

Prompts

```
['create a BoltGraphAPIClient instance with config dict and optional graphapi version and domain', 'create a private lift or attribution study instance via GraphAPI and return the instance id', 'run the next stage for a given study instance id using the GraphAPI client', 'update and retrieve the current BoltState including status, server IPs, and TLS certificates for an instance', 'get study data fields from the GraphAPI endpoint for a given study id', 'create a decorator that catches exceptions and exits with proper exit codes', 'create an enum defining custom exit codes for the one command runner', 'raise a base exception with message, cause, remediation, and exit code', 'raise a Graph API token validation error using make_error with a validation rule', 'raise an incorrect version error using make_error with instance id and tier info', 'run a private lift study with config, study_id, objective_ids, and input_paths', 'run a private lift study asynchronously with optional dry_run and stage_timeout_override', 'run BoltJobs in parallel using BoltRunner with publisher and partner clients', 'get a list of runnable MPC objective IDs for a given study', 'validate that objective_ids and input_paths have no duplicates and match in length', 'run all TokenValidationRule checkers against a DebugTokenData instance to validate a Facebook token', 'create a DebugTokenData dataclass instance with type, is_valid, expires_at, scopes, and data_access_expires_at fields', "test the user_type_checker function to validate a token's user type is USER or SYSTEM_USER", 'test the permission_checker function to verify a token has all required Facebook API scopes', 'review the TokenValidationRule enum and its five COMMON rule types for token validation', 'create a TokenValidator and call validate_common_rules to check all common token validation rules', 'create a TokenValidator and call validate_rule with a specific TokenValidationRule to validate one rule', 'use TokenValidator _load_data method to fetch and parse debug token data from the Graph API client', 'review the TokenValidator class and its token validation logic for Graph API tokens', 'refactor the TokenValidator validate_rule method to improve error handling and trace logging']
```

Usage

```
{'create_sys_exit_after_decorator': 'create a decorator that catches exceptions and exits with proper exit codes', 'create_OneCommandRunnerExitCode_enum': 'create an enum defining custom exit codes for the one command runner', 'raise_OneCommandRunnerBaseException': 'raise a base exception with message, cause, remediation, and exit code', 'raise_GraphAPITokenValidationError': 'raise a Graph API token validation error using make_error with a validation rule', 'raise_IncorrectVersionError': 'raise an incorrect version error using make_error with instance id and tier info'}
```

## File: facebookresearch_fbpcs/fbpcs/pl_coordinator/pl_study_runner.py

Prompts

```
['create a BoltGraphAPIClient instance with config dict and optional graphapi version and domain', 'create a private lift or attribution study instance via GraphAPI and return the instance id', 'run the next stage for a given study instance id using the GraphAPI client', 'update and retrieve the current BoltState including status, server IPs, and TLS certificates for an instance', 'get study data fields from the GraphAPI endpoint for a given study id', 'create a decorator that catches exceptions and exits with proper exit codes', 'create an enum defining custom exit codes for the one command runner', 'raise a base exception with message, cause, remediation, and exit code', 'raise a Graph API token validation error using make_error with a validation rule', 'raise an incorrect version error using make_error with instance id and tier info', 'run a private lift study with config, study_id, objective_ids, and input_paths', 'run a private lift study asynchronously with optional dry_run and stage_timeout_override', 'run BoltJobs in parallel using BoltRunner with publisher and partner clients', 'get a list of runnable MPC objective IDs for a given study', 'validate that objective_ids and input_paths have no duplicates and match in length', 'run all TokenValidationRule checkers against a DebugTokenData instance to validate a Facebook token', 'create a DebugTokenData dataclass instance with type, is_valid, expires_at, scopes, and data_access_expires_at fields', "test the user_type_checker function to validate a token's user type is USER or SYSTEM_USER", 'test the permission_checker function to verify a token has all required Facebook API scopes', 'review the TokenValidationRule enum and its five COMMON rule types for token validation', 'create a TokenValidator and call validate_common_rules to check all common token validation rules', 'create a TokenValidator and call validate_rule with a specific TokenValidationRule to validate one rule', 'use TokenValidator _load_data method to fetch and parse debug token data from the Graph API client', 'review the TokenValidator class and its token validation logic for Graph API tokens', 'refactor the TokenValidator validate_rule method to improve error handling and trace logging']
```

Usage

```
{'run_study': 'run a private lift study with config, study_id, objective_ids, and input_paths', 'run_study_async': 'run a private lift study asynchronously with optional dry_run and stage_timeout_override', 'run_bolt': 'run BoltJobs in parallel using BoltRunner with publisher and partner clients', 'get_runnable_objectives': 'get a list of runnable MPC objective IDs for a given study', 'validate_input': 'validate that objective_ids and input_paths have no duplicates and match in length'}
```

## File: facebookresearch_fbpcs/fbpcs/pl_coordinator/token_validation_rules.py

Prompts

```
['create a BoltGraphAPIClient instance with config dict and optional graphapi version and domain', 'create a private lift or attribution study instance via GraphAPI and return the instance id', 'run the next stage for a given study instance id using the GraphAPI client', 'update and retrieve the current BoltState including status, server IPs, and TLS certificates for an instance', 'get study data fields from the GraphAPI endpoint for a given study id', 'create a decorator that catches exceptions and exits with proper exit codes', 'create an enum defining custom exit codes for the one command runner', 'raise a base exception with message, cause, remediation, and exit code', 'raise a Graph API token validation error using make_error with a validation rule', 'raise an incorrect version error using make_error with instance id and tier info', 'run a private lift study with config, study_id, objective_ids, and input_paths', 'run a private lift study asynchronously with optional dry_run and stage_timeout_override', 'run BoltJobs in parallel using BoltRunner with publisher and partner clients', 'get a list of runnable MPC objective IDs for a given study', 'validate that objective_ids and input_paths have no duplicates and match in length', 'run all TokenValidationRule checkers against a DebugTokenData instance to validate a Facebook token', 'create a DebugTokenData dataclass instance with type, is_valid, expires_at, scopes, and data_access_expires_at fields', "test the user_type_checker function to validate a token's user type is USER or SYSTEM_USER", 'test the permission_checker function to verify a token has all required Facebook API scopes', 'review the TokenValidationRule enum and its five COMMON rule types for token validation', 'create a TokenValidator and call validate_common_rules to check all common token validation rules', 'create a TokenValidator and call validate_rule with a specific TokenValidationRule to validate one rule', 'use TokenValidator _load_data method to fetch and parse debug token data from the Graph API client', 'review the TokenValidator class and its token validation logic for Graph API tokens', 'refactor the TokenValidator validate_rule method to improve error handling and trace logging']
```

Usage

```
{'run_token_validation_rules': 'run all TokenValidationRule checkers against a DebugTokenData instance to validate a Facebook token', 'create_debug_token_data': 'create a DebugTokenData dataclass instance with type, is_valid, expires_at, scopes, and data_access_expires_at fields', 'test_user_type_checker': "test the user_type_checker function to validate a token's user type is USER or SYSTEM_USER", 'test_permission_checker': 'test the permission_checker function to verify a token has all required Facebook API scopes', 'review_token_validation_rule_enum': 'review the TokenValidationRule enum and its five COMMON rule types for token validation'}
```

## File: facebookresearch_fbpcs/fbpcs/pl_coordinator/token_validator.py

Prompts

```
['create a BoltGraphAPIClient instance with config dict and optional graphapi version and domain', 'create a private lift or attribution study instance via GraphAPI and return the instance id', 'run the next stage for a given study instance id using the GraphAPI client', 'update and retrieve the current BoltState including status, server IPs, and TLS certificates for an instance', 'get study data fields from the GraphAPI endpoint for a given study id', 'create a decorator that catches exceptions and exits with proper exit codes', 'create an enum defining custom exit codes for the one command runner', 'raise a base exception with message, cause, remediation, and exit code', 'raise a Graph API token validation error using make_error with a validation rule', 'raise an incorrect version error using make_error with instance id and tier info', 'run a private lift study with config, study_id, objective_ids, and input_paths', 'run a private lift study asynchronously with optional dry_run and stage_timeout_override', 'run BoltJobs in parallel using BoltRunner with publisher and partner clients', 'get a list of runnable MPC objective IDs for a given study', 'validate that objective_ids and input_paths have no duplicates and match in length', 'run all TokenValidationRule checkers against a DebugTokenData instance to validate a Facebook token', 'create a DebugTokenData dataclass instance with type, is_valid, expires_at, scopes, and data_access_expires_at fields', "test the user_type_checker function to validate a token's user type is USER or SYSTEM_USER", 'test the permission_checker function to verify a token has all required Facebook API scopes', 'review the TokenValidationRule enum and its five COMMON rule types for token validation', 'create a TokenValidator and call validate_common_rules to check all common token validation rules', 'create a TokenValidator and call validate_rule with a specific TokenValidationRule to validate one rule', 'use TokenValidator _load_data method to fetch and parse debug token data from the Graph API client', 'review the TokenValidator class and its token validation logic for Graph API tokens', 'refactor the TokenValidator validate_rule method to improve error handling and trace logging']
```

Usage

```
{'validate_common_token_rules': 'create a TokenValidator and call validate_common_rules to check all common token validation rules', 'validate_single_token_rule': 'create a TokenValidator and call validate_rule with a specific TokenValidationRule to validate one rule', 'load_debug_token_data': 'use TokenValidator _load_data method to fetch and parse debug token data from the Graph API client', 'review_TOKENVALIDATOR_CLASS': 'review the TokenValidator class and its token validation logic for Graph API tokens', 'refactor_TOKENVALIDATOR_ERROR_HANDLING': 'refactor the TokenValidator validate_rule method to improve error handling and trace logging'}
```

