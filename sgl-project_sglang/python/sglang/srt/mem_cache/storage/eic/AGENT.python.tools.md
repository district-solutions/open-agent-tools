# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/eic/eic_storage.py

Prompts

```
['build an EICStorage instance for distributed KV cache storage with HiCacheStorageConfig and HostKVCache memory pool', 'create a FlexibleKVCacheMemoryPool for managing tensor allocations with eic connection and configurable device', 'test the EICStorage batch_set method to store KV cache tensors with zero-copy or generic transfer modes', 'run the EICStorage batch_get method to retrieve KV cache tensors using keys and host indices', 'review the EICStorage batch_exists method to check prefix existence of cached KV entries', 'build an EIC client from a YAML config file with remote URL and instance ID', 'test the EIC client mset method to store 16 bfloat16 tensors with a 3-second TTL', 'test the EIC client mget method to retrieve 16 bfloat16 tensors by key', 'test the EIC client mexist method to check existence of 16 keys', 'run the main test suite initializing the client then testing set, exists, and get operations']
```

Usage

```
{'build_eic_storage': 'build an EICStorage instance for distributed KV cache storage with HiCacheStorageConfig and HostKVCache memory pool', 'create_flexible_kv_cache_memory_pool': 'create a FlexibleKVCacheMemoryPool for managing tensor allocations with eic connection and configurable device', 'test_eic_batch_set': 'test the EICStorage batch_set method to store KV cache tensors with zero-copy or generic transfer modes', 'run_eic_batch_get': 'run the EICStorage batch_get method to retrieve KV cache tensors using keys and host indices', 'review_eic_batch_exists': 'review the EICStorage batch_exists method to check prefix existence of cached KV entries'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/eic/test_unit.py

Prompts

```
['build an EICStorage instance for distributed KV cache storage with HiCacheStorageConfig and HostKVCache memory pool', 'create a FlexibleKVCacheMemoryPool for managing tensor allocations with eic connection and configurable device', 'test the EICStorage batch_set method to store KV cache tensors with zero-copy or generic transfer modes', 'run the EICStorage batch_get method to retrieve KV cache tensors using keys and host indices', 'review the EICStorage batch_exists method to check prefix existence of cached KV entries', 'build an EIC client from a YAML config file with remote URL and instance ID', 'test the EIC client mset method to store 16 bfloat16 tensors with a 3-second TTL', 'test the EIC client mget method to retrieve 16 bfloat16 tensors by key', 'test the EIC client mexist method to check existence of 16 keys', 'run the main test suite initializing the client then testing set, exists, and get operations']
```

Usage

```
{'build_eic_client': 'build an EIC client from a YAML config file with remote URL and instance ID', 'test_set_tensors': 'test the EIC client mset method to store 16 bfloat16 tensors with a 3-second TTL', 'test_get_tensors': 'test the EIC client mget method to retrieve 16 bfloat16 tensors by key', 'test_exists_keys': 'test the EIC client mexist method to check existence of 16 keys', 'run_main_tests': 'run the main test suite initializing the client then testing set, exists, and get operations'}
```

