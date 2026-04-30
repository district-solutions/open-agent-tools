# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/openai/common_utils.py

Prompts

```
['create an OpenAIError with status code, message, request, response, headers, and body', 'drop invalid parameters from a data dict based on an UnprocessableEntityError or HTTPStatusError', 'get a cached OpenAI client from the in-memory cache using initialization params and client type', 'build OpenAI credentials by resolving api_base, api_key, and organization from params, globals, and env vars', 'test generating a cache key for an OpenAI client from its initialization parameters and client type', 'calculate the prompt and completion cost in USD for an OpenAI model given usage tokens', 'calculate the prompt and completion cost in USD for speech or audio models by duration in seconds', 'calculate the total cost in USD for a video generation given duration and resolution', 'determine whether a call type should use cost_per_token or cost_per_second pricing', 'map a video resolution string to a safe suffix for cost lookup keys', 'create a chat completion request using OpenAIChatCompletion with messages, model, and optional parameters', 'create an embedding using OpenAI embedding method with model name and input text list', 'generate an image using OpenAI image generation with a text prompt and optional size parameters', 'create audio speech from text using OpenAI audio_speech with model, input text, and voice selection', 'manage OpenAI assistants including create, list, get, delete assistants and run threads with messages']
```

Usage

```
{'create_openai_error': 'create an OpenAIError with status code, message, request, response, headers, and body', 'drop_params_unprocessable_entity': 'drop invalid parameters from a data dict based on an UnprocessableEntityError or HTTPStatusError', 'get_cached_openai_client': 'get a cached OpenAI client from the in-memory cache using initialization params and client type', 'build_openai_credentials': 'build OpenAI credentials by resolving api_base, api_key, and organization from params, globals, and env vars', 'test_openai_client_cache_key': 'test generating a cache key for an OpenAI client from its initialization parameters and client type'}
```

## File: berriai_litellm/litellm/llms/openai/cost_calculation.py

Prompts

```
['create an OpenAIError with status code, message, request, response, headers, and body', 'drop invalid parameters from a data dict based on an UnprocessableEntityError or HTTPStatusError', 'get a cached OpenAI client from the in-memory cache using initialization params and client type', 'build OpenAI credentials by resolving api_base, api_key, and organization from params, globals, and env vars', 'test generating a cache key for an OpenAI client from its initialization parameters and client type', 'calculate the prompt and completion cost in USD for an OpenAI model given usage tokens', 'calculate the prompt and completion cost in USD for speech or audio models by duration in seconds', 'calculate the total cost in USD for a video generation given duration and resolution', 'determine whether a call type should use cost_per_token or cost_per_second pricing', 'map a video resolution string to a safe suffix for cost lookup keys', 'create a chat completion request using OpenAIChatCompletion with messages, model, and optional parameters', 'create an embedding using OpenAI embedding method with model name and input text list', 'generate an image using OpenAI image generation with a text prompt and optional size parameters', 'create audio speech from text using OpenAI audio_speech with model, input text, and voice selection', 'manage OpenAI assistants including create, list, get, delete assistants and run threads with messages']
```

Usage

```
{'calculate_cost_per_token': 'calculate the prompt and completion cost in USD for an OpenAI model given usage tokens', 'calculate_cost_per_second': 'calculate the prompt and completion cost in USD for speech or audio models by duration in seconds', 'calculate_video_generation_cost': 'calculate the total cost in USD for a video generation given duration and resolution', 'determine_cost_routing': 'determine whether a call type should use cost_per_token or cost_per_second pricing', 'map_video_resolution_to_cost_suffix': 'map a video resolution string to a safe suffix for cost lookup keys'}
```

## File: berriai_litellm/litellm/llms/openai/openai.py

Prompts

```
['create an OpenAIError with status code, message, request, response, headers, and body', 'drop invalid parameters from a data dict based on an UnprocessableEntityError or HTTPStatusError', 'get a cached OpenAI client from the in-memory cache using initialization params and client type', 'build OpenAI credentials by resolving api_base, api_key, and organization from params, globals, and env vars', 'test generating a cache key for an OpenAI client from its initialization parameters and client type', 'calculate the prompt and completion cost in USD for an OpenAI model given usage tokens', 'calculate the prompt and completion cost in USD for speech or audio models by duration in seconds', 'calculate the total cost in USD for a video generation given duration and resolution', 'determine whether a call type should use cost_per_token or cost_per_second pricing', 'map a video resolution string to a safe suffix for cost lookup keys', 'create a chat completion request using OpenAIChatCompletion with messages, model, and optional parameters', 'create an embedding using OpenAI embedding method with model name and input text list', 'generate an image using OpenAI image generation with a text prompt and optional size parameters', 'create audio speech from text using OpenAI audio_speech with model, input text, and voice selection', 'manage OpenAI assistants including create, list, get, delete assistants and run threads with messages']
```

Usage

```
{'create_chat_completion': 'create a chat completion request using OpenAIChatCompletion with messages, model, and optional parameters', 'create_embedding': 'create an embedding using OpenAI embedding method with model name and input text list', 'generate_image': 'generate an image using OpenAI image generation with a text prompt and optional size parameters', 'create_audio_speech': 'create audio speech from text using OpenAI audio_speech with model, input text, and voice selection', 'manage_assistants': 'manage OpenAI assistants including create, list, get, delete assistants and run threads with messages'}
```

