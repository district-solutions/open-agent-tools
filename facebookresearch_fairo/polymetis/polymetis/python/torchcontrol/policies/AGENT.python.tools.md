# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/torchcontrol/policies/default_controller.py

Prompts

```
['create a DefaultController with Kp and Kd gains for PD joint-space control over robot state', 'run the DefaultController forward pass with a state dict containing joint positions and velocities to get torque feedback', 'reset the DefaultController running flag so the next forward pass re-initializes the desired joint positions', 'review the DefaultController constructor to understand how JointSpacePD and joint_pos_desired are initialized from Kq and Kd gains', 'summarize the DefaultController class which provides PD control by holding the robot at its initial joint configuration', 'create a JointImpedanceControl policy module with Kp and Kd gains for joint space impedance control', 'create a HybridJointImpedanceControl policy with both fixed joint gains and adaptive operational space gains', 'create a CartesianImpedanceControl policy module with Kp and Kd gains for Cartesian space impedance control', 'run the JointImpedanceControl forward pass with a state dict to compute joint torques', 'run the CartesianImpedanceControl forward pass to compute joint torques from end-effector pose errors', 'create a JointTrajectoryExecutor with joint position and velocity trajectories and PD gains', 'run the JointTrajectoryExecutor forward pass with a state dict to compute joint torques', 'create an EndEffectorTrajectoryExecutor with EE pose and twist trajectories and Cartesian PD gains', 'run the EndEffectorTrajectoryExecutor forward pass with a state dict to compute joint torques', 'create an iLQR policy with time-varying feedback gains, desired states, and feedforward torques', 'create a JointVelocityControl policy with desired joint velocities, PD gains, and a robot model', 'run the forward pass of JointVelocityControl with a state dictionary to compute joint torques', 'build an InverseDynamics feedforward module using the robot model for Coriolis compensation', 'test the JointSpacePD feedback controller with position and velocity inputs and desired targets', 'review the JointVelocityControl __init__ to understand how PD gains and desired velocities are configured']
```

Usage

```
{'create_DefaultController': 'create a DefaultController with Kp and Kd gains for PD joint-space control over robot state', 'run_DefaultController_forward': 'run the DefaultController forward pass with a state dict containing joint positions and velocities to get torque feedback', 'reset_DefaultController': 'reset the DefaultController running flag so the next forward pass re-initializes the desired joint positions', 'review_DefaultController_init': 'review the DefaultController constructor to understand how JointSpacePD and joint_pos_desired are initialized from Kq and Kd gains', 'summarize_DefaultController': 'summarize the DefaultController class which provides PD control by holding the robot at its initial joint configuration'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/torchcontrol/policies/impedance.py

Prompts

```
['create a DefaultController with Kp and Kd gains for PD joint-space control over robot state', 'run the DefaultController forward pass with a state dict containing joint positions and velocities to get torque feedback', 'reset the DefaultController running flag so the next forward pass re-initializes the desired joint positions', 'review the DefaultController constructor to understand how JointSpacePD and joint_pos_desired are initialized from Kq and Kd gains', 'summarize the DefaultController class which provides PD control by holding the robot at its initial joint configuration', 'create a JointImpedanceControl policy module with Kp and Kd gains for joint space impedance control', 'create a HybridJointImpedanceControl policy with both fixed joint gains and adaptive operational space gains', 'create a CartesianImpedanceControl policy module with Kp and Kd gains for Cartesian space impedance control', 'run the JointImpedanceControl forward pass with a state dict to compute joint torques', 'run the CartesianImpedanceControl forward pass to compute joint torques from end-effector pose errors', 'create a JointTrajectoryExecutor with joint position and velocity trajectories and PD gains', 'run the JointTrajectoryExecutor forward pass with a state dict to compute joint torques', 'create an EndEffectorTrajectoryExecutor with EE pose and twist trajectories and Cartesian PD gains', 'run the EndEffectorTrajectoryExecutor forward pass with a state dict to compute joint torques', 'create an iLQR policy with time-varying feedback gains, desired states, and feedforward torques', 'create a JointVelocityControl policy with desired joint velocities, PD gains, and a robot model', 'run the forward pass of JointVelocityControl with a state dictionary to compute joint torques', 'build an InverseDynamics feedforward module using the robot model for Coriolis compensation', 'test the JointSpacePD feedback controller with position and velocity inputs and desired targets', 'review the JointVelocityControl __init__ to understand how PD gains and desired velocities are configured']
```

Usage

```
{'create_joint_impedance_controller': 'create a JointImpedanceControl policy module with Kp and Kd gains for joint space impedance control', 'create_hybrid_joint_impedance_controller': 'create a HybridJointImpedanceControl policy with both fixed joint gains and adaptive operational space gains', 'create_cartesian_impedance_controller': 'create a CartesianImpedanceControl policy module with Kp and Kd gains for Cartesian space impedance control', 'run_joint_impedance_forward': 'run the JointImpedanceControl forward pass with a state dict to compute joint torques', 'run_cartesian_impedance_forward': 'run the CartesianImpedanceControl forward pass to compute joint torques from end-effector pose errors'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/torchcontrol/policies/trajectory.py

Prompts

```
['create a DefaultController with Kp and Kd gains for PD joint-space control over robot state', 'run the DefaultController forward pass with a state dict containing joint positions and velocities to get torque feedback', 'reset the DefaultController running flag so the next forward pass re-initializes the desired joint positions', 'review the DefaultController constructor to understand how JointSpacePD and joint_pos_desired are initialized from Kq and Kd gains', 'summarize the DefaultController class which provides PD control by holding the robot at its initial joint configuration', 'create a JointImpedanceControl policy module with Kp and Kd gains for joint space impedance control', 'create a HybridJointImpedanceControl policy with both fixed joint gains and adaptive operational space gains', 'create a CartesianImpedanceControl policy module with Kp and Kd gains for Cartesian space impedance control', 'run the JointImpedanceControl forward pass with a state dict to compute joint torques', 'run the CartesianImpedanceControl forward pass to compute joint torques from end-effector pose errors', 'create a JointTrajectoryExecutor with joint position and velocity trajectories and PD gains', 'run the JointTrajectoryExecutor forward pass with a state dict to compute joint torques', 'create an EndEffectorTrajectoryExecutor with EE pose and twist trajectories and Cartesian PD gains', 'run the EndEffectorTrajectoryExecutor forward pass with a state dict to compute joint torques', 'create an iLQR policy with time-varying feedback gains, desired states, and feedforward torques', 'create a JointVelocityControl policy with desired joint velocities, PD gains, and a robot model', 'run the forward pass of JointVelocityControl with a state dictionary to compute joint torques', 'build an InverseDynamics feedforward module using the robot model for Coriolis compensation', 'test the JointSpacePD feedback controller with position and velocity inputs and desired targets', 'review the JointVelocityControl __init__ to understand how PD gains and desired velocities are configured']
```

Usage

```
{'create_joint_trajectory_executor': 'create a JointTrajectoryExecutor with joint position and velocity trajectories and PD gains', 'run_joint_trajectory_forward': 'run the JointTrajectoryExecutor forward pass with a state dict to compute joint torques', 'create_ee_trajectory_executor': 'create an EndEffectorTrajectoryExecutor with EE pose and twist trajectories and Cartesian PD gains', 'run_ee_trajectory_forward': 'run the EndEffectorTrajectoryExecutor forward pass with a state dict to compute joint torques', 'create_iLQR_policy': 'create an iLQR policy with time-varying feedback gains, desired states, and feedforward torques'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/torchcontrol/policies/velocity.py

Prompts

```
['create a DefaultController with Kp and Kd gains for PD joint-space control over robot state', 'run the DefaultController forward pass with a state dict containing joint positions and velocities to get torque feedback', 'reset the DefaultController running flag so the next forward pass re-initializes the desired joint positions', 'review the DefaultController constructor to understand how JointSpacePD and joint_pos_desired are initialized from Kq and Kd gains', 'summarize the DefaultController class which provides PD control by holding the robot at its initial joint configuration', 'create a JointImpedanceControl policy module with Kp and Kd gains for joint space impedance control', 'create a HybridJointImpedanceControl policy with both fixed joint gains and adaptive operational space gains', 'create a CartesianImpedanceControl policy module with Kp and Kd gains for Cartesian space impedance control', 'run the JointImpedanceControl forward pass with a state dict to compute joint torques', 'run the CartesianImpedanceControl forward pass to compute joint torques from end-effector pose errors', 'create a JointTrajectoryExecutor with joint position and velocity trajectories and PD gains', 'run the JointTrajectoryExecutor forward pass with a state dict to compute joint torques', 'create an EndEffectorTrajectoryExecutor with EE pose and twist trajectories and Cartesian PD gains', 'run the EndEffectorTrajectoryExecutor forward pass with a state dict to compute joint torques', 'create an iLQR policy with time-varying feedback gains, desired states, and feedforward torques', 'create a JointVelocityControl policy with desired joint velocities, PD gains, and a robot model', 'run the forward pass of JointVelocityControl with a state dictionary to compute joint torques', 'build an InverseDynamics feedforward module using the robot model for Coriolis compensation', 'test the JointSpacePD feedback controller with position and velocity inputs and desired targets', 'review the JointVelocityControl __init__ to understand how PD gains and desired velocities are configured']
```

Usage

```
{'create_joint_velocity_control': 'create a JointVelocityControl policy with desired joint velocities, PD gains, and a robot model', 'run_forward_velocity_control': 'run the forward pass of JointVelocityControl with a state dictionary to compute joint torques', 'build_inverse_dynamics_feedforward': 'build an InverseDynamics feedforward module using the robot model for Coriolis compensation', 'test_joint_pd_feedback': 'test the JointSpacePD feedback controller with position and velocity inputs and desired targets', 'review_joint_velocity_control_init': 'review the JointVelocityControl __init__ to understand how PD gains and desired velocities are configured'}
```

