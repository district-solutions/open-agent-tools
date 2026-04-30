# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/openrouter/chat/transformation.py

Prompts

```
['transform the OpenRouter request with cache_control moved to content blocks and usage tracking enabled', 'transform the OpenRouter response to extract cost information from the usage object in the response body', 'map OpenAI parameters to OpenRouter extra_body parameters including transforms, models, and route', 'get supported OpenAI params for a model and add reasoning_effort and thinking for reasoning-capable models', 'run the streaming handler to parse OpenRouter SSE chunks and handle reasoning content extraction']
```

Usage

```
{'transform_OPENrouterConfig_request': 'transform the OpenRouter request with cache_control moved to content blocks and usage tracking enabled', 'transform_OPENrouterConfig_response': 'transform the OpenRouter response to extract cost information from the usage object in the response body', 'map_OPENrouterConfig_openai_params': 'map OpenAI parameters to OpenRouter extra_body parameters including transforms, models, and route', 'get_OPENrouterConfig_supported_openai_params': 'get supported OpenAI params for a model and add reasoning_effort and thinking for reasoning-capable models', 'run_OpenRouterChatCompletionStreamingHandler': 'run the streaming handler to parse OpenRouter SSE chunks and handle reasoning content extraction'}
```

