# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/mem_cache/unified_cache_components/full_component.py

Prompts

```
['create a FullComponent instance for unified radix cache KV pool management with allocator and cache params', 'test the FullComponent.evict_component method to free KV cache data from a tree node and update evictable sizes', 'refactor the FullComponent.drive_eviction method to evict leaf nodes from the LRU list until requested token count is freed', 'review the FullComponent.acquire_component_lock method to increment lock_ref up the tree and protect KV data from eviction', 'summarize the FullComponent.release_component_lock method to decrement lock_ref up the tree and unprotect KV data for eviction', 'create a validator function that checks if a tree node has valid mamba cache data', 'finalize a prefix match result by copying mamba state using copy-on-write for request isolation', 'commit mamba cache data to a tree node updating LRU lists and evictable size tracking', 'evict mamba cache entries from a tree node freeing pool indices and updating size counters', 'prepare mamba cache indices for a request supporting extra buffer and fork allocation with eviction fallback', 'create an SWAComponent instance for sliding window attention cache management in UnifiedRadixCache', "build a match validator function that checks if a tree node's SWA data meets the sliding window size threshold", 'refactor update_component_on_insert_overlap to handle tombstoned nodes and recover SWA data within the sliding window', 'review drive_eviction to manage LRU-based eviction of SWA tokens across internal and leaf nodes', 'create a TreeComponent subclass that implements abstract methods for a new cache component type', 'build HiCache transfer descriptors for a TreeComponent node in a given CacheTransferPhase', 'test the create_match_validator method returns a callable predicate for TreeComponent prefix matching', 'refactor the eviction_priority method to adjust cascade eviction order among FULL, SWA, and Mamba components', 'summarize the TreeComponent abstract class and its role in unified radix cache management']
```

Usage

```
{'create_FullComponent': 'create a FullComponent instance for unified radix cache KV pool management with allocator and cache params', 'test_evict_component': 'test the FullComponent.evict_component method to free KV cache data from a tree node and update evictable sizes', 'refactor_drive_eviction': 'refactor the FullComponent.drive_eviction method to evict leaf nodes from the LRU list until requested token count is freed', 'review_acquire_component_lock': 'review the FullComponent.acquire_component_lock method to increment lock_ref up the tree and protect KV data from eviction', 'summarize_release_component_lock': 'summarize the FullComponent.release_component_lock method to decrement lock_ref up the tree and unprotect KV data for eviction'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/unified_cache_components/mamba_component.py

Prompts

```
['create a FullComponent instance for unified radix cache KV pool management with allocator and cache params', 'test the FullComponent.evict_component method to free KV cache data from a tree node and update evictable sizes', 'refactor the FullComponent.drive_eviction method to evict leaf nodes from the LRU list until requested token count is freed', 'review the FullComponent.acquire_component_lock method to increment lock_ref up the tree and protect KV data from eviction', 'summarize the FullComponent.release_component_lock method to decrement lock_ref up the tree and unprotect KV data for eviction', 'create a validator function that checks if a tree node has valid mamba cache data', 'finalize a prefix match result by copying mamba state using copy-on-write for request isolation', 'commit mamba cache data to a tree node updating LRU lists and evictable size tracking', 'evict mamba cache entries from a tree node freeing pool indices and updating size counters', 'prepare mamba cache indices for a request supporting extra buffer and fork allocation with eviction fallback', 'create an SWAComponent instance for sliding window attention cache management in UnifiedRadixCache', "build a match validator function that checks if a tree node's SWA data meets the sliding window size threshold", 'refactor update_component_on_insert_overlap to handle tombstoned nodes and recover SWA data within the sliding window', 'review drive_eviction to manage LRU-based eviction of SWA tokens across internal and leaf nodes', 'create a TreeComponent subclass that implements abstract methods for a new cache component type', 'build HiCache transfer descriptors for a TreeComponent node in a given CacheTransferPhase', 'test the create_match_validator method returns a callable predicate for TreeComponent prefix matching', 'refactor the eviction_priority method to adjust cascade eviction order among FULL, SWA, and Mamba components', 'summarize the TreeComponent abstract class and its role in unified radix cache management']
```

Usage

```
{'create_match_validator': 'create a validator function that checks if a tree node has valid mamba cache data', 'finalize_match_result': 'finalize a prefix match result by copying mamba state using copy-on-write for request isolation', 'commit_insert_component_data': 'commit mamba cache data to a tree node updating LRU lists and evictable size tracking', 'evict_component': 'evict mamba cache entries from a tree node freeing pool indices and updating size counters', 'prepare_for_caching_req': 'prepare mamba cache indices for a request supporting extra buffer and fork allocation with eviction fallback'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/unified_cache_components/swa_component.py

Prompts

```
['create a FullComponent instance for unified radix cache KV pool management with allocator and cache params', 'test the FullComponent.evict_component method to free KV cache data from a tree node and update evictable sizes', 'refactor the FullComponent.drive_eviction method to evict leaf nodes from the LRU list until requested token count is freed', 'review the FullComponent.acquire_component_lock method to increment lock_ref up the tree and protect KV data from eviction', 'summarize the FullComponent.release_component_lock method to decrement lock_ref up the tree and unprotect KV data for eviction', 'create a validator function that checks if a tree node has valid mamba cache data', 'finalize a prefix match result by copying mamba state using copy-on-write for request isolation', 'commit mamba cache data to a tree node updating LRU lists and evictable size tracking', 'evict mamba cache entries from a tree node freeing pool indices and updating size counters', 'prepare mamba cache indices for a request supporting extra buffer and fork allocation with eviction fallback', 'create an SWAComponent instance for sliding window attention cache management in UnifiedRadixCache', "build a match validator function that checks if a tree node's SWA data meets the sliding window size threshold", 'refactor update_component_on_insert_overlap to handle tombstoned nodes and recover SWA data within the sliding window', 'review drive_eviction to manage LRU-based eviction of SWA tokens across internal and leaf nodes', 'create a TreeComponent subclass that implements abstract methods for a new cache component type', 'build HiCache transfer descriptors for a TreeComponent node in a given CacheTransferPhase', 'test the create_match_validator method returns a callable predicate for TreeComponent prefix matching', 'refactor the eviction_priority method to adjust cascade eviction order among FULL, SWA, and Mamba components', 'summarize the TreeComponent abstract class and its role in unified radix cache management']
```

Usage

```
{'create_swa_component': 'create an SWAComponent instance for sliding window attention cache management in UnifiedRadixCache', 'build_match_validator': "build a match validator function that checks if a tree node's SWA data meets the sliding window size threshold", 'refactor_update_on_insert': 'refactor update_component_on_insert_overlap to handle tombstoned nodes and recover SWA data within the sliding window', 'test_evict_component': 'test evict_component to free SWA token KV pool memory and update evictable size tracking for a tree node', 'review_drive_eviction': 'review drive_eviction to manage LRU-based eviction of SWA tokens across internal and leaf nodes'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/unified_cache_components/tree_component.py

Prompts

```
['create a FullComponent instance for unified radix cache KV pool management with allocator and cache params', 'test the FullComponent.evict_component method to free KV cache data from a tree node and update evictable sizes', 'refactor the FullComponent.drive_eviction method to evict leaf nodes from the LRU list until requested token count is freed', 'review the FullComponent.acquire_component_lock method to increment lock_ref up the tree and protect KV data from eviction', 'summarize the FullComponent.release_component_lock method to decrement lock_ref up the tree and unprotect KV data for eviction', 'create a validator function that checks if a tree node has valid mamba cache data', 'finalize a prefix match result by copying mamba state using copy-on-write for request isolation', 'commit mamba cache data to a tree node updating LRU lists and evictable size tracking', 'evict mamba cache entries from a tree node freeing pool indices and updating size counters', 'prepare mamba cache indices for a request supporting extra buffer and fork allocation with eviction fallback', 'create an SWAComponent instance for sliding window attention cache management in UnifiedRadixCache', "build a match validator function that checks if a tree node's SWA data meets the sliding window size threshold", 'refactor update_component_on_insert_overlap to handle tombstoned nodes and recover SWA data within the sliding window', 'review drive_eviction to manage LRU-based eviction of SWA tokens across internal and leaf nodes', 'create a TreeComponent subclass that implements abstract methods for a new cache component type', 'build HiCache transfer descriptors for a TreeComponent node in a given CacheTransferPhase', 'test the create_match_validator method returns a callable predicate for TreeComponent prefix matching', 'refactor the eviction_priority method to adjust cascade eviction order among FULL, SWA, and Mamba components', 'summarize the TreeComponent abstract class and its role in unified radix cache management']
```

Usage

```
{'create_tree_component': 'create a TreeComponent subclass that implements abstract methods for a new cache component type', 'build_hicache_transfers': 'build HiCache transfer descriptors for a TreeComponent node in a given CacheTransferPhase', 'test_match_validator': 'test the create_match_validator method returns a callable predicate for TreeComponent prefix matching', 'refactor_eviction_priority': 'refactor the eviction_priority method to adjust cascade eviction order among FULL, SWA, and Mamba components', 'summarize_tree_component': 'summarize the TreeComponent abstract class and its role in unified radix cache management'}
```

