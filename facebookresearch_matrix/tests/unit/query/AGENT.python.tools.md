# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/tests/unit/query/test_batch_requests.py

Prompts

```
['test batch_requests called from within an asyncio.run context with mocked responses', 'test batch_requests when called from a synchronous context with mocked async requests', 'test batch_requests with an empty list to verify no requests are made', 'review the batch_requests function tests covering async, sync, and empty list scenarios', 'refactor the batch_requests test suite to add new edge case scenarios', 'test the load_from_hf_dataset function by mocking datasets.load_dataset and verifying returned message structure', 'test creating a HuggingFace Dataset from a dictionary with problem keys and string values', 'test that load_from_hf_dataset correctly maps text_key values into nested request.messages structure', 'test that load_from_hf_dataset prepends a system prompt as the first message in each line', 'test that load_from_hf_dataset attaches a metadata index field to each returned line', 'convert Llama instruct-format text with special tokens into a list of role and content message dicts', 'load JSONL files and extract prompts or messages using dot-notation keys with system prompt injection', 'convert an object with a token_map attribute into a serializable dict of token log probabilities', 'create a standardized error response dict from a request and exception with a timestamp', 'access nested dict values using dot-notation keys and derive the corresponding metadata key path']
```

Usage

```
{'test_batch_requests_async': 'test batch_requests called from within an asyncio.run context with mocked responses', 'test_batch_requests_sync': 'test batch_requests when called from a synchronous context with mocked async requests', 'test_batch_requests_empty': 'test batch_requests with an empty list to verify no requests are made', 'review_batch_requests': 'review the batch_requests function tests covering async, sync, and empty list scenarios', 'refactor_batch_requests_tests': 'refactor the batch_requests test suite to add new edge case scenarios'}
```

## File: facebookresearch_matrix/tests/unit/query/test_load_from_hf_dataset.py

Prompts

```
['test batch_requests called from within an asyncio.run context with mocked responses', 'test batch_requests when called from a synchronous context with mocked async requests', 'test batch_requests with an empty list to verify no requests are made', 'review the batch_requests function tests covering async, sync, and empty list scenarios', 'refactor the batch_requests test suite to add new edge case scenarios', 'test the load_from_hf_dataset function by mocking datasets.load_dataset and verifying returned message structure', 'test creating a HuggingFace Dataset from a dictionary with problem keys and string values', 'test that load_from_hf_dataset correctly maps text_key values into nested request.messages structure', 'test that load_from_hf_dataset prepends a system prompt as the first message in each line', 'test that load_from_hf_dataset attaches a metadata index field to each returned line', 'convert Llama instruct-format text with special tokens into a list of role and content message dicts', 'load JSONL files and extract prompts or messages using dot-notation keys with system prompt injection', 'convert an object with a token_map attribute into a serializable dict of token log probabilities', 'create a standardized error response dict from a request and exception with a timestamp', 'access nested dict values using dot-notation keys and derive the corresponding metadata key path']
```

Usage

```
{'test_load_from_hf_dataset': 'test the load_from_hf_dataset function by mocking datasets.load_dataset and verifying returned message structure', 'test_dataset_from_dict': 'test creating a HuggingFace Dataset from a dictionary with problem keys and string values', 'test_query_llm_messages_key': 'test that load_from_hf_dataset correctly maps text_key values into nested request.messages structure', 'test_query_llm_system_prompt': 'test that load_from_hf_dataset prepends a system prompt as the first message in each line', 'test_query_llm_metadata_index': 'test that load_from_hf_dataset attaches a metadata index field to each returned line'}
```

## File: facebookresearch_matrix/tests/unit/query/test_query_helpers.py

Prompts

```
['test batch_requests called from within an asyncio.run context with mocked responses', 'test batch_requests when called from a synchronous context with mocked async requests', 'test batch_requests with an empty list to verify no requests are made', 'review the batch_requests function tests covering async, sync, and empty list scenarios', 'refactor the batch_requests test suite to add new edge case scenarios', 'test the load_from_hf_dataset function by mocking datasets.load_dataset and verifying returned message structure', 'test creating a HuggingFace Dataset from a dictionary with problem keys and string values', 'test that load_from_hf_dataset correctly maps text_key values into nested request.messages structure', 'test that load_from_hf_dataset prepends a system prompt as the first message in each line', 'test that load_from_hf_dataset attaches a metadata index field to each returned line', 'convert Llama instruct-format text with special tokens into a list of role and content message dicts', 'load JSONL files and extract prompts or messages using dot-notation keys with system prompt injection', 'convert an object with a token_map attribute into a serializable dict of token log probabilities', 'create a standardized error response dict from a request and exception with a timestamp', 'access nested dict values using dot-notation keys and derive the corresponding metadata key path']
```

Usage

```
{'convert_llama_instruct_text': 'convert Llama instruct-format text with special tokens into a list of role and content message dicts', 'load_from_jsonl': 'load JSONL files and extract prompts or messages using dot-notation keys with system prompt injection', 'convert_token_log_probs': 'convert an object with a token_map attribute into a serializable dict of token log probabilities', 'make_error_response': 'create a standardized error response dict from a request and exception with a timestamp', 'get_request_and_metadata_key': 'access nested dict values using dot-notation keys and derive the corresponding metadata key path'}
```

