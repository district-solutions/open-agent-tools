# Agent Python Tools

- repo: facebookresearch/ava-256
- repo_uri: https://github.com/facebookresearch/ava-256

## File: facebookresearch_ava-256/extensions/mvpraymarch/mvpraymarch.py

Prompts

```
['run raymarching on volumetric primitives with ray origins, directions, and template grids to render RGBA images', 'build a BVH acceleration structure from primitive position, rotation, and scale tensors for faster raymarching', 'review the MVPRaymarch custom autograd Function class that implements forward and backward passes for volumetric raymarching', 'create a PyTorch module that converts 3D rotation vectors into 3x3 rotation matrices using Rodrigues formula', 'test gradient correctness by comparing pure Python raymarching results against the CUDA-accelerated mvpraymarch implementation']
```

Usage

```
{'run_mvpraymarch': 'run raymarching on volumetric primitives with ray origins, directions, and template grids to render RGBA images', 'build_accel_bvh': 'build a BVH acceleration structure from primitive position, rotation, and scale tensors for faster raymarching', 'review_mvpraymarch_class': 'review the MVPRaymarch custom autograd Function class that implements forward and backward passes for volumetric raymarching', 'create_rodrigues_module': 'create a PyTorch module that converts 3D rotation vectors into 3x3 rotation matrices using Rodrigues formula', 'test_gradcheck': 'test gradient correctness by comparing pure Python raymarching results against the CUDA-accelerated mvpraymarch implementation'}
```

