# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/lmcache/lmc_radix_cache.py

Prompts

```
['create an LMCRadixCache instance with cache init params, model config, and TP rank for KV cache with LMCache integration', 'test the match_prefix method to match cached prefixes and prefetch missing chunks from LMCache', 'run cache_finished_req to insert device KV into radix tree and store to LMCache on request completion', 'test the evict method to synchronize in-flight stores and release node locks before base eviction', 'create a LayerTransferCounter to wire per-layer KV cache completion to async LMCache load calls', 'test the test_load_store_metadata function that validates LMCache KV cache store and load operations', 'run LMCacheLayerwiseConnector to initialize a layerwise KV cache connector with model config and buffers', 'create a StoreMetadata object with token ids, kv indices, offset, and last node for KV cache storage', 'create a LoadMetadata object with token ids, slot mapping, and offset for KV cache retrieval', 'test the connector store_kv and load_kv_layerwise methods to verify KV cache round-trip correctness']
```

Usage

```
{'create_LMCRadixCache': 'create an LMCRadixCache instance with cache init params, model config, and TP rank for KV cache with LMCache integration', 'test_match_prefix': 'test the match_prefix method to match cached prefixes and prefetch missing chunks from LMCache', 'run_cache_finished_req': 'run cache_finished_req to insert device KV into radix tree and store to LMCache on request completion', 'test_evict': 'test the evict method to synchronize in-flight stores and release node locks before base eviction', 'create_LayerTransferCounter': 'create a LayerTransferCounter to wire per-layer KV cache completion to async LMCache load calls'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/lmcache/unit_test.py

Prompts

```
['create an LMCRadixCache instance with cache init params, model config, and TP rank for KV cache with LMCache integration', 'test the match_prefix method to match cached prefixes and prefetch missing chunks from LMCache', 'run cache_finished_req to insert device KV into radix tree and store to LMCache on request completion', 'test the evict method to synchronize in-flight stores and release node locks before base eviction', 'create a LayerTransferCounter to wire per-layer KV cache completion to async LMCache load calls', 'test the test_load_store_metadata function that validates LMCache KV cache store and load operations', 'run LMCacheLayerwiseConnector to initialize a layerwise KV cache connector with model config and buffers', 'create a StoreMetadata object with token ids, kv indices, offset, and last node for KV cache storage', 'create a LoadMetadata object with token ids, slot mapping, and offset for KV cache retrieval', 'test the connector store_kv and load_kv_layerwise methods to verify KV cache round-trip correctness']
```

Usage

```
{'test_load_store_metadata': 'test the test_load_store_metadata function that validates LMCache KV cache store and load operations', 'run_LMCacheLayerwiseConnector': 'run LMCacheLayerwiseConnector to initialize a layerwise KV cache connector with model config and buffers', 'create_StoreMetadata': 'create a StoreMetadata object with token ids, kv indices, offset, and last node for KV cache storage', 'create_LoadMetadata': 'create a LoadMetadata object with token ids, slot mapping, and offset for KV cache retrieval', 'test_connector_store_load': 'test the connector store_kv and load_kv_layerwise methods to verify KV cache round-trip correctness'}
```

