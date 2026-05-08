# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/torchcontrol/transform/rotation.py

Prompts

```
['create a RotationObj from a quaternion tensor using from_quat function', 'create a RotationObj from a 3x3 rotation matrix tensor using from_matrix function', 'create a RotationObj from a rotation vector tensor using from_rotvec function', 'create an identity RotationObj representing zero rotation using the identity function', 'compose two RotationObj instances using the multiply operator to stack rotations', 'create a TransformationObj from a RotationObj and translation vector using from_rot_xyz', 'create a TransformationObj from a 4x4 transformation matrix using from_matrix', 'create an identity TransformationObj with zero rotation and zero translation using identity', 'apply a TransformationObj to a 3D vector using the apply method', 'invert a TransformationObj to get its inverse using the inv method']
```

Usage

```
{'create_rotation_from_quaternion': 'create a RotationObj from a quaternion tensor using from_quat function', 'create_rotation_from_matrix': 'create a RotationObj from a 3x3 rotation matrix tensor using from_matrix function', 'create_rotation_from_rotvec': 'create a RotationObj from a rotation vector tensor using from_rotvec function', 'create_identity_rotation': 'create an identity RotationObj representing zero rotation using the identity function', 'compose_rotations': 'compose two RotationObj instances using the multiply operator to stack rotations'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/torchcontrol/transform/transformation.py

Prompts

```
['create a RotationObj from a quaternion tensor using from_quat function', 'create a RotationObj from a 3x3 rotation matrix tensor using from_matrix function', 'create a RotationObj from a rotation vector tensor using from_rotvec function', 'create an identity RotationObj representing zero rotation using the identity function', 'compose two RotationObj instances using the multiply operator to stack rotations', 'create a TransformationObj from a RotationObj and translation vector using from_rot_xyz', 'create a TransformationObj from a 4x4 transformation matrix using from_matrix', 'create an identity TransformationObj with zero rotation and zero translation using identity', 'apply a TransformationObj to a 3D vector using the apply method', 'invert a TransformationObj to get its inverse using the inv method']
```

Usage

```
{'create_transformation_from_rotation_translation': 'create a TransformationObj from a RotationObj and translation vector using from_rot_xyz', 'create_transformation_from_matrix': 'create a TransformationObj from a 4x4 transformation matrix using from_matrix', 'create_identity_transformation': 'create an identity TransformationObj with zero rotation and zero translation using identity', 'apply_transformation_to_vector': 'apply a TransformationObj to a 3D vector using the apply method', 'invert_transformation': 'invert a TransformationObj to get its inverse using the inv method'}
```

