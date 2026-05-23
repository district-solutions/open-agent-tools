# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/theseus/embodied/collision/collision.py

Prompts

```
['create a Collision2D cost function with a Point2 or SE2 pose and signed distance field parameters', 'compute signed distances and jacobians for robot states against a 2D signed distance field', 'compute the collision error by clamping the difference between cost epsilon and signed distances', 'compute jacobians for collision cost function with zeroed values for faraway robot states', 'update an auxiliary variable in the Collision2D cost function and refresh the SDF container data', 'create an EffectorObjectContactPlanar cost function for planar effector-object collision using SDF data and SE2 poses', 'compute the collision error tensor for an EffectorObjectContactPlanar instance using its error method', 'compute Jacobians for object and effector poses from an EffectorObjectContactPlanar cost function', 'create a deep copy of an EffectorObjectContactPlanar instance with an optional new name', 'update an auxiliary variable on an EffectorObjectContactPlanar and refresh its internal SDF container', 'create a SignedDistanceField2D instance with origin, cell_size, and precomputed sdf_data tensors', 'create a SignedDistanceField2D instance from an occupancy map using distance transform computation', 'compute the signed distance and jacobian for points using bilinear interpolation on the SDF grid', 'convert world-space points to SDF grid row and column coordinates with bounds checking', 'update the origin, cell_size, and sdf_data of an existing SignedDistanceField2D instance']
```

Usage

```
{'create_Collision2D_instance': 'create a Collision2D cost function with a Point2 or SE2 pose and signed distance field parameters', 'compute_distances_and_jacobians': 'compute signed distances and jacobians for robot states against a 2D signed distance field', 'compute_collision_error': 'compute the collision error by clamping the difference between cost epsilon and signed distances', 'compute_collision_jacobians': 'compute jacobians for collision cost function with zeroed values for faraway robot states', 'update_auxiliary_variable': 'update an auxiliary variable in the Collision2D cost function and refresh the SDF container data'}
```

## File: facebookresearch_theseus/theseus/embodied/collision/eff_obj_contact.py

Prompts

```
['create a Collision2D cost function with a Point2 or SE2 pose and signed distance field parameters', 'compute signed distances and jacobians for robot states against a 2D signed distance field', 'compute the collision error by clamping the difference between cost epsilon and signed distances', 'compute jacobians for collision cost function with zeroed values for faraway robot states', 'update an auxiliary variable in the Collision2D cost function and refresh the SDF container data', 'create an EffectorObjectContactPlanar cost function for planar effector-object collision using SDF data and SE2 poses', 'compute the collision error tensor for an EffectorObjectContactPlanar instance using its error method', 'compute Jacobians for object and effector poses from an EffectorObjectContactPlanar cost function', 'create a deep copy of an EffectorObjectContactPlanar instance with an optional new name', 'update an auxiliary variable on an EffectorObjectContactPlanar and refresh its internal SDF container', 'create a SignedDistanceField2D instance with origin, cell_size, and precomputed sdf_data tensors', 'create a SignedDistanceField2D instance from an occupancy map using distance transform computation', 'compute the signed distance and jacobian for points using bilinear interpolation on the SDF grid', 'convert world-space points to SDF grid row and column coordinates with bounds checking', 'update the origin, cell_size, and sdf_data of an existing SignedDistanceField2D instance']
```

Usage

```
{'create_EffectorObjectContactPlanar': 'create an EffectorObjectContactPlanar cost function for planar effector-object collision using SDF data and SE2 poses', 'compute_error_EffectorObjectContactPlanar': 'compute the collision error tensor for an EffectorObjectContactPlanar instance using its error method', 'compute_jacobians_EffectorObjectContactPlanar': 'compute Jacobians for object and effector poses from an EffectorObjectContactPlanar cost function', 'copy_EffectorObjectContactPlanar': 'create a deep copy of an EffectorObjectContactPlanar instance with an optional new name', 'update_aux_var_EffectorObjectContactPlanar': 'update an auxiliary variable on an EffectorObjectContactPlanar and refresh its internal SDF container'}
```

## File: facebookresearch_theseus/theseus/embodied/collision/signed_distance_field.py

Prompts

```
['create a Collision2D cost function with a Point2 or SE2 pose and signed distance field parameters', 'compute signed distances and jacobians for robot states against a 2D signed distance field', 'compute the collision error by clamping the difference between cost epsilon and signed distances', 'compute jacobians for collision cost function with zeroed values for faraway robot states', 'update an auxiliary variable in the Collision2D cost function and refresh the SDF container data', 'create an EffectorObjectContactPlanar cost function for planar effector-object collision using SDF data and SE2 poses', 'compute the collision error tensor for an EffectorObjectContactPlanar instance using its error method', 'compute Jacobians for object and effector poses from an EffectorObjectContactPlanar cost function', 'create a deep copy of an EffectorObjectContactPlanar instance with an optional new name', 'update an auxiliary variable on an EffectorObjectContactPlanar and refresh its internal SDF container', 'create a SignedDistanceField2D instance with origin, cell_size, and precomputed sdf_data tensors', 'create a SignedDistanceField2D instance from an occupancy map using distance transform computation', 'compute the signed distance and jacobian for points using bilinear interpolation on the SDF grid', 'convert world-space points to SDF grid row and column coordinates with bounds checking', 'update the origin, cell_size, and sdf_data of an existing SignedDistanceField2D instance']
```

Usage

```
{'create_SignedDistanceField2D_from_sdf_data': 'create a SignedDistanceField2D instance with origin, cell_size, and precomputed sdf_data tensors', 'create_SignedDistanceField2D_from_occupancy_map': 'create a SignedDistanceField2D instance from an occupancy map using distance transform computation', 'compute_signed_distance': 'compute the signed distance and jacobian for points using bilinear interpolation on the SDF grid', 'convert_points_to_cell': 'convert world-space points to SDF grid row and column coordinates with bounds checking', 'update_SDF_data': 'update the origin, cell_size, and sdf_data of an existing SignedDistanceField2D instance'}
```

