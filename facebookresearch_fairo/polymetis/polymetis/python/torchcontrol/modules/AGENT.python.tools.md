# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/torchcontrol/modules/feedback.py

Prompts

```
['create a LinearFeedback control module with a gain matrix K for linear state feedback', 'create a JointSpacePD controller with Kp and Kd gain matrices for joint space PD control', 'create a HybridJointSpacePD controller combining constant joint gains with adaptive operational space gains', 'create a CartesianSpacePDFast controller with Kp and Kd gains for SE3 pose space PD control', 'create a CartesianSpacePD controller using TransformationObj inputs for SE3 pose space PD control', 'build a python module that uses InverseDynamics to compute required generalized forces for a robot model', 'create a python module that uses Coriolis to compute Coriolis forces from robot coordinates and velocities', 'test the InverseDynamics forward method with sample q, qd, and qdd tensors', 'test the Coriolis forward method with sample q and qd tensors', 'review the InverseDynamics and Coriolis classes for robot control feedforward computation']
```

Usage

```
{'create_LinearFeedback': 'create a LinearFeedback control module with a gain matrix K for linear state feedback', 'create_JointSpacePD': 'create a JointSpacePD controller with Kp and Kd gain matrices for joint space PD control', 'create_HybridJointSpacePD': 'create a HybridJointSpacePD controller combining constant joint gains with adaptive operational space gains', 'create_CartesianSpacePDFast': 'create a CartesianSpacePDFast controller with Kp and Kd gains for SE3 pose space PD control', 'create_CartesianSpacePD': 'create a CartesianSpacePD controller using TransformationObj inputs for SE3 pose space PD control'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/torchcontrol/modules/feedforward.py

Prompts

```
['create a LinearFeedback control module with a gain matrix K for linear state feedback', 'create a JointSpacePD controller with Kp and Kd gain matrices for joint space PD control', 'create a HybridJointSpacePD controller combining constant joint gains with adaptive operational space gains', 'create a CartesianSpacePDFast controller with Kp and Kd gains for SE3 pose space PD control', 'create a CartesianSpacePD controller using TransformationObj inputs for SE3 pose space PD control', 'build a python module that uses InverseDynamics to compute required generalized forces for a robot model', 'create a python module that uses Coriolis to compute Coriolis forces from robot coordinates and velocities', 'test the InverseDynamics forward method with sample q, qd, and qdd tensors', 'test the Coriolis forward method with sample q and qd tensors', 'review the InverseDynamics and Coriolis classes for robot control feedforward computation']
```

Usage

```
{'build_inverse_dynamics_module': 'build a python module that uses InverseDynamics to compute required generalized forces for a robot model', 'create_coriolis_force_module': 'create a python module that uses Coriolis to compute Coriolis forces from robot coordinates and velocities', 'test_inverse_dynamics_forward': 'test the InverseDynamics forward method with sample q, qd, and qdd tensors', 'test_coriolis_forward': 'test the Coriolis forward method with sample q and qd tensors', 'review_feedforward_classes': 'review the InverseDynamics and Coriolis classes for robot control feedforward computation'}
```

