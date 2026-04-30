# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/v1/kv_offload/cpu/policies/arc.py

Prompts

```
['create an ARCCachePolicy instance with a given cache capacity for adaptive KV block caching', 'test the ARC eviction logic that selects blocks from T1 or T2 based on the adaptive target_t1_size threshold', 'build a touch operation that promotes T1 blocks to T2 and adjusts target_t1_size on ghost list hits', 'review the ARC insert method that adds blocks to T1 and removes them from ghost lists', 'summarize the ARC get lookup that checks T1 then T2 for a cached block status by key', 'create a BlockStatus instance with a block_id to track KV data offloading state', 'check if a BlockStatus instance is ready to be read by inspecting its is_ready property', 'implement a CachePolicy subclass with get, insert, remove, touch, and evict methods for LRU or ARC eviction', 'call the get method on a CachePolicy subclass to look up a BlockStatus by OffloadKey', 'call the evict method on a CachePolicy subclass to evict n blocks while skipping protected keys', 'create an LRU cache policy instance with a given cache capacity for KV block offloading', 'insert a KV block with its key and block status into the LRU cache policy', 'touch a set of keys in the LRU cache to move them to the most-recently-used end', 'evict n KV blocks from the LRU cache that have zero reference count and are not protected', 'remove a KV block from the LRU cache by its key']
```

Usage

```
{'create_ARCCachePolicy': 'create an ARCCachePolicy instance with a given cache capacity for adaptive KV block caching', 'test_ARC_eviction': 'test the ARC eviction logic that selects blocks from T1 or T2 based on the adaptive target_t1_size threshold', 'build_ARC_touch': 'build a touch operation that promotes T1 blocks to T2 and adjusts target_t1_size on ghost list hits', 'review_ARC_insert': 'review the ARC insert method that adds blocks to T1 and removes them from ghost lists', 'summarize_ARC_get': 'summarize the ARC get lookup that checks T1 then T2 for a cached block status by key'}
```

## File: vllm-project_vllm/vllm/v1/kv_offload/cpu/policies/base.py

Prompts

```
['create an ARCCachePolicy instance with a given cache capacity for adaptive KV block caching', 'test the ARC eviction logic that selects blocks from T1 or T2 based on the adaptive target_t1_size threshold', 'build a touch operation that promotes T1 blocks to T2 and adjusts target_t1_size on ghost list hits', 'review the ARC insert method that adds blocks to T1 and removes them from ghost lists', 'summarize the ARC get lookup that checks T1 then T2 for a cached block status by key', 'create a BlockStatus instance with a block_id to track KV data offloading state', 'check if a BlockStatus instance is ready to be read by inspecting its is_ready property', 'implement a CachePolicy subclass with get, insert, remove, touch, and evict methods for LRU or ARC eviction', 'call the get method on a CachePolicy subclass to look up a BlockStatus by OffloadKey', 'call the evict method on a CachePolicy subclass to evict n blocks while skipping protected keys', 'create an LRU cache policy instance with a given cache capacity for KV block offloading', 'insert a KV block with its key and block status into the LRU cache policy', 'touch a set of keys in the LRU cache to move them to the most-recently-used end', 'evict n KV blocks from the LRU cache that have zero reference count and are not protected', 'remove a KV block from the LRU cache by its key']
```

Usage

```
{'create_BlockStatus': 'create a BlockStatus instance with a block_id to track KV data offloading state', 'check_BlockStatus_is_ready': 'check if a BlockStatus instance is ready to be read by inspecting its is_ready property', 'implement_CachePolicy_subclass': 'implement a CachePolicy subclass with get, insert, remove, touch, and evict methods for LRU or ARC eviction', 'call_CachePolicy_get': 'call the get method on a CachePolicy subclass to look up a BlockStatus by OffloadKey', 'call_CachePolicy_evict': 'call the evict method on a CachePolicy subclass to evict n blocks while skipping protected keys'}
```

## File: vllm-project_vllm/vllm/v1/kv_offload/cpu/policies/lru.py

Prompts

```
['create an ARCCachePolicy instance with a given cache capacity for adaptive KV block caching', 'test the ARC eviction logic that selects blocks from T1 or T2 based on the adaptive target_t1_size threshold', 'build a touch operation that promotes T1 blocks to T2 and adjusts target_t1_size on ghost list hits', 'review the ARC insert method that adds blocks to T1 and removes them from ghost lists', 'summarize the ARC get lookup that checks T1 then T2 for a cached block status by key', 'create a BlockStatus instance with a block_id to track KV data offloading state', 'check if a BlockStatus instance is ready to be read by inspecting its is_ready property', 'implement a CachePolicy subclass with get, insert, remove, touch, and evict methods for LRU or ARC eviction', 'call the get method on a CachePolicy subclass to look up a BlockStatus by OffloadKey', 'call the evict method on a CachePolicy subclass to evict n blocks while skipping protected keys', 'create an LRU cache policy instance with a given cache capacity for KV block offloading', 'insert a KV block with its key and block status into the LRU cache policy', 'touch a set of keys in the LRU cache to move them to the most-recently-used end', 'evict n KV blocks from the LRU cache that have zero reference count and are not protected', 'remove a KV block from the LRU cache by its key']
```

Usage

```
{'create_lru_cache_policy': 'create an LRU cache policy instance with a given cache capacity for KV block offloading', 'insert_lru_cache_block': 'insert a KV block with its key and block status into the LRU cache policy', 'touch_lru_cache_keys': 'touch a set of keys in the LRU cache to move them to the most-recently-used end', 'evict_lru_cache_blocks': 'evict n KV blocks from the LRU cache that have zero reference count and are not protected', 'remove_lru_cache_block': 'remove a KV block from the LRU cache by its key'}
```

