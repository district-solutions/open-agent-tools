# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/tests/plugins/image_gen/test_openai_codex_provider.py

Prompts

```
['test the OpenAICodexImageGenProvider.name and display_name attributes return correct values', 'test the OpenAICodexImageGenProvider.default_model method returns gpt-image-2-medium', 'test the OpenAICodexImageGenProvider.list_models method returns three model tiers', 'test the OpenAICodexImageGenProvider.get_setup_schema method returns empty env_vars and free badge', 'test the OpenAICodexImageGenProvider.is_available method with and without codex access token', 'test the OpenAICodexImageGenProvider.generate method produces image with correct result fields', 'test the codex_plugin.register function calls register_image_gen_provider with the provider instance', 'test the OpenAIImageGenProvider class name, default model, and list_models API', 'test the OpenAIImageGenProvider is_available method with and without API key', 'test the _resolve_model function for env var override, fallback, and config file resolution', 'test the OpenAIImageGenProvider.generate method for b64 image saving, tier mapping, and aspect ratio', 'test the OpenAIImageGenProvider.generate method for empty prompt, API errors, empty response, and URL fallback', 'test the XAIImageGenProvider class name and display name properties', 'test the XAIImageGenProvider is_available method with and without API key', 'test the XAIImageGenProvider generate method for successful and error image generation', 'test the _resolve_model and _resolve_resolution config functions', 'test the register function that registers XAIImageGenProvider with the plugin context']
```

Usage

```
{'test_provider_name_and_display_name': 'test the OpenAICodexImageGenProvider.name and display_name attributes return correct values', 'test_provider_default_model': 'test the OpenAICodexImageGenProvider.default_model method returns gpt-image-2-medium', 'test_provider_list_models': 'test the OpenAICodexImageGenProvider.list_models method returns three model tiers', 'test_provider_setup_schema': 'test the OpenAICodexImageGenProvider.get_setup_schema method returns empty env_vars and free badge', 'test_provider_is_available': 'test the OpenAICodexImageGenProvider.is_available method with and without codex access token', 'test_provider_generate': 'test the OpenAICodexImageGenProvider.generate method produces image with correct result fields', 'test_provider_register': 'test the codex_plugin.register function calls register_image_gen_provider with the provider instance'}
```

## File: NousResearch_hermes-agent/tests/plugins/image_gen/test_openai_provider.py

Prompts

```
['test the OpenAICodexImageGenProvider.name and display_name attributes return correct values', 'test the OpenAICodexImageGenProvider.default_model method returns gpt-image-2-medium', 'test the OpenAICodexImageGenProvider.list_models method returns three model tiers', 'test the OpenAICodexImageGenProvider.get_setup_schema method returns empty env_vars and free badge', 'test the OpenAICodexImageGenProvider.is_available method with and without codex access token', 'test the OpenAICodexImageGenProvider.generate method produces image with correct result fields', 'test the codex_plugin.register function calls register_image_gen_provider with the provider instance', 'test the OpenAIImageGenProvider class name, default model, and list_models API', 'test the OpenAIImageGenProvider is_available method with and without API key', 'test the _resolve_model function for env var override, fallback, and config file resolution', 'test the OpenAIImageGenProvider.generate method for b64 image saving, tier mapping, and aspect ratio', 'test the OpenAIImageGenProvider.generate method for empty prompt, API errors, empty response, and URL fallback', 'test the XAIImageGenProvider class name and display name properties', 'test the XAIImageGenProvider is_available method with and without API key', 'test the XAIImageGenProvider generate method for successful and error image generation', 'test the _resolve_model and _resolve_resolution config functions', 'test the register function that registers XAIImageGenProvider with the plugin context']
```

Usage

```
{'test_OpenAIImageGenProvider_metadata': 'test the OpenAIImageGenProvider class name, default model, and list_models API', 'test_OpenAIImageGenProvider_availability': 'test the OpenAIImageGenProvider is_available method with and without API key', 'test_resolve_model': 'test the _resolve_model function for env var override, fallback, and config file resolution', 'test_OpenAIImageGenProvider_generate': 'test the OpenAIImageGenProvider.generate method for b64 image saving, tier mapping, and aspect ratio', 'test_generate_error_handling': 'test the OpenAIImageGenProvider.generate method for empty prompt, API errors, empty response, and URL fallback'}
```

## File: NousResearch_hermes-agent/tests/plugins/image_gen/test_xai_provider.py

Prompts

```
['test the OpenAICodexImageGenProvider.name and display_name attributes return correct values', 'test the OpenAICodexImageGenProvider.default_model method returns gpt-image-2-medium', 'test the OpenAICodexImageGenProvider.list_models method returns three model tiers', 'test the OpenAICodexImageGenProvider.get_setup_schema method returns empty env_vars and free badge', 'test the OpenAICodexImageGenProvider.is_available method with and without codex access token', 'test the OpenAICodexImageGenProvider.generate method produces image with correct result fields', 'test the codex_plugin.register function calls register_image_gen_provider with the provider instance', 'test the OpenAIImageGenProvider class name, default model, and list_models API', 'test the OpenAIImageGenProvider is_available method with and without API key', 'test the _resolve_model function for env var override, fallback, and config file resolution', 'test the OpenAIImageGenProvider.generate method for b64 image saving, tier mapping, and aspect ratio', 'test the OpenAIImageGenProvider.generate method for empty prompt, API errors, empty response, and URL fallback', 'test the XAIImageGenProvider class name and display name properties', 'test the XAIImageGenProvider is_available method with and without API key', 'test the XAIImageGenProvider generate method for successful and error image generation', 'test the _resolve_model and _resolve_resolution config functions', 'test the register function that registers XAIImageGenProvider with the plugin context']
```

Usage

```
{'test_XAIImageGenProvider_name': 'test the XAIImageGenProvider class name and display name properties', 'test_XAIImageGenProvider_is_available': 'test the XAIImageGenProvider is_available method with and without API key', 'test_XAIImageGenProvider_generate': 'test the XAIImageGenProvider generate method for successful and error image generation', 'test_resolve_model_resolution': 'test the _resolve_model and _resolve_resolution config functions', 'test_register_provider': 'test the register function that registers XAIImageGenProvider with the plugin context'}
```

