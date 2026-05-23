# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/concept_graphs/datautils.py

Prompts

```
['normalize an RGB image tensor from 0-255 range to 0-1 range for neural network input', 'scale camera intrinsics matrix to match resized frame dimensions by height and width ratios', 'convert 3D point and unit quaternion pairs to 4x4 homogeneous transformation matrices', 'convert a quaternion in x y z w format to a 3x3 rotation matrix', 'apply an SE3 rigid-body transformation matrix to rotate and translate a 3D point cloud', 'create a 3x3 camera intrinsics matrix from fx, fy, cx, cy values', 'extract fx, fy, cx, cy scalars from a camera intrinsics matrix', 'build a GradSLAMDataset PyTorch dataset for RGB-D SLAM with configurable stride and pose options', 'load a HabitatDataset to read Habitat simulator RGB-D sequences with camera poses', 'preprocess a depth image by resizing, scaling to meters, and converting channel layout', 'convert a PyTorch tensor to a NumPy array using the to_numpy function', 'convert a NumPy array to a PyTorch tensor on a specified device using to_tensor', 'extract a scalar value from a single-element PyTorch tensor using the to_scalar function', 'extract a scalar value from a single-element NumPy array using the to_scalar function', 'convert a single-element PyTorch tensor to a Python int or float scalar using to_scalar']
```

Usage

```
{'normalize_image': 'normalize an RGB image tensor from 0-255 range to 0-1 range for neural network input', 'scale_intrinsics': 'scale camera intrinsics matrix to match resized frame dimensions by height and width ratios', 'pointquaternion_to_homogeneous': 'convert 3D point and unit quaternion pairs to 4x4 homogeneous transformation matrices', 'quaternion_to_rotation_matrix': 'convert a quaternion in x y z w format to a 3x3 rotation matrix', 'transform_pointcloud': 'apply an SE3 rigid-body transformation matrix to rotate and translate a 3D point cloud'}
```

## File: facebookresearch_partnr-planner/habitat_llm/concept_graphs/hab_dataset.py

Prompts

```
['normalize an RGB image tensor from 0-255 range to 0-1 range for neural network input', 'scale camera intrinsics matrix to match resized frame dimensions by height and width ratios', 'convert 3D point and unit quaternion pairs to 4x4 homogeneous transformation matrices', 'convert a quaternion in x y z w format to a 3x3 rotation matrix', 'apply an SE3 rigid-body transformation matrix to rotate and translate a 3D point cloud', 'create a 3x3 camera intrinsics matrix from fx, fy, cx, cy values', 'extract fx, fy, cx, cy scalars from a camera intrinsics matrix', 'build a GradSLAMDataset PyTorch dataset for RGB-D SLAM with configurable stride and pose options', 'load a HabitatDataset to read Habitat simulator RGB-D sequences with camera poses', 'preprocess a depth image by resizing, scaling to meters, and converting channel layout', 'convert a PyTorch tensor to a NumPy array using the to_numpy function', 'convert a NumPy array to a PyTorch tensor on a specified device using to_tensor', 'extract a scalar value from a single-element PyTorch tensor using the to_scalar function', 'extract a scalar value from a single-element NumPy array using the to_scalar function', 'convert a single-element PyTorch tensor to a Python int or float scalar using to_scalar']
```

Usage

```
{'create_intrinsics_matrix': 'create a 3x3 camera intrinsics matrix from fx, fy, cx, cy values', 'extract_intrinsics_from_matrix': 'extract fx, fy, cx, cy scalars from a camera intrinsics matrix', 'build_gradslam_dataset': 'build a GradSLAMDataset PyTorch dataset for RGB-D SLAM with configurable stride and pose options', 'load_habitat_dataset': 'load a HabitatDataset to read Habitat simulator RGB-D sequences with camera poses', 'preprocess_depth_image': 'preprocess a depth image by resizing, scaling to meters, and converting channel layout'}
```

## File: facebookresearch_partnr-planner/habitat_llm/concept_graphs/typecasting_utils.py

Prompts

```
['normalize an RGB image tensor from 0-255 range to 0-1 range for neural network input', 'scale camera intrinsics matrix to match resized frame dimensions by height and width ratios', 'convert 3D point and unit quaternion pairs to 4x4 homogeneous transformation matrices', 'convert a quaternion in x y z w format to a 3x3 rotation matrix', 'apply an SE3 rigid-body transformation matrix to rotate and translate a 3D point cloud', 'create a 3x3 camera intrinsics matrix from fx, fy, cx, cy values', 'extract fx, fy, cx, cy scalars from a camera intrinsics matrix', 'build a GradSLAMDataset PyTorch dataset for RGB-D SLAM with configurable stride and pose options', 'load a HabitatDataset to read Habitat simulator RGB-D sequences with camera poses', 'preprocess a depth image by resizing, scaling to meters, and converting channel layout', 'convert a PyTorch tensor to a NumPy array using the to_numpy function', 'convert a NumPy array to a PyTorch tensor on a specified device using to_tensor', 'extract a scalar value from a single-element PyTorch tensor using the to_scalar function', 'extract a scalar value from a single-element NumPy array using the to_scalar function', 'convert a single-element PyTorch tensor to a Python int or float scalar using to_scalar']
```

Usage

```
{'convert_tensor_to_numpy': 'convert a PyTorch tensor to a NumPy array using the to_numpy function', 'convert_numpy_to_tensor': 'convert a NumPy array to a PyTorch tensor on a specified device using to_tensor', 'extract_scalar_from_tensor': 'extract a scalar value from a single-element PyTorch tensor using the to_scalar function', 'extract_scalar_from_numpy': 'extract a scalar value from a single-element NumPy array using the to_scalar function', 'convert_tensor_to_scalar': 'convert a single-element PyTorch tensor to a Python int or float scalar using to_scalar'}
```

