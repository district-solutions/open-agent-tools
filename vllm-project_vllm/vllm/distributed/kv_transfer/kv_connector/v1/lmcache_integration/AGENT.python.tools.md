# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/lmcache_integration/multi_process_adapter.py

Prompts

```
['build an LMCacheMPSchedulerAdapter to submit lookup requests and check results for KV cache retrieval', 'create an LMCacheMPWorkerAdapter to submit store and retrieve requests for KV cache operations', 'test the batched_submit_store_requests method to batch multiple KV cache store operations', 'review the get_finished method to check and return finished store and retrieve request IDs', 'summarize the LMCacheMPSchedulerAdapter class for managing KV cache lookup requests', 'create LMCacheEngineMetadata from vLLM model, parallel, and cache configuration objects', 'extract multimodal hash identifiers and placeholder positions from a vLLM request object', 'apply multimodal hash values to token IDs tensor at specified placeholder positions', 'test the thread-safe singleton LMCache config loader that reads from env or config file', "test the string-to-boolean helper that recognizes false-like values such as 'false', '0', 'no', 'off'", 'initialize the LMCache engine with vLLM configuration and parallel settings', 'build connector metadata from scheduler output for new and cached requests', 'check for external KV cache hits and return the number of matched tokens', "load KV cache from LMCache connector buffer into vLLM's paged KV buffer", "save KV cache from vLLM's paged buffer to the LMCache connector"]
```

Usage

```
{'build_LMCacheMPSchedulerAdapter': 'build an LMCacheMPSchedulerAdapter to submit lookup requests and check results for KV cache retrieval', 'create_LMCacheMPWorkerAdapter': 'create an LMCacheMPWorkerAdapter to submit store and retrieve requests for KV cache operations', 'test_batched_submit_store_requests': 'test the batched_submit_store_requests method to batch multiple KV cache store operations', 'review_get_finished': 'review the get_finished method to check and return finished store and retrieve request IDs', 'summarize_LMCacheMPSchedulerAdapter': 'summarize the LMCacheMPSchedulerAdapter class for managing KV cache lookup requests'}
```

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/lmcache_integration/utils.py

Prompts

```
['build an LMCacheMPSchedulerAdapter to submit lookup requests and check results for KV cache retrieval', 'create an LMCacheMPWorkerAdapter to submit store and retrieve requests for KV cache operations', 'test the batched_submit_store_requests method to batch multiple KV cache store operations', 'review the get_finished method to check and return finished store and retrieve request IDs', 'summarize the LMCacheMPSchedulerAdapter class for managing KV cache lookup requests', 'create LMCacheEngineMetadata from vLLM model, parallel, and cache configuration objects', 'extract multimodal hash identifiers and placeholder positions from a vLLM request object', 'apply multimodal hash values to token IDs tensor at specified placeholder positions', 'test the thread-safe singleton LMCache config loader that reads from env or config file', "test the string-to-boolean helper that recognizes false-like values such as 'false', '0', 'no', 'off'", 'initialize the LMCache engine with vLLM configuration and parallel settings', 'build connector metadata from scheduler output for new and cached requests', 'check for external KV cache hits and return the number of matched tokens', "load KV cache from LMCache connector buffer into vLLM's paged KV buffer", "save KV cache from vLLM's paged buffer to the LMCache connector"]
```

Usage

```
{'create_lmcache_metadata': 'create LMCacheEngineMetadata from vLLM model, parallel, and cache configuration objects', 'extract_mm_features': 'extract multimodal hash identifiers and placeholder positions from a vLLM request object', 'apply_mm_hashes_to_token_ids': 'apply multimodal hash values to token IDs tensor at specified placeholder positions', 'test_lmcache_get_or_create_config': 'test the thread-safe singleton LMCache config loader that reads from env or config file', 'test_is_false': "test the string-to-boolean helper that recognizes false-like values such as 'false', '0', 'no', 'off'"}
```

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/lmcache_integration/vllm_v1_adapter.py

Prompts

```
['build an LMCacheMPSchedulerAdapter to submit lookup requests and check results for KV cache retrieval', 'create an LMCacheMPWorkerAdapter to submit store and retrieve requests for KV cache operations', 'test the batched_submit_store_requests method to batch multiple KV cache store operations', 'review the get_finished method to check and return finished store and retrieve request IDs', 'summarize the LMCacheMPSchedulerAdapter class for managing KV cache lookup requests', 'create LMCacheEngineMetadata from vLLM model, parallel, and cache configuration objects', 'extract multimodal hash identifiers and placeholder positions from a vLLM request object', 'apply multimodal hash values to token IDs tensor at specified placeholder positions', 'test the thread-safe singleton LMCache config loader that reads from env or config file', "test the string-to-boolean helper that recognizes false-like values such as 'false', '0', 'no', 'off'", 'initialize the LMCache engine with vLLM configuration and parallel settings', 'build connector metadata from scheduler output for new and cached requests', 'check for external KV cache hits and return the number of matched tokens', "load KV cache from LMCache connector buffer into vLLM's paged KV buffer", "save KV cache from vLLM's paged buffer to the LMCache connector"]
```

Usage

```
{'init_lmcache_engine': 'initialize the LMCache engine with vLLM configuration and parallel settings', 'build_connector_metadata': 'build connector metadata from scheduler output for new and cached requests', 'check_external_kv_cache_hit': 'check for external KV cache hits and return the number of matched tokens', 'load_kv_cache_from_connector': "load KV cache from LMCache connector buffer into vLLM's paged KV buffer", 'save_kv_cache_to_connector': "save KV cache from vLLM's paged buffer to the LMCache connector"}
```

