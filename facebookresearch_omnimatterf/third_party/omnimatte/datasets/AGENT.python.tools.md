# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/omnimatte/datasets/confidence.py

Prompts

```
['run the CLI to generate confidence maps from forward and backward optical flow files in a dataroot directory', 'compute a confidence map from forward and backward optical flow and an RGB image using threshold parameters', "map pixel-space coordinates to the [-1, 1] range required by PyTorch's grid_sample function", 'create an identity grid of pixel coordinates for a given image height and width', 'review the compute_confidence function that uses forward-backward flow consistency and photometric error to generate confidence maps', 'run the homography CLI tool to compute world bounds from a homography file', 'run transform2h to apply a 2D homogeneous transformation on x and y coordinates', 'run compute_world_bounds to find min and max coordinates from a list of homographies', 'review the transform2h function that applies 2D homogeneous transformation using a 3x3 matrix', 'review the compute_world_bounds function that computes bounding box coordinates from homographies']
```

Usage

```
{'run_confidence_map_generation': 'run the CLI to generate confidence maps from forward and backward optical flow files in a dataroot directory', 'compute_confidence_map': 'compute a confidence map from forward and backward optical flow and an RGB image using threshold parameters', 'map_coords_for_grid_sample': "map pixel-space coordinates to the [-1, 1] range required by PyTorch's grid_sample function", 'create_identity_grid': 'create an identity grid of pixel coordinates for a given image height and width', 'review_compute_confidence': 'review the compute_confidence function that uses forward-backward flow consistency and photometric error to generate confidence maps'}
```

## File: facebookresearch_omnimatterf/third_party/omnimatte/datasets/homography.py

Prompts

```
['run the CLI to generate confidence maps from forward and backward optical flow files in a dataroot directory', 'compute a confidence map from forward and backward optical flow and an RGB image using threshold parameters', "map pixel-space coordinates to the [-1, 1] range required by PyTorch's grid_sample function", 'create an identity grid of pixel coordinates for a given image height and width', 'review the compute_confidence function that uses forward-backward flow consistency and photometric error to generate confidence maps', 'run the homography CLI tool to compute world bounds from a homography file', 'run transform2h to apply a 2D homogeneous transformation on x and y coordinates', 'run compute_world_bounds to find min and max coordinates from a list of homographies', 'review the transform2h function that applies 2D homogeneous transformation using a 3x3 matrix', 'review the compute_world_bounds function that computes bounding box coordinates from homographies']
```

Usage

```
{'run_homography_cli': 'run the homography CLI tool to compute world bounds from a homography file', 'run_transform2h': 'run transform2h to apply a 2D homogeneous transformation on x and y coordinates', 'run_compute_world_bounds': 'run compute_world_bounds to find min and max coordinates from a list of homographies', 'review_transform2h': 'review the transform2h function that applies 2D homogeneous transformation using a 3x3 matrix', 'review_compute_world_bounds': 'review the compute_world_bounds function that computes bounding box coordinates from homographies'}
```

