# Agent Python Tools

- repo: facebookresearch/differentiable-robot-model
- repo_uri: https://github.com/facebookresearch/differentiable-robot-model

## File: facebookresearch_differentiable-robot-model/tests/test_devices.py

Prompts

```
['test the DifferentiableRobotModel class by running all kinematic and dynamic methods on a 2-link robot', 'compute forward kinematics to get translation and rotation of a robot link from joint angles', 'compute inverse dynamics to find joint forces needed to achieve desired accelerations', 'compute forward dynamics to get joint accelerations from applied forces using articulated body algorithm', 'compute the end-effector Jacobian matrix for a specified robot link given joint angles', 'run the pytest test_examples parametrized across iiwa dynamics, forward dynamics, and kinematics experiments on cpu or cuda', 'run the learn_dynamics_iiwa experiment to learn inverse dynamics of the KUKA iiwa robot', 'run the learn_forward_dynamics_iiwa experiment to learn forward dynamics of the KUKA iiwa robot', 'run the learn_kinematics_of_iiwa experiment to learn kinematics of the KUKA iiwa robot', 'run the learn_kinematics_of_toy experiment to learn kinematics of a toy robot', 'test compute_forward_kinematics against PyBullet link state for multiple robot URDFs and batch shapes', 'test compute_endeffector_jacobian against PyBullet calculateJacobian for linear and angular jacobian components', 'test compute_inverse_dynamics against PyBullet calculateInverseDynamics with and without joint damping', 'test compute_lagrangian_inertia_matrix against PyBullet calculateMassMatrix for robot inertia at sampled joint positions', 'test compute_forward_dynamics against PyBullet torque-controlled simulation step to verify joint acceleration output']
```

Usage

```
{'test_differentiable_robot_model': 'test the DifferentiableRobotModel class by running all kinematic and dynamic methods on a 2-link robot', 'compute_forward_kinematics': 'compute forward kinematics to get translation and rotation of a robot link from joint angles', 'compute_inverse_dynamics': 'compute inverse dynamics to find joint forces needed to achieve desired accelerations', 'compute_forward_dynamics': 'compute forward dynamics to get joint accelerations from applied forces using articulated body algorithm', 'compute_endeffector_jacobian': 'compute the end-effector Jacobian matrix for a specified robot link given joint angles'}
```

## File: facebookresearch_differentiable-robot-model/tests/test_examples.py

Prompts

```
['test the DifferentiableRobotModel class by running all kinematic and dynamic methods on a 2-link robot', 'compute forward kinematics to get translation and rotation of a robot link from joint angles', 'compute inverse dynamics to find joint forces needed to achieve desired accelerations', 'compute forward dynamics to get joint accelerations from applied forces using articulated body algorithm', 'compute the end-effector Jacobian matrix for a specified robot link given joint angles', 'run the pytest test_examples parametrized across iiwa dynamics, forward dynamics, and kinematics experiments on cpu or cuda', 'run the learn_dynamics_iiwa experiment to learn inverse dynamics of the KUKA iiwa robot', 'run the learn_forward_dynamics_iiwa experiment to learn forward dynamics of the KUKA iiwa robot', 'run the learn_kinematics_of_iiwa experiment to learn kinematics of the KUKA iiwa robot', 'run the learn_kinematics_of_toy experiment to learn kinematics of a toy robot', 'test compute_forward_kinematics against PyBullet link state for multiple robot URDFs and batch shapes', 'test compute_endeffector_jacobian against PyBullet calculateJacobian for linear and angular jacobian components', 'test compute_inverse_dynamics against PyBullet calculateInverseDynamics with and without joint damping', 'test compute_lagrangian_inertia_matrix against PyBullet calculateMassMatrix for robot inertia at sampled joint positions', 'test compute_forward_dynamics against PyBullet torque-controlled simulation step to verify joint acceleration output']
```

Usage

```
{'run_test_examples': 'run the pytest test_examples parametrized across iiwa dynamics, forward dynamics, and kinematics experiments on cpu or cuda', 'run_learn_dynamics_iiwa': 'run the learn_dynamics_iiwa experiment to learn inverse dynamics of the KUKA iiwa robot', 'run_learn_forward_dynamics_iiwa': 'run the learn_forward_dynamics_iiwa experiment to learn forward dynamics of the KUKA iiwa robot', 'run_learn_kinematics_of_iiwa': 'run the learn_kinematics_of_iiwa experiment to learn kinematics of the KUKA iiwa robot', 'run_learn_kinematics_of_toy': 'run the learn_kinematics_of_toy experiment to learn kinematics of a toy robot'}
```

## File: facebookresearch_differentiable-robot-model/tests/test_kinematics_dynamics.py

Prompts

```
['test the DifferentiableRobotModel class by running all kinematic and dynamic methods on a 2-link robot', 'compute forward kinematics to get translation and rotation of a robot link from joint angles', 'compute inverse dynamics to find joint forces needed to achieve desired accelerations', 'compute forward dynamics to get joint accelerations from applied forces using articulated body algorithm', 'compute the end-effector Jacobian matrix for a specified robot link given joint angles', 'run the pytest test_examples parametrized across iiwa dynamics, forward dynamics, and kinematics experiments on cpu or cuda', 'run the learn_dynamics_iiwa experiment to learn inverse dynamics of the KUKA iiwa robot', 'run the learn_forward_dynamics_iiwa experiment to learn forward dynamics of the KUKA iiwa robot', 'run the learn_kinematics_of_iiwa experiment to learn kinematics of the KUKA iiwa robot', 'run the learn_kinematics_of_toy experiment to learn kinematics of a toy robot', 'test compute_forward_kinematics against PyBullet link state for multiple robot URDFs and batch shapes', 'test compute_endeffector_jacobian against PyBullet calculateJacobian for linear and angular jacobian components', 'test compute_inverse_dynamics against PyBullet calculateInverseDynamics with and without joint damping', 'test compute_lagrangian_inertia_matrix against PyBullet calculateMassMatrix for robot inertia at sampled joint positions', 'test compute_forward_dynamics against PyBullet torque-controlled simulation step to verify joint acceleration output']
```

Usage

```
{'test_forward_kinematics': 'test compute_forward_kinematics against PyBullet link state for multiple robot URDFs and batch shapes', 'test_ee_jacobian': 'test compute_endeffector_jacobian against PyBullet calculateJacobian for linear and angular jacobian components', 'test_inverse_dynamics': 'test compute_inverse_dynamics against PyBullet calculateInverseDynamics with and without joint damping', 'test_mass_computation': 'test compute_lagrangian_inertia_matrix against PyBullet calculateMassMatrix for robot inertia at sampled joint positions', 'test_forward_dynamics': 'test compute_forward_dynamics against PyBullet torque-controlled simulation step to verify joint acceleration output'}
```

