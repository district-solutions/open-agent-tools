# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/ops/interpolate/three_interpolate.py

Prompts

```
['build a PyTorch module that performs weighted linear interpolation on 3D features using ThreeInterpolate.forward', 'create a function that computes gradients for three interpolate using ThreeInterpolate.backward', 'test the three_interpolate function by applying weighted interpolation on CUDA feature tensors', 'refactor the ThreeInterpolate class to support additional interpolation neighbor counts beyond three', 'review the ThreeInterpolate class and its CUDA extension wrapper calls for correctness', 'build a python module that finds the top 3 nearest neighbors of target points from a source point cloud', 'create a function that computes L2 distances and indices of 3 nearest neighbors for each target point', 'test the ThreeNN autograd Function class with contiguous CUDA tensors of shape B N 3', 'refactor the ThreeNN backward pass to support gradient computation for nearest neighbor interpolation', 'summarize the three_nn convenience function that applies ThreeNN for finding nearest neighbors in point clouds']
```

Usage

```
{'build_three_interpolate_forward': 'build a PyTorch module that performs weighted linear interpolation on 3D features using ThreeInterpolate.forward', 'create_three_interpolate_backward': 'create a function that computes gradients for three interpolate using ThreeInterpolate.backward', 'test_three_interpolate_apply': 'test the three_interpolate function by applying weighted interpolation on CUDA feature tensors', 'refactor_three_interpolate_class': 'refactor the ThreeInterpolate class to support additional interpolation neighbor counts beyond three', 'review_three_interpolate_ext': 'review the ThreeInterpolate class and its CUDA extension wrapper calls for correctness'}
```

## File: facebookresearch_nerf-det/mmdet3d/ops/interpolate/three_nn.py

Prompts

```
['build a PyTorch module that performs weighted linear interpolation on 3D features using ThreeInterpolate.forward', 'create a function that computes gradients for three interpolate using ThreeInterpolate.backward', 'test the three_interpolate function by applying weighted interpolation on CUDA feature tensors', 'refactor the ThreeInterpolate class to support additional interpolation neighbor counts beyond three', 'review the ThreeInterpolate class and its CUDA extension wrapper calls for correctness', 'build a python module that finds the top 3 nearest neighbors of target points from a source point cloud', 'create a function that computes L2 distances and indices of 3 nearest neighbors for each target point', 'test the ThreeNN autograd Function class with contiguous CUDA tensors of shape B N 3', 'refactor the ThreeNN backward pass to support gradient computation for nearest neighbor interpolation', 'summarize the three_nn convenience function that applies ThreeNN for finding nearest neighbors in point clouds']
```

Usage

```
{'build_three_nn_module': 'build a python module that finds the top 3 nearest neighbors of target points from a source point cloud', 'create_three_nn_forward': 'create a function that computes L2 distances and indices of 3 nearest neighbors for each target point', 'test_three_nn_class': 'test the ThreeNN autograd Function class with contiguous CUDA tensors of shape B N 3', 'refactor_three_nn_backward': 'refactor the ThreeNN backward pass to support gradient computation for nearest neighbor interpolation', 'summarize_three_nn_apply': 'summarize the three_nn convenience function that applies ThreeNN for finding nearest neighbors in point clouds'}
```

