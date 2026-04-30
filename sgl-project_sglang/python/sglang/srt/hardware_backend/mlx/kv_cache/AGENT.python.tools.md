# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/mlx/kv_cache/attention_wrapper.py

Prompts

```
['create a BatchedDecodeContext dataclass instance with batch_size, seq_lens, and layer_caches for batched decode', 'set the BatchedDecodeContext on thread-local storage before calling attention wrapper', 'get the current BatchedDecodeContext from thread-local storage', 'clear the BatchedDecodeContext from thread-local storage', 'build an MLXAttentionWrapper that wraps an mlx-lm Attention module for batched decode with per-request RoPE and SDPA', 'create a ContiguousKVCache with n_kv_heads, head_dim, max_seq_len, and dtype for pre-allocated KV buffer', 'test ContiguousKVCache.update_and_fetch to append K/V tensors and return all valid K/V up to current offset', 'review ContiguousKVCache.write_token to write a single token key-value pair at the current offset', 'build a PoolBackedCache from a KV pool and convert it to ContiguousKVCache after the forward pass', "summarize OffsetCache as a data-free shim satisfying mlx-lm's cache protocol without storing actual K/V", 'create an MlxKVPool with pool_size, num_layers, n_kv_heads, head_dim, and dtype parameters', 'build a pre-allocated flat KV pool with per-layer buffers indexed by integer slot IDs', 'test the MlxKVPool.set_kv method to scatter K and V tensors into specified slots for one layer', 'test the MlxKVPool.get_kv method to gather K and V tensors from specified slots for one layer', 'test the MlxKVPool.get_kv_all_layers method to gather K and V tensors across all layers for given slots', 'find the transformer layers and attention attribute name in an MLX model', 'patch all attention layers in an MLX model with MLXAttentionWrapper', 'get the number of transformer layers in an MLX model', 'refactor find_attention_layers to support custom layer attribute names', 'review patch_model_attention to ensure idempotent wrapper installation']
```

Usage

```
{'create_BatchedDecodeContext': 'create a BatchedDecodeContext dataclass instance with batch_size, seq_lens, and layer_caches for batched decode', 'set_context_batched_decode': 'set the BatchedDecodeContext on thread-local storage before calling attention wrapper', 'get_context_batched_decode': 'get the current BatchedDecodeContext from thread-local storage', 'clear_context_batched_decode': 'clear the BatchedDecodeContext from thread-local storage', 'build_MLXAttentionWrapper': 'build an MLXAttentionWrapper that wraps an mlx-lm Attention module for batched decode with per-request RoPE and SDPA'}
```

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/mlx/kv_cache/contiguous_cache.py

Prompts

```
['create a BatchedDecodeContext dataclass instance with batch_size, seq_lens, and layer_caches for batched decode', 'set the BatchedDecodeContext on thread-local storage before calling attention wrapper', 'get the current BatchedDecodeContext from thread-local storage', 'clear the BatchedDecodeContext from thread-local storage', 'build an MLXAttentionWrapper that wraps an mlx-lm Attention module for batched decode with per-request RoPE and SDPA', 'create a ContiguousKVCache with n_kv_heads, head_dim, max_seq_len, and dtype for pre-allocated KV buffer', 'test ContiguousKVCache.update_and_fetch to append K/V tensors and return all valid K/V up to current offset', 'review ContiguousKVCache.write_token to write a single token key-value pair at the current offset', 'build a PoolBackedCache from a KV pool and convert it to ContiguousKVCache after the forward pass', "summarize OffsetCache as a data-free shim satisfying mlx-lm's cache protocol without storing actual K/V", 'create an MlxKVPool with pool_size, num_layers, n_kv_heads, head_dim, and dtype parameters', 'build a pre-allocated flat KV pool with per-layer buffers indexed by integer slot IDs', 'test the MlxKVPool.set_kv method to scatter K and V tensors into specified slots for one layer', 'test the MlxKVPool.get_kv method to gather K and V tensors from specified slots for one layer', 'test the MlxKVPool.get_kv_all_layers method to gather K and V tensors across all layers for given slots', 'find the transformer layers and attention attribute name in an MLX model', 'patch all attention layers in an MLX model with MLXAttentionWrapper', 'get the number of transformer layers in an MLX model', 'refactor find_attention_layers to support custom layer attribute names', 'review patch_model_attention to ensure idempotent wrapper installation']
```

Usage

```
{'create_ContiguousKVCache': 'create a ContiguousKVCache with n_kv_heads, head_dim, max_seq_len, and dtype for pre-allocated KV buffer', 'test_ContiguousKVCache_update_and_fetch': 'test ContiguousKVCache.update_and_fetch to append K/V tensors and return all valid K/V up to current offset', 'review_ContiguousKVCache_write_token': 'review ContiguousKVCache.write_token to write a single token key-value pair at the current offset', 'build_PoolBackedCache_to_contiguous': 'build a PoolBackedCache from a KV pool and convert it to ContiguousKVCache after the forward pass', 'summarize_OffsetCache_protocol': "summarize OffsetCache as a data-free shim satisfying mlx-lm's cache protocol without storing actual K/V"}
```

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/mlx/kv_cache/kv_pool.py

Prompts

```
['create a BatchedDecodeContext dataclass instance with batch_size, seq_lens, and layer_caches for batched decode', 'set the BatchedDecodeContext on thread-local storage before calling attention wrapper', 'get the current BatchedDecodeContext from thread-local storage', 'clear the BatchedDecodeContext from thread-local storage', 'build an MLXAttentionWrapper that wraps an mlx-lm Attention module for batched decode with per-request RoPE and SDPA', 'create a ContiguousKVCache with n_kv_heads, head_dim, max_seq_len, and dtype for pre-allocated KV buffer', 'test ContiguousKVCache.update_and_fetch to append K/V tensors and return all valid K/V up to current offset', 'review ContiguousKVCache.write_token to write a single token key-value pair at the current offset', 'build a PoolBackedCache from a KV pool and convert it to ContiguousKVCache after the forward pass', "summarize OffsetCache as a data-free shim satisfying mlx-lm's cache protocol without storing actual K/V", 'create an MlxKVPool with pool_size, num_layers, n_kv_heads, head_dim, and dtype parameters', 'build a pre-allocated flat KV pool with per-layer buffers indexed by integer slot IDs', 'test the MlxKVPool.set_kv method to scatter K and V tensors into specified slots for one layer', 'test the MlxKVPool.get_kv method to gather K and V tensors from specified slots for one layer', 'test the MlxKVPool.get_kv_all_layers method to gather K and V tensors across all layers for given slots', 'find the transformer layers and attention attribute name in an MLX model', 'patch all attention layers in an MLX model with MLXAttentionWrapper', 'get the number of transformer layers in an MLX model', 'refactor find_attention_layers to support custom layer attribute names', 'review patch_model_attention to ensure idempotent wrapper installation']
```

Usage

```
{'create_MlxKVPool': 'create an MlxKVPool with pool_size, num_layers, n_kv_heads, head_dim, and dtype parameters', 'build_MlxKVPool': 'build a pre-allocated flat KV pool with per-layer buffers indexed by integer slot IDs', 'test_set_kv': 'test the MlxKVPool.set_kv method to scatter K and V tensors into specified slots for one layer', 'test_get_kv': 'test the MlxKVPool.get_kv method to gather K and V tensors from specified slots for one layer', 'test_get_kv_all_layers': 'test the MlxKVPool.get_kv_all_layers method to gather K and V tensors across all layers for given slots'}
```

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/mlx/kv_cache/model_patching.py

Prompts

```
['create a BatchedDecodeContext dataclass instance with batch_size, seq_lens, and layer_caches for batched decode', 'set the BatchedDecodeContext on thread-local storage before calling attention wrapper', 'get the current BatchedDecodeContext from thread-local storage', 'clear the BatchedDecodeContext from thread-local storage', 'build an MLXAttentionWrapper that wraps an mlx-lm Attention module for batched decode with per-request RoPE and SDPA', 'create a ContiguousKVCache with n_kv_heads, head_dim, max_seq_len, and dtype for pre-allocated KV buffer', 'test ContiguousKVCache.update_and_fetch to append K/V tensors and return all valid K/V up to current offset', 'review ContiguousKVCache.write_token to write a single token key-value pair at the current offset', 'build a PoolBackedCache from a KV pool and convert it to ContiguousKVCache after the forward pass', "summarize OffsetCache as a data-free shim satisfying mlx-lm's cache protocol without storing actual K/V", 'create an MlxKVPool with pool_size, num_layers, n_kv_heads, head_dim, and dtype parameters', 'build a pre-allocated flat KV pool with per-layer buffers indexed by integer slot IDs', 'test the MlxKVPool.set_kv method to scatter K and V tensors into specified slots for one layer', 'test the MlxKVPool.get_kv method to gather K and V tensors from specified slots for one layer', 'test the MlxKVPool.get_kv_all_layers method to gather K and V tensors across all layers for given slots', 'find the transformer layers and attention attribute name in an MLX model', 'patch all attention layers in an MLX model with MLXAttentionWrapper', 'get the number of transformer layers in an MLX model', 'refactor find_attention_layers to support custom layer attribute names', 'review patch_model_attention to ensure idempotent wrapper installation']
```

Usage

```
{'find_attention_layers': 'find the transformer layers and attention attribute name in an MLX model', 'patch_model_attention': 'patch all attention layers in an MLX model with MLXAttentionWrapper', 'get_num_layers': 'get the number of transformer layers in an MLX model', 'refactor_find_attention_layers': 'refactor find_attention_layers to support custom layer attribute names', 'review_patch_model_attention': 'review patch_model_attention to ensure idempotent wrapper installation'}
```

