# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/manipulation/props/parametric_object/rgb_objects/parametric_rgb_object.py

Prompts

```
['create an RgbObject instance with version v1_0 to parametrically describe a 3D shape with 9 shape parameters', 'create an RgbObject instance with version v1_3 to use expanded shape parameter bounds for 3D objects', 'inspect the shape_bounds property of an RgbObject to retrieve ParametricMinMaxBounds for the 9 shape parameters', 'use the RgbVersion enum to select between v1_0 and v1_3 versions when initializing an RgbObject', 'review the RgbObject class that extends ParametricObject with shape and texture properties for RGB-object generation', 'create an RgbObject instance with a specified version like RgbVersion.v1_0 or v1_3', 'test that a shape parameter dict like cylinder cube or triangle passes check_instance validation', 'test that a shape and texture parameter dict together pass the full check_instance validation', 'test that the shape param_names tuple and texture param_names tuple match expected values', 'test that shape.get_name returns the canonical full name string for a given nickname parameters dict', 'create an RgbObjectsNames instance with version v1_0 to get the 15 predefined RGB object nicknames and parameters', 'create an RgbObjectsNames instance with version v1_3 to get the full interpolated RGB object set with 8 deformation axes', 'use parameters_interpolations to generate equally-spaced parameter samples between two ParametersDict objects', 'use parameters_numeric_combinations to create averaged combinations of ParametersDicts by alphabetic and numeric key groups', 'use parameters_equispaced_combinations to create convex combinations of ParametersDicts with specified integer percentage coefficients']
```

Usage

```
{'create_rgb_object_v1': 'create an RgbObject instance with version v1_0 to parametrically describe a 3D shape with 9 shape parameters', 'create_rgb_object_v1_3': 'create an RgbObject instance with version v1_3 to use expanded shape parameter bounds for 3D objects', 'inspect_shape_bounds': 'inspect the shape_bounds property of an RgbObject to retrieve ParametricMinMaxBounds for the 9 shape parameters', 'use_rgbversion_enum': 'use the RgbVersion enum to select between v1_0 and v1_3 versions when initializing an RgbObject', 'review_rgb_object_class': 'review the RgbObject class that extends ParametricObject with shape and texture properties for RGB-object generation'}
```

## File: google-deepmind_dmrobotics/py/manipulation/props/parametric_object/rgb_objects/parametric_rgb_object_test.py

Prompts

```
['create an RgbObject instance with version v1_0 to parametrically describe a 3D shape with 9 shape parameters', 'create an RgbObject instance with version v1_3 to use expanded shape parameter bounds for 3D objects', 'inspect the shape_bounds property of an RgbObject to retrieve ParametricMinMaxBounds for the 9 shape parameters', 'use the RgbVersion enum to select between v1_0 and v1_3 versions when initializing an RgbObject', 'review the RgbObject class that extends ParametricObject with shape and texture properties for RGB-object generation', 'create an RgbObject instance with a specified version like RgbVersion.v1_0 or v1_3', 'test that a shape parameter dict like cylinder cube or triangle passes check_instance validation', 'test that a shape and texture parameter dict together pass the full check_instance validation', 'test that the shape param_names tuple and texture param_names tuple match expected values', 'test that shape.get_name returns the canonical full name string for a given nickname parameters dict', 'create an RgbObjectsNames instance with version v1_0 to get the 15 predefined RGB object nicknames and parameters', 'create an RgbObjectsNames instance with version v1_3 to get the full interpolated RGB object set with 8 deformation axes', 'use parameters_interpolations to generate equally-spaced parameter samples between two ParametersDict objects', 'use parameters_numeric_combinations to create averaged combinations of ParametersDicts by alphabetic and numeric key groups', 'use parameters_equispaced_combinations to create convex combinations of ParametersDicts with specified integer percentage coefficients']
```

Usage

```
{'create_rgb_object': 'create an RgbObject instance with a specified version like RgbVersion.v1_0 or v1_3', 'test_rgb_shape_init_and_instances': 'test that a shape parameter dict like cylinder cube or triangle passes check_instance validation', 'test_check_instance': 'test that a shape and texture parameter dict together pass the full check_instance validation', 'test_param_names': 'test that the shape param_names tuple and texture param_names tuple match expected values', 'test_get_name_v1_0': 'test that shape.get_name returns the canonical full name string for a given nickname parameters dict'}
```

## File: google-deepmind_dmrobotics/py/manipulation/props/parametric_object/rgb_objects/rgb_object_names.py

Prompts

```
['create an RgbObject instance with version v1_0 to parametrically describe a 3D shape with 9 shape parameters', 'create an RgbObject instance with version v1_3 to use expanded shape parameter bounds for 3D objects', 'inspect the shape_bounds property of an RgbObject to retrieve ParametricMinMaxBounds for the 9 shape parameters', 'use the RgbVersion enum to select between v1_0 and v1_3 versions when initializing an RgbObject', 'review the RgbObject class that extends ParametricObject with shape and texture properties for RGB-object generation', 'create an RgbObject instance with a specified version like RgbVersion.v1_0 or v1_3', 'test that a shape parameter dict like cylinder cube or triangle passes check_instance validation', 'test that a shape and texture parameter dict together pass the full check_instance validation', 'test that the shape param_names tuple and texture param_names tuple match expected values', 'test that shape.get_name returns the canonical full name string for a given nickname parameters dict', 'create an RgbObjectsNames instance with version v1_0 to get the 15 predefined RGB object nicknames and parameters', 'create an RgbObjectsNames instance with version v1_3 to get the full interpolated RGB object set with 8 deformation axes', 'use parameters_interpolations to generate equally-spaced parameter samples between two ParametersDict objects', 'use parameters_numeric_combinations to create averaged combinations of ParametersDicts by alphabetic and numeric key groups', 'use parameters_equispaced_combinations to create convex combinations of ParametersDicts with specified integer percentage coefficients']
```

Usage

```
{'create_rgb_objects_v1_0': 'create an RgbObjectsNames instance with version v1_0 to get the 15 predefined RGB object nicknames and parameters', 'create_rgb_objects_v1_3': 'create an RgbObjectsNames instance with version v1_3 to get the full interpolated RGB object set with 8 deformation axes', 'interpolate_parameters': 'use parameters_interpolations to generate equally-spaced parameter samples between two ParametersDict objects', 'combine_parameters_numeric': 'use parameters_numeric_combinations to create averaged combinations of ParametersDicts by alphabetic and numeric key groups', 'combine_parameters_equispaced': 'use parameters_equispaced_combinations to create convex combinations of ParametersDicts with specified integer percentage coefficients'}
```

