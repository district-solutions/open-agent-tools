# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/enterprise/litellm_enterprise/proxy/hooks/managed_files.py

Prompts

```
['create a managed file across multiple LLM providers and store unified file ID mappings', 'retrieve a LiteLLM managed file object by its unified file ID from cache or provider', 'delete a managed file across all providers and clean up unified file ID mappings', 'check if a user has access to a specific unified file ID or object ID', 'convert storage backend files to base64 data URIs for Vertex AI Gemini compatibility', 'create a managed vector store across multiple models with a unified ID using the litellm proxy', 'list all vector stores created by a user with pagination support using the litellm proxy', 'check if a user has access to a specific managed vector store by its unified ID', 'handle pre-call hook for vector store search operations that validates access and transforms unified IDs to provider IDs', 'filter healthy deployments to only those that have the requested vector store available']
```

Usage

```
{'create_managed_file_acreate_file': 'create a managed file across multiple LLM providers and store unified file ID mappings', 'retrieve_managed_file_afile_retrieve': 'retrieve a LiteLLM managed file object by its unified file ID from cache or provider', 'delete_managed_file_afile_delete': 'delete a managed file across all providers and clean up unified file ID mappings', 'check_file_access_can_user_call': 'check if a user has access to a specific unified file ID or object ID', 'convert_storage_to_base64_convert_storage_files': 'convert storage backend files to base64 data URIs for Vertex AI Gemini compatibility'}
```

## File: berriai_litellm/enterprise/litellm_enterprise/proxy/hooks/managed_vector_stores.py

Prompts

```
['create a managed file across multiple LLM providers and store unified file ID mappings', 'retrieve a LiteLLM managed file object by its unified file ID from cache or provider', 'delete a managed file across all providers and clean up unified file ID mappings', 'check if a user has access to a specific unified file ID or object ID', 'convert storage backend files to base64 data URIs for Vertex AI Gemini compatibility', 'create a managed vector store across multiple models with a unified ID using the litellm proxy', 'list all vector stores created by a user with pagination support using the litellm proxy', 'check if a user has access to a specific managed vector store by its unified ID', 'handle pre-call hook for vector store search operations that validates access and transforms unified IDs to provider IDs', 'filter healthy deployments to only those that have the requested vector store available']
```

Usage

```
{'create_managed_vector_store': 'create a managed vector store across multiple models with a unified ID using the litellm proxy', 'list_vector_stores': 'list all vector stores created by a user with pagination support using the litellm proxy', 'check_vector_store_access': 'check if a user has access to a specific managed vector store by its unified ID', 'handle_vector_store_pre_call_hook': 'handle pre-call hook for vector store search operations that validates access and transforms unified IDs to provider IDs', 'filter_deployments_by_vector_store': 'filter healthy deployments to only those that have the requested vector store available'}
```

