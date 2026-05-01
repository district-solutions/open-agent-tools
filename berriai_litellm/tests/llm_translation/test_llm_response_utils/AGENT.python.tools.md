# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/tests/llm_translation/test_llm_response_utils/test_convert_dict_to_chat_completion.py

Prompts

```
['convert an OpenAI chat completion response dict into a typed ModelResponse object with choices, usage, and message fields', 'convert a response dict containing tool calls with function names and JSON arguments into a ModelResponse with parsed tool call objects', 'convert a tool call response into message content when using JSON mode by extracting the tool call arguments as the response content', 'convert a response dict with token-level logprobs and top logprobs into a ModelResponse preserving all probability data', 'convert a response dict that contains an empty error object without raising an exception and return a valid ModelResponse', 'test get_response_headers returns an empty dict when called with no input arguments', 'test get_response_headers forwards OpenAI rate limit headers as-is and prefixes others with llm_provider', 'test get_response_headers prefixes all non-OpenAI custom headers with the llm_provider prefix', 'test _get_llm_provider_headers prefixes headers with llm_provider and avoids double-prefixing existing ones', 'refactor get_response_headers to support additional OpenAI-compatible header keys beyond rate limit headers']
```

Usage

```
{'convert_dict_to_model_response': 'convert an OpenAI chat completion response dict into a typed ModelResponse object with choices, usage, and message fields', 'convert_tool_calls_in_response': 'convert a response dict containing tool calls with function names and JSON arguments into a ModelResponse with parsed tool call objects', 'convert_json_mode_response': 'convert a tool call response into message content when using JSON mode by extracting the tool call arguments as the response content', 'convert_response_with_logprobs': 'convert a response dict with token-level logprobs and top logprobs into a ModelResponse preserving all probability data', 'handle_empty_error_in_response': 'convert a response dict that contains an empty error object without raising an exception and return a valid ModelResponse'}
```

## File: berriai_litellm/tests/llm_translation/test_llm_response_utils/test_get_headers.py

Prompts

```
['convert an OpenAI chat completion response dict into a typed ModelResponse object with choices, usage, and message fields', 'convert a response dict containing tool calls with function names and JSON arguments into a ModelResponse with parsed tool call objects', 'convert a tool call response into message content when using JSON mode by extracting the tool call arguments as the response content', 'convert a response dict with token-level logprobs and top logprobs into a ModelResponse preserving all probability data', 'convert a response dict that contains an empty error object without raising an exception and return a valid ModelResponse', 'test get_response_headers returns an empty dict when called with no input arguments', 'test get_response_headers forwards OpenAI rate limit headers as-is and prefixes others with llm_provider', 'test get_response_headers prefixes all non-OpenAI custom headers with the llm_provider prefix', 'test _get_llm_provider_headers prefixes headers with llm_provider and avoids double-prefixing existing ones', 'refactor get_response_headers to support additional OpenAI-compatible header keys beyond rate limit headers']
```

Usage

```
{'test_get_response_headers_empty': 'test get_response_headers returns an empty dict when called with no input arguments', 'test_get_response_headers_openai': 'test get_response_headers forwards OpenAI rate limit headers as-is and prefixes others with llm_provider', 'test_get_response_headers_non_openai': 'test get_response_headers prefixes all non-OpenAI custom headers with the llm_provider prefix', 'test_get_llm_provider_headers': 'test _get_llm_provider_headers prefixes headers with llm_provider and avoids double-prefixing existing ones', 'refactor_get_response_headers': 'refactor get_response_headers to support additional OpenAI-compatible header keys beyond rate limit headers'}
```

