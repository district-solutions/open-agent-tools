# Agent Python Tools

- repo: facebookresearch/audiomae
- repo_uri: https://github.com/facebookresearch/audiomae

## File: facebookresearch_audiomae/timm_patch/helpers.py

Prompts

```
['use to_2tuple to convert a single integer stride into a 2-tuple for convolution layers', 'use to_4tuple to convert a single integer padding value into a 4-tuple for conv operations', 'use to_3tuple to convert a single integer kernel size into a 3-tuple for 3D convolutions', 'use to_1tuple to wrap a single value into a 1-tuple for consistent tuple handling', 'use _ntuple to create a custom n-tuple converter for arbitrary tuple lengths', 'build a SwinTransformerBlock with specified dim, num_heads, window_size, and shift_size for shifted window attention', 'create a WindowMultiHeadAttention module with scaled cosine self-attention and log-spaced continuous position bias', 'test the window_partition function to split a BHWC tensor into non-overlapping windows of given size', 'test the window_reverse function to reconstruct a BHWC tensor from partitioned windows using window and image size', 'review the Mlp class forward pass that applies fc1, activation, dropout, fc2, and dropout sequentially']
```

Usage

```
{'use_to_2tuple': 'use to_2tuple to convert a single integer stride into a 2-tuple for convolution layers', 'use_to_4tuple': 'use to_4tuple to convert a single integer padding value into a 4-tuple for conv operations', 'use_to_3tuple': 'use to_3tuple to convert a single integer kernel size into a 3-tuple for 3D convolutions', 'use_to_1tuple': 'use to_1tuple to wrap a single value into a 1-tuple for consistent tuple handling', 'use_ntuple': 'use _ntuple to create a custom n-tuple converter for arbitrary tuple lengths'}
```

## File: facebookresearch_audiomae/timm_patch/swin_transformer.py

Prompts

```
['use to_2tuple to convert a single integer stride into a 2-tuple for convolution layers', 'use to_4tuple to convert a single integer padding value into a 4-tuple for conv operations', 'use to_3tuple to convert a single integer kernel size into a 3-tuple for 3D convolutions', 'use to_1tuple to wrap a single value into a 1-tuple for consistent tuple handling', 'use _ntuple to create a custom n-tuple converter for arbitrary tuple lengths', 'build a SwinTransformerBlock with specified dim, num_heads, window_size, and shift_size for shifted window attention', 'create a WindowMultiHeadAttention module with scaled cosine self-attention and log-spaced continuous position bias', 'test the window_partition function to split a BHWC tensor into non-overlapping windows of given size', 'test the window_reverse function to reconstruct a BHWC tensor from partitioned windows using window and image size', 'review the Mlp class forward pass that applies fc1, activation, dropout, fc2, and dropout sequentially']
```

Usage

```
{'build_swin_transformer_block': 'build a SwinTransformerBlock with specified dim, num_heads, window_size, and shift_size for shifted window attention', 'create_window_multihead_attention': 'create a WindowMultiHeadAttention module with scaled cosine self-attention and log-spaced continuous position bias', 'test_window_partition': 'test the window_partition function to split a BHWC tensor into non-overlapping windows of given size', 'test_window_reverse': 'test the window_reverse function to reconstruct a BHWC tensor from partitioned windows using window and image size', 'review_mlp_forward': 'review the Mlp class forward pass that applies fc1, activation, dropout, fc2, and dropout sequentially'}
```

