# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/modules/sparse/conv/conv_spconv.py

Prompts

```
['create a SparseConv3d layer with specified in_channels, out_channels, and kernel_size for sparse 3D convolution', 'create a SparseInverseConv3d layer for upsampling sparse 3D tensors with transposed convolution', 'run forward pass of SparseConv3d on a SparseTensor input and get the convolved output', 'run forward pass of SparseInverseConv3d to recover spatial resolution from a downsampled SparseTensor', 'review the SparseConv3d spatial sorting logic that reorders tensor features when stride changes spatial layout']
```

Usage

```
{'create_sparse_conv3d_layer': 'create a SparseConv3d layer with specified in_channels, out_channels, and kernel_size for sparse 3D convolution', 'create_sparse_inverse_conv3d_layer': 'create a SparseInverseConv3d layer for upsampling sparse 3D tensors with transposed convolution', 'run_sparse_conv3d_forward': 'run forward pass of SparseConv3d on a SparseTensor input and get the convolved output', 'run_sparse_inverse_conv3d_forward': 'run forward pass of SparseInverseConv3d to recover spatial resolution from a downsampled SparseTensor', 'review_sparse_conv_spatial_sorting': 'review the SparseConv3d spatial sorting logic that reorders tensor features when stride changes spatial layout'}
```

