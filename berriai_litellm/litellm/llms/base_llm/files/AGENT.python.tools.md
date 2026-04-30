# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/base_llm/files/storage_backend_factory.py

Prompts

```
['create a storage backend instance by calling get_storage_backend with backend_type like azure_storage', 'test get_storage_backend returns AzureBlobStorageBackend when backend_type is azure_storage', 'test get_storage_backend raises ValueError for unsupported backend_type', 'review the get_storage_backend factory function that dispatches to AzureBlobStorageBackend', 'summarize the get_storage_backend factory function and its supported backend types', 'create a file upload request transformed to provider-specific format for LLM providers', 'retrieve file metadata by file ID and transform response into OpenAI file object format', 'delete a file by its ID and transform the response into OpenAI FileDeleted format', 'list uploaded files filtered by purpose and transform response into OpenAI file objects', 'retrieve the binary content of a file by its file ID']
```

Usage

```
{'create_get_storage_backend': 'create a storage backend instance by calling get_storage_backend with backend_type like azure_storage', 'test_get_storage_backend': 'test get_storage_backend returns AzureBlobStorageBackend when backend_type is azure_storage', 'test_get_storage_backend_error': 'test get_storage_backend raises ValueError for unsupported backend_type', 'review_get_storage_backend': 'review the get_storage_backend factory function that dispatches to AzureBlobStorageBackend', 'summarize_get_storage_backend': 'summarize the get_storage_backend factory function and its supported backend types'}
```

## File: berriai_litellm/litellm/llms/base_llm/files/transformation.py

Prompts

```
['create a storage backend instance by calling get_storage_backend with backend_type like azure_storage', 'test get_storage_backend returns AzureBlobStorageBackend when backend_type is azure_storage', 'test get_storage_backend raises ValueError for unsupported backend_type', 'review the get_storage_backend factory function that dispatches to AzureBlobStorageBackend', 'summarize the get_storage_backend factory function and its supported backend types', 'create a file upload request transformed to provider-specific format for LLM providers', 'retrieve file metadata by file ID and transform response into OpenAI file object format', 'delete a file by its ID and transform the response into OpenAI FileDeleted format', 'list uploaded files filtered by purpose and transform response into OpenAI file objects', 'retrieve the binary content of a file by its file ID']
```

Usage

```
{'create_file_upload': 'create a file upload request transformed to provider-specific format for LLM providers', 'retrieve_file_metadata': 'retrieve file metadata by file ID and transform response into OpenAI file object format', 'delete_file_by_id': 'delete a file by its ID and transform the response into OpenAI FileDeleted format', 'list_files_by_purpose': 'list uploaded files filtered by purpose and transform response into OpenAI file objects', 'get_file_content': 'retrieve the binary content of a file by its file ID'}
```

