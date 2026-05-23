# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/tests/theseus_tests/embodied/collision/test_collision_factor.py

Prompts

```
['test the Collision2D cost function error and jacobian output shapes for various batch sizes', 'test the Collision2D copy method to verify deep copying of pose, sdf, and weight attributes', 'test the Collision2D jacobian computation against numeric jacobian for Point2 and SE2 pose types', 'build a Collision2D cost function with pose, origin, sdf_data, cell_size, cost_eps, and cost_weight', 'review the Collision2D jacobian validation using numeric_jacobian utility with delta_mag tolerance', 'test EffectorObjectContactPlanar jacobians by comparing computed jacobians against numeric jacobian for SE2 effector and object poses', 'test EffectorObjectContactPlanar error computation by verifying output against expected error values for multiple SDF datasets', 'test EffectorObjectContactPlanar eff_radius variable type handling for Variable, tensor, and scalar inputs', 'load SDF grid data from a JSON file and return sdf_data matrix, cell size, and origin tensors', 'create SDF data matrix, cell size, and origin tensors from a CSV file for a given SDF index', 'create a SignedDistanceField2D from an occupancy map tensor with origin and resolution parameters', 'test the signed_distance method to compute distances and jacobians for 2D points on an SDF', 'test the convert_points_to_cell method to map 2D points to SDF grid row and column indices', 'test creating a batched SignedDistanceField2D from occupancy maps with obstacles and empty space', 'test transferring a SignedDistanceField2D to a CUDA device and computing signed distance on GPU', 'create a function that generates a random scalar as a Variable, tensor, or float for collision tests', 'create a function that generates a random 2D origin as a Point2 or tensor for collision tests', 'create a function that generates random signed distance field data as a Variable or tensor', 'create a function that builds a random SignedDistanceField2D using random origin, scalar, and sdf data', 'test the random_sdf function to generate SignedDistanceField2D instances with varied input types']
```

Usage

```
{'test_collision2d_error_shapes': 'test the Collision2D cost function error and jacobian output shapes for various batch sizes', 'test_collision2d_copy': 'test the Collision2D copy method to verify deep copying of pose, sdf, and weight attributes', 'test_collision2d_jacobians': 'test the Collision2D jacobian computation against numeric jacobian for Point2 and SE2 pose types', 'build_collision2d_cost_function': 'build a Collision2D cost function with pose, origin, sdf_data, cell_size, cost_eps, and cost_weight', 'review_collision2d_jacobian_validation': 'review the Collision2D jacobian validation using numeric_jacobian utility with delta_mag tolerance'}
```

## File: facebookresearch_theseus/tests/theseus_tests/embodied/collision/test_eff_obj_contact.py

Prompts

```
['test the Collision2D cost function error and jacobian output shapes for various batch sizes', 'test the Collision2D copy method to verify deep copying of pose, sdf, and weight attributes', 'test the Collision2D jacobian computation against numeric jacobian for Point2 and SE2 pose types', 'build a Collision2D cost function with pose, origin, sdf_data, cell_size, cost_eps, and cost_weight', 'review the Collision2D jacobian validation using numeric_jacobian utility with delta_mag tolerance', 'test EffectorObjectContactPlanar jacobians by comparing computed jacobians against numeric jacobian for SE2 effector and object poses', 'test EffectorObjectContactPlanar error computation by verifying output against expected error values for multiple SDF datasets', 'test EffectorObjectContactPlanar eff_radius variable type handling for Variable, tensor, and scalar inputs', 'load SDF grid data from a JSON file and return sdf_data matrix, cell size, and origin tensors', 'create SDF data matrix, cell size, and origin tensors from a CSV file for a given SDF index', 'create a SignedDistanceField2D from an occupancy map tensor with origin and resolution parameters', 'test the signed_distance method to compute distances and jacobians for 2D points on an SDF', 'test the convert_points_to_cell method to map 2D points to SDF grid row and column indices', 'test creating a batched SignedDistanceField2D from occupancy maps with obstacles and empty space', 'test transferring a SignedDistanceField2D to a CUDA device and computing signed distance on GPU', 'create a function that generates a random scalar as a Variable, tensor, or float for collision tests', 'create a function that generates a random 2D origin as a Point2 or tensor for collision tests', 'create a function that generates random signed distance field data as a Variable or tensor', 'create a function that builds a random SignedDistanceField2D using random origin, scalar, and sdf data', 'test the random_sdf function to generate SignedDistanceField2D instances with varied input types']
```

Usage

```
{'test_EffectorObjectContactPlanar_jacobians': 'test EffectorObjectContactPlanar jacobians by comparing computed jacobians against numeric jacobian for SE2 effector and object poses', 'test_EffectorObjectContactPlanar_errors': 'test EffectorObjectContactPlanar error computation by verifying output against expected error values for multiple SDF datasets', 'test_EffectorObjectContactPlanar_variable_type': 'test EffectorObjectContactPlanar eff_radius variable type handling for Variable, tensor, and scalar inputs', 'load_sdf_data_from_file': 'load SDF grid data from a JSON file and return sdf_data matrix, cell size, and origin tensors', 'create_sdf_data': 'create SDF data matrix, cell size, and origin tensors from a CSV file for a given SDF index'}
```

## File: facebookresearch_theseus/tests/theseus_tests/embodied/collision/test_signed_distance_field.py

Prompts

```
['test the Collision2D cost function error and jacobian output shapes for various batch sizes', 'test the Collision2D copy method to verify deep copying of pose, sdf, and weight attributes', 'test the Collision2D jacobian computation against numeric jacobian for Point2 and SE2 pose types', 'build a Collision2D cost function with pose, origin, sdf_data, cell_size, cost_eps, and cost_weight', 'review the Collision2D jacobian validation using numeric_jacobian utility with delta_mag tolerance', 'test EffectorObjectContactPlanar jacobians by comparing computed jacobians against numeric jacobian for SE2 effector and object poses', 'test EffectorObjectContactPlanar error computation by verifying output against expected error values for multiple SDF datasets', 'test EffectorObjectContactPlanar eff_radius variable type handling for Variable, tensor, and scalar inputs', 'load SDF grid data from a JSON file and return sdf_data matrix, cell size, and origin tensors', 'create SDF data matrix, cell size, and origin tensors from a CSV file for a given SDF index', 'create a SignedDistanceField2D from an occupancy map tensor with origin and resolution parameters', 'test the signed_distance method to compute distances and jacobians for 2D points on an SDF', 'test the convert_points_to_cell method to map 2D points to SDF grid row and column indices', 'test creating a batched SignedDistanceField2D from occupancy maps with obstacles and empty space', 'test transferring a SignedDistanceField2D to a CUDA device and computing signed distance on GPU', 'create a function that generates a random scalar as a Variable, tensor, or float for collision tests', 'create a function that generates a random 2D origin as a Point2 or tensor for collision tests', 'create a function that generates random signed distance field data as a Variable or tensor', 'create a function that builds a random SignedDistanceField2D using random origin, scalar, and sdf data', 'test the random_sdf function to generate SignedDistanceField2D instances with varied input types']
```

Usage

```
{'create_SignedDistanceField2D': 'create a SignedDistanceField2D from an occupancy map tensor with origin and resolution parameters', 'test_signed_distance': 'test the signed_distance method to compute distances and jacobians for 2D points on an SDF', 'test_convert_points_to_cell': 'test the convert_points_to_cell method to map 2D points to SDF grid row and column indices', 'test_sdf_creation_from_occupancy': 'test creating a batched SignedDistanceField2D from occupancy maps with obstacles and empty space', 'test_sdf_cuda_device_transfer': 'test transferring a SignedDistanceField2D to a CUDA device and computing signed distance on GPU'}
```

## File: facebookresearch_theseus/tests/theseus_tests/embodied/collision/utils.py

Prompts

```
['test the Collision2D cost function error and jacobian output shapes for various batch sizes', 'test the Collision2D copy method to verify deep copying of pose, sdf, and weight attributes', 'test the Collision2D jacobian computation against numeric jacobian for Point2 and SE2 pose types', 'build a Collision2D cost function with pose, origin, sdf_data, cell_size, cost_eps, and cost_weight', 'review the Collision2D jacobian validation using numeric_jacobian utility with delta_mag tolerance', 'test EffectorObjectContactPlanar jacobians by comparing computed jacobians against numeric jacobian for SE2 effector and object poses', 'test EffectorObjectContactPlanar error computation by verifying output against expected error values for multiple SDF datasets', 'test EffectorObjectContactPlanar eff_radius variable type handling for Variable, tensor, and scalar inputs', 'load SDF grid data from a JSON file and return sdf_data matrix, cell size, and origin tensors', 'create SDF data matrix, cell size, and origin tensors from a CSV file for a given SDF index', 'create a SignedDistanceField2D from an occupancy map tensor with origin and resolution parameters', 'test the signed_distance method to compute distances and jacobians for 2D points on an SDF', 'test the convert_points_to_cell method to map 2D points to SDF grid row and column indices', 'test creating a batched SignedDistanceField2D from occupancy maps with obstacles and empty space', 'test transferring a SignedDistanceField2D to a CUDA device and computing signed distance on GPU', 'create a function that generates a random scalar as a Variable, tensor, or float for collision tests', 'create a function that generates a random 2D origin as a Point2 or tensor for collision tests', 'create a function that generates random signed distance field data as a Variable or tensor', 'create a function that builds a random SignedDistanceField2D using random origin, scalar, and sdf data', 'test the random_sdf function to generate SignedDistanceField2D instances with varied input types']
```

Usage

```
{'create_random_scalar': 'create a function that generates a random scalar as a Variable, tensor, or float for collision tests', 'create_random_origin': 'create a function that generates a random 2D origin as a Point2 or tensor for collision tests', 'create_random_sdf_data': 'create a function that generates random signed distance field data as a Variable or tensor', 'create_random_sdf': 'create a function that builds a random SignedDistanceField2D using random origin, scalar, and sdf data', 'test_random_sdf': 'test the random_sdf function to generate SignedDistanceField2D instances with varied input types'}
```

