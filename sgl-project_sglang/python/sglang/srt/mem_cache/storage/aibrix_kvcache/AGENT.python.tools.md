# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/aibrix_kvcache/aibrix_kvcache_storage.py

Prompts

```
['create an AibrixKVCacheStorage instance with HiCacheStorageConfig and HostKVCache memory pool', 'run batch_get to retrieve multiple KV cache blocks by list of string keys into target locations', 'run batch_set to store multiple KV cache tensor values into KV cache by list of string keys', 'test batch_exists to check how many of a list of string keys exist in the KV cache', 'run get to retrieve a single KV cache block by key into a target torch tensor location', 'build a HiCacheStorageConfig with tp_rank, tp_size, model_name, and layout settings for KV cache storage', 'create an MHATokenToKVPool CPU memory pool with page_size, head_num, head_dim, and layer_num parameters', 'test the AibrixKVCacheStorage batch_set method to store KV cache tensors with string hash keys', 'test the AibrixKVCacheStorage batch_get method to retrieve stored KV cache tensors by hash keys', 'test the AibrixKVCacheStorage batch_exists method to check which keys have cached KV tensors']
```

Usage

```
{'create_AibrixKVCacheStorage': 'create an AibrixKVCacheStorage instance with HiCacheStorageConfig and HostKVCache memory pool', 'run_batch_get': 'run batch_get to retrieve multiple KV cache blocks by list of string keys into target locations', 'run_batch_set': 'run batch_set to store multiple KV cache tensor values into KV cache by list of string keys', 'test_batch_exists': 'test batch_exists to check how many of a list of string keys exist in the KV cache', 'run_get': 'run get to retrieve a single KV cache block by key into a target torch tensor location'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/aibrix_kvcache/unit_test.py

Prompts

```
['create an AibrixKVCacheStorage instance with HiCacheStorageConfig and HostKVCache memory pool', 'run batch_get to retrieve multiple KV cache blocks by list of string keys into target locations', 'run batch_set to store multiple KV cache tensor values into KV cache by list of string keys', 'test batch_exists to check how many of a list of string keys exist in the KV cache', 'run get to retrieve a single KV cache block by key into a target torch tensor location', 'build a HiCacheStorageConfig with tp_rank, tp_size, model_name, and layout settings for KV cache storage', 'create an MHATokenToKVPool CPU memory pool with page_size, head_num, head_dim, and layer_num parameters', 'test the AibrixKVCacheStorage batch_set method to store KV cache tensors with string hash keys', 'test the AibrixKVCacheStorage batch_get method to retrieve stored KV cache tensors by hash keys', 'test the AibrixKVCacheStorage batch_exists method to check which keys have cached KV tensors']
```

Usage

```
{'build_HiCacheStorageConfig': 'build a HiCacheStorageConfig with tp_rank, tp_size, model_name, and layout settings for KV cache storage', 'create_MHATokenToKVPool': 'create an MHATokenToKVPool CPU memory pool with page_size, head_num, head_dim, and layer_num parameters', 'test_AIBrixKVCacheStorage_batch_set': 'test the AibrixKVCacheStorage batch_set method to store KV cache tensors with string hash keys', 'test_AIBrixKVCacheStorage_batch_get': 'test the AibrixKVCacheStorage batch_get method to retrieve stored KV cache tensors by hash keys', 'test_AIBrixKVCacheStorage_batch_exists': 'test the AibrixKVCacheStorage batch_exists method to check which keys have cached KV tensors'}
```

