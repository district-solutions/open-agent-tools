# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/core/feature_flags/base.py

Prompts

```
['test the flag_set function to check if a LaunchDarkly feature flag is enabled for a given user with optional override and organization support', 'test the all_flags function to return a dictionary of all feature flag states for a user including environment variables and stale flags', 'test the get_feature_file_path function to resolve the feature flags YAML file path from settings or package internals', 'review the flag_set function to verify stale flag handling, environment variable override, and LaunchDarkly client variation fallback', 'summarize the all_flags function that merges LaunchDarkly flag states, environment variables with ff_ prefixes, and stale feature flags into a single dictionary', 'create a user repr dict from a user object with email, key, and organization info', 'create an owner dict from an organization object with email and organization id']
```

Usage

```
{'test_flag_set': 'test the flag_set function to check if a LaunchDarkly feature flag is enabled for a given user with optional override and organization support', 'test_all_flags': 'test the all_flags function to return a dictionary of all feature flag states for a user including environment variables and stale flags', 'test_get_feature_file_path': 'test the get_feature_file_path function to resolve the feature flags YAML file path from settings or package internals', 'review_flag_set': 'review the flag_set function to verify stale flag handling, environment variable override, and LaunchDarkly client variation fallback', 'summarize_all_flags': 'summarize the all_flags function that merges LaunchDarkly flag states, environment variables with ff_ prefixes, and stale feature flags into a single dictionary'}
```

## File: HumanSignal_label-studio/label_studio/core/feature_flags/utils.py

Prompts

```
['test the flag_set function to check if a LaunchDarkly feature flag is enabled for a given user with optional override and organization support', 'test the all_flags function to return a dictionary of all feature flag states for a user including environment variables and stale flags', 'test the get_feature_file_path function to resolve the feature flags YAML file path from settings or package internals', 'review the flag_set function to verify stale flag handling, environment variable override, and LaunchDarkly client variation fallback', 'summarize the all_flags function that merges LaunchDarkly flag states, environment variables with ff_ prefixes, and stale feature flags into a single dictionary', 'create a user repr dict from a user object with email, key, and organization info', 'create an owner dict from an organization object with email and organization id']
```

Usage

```
{'create_get_user_repr': 'create a user repr dict from a user object with email, key, and organization info', 'create_get_user_repr_from_organization': 'create an owner dict from an organization object with email and organization id'}
```

