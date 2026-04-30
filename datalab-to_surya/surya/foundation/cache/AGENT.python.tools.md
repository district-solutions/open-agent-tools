# Agent Python Tools

- repo: datalab-to/surya
- repo_uri: https://github.com/datalab-to/surya

## File: datalab-to_surya/surya/foundation/cache/dynamic_ops.py

Prompts

```
['create a DynamicOpsCache instance with config, batch size, max cache length, text sliding window, device, and dtype', 'build KV cache updates for prefill and decode phases using the DynamicOpsCache.update method with key and value states', 'test the sliding window behavior where image tokens stay in cache and text tokens are rotated out during decode', 'review the prefill and decode attention mask update logic that manages cache-aware attention masks per batch', 'summarize how continuous batching and merge index handling work across text token counts and cache slots', 'create a StaticOpsCache instance with config, batch size, max cache length, sliding window, device, and dtype', 'update key and value cache states for a given layer using prefill or decode mode', 'build a KV cache with sliding window that keeps image tokens and pops text tokens', 'manage attention mask for cache alignment during prefill and decode updates', 'roll decode cache by valid tokens and insert new key and value states at the end']
```

Usage

```
{'create_cache_dynamic_ops': 'create a DynamicOpsCache instance with config, batch size, max cache length, text sliding window, device, and dtype', 'build_update_kv_cache': 'build KV cache updates for prefill and decode phases using the DynamicOpsCache.update method with key and value states', 'test_sliding_window_text': 'test the sliding window behavior where image tokens stay in cache and text tokens are rotated out during decode', 'review_attention_mask_update': 'review the prefill and decode attention mask update logic that manages cache-aware attention masks per batch', 'summarize_continuous_batching': 'summarize how continuous batching and merge index handling work across text token counts and cache slots'}
```

## File: datalab-to_surya/surya/foundation/cache/static_ops.py

Prompts

```
['create a DynamicOpsCache instance with config, batch size, max cache length, text sliding window, device, and dtype', 'build KV cache updates for prefill and decode phases using the DynamicOpsCache.update method with key and value states', 'test the sliding window behavior where image tokens stay in cache and text tokens are rotated out during decode', 'review the prefill and decode attention mask update logic that manages cache-aware attention masks per batch', 'summarize how continuous batching and merge index handling work across text token counts and cache slots', 'create a StaticOpsCache instance with config, batch size, max cache length, sliding window, device, and dtype', 'update key and value cache states for a given layer using prefill or decode mode', 'build a KV cache with sliding window that keeps image tokens and pops text tokens', 'manage attention mask for cache alignment during prefill and decode updates', 'roll decode cache by valid tokens and insert new key and value states at the end']
```

Usage

```
{'create_static_ops_cache': 'create a StaticOpsCache instance with config, batch size, max cache length, sliding window, device, and dtype', 'update_cache_states': 'update key and value cache states for a given layer using prefill or decode mode', 'build_sliding_window_cache': 'build a KV cache with sliding window that keeps image tokens and pops text tokens', 'manage_attention_mask': 'manage attention mask for cache alignment during prefill and decode updates', 'roll_decode_cache': 'roll decode cache by valid tokens and insert new key and value states at the end'}
```

