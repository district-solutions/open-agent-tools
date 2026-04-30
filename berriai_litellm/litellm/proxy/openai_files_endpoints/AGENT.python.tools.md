# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/openai_files_endpoints/common_utils.py

Prompts

```
['encode a file or batch ID with model routing information using base64 encoding', 'decode the model name from an encoded file or batch ID containing embedded routing info', 'extract the original provider file or batch ID from an encoded ID', 'orchestrate model-based credential routing for file operations using embedded or request model params', 'extract structured file creation parameters from a FastAPI request including storage and model names', 'test if a MIME type is supported by Gemini multimodal models for images, video, audio, and documents', 'update batch status and object in the managed object database table', 'resolve the provider, file ID, and request payload for streaming file content requests', 'check if a custom LLM provider supports streaming file content', 'stream file content chunks with proxy logging, error handling, and cleanup', 'create a FastAPI StreamingResponse for streaming file content with custom headers', 'build a file content streaming handler class that resolves streaming params and returns FastAPI StreamingResponse', 'create a file upload endpoint for Assistants API, Batch API, or fine-tuning via POST /v1/files', 'list uploaded files with optional provider, target_model_names, and purpose filters via GET /v1/files', 'retrieve metadata for a specific file by file_id via GET /v1/files/{file_id}', 'download the raw content of a file by file_id via GET /v1/files/{file_id}/content', 'delete a specific file by file_id via DELETE /v1/files/{file_id}', 'set the files_config with a list of provider configurations including custom_llm_provider and credentials', 'route a file creation request to the appropriate provider using model-based routing or managed files', 'handle model-based credential routing for file operations using encoded file IDs']
```

Usage

```
{'encode_file_id_with_model': 'encode a file or batch ID with model routing information using base64 encoding', 'decode_model_from_file_id': 'decode the model name from an encoded file or batch ID containing embedded routing info', 'get_original_file_id': 'extract the original provider file or batch ID from an encoded ID', 'handle_model_based_routing': 'orchestrate model-based credential routing for file operations using embedded or request model params', 'extract_file_creation_params': 'extract structured file creation parameters from a FastAPI request including storage and model names', 'is_gemini_supported_mime_type': 'test if a MIME type is supported by Gemini multimodal models for images, video, audio, and documents', 'update_batch_in_database': 'update batch status and object in the managed object database table'}
```

## File: berriai_litellm/litellm/proxy/openai_files_endpoints/file_content_streaming_handler.py

Prompts

```
['encode a file or batch ID with model routing information using base64 encoding', 'decode the model name from an encoded file or batch ID containing embedded routing info', 'extract the original provider file or batch ID from an encoded ID', 'orchestrate model-based credential routing for file operations using embedded or request model params', 'extract structured file creation parameters from a FastAPI request including storage and model names', 'test if a MIME type is supported by Gemini multimodal models for images, video, audio, and documents', 'update batch status and object in the managed object database table', 'resolve the provider, file ID, and request payload for streaming file content requests', 'check if a custom LLM provider supports streaming file content', 'stream file content chunks with proxy logging, error handling, and cleanup', 'create a FastAPI StreamingResponse for streaming file content with custom headers', 'build a file content streaming handler class that resolves streaming params and returns FastAPI StreamingResponse', 'create a file upload endpoint for Assistants API, Batch API, or fine-tuning via POST /v1/files', 'list uploaded files with optional provider, target_model_names, and purpose filters via GET /v1/files', 'retrieve metadata for a specific file by file_id via GET /v1/files/{file_id}', 'download the raw content of a file by file_id via GET /v1/files/{file_id}/content', 'delete a specific file by file_id via DELETE /v1/files/{file_id}', 'set the files_config with a list of provider configurations including custom_llm_provider and credentials', 'route a file creation request to the appropriate provider using model-based routing or managed files', 'handle model-based credential routing for file operations using encoded file IDs']
```

Usage

```
{'resolve_streaming_request_params': 'resolve the provider, file ID, and request payload for streaming file content requests', 'should_stream_file_content': 'check if a custom LLM provider supports streaming file content', 'stream_file_content_with_logging': 'stream file content chunks with proxy logging, error handling, and cleanup', 'get_streaming_file_content_response': 'create a FastAPI StreamingResponse for streaming file content with custom headers', 'build_file_content_streaming_handler': 'build a file content streaming handler class that resolves streaming params and returns FastAPI StreamingResponse'}
```

## File: berriai_litellm/litellm/proxy/openai_files_endpoints/files_endpoints.py

Prompts

```
['encode a file or batch ID with model routing information using base64 encoding', 'decode the model name from an encoded file or batch ID containing embedded routing info', 'extract the original provider file or batch ID from an encoded ID', 'orchestrate model-based credential routing for file operations using embedded or request model params', 'extract structured file creation parameters from a FastAPI request including storage and model names', 'test if a MIME type is supported by Gemini multimodal models for images, video, audio, and documents', 'update batch status and object in the managed object database table', 'resolve the provider, file ID, and request payload for streaming file content requests', 'check if a custom LLM provider supports streaming file content', 'stream file content chunks with proxy logging, error handling, and cleanup', 'create a FastAPI StreamingResponse for streaming file content with custom headers', 'build a file content streaming handler class that resolves streaming params and returns FastAPI StreamingResponse', 'create a file upload endpoint for Assistants API, Batch API, or fine-tuning via POST /v1/files', 'list uploaded files with optional provider, target_model_names, and purpose filters via GET /v1/files', 'retrieve metadata for a specific file by file_id via GET /v1/files/{file_id}', 'download the raw content of a file by file_id via GET /v1/files/{file_id}/content', 'delete a specific file by file_id via DELETE /v1/files/{file_id}', 'set the files_config with a list of provider configurations including custom_llm_provider and credentials', 'route a file creation request to the appropriate provider using model-based routing or managed files', 'handle model-based credential routing for file operations using encoded file IDs']
```

Usage

```
{'create_upload_file': 'create a file upload endpoint for Assistants API, Batch API, or fine-tuning via POST /v1/files', 'create_list_files': 'list uploaded files with optional provider, target_model_names, and purpose filters via GET /v1/files', 'create_retrieve_file': 'retrieve metadata for a specific file by file_id via GET /v1/files/{file_id}', 'create_retrieve_file_content': 'download the raw content of a file by file_id via GET /v1/files/{file_id}/content', 'create_delete_file': 'delete a specific file by file_id via DELETE /v1/files/{file_id}', 'create_set_files_config': 'set the files_config with a list of provider configurations including custom_llm_provider and credentials', 'create_route_create_file': 'route a file creation request to the appropriate provider using model-based routing or managed files', 'create_handle_model_based_routing': 'handle model-based credential routing for file operations using encoded file IDs'}
```

