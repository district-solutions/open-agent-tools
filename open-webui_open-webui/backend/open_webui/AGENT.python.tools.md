# Agent Python Tools

- repo: open-webui/open-webui
- repo_uri: https://github.com/open-webui/open-webui

## File: open-webui_open-webui/backend/open_webui/config.py

Prompts

```
['create a PersistentConfig instance to manage a persistent configuration value with environment variable fallback', 'build an AppConfig instance with Redis support for distributed configuration state management', 'test the load_oauth_providers function to register OAuth providers like Google, Microsoft, GitHub, OIDC, and Feishu', 'run get_config to retrieve the application configuration dictionary from the database', 'refactor save_config to persist a configuration dictionary to the database and update registered PersistentConfig entries', 'load a function module by its pipe id and inject valves configuration from the database', 'retrieve all active pipe functions as model entries, including manifold sub-pipes and user valve flags', 'execute a pipe function with form data, tools, and user context, returning streamed or blocking chat completion', 'test loading a function module by id with valves and user valves properly injected', 'review the chat completion generator that handles streaming, async generators, and error propagation for pipe functions', 'run the chat_completion endpoint to generate AI chat completions with streaming support and model access control', 'test the get_models endpoint that returns filtered available AI models accessible to the authenticated user', 'test the embeddings endpoint that generates OpenAI-compatible embeddings for text inputs', 'run the get_app_config endpoint to retrieve application configuration, feature flags, and OAuth provider settings', 'test the healthcheck endpoint that verifies the Open WebUI server is running and responsive']
```

Usage

```
{'create_PersistentConfig': 'create a PersistentConfig instance to manage a persistent configuration value with environment variable fallback', 'build_AppConfig': 'build an AppConfig instance with Redis support for distributed configuration state management', 'test_load_oauth_providers': 'test the load_oauth_providers function to register OAuth providers like Google, Microsoft, GitHub, OIDC, and Feishu', 'run_get_config': 'run get_config to retrieve the application configuration dictionary from the database', 'refactor_save_config': 'refactor save_config to persist a configuration dictionary to the database and update registered PersistentConfig entries'}
```

## File: open-webui_open-webui/backend/open_webui/functions.py

Prompts

```
['create a PersistentConfig instance to manage a persistent configuration value with environment variable fallback', 'build an AppConfig instance with Redis support for distributed configuration state management', 'test the load_oauth_providers function to register OAuth providers like Google, Microsoft, GitHub, OIDC, and Feishu', 'run get_config to retrieve the application configuration dictionary from the database', 'refactor save_config to persist a configuration dictionary to the database and update registered PersistentConfig entries', 'load a function module by its pipe id and inject valves configuration from the database', 'retrieve all active pipe functions as model entries, including manifold sub-pipes and user valve flags', 'execute a pipe function with form data, tools, and user context, returning streamed or blocking chat completion', 'test loading a function module by id with valves and user valves properly injected', 'review the chat completion generator that handles streaming, async generators, and error propagation for pipe functions', 'run the chat_completion endpoint to generate AI chat completions with streaming support and model access control', 'test the get_models endpoint that returns filtered available AI models accessible to the authenticated user', 'test the embeddings endpoint that generates OpenAI-compatible embeddings for text inputs', 'run the get_app_config endpoint to retrieve application configuration, feature flags, and OAuth provider settings', 'test the healthcheck endpoint that verifies the Open WebUI server is running and responsive']
```

Usage

```
{'get_function_module_by_id': 'load a function module by its pipe id and inject valves configuration from the database', 'get_function_models': 'retrieve all active pipe functions as model entries, including manifold sub-pipes and user valve flags', 'run_generate_function_chat_completion': 'execute a pipe function with form data, tools, and user context, returning streamed or blocking chat completion', 'test_get_function_module_by_id': 'test loading a function module by id with valves and user valves properly injected', 'review_generate_function_chat_completion': 'review the chat completion generator that handles streaming, async generators, and error propagation for pipe functions'}
```

## File: open-webui_open-webui/backend/open_webui/main.py

Prompts

```
['create a PersistentConfig instance to manage a persistent configuration value with environment variable fallback', 'build an AppConfig instance with Redis support for distributed configuration state management', 'test the load_oauth_providers function to register OAuth providers like Google, Microsoft, GitHub, OIDC, and Feishu', 'run get_config to retrieve the application configuration dictionary from the database', 'refactor save_config to persist a configuration dictionary to the database and update registered PersistentConfig entries', 'load a function module by its pipe id and inject valves configuration from the database', 'retrieve all active pipe functions as model entries, including manifold sub-pipes and user valve flags', 'execute a pipe function with form data, tools, and user context, returning streamed or blocking chat completion', 'test loading a function module by id with valves and user valves properly injected', 'review the chat completion generator that handles streaming, async generators, and error propagation for pipe functions', 'run the chat_completion endpoint to generate AI chat completions with streaming support and model access control', 'test the get_models endpoint that returns filtered available AI models accessible to the authenticated user', 'test the embeddings endpoint that generates OpenAI-compatible embeddings for text inputs', 'run the get_app_config endpoint to retrieve application configuration, feature flags, and OAuth provider settings', 'test the healthcheck endpoint that verifies the Open WebUI server is running and responsive']
```

Usage

```
{'run_chat_completion': 'run the chat_completion endpoint to generate AI chat completions with streaming support and model access control', 'test_get_models': 'test the get_models endpoint that returns filtered available AI models accessible to the authenticated user', 'test_embeddings': 'test the embeddings endpoint that generates OpenAI-compatible embeddings for text inputs', 'run_get_app_config': 'run the get_app_config endpoint to retrieve application configuration, feature flags, and OAuth provider settings', 'test_healthcheck': 'test the healthcheck endpoint that verifies the Open WebUI server is running and responsive'}
```

