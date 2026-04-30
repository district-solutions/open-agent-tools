# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/openai_like/dynamic_config.py

Prompts

```
['create a dynamic config class from a SimpleProviderConfig for OpenAI-compatible chat completions', 'create a dynamic responses API config class from a SimpleProviderConfig with caching', 'build a complete chat completions URL from api_base and provider configuration', 'build a complete responses API URL from api_base and provider configuration', 'map OpenAI parameters to provider-specific params with temperature constraints and function calling filtering', 'create a SimpleProviderConfig instance from a provider slug and configuration dictionary', 'build a JSON provider registry that loads provider configurations from a providers.json file', 'test the JSONProviderRegistry.get method to retrieve a provider configuration by slug', 'test the JSONProviderRegistry.exists method to check if a provider slug is registered', 'test the JSONProviderRegistry.supports_responses_api method to check if a provider supports the Responses API', 'list all registered provider slugs from the JSONProviderRegistry']
```

Usage

```
{'create_config_class': 'create a dynamic config class from a SimpleProviderConfig for OpenAI-compatible chat completions', 'create_responses_config_class': 'create a dynamic responses API config class from a SimpleProviderConfig with caching', 'get_complete_url_chat': 'build a complete chat completions URL from api_base and provider configuration', 'get_complete_url_responses': 'build a complete responses API URL from api_base and provider configuration', 'map_openai_params': 'map OpenAI parameters to provider-specific params with temperature constraints and function calling filtering'}
```

## File: berriai_litellm/litellm/llms/openai_like/json_loader.py

Prompts

```
['create a dynamic config class from a SimpleProviderConfig for OpenAI-compatible chat completions', 'create a dynamic responses API config class from a SimpleProviderConfig with caching', 'build a complete chat completions URL from api_base and provider configuration', 'build a complete responses API URL from api_base and provider configuration', 'map OpenAI parameters to provider-specific params with temperature constraints and function calling filtering', 'create a SimpleProviderConfig instance from a provider slug and configuration dictionary', 'build a JSON provider registry that loads provider configurations from a providers.json file', 'test the JSONProviderRegistry.get method to retrieve a provider configuration by slug', 'test the JSONProviderRegistry.exists method to check if a provider slug is registered', 'test the JSONProviderRegistry.supports_responses_api method to check if a provider supports the Responses API', 'list all registered provider slugs from the JSONProviderRegistry']
```

Usage

```
{'create_simple_provider_config': 'create a SimpleProviderConfig instance from a provider slug and configuration dictionary', 'build_json_provider_registry': 'build a JSON provider registry that loads provider configurations from a providers.json file', 'test_json_provider_registry_get': 'test the JSONProviderRegistry.get method to retrieve a provider configuration by slug', 'test_json_provider_registry_exists': 'test the JSONProviderRegistry.exists method to check if a provider slug is registered', 'test_json_provider_registry_supports_responses_api': 'test the JSONProviderRegistry.supports_responses_api method to check if a provider supports the Responses API', 'list_json_provider_registry': 'list all registered provider slugs from the JSONProviderRegistry'}
```

