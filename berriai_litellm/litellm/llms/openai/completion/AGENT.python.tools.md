# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/openai/completion/handler.py

Prompts

```
['create an OpenAI text completion call with model, messages, api_key and optional streaming parameters', 'create an async OpenAI text completion call returning a structured response object', 'create a streaming OpenAI text completion call yielding response chunks', 'create an async streaming OpenAI text completion call yielding transformed chunks', 'test the validate_environment method to build headers with Bearer token from api_key', 'convert the text completion response object to a chat model response object with message content and role', 'get the list of supported OpenAI parameters for a given model string', 'transform messages and optional parameters into a text completion request dictionary with model and prompt', 'build an OpenAITextCompletionConfig instance with best_of, echo, frequency_penalty, logit_bias, max_tokens, stop, suffix, temperature, and top_p', 'get the configuration dictionary from OpenAITextCompletionConfig using get_config', 'test the is_tokens_or_list_of_tokens function with a list of integers', 'test the is_tokens_or_list_of_tokens function with a list of lists of integers', 'test the is_tokens_or_list_of_tokens function with a list of strings', 'test the _transform_prompt function with a single message containing string content', 'test the _transform_prompt function with multiple messages']
```

Usage

```
{'create_openai_text_completion': 'create an OpenAI text completion call with model, messages, api_key and optional streaming parameters', 'create_async_openai_completion': 'create an async OpenAI text completion call returning a structured response object', 'create_openai_streaming_completion': 'create a streaming OpenAI text completion call yielding response chunks', 'create_async_openai_streaming_completion': 'create an async streaming OpenAI text completion call yielding transformed chunks', 'test_validate_environment': 'test the validate_environment method to build headers with Bearer token from api_key'}
```

## File: berriai_litellm/litellm/llms/openai/completion/transformation.py

Prompts

```
['create an OpenAI text completion call with model, messages, api_key and optional streaming parameters', 'create an async OpenAI text completion call returning a structured response object', 'create a streaming OpenAI text completion call yielding response chunks', 'create an async streaming OpenAI text completion call yielding transformed chunks', 'test the validate_environment method to build headers with Bearer token from api_key', 'convert the text completion response object to a chat model response object with message content and role', 'get the list of supported OpenAI parameters for a given model string', 'transform messages and optional parameters into a text completion request dictionary with model and prompt', 'build an OpenAITextCompletionConfig instance with best_of, echo, frequency_penalty, logit_bias, max_tokens, stop, suffix, temperature, and top_p', 'get the configuration dictionary from OpenAITextCompletionConfig using get_config', 'test the is_tokens_or_list_of_tokens function with a list of integers', 'test the is_tokens_or_list_of_tokens function with a list of lists of integers', 'test the is_tokens_or_list_of_tokens function with a list of strings', 'test the _transform_prompt function with a single message containing string content', 'test the _transform_prompt function with multiple messages']
```

Usage

```
{'convert_text_completion_to_chat_response': 'convert the text completion response object to a chat model response object with message content and role', 'get_supported_openai_params': 'get the list of supported OpenAI parameters for a given model string', 'transform_text_completion_request': 'transform messages and optional parameters into a text completion request dictionary with model and prompt', 'build_openai_text_completion_config': 'build an OpenAITextCompletionConfig instance with best_of, echo, frequency_penalty, logit_bias, max_tokens, stop, suffix, temperature, and top_p', 'get_openai_text_completion_config': 'get the configuration dictionary from OpenAITextCompletionConfig using get_config'}
```

## File: berriai_litellm/litellm/llms/openai/completion/utils.py

Prompts

```
['create an OpenAI text completion call with model, messages, api_key and optional streaming parameters', 'create an async OpenAI text completion call returning a structured response object', 'create a streaming OpenAI text completion call yielding response chunks', 'create an async streaming OpenAI text completion call yielding transformed chunks', 'test the validate_environment method to build headers with Bearer token from api_key', 'convert the text completion response object to a chat model response object with message content and role', 'get the list of supported OpenAI parameters for a given model string', 'transform messages and optional parameters into a text completion request dictionary with model and prompt', 'build an OpenAITextCompletionConfig instance with best_of, echo, frequency_penalty, logit_bias, max_tokens, stop, suffix, temperature, and top_p', 'get the configuration dictionary from OpenAITextCompletionConfig using get_config', 'test the is_tokens_or_list_of_tokens function with a list of integers', 'test the is_tokens_or_list_of_tokens function with a list of lists of integers', 'test the is_tokens_or_list_of_tokens function with a list of strings', 'test the _transform_prompt function with a single message containing string content', 'test the _transform_prompt function with multiple messages']
```

Usage

```
{'test_is_tokens_or_list_of_tokens': 'test the is_tokens_or_list_of_tokens function with a list of integers', 'test_is_tokens_or_list_of_tokens_nested': 'test the is_tokens_or_list_of_tokens function with a list of lists of integers', 'test_is_tokens_or_list_of_tokens_invalid': 'test the is_tokens_or_list_of_tokens function with a list of strings', 'test_transform_prompt_single': 'test the _transform_prompt function with a single message containing string content', 'test_transform_prompt_multiple': 'test the _transform_prompt function with multiple messages'}
```

