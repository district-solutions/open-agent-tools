# Agent Python Tools

- repo: facebookresearch/fast3r
- repo_uri: https://github.com/facebookresearch/fast3r

## File: facebookresearch_fast3r/fast3r/eval/cam_pose_metric.py

Prompts

```
['compute relative rotation and translation angle errors between predicted and ground truth camera poses in degrees', 'calculate the area under the curve for rotation and translation error arrays using PyTorch tensors', 'compute the closed-form inverse of a batch of 4x4 SE(3) transformation matrices', 'compute the angle in degrees between ground truth and predicted translation vectors', 'compute the absolute relative rotation error in degrees between two batches of rotation matrices', 'run the accuracy function to compute mean and median distance between reconstructed and ground truth points', 'run the completion function to compute mean and median distance from ground truth to reconstructed points', 'run the completion_ratio function to compute the fraction of ground truth points within a distance threshold', 'run the downsample_point_cloud function to reduce point cloud density by removing points closer than a threshold', 'run the compute_iou function to calculate intersection over union between predicted and target voxel grids']
```

Usage

```
{'compute_relative_camera_pose_errors': 'compute relative rotation and translation angle errors between predicted and ground truth camera poses in degrees', 'calculate_auc_for_pose_errors': 'calculate the area under the curve for rotation and translation error arrays using PyTorch tensors', 'invert_se3_matrices': 'compute the closed-form inverse of a batch of 4x4 SE(3) transformation matrices', 'compute_translation_angle_error': 'compute the angle in degrees between ground truth and predicted translation vectors', 'compute_absolute_relative_error': 'compute the absolute relative rotation error in degrees between two batches of rotation matrices'}
```

## File: facebookresearch_fast3r/fast3r/eval/recon_metric.py

Prompts

```
['compute relative rotation and translation angle errors between predicted and ground truth camera poses in degrees', 'calculate the area under the curve for rotation and translation error arrays using PyTorch tensors', 'compute the closed-form inverse of a batch of 4x4 SE(3) transformation matrices', 'compute the angle in degrees between ground truth and predicted translation vectors', 'compute the absolute relative rotation error in degrees between two batches of rotation matrices', 'run the accuracy function to compute mean and median distance between reconstructed and ground truth points', 'run the completion function to compute mean and median distance from ground truth to reconstructed points', 'run the completion_ratio function to compute the fraction of ground truth points within a distance threshold', 'run the downsample_point_cloud function to reduce point cloud density by removing points closer than a threshold', 'run the compute_iou function to calculate intersection over union between predicted and target voxel grids']
```

Usage

```
{'run_accuracy': 'run the accuracy function to compute mean and median distance between reconstructed and ground truth points', 'run_completion': 'run the completion function to compute mean and median distance from ground truth to reconstructed points', 'run_completion_ratio': 'run the completion_ratio function to compute the fraction of ground truth points within a distance threshold', 'run_downsample_point_cloud': 'run the downsample_point_cloud function to reduce point cloud density by removing points closer than a threshold', 'run_compute_iou': 'run the compute_iou function to calculate intersection over union between predicted and target voxel grids'}
```

