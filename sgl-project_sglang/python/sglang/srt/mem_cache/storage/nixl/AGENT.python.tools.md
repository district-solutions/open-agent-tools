# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/nixl/hicache_nixl.py

Prompts

```
['create a HiCacheNixl storage backend with NIXL agent for high-performance KV cache transfer', 'register torch tensor buffers with NIXL for zero-copy memory transfers', 'batch get KV cache pages from NIXL storage into host memory using zero-copy or non-zero-copy mode', 'batch set KV cache pages from host memory to NIXL storage with file or object backend', 'check which keys exist in NIXL storage and return count of present keys', 'build a NixlBackendConfig to parse plugin backend configurations from a dictionary', 'create a NixlBackendSelection to auto-select or specify a NIXL backend plugin and create it', 'test NixlRegistration.create_query_tuples to generate NIXL memory query tuples for FILE or OBJ memory types', 'refactor NixlRegistration._register_memory to register tensor or file memory descriptors with a NIXL agent', 'review NixlFileManager for creating, opening, and managing file descriptors for NIXL file-based storage', 'test HiCacheNixl set and get operations for single and batch tensor storage with key-based and address-based APIs', 'test NixlFileManager create_file and files_to_nixl_tuples for managing NIXL-backed storage files', 'test HiCacheNixl batch_set and batch_get operations for bulk tensor storage and retrieval', 'test HiCacheNixl data integrity across float32, float64, int32, int64, and bool tensor types', 'test NixlRegistration register_buffers for memory buffer registration with NIXL agent']
```

Usage

```
{'create_HiCacheNixl_backend': 'create a HiCacheNixl storage backend with NIXL agent for high-performance KV cache transfer', 'register_buffers_with_nixl': 'register torch tensor buffers with NIXL for zero-copy memory transfers', 'batch_get_v1_from_storage': 'batch get KV cache pages from NIXL storage into host memory using zero-copy or non-zero-copy mode', 'batch_set_v1_to_storage': 'batch set KV cache pages from host memory to NIXL storage with file or object backend', 'batch_exists_in_storage': 'check which keys exist in NIXL storage and return count of present keys'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/nixl/nixl_utils.py

Prompts

```
['create a HiCacheNixl storage backend with NIXL agent for high-performance KV cache transfer', 'register torch tensor buffers with NIXL for zero-copy memory transfers', 'batch get KV cache pages from NIXL storage into host memory using zero-copy or non-zero-copy mode', 'batch set KV cache pages from host memory to NIXL storage with file or object backend', 'check which keys exist in NIXL storage and return count of present keys', 'build a NixlBackendConfig to parse plugin backend configurations from a dictionary', 'create a NixlBackendSelection to auto-select or specify a NIXL backend plugin and create it', 'test NixlRegistration.create_query_tuples to generate NIXL memory query tuples for FILE or OBJ memory types', 'refactor NixlRegistration._register_memory to register tensor or file memory descriptors with a NIXL agent', 'review NixlFileManager for creating, opening, and managing file descriptors for NIXL file-based storage', 'test HiCacheNixl set and get operations for single and batch tensor storage with key-based and address-based APIs', 'test NixlFileManager create_file and files_to_nixl_tuples for managing NIXL-backed storage files', 'test HiCacheNixl batch_set and batch_get operations for bulk tensor storage and retrieval', 'test HiCacheNixl data integrity across float32, float64, int32, int64, and bool tensor types', 'test NixlRegistration register_buffers for memory buffer registration with NIXL agent']
```

Usage

```
{'build_nixl_backend_config': 'build a NixlBackendConfig to parse plugin backend configurations from a dictionary', 'create_nixl_backend_selection': 'create a NixlBackendSelection to auto-select or specify a NIXL backend plugin and create it', 'test_nixl_registration_query_tuples': 'test NixlRegistration.create_query_tuples to generate NIXL memory query tuples for FILE or OBJ memory types', 'refactor_nixl_registration_register_memory': 'refactor NixlRegistration._register_memory to register tensor or file memory descriptors with a NIXL agent', 'review_nixl_file_manager': 'review NixlFileManager for creating, opening, and managing file descriptors for NIXL file-based storage'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/nixl/test_hicache_nixl_storage.py

Prompts

```
['create a HiCacheNixl storage backend with NIXL agent for high-performance KV cache transfer', 'register torch tensor buffers with NIXL for zero-copy memory transfers', 'batch get KV cache pages from NIXL storage into host memory using zero-copy or non-zero-copy mode', 'batch set KV cache pages from host memory to NIXL storage with file or object backend', 'check which keys exist in NIXL storage and return count of present keys', 'build a NixlBackendConfig to parse plugin backend configurations from a dictionary', 'create a NixlBackendSelection to auto-select or specify a NIXL backend plugin and create it', 'test NixlRegistration.create_query_tuples to generate NIXL memory query tuples for FILE or OBJ memory types', 'refactor NixlRegistration._register_memory to register tensor or file memory descriptors with a NIXL agent', 'review NixlFileManager for creating, opening, and managing file descriptors for NIXL file-based storage', 'test HiCacheNixl set and get operations for single and batch tensor storage with key-based and address-based APIs', 'test NixlFileManager create_file and files_to_nixl_tuples for managing NIXL-backed storage files', 'test HiCacheNixl batch_set and batch_get operations for bulk tensor storage and retrieval', 'test HiCacheNixl data integrity across float32, float64, int32, int64, and bool tensor types', 'test NixlRegistration register_buffers for memory buffer registration with NIXL agent']
```

Usage

```
{'test_HiCacheNixl_set_get': 'test HiCacheNixl set and get operations for single and batch tensor storage with key-based and address-based APIs', 'test_NixlFileManager_create_file': 'test NixlFileManager create_file and files_to_nixl_tuples for managing NIXL-backed storage files', 'test_HiCacheNixl_batch_operations': 'test HiCacheNixl batch_set and batch_get operations for bulk tensor storage and retrieval', 'test_HiCacheNixl_data_integrity': 'test HiCacheNixl data integrity across float32, float64, int32, int64, and bool tensor types', 'test_NixlRegistration_register_buffers': 'test NixlRegistration register_buffers for memory buffer registration with NIXL agent'}
```

