# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/theseus/embodied/measurements/between.py

Prompts

```
['create a Between cost function with two LieGroup variables and a measurement', 'compute the error tensor for a Between cost function using the between operation', 'compute the Jacobian matrices for a Between cost function with respect to its variables', 'get the dimension of a Between cost function using its degrees of freedom', 'copy a Between cost function with all its variables and weight to a new instance', 'create a MovingFrameBetween cost function with two frames, two poses, a measurement, and cost weight', 'compute the error tensor for a MovingFrameBetween cost function using between and local operations', 'compute Jacobians for all four optimizable variables in a MovingFrameBetween cost function', 'get the dimension of a MovingFrameBetween cost function by returning the frame degrees of freedom', 'copy a MovingFrameBetween cost function with all frames, poses, measurement, and weight cloned', 'create a Reprojection cost function with camera pose, world point, image feature, and focal length', 'build a Reprojection cost function with radial distortion coefficients calib_k1 and calib_k2', 'test the Reprojection error method to compute projection error between predicted and observed points', 'review the Reprojection jacobians method that computes derivatives w.r.t. camera pose and world point', 'summarize the Reprojection _copy_impl method that creates a deep copy of the cost function']
```

Usage

```
{'create_between_cost_function': 'create a Between cost function with two LieGroup variables and a measurement', 'compute_between_error': 'compute the error tensor for a Between cost function using the between operation', 'compute_between_jacobians': 'compute the Jacobian matrices for a Between cost function with respect to its variables', 'get_between_dimension': 'get the dimension of a Between cost function using its degrees of freedom', 'copy_between_cost_function': 'copy a Between cost function with all its variables and weight to a new instance'}
```

## File: facebookresearch_theseus/theseus/embodied/measurements/moving_frame_between.py

Prompts

```
['create a Between cost function with two LieGroup variables and a measurement', 'compute the error tensor for a Between cost function using the between operation', 'compute the Jacobian matrices for a Between cost function with respect to its variables', 'get the dimension of a Between cost function using its degrees of freedom', 'copy a Between cost function with all its variables and weight to a new instance', 'create a MovingFrameBetween cost function with two frames, two poses, a measurement, and cost weight', 'compute the error tensor for a MovingFrameBetween cost function using between and local operations', 'compute Jacobians for all four optimizable variables in a MovingFrameBetween cost function', 'get the dimension of a MovingFrameBetween cost function by returning the frame degrees of freedom', 'copy a MovingFrameBetween cost function with all frames, poses, measurement, and weight cloned', 'create a Reprojection cost function with camera pose, world point, image feature, and focal length', 'build a Reprojection cost function with radial distortion coefficients calib_k1 and calib_k2', 'test the Reprojection error method to compute projection error between predicted and observed points', 'review the Reprojection jacobians method that computes derivatives w.r.t. camera pose and world point', 'summarize the Reprojection _copy_impl method that creates a deep copy of the cost function']
```

Usage

```
{'create_MovingFrameBetween': 'create a MovingFrameBetween cost function with two frames, two poses, a measurement, and cost weight', 'compute_error_MovingFrameBetween': 'compute the error tensor for a MovingFrameBetween cost function using between and local operations', 'compute_jacobians_MovingFrameBetween': 'compute Jacobians for all four optimizable variables in a MovingFrameBetween cost function', 'get_dim_MovingFrameBetween': 'get the dimension of a MovingFrameBetween cost function by returning the frame degrees of freedom', 'copy_MovingFrameBetween': 'copy a MovingFrameBetween cost function with all frames, poses, measurement, and weight cloned'}
```

## File: facebookresearch_theseus/theseus/embodied/measurements/reprojection.py

Prompts

```
['create a Between cost function with two LieGroup variables and a measurement', 'compute the error tensor for a Between cost function using the between operation', 'compute the Jacobian matrices for a Between cost function with respect to its variables', 'get the dimension of a Between cost function using its degrees of freedom', 'copy a Between cost function with all its variables and weight to a new instance', 'create a MovingFrameBetween cost function with two frames, two poses, a measurement, and cost weight', 'compute the error tensor for a MovingFrameBetween cost function using between and local operations', 'compute Jacobians for all four optimizable variables in a MovingFrameBetween cost function', 'get the dimension of a MovingFrameBetween cost function by returning the frame degrees of freedom', 'copy a MovingFrameBetween cost function with all frames, poses, measurement, and weight cloned', 'create a Reprojection cost function with camera pose, world point, image feature, and focal length', 'build a Reprojection cost function with radial distortion coefficients calib_k1 and calib_k2', 'test the Reprojection error method to compute projection error between predicted and observed points', 'review the Reprojection jacobians method that computes derivatives w.r.t. camera pose and world point', 'summarize the Reprojection _copy_impl method that creates a deep copy of the cost function']
```

Usage

```
{'create_Reprojection_cost_function': 'create a Reprojection cost function with camera pose, world point, image feature, and focal length', 'build_Reprojection_with_distortion': 'build a Reprojection cost function with radial distortion coefficients calib_k1 and calib_k2', 'test_Reprojection_error': 'test the Reprojection error method to compute projection error between predicted and observed points', 'review_Reprojection_jacobians': 'review the Reprojection jacobians method that computes derivatives w.r.t. camera pose and world point', 'summarize_Reprojection_copy': 'summarize the Reprojection _copy_impl method that creates a deep copy of the cost function'}
```

