# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/google_genai/adapters/handler.py

Prompts

```
['create a generate_content handler that transforms generate_content calls to litellm completion format', 'build an async generate_content handler using litellm.acompletion with streaming support', 'run generate_content handler with stream enabled to receive transformed streaming responses', 'test the sync generate_content_handler that bridges generate_content API to litellm.completion', 'review _prepare_completion_kwargs to understand how generate_content requests are transformed to completion format', 'build a function that transforms Google GenAI generate_content requests to OpenAI completion format', 'build a function that transforms litellm completion responses to Google GenAI generate_content format', 'build a function that transforms streaming litellm completion chunks to Google GenAI generate_content streaming format', 'build a function that transforms Google GenAI tools to OpenAI tools format', 'build a function that transforms Google GenAI contents to OpenAI messages format']
```

Usage

```
{'create_generate_content_handler': 'create a generate_content handler that transforms generate_content calls to litellm completion format', 'build_async_generate_content_handler': 'build an async generate_content handler using litellm.acompletion with streaming support', 'run_generate_content_streaming': 'run generate_content handler with stream enabled to receive transformed streaming responses', 'test_generate_content_sync': 'test the sync generate_content_handler that bridges generate_content API to litellm.completion', 'review_prepare_completion_kwargs': 'review _prepare_completion_kwargs to understand how generate_content requests are transformed to completion format'}
```

## File: berriai_litellm/litellm/google_genai/adapters/transformation.py

Prompts

```
['create a generate_content handler that transforms generate_content calls to litellm completion format', 'build an async generate_content handler using litellm.acompletion with streaming support', 'run generate_content handler with stream enabled to receive transformed streaming responses', 'test the sync generate_content_handler that bridges generate_content API to litellm.completion', 'review _prepare_completion_kwargs to understand how generate_content requests are transformed to completion format', 'build a function that transforms Google GenAI generate_content requests to OpenAI completion format', 'build a function that transforms litellm completion responses to Google GenAI generate_content format', 'build a function that transforms streaming litellm completion chunks to Google GenAI generate_content streaming format', 'build a function that transforms Google GenAI tools to OpenAI tools format', 'build a function that transforms Google GenAI contents to OpenAI messages format']
```

Usage

```
{'build_translate_generate_content_to_completion': 'build a function that transforms Google GenAI generate_content requests to OpenAI completion format', 'build_translate_completion_to_generate_content': 'build a function that transforms litellm completion responses to Google GenAI generate_content format', 'build_translate_streaming_completion_to_generate_content': 'build a function that transforms streaming litellm completion chunks to Google GenAI generate_content streaming format', 'build_transform_google_genai_tools_to_openai': 'build a function that transforms Google GenAI tools to OpenAI tools format', 'build_transform_contents_to_messages': 'build a function that transforms Google GenAI contents to OpenAI messages format'}
```

