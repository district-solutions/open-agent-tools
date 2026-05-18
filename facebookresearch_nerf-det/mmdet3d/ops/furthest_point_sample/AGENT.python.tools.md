# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/ops/furthest_point_sample/furthest_point_sample.py

Prompts

```
['build a python module to run furthest_point_sample on a batch of 3D point cloud coordinates', 'build a python module to run furthest_point_sample_with_dist on a precomputed pairwise distance matrix', 'test the FurthestPointSampling class by sampling N points from a (B, N, 3) point cloud tensor', 'test the FurthestPointSamplingWithDist class by sampling N points from a (B, N, N) distance tensor', 'review the furthest_point_sample_ext CUDA extension wrapper calls used by both sampling functions', 'build a Points_Sampler module to sample 3D points using D-FPS, F-FPS, or FS methods', 'create a DFPS_Sampler class to sample points using Euclidean distances for furthest point sampling', 'create a FFPS_Sampler class to sample points using feature distances for furthest point sampling', 'create a FS_Sampler class to sample points using both feature and Euclidean distances simultaneously', 'review the get_sampler_type function to return the correct sampler class for a given sampler type string', 'calculate the normalized square distance between two sets of PyTorch point feature tensors', 'calculate the unnormalized square distance between two point feature tensors by setting norm to False', 'calculate the pairwise distance matrix of a single point feature tensor against itself', 'review the calc_square_dist function to understand how it computes pairwise distances using the expansion formula', 'refactor calc_square_dist to use torch.cdist for improved performance on large point clouds']
```

Usage

```
{'build_furthest_point_sample': 'build a python module to run furthest_point_sample on a batch of 3D point cloud coordinates', 'build_furthest_point_sample_with_dist': 'build a python module to run furthest_point_sample_with_dist on a precomputed pairwise distance matrix', 'test_FurthestPointSampling': 'test the FurthestPointSampling class by sampling N points from a (B, N, 3) point cloud tensor', 'test_FurthestPointSamplingWithDist': 'test the FurthestPointSamplingWithDist class by sampling N points from a (B, N, N) distance tensor', 'review_furthest_point_sample_ext': 'review the furthest_point_sample_ext CUDA extension wrapper calls used by both sampling functions'}
```

## File: facebookresearch_nerf-det/mmdet3d/ops/furthest_point_sample/points_sampler.py

Prompts

```
['build a python module to run furthest_point_sample on a batch of 3D point cloud coordinates', 'build a python module to run furthest_point_sample_with_dist on a precomputed pairwise distance matrix', 'test the FurthestPointSampling class by sampling N points from a (B, N, 3) point cloud tensor', 'test the FurthestPointSamplingWithDist class by sampling N points from a (B, N, N) distance tensor', 'review the furthest_point_sample_ext CUDA extension wrapper calls used by both sampling functions', 'build a Points_Sampler module to sample 3D points using D-FPS, F-FPS, or FS methods', 'create a DFPS_Sampler class to sample points using Euclidean distances for furthest point sampling', 'create a FFPS_Sampler class to sample points using feature distances for furthest point sampling', 'create a FS_Sampler class to sample points using both feature and Euclidean distances simultaneously', 'review the get_sampler_type function to return the correct sampler class for a given sampler type string', 'calculate the normalized square distance between two sets of PyTorch point feature tensors', 'calculate the unnormalized square distance between two point feature tensors by setting norm to False', 'calculate the pairwise distance matrix of a single point feature tensor against itself', 'review the calc_square_dist function to understand how it computes pairwise distances using the expansion formula', 'refactor calc_square_dist to use torch.cdist for improved performance on large point clouds']
```

Usage

```
{'build_points_sampler': 'build a Points_Sampler module to sample 3D points using D-FPS, F-FPS, or FS methods', 'create_dfps_sampler': 'create a DFPS_Sampler class to sample points using Euclidean distances for furthest point sampling', 'create_ffps_sampler': 'create a FFPS_Sampler class to sample points using feature distances for furthest point sampling', 'create_fs_sampler': 'create a FS_Sampler class to sample points using both feature and Euclidean distances simultaneously', 'review_get_sampler_type': 'review the get_sampler_type function to return the correct sampler class for a given sampler type string'}
```

## File: facebookresearch_nerf-det/mmdet3d/ops/furthest_point_sample/utils.py

Prompts

```
['build a python module to run furthest_point_sample on a batch of 3D point cloud coordinates', 'build a python module to run furthest_point_sample_with_dist on a precomputed pairwise distance matrix', 'test the FurthestPointSampling class by sampling N points from a (B, N, 3) point cloud tensor', 'test the FurthestPointSamplingWithDist class by sampling N points from a (B, N, N) distance tensor', 'review the furthest_point_sample_ext CUDA extension wrapper calls used by both sampling functions', 'build a Points_Sampler module to sample 3D points using D-FPS, F-FPS, or FS methods', 'create a DFPS_Sampler class to sample points using Euclidean distances for furthest point sampling', 'create a FFPS_Sampler class to sample points using feature distances for furthest point sampling', 'create a FS_Sampler class to sample points using both feature and Euclidean distances simultaneously', 'review the get_sampler_type function to return the correct sampler class for a given sampler type string', 'calculate the normalized square distance between two sets of PyTorch point feature tensors', 'calculate the unnormalized square distance between two point feature tensors by setting norm to False', 'calculate the pairwise distance matrix of a single point feature tensor against itself', 'review the calc_square_dist function to understand how it computes pairwise distances using the expansion formula', 'refactor calc_square_dist to use torch.cdist for improved performance on large point clouds']
```

Usage

```
{'calc_square_dist_basic': 'calculate the normalized square distance between two sets of PyTorch point feature tensors', 'calc_square_dist_unnormalized': 'calculate the unnormalized square distance between two point feature tensors by setting norm to False', 'calc_square_dist_same_set': 'calculate the pairwise distance matrix of a single point feature tensor against itself', 'review_calc_square_dist': 'review the calc_square_dist function to understand how it computes pairwise distances using the expansion formula', 'refactor_calc_square_dist': 'refactor calc_square_dist to use torch.cdist for improved performance on large point clouds'}
```

