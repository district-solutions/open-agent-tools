# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/transformations/_transformations.py

Prompts

```
['build a python module that converts XYZ euler angles to a 3x3 rotation matrix using euler_to_rmat', 'build a python module that converts a unit quaternion to a 4x4 homogeneous rotation matrix using quat_to_mat', 'build a python module that performs spherical linear interpolation between two quaternions using quat_slerp', 'build a python module that converts a 3x3 rotation matrix to ZYX euler angles using rmat_to_euler', 'build a python module that computes the active quaternion difference between source and target orientations using quat_diff_active', 'convert an axis-angle rotation vector to a unit quaternion using axisangle_to_quat', 'multiply two quaternions together using quat_mul to compose rotations', 'rotate a 3D position vector by a unit quaternion using quat_rotate', 'spherically interpolate between two unit quaternions using quat_slerp with a fraction', 'integrate a unit quaternion by an angular velocity vector using integrate_quat', 'convert euler angles to a 3x3 rotation matrix with a specified axis ordering like XYZ or ZYZ', 'build a 4x4 homogeneous transformation matrix from position and quaternion using pos_quat_to_hmat', 'slerp interpolate between two quaternions at a given fraction using quat_slerp', 'transform a 6D twist or wrench between coordinate frames using velocity_transform or force_transform']
```

Usage

```
{'convert_euler_to_rotation_matrix': 'build a python module that converts XYZ euler angles to a 3x3 rotation matrix using euler_to_rmat', 'convert_quaternion_to_rotation_matrix': 'build a python module that converts a unit quaternion to a 4x4 homogeneous rotation matrix using quat_to_mat', 'compute_quaternion_slerp': 'build a python module that performs spherical linear interpolation between two quaternions using quat_slerp', 'convert_rotation_matrix_to_euler': 'build a python module that converts a 3x3 rotation matrix to ZYX euler angles using rmat_to_euler', 'compute_quaternion_difference': 'build a python module that computes the active quaternion difference between source and target orientations using quat_diff_active'}
```

## File: google-deepmind_dmrobotics/py/transformations/_transformations_quat.py

Prompts

```
['build a python module that converts XYZ euler angles to a 3x3 rotation matrix using euler_to_rmat', 'build a python module that converts a unit quaternion to a 4x4 homogeneous rotation matrix using quat_to_mat', 'build a python module that performs spherical linear interpolation between two quaternions using quat_slerp', 'build a python module that converts a 3x3 rotation matrix to ZYX euler angles using rmat_to_euler', 'build a python module that computes the active quaternion difference between source and target orientations using quat_diff_active', 'convert an axis-angle rotation vector to a unit quaternion using axisangle_to_quat', 'multiply two quaternions together using quat_mul to compose rotations', 'rotate a 3D position vector by a unit quaternion using quat_rotate', 'spherically interpolate between two unit quaternions using quat_slerp with a fraction', 'integrate a unit quaternion by an angular velocity vector using integrate_quat', 'convert euler angles to a 3x3 rotation matrix with a specified axis ordering like XYZ or ZYZ', 'build a 4x4 homogeneous transformation matrix from position and quaternion using pos_quat_to_hmat', 'slerp interpolate between two quaternions at a given fraction using quat_slerp', 'transform a 6D twist or wrench between coordinate frames using velocity_transform or force_transform']
```

Usage

```
{'convert_axisangle_to_quat': 'convert an axis-angle rotation vector to a unit quaternion using axisangle_to_quat', 'multiply_quaternions': 'multiply two quaternions together using quat_mul to compose rotations', 'rotate_vector_by_quat': 'rotate a 3D position vector by a unit quaternion using quat_rotate', 'interpolate_quaternions': 'spherically interpolate between two unit quaternions using quat_slerp with a fraction', 'integrate_quaternion_with_angular_velocity': 'integrate a unit quaternion by an angular velocity vector using integrate_quat'}
```

## File: google-deepmind_dmrobotics/py/transformations/transformations_test.py

Prompts

```
['build a python module that converts XYZ euler angles to a 3x3 rotation matrix using euler_to_rmat', 'build a python module that converts a unit quaternion to a 4x4 homogeneous rotation matrix using quat_to_mat', 'build a python module that performs spherical linear interpolation between two quaternions using quat_slerp', 'build a python module that converts a 3x3 rotation matrix to ZYX euler angles using rmat_to_euler', 'build a python module that computes the active quaternion difference between source and target orientations using quat_diff_active', 'convert an axis-angle rotation vector to a unit quaternion using axisangle_to_quat', 'multiply two quaternions together using quat_mul to compose rotations', 'rotate a 3D position vector by a unit quaternion using quat_rotate', 'spherically interpolate between two unit quaternions using quat_slerp with a fraction', 'integrate a unit quaternion by an angular velocity vector using integrate_quat', 'convert euler angles to a 3x3 rotation matrix with a specified axis ordering like XYZ or ZYZ', 'build a 4x4 homogeneous transformation matrix from position and quaternion using pos_quat_to_hmat', 'slerp interpolate between two quaternions at a given fraction using quat_slerp', 'transform a 6D twist or wrench between coordinate frames using velocity_transform or force_transform']
```

Usage

```
{'convert_quaternion_to_rotation_matrix': 'convert a quaternion to a 4x4 homogeneous rotation matrix using quat_to_mat', 'convert_euler_angles_to_rotation_matrix': 'convert euler angles to a 3x3 rotation matrix with a specified axis ordering like XYZ or ZYZ', 'compute_homogeneous_transform_from_pose': 'build a 4x4 homogeneous transformation matrix from position and quaternion using pos_quat_to_hmat', 'interpolate_quaternions_with_slerp': 'slerp interpolate between two quaternions at a given fraction using quat_slerp', 'transform_velocity_or_force_between_frames': 'transform a 6D twist or wrench between coordinate frames using velocity_transform or force_transform'}
```

