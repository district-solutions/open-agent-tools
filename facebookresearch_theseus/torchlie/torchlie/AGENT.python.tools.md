# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/torchlie/torchlie/global_params.py

Prompts

```
['set torchlie global parameters like so3_near_pi_eps_float32 using a dictionary of key-value options', 'reset all torchlie global parameters back to their default epsilon values', 'get an epsilon value for a given Lie group type, attribute, and torch dtype', 'review the TorchLieGlobalParams dataclass and its SO3/SE3 epsilon configuration for float32 and float64', 'test the CHECK_DTYPE_SUPPORTED function to validate that only float32 and float64 dtypes are accepted', 'create a LieTensor from SE3 group elements using SE3.rand or SE3.identity for random or identity transforms', 'compose two LieTensor transforms together using the compose method or multiply operator to chain group operations', 'transform 3D points using a LieTensor group element via the transform method or matmul operator', 'retract a LieTensor by a tangent space delta using the retract method to update group elements', 'compute Jacobians of LieTensor operations like jcompose, jtransform, or jlog for differentiable geometry', 'create a LieTensor by calling SE3.exp on a tangent vector tensor', 'create a LieTensor and its jacobians by calling SE3.jexp on a tangent vector', 'convert a tangent vector to its matrix representation using SE3.hat', 'convert a matrix back to its tangent vector using SE3.vee', 'lift a matrix to Lie group representation or project it back using SE3.lift and SE3.project']
```

Usage

```
{'set_global_params': 'set torchlie global parameters like so3_near_pi_eps_float32 using a dictionary of key-value options', 'reset_global_params': 'reset all torchlie global parameters back to their default epsilon values', 'get_eps': 'get an epsilon value for a given Lie group type, attribute, and torch dtype', 'review_TorchLieGlobalParams': 'review the TorchLieGlobalParams dataclass and its SO3/SE3 epsilon configuration for float32 and float64', 'test_CHECK_DTYPE_SUPPORTED': 'test the CHECK_DTYPE_SUPPORTED function to validate that only float32 and float64 dtypes are accepted'}
```

## File: facebookresearch_theseus/torchlie/torchlie/lie_tensor.py

Prompts

```
['set torchlie global parameters like so3_near_pi_eps_float32 using a dictionary of key-value options', 'reset all torchlie global parameters back to their default epsilon values', 'get an epsilon value for a given Lie group type, attribute, and torch dtype', 'review the TorchLieGlobalParams dataclass and its SO3/SE3 epsilon configuration for float32 and float64', 'test the CHECK_DTYPE_SUPPORTED function to validate that only float32 and float64 dtypes are accepted', 'create a LieTensor from SE3 group elements using SE3.rand or SE3.identity for random or identity transforms', 'compose two LieTensor transforms together using the compose method or multiply operator to chain group operations', 'transform 3D points using a LieTensor group element via the transform method or matmul operator', 'retract a LieTensor by a tangent space delta using the retract method to update group elements', 'compute Jacobians of LieTensor operations like jcompose, jtransform, or jlog for differentiable geometry', 'create a LieTensor by calling SE3.exp on a tangent vector tensor', 'create a LieTensor and its jacobians by calling SE3.jexp on a tangent vector', 'convert a tangent vector to its matrix representation using SE3.hat', 'convert a matrix back to its tangent vector using SE3.vee', 'lift a matrix to Lie group representation or project it back using SE3.lift and SE3.project']
```

Usage

```
{'create_LieTensor_from_SE3': 'create a LieTensor from SE3 group elements using SE3.rand or SE3.identity for random or identity transforms', 'compose_LieTensor_transforms': 'compose two LieTensor transforms together using the compose method or multiply operator to chain group operations', 'transform_points_with_LieTensor': 'transform 3D points using a LieTensor group element via the transform method or matmul operator', 'retract_LieTensor_with_delta': 'retract a LieTensor by a tangent space delta using the retract method to update group elements', 'compute_jacobian_of_LieTensor_ops': 'compute Jacobians of LieTensor operations like jcompose, jtransform, or jlog for differentiable geometry'}
```

## File: facebookresearch_theseus/torchlie/torchlie/types.py

Prompts

```
['set torchlie global parameters like so3_near_pi_eps_float32 using a dictionary of key-value options', 'reset all torchlie global parameters back to their default epsilon values', 'get an epsilon value for a given Lie group type, attribute, and torch dtype', 'review the TorchLieGlobalParams dataclass and its SO3/SE3 epsilon configuration for float32 and float64', 'test the CHECK_DTYPE_SUPPORTED function to validate that only float32 and float64 dtypes are accepted', 'create a LieTensor from SE3 group elements using SE3.rand or SE3.identity for random or identity transforms', 'compose two LieTensor transforms together using the compose method or multiply operator to chain group operations', 'transform 3D points using a LieTensor group element via the transform method or matmul operator', 'retract a LieTensor by a tangent space delta using the retract method to update group elements', 'compute Jacobians of LieTensor operations like jcompose, jtransform, or jlog for differentiable geometry', 'create a LieTensor by calling SE3.exp on a tangent vector tensor', 'create a LieTensor and its jacobians by calling SE3.jexp on a tangent vector', 'convert a tangent vector to its matrix representation using SE3.hat', 'convert a matrix back to its tangent vector using SE3.vee', 'lift a matrix to Lie group representation or project it back using SE3.lift and SE3.project']
```

Usage

```
{'create_lie_tensor_exp': 'create a LieTensor by calling SE3.exp on a tangent vector tensor', 'create_lie_tensor_jexp': 'create a LieTensor and its jacobians by calling SE3.jexp on a tangent vector', 'convert_hat': 'convert a tangent vector to its matrix representation using SE3.hat', 'convert_vee': 'convert a matrix back to its tangent vector using SE3.vee', 'lift_and_project': 'lift a matrix to Lie group representation or project it back using SE3.lift and SE3.project'}
```

