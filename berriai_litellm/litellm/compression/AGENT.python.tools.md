# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/compression/compress.py

Prompts

```
['compress a list of conversation messages by replacing low-relevance content with stubs when token count exceeds a trigger threshold', 'extract the text content from the last user message in a conversation list', 'get indices of messages that must never be compressed including system, last user, and last assistant messages', 'combine BM25 and embedding scores with weighted average and min-max normalization for message relevance ranking', 'build a retrieval tool definition from a list of cache keys for recovering stubbed message content', 'detect whether content is code, JSON, or plain text by analyzing keywords and structure', 'detect if a string is valid JSON content and return the json type', 'detect if a string contains code by checking for language keywords and indentation patterns', 'detect if a string is plain text with no code keywords or JSON structure', 'detect the content type of an empty string and return text', 'extract a human-readable key from a message dict, handling duplicates with numeric suffixes', 'stub a message by replacing its content with a compact description referencing line count and content type', 'truncate a message content to a max token budget by keeping 70% of first lines and 30% of last lines']
```

Usage

```
{'compress_messages': 'compress a list of conversation messages by replacing low-relevance content with stubs when token count exceeds a trigger threshold', 'extract_last_user_message': 'extract the text content from the last user message in a conversation list', 'get_protected_indices': 'get indices of messages that must never be compressed including system, last user, and last assistant messages', 'combine_scores': 'combine BM25 and embedding scores with weighted average and min-max normalization for message relevance ranking', 'build_retrieval_tool': 'build a retrieval tool definition from a list of cache keys for recovering stubbed message content'}
```

## File: berriai_litellm/litellm/compression/content_detection.py

Prompts

```
['compress a list of conversation messages by replacing low-relevance content with stubs when token count exceeds a trigger threshold', 'extract the text content from the last user message in a conversation list', 'get indices of messages that must never be compressed including system, last user, and last assistant messages', 'combine BM25 and embedding scores with weighted average and min-max normalization for message relevance ranking', 'build a retrieval tool definition from a list of cache keys for recovering stubbed message content', 'detect whether content is code, JSON, or plain text by analyzing keywords and structure', 'detect if a string is valid JSON content and return the json type', 'detect if a string contains code by checking for language keywords and indentation patterns', 'detect if a string is plain text with no code keywords or JSON structure', 'detect the content type of an empty string and return text', 'extract a human-readable key from a message dict, handling duplicates with numeric suffixes', 'stub a message by replacing its content with a compact description referencing line count and content type', 'truncate a message content to a max token budget by keeping 70% of first lines and 30% of last lines']
```

Usage

```
{'detect_content_type': 'detect whether content is code, JSON, or plain text by analyzing keywords and structure', 'detect_content_type_json': 'detect if a string is valid JSON content and return the json type', 'detect_content_type_code': 'detect if a string contains code by checking for language keywords and indentation patterns', 'detect_content_type_text': 'detect if a string is plain text with no code keywords or JSON structure', 'detect_content_type_empty': 'detect the content type of an empty string and return text'}
```

## File: berriai_litellm/litellm/compression/message_stubbing.py

Prompts

```
['compress a list of conversation messages by replacing low-relevance content with stubs when token count exceeds a trigger threshold', 'extract the text content from the last user message in a conversation list', 'get indices of messages that must never be compressed including system, last user, and last assistant messages', 'combine BM25 and embedding scores with weighted average and min-max normalization for message relevance ranking', 'build a retrieval tool definition from a list of cache keys for recovering stubbed message content', 'detect whether content is code, JSON, or plain text by analyzing keywords and structure', 'detect if a string is valid JSON content and return the json type', 'detect if a string contains code by checking for language keywords and indentation patterns', 'detect if a string is plain text with no code keywords or JSON structure', 'detect the content type of an empty string and return text', 'extract a human-readable key from a message dict, handling duplicates with numeric suffixes', 'stub a message by replacing its content with a compact description referencing line count and content type', 'truncate a message content to a max token budget by keeping 70% of first lines and 30% of last lines']
```

Usage

```
{'extract_key_message': 'extract a human-readable key from a message dict, handling duplicates with numeric suffixes', 'stub_message_content': 'stub a message by replacing its content with a compact description referencing line count and content type', 'truncate_message_content': 'truncate a message content to a max token budget by keeping 70% of first lines and 30% of last lines', 'detect_content_type': 'detect the content type of a message string using litellm compression content detection', 'compress_messages': 'compress messages by extracting keys, stubbing content, and truncating oversized messages for context window management'}
```

## File: berriai_litellm/litellm/compression/retrieval_tool.py

Prompts

```
['compress a list of conversation messages by replacing low-relevance content with stubs when token count exceeds a trigger threshold', 'extract the text content from the last user message in a conversation list', 'get indices of messages that must never be compressed including system, last user, and last assistant messages', 'combine BM25 and embedding scores with weighted average and min-max normalization for message relevance ranking', 'build a retrieval tool definition from a list of cache keys for recovering stubbed message content', 'detect whether content is code, JSON, or plain text by analyzing keywords and structure', 'detect if a string is valid JSON content and return the json type', 'detect if a string contains code by checking for language keywords and indentation patterns', 'detect if a string is plain text with no code keywords or JSON structure', 'detect the content type of an empty string and return text', 'extract a human-readable key from a message dict, handling duplicates with numeric suffixes', 'stub a message by replacing its content with a compact description referencing line count and content type', 'truncate a message content to a max token budget by keeping 70% of first lines and 30% of last lines']
```

Usage

```
{'build_retrieval_tool': 'build a function that creates an OpenAI-format tool definition for retrieving compressed content by key'}
```

