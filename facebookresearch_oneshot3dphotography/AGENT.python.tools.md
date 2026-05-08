# Agent Python Tools

- repo: facebookresearch/oneshot3dphotography
- repo_uri: https://github.com/facebookresearch/one_shot_3d_photography

## File: facebookresearch_oneshot3dphotography/cli.py

Prompts

```
['run the Tiefenrausch model to estimate depth from a single image file using Caffe2', 'run the Tiefenrausch model to estimate depth for all images in a directory recursively', 'create a DepthEstimatorCaffe2 instance from init and predict Caffe2 protobuf net files', 'estimate depth from an image and save both the disparity numpy array and a visualization PNG', 'parse command line arguments for single file or directory depth estimation with optional visualization output', 'create a function that visualizes a depth map using the magma colormap with gamma correction', 'create a function that visualizes a depth map with custom min and max depth values', 'create a function that converts all raw depth files in a directory to colorized PNG images', 'create a function that reprocesses all depth files in a directory overwriting existing PNG outputs', 'review the CM_MAGMA constant that converts the magma colormap to a BGR uint8 array for OpenCV']
```

Usage

```
{'run_depth_estimation_single_image': 'run the Tiefenrausch model to estimate depth from a single image file using Caffe2', 'run_depth_estimation_directory': 'run the Tiefenrausch model to estimate depth for all images in a directory recursively', 'create_depth_estimator': 'create a DepthEstimatorCaffe2 instance from init and predict Caffe2 protobuf net files', 'estimate_depth_with_visualization': 'estimate depth from an image and save both the disparity numpy array and a visualization PNG', 'parse_args_depth_cli': 'parse command line arguments for single file or directory depth estimation with optional visualization output'}
```

## File: facebookresearch_oneshot3dphotography/visualization.py

Prompts

```
['run the Tiefenrausch model to estimate depth from a single image file using Caffe2', 'run the Tiefenrausch model to estimate depth for all images in a directory recursively', 'create a DepthEstimatorCaffe2 instance from init and predict Caffe2 protobuf net files', 'estimate depth from an image and save both the disparity numpy array and a visualization PNG', 'parse command line arguments for single file or directory depth estimation with optional visualization output', 'create a function that visualizes a depth map using the magma colormap with gamma correction', 'create a function that visualizes a depth map with custom min and max depth values', 'create a function that converts all raw depth files in a directory to colorized PNG images', 'create a function that reprocesses all depth files in a directory overwriting existing PNG outputs', 'review the CM_MAGMA constant that converts the magma colormap to a BGR uint8 array for OpenCV']
```

Usage

```
{'visualize_depth_map': 'create a function that visualizes a depth map using the magma colormap with gamma correction', 'visualize_depth_with_range': 'create a function that visualizes a depth map with custom min and max depth values', 'visualize_depth_directory': 'create a function that converts all raw depth files in a directory to colorized PNG images', 'visualize_depth_dir_force': 'create a function that reprocesses all depth files in a directory overwriting existing PNG outputs', 'review_CM_MAGMA': 'review the CM_MAGMA constant that converts the magma colormap to a BGR uint8 array for OpenCV'}
```

