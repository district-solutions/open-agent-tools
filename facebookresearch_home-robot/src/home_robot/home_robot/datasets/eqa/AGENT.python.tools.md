# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/datasets/eqa/dataset.py

Prompts

```
['create a GradSLAMDataset instance from a config dict to load color, depth, and pose data', 'create an EQADataset instance from a config dict and sequence folder to load EQA data', 'build a 3x3 camera intrinsics matrix from fx, fy, cx, cy values using as_intrinsics_matrix', 'extract fx, fy, cx, cy scalars from a camera intrinsics matrix using from_intrinsics_matrix', 'read depth buffer data from an EXR image file using readEXR_onlydepth', 'normalize an RGB image from 0-255 range to 0-1 range using the normalize_image function', 'convert an image from channels last HWC format to channels first CHW format', 'scale a camera intrinsics matrix for resized frames using the scale_intrinsics function', 'convert 3D point and quaternion poses to 4x4 homogeneous transformation matrices', 'convert a sequence of camera poses to frame-to-frame transformations relative to the first frame', 'convert a PyTorch tensor to a NumPy array using the to_numpy utility function', 'convert a NumPy array to a PyTorch tensor with optional device placement using to_tensor', 'convert a single-element NumPy array, PyTorch tensor, or float to a Python scalar using to_scalar', 'compute the relative 4x4 homogeneous transformation between two reference poses using relative_transformation', 'review the utils module containing to_numpy, to_tensor, to_scalar, and relative_transformation helper functions']
```

Usage

```
{'create_gradslam_dataset': 'create a GradSLAMDataset instance from a config dict to load color, depth, and pose data', 'create_eqa_dataset': 'create an EQADataset instance from a config dict and sequence folder to load EQA data', 'build_intrinsics_matrix': 'build a 3x3 camera intrinsics matrix from fx, fy, cx, cy values using as_intrinsics_matrix', 'extract_intrinsics_from_matrix': 'extract fx, fy, cx, cy scalars from a camera intrinsics matrix using from_intrinsics_matrix', 'read_depth_from_exr': 'read depth buffer data from an EXR image file using readEXR_onlydepth'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/datasets/eqa/datautils.py

Prompts

```
['create a GradSLAMDataset instance from a config dict to load color, depth, and pose data', 'create an EQADataset instance from a config dict and sequence folder to load EQA data', 'build a 3x3 camera intrinsics matrix from fx, fy, cx, cy values using as_intrinsics_matrix', 'extract fx, fy, cx, cy scalars from a camera intrinsics matrix using from_intrinsics_matrix', 'read depth buffer data from an EXR image file using readEXR_onlydepth', 'normalize an RGB image from 0-255 range to 0-1 range using the normalize_image function', 'convert an image from channels last HWC format to channels first CHW format', 'scale a camera intrinsics matrix for resized frames using the scale_intrinsics function', 'convert 3D point and quaternion poses to 4x4 homogeneous transformation matrices', 'convert a sequence of camera poses to frame-to-frame transformations relative to the first frame', 'convert a PyTorch tensor to a NumPy array using the to_numpy utility function', 'convert a NumPy array to a PyTorch tensor with optional device placement using to_tensor', 'convert a single-element NumPy array, PyTorch tensor, or float to a Python scalar using to_scalar', 'compute the relative 4x4 homogeneous transformation between two reference poses using relative_transformation', 'review the utils module containing to_numpy, to_tensor, to_scalar, and relative_transformation helper functions']
```

Usage

```
{'normalize_image': 'normalize an RGB image from 0-255 range to 0-1 range using the normalize_image function', 'channels_first': 'convert an image from channels last HWC format to channels first CHW format', 'scale_intrinsics': 'scale a camera intrinsics matrix for resized frames using the scale_intrinsics function', 'pointquaternion_to_homogeneous': 'convert 3D point and quaternion poses to 4x4 homogeneous transformation matrices', 'poses_to_transforms': 'convert a sequence of camera poses to frame-to-frame transformations relative to the first frame'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/datasets/eqa/utils.py

Prompts

```
['create a GradSLAMDataset instance from a config dict to load color, depth, and pose data', 'create an EQADataset instance from a config dict and sequence folder to load EQA data', 'build a 3x3 camera intrinsics matrix from fx, fy, cx, cy values using as_intrinsics_matrix', 'extract fx, fy, cx, cy scalars from a camera intrinsics matrix using from_intrinsics_matrix', 'read depth buffer data from an EXR image file using readEXR_onlydepth', 'normalize an RGB image from 0-255 range to 0-1 range using the normalize_image function', 'convert an image from channels last HWC format to channels first CHW format', 'scale a camera intrinsics matrix for resized frames using the scale_intrinsics function', 'convert 3D point and quaternion poses to 4x4 homogeneous transformation matrices', 'convert a sequence of camera poses to frame-to-frame transformations relative to the first frame', 'convert a PyTorch tensor to a NumPy array using the to_numpy utility function', 'convert a NumPy array to a PyTorch tensor with optional device placement using to_tensor', 'convert a single-element NumPy array, PyTorch tensor, or float to a Python scalar using to_scalar', 'compute the relative 4x4 homogeneous transformation between two reference poses using relative_transformation', 'review the utils module containing to_numpy, to_tensor, to_scalar, and relative_transformation helper functions']
```

Usage

```
{'convert_tensor_to_numpy': 'convert a PyTorch tensor to a NumPy array using the to_numpy utility function', 'convert_numpy_to_tensor': 'convert a NumPy array to a PyTorch tensor with optional device placement using to_tensor', 'convert_to_scalar': 'convert a single-element NumPy array, PyTorch tensor, or float to a Python scalar using to_scalar', 'compute_relative_transformation': 'compute the relative 4x4 homogeneous transformation between two reference poses using relative_transformation', 'review_utils_functions': 'review the utils module containing to_numpy, to_tensor, to_scalar, and relative_transformation helper functions'}
```

