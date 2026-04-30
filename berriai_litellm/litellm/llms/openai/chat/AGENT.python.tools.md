# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/openai/chat/gpt_5_transformation.py

Prompts

```
['normalize reasoning_effort dict to string format for OpenAI chat completion API', 'extract effective effort level from reasoning_effort string or dict input', 'test if a model name is a gpt-5 model excluding chat variants', 'test if a model name is a gpt-5 search variant', 'map openai params for gpt-5 models handling max_tokens, temperature, and reasoning_effort validation', 'test the OpenAIGPTAudioConfig.get_config class method to return the configuration dict', 'test the get_supported_openai_params method to return supported OpenAI params for gpt-audio models', 'test the is_model_gpt_audio_model method to check if a model name is a gpt-audio model', 'test the _map_openai_params method to map non-default and optional params for gpt-audio models', 'transform request messages and optional params for OpenAI Chat Completions API call', 'transform raw httpx response into ModelResponse object with logging', 'transform message content items handling image_url dicts and file objects with pdf base64 conversion', 'get list of supported OpenAI parameters for a given model name', 'parse streaming chunk dict into ModelResponseStream with reasoning field mapping', 'get the supported OpenAI params for an o-series model filtering unsupported ones like logprobs and top_p', 'transform messages for o-series models converting system role to user role when system messages are unsupported', 'check if a given model string matches the o-series pattern like o1 or o3', 'translate developer role messages for o-series models that support the developer role']
```

Usage

```
{'normalize_reasoning_effort_for_chat_completion': 'normalize reasoning_effort dict to string format for OpenAI chat completion API', 'get_effort_level': 'extract effective effort level from reasoning_effort string or dict input', 'is_model_gpt_5_model': 'test if a model name is a gpt-5 model excluding chat variants', 'is_model_gpt_5_search_model': 'test if a model name is a gpt-5 search variant', 'map_openai_params': 'map openai params for gpt-5 models handling max_tokens, temperature, and reasoning_effort validation'}
```

## File: berriai_litellm/litellm/llms/openai/chat/gpt_audio_transformation.py

Prompts

```
['normalize reasoning_effort dict to string format for OpenAI chat completion API', 'extract effective effort level from reasoning_effort string or dict input', 'test if a model name is a gpt-5 model excluding chat variants', 'test if a model name is a gpt-5 search variant', 'map openai params for gpt-5 models handling max_tokens, temperature, and reasoning_effort validation', 'test the OpenAIGPTAudioConfig.get_config class method to return the configuration dict', 'test the get_supported_openai_params method to return supported OpenAI params for gpt-audio models', 'test the is_model_gpt_audio_model method to check if a model name is a gpt-audio model', 'test the _map_openai_params method to map non-default and optional params for gpt-audio models', 'transform request messages and optional params for OpenAI Chat Completions API call', 'transform raw httpx response into ModelResponse object with logging', 'transform message content items handling image_url dicts and file objects with pdf base64 conversion', 'get list of supported OpenAI parameters for a given model name', 'parse streaming chunk dict into ModelResponseStream with reasoning field mapping', 'get the supported OpenAI params for an o-series model filtering unsupported ones like logprobs and top_p', 'transform messages for o-series models converting system role to user role when system messages are unsupported', 'check if a given model string matches the o-series pattern like o1 or o3', 'translate developer role messages for o-series models that support the developer role']
```

Usage

```
{'test_get_config': 'test the OpenAIGPTAudioConfig.get_config class method to return the configuration dict', 'test_get_supported_openai_params': 'test the get_supported_openai_params method to return supported OpenAI params for gpt-audio models', 'test_is_model_gpt_audio_model': 'test the is_model_gpt_audio_model method to check if a model name is a gpt-audio model', 'test__map_openai_params': 'test the _map_openai_params method to map non-default and optional params for gpt-audio models'}
```

## File: berriai_litellm/litellm/llms/openai/chat/gpt_transformation.py

Prompts

```
['normalize reasoning_effort dict to string format for OpenAI chat completion API', 'extract effective effort level from reasoning_effort string or dict input', 'test if a model name is a gpt-5 model excluding chat variants', 'test if a model name is a gpt-5 search variant', 'map openai params for gpt-5 models handling max_tokens, temperature, and reasoning_effort validation', 'test the OpenAIGPTAudioConfig.get_config class method to return the configuration dict', 'test the get_supported_openai_params method to return supported OpenAI params for gpt-audio models', 'test the is_model_gpt_audio_model method to check if a model name is a gpt-audio model', 'test the _map_openai_params method to map non-default and optional params for gpt-audio models', 'transform request messages and optional params for OpenAI Chat Completions API call', 'transform raw httpx response into ModelResponse object with logging', 'transform message content items handling image_url dicts and file objects with pdf base64 conversion', 'get list of supported OpenAI parameters for a given model name', 'parse streaming chunk dict into ModelResponseStream with reasoning field mapping', 'get the supported OpenAI params for an o-series model filtering unsupported ones like logprobs and top_p', 'transform messages for o-series models converting system role to user role when system messages are unsupported', 'check if a given model string matches the o-series pattern like o1 or o3', 'translate developer role messages for o-series models that support the developer role']
```

Usage

```
{'transform_request_OpenAIGPTConfig': 'transform request messages and optional params for OpenAI Chat Completions API call', 'transform_response_OpenAIGPTConfig': 'transform raw httpx response into ModelResponse object with logging', 'transform_content_item_OpenAIGPTConfig': 'transform message content items handling image_url dicts and file objects with pdf base64 conversion', 'get_supported_openai_params_OpenAIGPTConfig': 'get list of supported OpenAI parameters for a given model name', 'chunk_parser_OpenAIChatCompletionStreamingHandler': 'parse streaming chunk dict into ModelResponseStream with reasoning field mapping'}
```

## File: berriai_litellm/litellm/llms/openai/chat/o_series_transformation.py

Prompts

```
['normalize reasoning_effort dict to string format for OpenAI chat completion API', 'extract effective effort level from reasoning_effort string or dict input', 'test if a model name is a gpt-5 model excluding chat variants', 'test if a model name is a gpt-5 search variant', 'map openai params for gpt-5 models handling max_tokens, temperature, and reasoning_effort validation', 'test the OpenAIGPTAudioConfig.get_config class method to return the configuration dict', 'test the get_supported_openai_params method to return supported OpenAI params for gpt-audio models', 'test the is_model_gpt_audio_model method to check if a model name is a gpt-audio model', 'test the _map_openai_params method to map non-default and optional params for gpt-audio models', 'transform request messages and optional params for OpenAI Chat Completions API call', 'transform raw httpx response into ModelResponse object with logging', 'transform message content items handling image_url dicts and file objects with pdf base64 conversion', 'get list of supported OpenAI parameters for a given model name', 'parse streaming chunk dict into ModelResponseStream with reasoning field mapping', 'get the supported OpenAI params for an o-series model filtering unsupported ones like logprobs and top_p', 'transform messages for o-series models converting system role to user role when system messages are unsupported', 'check if a given model string matches the o-series pattern like o1 or o3', 'translate developer role messages for o-series models that support the developer role']
```

Usage

```
{'get_supported_openai_params': 'get the supported OpenAI params for an o-series model filtering unsupported ones like logprobs and top_p', 'map_openai_params': 'map openai params for o-series models translating max_tokens to max_completion_tokens and enforcing temperature=1', 'transform_messages': 'transform messages for o-series models converting system role to user role when system messages are unsupported', 'is_model_o_series_model': 'check if a given model string matches the o-series pattern like o1 or o3', 'translate_developer_role_to_system_role': 'translate developer role messages for o-series models that support the developer role'}
```

