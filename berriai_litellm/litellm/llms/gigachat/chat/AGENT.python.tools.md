# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/gigachat/chat/streaming.py

Prompts

```
['create a GigaChatModelResponseIterator to consume streaming responses from GigaChat API', 'parse a GigaChatModelResponseIterator chunk into a GenericStreamingChunk with text and tool_use fields', 'iterate over GigaChatModelResponseIterator using __next__ to yield streaming chunks synchronously', 'async iterate over GigaChatModelResponseIterator using __anext__ to yield streaming chunks asynchronously', 'handle function_call finish_reason in GigaChatModelResponseIterator by converting to tool_calls format', 'build a GigaChat chat request by transforming OpenAI-format messages and parameters to GigaChat API format', 'create a GigaChat response by transforming the raw API response into OpenAI-compatible ModelResponse format', 'test the GigaChatConfig.validate_environment method to set up OAuth headers with access token', 'refactor the GigaChatConfig.map_openai_params method to map OpenAI parameters to GigaChat parameter format', 'summarize the GigaChatConfig._transform_messages method that converts OpenAI message roles and multimodal content to GigaChat format']
```

Usage

```
{'create_GigaChatModelResponseIterator': 'create a GigaChatModelResponseIterator to consume streaming responses from GigaChat API', 'parse_GigaChatModelResponseIterator_chunk_parser': 'parse a GigaChatModelResponseIterator chunk into a GenericStreamingChunk with text and tool_use fields', 'iterate_GigaChatModelResponseIterator_next': 'iterate over GigaChatModelResponseIterator using __next__ to yield streaming chunks synchronously', 'async_iterate_GigaChatModelResponseIterator_anext': 'async iterate over GigaChatModelResponseIterator using __anext__ to yield streaming chunks asynchronously', 'handle_GigaChatModelResponseIterator_function_call': 'handle function_call finish_reason in GigaChatModelResponseIterator by converting to tool_calls format'}
```

## File: berriai_litellm/litellm/llms/gigachat/chat/transformation.py

Prompts

```
['create a GigaChatModelResponseIterator to consume streaming responses from GigaChat API', 'parse a GigaChatModelResponseIterator chunk into a GenericStreamingChunk with text and tool_use fields', 'iterate over GigaChatModelResponseIterator using __next__ to yield streaming chunks synchronously', 'async iterate over GigaChatModelResponseIterator using __anext__ to yield streaming chunks asynchronously', 'handle function_call finish_reason in GigaChatModelResponseIterator by converting to tool_calls format', 'build a GigaChat chat request by transforming OpenAI-format messages and parameters to GigaChat API format', 'create a GigaChat response by transforming the raw API response into OpenAI-compatible ModelResponse format', 'test the GigaChatConfig.validate_environment method to set up OAuth headers with access token', 'refactor the GigaChatConfig.map_openai_params method to map OpenAI parameters to GigaChat parameter format', 'summarize the GigaChatConfig._transform_messages method that converts OpenAI message roles and multimodal content to GigaChat format']
```

Usage

```
{'build_transform_request': 'build a GigaChat chat request by transforming OpenAI-format messages and parameters to GigaChat API format', 'create_transform_response': 'create a GigaChat response by transforming the raw API response into OpenAI-compatible ModelResponse format', 'test_validate_environment': 'test the GigaChatConfig.validate_environment method to set up OAuth headers with access token', 'refactor_map_openai_params': 'refactor the GigaChatConfig.map_openai_params method to map OpenAI parameters to GigaChat parameter format', 'summarize_transform_messages': 'summarize the GigaChatConfig._transform_messages method that converts OpenAI message roles and multimodal content to GigaChat format'}
```

