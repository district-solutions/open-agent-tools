# Agent Python Tools

- repo: facebookresearch/fairmotion
- repo_uri: https://github.com/facebookresearch/fairmotion

## File: facebookresearch_fairmotion/fairmotion/ops/conversions.py

Prompts

```
['convert an axis-angle vector to a 3x3 rotation matrix using A2R', 'convert a 3x3 rotation matrix to a quaternion using R2Q', 'convert euler angles to a rotation matrix using E2R with xyz order', 'build a 4x4 transformation matrix from rotation and position using Rp2T', 'normalize an axis-angle vector to use angles between 0 and pi using A2A', 'normalize a vector by dividing it by its norm using the normalize function', 'spherically interpolate between two rotation matrices with the slerp function and a t parameter', 'linearly interpolate between two values or vectors using the lerp function with a t parameter', 'compute the inverse of a 4x4 transformation matrix using the invertT function', 'compute a rotation matrix that aligns one vector to another using the R_from_vectors function', 'blend two motion poses together using slerp and lerp interpolation with a configurable alpha weight', 'stitch two motion sequences together with pivot alignment and overlapping blend for smooth transitions', 'append a second motion sequence to a first one with optional pivot alignment and blending', 'apply a 4x4 transformation matrix to all poses in a motion sequence with an optional pivot frame', 'cut a motion sequence to return only poses within a specified frame start and end range', 'normalize a quaternion array by dividing each quaternion by its norm', 'change the order of a quaternion between xyzw and wxyz formats', 'negate a quaternion if its w component is less than zero', 'multiply two quaternions together using scipy Rotation and return the result', 'compute the optimal in-place orientation closest to a target along a geodesic axis']
```

Usage

```
{'convert_axis_angle_to_rotation_matrix': 'convert an axis-angle vector to a 3x3 rotation matrix using A2R', 'convert_rotation_matrix_to_quaternion': 'convert a 3x3 rotation matrix to a quaternion using R2Q', 'convert_euler_angles_to_rotation_matrix': 'convert euler angles to a rotation matrix using E2R with xyz order', 'build_transformation_matrix_from_rotation_and_position': 'build a 4x4 transformation matrix from rotation and position using Rp2T', 'normalize_axis_angle_representation': 'normalize an axis-angle vector to use angles between 0 and pi using A2A'}
```

## File: facebookresearch_fairmotion/fairmotion/ops/math.py

Prompts

```
['convert an axis-angle vector to a 3x3 rotation matrix using A2R', 'convert a 3x3 rotation matrix to a quaternion using R2Q', 'convert euler angles to a rotation matrix using E2R with xyz order', 'build a 4x4 transformation matrix from rotation and position using Rp2T', 'normalize an axis-angle vector to use angles between 0 and pi using A2A', 'normalize a vector by dividing it by its norm using the normalize function', 'spherically interpolate between two rotation matrices with the slerp function and a t parameter', 'linearly interpolate between two values or vectors using the lerp function with a t parameter', 'compute the inverse of a 4x4 transformation matrix using the invertT function', 'compute a rotation matrix that aligns one vector to another using the R_from_vectors function', 'blend two motion poses together using slerp and lerp interpolation with a configurable alpha weight', 'stitch two motion sequences together with pivot alignment and overlapping blend for smooth transitions', 'append a second motion sequence to a first one with optional pivot alignment and blending', 'apply a 4x4 transformation matrix to all poses in a motion sequence with an optional pivot frame', 'cut a motion sequence to return only poses within a specified frame start and end range', 'normalize a quaternion array by dividing each quaternion by its norm', 'change the order of a quaternion between xyzw and wxyz formats', 'negate a quaternion if its w component is less than zero', 'multiply two quaternions together using scipy Rotation and return the result', 'compute the optimal in-place orientation closest to a target along a geodesic axis']
```

Usage

```
{'normalize_vector': 'normalize a vector by dividing it by its norm using the normalize function', 'slerp_rotations': 'spherically interpolate between two rotation matrices with the slerp function and a t parameter', 'lerp_values': 'linearly interpolate between two values or vectors using the lerp function with a t parameter', 'invert_transform': 'compute the inverse of a 4x4 transformation matrix using the invertT function', 'R_from_vectors': 'compute a rotation matrix that aligns one vector to another using the R_from_vectors function'}
```

## File: facebookresearch_fairmotion/fairmotion/ops/motion.py

Prompts

```
['convert an axis-angle vector to a 3x3 rotation matrix using A2R', 'convert a 3x3 rotation matrix to a quaternion using R2Q', 'convert euler angles to a rotation matrix using E2R with xyz order', 'build a 4x4 transformation matrix from rotation and position using Rp2T', 'normalize an axis-angle vector to use angles between 0 and pi using A2A', 'normalize a vector by dividing it by its norm using the normalize function', 'spherically interpolate between two rotation matrices with the slerp function and a t parameter', 'linearly interpolate between two values or vectors using the lerp function with a t parameter', 'compute the inverse of a 4x4 transformation matrix using the invertT function', 'compute a rotation matrix that aligns one vector to another using the R_from_vectors function', 'blend two motion poses together using slerp and lerp interpolation with a configurable alpha weight', 'stitch two motion sequences together with pivot alignment and overlapping blend for smooth transitions', 'append a second motion sequence to a first one with optional pivot alignment and blending', 'apply a 4x4 transformation matrix to all poses in a motion sequence with an optional pivot frame', 'cut a motion sequence to return only poses within a specified frame start and end range', 'normalize a quaternion array by dividing each quaternion by its norm', 'change the order of a quaternion between xyzw and wxyz formats', 'negate a quaternion if its w component is less than zero', 'multiply two quaternions together using scipy Rotation and return the result', 'compute the optimal in-place orientation closest to a target along a geodesic axis']
```

Usage

```
{'blend_two_poses': 'blend two motion poses together using slerp and lerp interpolation with a configurable alpha weight', 'stitch_two_motions': 'stitch two motion sequences together with pivot alignment and overlapping blend for smooth transitions', 'append_motion_sequences': 'append a second motion sequence to a first one with optional pivot alignment and blending', 'transform_motion': 'apply a 4x4 transformation matrix to all poses in a motion sequence with an optional pivot frame', 'cut_motion_range': 'cut a motion sequence to return only poses within a specified frame start and end range'}
```

## File: facebookresearch_fairmotion/fairmotion/ops/quaternion.py

Prompts

```
['convert an axis-angle vector to a 3x3 rotation matrix using A2R', 'convert a 3x3 rotation matrix to a quaternion using R2Q', 'convert euler angles to a rotation matrix using E2R with xyz order', 'build a 4x4 transformation matrix from rotation and position using Rp2T', 'normalize an axis-angle vector to use angles between 0 and pi using A2A', 'normalize a vector by dividing it by its norm using the normalize function', 'spherically interpolate between two rotation matrices with the slerp function and a t parameter', 'linearly interpolate between two values or vectors using the lerp function with a t parameter', 'compute the inverse of a 4x4 transformation matrix using the invertT function', 'compute a rotation matrix that aligns one vector to another using the R_from_vectors function', 'blend two motion poses together using slerp and lerp interpolation with a configurable alpha weight', 'stitch two motion sequences together with pivot alignment and overlapping blend for smooth transitions', 'append a second motion sequence to a first one with optional pivot alignment and blending', 'apply a 4x4 transformation matrix to all poses in a motion sequence with an optional pivot frame', 'cut a motion sequence to return only poses within a specified frame start and end range', 'normalize a quaternion array by dividing each quaternion by its norm', 'change the order of a quaternion between xyzw and wxyz formats', 'negate a quaternion if its w component is less than zero', 'multiply two quaternions together using scipy Rotation and return the result', 'compute the optimal in-place orientation closest to a target along a geodesic axis']
```

Usage

```
{'normalize_quaternion': 'normalize a quaternion array by dividing each quaternion by its norm', 'change_quaternion_order': 'change the order of a quaternion between xyzw and wxyz formats', 'halfspace_quaternion': 'negate a quaternion if its w component is less than zero', 'multiply_quaternions': 'multiply two quaternions together using scipy Rotation and return the result', 'find_closest_orientation': 'compute the optimal in-place orientation closest to a target along a geodesic axis'}
```

