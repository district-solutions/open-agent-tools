# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/base_llm/realtime/http_transformation.py

Prompts

```
['build the provider API base URL from explicit api_base, litellm config, env var, or default', 'build the provider API key from explicit key, litellm config, env var, or empty string', 'build the full URL for POST /realtime/client_secrets endpoint call', 'build the full URL for POST /realtime/calls SDP exchange endpoint', 'build and merge request headers with auth and content-type for client_secrets call', 'test the BaseRealtimeConfig.validate_environment method to validate API headers and model configuration', 'build the BaseRealtimeConfig.get_complete_url method to construct the full API endpoint URL for a realtime model request', 'refactor the BaseRealtimeConfig.transform_realtime_request method to transform incoming realtime messages for a given model', 'review the BaseRealtimeConfig.transform_realtime_response method to transform realtime responses into typed dictionaries', 'summarize the BaseRealtimeConfig.session_configuration_request method to generate initial session setup configuration messages']
```

Usage

```
{'build_get_api_base_url': 'build the provider API base URL from explicit api_base, litellm config, env var, or default', 'build_get_api_key': 'build the provider API key from explicit key, litellm config, env var, or empty string', 'build_get_complete_url': 'build the full URL for POST /realtime/client_secrets endpoint call', 'build_get_realtime_calls_url': 'build the full URL for POST /realtime/calls SDP exchange endpoint', 'build_validate_environment_headers': 'build and merge request headers with auth and content-type for client_secrets call'}
```

## File: berriai_litellm/litellm/llms/base_llm/realtime/transformation.py

Prompts

```
['build the provider API base URL from explicit api_base, litellm config, env var, or default', 'build the provider API key from explicit key, litellm config, env var, or empty string', 'build the full URL for POST /realtime/client_secrets endpoint call', 'build the full URL for POST /realtime/calls SDP exchange endpoint', 'build and merge request headers with auth and content-type for client_secrets call', 'test the BaseRealtimeConfig.validate_environment method to validate API headers and model configuration', 'build the BaseRealtimeConfig.get_complete_url method to construct the full API endpoint URL for a realtime model request', 'refactor the BaseRealtimeConfig.transform_realtime_request method to transform incoming realtime messages for a given model', 'review the BaseRealtimeConfig.transform_realtime_response method to transform realtime responses into typed dictionaries', 'summarize the BaseRealtimeConfig.session_configuration_request method to generate initial session setup configuration messages']
```

Usage

```
{'test_BaseRealtimeConfig_validate_environment': 'test the BaseRealtimeConfig.validate_environment method to validate API headers and model configuration', 'build_BaseRealtimeConfig_get_complete_url': 'build the BaseRealtimeConfig.get_complete_url method to construct the full API endpoint URL for a realtime model request', 'refactor_BaseRealtimeConfig_transform_realtime_request': 'refactor the BaseRealtimeConfig.transform_realtime_request method to transform incoming realtime messages for a given model', 'review_BaseRealtimeConfig_transform_realtime_response': 'review the BaseRealtimeConfig.transform_realtime_response method to transform realtime responses into typed dictionaries', 'summarize_BaseRealtimeConfig_session_configuration_request': 'summarize the BaseRealtimeConfig.session_configuration_request method to generate initial session setup configuration messages'}
```

