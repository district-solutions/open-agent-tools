# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/simm/hicache_simm.py

Prompts

```
['build a HiCacheSiMM storage instance with a HiCacheStorageConfig for SGLang KV cache offloading', 'create a SiMMConfig from a JSON file or extra_config dictionary with manager_address and threadpool settings', 'test the HiCacheSiMM batch_get_v1 method to retrieve KV cache blocks via zero-copy RDMA reads', 'run the HiCacheSiMM batch_set_v1 method to store KV cache blocks with zero-copy RDMA writes skipping existing keys', 'review the HiCacheSiMM class and its batch KV cache operations with MHA and MLA backend support', 'test the HiCacheSiMM set, exists, and get APIs with a single key-value pair', 'test the HiCacheSiMM batch_set_v1, batch_get_v1, and batch_exists APIs with multiple key-value pairs', 'create a mock HostKVCache object with a torch tensor buffer for testing HiCacheSiMM', 'generate batch set keys, get keys, and exist keys for HiCacheSiMM test operations', 'test HiCacheSiMM with MLA model configuration using different tp_rank and tp_size values']
```

Usage

```
{'build_HiCacheSiMM': 'build a HiCacheSiMM storage instance with a HiCacheStorageConfig for SGLang KV cache offloading', 'create_SiMMConfig': 'create a SiMMConfig from a JSON file or extra_config dictionary with manager_address and threadpool settings', 'test_batch_get_v1': 'test the HiCacheSiMM batch_get_v1 method to retrieve KV cache blocks via zero-copy RDMA reads', 'run_batch_set_v1': 'run the HiCacheSiMM batch_set_v1 method to store KV cache blocks with zero-copy RDMA writes skipping existing keys', 'review_HiCacheSiMM': 'review the HiCacheSiMM class and its batch KV cache operations with MHA and MLA backend support'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/simm/test_simm.py

Prompts

```
['build a HiCacheSiMM storage instance with a HiCacheStorageConfig for SGLang KV cache offloading', 'create a SiMMConfig from a JSON file or extra_config dictionary with manager_address and threadpool settings', 'test the HiCacheSiMM batch_get_v1 method to retrieve KV cache blocks via zero-copy RDMA reads', 'run the HiCacheSiMM batch_set_v1 method to store KV cache blocks with zero-copy RDMA writes skipping existing keys', 'review the HiCacheSiMM class and its batch KV cache operations with MHA and MLA backend support', 'test the HiCacheSiMM set, exists, and get APIs with a single key-value pair', 'test the HiCacheSiMM batch_set_v1, batch_get_v1, and batch_exists APIs with multiple key-value pairs', 'create a mock HostKVCache object with a torch tensor buffer for testing HiCacheSiMM', 'generate batch set keys, get keys, and exist keys for HiCacheSiMM test operations', 'test HiCacheSiMM with MLA model configuration using different tp_rank and tp_size values']
```

Usage

```
{'test_single_operation': 'test the HiCacheSiMM set, exists, and get APIs with a single key-value pair', 'test_batch_operation': 'test the HiCacheSiMM batch_set_v1, batch_get_v1, and batch_exists APIs with multiple key-value pairs', 'create_mock_host_kv_cache': 'create a mock HostKVCache object with a torch tensor buffer for testing HiCacheSiMM', 'generate_batch_query_keys': 'generate batch set keys, get keys, and exist keys for HiCacheSiMM test operations', 'test_HiCacheSiMM_mla_model': 'test HiCacheSiMM with MLA model configuration using different tp_rank and tp_size values'}
```

