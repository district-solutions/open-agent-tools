# Agent Python Tools

- repo: facebookresearch/dynamicstereo
- repo_uri: https://github.com/facebookresearch/dynamic_stereo

## File: facebookresearch_dynamicstereo/evaluation/utils/eval_utils.py

Prompts

```
['compute endpoint error and temporal endpoint error metrics for predicted disparity sequences against ground truth', 'evaluate disparity prediction performance metrics for a batch including mean error and bad pixel percentages', 'convert a depth map and image into a 3D point cloud with optional outlier filtering and extrinsic transforms', 'compute the focal length times baseline scale factor from left and right camera projections', 'create a frozen dataclass representing a perception metric name with optional depth scaling norm and suffix', 'create a PerceptionPrediction dataclass to hold depth map, disparity, image RGB, and foreground probability tensors', 'aggregate per-batch evaluation results using mean or sum reduction across all metrics', 'aggregate per-batch evaluation results and print a formatted table of perception metrics', 'read a ZED stereo camera calibration config file and return rectification maps and poses', 'visualize depth predictions as 3D point cloud reconstruction videos with multiple camera angles']
```

Usage

```
{'eval_endpoint_error_sequence': 'compute endpoint error and temporal endpoint error metrics for predicted disparity sequences against ground truth', 'eval_batch': 'evaluate disparity prediction performance metrics for a batch including mean error and bad pixel percentages', 'depth_to_pcd': 'convert a depth map and image into a 3D point cloud with optional outlier filtering and extrinsic transforms', 'depth2disparity_scale': 'compute the focal length times baseline scale factor from left and right camera projections', 'PerceptionMetric': 'create a frozen dataclass representing a perception metric name with optional depth scaling norm and suffix'}
```

## File: facebookresearch_dynamicstereo/evaluation/utils/utils.py

Prompts

```
['compute endpoint error and temporal endpoint error metrics for predicted disparity sequences against ground truth', 'evaluate disparity prediction performance metrics for a batch including mean error and bad pixel percentages', 'convert a depth map and image into a 3D point cloud with optional outlier filtering and extrinsic transforms', 'compute the focal length times baseline scale factor from left and right camera projections', 'create a frozen dataclass representing a perception metric name with optional depth scaling norm and suffix', 'create a PerceptionPrediction dataclass to hold depth map, disparity, image RGB, and foreground probability tensors', 'aggregate per-batch evaluation results using mean or sum reduction across all metrics', 'aggregate per-batch evaluation results and print a formatted table of perception metrics', 'read a ZED stereo camera calibration config file and return rectification maps and poses', 'visualize depth predictions as 3D point cloud reconstruction videos with multiple camera angles']
```

Usage

```
{'create_PerceptionPrediction': 'create a PerceptionPrediction dataclass to hold depth map, disparity, image RGB, and foreground probability tensors', 'aggregate_eval_results': 'aggregate per-batch evaluation results using mean or sum reduction across all metrics', 'aggregate_and_print_results': 'aggregate per-batch evaluation results and print a formatted table of perception metrics', 'read_calibration': 'read a ZED stereo camera calibration config file and return rectification maps and poses', 'visualize_batch': 'visualize depth predictions as 3D point cloud reconstruction videos with multiple camera angles'}
```

