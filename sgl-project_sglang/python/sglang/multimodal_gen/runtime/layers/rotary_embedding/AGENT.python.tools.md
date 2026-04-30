# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/layers/rotary_embedding/base.py

Prompts

```
['build a RotaryEmbedding instance with head_size, rotary_dim, max_position_embeddings, base, is_neox_style, and dtype parameters', 'create a LinearScalingRotaryEmbedding instance with a scaling_factor for extended context window support', 'test the forward_native method that applies rotary embeddings to query and key tensors given positions', 'review the forward_cuda method that dispatches to the native PyTorch forward implementation', 'summarize the _compute_cos_sin_cache method that computes inverse frequency, cos, and sin lookup tables', 'create a rotary embedding using get_rope with head_size, rotary_dim, max_position, base, and optional rope_scaling', 'build a linear-scaling rotary embedding by passing rope_type linear with factor to get_rope', 'create rotary positional embeddings with get_rotary_pos_embed given rope_sizes, hidden_size, heads_num, and rope_theta', 'build a cached N-D rotary embedding via get_rotary_pos_embed with LRU eviction after 16 entries', 'test get_rope handles rope_type linear scaling and expands max_position_embeddings by factor', 'create 1D rotary positional embeddings from position indices with configurable theta and interpolation factor', 'build a 1D rotary embedding module with LRU-cached frequency computation for reusable positional encodings', 'build an N-dimensional rotary embedding module that composes multiple 1D generators for multi-axis positional encoding', 'test NDRotaryEmbedding grid-based forward pass with sequence parallel sharding and frame offset support', 'summarize how get_1d_rotary_pos_embed precomputes cos and sin frequency tensors for rotary embeddings', 'apply flashinfer RoPE to query and key tensors in-place using a cos-sin cache', 'apply rotary positional embeddings to a tensor using cos and sin caches with neox or gpt-j style', 'register flashinfer apply_rope_with_cos_sin_cache_inplace as a custom op with query and key mutation', 'fallback to triton apply_rotary_embedding when flashinfer is unavailable on amd/rocm hardware', 'validate that query and key tensors are 4D with matching shapes and cos_sin_cache is 2D']
```

Usage

```
{'build_RotaryEmbedding': 'build a RotaryEmbedding instance with head_size, rotary_dim, max_position_embeddings, base, is_neox_style, and dtype parameters', 'create_LinearScalingRotaryEmbedding': 'create a LinearScalingRotaryEmbedding instance with a scaling_factor for extended context window support', 'test_forward_native': 'test the forward_native method that applies rotary embeddings to query and key tensors given positions', 'review_forward_cuda': 'review the forward_cuda method that dispatches to the native PyTorch forward implementation', 'summarize_compute_cos_sin_cache': 'summarize the _compute_cos_sin_cache method that computes inverse frequency, cos, and sin lookup tables'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/layers/rotary_embedding/factory.py

Prompts

```
['build a RotaryEmbedding instance with head_size, rotary_dim, max_position_embeddings, base, is_neox_style, and dtype parameters', 'create a LinearScalingRotaryEmbedding instance with a scaling_factor for extended context window support', 'test the forward_native method that applies rotary embeddings to query and key tensors given positions', 'review the forward_cuda method that dispatches to the native PyTorch forward implementation', 'summarize the _compute_cos_sin_cache method that computes inverse frequency, cos, and sin lookup tables', 'create a rotary embedding using get_rope with head_size, rotary_dim, max_position, base, and optional rope_scaling', 'build a linear-scaling rotary embedding by passing rope_type linear with factor to get_rope', 'create rotary positional embeddings with get_rotary_pos_embed given rope_sizes, hidden_size, heads_num, and rope_theta', 'build a cached N-D rotary embedding via get_rotary_pos_embed with LRU eviction after 16 entries', 'test get_rope handles rope_type linear scaling and expands max_position_embeddings by factor', 'create 1D rotary positional embeddings from position indices with configurable theta and interpolation factor', 'build a 1D rotary embedding module with LRU-cached frequency computation for reusable positional encodings', 'build an N-dimensional rotary embedding module that composes multiple 1D generators for multi-axis positional encoding', 'test NDRotaryEmbedding grid-based forward pass with sequence parallel sharding and frame offset support', 'summarize how get_1d_rotary_pos_embed precomputes cos and sin frequency tensors for rotary embeddings', 'apply flashinfer RoPE to query and key tensors in-place using a cos-sin cache', 'apply rotary positional embeddings to a tensor using cos and sin caches with neox or gpt-j style', 'register flashinfer apply_rope_with_cos_sin_cache_inplace as a custom op with query and key mutation', 'fallback to triton apply_rotary_embedding when flashinfer is unavailable on amd/rocm hardware', 'validate that query and key tensors are 4D with matching shapes and cos_sin_cache is 2D']
```

Usage

```
{'create_get_rope': 'create a rotary embedding using get_rope with head_size, rotary_dim, max_position, base, and optional rope_scaling', 'build_linear_scaling_rope': 'build a linear-scaling rotary embedding by passing rope_type linear with factor to get_rope', 'create_rotary_pos_embed': 'create rotary positional embeddings with get_rotary_pos_embed given rope_sizes, hidden_size, heads_num, and rope_theta', 'build_nd_rotary_cache': 'build a cached N-D rotary embedding via get_rotary_pos_embed with LRU eviction after 16 entries', 'test_get_rope_scaling': 'test get_rope handles rope_type linear scaling and expands max_position_embeddings by factor'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/layers/rotary_embedding/mrope.py

Prompts

```
['build a RotaryEmbedding instance with head_size, rotary_dim, max_position_embeddings, base, is_neox_style, and dtype parameters', 'create a LinearScalingRotaryEmbedding instance with a scaling_factor for extended context window support', 'test the forward_native method that applies rotary embeddings to query and key tensors given positions', 'review the forward_cuda method that dispatches to the native PyTorch forward implementation', 'summarize the _compute_cos_sin_cache method that computes inverse frequency, cos, and sin lookup tables', 'create a rotary embedding using get_rope with head_size, rotary_dim, max_position, base, and optional rope_scaling', 'build a linear-scaling rotary embedding by passing rope_type linear with factor to get_rope', 'create rotary positional embeddings with get_rotary_pos_embed given rope_sizes, hidden_size, heads_num, and rope_theta', 'build a cached N-D rotary embedding via get_rotary_pos_embed with LRU eviction after 16 entries', 'test get_rope handles rope_type linear scaling and expands max_position_embeddings by factor', 'create 1D rotary positional embeddings from position indices with configurable theta and interpolation factor', 'build a 1D rotary embedding module with LRU-cached frequency computation for reusable positional encodings', 'build an N-dimensional rotary embedding module that composes multiple 1D generators for multi-axis positional encoding', 'test NDRotaryEmbedding grid-based forward pass with sequence parallel sharding and frame offset support', 'summarize how get_1d_rotary_pos_embed precomputes cos and sin frequency tensors for rotary embeddings', 'apply flashinfer RoPE to query and key tensors in-place using a cos-sin cache', 'apply rotary positional embeddings to a tensor using cos and sin caches with neox or gpt-j style', 'register flashinfer apply_rope_with_cos_sin_cache_inplace as a custom op with query and key mutation', 'fallback to triton apply_rotary_embedding when flashinfer is unavailable on amd/rocm hardware', 'validate that query and key tensors are 4D with matching shapes and cos_sin_cache is 2D']
```

Usage

```
{'create_function_get_1d_rotary_pos_embed': 'create 1D rotary positional embeddings from position indices with configurable theta and interpolation factor', 'build_class_OneDRotaryEmbedding': 'build a 1D rotary embedding module with LRU-cached frequency computation for reusable positional encodings', 'build_class_NDRotaryEmbedding': 'build an N-dimensional rotary embedding module that composes multiple 1D generators for multi-axis positional encoding', 'test_NDRotaryEmbedding_forward_from_grid': 'test NDRotaryEmbedding grid-based forward pass with sequence parallel sharding and frame offset support', 'summarize_function_get_1d_rotary_pos_embed': 'summarize how get_1d_rotary_pos_embed precomputes cos and sin frequency tensors for rotary embeddings'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/layers/rotary_embedding/utils.py

Prompts

```
['build a RotaryEmbedding instance with head_size, rotary_dim, max_position_embeddings, base, is_neox_style, and dtype parameters', 'create a LinearScalingRotaryEmbedding instance with a scaling_factor for extended context window support', 'test the forward_native method that applies rotary embeddings to query and key tensors given positions', 'review the forward_cuda method that dispatches to the native PyTorch forward implementation', 'summarize the _compute_cos_sin_cache method that computes inverse frequency, cos, and sin lookup tables', 'create a rotary embedding using get_rope with head_size, rotary_dim, max_position, base, and optional rope_scaling', 'build a linear-scaling rotary embedding by passing rope_type linear with factor to get_rope', 'create rotary positional embeddings with get_rotary_pos_embed given rope_sizes, hidden_size, heads_num, and rope_theta', 'build a cached N-D rotary embedding via get_rotary_pos_embed with LRU eviction after 16 entries', 'test get_rope handles rope_type linear scaling and expands max_position_embeddings by factor', 'create 1D rotary positional embeddings from position indices with configurable theta and interpolation factor', 'build a 1D rotary embedding module with LRU-cached frequency computation for reusable positional encodings', 'build an N-dimensional rotary embedding module that composes multiple 1D generators for multi-axis positional encoding', 'test NDRotaryEmbedding grid-based forward pass with sequence parallel sharding and frame offset support', 'summarize how get_1d_rotary_pos_embed precomputes cos and sin frequency tensors for rotary embeddings', 'apply flashinfer RoPE to query and key tensors in-place using a cos-sin cache', 'apply rotary positional embeddings to a tensor using cos and sin caches with neox or gpt-j style', 'register flashinfer apply_rope_with_cos_sin_cache_inplace as a custom op with query and key mutation', 'fallback to triton apply_rotary_embedding when flashinfer is unavailable on amd/rocm hardware', 'validate that query and key tensors are 4D with matching shapes and cos_sin_cache is 2D']
```

Usage

```
{'apply_flashinfer_rope_qk_inplace': 'apply flashinfer RoPE to query and key tensors in-place using a cos-sin cache', '_apply_rotary_emb': 'apply rotary positional embeddings to a tensor using cos and sin caches with neox or gpt-j style', 'register_flashinfer_rope_custom_op': 'register flashinfer apply_rope_with_cos_sin_cache_inplace as a custom op with query and key mutation', 'fallback_triton_rope': 'fallback to triton apply_rotary_embedding when flashinfer is unavailable on amd/rocm hardware', 'validate_rope_input_shapes': 'validate that query and key tensors are 4D with matching shapes and cos_sin_cache is 2D'}
```

