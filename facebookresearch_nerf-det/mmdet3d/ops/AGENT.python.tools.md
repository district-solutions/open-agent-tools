# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/ops/norm.py

Prompts

```
['build a NaiveSyncBatchNorm1d layer for synchronized batch normalization on 3D tensors in multi-GPU training', 'build a NaiveSyncBatchNorm2d layer for synchronized batch normalization on 4D tensors in multi-GPU training', 'review the AllReduce forward method that uses all_gather to sum inputs across distributed workers', 'review the AllReduce backward method that uses all_reduce to synchronize gradients across distributed workers', 'refactor the NaiveSyncBatchNorm1d forward method to compute mean and variance across GPUs for 3D tensor normalization', 'build a SparseBottleneck block with submanifold sparse convolution for PartA^2 3D detection', 'build a SparseBasicBlock with submanifold sparse convolution for sparse 3D feature extraction', 'build a sparse convolution module with configurable conv, norm, and activation layer ordering', 'review the SparseBottleneck forward pass that applies three conv layers with batch norm and residual connection', 'review the SparseBasicBlock forward pass that applies two conv layers with norm and residual connection']
```

Usage

```
{'build_NaiveSyncBatchNorm1d': 'build a NaiveSyncBatchNorm1d layer for synchronized batch normalization on 3D tensors in multi-GPU training', 'build_NaiveSyncBatchNorm2d': 'build a NaiveSyncBatchNorm2d layer for synchronized batch normalization on 4D tensors in multi-GPU training', 'review_AllReduce_forward': 'review the AllReduce forward method that uses all_gather to sum inputs across distributed workers', 'review_AllReduce_backward': 'review the AllReduce backward method that uses all_reduce to synchronize gradients across distributed workers', 'refactor_NaiveSyncBatchNorm1d_forward': 'refactor the NaiveSyncBatchNorm1d forward method to compute mean and variance across GPUs for 3D tensor normalization'}
```

## File: facebookresearch_nerf-det/mmdet3d/ops/sparse_block.py

Prompts

```
['build a NaiveSyncBatchNorm1d layer for synchronized batch normalization on 3D tensors in multi-GPU training', 'build a NaiveSyncBatchNorm2d layer for synchronized batch normalization on 4D tensors in multi-GPU training', 'review the AllReduce forward method that uses all_gather to sum inputs across distributed workers', 'review the AllReduce backward method that uses all_reduce to synchronize gradients across distributed workers', 'refactor the NaiveSyncBatchNorm1d forward method to compute mean and variance across GPUs for 3D tensor normalization', 'build a SparseBottleneck block with submanifold sparse convolution for PartA^2 3D detection', 'build a SparseBasicBlock with submanifold sparse convolution for sparse 3D feature extraction', 'build a sparse convolution module with configurable conv, norm, and activation layer ordering', 'review the SparseBottleneck forward pass that applies three conv layers with batch norm and residual connection', 'review the SparseBasicBlock forward pass that applies two conv layers with norm and residual connection']
```

Usage

```
{'build_SparseBottleneck': 'build a SparseBottleneck block with submanifold sparse convolution for PartA^2 3D detection', 'build_SparseBasicBlock': 'build a SparseBasicBlock with submanifold sparse convolution for sparse 3D feature extraction', 'build_make_sparse_convmodule': 'build a sparse convolution module with configurable conv, norm, and activation layer ordering', 'review_SparseBottleneck_forward': 'review the SparseBottleneck forward pass that applies three conv layers with batch norm and residual connection', 'review_SparseBasicBlock_forward': 'review the SparseBasicBlock forward pass that applies two conv layers with norm and residual connection'}
```

