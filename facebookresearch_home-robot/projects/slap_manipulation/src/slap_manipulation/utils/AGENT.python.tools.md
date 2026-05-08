# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/slap_manipulation/src/slap_manipulation/utils/data_visualizers.py

Prompts

```
['visualize a point cloud with an end-effector pose coordinate frame and a labeled closest interaction point sphere', 'visualize a point cloud with a semantic mask highlighting points matching a given semantic ID in green', 'create an Open3D coordinate frame mesh at a keyframe origin position with an optional rotation matrix', 'create a colored sphere mesh at a closest interaction point to mark it in the visualization', 'normalize RGB color values from 0-255 to 0-1 range for Open3D point cloud rendering', 'crop a point cloud around a given voxel location with a specified radius', 'crop and mean-center a point cloud around a predicted interaction point for action prediction', 'find the closest point in a point cloud to a line defined by a gripper position and action axis', 'filter point cloud points by depth range and remove duplicates via fine-resolution voxelization', 'aggregate features over a downsampled point cloud using Open3D index trace vectors', 'build a python module to instantiate CombinedSLAPPlanner with a StretchClient robot instance', 'create a function that linearly interpolates between waypoints and gripper states for smooth motion', 'run the plan_for_skill method to generate a joint trajectory from pose matrices and gripper commands', 'test the try_executing_skill method to execute a predefined end-effector trajectory on the Stretch robot', 'review the _send_action_to_tf helper that broadcasts predicted action poses to ROS TF for visualization', 'build a 4x4 rotation matrix from an angle, direction vector, and optional pivot point', 'create a 4x4 translation matrix from a 3D direction vector for spatial transforms', 'test spherical linear interpolation between two quaternions with a given fraction and spin', 'refactor code to decompose a 4x4 transformation matrix into scale, shear, angles, translation, and perspective', 'review the superimposition_matrix function that aligns two sets of 3D vectors using SVD or quaternion methods']
```

Usage

```
{'visualize_point_cloud_with_keypoint_and_closest_point': 'visualize a point cloud with an end-effector pose coordinate frame and a labeled closest interaction point sphere', 'visualize_point_cloud_with_semantic_mask': 'visualize a point cloud with a semantic mask highlighting points matching a given semantic ID in green', 'create_coordinate_frame_for_ee_pose': 'create an Open3D coordinate frame mesh at a keyframe origin position with an optional rotation matrix', 'create_sphere_marker_for_interaction_point': 'create a colored sphere mesh at a closest interaction point to mark it in the visualization', 'normalize_rgb_values_for_point_cloud': 'normalize RGB color values from 0-255 to 0-1 range for Open3D point cloud rendering'}
```

## File: facebookresearch_home-robot/projects/slap_manipulation/src/slap_manipulation/utils/pointcloud_preprocessing.py

Prompts

```
['visualize a point cloud with an end-effector pose coordinate frame and a labeled closest interaction point sphere', 'visualize a point cloud with a semantic mask highlighting points matching a given semantic ID in green', 'create an Open3D coordinate frame mesh at a keyframe origin position with an optional rotation matrix', 'create a colored sphere mesh at a closest interaction point to mark it in the visualization', 'normalize RGB color values from 0-255 to 0-1 range for Open3D point cloud rendering', 'crop a point cloud around a given voxel location with a specified radius', 'crop and mean-center a point cloud around a predicted interaction point for action prediction', 'find the closest point in a point cloud to a line defined by a gripper position and action axis', 'filter point cloud points by depth range and remove duplicates via fine-resolution voxelization', 'aggregate features over a downsampled point cloud using Open3D index trace vectors', 'build a python module to instantiate CombinedSLAPPlanner with a StretchClient robot instance', 'create a function that linearly interpolates between waypoints and gripper states for smooth motion', 'run the plan_for_skill method to generate a joint trajectory from pose matrices and gripper commands', 'test the try_executing_skill method to execute a predefined end-effector trajectory on the Stretch robot', 'review the _send_action_to_tf helper that broadcasts predicted action poses to ROS TF for visualization', 'build a 4x4 rotation matrix from an angle, direction vector, and optional pivot point', 'create a 4x4 translation matrix from a 3D direction vector for spatial transforms', 'test spherical linear interpolation between two quaternions with a given fraction and spin', 'refactor code to decompose a 4x4 transformation matrix into scale, shear, angles, translation, and perspective', 'review the superimposition_matrix function that aligns two sets of 3D vectors using SVD or quaternion methods']
```

Usage

```
{'crop_point_cloud_around_voxel': 'crop a point cloud around a given voxel location with a specified radius', 'get_local_action_prediction_problem': 'crop and mean-center a point cloud around a predicted interaction point for action prediction', 'find_closest_point_to_line': 'find the closest point in a point cloud to a line defined by a gripper position and action axis', 'filter_and_remove_duplicate_points': 'filter point cloud points by depth range and remove duplicates via fine-resolution voxelization', 'aggregate_features': 'aggregate features over a downsampled point cloud using Open3D index trace vectors'}
```

## File: facebookresearch_home-robot/projects/slap_manipulation/src/slap_manipulation/utils/slap_planner.py

Prompts

```
['visualize a point cloud with an end-effector pose coordinate frame and a labeled closest interaction point sphere', 'visualize a point cloud with a semantic mask highlighting points matching a given semantic ID in green', 'create an Open3D coordinate frame mesh at a keyframe origin position with an optional rotation matrix', 'create a colored sphere mesh at a closest interaction point to mark it in the visualization', 'normalize RGB color values from 0-255 to 0-1 range for Open3D point cloud rendering', 'crop a point cloud around a given voxel location with a specified radius', 'crop and mean-center a point cloud around a predicted interaction point for action prediction', 'find the closest point in a point cloud to a line defined by a gripper position and action axis', 'filter point cloud points by depth range and remove duplicates via fine-resolution voxelization', 'aggregate features over a downsampled point cloud using Open3D index trace vectors', 'build a python module to instantiate CombinedSLAPPlanner with a StretchClient robot instance', 'create a function that linearly interpolates between waypoints and gripper states for smooth motion', 'run the plan_for_skill method to generate a joint trajectory from pose matrices and gripper commands', 'test the try_executing_skill method to execute a predefined end-effector trajectory on the Stretch robot', 'review the _send_action_to_tf helper that broadcasts predicted action poses to ROS TF for visualization', 'build a 4x4 rotation matrix from an angle, direction vector, and optional pivot point', 'create a 4x4 translation matrix from a 3D direction vector for spatial transforms', 'test spherical linear interpolation between two quaternions with a given fraction and spin', 'refactor code to decompose a 4x4 transformation matrix into scale, shear, angles, translation, and perspective', 'review the superimposition_matrix function that aligns two sets of 3D vectors using SVD or quaternion methods']
```

Usage

```
{'build_CombinedSLAPPlanner': 'build a python module to instantiate CombinedSLAPPlanner with a StretchClient robot instance', 'create_linear_interpolation': 'create a function that linearly interpolates between waypoints and gripper states for smooth motion', 'run_plan_for_skill': 'run the plan_for_skill method to generate a joint trajectory from pose matrices and gripper commands', 'test_try_executing_skill': 'test the try_executing_skill method to execute a predefined end-effector trajectory on the Stretch robot', 'review_send_action_to_tf': 'review the _send_action_to_tf helper that broadcasts predicted action poses to ROS TF for visualization'}
```

## File: facebookresearch_home-robot/projects/slap_manipulation/src/slap_manipulation/utils/transformations.py

Prompts

```
['visualize a point cloud with an end-effector pose coordinate frame and a labeled closest interaction point sphere', 'visualize a point cloud with a semantic mask highlighting points matching a given semantic ID in green', 'create an Open3D coordinate frame mesh at a keyframe origin position with an optional rotation matrix', 'create a colored sphere mesh at a closest interaction point to mark it in the visualization', 'normalize RGB color values from 0-255 to 0-1 range for Open3D point cloud rendering', 'crop a point cloud around a given voxel location with a specified radius', 'crop and mean-center a point cloud around a predicted interaction point for action prediction', 'find the closest point in a point cloud to a line defined by a gripper position and action axis', 'filter point cloud points by depth range and remove duplicates via fine-resolution voxelization', 'aggregate features over a downsampled point cloud using Open3D index trace vectors', 'build a python module to instantiate CombinedSLAPPlanner with a StretchClient robot instance', 'create a function that linearly interpolates between waypoints and gripper states for smooth motion', 'run the plan_for_skill method to generate a joint trajectory from pose matrices and gripper commands', 'test the try_executing_skill method to execute a predefined end-effector trajectory on the Stretch robot', 'review the _send_action_to_tf helper that broadcasts predicted action poses to ROS TF for visualization', 'build a 4x4 rotation matrix from an angle, direction vector, and optional pivot point', 'create a 4x4 translation matrix from a 3D direction vector for spatial transforms', 'test spherical linear interpolation between two quaternions with a given fraction and spin', 'refactor code to decompose a 4x4 transformation matrix into scale, shear, angles, translation, and perspective', 'review the superimposition_matrix function that aligns two sets of 3D vectors using SVD or quaternion methods']
```

Usage

```
{'build_rotation_matrix': 'build a 4x4 rotation matrix from an angle, direction vector, and optional pivot point', 'create_translation_matrix': 'create a 4x4 translation matrix from a 3D direction vector for spatial transforms', 'test_quaternion_slerp': 'test spherical linear interpolation between two quaternions with a given fraction and spin', 'refactor_decompose_matrix': 'refactor code to decompose a 4x4 transformation matrix into scale, shear, angles, translation, and perspective', 'review_superimposition_matrix': 'review the superimposition_matrix function that aligns two sets of 3D vectors using SVD or quaternion methods'}
```

