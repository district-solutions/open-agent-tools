# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/utils/geometry/_base.py

Prompts

```
['transform a point cloud from geocentric frame to robot base frame using xyt_global_to_base', 'transform a point cloud from robot base frame to geocentric frame using xyt_base_to_global', 'convert SE2 coordinates (x, y, rz) to a sophus SE3 pose object using xyt2sophus', 'convert a sophus SE3 pose object to SE2 coordinates (x, y, rz) using sophus2xyt', 'convert a Pose object with position and quaternion orientation to SE2 coordinates using obs2xyt', 'calculate the smallest difference between two angles in radians using angle_difference', 'interpolate between two angles in radians with a given step size using interpolate_angles', 'review the angle_difference function to understand how it normalizes angles before computing the smallest difference', 'review the interpolate_angles function to understand how it chooses the shortest direction between two angles', 'summarize the angles module that provides utility functions for angle arithmetic in radians']
```

Usage

```
{'transform_global_to_base': 'transform a point cloud from geocentric frame to robot base frame using xyt_global_to_base', 'transform_base_to_global': 'transform a point cloud from robot base frame to geocentric frame using xyt_base_to_global', 'convert_xyt_to_sophus': 'convert SE2 coordinates (x, y, rz) to a sophus SE3 pose object using xyt2sophus', 'convert_sophus_to_xyt': 'convert a sophus SE3 pose object to SE2 coordinates (x, y, rz) using sophus2xyt', 'convert_pose_to_xyt': 'convert a Pose object with position and quaternion orientation to SE2 coordinates using obs2xyt'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/utils/geometry/angles.py

Prompts

```
['transform a point cloud from geocentric frame to robot base frame using xyt_global_to_base', 'transform a point cloud from robot base frame to geocentric frame using xyt_base_to_global', 'convert SE2 coordinates (x, y, rz) to a sophus SE3 pose object using xyt2sophus', 'convert a sophus SE3 pose object to SE2 coordinates (x, y, rz) using sophus2xyt', 'convert a Pose object with position and quaternion orientation to SE2 coordinates using obs2xyt', 'calculate the smallest difference between two angles in radians using angle_difference', 'interpolate between two angles in radians with a given step size using interpolate_angles', 'review the angle_difference function to understand how it normalizes angles before computing the smallest difference', 'review the interpolate_angles function to understand how it chooses the shortest direction between two angles', 'summarize the angles module that provides utility functions for angle arithmetic in radians']
```

Usage

```
{'calculate_angle_difference': 'calculate the smallest difference between two angles in radians using angle_difference', 'interpolate_between_angles': 'interpolate between two angles in radians with a given step size using interpolate_angles', 'review_angle_difference': 'review the angle_difference function to understand how it normalizes angles before computing the smallest difference', 'review_interpolate_angles': 'review the interpolate_angles function to understand how it chooses the shortest direction between two angles', 'summarize_angles_module': 'summarize the angles module that provides utility functions for angle arithmetic in radians'}
```

