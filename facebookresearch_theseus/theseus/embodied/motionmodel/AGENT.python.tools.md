# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/theseus/embodied/motionmodel/double_integrator.py

Prompts

```
['create a DoubleIntegrator cost function with pose and velocity variables for motion optimization', 'compute the error tensor from pose and velocity differences using DoubleIntegrator', 'compute jacobians for pose and velocity variables in a DoubleIntegrator cost function', 'create a GPCostWeight with inverse covariance matrix and time step for Gaussian process weighting', 'create a GPMotionModel cost function using GPCostWeight for Gaussian process motion optimization', 'create a HingeCost cost function with vector limits and threshold for optimization', 'create a Nonholonomic cost function to enforce nonholonomic constraints on pose and velocity', 'test the HingeCost error computation for vectors outside down and up limits', 'test the Nonholonomic jacobian computation for SE2 and Vector pose types', 'review the HingeCost and Nonholonomic cost function classes for motion model constraints', 'create a QuasiStaticPushingPlanar cost function with SE2 object and end effector poses plus c_square parameter', 'compute the 3x3 contact matrix D from a contact point and end effector jacobian using _compute_D', 'compute the object velocity vector V from consecutive object poses and rotation angle using _compute_V', 'compute the contact point velocity vector Vp from end effector poses and rotation using _compute_Vp', 'get the 3-D error tensor and jacobians for all optimization variables using error or jacobians methods']
```

Usage

```
{'create_double_integrator': 'create a DoubleIntegrator cost function with pose and velocity variables for motion optimization', 'compute_double_integrator_error': 'compute the error tensor from pose and velocity differences using DoubleIntegrator', 'compute_double_integrator_jacobians': 'compute jacobians for pose and velocity variables in a DoubleIntegrator cost function', 'create_gp_cost_weight': 'create a GPCostWeight with inverse covariance matrix and time step for Gaussian process weighting', 'create_gp_motion_model': 'create a GPMotionModel cost function using GPCostWeight for Gaussian process motion optimization'}
```

## File: facebookresearch_theseus/theseus/embodied/motionmodel/misc.py

Prompts

```
['create a DoubleIntegrator cost function with pose and velocity variables for motion optimization', 'compute the error tensor from pose and velocity differences using DoubleIntegrator', 'compute jacobians for pose and velocity variables in a DoubleIntegrator cost function', 'create a GPCostWeight with inverse covariance matrix and time step for Gaussian process weighting', 'create a GPMotionModel cost function using GPCostWeight for Gaussian process motion optimization', 'create a HingeCost cost function with vector limits and threshold for optimization', 'create a Nonholonomic cost function to enforce nonholonomic constraints on pose and velocity', 'test the HingeCost error computation for vectors outside down and up limits', 'test the Nonholonomic jacobian computation for SE2 and Vector pose types', 'review the HingeCost and Nonholonomic cost function classes for motion model constraints', 'create a QuasiStaticPushingPlanar cost function with SE2 object and end effector poses plus c_square parameter', 'compute the 3x3 contact matrix D from a contact point and end effector jacobian using _compute_D', 'compute the object velocity vector V from consecutive object poses and rotation angle using _compute_V', 'compute the contact point velocity vector Vp from end effector poses and rotation using _compute_Vp', 'get the 3-D error tensor and jacobians for all optimization variables using error or jacobians methods']
```

Usage

```
{'create_HingeCost': 'create a HingeCost cost function with vector limits and threshold for optimization', 'create_Nonholonomic': 'create a Nonholonomic cost function to enforce nonholonomic constraints on pose and velocity', 'test_HingeCost_error': 'test the HingeCost error computation for vectors outside down and up limits', 'test_Nonholonomic_jacobians': 'test the Nonholonomic jacobian computation for SE2 and Vector pose types', 'review_HingeCost_Nonholonomic': 'review the HingeCost and Nonholonomic cost function classes for motion model constraints'}
```

## File: facebookresearch_theseus/theseus/embodied/motionmodel/quasi_static_pushing_planar.py

Prompts

```
['create a DoubleIntegrator cost function with pose and velocity variables for motion optimization', 'compute the error tensor from pose and velocity differences using DoubleIntegrator', 'compute jacobians for pose and velocity variables in a DoubleIntegrator cost function', 'create a GPCostWeight with inverse covariance matrix and time step for Gaussian process weighting', 'create a GPMotionModel cost function using GPCostWeight for Gaussian process motion optimization', 'create a HingeCost cost function with vector limits and threshold for optimization', 'create a Nonholonomic cost function to enforce nonholonomic constraints on pose and velocity', 'test the HingeCost error computation for vectors outside down and up limits', 'test the Nonholonomic jacobian computation for SE2 and Vector pose types', 'review the HingeCost and Nonholonomic cost function classes for motion model constraints', 'create a QuasiStaticPushingPlanar cost function with SE2 object and end effector poses plus c_square parameter', 'compute the 3x3 contact matrix D from a contact point and end effector jacobian using _compute_D', 'compute the object velocity vector V from consecutive object poses and rotation angle using _compute_V', 'compute the contact point velocity vector Vp from end effector poses and rotation using _compute_Vp', 'get the 3-D error tensor and jacobians for all optimization variables using error or jacobians methods']
```

Usage

```
{'create_quasi_static_pushing_planar': 'create a QuasiStaticPushingPlanar cost function with SE2 object and end effector poses plus c_square parameter', 'compute_contact_matrix_D': 'compute the 3x3 contact matrix D from a contact point and end effector jacobian using _compute_D', 'compute_object_velocity_V': 'compute the object velocity vector V from consecutive object poses and rotation angle using _compute_V', 'compute_contact_velocity_Vp': 'compute the contact point velocity vector Vp from end effector poses and rotation using _compute_Vp', 'get_error_and_jacobians': 'get the 3-D error tensor and jacobians for all optimization variables using error or jacobians methods'}
```

