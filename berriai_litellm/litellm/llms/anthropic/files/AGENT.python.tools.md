# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/anthropic/files/handler.py

Prompts

```
['retrieve file content from Anthropic batch results using file_id and return transformed OpenAI format response', 'transform Anthropic batch results JSONL to OpenAI batch results JSONL format with status codes and error bodies', 'transform a single Anthropic message to OpenAI chat completion format with choices and usage', 'run synchronous file content retrieval from Anthropic API with batch_id and API key', 'run asynchronous file content retrieval from Anthropic API with batch_id and API key', 'create an AnthropicFilesConfig instance to transform requests and responses for the Anthropic Files API', 'transform a create file request into multipart form data for uploading files to the Anthropic Files API', 'transform a retrieve file request into the correct Anthropic API URL for a given file ID', 'transform a list files request into the Anthropic API URL with optional purpose filter parameter', 'transform a delete file request into the correct Anthropic API URL for removing a file by ID']
```

Usage

```
{'retrieve_anthropic_batch_results': 'retrieve file content from Anthropic batch results using file_id and return transformed OpenAI format response', 'transform_anthropic_batch_results_to_openai_format': 'transform Anthropic batch results JSONL to OpenAI batch results JSONL format with status codes and error bodies', 'transform_anthropic_message_to_openai_format': 'transform a single Anthropic message to OpenAI chat completion format with choices and usage', 'run_anthropic_file_content_sync': 'run synchronous file content retrieval from Anthropic API with batch_id and API key', 'run_anthropic_file_content_async': 'run asynchronous file content retrieval from Anthropic API with batch_id and API key'}
```

## File: berriai_litellm/litellm/llms/anthropic/files/transformation.py

Prompts

```
['retrieve file content from Anthropic batch results using file_id and return transformed OpenAI format response', 'transform Anthropic batch results JSONL to OpenAI batch results JSONL format with status codes and error bodies', 'transform a single Anthropic message to OpenAI chat completion format with choices and usage', 'run synchronous file content retrieval from Anthropic API with batch_id and API key', 'run asynchronous file content retrieval from Anthropic API with batch_id and API key', 'create an AnthropicFilesConfig instance to transform requests and responses for the Anthropic Files API', 'transform a create file request into multipart form data for uploading files to the Anthropic Files API', 'transform a retrieve file request into the correct Anthropic API URL for a given file ID', 'transform a list files request into the Anthropic API URL with optional purpose filter parameter', 'transform a delete file request into the correct Anthropic API URL for removing a file by ID']
```

Usage

```
{'create_anthropic_files_config': 'create an AnthropicFilesConfig instance to transform requests and responses for the Anthropic Files API', 'transform_create_file_request': 'transform a create file request into multipart form data for uploading files to the Anthropic Files API', 'transform_retrieve_file_request': 'transform a retrieve file request into the correct Anthropic API URL for a given file ID', 'transform_list_files_request': 'transform a list files request into the Anthropic API URL with optional purpose filter parameter', 'transform_delete_file_request': 'transform a delete file request into the correct Anthropic API URL for removing a file by ID'}
```

