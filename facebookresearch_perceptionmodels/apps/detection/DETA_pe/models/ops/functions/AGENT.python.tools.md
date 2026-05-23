# Agent Python Tools

- repo: facebookresearch/perceptionmodels
- repo_uri: https://github.com/facebookresearch/perception_models

## File: facebookresearch_perceptionmodels/apps/detection/DETA_pe/models/ops/functions/ms_deform_attn_func.py

Prompts

```
['build a multi-scale deformable attention forward pass using the CUDA-accelerated MSDA kernel', 'build a multi-scale deformable attention backward pass to compute gradients for value, sampling locations, and attention weights', 'test the pure PyTorch reference implementation of multi-scale deformable attention for debugging and validation', 'review the MSDeformAttnFunction autograd Function class that wraps CUDA forward and backward kernels', 'refactor the PyTorch reference implementation to use F.grid_sample for bilinear sampling across multiple feature levels']
```

Usage

```
{'build_ms_deform_attn_forward': 'build a multi-scale deformable attention forward pass using the CUDA-accelerated MSDA kernel', 'build_ms_deform_attn_backward': 'build a multi-scale deformable attention backward pass to compute gradients for value, sampling locations, and attention weights', 'test_ms_deform_attn_core_pytorch': 'test the pure PyTorch reference implementation of multi-scale deformable attention for debugging and validation', 'review_MSDeformAttnFunction_class': 'review the MSDeformAttnFunction autograd Function class that wraps CUDA forward and backward kernels', 'refactor_ms_deform_attn_core_pytorch': 'refactor the PyTorch reference implementation to use F.grid_sample for bilinear sampling across multiple feature levels'}
```

