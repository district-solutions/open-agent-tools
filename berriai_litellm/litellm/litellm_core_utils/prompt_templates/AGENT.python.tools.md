# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/litellm_core_utils/prompt_templates/common_utils.py

Prompts

```
['extract file data from a tuple of filename, content, optional content_type, and optional headers', 'parse tool call arguments from a JSON string, repairing truncated JSON when needed', 'unpack and expand all $ref entries in a JSON schema dictionary in-place', 'split a string of concatenated JSON objects into a list of parsed dictionaries', 'get concatenated content string from a model response object or dictionary', 'build a prompt factory that converts OpenAI messages to provider-specific formats for ollama, anthropic, gemini, bedrock, mistral, and falcon', 'create anthropic message formatting that converts OpenAI-format messages to Anthropic Messages API format with tool use and thinking blocks', 'convert OpenAI-format messages to Bedrock Converse API format with tool calls, images, and reasoning content blocks', 'sanitize messages for tool calling by adding missing tool results, removing orphaned tool results, and deduplicating results', 'convert OpenAI tool calls to Gemini function call format with thought signatures for gemini-3 models', 'build a function that fetches tokenizer_config.json from a HuggingFace model repo using sync HTTP', 'create an async function that fetches tokenizer_config.json from a HuggingFace model repo', 'test the function that fetches chat_template.jinja from a HuggingFace model repo', 'run the async function that fetches chat_template.jinja2 from a HuggingFace model repo', 'review the function that extracts a token string from None, str, or dict formats', 'convert an image URL to a base64 data URI string with content type detection', 'asynchronously convert an image URL to a base64 data URI string with caching', 'process an HTTP image response by downloading, validating size, and encoding to base64', 'fetch an image from a URL with retry logic and in-memory caching support', 'validate image download size against the maximum allowed limit before streaming']
```

Usage

```
{'extract_file_data_from_tuple': 'extract file data from a tuple of filename, content, optional content_type, and optional headers', 'parse_tool_call_arguments_json': 'parse tool call arguments from a JSON string, repairing truncated JSON when needed', 'unpack_json_schema_refs': 'unpack and expand all $ref entries in a JSON schema dictionary in-place', 'split_concatenated_json_objects': 'split a string of concatenated JSON objects into a list of parsed dictionaries', 'get_content_from_model_response': 'get concatenated content string from a model response object or dictionary'}
```

## File: berriai_litellm/litellm/litellm_core_utils/prompt_templates/factory.py

Prompts

```
['extract file data from a tuple of filename, content, optional content_type, and optional headers', 'parse tool call arguments from a JSON string, repairing truncated JSON when needed', 'unpack and expand all $ref entries in a JSON schema dictionary in-place', 'split a string of concatenated JSON objects into a list of parsed dictionaries', 'get concatenated content string from a model response object or dictionary', 'build a prompt factory that converts OpenAI messages to provider-specific formats for ollama, anthropic, gemini, bedrock, mistral, and falcon', 'create anthropic message formatting that converts OpenAI-format messages to Anthropic Messages API format with tool use and thinking blocks', 'convert OpenAI-format messages to Bedrock Converse API format with tool calls, images, and reasoning content blocks', 'sanitize messages for tool calling by adding missing tool results, removing orphaned tool results, and deduplicating results', 'convert OpenAI tool calls to Gemini function call format with thought signatures for gemini-3 models', 'build a function that fetches tokenizer_config.json from a HuggingFace model repo using sync HTTP', 'create an async function that fetches tokenizer_config.json from a HuggingFace model repo', 'test the function that fetches chat_template.jinja from a HuggingFace model repo', 'run the async function that fetches chat_template.jinja2 from a HuggingFace model repo', 'review the function that extracts a token string from None, str, or dict formats', 'convert an image URL to a base64 data URI string with content type detection', 'asynchronously convert an image URL to a base64 data URI string with caching', 'process an HTTP image response by downloading, validating size, and encoding to base64', 'fetch an image from a URL with retry logic and in-memory caching support', 'validate image download size against the maximum allowed limit before streaming']
```

Usage

```
{'build_prompt_factory': 'build a prompt factory that converts OpenAI messages to provider-specific formats for ollama, anthropic, gemini, bedrock, mistral, and falcon', 'create_anthropic_messages_pt': 'create anthropic message formatting that converts OpenAI-format messages to Anthropic Messages API format with tool use and thinking blocks', 'convert_bedrock_converse_messages': 'convert OpenAI-format messages to Bedrock Converse API format with tool calls, images, and reasoning content blocks', 'sanitize_tool_calling_messages': 'sanitize messages for tool calling by adding missing tool results, removing orphaned tool results, and deduplicating results', 'create_gemini_tool_calls': 'convert OpenAI tool calls to Gemini function call format with thought signatures for gemini-3 models'}
```

## File: berriai_litellm/litellm/litellm_core_utils/prompt_templates/huggingface_template_handler.py

Prompts

```
['extract file data from a tuple of filename, content, optional content_type, and optional headers', 'parse tool call arguments from a JSON string, repairing truncated JSON when needed', 'unpack and expand all $ref entries in a JSON schema dictionary in-place', 'split a string of concatenated JSON objects into a list of parsed dictionaries', 'get concatenated content string from a model response object or dictionary', 'build a prompt factory that converts OpenAI messages to provider-specific formats for ollama, anthropic, gemini, bedrock, mistral, and falcon', 'create anthropic message formatting that converts OpenAI-format messages to Anthropic Messages API format with tool use and thinking blocks', 'convert OpenAI-format messages to Bedrock Converse API format with tool calls, images, and reasoning content blocks', 'sanitize messages for tool calling by adding missing tool results, removing orphaned tool results, and deduplicating results', 'convert OpenAI tool calls to Gemini function call format with thought signatures for gemini-3 models', 'build a function that fetches tokenizer_config.json from a HuggingFace model repo using sync HTTP', 'create an async function that fetches tokenizer_config.json from a HuggingFace model repo', 'test the function that fetches chat_template.jinja from a HuggingFace model repo', 'run the async function that fetches chat_template.jinja2 from a HuggingFace model repo', 'review the function that extracts a token string from None, str, or dict formats', 'convert an image URL to a base64 data URI string with content type detection', 'asynchronously convert an image URL to a base64 data URI string with caching', 'process an HTTP image response by downloading, validating size, and encoding to base64', 'fetch an image from a URL with retry logic and in-memory caching support', 'validate image download size against the maximum allowed limit before streaming']
```

Usage

```
{'build_get_tokenizer_config': 'build a function that fetches tokenizer_config.json from a HuggingFace model repo using sync HTTP', 'create_aget_tokenizer_config': 'create an async function that fetches tokenizer_config.json from a HuggingFace model repo', 'test_get_chat_template_file': 'test the function that fetches chat_template.jinja from a HuggingFace model repo', 'run_aget_chat_template_file': 'run the async function that fetches chat_template.jinja2 from a HuggingFace model repo', 'review_extract_token_value': 'review the function that extracts a token string from None, str, or dict formats'}
```

## File: berriai_litellm/litellm/litellm_core_utils/prompt_templates/image_handling.py

Prompts

```
['extract file data from a tuple of filename, content, optional content_type, and optional headers', 'parse tool call arguments from a JSON string, repairing truncated JSON when needed', 'unpack and expand all $ref entries in a JSON schema dictionary in-place', 'split a string of concatenated JSON objects into a list of parsed dictionaries', 'get concatenated content string from a model response object or dictionary', 'build a prompt factory that converts OpenAI messages to provider-specific formats for ollama, anthropic, gemini, bedrock, mistral, and falcon', 'create anthropic message formatting that converts OpenAI-format messages to Anthropic Messages API format with tool use and thinking blocks', 'convert OpenAI-format messages to Bedrock Converse API format with tool calls, images, and reasoning content blocks', 'sanitize messages for tool calling by adding missing tool results, removing orphaned tool results, and deduplicating results', 'convert OpenAI tool calls to Gemini function call format with thought signatures for gemini-3 models', 'build a function that fetches tokenizer_config.json from a HuggingFace model repo using sync HTTP', 'create an async function that fetches tokenizer_config.json from a HuggingFace model repo', 'test the function that fetches chat_template.jinja from a HuggingFace model repo', 'run the async function that fetches chat_template.jinja2 from a HuggingFace model repo', 'review the function that extracts a token string from None, str, or dict formats', 'convert an image URL to a base64 data URI string with content type detection', 'asynchronously convert an image URL to a base64 data URI string with caching', 'process an HTTP image response by downloading, validating size, and encoding to base64', 'fetch an image from a URL with retry logic and in-memory caching support', 'validate image download size against the maximum allowed limit before streaming']
```

Usage

```
{'convert_url_to_base64': 'convert an image URL to a base64 data URI string with content type detection', 'async_convert_url_to_base64': 'asynchronously convert an image URL to a base64 data URI string with caching', 'process_image_response': 'process an HTTP image response by downloading, validating size, and encoding to base64', 'fetch_image_from_url': 'fetch an image from a URL with retry logic and in-memory caching support', 'validate_image_size': 'validate image download size against the maximum allowed limit before streaming'}
```

