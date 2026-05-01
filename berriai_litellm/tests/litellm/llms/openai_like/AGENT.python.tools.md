# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/tests/litellm/llms/openai_like/test_abliteration_provider.py

Prompts

```
['test that the abliteration provider is registered with the correct base URL and API key env variable', 'test that the abliteration config resolves the API key from the ABLITERATION_API_KEY environment variable', 'test that get_complete_url appends the chat completions endpoint to the abliteration base URL', 'review the JSONProviderRegistry get method to verify abliteration provider registration and configuration', 'review the create_config_class function to understand how it dynamically builds a config class from a provider definition', 'test that the assemblyai provider is registered with the correct base URL and API key env variable', 'test that the assemblyai config resolves the ASSEMBLYAI_API_KEY environment variable for the API key', 'test that get_complete_url appends the chat completions endpoint to the AssemblyAI base URL', 'test that get_llm_provider correctly resolves the assemblyai provider from a prefixed model string', 'test that ProviderConfigManager returns the correct chat config for the assemblyai provider']
```

Usage

```
{'test_abliteration_provider_registered': 'test that the abliteration provider is registered with the correct base URL and API key env variable', 'test_abliteration_resolves_env_api_key': 'test that the abliteration config resolves the API key from the ABLITERATION_API_KEY environment variable', 'test_abliteration_complete_url_appends_endpoint': 'test that get_complete_url appends the chat completions endpoint to the abliteration base URL', 'review_JSONProviderRegistry_get': 'review the JSONProviderRegistry get method to verify abliteration provider registration and configuration', 'review_create_config_class': 'review the create_config_class function to understand how it dynamically builds a config class from a provider definition'}
```

## File: berriai_litellm/tests/litellm/llms/openai_like/test_assemblyai_provider.py

Prompts

```
['test that the abliteration provider is registered with the correct base URL and API key env variable', 'test that the abliteration config resolves the API key from the ABLITERATION_API_KEY environment variable', 'test that get_complete_url appends the chat completions endpoint to the abliteration base URL', 'review the JSONProviderRegistry get method to verify abliteration provider registration and configuration', 'review the create_config_class function to understand how it dynamically builds a config class from a provider definition', 'test that the assemblyai provider is registered with the correct base URL and API key env variable', 'test that the assemblyai config resolves the ASSEMBLYAI_API_KEY environment variable for the API key', 'test that get_complete_url appends the chat completions endpoint to the AssemblyAI base URL', 'test that get_llm_provider correctly resolves the assemblyai provider from a prefixed model string', 'test that ProviderConfigManager returns the correct chat config for the assemblyai provider']
```

Usage

```
{'test_assemblyai_provider_registered': 'test that the assemblyai provider is registered with the correct base URL and API key env variable', 'test_assemblyai_resolves_env_api_key': 'test that the assemblyai config resolves the ASSEMBLYAI_API_KEY environment variable for the API key', 'test_assemblyai_complete_url_appends_endpoint': 'test that get_complete_url appends the chat completions endpoint to the AssemblyAI base URL', 'test_assemblyai_provider_resolution': 'test that get_llm_provider correctly resolves the assemblyai provider from a prefixed model string', 'test_assemblyai_provider_config_manager': 'test that ProviderConfigManager returns the correct chat config for the assemblyai provider'}
```

