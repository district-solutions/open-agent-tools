# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/cortexbench/trifinger_vc/src/trifinger_vc/control/cube_utils.py

Prompts

```
['compute the contact point position in world frame from a contact point parameter and object pose', 'get contact point positions in world frame from a list of contact point parameters and object pose', 'compute the contact point position in object frame from a contact point parameter and cube half size', 'get contact point parameters on the cube for each finger based on object pose and finger type', 'linearly interpolate between position waypoints to generate position and velocity trajectories with a given timestep', 'build a python module to initialize CustomPinocchioUtils with a URDF path and link names for kinematic control', 'create a function that computes the 9x9 linear Jacobian matrix for all three fingers given joint configuration q', 'test the get_tip_link_jacobian method to compute the 6x9 Jacobian for a specified finger tip link', 'refactor the get_finger_g method to compute joint space gravity vector for a single finger using link Jacobians', 'review the inverse_dyn method that computes joint torques using Pinocchio RNEA algorithm for a given configuration', 'get the fingertip radius offset for a given trifinger robot type like trifingeredu or trifingerpro', 'get the initial fingertip base positions as numpy arrays for a given trifinger robot type', 'get the constant DIST_FRAME_TO_SURFACE value used for contact point computation offsets', 'refactor get_ft_radius to support additional trifinger robot types beyond edu and pro variants', 'refactor get_finger_base_positions to parameterize the radius r instead of hardcoding 0.15', 'build a python module to create an ImpedanceController for TriFinger robot with configurable kp and kv gains', 'compute joint torques for all fingers given desired fingertip positions and velocities using get_command_torque', 'check if all finger linear velocity magnitudes have converged below epsilon using is_avg_dx_converged', 'get the current observation dictionary with fingertip positions, velocities, gains, and torque from get_observation', 'refactor the ImpedanceController to support per-finger kp and kv gain tuning instead of uniform gains']
```

Usage

```
{'compute_contact_point_world_frame': 'compute the contact point position in world frame from a contact point parameter and object pose', 'compute_contact_points_batch': 'get contact point positions in world frame from a list of contact point parameters and object pose', 'compute_contact_point_object_frame': 'compute the contact point position in object frame from a contact point parameter and cube half size', 'get_cube_contact_params': 'get contact point parameters on the cube for each finger based on object pose and finger type', 'linearly_interpolate_trajectory': 'linearly interpolate between position waypoints to generate position and velocity trajectories with a given timestep'}
```

## File: facebookresearch_eai-vc/cortexbench/trifinger_vc/src/trifinger_vc/control/custom_pinocchio_utils.py

Prompts

```
['compute the contact point position in world frame from a contact point parameter and object pose', 'get contact point positions in world frame from a list of contact point parameters and object pose', 'compute the contact point position in object frame from a contact point parameter and cube half size', 'get contact point parameters on the cube for each finger based on object pose and finger type', 'linearly interpolate between position waypoints to generate position and velocity trajectories with a given timestep', 'build a python module to initialize CustomPinocchioUtils with a URDF path and link names for kinematic control', 'create a function that computes the 9x9 linear Jacobian matrix for all three fingers given joint configuration q', 'test the get_tip_link_jacobian method to compute the 6x9 Jacobian for a specified finger tip link', 'refactor the get_finger_g method to compute joint space gravity vector for a single finger using link Jacobians', 'review the inverse_dyn method that computes joint torques using Pinocchio RNEA algorithm for a given configuration', 'get the fingertip radius offset for a given trifinger robot type like trifingeredu or trifingerpro', 'get the initial fingertip base positions as numpy arrays for a given trifinger robot type', 'get the constant DIST_FRAME_TO_SURFACE value used for contact point computation offsets', 'refactor get_ft_radius to support additional trifinger robot types beyond edu and pro variants', 'refactor get_finger_base_positions to parameterize the radius r instead of hardcoding 0.15', 'build a python module to create an ImpedanceController for TriFinger robot with configurable kp and kv gains', 'compute joint torques for all fingers given desired fingertip positions and velocities using get_command_torque', 'check if all finger linear velocity magnitudes have converged below epsilon using is_avg_dx_converged', 'get the current observation dictionary with fingertip positions, velocities, gains, and torque from get_observation', 'refactor the ImpedanceController to support per-finger kp and kv gain tuning instead of uniform gains']
```

Usage

```
{'build_custom_pinocchio_utils': 'build a python module to initialize CustomPinocchioUtils with a URDF path and link names for kinematic control', 'create_get_hand_lin_jacobian': 'create a function that computes the 9x9 linear Jacobian matrix for all three fingers given joint configuration q', 'test_get_tip_link_jacobian': 'test the get_tip_link_jacobian method to compute the 6x9 Jacobian for a specified finger tip link', 'refactor_get_finger_g': 'refactor the get_finger_g method to compute joint space gravity vector for a single finger using link Jacobians', 'review_inverse_dyn': 'review the inverse_dyn method that computes joint torques using Pinocchio RNEA algorithm for a given configuration'}
```

## File: facebookresearch_eai-vc/cortexbench/trifinger_vc/src/trifinger_vc/control/finger_utils.py

Prompts

```
['compute the contact point position in world frame from a contact point parameter and object pose', 'get contact point positions in world frame from a list of contact point parameters and object pose', 'compute the contact point position in object frame from a contact point parameter and cube half size', 'get contact point parameters on the cube for each finger based on object pose and finger type', 'linearly interpolate between position waypoints to generate position and velocity trajectories with a given timestep', 'build a python module to initialize CustomPinocchioUtils with a URDF path and link names for kinematic control', 'create a function that computes the 9x9 linear Jacobian matrix for all three fingers given joint configuration q', 'test the get_tip_link_jacobian method to compute the 6x9 Jacobian for a specified finger tip link', 'refactor the get_finger_g method to compute joint space gravity vector for a single finger using link Jacobians', 'review the inverse_dyn method that computes joint torques using Pinocchio RNEA algorithm for a given configuration', 'get the fingertip radius offset for a given trifinger robot type like trifingeredu or trifingerpro', 'get the initial fingertip base positions as numpy arrays for a given trifinger robot type', 'get the constant DIST_FRAME_TO_SURFACE value used for contact point computation offsets', 'refactor get_ft_radius to support additional trifinger robot types beyond edu and pro variants', 'refactor get_finger_base_positions to parameterize the radius r instead of hardcoding 0.15', 'build a python module to create an ImpedanceController for TriFinger robot with configurable kp and kv gains', 'compute joint torques for all fingers given desired fingertip positions and velocities using get_command_torque', 'check if all finger linear velocity magnitudes have converged below epsilon using is_avg_dx_converged', 'get the current observation dictionary with fingertip positions, velocities, gains, and torque from get_observation', 'refactor the ImpedanceController to support per-finger kp and kv gain tuning instead of uniform gains']
```

Usage

```
{'get_ft_radius': 'get the fingertip radius offset for a given trifinger robot type like trifingeredu or trifingerpro', 'get_finger_base_positions': 'get the initial fingertip base positions as numpy arrays for a given trifinger robot type', 'get_DIST_FRAME_TO_SURFACE': 'get the constant DIST_FRAME_TO_SURFACE value used for contact point computation offsets', 'refactor_get_ft_radius': 'refactor get_ft_radius to support additional trifinger robot types beyond edu and pro variants', 'refactor_get_finger_base_positions': 'refactor get_finger_base_positions to parameterize the radius r instead of hardcoding 0.15'}
```

## File: facebookresearch_eai-vc/cortexbench/trifinger_vc/src/trifinger_vc/control/impedance_controller.py

Prompts

```
['compute the contact point position in world frame from a contact point parameter and object pose', 'get contact point positions in world frame from a list of contact point parameters and object pose', 'compute the contact point position in object frame from a contact point parameter and cube half size', 'get contact point parameters on the cube for each finger based on object pose and finger type', 'linearly interpolate between position waypoints to generate position and velocity trajectories with a given timestep', 'build a python module to initialize CustomPinocchioUtils with a URDF path and link names for kinematic control', 'create a function that computes the 9x9 linear Jacobian matrix for all three fingers given joint configuration q', 'test the get_tip_link_jacobian method to compute the 6x9 Jacobian for a specified finger tip link', 'refactor the get_finger_g method to compute joint space gravity vector for a single finger using link Jacobians', 'review the inverse_dyn method that computes joint torques using Pinocchio RNEA algorithm for a given configuration', 'get the fingertip radius offset for a given trifinger robot type like trifingeredu or trifingerpro', 'get the initial fingertip base positions as numpy arrays for a given trifinger robot type', 'get the constant DIST_FRAME_TO_SURFACE value used for contact point computation offsets', 'refactor get_ft_radius to support additional trifinger robot types beyond edu and pro variants', 'refactor get_finger_base_positions to parameterize the radius r instead of hardcoding 0.15', 'build a python module to create an ImpedanceController for TriFinger robot with configurable kp and kv gains', 'compute joint torques for all fingers given desired fingertip positions and velocities using get_command_torque', 'check if all finger linear velocity magnitudes have converged below epsilon using is_avg_dx_converged', 'get the current observation dictionary with fingertip positions, velocities, gains, and torque from get_observation', 'refactor the ImpedanceController to support per-finger kp and kv gain tuning instead of uniform gains']
```

Usage

```
{'build_impedance_controller': 'build a python module to create an ImpedanceController for TriFinger robot with configurable kp and kv gains', 'compute_command_torque': 'compute joint torques for all fingers given desired fingertip positions and velocities using get_command_torque', 'check_velocity_convergence': 'check if all finger linear velocity magnitudes have converged below epsilon using is_avg_dx_converged', 'get_controller_observation': 'get the current observation dictionary with fingertip positions, velocities, gains, and torque from get_observation', 'refactor_impedance_gains': 'refactor the ImpedanceController to support per-finger kp and kv gain tuning instead of uniform gains'}
```

