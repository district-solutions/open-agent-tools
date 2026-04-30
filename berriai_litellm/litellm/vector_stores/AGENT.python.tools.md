# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/vector_stores/main.py

Prompts

```
['create a vector store with a name, file IDs, expiration policy, and metadata using LiteLLM', 'search a vector store by query string and return ranked results with scores and text content', 'retrieve a vector store by its ID to get its name, status, and file counts', 'update a vector store name, expiration policy, or metadata by vector store ID', 'delete a vector store by its ID and confirm the deletion', 'filter a dictionary of parameters to only those valid for VectorStoreSearchOptionalRequestParams', 'map openai-style parameters for vector store search using a provider config', 'filter a dictionary of parameters to only those valid for VectorStoreCreateOptionalRequestParams', 'use the VectorStoreRequestUtils class to construct vector store search and create request parameters', 'validate and cast vector store request parameters against their type hint schemas', 'build a VectorStoreRegistry instance and load vector stores from a config list', 'create vector store instances to run by popping vector_store_ids from params and merging tool parameters', 'test the VectorStoreIndexRegistry.get_vector_store_index_by_name method to find an index by name', 'review the VectorStoreRegistry.pop_vector_stores_to_run_with_db_fallback method for cache invalidation and db sync', 'summarize the VectorStoreRegistry.get_credentials_for_vector_store method for credential retrieval']
```

Usage

```
{'create_vector_store': 'create a vector store with a name, file IDs, expiration policy, and metadata using LiteLLM', 'search_vector_store': 'search a vector store by query string and return ranked results with scores and text content', 'retrieve_vector_store': 'retrieve a vector store by its ID to get its name, status, and file counts', 'update_vector_store': 'update a vector store name, expiration policy, or metadata by vector store ID', 'delete_vector_store': 'delete a vector store by its ID and confirm the deletion'}
```

## File: berriai_litellm/litellm/vector_stores/utils.py

Prompts

```
['create a vector store with a name, file IDs, expiration policy, and metadata using LiteLLM', 'search a vector store by query string and return ranked results with scores and text content', 'retrieve a vector store by its ID to get its name, status, and file counts', 'update a vector store name, expiration policy, or metadata by vector store ID', 'delete a vector store by its ID and confirm the deletion', 'filter a dictionary of parameters to only those valid for VectorStoreSearchOptionalRequestParams', 'map openai-style parameters for vector store search using a provider config', 'filter a dictionary of parameters to only those valid for VectorStoreCreateOptionalRequestParams', 'use the VectorStoreRequestUtils class to construct vector store search and create request parameters', 'validate and cast vector store request parameters against their type hint schemas', 'build a VectorStoreRegistry instance and load vector stores from a config list', 'create vector store instances to run by popping vector_store_ids from params and merging tool parameters', 'test the VectorStoreIndexRegistry.get_vector_store_index_by_name method to find an index by name', 'review the VectorStoreRegistry.pop_vector_stores_to_run_with_db_fallback method for cache invalidation and db sync', 'summarize the VectorStoreRegistry.get_credentials_for_vector_store method for credential retrieval']
```

Usage

```
{'filter_vector_store_search_params': 'filter a dictionary of parameters to only those valid for VectorStoreSearchOptionalRequestParams', 'map_vector_store_search_params': 'map openai-style parameters for vector store search using a provider config', 'filter_vector_store_create_params': 'filter a dictionary of parameters to only those valid for VectorStoreCreateOptionalRequestParams', 'use_VectorStoreRequestUtils': 'use the VectorStoreRequestUtils class to construct vector store search and create request parameters', 'validate_vector_store_params': 'validate and cast vector store request parameters against their type hint schemas'}
```

## File: berriai_litellm/litellm/vector_stores/vector_store_registry.py

Prompts

```
['create a vector store with a name, file IDs, expiration policy, and metadata using LiteLLM', 'search a vector store by query string and return ranked results with scores and text content', 'retrieve a vector store by its ID to get its name, status, and file counts', 'update a vector store name, expiration policy, or metadata by vector store ID', 'delete a vector store by its ID and confirm the deletion', 'filter a dictionary of parameters to only those valid for VectorStoreSearchOptionalRequestParams', 'map openai-style parameters for vector store search using a provider config', 'filter a dictionary of parameters to only those valid for VectorStoreCreateOptionalRequestParams', 'use the VectorStoreRequestUtils class to construct vector store search and create request parameters', 'validate and cast vector store request parameters against their type hint schemas', 'build a VectorStoreRegistry instance and load vector stores from a config list', 'create vector store instances to run by popping vector_store_ids from params and merging tool parameters', 'test the VectorStoreIndexRegistry.get_vector_store_index_by_name method to find an index by name', 'review the VectorStoreRegistry.pop_vector_stores_to_run_with_db_fallback method for cache invalidation and db sync', 'summarize the VectorStoreRegistry.get_credentials_for_vector_store method for credential retrieval']
```

Usage

```
{'build_VectorStoreRegistry': 'build a VectorStoreRegistry instance and load vector stores from a config list', 'create_pop_vector_stores_to_run': 'create vector store instances to run by popping vector_store_ids from params and merging tool parameters', 'test_get_vector_store_index_by_name': 'test the VectorStoreIndexRegistry.get_vector_store_index_by_name method to find an index by name', 'review_pop_vector_stores_to_run_with_db_fallback': 'review the VectorStoreRegistry.pop_vector_stores_to_run_with_db_fallback method for cache invalidation and db sync', 'summarize_get_credentials_for_vector_store': 'summarize the VectorStoreRegistry.get_credentials_for_vector_store method for credential retrieval'}
```

