# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/mem_cache/hybrid_cache/hybrid_cache_controller.py

Prompts

```
['create a HybridCacheController instance to manage hybrid KV cache with storage backend integration', 'build merged CacheOperation from a list of CacheOperation instances by concatenating indices and pool transfers', 'test the HybridCacheController write method to allocate host indices and queue cache write operations', 'review the HybridCacheController load method to transfer KV cache from host to device per layer', 'summarize the HybridCacheController prefetch method that queues PrefetchOperation for background prefetching', 'build a hybrid hierarchical cache stack with HostPoolGroup (KV + INDEXER) and HybridCacheController for NSA/DSA models', 'build a hybrid hierarchical cache stack with HostPoolGroup (KV + MAMBA) and HybridCacheController for hybrid SSM models', 'review the build_nsa_hybrid_stack function that configures MLA KV pool host and NSA indexer pool host with layer mapping', 'review the build_mamba_hybrid_stack function that configures KV and Mamba pool hosts with separate layer mappers for hybrid SSM models', 'summarize the hybrid_pool_assembler module that constructs hybrid cache stacks with HostPoolGroup and HybridCacheController for different model types']
```

Usage

```
{'create_HybridCacheController': 'create a HybridCacheController instance to manage hybrid KV cache with storage backend integration', 'build_CacheOperation_merge_ops': 'build merged CacheOperation from a list of CacheOperation instances by concatenating indices and pool transfers', 'test_HybridCacheController_write': 'test the HybridCacheController write method to allocate host indices and queue cache write operations', 'review_HybridCacheController_load': 'review the HybridCacheController load method to transfer KV cache from host to device per layer', 'summarize_HybridCacheController_prefetch': 'summarize the HybridCacheController prefetch method that queues PrefetchOperation for background prefetching'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/hybrid_cache/hybrid_pool_assembler.py

Prompts

```
['create a HybridCacheController instance to manage hybrid KV cache with storage backend integration', 'build merged CacheOperation from a list of CacheOperation instances by concatenating indices and pool transfers', 'test the HybridCacheController write method to allocate host indices and queue cache write operations', 'review the HybridCacheController load method to transfer KV cache from host to device per layer', 'summarize the HybridCacheController prefetch method that queues PrefetchOperation for background prefetching', 'build a hybrid hierarchical cache stack with HostPoolGroup (KV + INDEXER) and HybridCacheController for NSA/DSA models', 'build a hybrid hierarchical cache stack with HostPoolGroup (KV + MAMBA) and HybridCacheController for hybrid SSM models', 'review the build_nsa_hybrid_stack function that configures MLA KV pool host and NSA indexer pool host with layer mapping', 'review the build_mamba_hybrid_stack function that configures KV and Mamba pool hosts with separate layer mappers for hybrid SSM models', 'summarize the hybrid_pool_assembler module that constructs hybrid cache stacks with HostPoolGroup and HybridCacheController for different model types']
```

Usage

```
{'build_nsa_hybrid_stack': 'build a hybrid hierarchical cache stack with HostPoolGroup (KV + INDEXER) and HybridCacheController for NSA/DSA models', 'build_mamba_hybrid_stack': 'build a hybrid hierarchical cache stack with HostPoolGroup (KV + MAMBA) and HybridCacheController for hybrid SSM models', 'review_build_nsa_hybrid_stack': 'review the build_nsa_hybrid_stack function that configures MLA KV pool host and NSA indexer pool host with layer mapping', 'review_build_mamba_hybrid_stack': 'review the build_mamba_hybrid_stack function that configures KV and Mamba pool hosts with separate layer mappers for hybrid SSM models', 'summarize_hybrid_pool_assembler': 'summarize the hybrid_pool_assembler module that constructs hybrid cache stacks with HostPoolGroup and HybridCacheController for different model types'}
```

