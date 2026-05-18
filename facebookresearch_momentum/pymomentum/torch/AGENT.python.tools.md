# Agent Python Tools

- repo: facebookresearch/momentum
- repo_uri: https://github.com/facebookresearch/momentum

## File: facebookresearch_momentum/pymomentum/torch/character.py

Prompts

```
['build a python module to compute skeleton state from joint parameters using the Character class forward kinematics pipeline', 'build a python module to skin mesh vertices using LinearBlendSkinning with global skeleton state and rest vertex positions', 'build a python module to convert joint parameters to global TRS transforms using Skeleton joint_parameters_to_trs method', 'build a python module to compute model parameters from joint parameters using AdvancedInverseParameterTransform with known scales', 'build a python module to apply blend shape deformations to mesh vertices using BlendShape with coefficient tensors', 'build a PyTorch module to enforce parameter limits using soft constraints for character animation', 'create a function that evaluates minmax constraint violations on model parameters and returns weighted error', 'create a function that evaluates linear constraint violations between reference and target model parameters', 'create a function that evaluates ellipsoid collision constraints using skeletal state transforms', 'create a forward pass that concatenates all six limit error types into a single error tensor', 'create an SDFCollider from a pymomentum.geometry.SDFCollider instance with torch.float32 dtype', 'create an SDFCollisionGeometry from a list of pymomentum SDFCollider instances', 'evaluate SDF distances for world-space query points using a skeleton state tensor', 'evaluate the minimum SDF distance across all colliders for each query point', 'evaluate signed distance field values at query points in SDF local space']
```

Usage

```
{'build_character_forward_kinematics': 'build a python module to compute skeleton state from joint parameters using the Character class forward kinematics pipeline', 'build_skinning_mesh_vertices': 'build a python module to skin mesh vertices using LinearBlendSkinning with global skeleton state and rest vertex positions', 'build_trs_transform_conversion': 'build a python module to convert joint parameters to global TRS transforms using Skeleton joint_parameters_to_trs method', 'build_inverse_parameter_transform': 'build a python module to compute model parameters from joint parameters using AdvancedInverseParameterTransform with known scales', 'build_blendshape_deformation': 'build a python module to apply blend shape deformations to mesh vertices using BlendShape with coefficient tensors'}
```

## File: facebookresearch_momentum/pymomentum/torch/parameter_limits.py

Prompts

```
['build a python module to compute skeleton state from joint parameters using the Character class forward kinematics pipeline', 'build a python module to skin mesh vertices using LinearBlendSkinning with global skeleton state and rest vertex positions', 'build a python module to convert joint parameters to global TRS transforms using Skeleton joint_parameters_to_trs method', 'build a python module to compute model parameters from joint parameters using AdvancedInverseParameterTransform with known scales', 'build a python module to apply blend shape deformations to mesh vertices using BlendShape with coefficient tensors', 'build a PyTorch module to enforce parameter limits using soft constraints for character animation', 'create a function that evaluates minmax constraint violations on model parameters and returns weighted error', 'create a function that evaluates linear constraint violations between reference and target model parameters', 'create a function that evaluates ellipsoid collision constraints using skeletal state transforms', 'create a forward pass that concatenates all six limit error types into a single error tensor', 'create an SDFCollider from a pymomentum.geometry.SDFCollider instance with torch.float32 dtype', 'create an SDFCollisionGeometry from a list of pymomentum SDFCollider instances', 'evaluate SDF distances for world-space query points using a skeleton state tensor', 'evaluate the minimum SDF distance across all colliders for each query point', 'evaluate signed distance field values at query points in SDF local space']
```

Usage

```
{'build_parameter_limits_module': 'build a PyTorch module to enforce parameter limits using soft constraints for character animation', 'create_minmax_error_evaluation': 'create a function that evaluates minmax constraint violations on model parameters and returns weighted error', 'create_linear_error_evaluation': 'create a function that evaluates linear constraint violations between reference and target model parameters', 'create_ellipsoid_error_evaluation': 'create a function that evaluates ellipsoid collision constraints using skeletal state transforms', 'create_forward_pass': 'create a forward pass that concatenates all six limit error types into a single error tensor'}
```

## File: facebookresearch_momentum/pymomentum/torch/sdf_collision.py

Prompts

```
['build a python module to compute skeleton state from joint parameters using the Character class forward kinematics pipeline', 'build a python module to skin mesh vertices using LinearBlendSkinning with global skeleton state and rest vertex positions', 'build a python module to convert joint parameters to global TRS transforms using Skeleton joint_parameters_to_trs method', 'build a python module to compute model parameters from joint parameters using AdvancedInverseParameterTransform with known scales', 'build a python module to apply blend shape deformations to mesh vertices using BlendShape with coefficient tensors', 'build a PyTorch module to enforce parameter limits using soft constraints for character animation', 'create a function that evaluates minmax constraint violations on model parameters and returns weighted error', 'create a function that evaluates linear constraint violations between reference and target model parameters', 'create a function that evaluates ellipsoid collision constraints using skeletal state transforms', 'create a forward pass that concatenates all six limit error types into a single error tensor', 'create an SDFCollider from a pymomentum.geometry.SDFCollider instance with torch.float32 dtype', 'create an SDFCollisionGeometry from a list of pymomentum SDFCollider instances', 'evaluate SDF distances for world-space query points using a skeleton state tensor', 'evaluate the minimum SDF distance across all colliders for each query point', 'evaluate signed distance field values at query points in SDF local space']
```

Usage

```
{'create_SDFCollider_from_pymomentum': 'create an SDFCollider from a pymomentum.geometry.SDFCollider instance with torch.float32 dtype', 'create_SDFCollisionGeometry_from_pymomentum': 'create an SDFCollisionGeometry from a list of pymomentum SDFCollider instances', 'evaluate_SDFCollider': 'evaluate SDF distances for world-space query points using a skeleton state tensor', 'evaluate_SDFCollisionGeometry_min': 'evaluate the minimum SDF distance across all colliders for each query point', 'evaluate_evaluate_sdf_function': 'evaluate signed distance field values at query points in SDF local space'}
```

