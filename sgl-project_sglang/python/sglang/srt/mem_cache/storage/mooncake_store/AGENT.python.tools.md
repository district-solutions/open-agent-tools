# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/mooncake_store/embedding_cache_controller.py

Prompts

```
['create an EmbeddingCacheController instance with tp_rank, tp_size, and max_pool_size_gb for distributed embedding cache management', 'build a batch prefetch operation for missing image embeddings using req_id and image_hashes from the Mooncake cluster', 'insert a batch of newly computed embedding tensors into the Mooncake distributed cache', 'test the check_prefetch_progress method to verify all TP ranks have the request batch ready', 'get cached embedding tensors from the local pool by image_hashes for model input reconstruction', 'create a MooncakeEmbeddingStore instance with storage configuration for embedding data management', 'get a prefixed key string from an image hash for embedding store lookups', 'batch get embedding data by hashes, pointers, and sizes from the mooncake store', 'batch put embedding data by hashes, pointers, and sizes into the mooncake store', 'batch check if embedding entries exist in the mooncake store by their hashes', 'create MooncakeStoreConfig from environment variables for Mooncake distributed store setup', 'build MooncakeStore instance with HiCacheStorageConfig and HostKVCache memory pool', 'test MooncakeStore batch_get_v2 for zero-copy retrieval of KV cache pages from distributed storage', 'refactor MooncakeStore batch_set_v2 for zero-copy storage of KV cache pages with hybrid pool support', 'summarize MooncakeStore batch_exists_v2 for checking existence of KV cache pages across multiple pool types', 'test the MooncakeStore set and get operations with a single key-value pair', 'test the MooncakeStore batch_set and batch_get operations with multiple key-value pairs', 'test the MooncakeStore batch_exists operation to verify multiple keys exist after batch set', 'test the MooncakeStore register_mem_pool_host method to register a mock HostKVCache memory pool', 'test the test_single_operation function that exercises set, get, and exists on a single key', 'test the test_batch_operation function with HiCacheStorageConfig for batch set and get']
```

Usage

```
{'create_EmbeddingCacheController': 'create an EmbeddingCacheController instance with tp_rank, tp_size, and max_pool_size_gb for distributed embedding cache management', 'build_prefetch_batch': 'build a batch prefetch operation for missing image embeddings using req_id and image_hashes from the Mooncake cluster', 'insert_batch_embeddings': 'insert a batch of newly computed embedding tensors into the Mooncake distributed cache', 'test_check_prefetch_progress': 'test the check_prefetch_progress method to verify all TP ranks have the request batch ready', 'get_cached_embeddings': 'get cached embedding tensors from the local pool by image_hashes for model input reconstruction'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/mooncake_store/mooncake_embedding_store.py

Prompts

```
['create an EmbeddingCacheController instance with tp_rank, tp_size, and max_pool_size_gb for distributed embedding cache management', 'build a batch prefetch operation for missing image embeddings using req_id and image_hashes from the Mooncake cluster', 'insert a batch of newly computed embedding tensors into the Mooncake distributed cache', 'test the check_prefetch_progress method to verify all TP ranks have the request batch ready', 'get cached embedding tensors from the local pool by image_hashes for model input reconstruction', 'create a MooncakeEmbeddingStore instance with storage configuration for embedding data management', 'get a prefixed key string from an image hash for embedding store lookups', 'batch get embedding data by hashes, pointers, and sizes from the mooncake store', 'batch put embedding data by hashes, pointers, and sizes into the mooncake store', 'batch check if embedding entries exist in the mooncake store by their hashes', 'create MooncakeStoreConfig from environment variables for Mooncake distributed store setup', 'build MooncakeStore instance with HiCacheStorageConfig and HostKVCache memory pool', 'test MooncakeStore batch_get_v2 for zero-copy retrieval of KV cache pages from distributed storage', 'refactor MooncakeStore batch_set_v2 for zero-copy storage of KV cache pages with hybrid pool support', 'summarize MooncakeStore batch_exists_v2 for checking existence of KV cache pages across multiple pool types', 'test the MooncakeStore set and get operations with a single key-value pair', 'test the MooncakeStore batch_set and batch_get operations with multiple key-value pairs', 'test the MooncakeStore batch_exists operation to verify multiple keys exist after batch set', 'test the MooncakeStore register_mem_pool_host method to register a mock HostKVCache memory pool', 'test the test_single_operation function that exercises set, get, and exists on a single key', 'test the test_batch_operation function with HiCacheStorageConfig for batch set and get']
```

Usage

```
{'create_mooncake_embedding_store': 'create a MooncakeEmbeddingStore instance with storage configuration for embedding data management', 'get_key_from_image_hash': 'get a prefixed key string from an image hash for embedding store lookups', 'batch_get_embeddings': 'batch get embedding data by hashes, pointers, and sizes from the mooncake store', 'batch_put_embeddings': 'batch put embedding data by hashes, pointers, and sizes into the mooncake store', 'batch_is_exist_embeddings': 'batch check if embedding entries exist in the mooncake store by their hashes'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/mooncake_store/mooncake_store.py

Prompts

```
['create an EmbeddingCacheController instance with tp_rank, tp_size, and max_pool_size_gb for distributed embedding cache management', 'build a batch prefetch operation for missing image embeddings using req_id and image_hashes from the Mooncake cluster', 'insert a batch of newly computed embedding tensors into the Mooncake distributed cache', 'test the check_prefetch_progress method to verify all TP ranks have the request batch ready', 'get cached embedding tensors from the local pool by image_hashes for model input reconstruction', 'create a MooncakeEmbeddingStore instance with storage configuration for embedding data management', 'get a prefixed key string from an image hash for embedding store lookups', 'batch get embedding data by hashes, pointers, and sizes from the mooncake store', 'batch put embedding data by hashes, pointers, and sizes into the mooncake store', 'batch check if embedding entries exist in the mooncake store by their hashes', 'create MooncakeStoreConfig from environment variables for Mooncake distributed store setup', 'build MooncakeStore instance with HiCacheStorageConfig and HostKVCache memory pool', 'test MooncakeStore batch_get_v2 for zero-copy retrieval of KV cache pages from distributed storage', 'refactor MooncakeStore batch_set_v2 for zero-copy storage of KV cache pages with hybrid pool support', 'summarize MooncakeStore batch_exists_v2 for checking existence of KV cache pages across multiple pool types', 'test the MooncakeStore set and get operations with a single key-value pair', 'test the MooncakeStore batch_set and batch_get operations with multiple key-value pairs', 'test the MooncakeStore batch_exists operation to verify multiple keys exist after batch set', 'test the MooncakeStore register_mem_pool_host method to register a mock HostKVCache memory pool', 'test the test_single_operation function that exercises set, get, and exists on a single key', 'test the test_batch_operation function with HiCacheStorageConfig for batch set and get']
```

Usage

```
{'create_MooncakeStoreConfig_load_from_env': 'create MooncakeStoreConfig from environment variables for Mooncake distributed store setup', 'build_MooncakeStore_init': 'build MooncakeStore instance with HiCacheStorageConfig and HostKVCache memory pool', 'test_MooncakeStore_batch_get_v2': 'test MooncakeStore batch_get_v2 for zero-copy retrieval of KV cache pages from distributed storage', 'refactor_MooncakeStore_batch_set_v2': 'refactor MooncakeStore batch_set_v2 for zero-copy storage of KV cache pages with hybrid pool support', 'summarize_MooncakeStore_batch_exists_v2': 'summarize MooncakeStore batch_exists_v2 for checking existence of KV cache pages across multiple pool types'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/mooncake_store/test_mooncake_store.py

Prompts

```
['create an EmbeddingCacheController instance with tp_rank, tp_size, and max_pool_size_gb for distributed embedding cache management', 'build a batch prefetch operation for missing image embeddings using req_id and image_hashes from the Mooncake cluster', 'insert a batch of newly computed embedding tensors into the Mooncake distributed cache', 'test the check_prefetch_progress method to verify all TP ranks have the request batch ready', 'get cached embedding tensors from the local pool by image_hashes for model input reconstruction', 'create a MooncakeEmbeddingStore instance with storage configuration for embedding data management', 'get a prefixed key string from an image hash for embedding store lookups', 'batch get embedding data by hashes, pointers, and sizes from the mooncake store', 'batch put embedding data by hashes, pointers, and sizes into the mooncake store', 'batch check if embedding entries exist in the mooncake store by their hashes', 'create MooncakeStoreConfig from environment variables for Mooncake distributed store setup', 'build MooncakeStore instance with HiCacheStorageConfig and HostKVCache memory pool', 'test MooncakeStore batch_get_v2 for zero-copy retrieval of KV cache pages from distributed storage', 'refactor MooncakeStore batch_set_v2 for zero-copy storage of KV cache pages with hybrid pool support', 'summarize MooncakeStore batch_exists_v2 for checking existence of KV cache pages across multiple pool types', 'test the MooncakeStore set and get operations with a single key-value pair', 'test the MooncakeStore batch_set and batch_get operations with multiple key-value pairs', 'test the MooncakeStore batch_exists operation to verify multiple keys exist after batch set', 'test the MooncakeStore register_mem_pool_host method to register a mock HostKVCache memory pool', 'test the test_single_operation function that exercises set, get, and exists on a single key', 'test the test_batch_operation function with HiCacheStorageConfig for batch set and get']
```

Usage

```
{'test_single_set_get': 'test the MooncakeStore set and get operations with a single key-value pair', 'test_batch_set_get': 'test the MooncakeStore batch_set and batch_get operations with multiple key-value pairs', 'test_batch_exists': 'test the MooncakeStore batch_exists operation to verify multiple keys exist after batch set', 'test_register_mem_pool_host': 'test the MooncakeStore register_mem_pool_host method to register a mock HostKVCache memory pool', 'test_single_operation': 'test the test_single_operation function that exercises set, get, and exists on a single key', 'test_batch_operation': 'test the test_batch_operation function with HiCacheStorageConfig for batch set and get'}
```

