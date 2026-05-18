# Agent Python Tools

- repo: facebookresearch/neuralvolumes
- repo_uri: https://github.com/facebookresearch/neuralvolumes

## File: facebookresearch_neuralvolumes/models/volsamplers/warpvoxel.py

Prompts

```
['build a VolSampler module to sample 3D volumes from a template using grid sampling with optional warp fields', 'create a VolSampler with displacementwarp enabled to add warp offsets to positions before sampling the template volume', 'test the VolSampler forward pass by providing position tensors and a template volume to get sampled RGB and alpha values', 'review the VolSampler forward method to understand how global warp parameters transform positions before grid sampling', 'refactor the VolSampler forward method to improve the validity mask computation for out-of-bounds position filtering']
```

Usage

```
{'build_VolSampler': 'build a VolSampler module to sample 3D volumes from a template using grid sampling with optional warp fields', 'create_VolSampler_displacementwarp': 'create a VolSampler with displacementwarp enabled to add warp offsets to positions before sampling the template volume', 'test_VolSampler_forward': 'test the VolSampler forward pass by providing position tensors and a template volume to get sampled RGB and alpha values', 'review_VolSampler_gwarps': 'review the VolSampler forward method to understand how global warp parameters transform positions before grid sampling', 'refactor_VolSampler_valid_mask': 'refactor the VolSampler forward method to improve the validity mask computation for out-of-bounds position filtering'}
```

