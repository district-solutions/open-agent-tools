# Agent Python Tools

- repo: facebookresearch/dinov3
- repo_uri: https://github.com/facebookresearch/dinov3

## File: facebookresearch_dinov3/dinov3/eval/segmentation/models/utils/batch_norm.py

Prompts

```
['create a FrozenBatchNorm2d layer with fixed batch statistics for a given number of features', 'convert all BatchNorm2d and SyncBatchNorm layers in a module to FrozenBatchNorm2d', 'convert all FrozenBatchNorm2d layers in a module back to standard BatchNorm2d', 'get a normalization layer by name string like BN, SyncBN, FrozenBN, GN, or LN', 'create a NaiveSyncBatchNorm layer for correct cross-worker gradient sync with equal or N-weighted stats', 'build a Multi-Scale Deformable Attention module with configurable heads, levels, and sampling points', 'create a forward pass through MSDeformAttn using query, reference points, and flattened multi-scale input features', 'test the pure PyTorch multi-scale deformable attention core function with bilinear grid sampling', 'review the MSDeformAttnFunction autograd Function class for custom forward and backward CUDA passes', 'refactor the MSDeformAttn parameter initialization to use angular sampling offsets and Xavier uniform weights', 'build a PositionEmbeddingSine module with 64 positional features for transformer image encoding', 'create a PositionEmbeddingSine with normalize=True and custom scale for normalized image coordinates', 'run forward pass on a feature tensor through PositionEmbeddingSine to get sinusoidal positional embeddings', 'test PositionEmbeddingSine forward pass with a boolean mask to handle padded image regions', 'review the PositionEmbeddingSine __repr__ output to inspect num_pos_feats, temperature, normalize, and scale config', 'build a Transformer encoder-decoder model with configurable d_model, nhead, and layer count for segmentation', 'create a TransformerEncoder that stacks cloned encoder layers with optional layer normalization', 'create a TransformerDecoder that returns intermediate activations from all decoding layers', 'test the TransformerEncoderLayer forward pass with self-attention and feedforward sublayers', 'test the TransformerDecoderLayer forward pass with self-attention, cross-attention, and feedforward sublayers']
```

Usage

```
{'create_FrozenBatchNorm2d': 'create a FrozenBatchNorm2d layer with fixed batch statistics for a given number of features', 'convert_frozen_batchnorm': 'convert all BatchNorm2d and SyncBatchNorm layers in a module to FrozenBatchNorm2d', 'convert_frozenbatchnorm2d_to_batchnorm2d': 'convert all FrozenBatchNorm2d layers in a module back to standard BatchNorm2d', 'get_norm': 'get a normalization layer by name string like BN, SyncBN, FrozenBN, GN, or LN', 'create_NaiveSyncBatchNorm': 'create a NaiveSyncBatchNorm layer for correct cross-worker gradient sync with equal or N-weighted stats'}
```

## File: facebookresearch_dinov3/dinov3/eval/segmentation/models/utils/ms_deform_attn.py

Prompts

```
['create a FrozenBatchNorm2d layer with fixed batch statistics for a given number of features', 'convert all BatchNorm2d and SyncBatchNorm layers in a module to FrozenBatchNorm2d', 'convert all FrozenBatchNorm2d layers in a module back to standard BatchNorm2d', 'get a normalization layer by name string like BN, SyncBN, FrozenBN, GN, or LN', 'create a NaiveSyncBatchNorm layer for correct cross-worker gradient sync with equal or N-weighted stats', 'build a Multi-Scale Deformable Attention module with configurable heads, levels, and sampling points', 'create a forward pass through MSDeformAttn using query, reference points, and flattened multi-scale input features', 'test the pure PyTorch multi-scale deformable attention core function with bilinear grid sampling', 'review the MSDeformAttnFunction autograd Function class for custom forward and backward CUDA passes', 'refactor the MSDeformAttn parameter initialization to use angular sampling offsets and Xavier uniform weights', 'build a PositionEmbeddingSine module with 64 positional features for transformer image encoding', 'create a PositionEmbeddingSine with normalize=True and custom scale for normalized image coordinates', 'run forward pass on a feature tensor through PositionEmbeddingSine to get sinusoidal positional embeddings', 'test PositionEmbeddingSine forward pass with a boolean mask to handle padded image regions', 'review the PositionEmbeddingSine __repr__ output to inspect num_pos_feats, temperature, normalize, and scale config', 'build a Transformer encoder-decoder model with configurable d_model, nhead, and layer count for segmentation', 'create a TransformerEncoder that stacks cloned encoder layers with optional layer normalization', 'create a TransformerDecoder that returns intermediate activations from all decoding layers', 'test the TransformerEncoderLayer forward pass with self-attention and feedforward sublayers', 'test the TransformerDecoderLayer forward pass with self-attention, cross-attention, and feedforward sublayers']
```

Usage

```
{'build_msdeformattn_module': 'build a Multi-Scale Deformable Attention module with configurable heads, levels, and sampling points', 'create_msdeformattn_forward': 'create a forward pass through MSDeformAttn using query, reference points, and flattened multi-scale input features', 'test_ms_deform_attn_core_pytorch': 'test the pure PyTorch multi-scale deformable attention core function with bilinear grid sampling', 'review_msdeformattnfunction_autograd': 'review the MSDeformAttnFunction autograd Function class for custom forward and backward CUDA passes', 'refactor_msdeformattn_parameter_init': 'refactor the MSDeformAttn parameter initialization to use angular sampling offsets and Xavier uniform weights'}
```

## File: facebookresearch_dinov3/dinov3/eval/segmentation/models/utils/position_encoding.py

Prompts

```
['create a FrozenBatchNorm2d layer with fixed batch statistics for a given number of features', 'convert all BatchNorm2d and SyncBatchNorm layers in a module to FrozenBatchNorm2d', 'convert all FrozenBatchNorm2d layers in a module back to standard BatchNorm2d', 'get a normalization layer by name string like BN, SyncBN, FrozenBN, GN, or LN', 'create a NaiveSyncBatchNorm layer for correct cross-worker gradient sync with equal or N-weighted stats', 'build a Multi-Scale Deformable Attention module with configurable heads, levels, and sampling points', 'create a forward pass through MSDeformAttn using query, reference points, and flattened multi-scale input features', 'test the pure PyTorch multi-scale deformable attention core function with bilinear grid sampling', 'review the MSDeformAttnFunction autograd Function class for custom forward and backward CUDA passes', 'refactor the MSDeformAttn parameter initialization to use angular sampling offsets and Xavier uniform weights', 'build a PositionEmbeddingSine module with 64 positional features for transformer image encoding', 'create a PositionEmbeddingSine with normalize=True and custom scale for normalized image coordinates', 'run forward pass on a feature tensor through PositionEmbeddingSine to get sinusoidal positional embeddings', 'test PositionEmbeddingSine forward pass with a boolean mask to handle padded image regions', 'review the PositionEmbeddingSine __repr__ output to inspect num_pos_feats, temperature, normalize, and scale config', 'build a Transformer encoder-decoder model with configurable d_model, nhead, and layer count for segmentation', 'create a TransformerEncoder that stacks cloned encoder layers with optional layer normalization', 'create a TransformerDecoder that returns intermediate activations from all decoding layers', 'test the TransformerEncoderLayer forward pass with self-attention and feedforward sublayers', 'test the TransformerDecoderLayer forward pass with self-attention, cross-attention, and feedforward sublayers']
```

Usage

```
{'build_sine_positional_encoding': 'build a PositionEmbeddingSine module with 64 positional features for transformer image encoding', 'create_normalized_positional_encoding': 'create a PositionEmbeddingSine with normalize=True and custom scale for normalized image coordinates', 'run_forward_positional_encoding': 'run forward pass on a feature tensor through PositionEmbeddingSine to get sinusoidal positional embeddings', 'test_positional_encoding_with_mask': 'test PositionEmbeddingSine forward pass with a boolean mask to handle padded image regions', 'review_positional_encoding_repr': 'review the PositionEmbeddingSine __repr__ output to inspect num_pos_feats, temperature, normalize, and scale config'}
```

## File: facebookresearch_dinov3/dinov3/eval/segmentation/models/utils/transformer.py

Prompts

```
['create a FrozenBatchNorm2d layer with fixed batch statistics for a given number of features', 'convert all BatchNorm2d and SyncBatchNorm layers in a module to FrozenBatchNorm2d', 'convert all FrozenBatchNorm2d layers in a module back to standard BatchNorm2d', 'get a normalization layer by name string like BN, SyncBN, FrozenBN, GN, or LN', 'create a NaiveSyncBatchNorm layer for correct cross-worker gradient sync with equal or N-weighted stats', 'build a Multi-Scale Deformable Attention module with configurable heads, levels, and sampling points', 'create a forward pass through MSDeformAttn using query, reference points, and flattened multi-scale input features', 'test the pure PyTorch multi-scale deformable attention core function with bilinear grid sampling', 'review the MSDeformAttnFunction autograd Function class for custom forward and backward CUDA passes', 'refactor the MSDeformAttn parameter initialization to use angular sampling offsets and Xavier uniform weights', 'build a PositionEmbeddingSine module with 64 positional features for transformer image encoding', 'create a PositionEmbeddingSine with normalize=True and custom scale for normalized image coordinates', 'run forward pass on a feature tensor through PositionEmbeddingSine to get sinusoidal positional embeddings', 'test PositionEmbeddingSine forward pass with a boolean mask to handle padded image regions', 'review the PositionEmbeddingSine __repr__ output to inspect num_pos_feats, temperature, normalize, and scale config', 'build a Transformer encoder-decoder model with configurable d_model, nhead, and layer count for segmentation', 'create a TransformerEncoder that stacks cloned encoder layers with optional layer normalization', 'create a TransformerDecoder that returns intermediate activations from all decoding layers', 'test the TransformerEncoderLayer forward pass with self-attention and feedforward sublayers', 'test the TransformerDecoderLayer forward pass with self-attention, cross-attention, and feedforward sublayers']
```

Usage

```
{'build_Transformer': 'build a Transformer encoder-decoder model with configurable d_model, nhead, and layer count for segmentation', 'create_TransformerEncoder': 'create a TransformerEncoder that stacks cloned encoder layers with optional layer normalization', 'create_TransformerDecoder': 'create a TransformerDecoder that returns intermediate activations from all decoding layers', 'test_TransformerEncoderLayer': 'test the TransformerEncoderLayer forward pass with self-attention and feedforward sublayers', 'test_TransformerDecoderLayer': 'test the TransformerDecoderLayer forward pass with self-attention, cross-attention, and feedforward sublayers'}
```

