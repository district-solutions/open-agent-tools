# Agent Python Tools

- repo: facebookresearch/mvp
- repo_uri: https://github.com/facebookresearch/mvp

## File: facebookresearch_mvp/extensions/utils/utils.py

Prompts

```
['compute camera ray positions, directions, and tmin/tmax from view parameters and pixel coordinates using CUDA', 'run the forward pass of ComputeRaydirs to compute ray positions and directions from view pose and camera intrinsics', 'convert a batch of 3D rotation vectors into 3x3 rotation matrices using Rodrigues formula', 'run the gradient check comparing pure PyTorch ray direction computation against the CUDA implementation', 'review the compute_raydirs function and ComputeRaydirs autograd Function for correctness and performance']
```

Usage

```
{'compute_raydirs': 'compute camera ray positions, directions, and tmin/tmax from view parameters and pixel coordinates using CUDA', 'ComputeRaydirs_forward': 'run the forward pass of ComputeRaydirs to compute ray positions and directions from view pose and camera intrinsics', 'Rodrigues_forward': 'convert a batch of 3D rotation vectors into 3x3 rotation matrices using Rodrigues formula', 'gradcheck': 'run the gradient check comparing pure PyTorch ray direction computation against the CUDA implementation', 'review_compute_raydirs': 'review the compute_raydirs function and ComputeRaydirs autograd Function for correctness and performance'}
```

