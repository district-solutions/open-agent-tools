# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/transformations/jax_transformations/transformations.py

Prompts

```
['convert an axis-angle vector to a 3x3 rotation matrix using axisangle_to_rmat', 'convert a 3x3 rotation matrix to an axis-angle vector using rmat_to_axisangle', 'multiply two quaternions using quat_mul to compose rotations via the Hamiltonian product', 'convert a position and quaternion to a 4x4 homogeneous transform using pos_quat_to_hmat', 'extract the 6D exponential coordinates twist from a homogeneous transform using hmat_to_twist', 'test quat_rotate to rotate a 3D vector by a quaternion using JAX transformations', 'test pos_quat_mul to compose two position-quaternion poses using JAX transformations', 'test quat_to_mat to convert a quaternion to a 3x3 rotation matrix using JAX', 'test pos_quat_to_hmat to build a 4x4 homogeneous transformation matrix from position and quaternion', 'test velocity_transform to transform a 6D twist vector by a homogeneous transformation matrix']
```

Usage

```
{'convert_axisangle_to_rotation_matrix': 'convert an axis-angle vector to a 3x3 rotation matrix using axisangle_to_rmat', 'convert_rotation_matrix_to_axisangle': 'convert a 3x3 rotation matrix to an axis-angle vector using rmat_to_axisangle', 'multiply_quaternions': 'multiply two quaternions using quat_mul to compose rotations via the Hamiltonian product', 'convert_quaternion_to_homogeneous_matrix': 'convert a position and quaternion to a 4x4 homogeneous transform using pos_quat_to_hmat', 'convert_homogeneous_to_twist': 'extract the 6D exponential coordinates twist from a homogeneous transform using hmat_to_twist'}
```

## File: google-deepmind_dmrobotics/py/transformations/jax_transformations/transformations_test.py

Prompts

```
['convert an axis-angle vector to a 3x3 rotation matrix using axisangle_to_rmat', 'convert a 3x3 rotation matrix to an axis-angle vector using rmat_to_axisangle', 'multiply two quaternions using quat_mul to compose rotations via the Hamiltonian product', 'convert a position and quaternion to a 4x4 homogeneous transform using pos_quat_to_hmat', 'extract the 6D exponential coordinates twist from a homogeneous transform using hmat_to_twist', 'test quat_rotate to rotate a 3D vector by a quaternion using JAX transformations', 'test pos_quat_mul to compose two position-quaternion poses using JAX transformations', 'test quat_to_mat to convert a quaternion to a 3x3 rotation matrix using JAX', 'test pos_quat_to_hmat to build a 4x4 homogeneous transformation matrix from position and quaternion', 'test velocity_transform to transform a 6D twist vector by a homogeneous transformation matrix']
```

Usage

```
{'test_quat_rotate': 'test quat_rotate to rotate a 3D vector by a quaternion using JAX transformations', 'test_pos_quat_mul': 'test pos_quat_mul to compose two position-quaternion poses using JAX transformations', 'test_quat_to_mat': 'test quat_to_mat to convert a quaternion to a 3x3 rotation matrix using JAX', 'test_pos_quat_to_hmat': 'test pos_quat_to_hmat to build a 4x4 homogeneous transformation matrix from position and quaternion', 'test_velocity_transform': 'test velocity_transform to transform a 6D twist vector by a homogeneous transformation matrix'}
```

