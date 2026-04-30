# Agent Python Tools

- repo: OpenBMB/VoxCPM
- repo_uri: https://github.com/OpenBMB/VoxCPM

## File: OpenBMB_VoxCPM/src/voxcpm/modules/minicpm4/cache.py

Prompts

```
['create a StaticKVCache instance with num_layers, num_kv_heads, dim_kv_head, batch_size, device, dtype, and max_length', 'get the key and value cache tensors for a specific layer index from a StaticKVCache instance', 'step the StaticKVCache forward by one token position and return the current cache index', 'fill the StaticKVCache with existing key-value tensors from a list of layer cache pairs', 'test that StaticKVCache raises ValueError when current_length reaches max_length during step', 'build a MiniCPM4 model by instantiating MiniCPMModel with a MiniCPM4Config for transformer inference', 'create an RMS normalization layer using MiniCPMRMSNorm with a given hidden size and epsilon', 'test the apply_rotary_pos_emb function to apply rotary position embeddings to query and key tensors', 'refactor MiniCPMAttention to support grouped query attention with kv caching for autoregressive decoding', 'summarize the MiniCPMDecoderLayer forward and forward_step methods for prefill and decode phases']
```

Usage

```
{'create_static_kv_cache': 'create a StaticKVCache instance with num_layers, num_kv_heads, dim_kv_head, batch_size, device, dtype, and max_length', 'get_layer_cache': 'get the key and value cache tensors for a specific layer index from a StaticKVCache instance', 'step_cache': 'step the StaticKVCache forward by one token position and return the current cache index', 'fill_caches': 'fill the StaticKVCache with existing key-value tensors from a list of layer cache pairs', 'test_cache_full': 'test that StaticKVCache raises ValueError when current_length reaches max_length during step'}
```

## File: OpenBMB_VoxCPM/src/voxcpm/modules/minicpm4/model.py

Prompts

```
['create a StaticKVCache instance with num_layers, num_kv_heads, dim_kv_head, batch_size, device, dtype, and max_length', 'get the key and value cache tensors for a specific layer index from a StaticKVCache instance', 'step the StaticKVCache forward by one token position and return the current cache index', 'fill the StaticKVCache with existing key-value tensors from a list of layer cache pairs', 'test that StaticKVCache raises ValueError when current_length reaches max_length during step', 'build a MiniCPM4 model by instantiating MiniCPMModel with a MiniCPM4Config for transformer inference', 'create an RMS normalization layer using MiniCPMRMSNorm with a given hidden size and epsilon', 'test the apply_rotary_pos_emb function to apply rotary position embeddings to query and key tensors', 'refactor MiniCPMAttention to support grouped query attention with kv caching for autoregressive decoding', 'summarize the MiniCPMDecoderLayer forward and forward_step methods for prefill and decode phases']
```

Usage

```
{'build_minicpm_model': 'build a MiniCPM4 model by instantiating MiniCPMModel with a MiniCPM4Config for transformer inference', 'create_rms_layernorm': 'create an RMS normalization layer using MiniCPMRMSNorm with a given hidden size and epsilon', 'test_apply_rotary_pos_emb': 'test the apply_rotary_pos_emb function to apply rotary position embeddings to query and key tensors', 'refactor_minicpm_attention': 'refactor MiniCPMAttention to support grouped query attention with kv caching for autoregressive decoding', 'summarize_minicpm_decoder_layer': 'summarize the MiniCPMDecoderLayer forward and forward_step methods for prefill and decode phases'}
```

