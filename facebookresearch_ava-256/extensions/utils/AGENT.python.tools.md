# Agent Python Tools

- repo: facebookresearch/ava-256
- repo_uri: https://github.com/facebookresearch/ava-256

## File: facebookresearch_ava-256/extensions/utils/utils.py

Prompts

```
['compute ray positions, directions, and t-min/max for camera rays using CUDA-accelerated forward pass', 'compute camera ray origins, normalized directions, and bounding box intersection intervals from view parameters', 'convert rotation vectors to 3x3 rotation matrices using the Rodrigues formula for camera orientation', 'apply the Rodrigues nn.Module to transform a batch of rotation vectors into rotation matrices', 'validate CUDA ray direction computation against pure PyTorch reference implementation and compare gradients']
```

Usage

```
{'compute_raydirs_cuda': 'compute ray positions, directions, and t-min/max for camera rays using CUDA-accelerated forward pass', 'compute_raydirs_function': 'compute camera ray origins, normalized directions, and bounding box intersection intervals from view parameters', 'rodrigues_rotation_matrix': 'convert rotation vectors to 3x3 rotation matrices using the Rodrigues formula for camera orientation', 'rodrigues_module_forward': 'apply the Rodrigues nn.Module to transform a batch of rotation vectors into rotation matrices', 'gradcheck_validate_cuda': 'validate CUDA ray direction computation against pure PyTorch reference implementation and compare gradients'}
```

