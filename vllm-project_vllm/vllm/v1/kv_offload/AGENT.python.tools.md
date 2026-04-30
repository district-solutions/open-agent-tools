# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/v1/kv_offload/base.py

Prompts

```
['create an OffloadKey by packing a block hash and group index into raw bytes', 'extract the block hash bytes from an existing OffloadKey using get_offload_block_hash', 'extract the group index integer from an existing OffloadKey using get_offload_group_idx', 'implement a concrete OffloadingManager subclass with lookup, prepare_load, and prepare_store methods for KV cache offloading', 'build a concrete OffloadingSpec subclass that returns an OffloadingManager and offloading handlers for KV cache groups', 'create an offloading spec from VllmConfig and KVCacheConfig using OffloadingSpecFactory.create_spec', 'register a custom offloading spec class with lazy-loading module and class name via OffloadingSpecFactory.register_spec', 'build a CPU offloading spec by creating an OffloadingSpecFactory instance with config and kv_cache_config', 'test the OffloadingSpecFactory registry for a registered spec name before instantiation', 'review OffloadingSpecFactory.create_spec error handling for unsupported spec types and missing module paths', 'create a FilterReusedOffloadingManager decorator wrapping a backing OffloadingManager with a store threshold of 2', 'test the FilterReusedOffloadingManager.lookup method to record key reuse counts with LRU eviction', 'review the FilterReusedOffloadingManager.prepare_store method to filter out blocks below the reuse threshold', 'build a KV-cache offload pipeline using FilterReusedOffloadingManager to skip storing infrequently-reused blocks', 'summarize how FilterReusedOffloadingManager uses reuse-frequency gating to reduce unnecessary CPU offload writes']
```

Usage

```
{'create_offload_key': 'create an OffloadKey by packing a block hash and group index into raw bytes', 'extract_block_hash': 'extract the block hash bytes from an existing OffloadKey using get_offload_block_hash', 'extract_group_index': 'extract the group index integer from an existing OffloadKey using get_offload_group_idx', 'implement_offloading_manager': 'implement a concrete OffloadingManager subclass with lookup, prepare_load, and prepare_store methods for KV cache offloading', 'build_offloading_spec': 'build a concrete OffloadingSpec subclass that returns an OffloadingManager and offloading handlers for KV cache groups'}
```

## File: vllm-project_vllm/vllm/v1/kv_offload/factory.py

Prompts

```
['create an OffloadKey by packing a block hash and group index into raw bytes', 'extract the block hash bytes from an existing OffloadKey using get_offload_block_hash', 'extract the group index integer from an existing OffloadKey using get_offload_group_idx', 'implement a concrete OffloadingManager subclass with lookup, prepare_load, and prepare_store methods for KV cache offloading', 'build a concrete OffloadingSpec subclass that returns an OffloadingManager and offloading handlers for KV cache groups', 'create an offloading spec from VllmConfig and KVCacheConfig using OffloadingSpecFactory.create_spec', 'register a custom offloading spec class with lazy-loading module and class name via OffloadingSpecFactory.register_spec', 'build a CPU offloading spec by creating an OffloadingSpecFactory instance with config and kv_cache_config', 'test the OffloadingSpecFactory registry for a registered spec name before instantiation', 'review OffloadingSpecFactory.create_spec error handling for unsupported spec types and missing module paths', 'create a FilterReusedOffloadingManager decorator wrapping a backing OffloadingManager with a store threshold of 2', 'test the FilterReusedOffloadingManager.lookup method to record key reuse counts with LRU eviction', 'review the FilterReusedOffloadingManager.prepare_store method to filter out blocks below the reuse threshold', 'build a KV-cache offload pipeline using FilterReusedOffloadingManager to skip storing infrequently-reused blocks', 'summarize how FilterReusedOffloadingManager uses reuse-frequency gating to reduce unnecessary CPU offload writes']
```

Usage

```
{'create_offloading_spec': 'create an offloading spec from VllmConfig and KVCacheConfig using OffloadingSpecFactory.create_spec', 'register_offloading_spec': 'register a custom offloading spec class with lazy-loading module and class name via OffloadingSpecFactory.register_spec', 'build_cpu_offloading_spec': 'build a CPU offloading spec by creating an OffloadingSpecFactory instance with config and kv_cache_config', 'test_registry_lookup': 'test the OffloadingSpecFactory registry for a registered spec name before instantiation', 'review_create_spec_error_handling': 'review OffloadingSpecFactory.create_spec error handling for unsupported spec types and missing module paths'}
```

## File: vllm-project_vllm/vllm/v1/kv_offload/reuse_manager.py

Prompts

```
['create an OffloadKey by packing a block hash and group index into raw bytes', 'extract the block hash bytes from an existing OffloadKey using get_offload_block_hash', 'extract the group index integer from an existing OffloadKey using get_offload_group_idx', 'implement a concrete OffloadingManager subclass with lookup, prepare_load, and prepare_store methods for KV cache offloading', 'build a concrete OffloadingSpec subclass that returns an OffloadingManager and offloading handlers for KV cache groups', 'create an offloading spec from VllmConfig and KVCacheConfig using OffloadingSpecFactory.create_spec', 'register a custom offloading spec class with lazy-loading module and class name via OffloadingSpecFactory.register_spec', 'build a CPU offloading spec by creating an OffloadingSpecFactory instance with config and kv_cache_config', 'test the OffloadingSpecFactory registry for a registered spec name before instantiation', 'review OffloadingSpecFactory.create_spec error handling for unsupported spec types and missing module paths', 'create a FilterReusedOffloadingManager decorator wrapping a backing OffloadingManager with a store threshold of 2', 'test the FilterReusedOffloadingManager.lookup method to record key reuse counts with LRU eviction', 'review the FilterReusedOffloadingManager.prepare_store method to filter out blocks below the reuse threshold', 'build a KV-cache offload pipeline using FilterReusedOffloadingManager to skip storing infrequently-reused blocks', 'summarize how FilterReusedOffloadingManager uses reuse-frequency gating to reduce unnecessary CPU offload writes']
```

Usage

```
{'create_filter_reused_offloading_manager': 'create a FilterReusedOffloadingManager decorator wrapping a backing OffloadingManager with a store threshold of 2', 'test_lookup_tracking': 'test the FilterReusedOffloadingManager.lookup method to record key reuse counts with LRU eviction', 'review_prepare_store_filtering': 'review the FilterReusedOffloadingManager.prepare_store method to filter out blocks below the reuse threshold', 'build_kv_cache_offload_pipeline': 'build a KV-cache offload pipeline using FilterReusedOffloadingManager to skip storing infrequently-reused blocks', 'summarize_reuse_frequency_gating': 'summarize how FilterReusedOffloadingManager uses reuse-frequency gating to reduce unnecessary CPU offload writes'}
```

