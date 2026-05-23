# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/modules/attention/full_attn.py

Prompts

```
['run scaled dot product attention on a packed qkv tensor with shape [N, L, 3, H, C]', 'run scaled dot product attention with separate q and kv tensors for cross-attention', 'run scaled dot product attention with separate q, k, and v tensors', 'review the attention backend selection logic supporting xformers, flash_attn, sdpa, and naive modes', 'test the naive scaled dot product attention implementation using matrix multiplication and softmax', 'build a MultiHeadAttention module with self-attention mode and configurable number of heads and channels', 'build a MultiHeadAttention module with cross-attention mode using separate query and key-value projections', 'build a RotaryPositionEmbedder to apply rotary position embeddings to query and key tensors', 'build a MultiHeadRMSNorm layer to normalize multi-head attention queries and keys with learnable gamma', 'build a MOTMultiHeadSelfAttention module that performs modality-aware self-attention with protected modalities like shape']
```

Usage

```
{'run_scaled_dot_product_attention_qkv': 'run scaled dot product attention on a packed qkv tensor with shape [N, L, 3, H, C]', 'run_scaled_dot_product_attention_q_kv': 'run scaled dot product attention with separate q and kv tensors for cross-attention', 'run_scaled_dot_product_attention_q_k_v': 'run scaled dot product attention with separate q, k, and v tensors', 'review_attention_backend_selection': 'review the attention backend selection logic supporting xformers, flash_attn, sdpa, and naive modes', 'test_naive_sdpa_implementation': 'test the naive scaled dot product attention implementation using matrix multiplication and softmax'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/modules/attention/modules.py

Prompts

```
['run scaled dot product attention on a packed qkv tensor with shape [N, L, 3, H, C]', 'run scaled dot product attention with separate q and kv tensors for cross-attention', 'run scaled dot product attention with separate q, k, and v tensors', 'review the attention backend selection logic supporting xformers, flash_attn, sdpa, and naive modes', 'test the naive scaled dot product attention implementation using matrix multiplication and softmax', 'build a MultiHeadAttention module with self-attention mode and configurable number of heads and channels', 'build a MultiHeadAttention module with cross-attention mode using separate query and key-value projections', 'build a RotaryPositionEmbedder to apply rotary position embeddings to query and key tensors', 'build a MultiHeadRMSNorm layer to normalize multi-head attention queries and keys with learnable gamma', 'build a MOTMultiHeadSelfAttention module that performs modality-aware self-attention with protected modalities like shape']
```

Usage

```
{'build_MultiHeadAttention_self': 'build a MultiHeadAttention module with self-attention mode and configurable number of heads and channels', 'build_MultiHeadAttention_cross': 'build a MultiHeadAttention module with cross-attention mode using separate query and key-value projections', 'build_RotaryPositionEmbedder': 'build a RotaryPositionEmbedder to apply rotary position embeddings to query and key tensors', 'build_MultiHeadRMSNorm': 'build a MultiHeadRMSNorm layer to normalize multi-head attention queries and keys with learnable gamma', 'build_MOTMultiHeadSelfAttention': 'build a MOTMultiHeadSelfAttention module that performs modality-aware self-attention with protected modalities like shape'}
```

