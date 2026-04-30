# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/files/main.py

Prompts

```
['create a file upload to OpenAI or Azure for assistants, batch, fine-tune, or messages purposes', 'retrieve metadata for a specific file by its file_id across supported LLM providers', 'delete a previously uploaded file by its file_id from OpenAI, Azure, or other supported providers', 'list uploaded files filtered by purpose across OpenAI, Azure, Manus, or Anthropic providers', 'download the binary content of a file by its file_id from OpenAI, Azure, Vertex AI, Bedrock, or other providers', 'create a FileContentStreamingResponse iterator wrapper for file content streaming with LiteLLM logging callbacks', 'build sync iteration over a file content stream using __iter__ and __next__ methods', 'build async iteration over a file content stream using __aiter__ and __anext__ methods', 'test the aclose method that cleans up async file content streams with shielded cancellation scope', 'review the close method that synchronously closes file content streams and releases resources', 'test the FilesAPIUtils class and its static methods for file validation', 'test the is_batch_jsonl_file method to check if a file is a batch jsonl file', 'test the valid_content_type method to validate content type strings', 'review the FilesAPIUtils class and its utility methods for the files API interface', 'summarize the is_batch_jsonl_file method and its batch jsonl file detection logic']
```

Usage

```
{'create_file_upload': 'create a file upload to OpenAI or Azure for assistants, batch, fine-tune, or messages purposes', 'retrieve_file_metadata': 'retrieve metadata for a specific file by its file_id across supported LLM providers', 'delete_file': 'delete a previously uploaded file by its file_id from OpenAI, Azure, or other supported providers', 'list_files': 'list uploaded files filtered by purpose across OpenAI, Azure, Manus, or Anthropic providers', 'get_file_content': 'download the binary content of a file by its file_id from OpenAI, Azure, Vertex AI, Bedrock, or other providers'}
```

## File: berriai_litellm/litellm/files/streaming.py

Prompts

```
['create a file upload to OpenAI or Azure for assistants, batch, fine-tune, or messages purposes', 'retrieve metadata for a specific file by its file_id across supported LLM providers', 'delete a previously uploaded file by its file_id from OpenAI, Azure, or other supported providers', 'list uploaded files filtered by purpose across OpenAI, Azure, Manus, or Anthropic providers', 'download the binary content of a file by its file_id from OpenAI, Azure, Vertex AI, Bedrock, or other providers', 'create a FileContentStreamingResponse iterator wrapper for file content streaming with LiteLLM logging callbacks', 'build sync iteration over a file content stream using __iter__ and __next__ methods', 'build async iteration over a file content stream using __aiter__ and __anext__ methods', 'test the aclose method that cleans up async file content streams with shielded cancellation scope', 'review the close method that synchronously closes file content streams and releases resources', 'test the FilesAPIUtils class and its static methods for file validation', 'test the is_batch_jsonl_file method to check if a file is a batch jsonl file', 'test the valid_content_type method to validate content type strings', 'review the FilesAPIUtils class and its utility methods for the files API interface', 'summarize the is_batch_jsonl_file method and its batch jsonl file detection logic']
```

Usage

```
{'create_file_content_streaming_response': 'create a FileContentStreamingResponse iterator wrapper for file content streaming with LiteLLM logging callbacks', 'build_sync_iteration': 'build sync iteration over a file content stream using __iter__ and __next__ methods', 'build_async_iteration': 'build async iteration over a file content stream using __aiter__ and __anext__ methods', 'test_aclose_cleanup': 'test the aclose method that cleans up async file content streams with shielded cancellation scope', 'review_close_method': 'review the close method that synchronously closes file content streams and releases resources'}
```

## File: berriai_litellm/litellm/files/utils.py

Prompts

```
['create a file upload to OpenAI or Azure for assistants, batch, fine-tune, or messages purposes', 'retrieve metadata for a specific file by its file_id across supported LLM providers', 'delete a previously uploaded file by its file_id from OpenAI, Azure, or other supported providers', 'list uploaded files filtered by purpose across OpenAI, Azure, Manus, or Anthropic providers', 'download the binary content of a file by its file_id from OpenAI, Azure, Vertex AI, Bedrock, or other providers', 'create a FileContentStreamingResponse iterator wrapper for file content streaming with LiteLLM logging callbacks', 'build sync iteration over a file content stream using __iter__ and __next__ methods', 'build async iteration over a file content stream using __aiter__ and __anext__ methods', 'test the aclose method that cleans up async file content streams with shielded cancellation scope', 'review the close method that synchronously closes file content streams and releases resources', 'test the FilesAPIUtils class and its static methods for file validation', 'test the is_batch_jsonl_file method to check if a file is a batch jsonl file', 'test the valid_content_type method to validate content type strings', 'review the FilesAPIUtils class and its utility methods for the files API interface', 'summarize the is_batch_jsonl_file method and its batch jsonl file detection logic']
```

Usage

```
{'test_files_api_utils': 'test the FilesAPIUtils class and its static methods for file validation', 'test_is_batch_jsonl_file': 'test the is_batch_jsonl_file method to check if a file is a batch jsonl file', 'test_valid_content_type': 'test the valid_content_type method to validate content type strings', 'review_files_api_utils': 'review the FilesAPIUtils class and its utility methods for the files API interface', 'summarize_is_batch_jsonl_file': 'summarize the is_batch_jsonl_file method and its batch jsonl file detection logic'}
```

