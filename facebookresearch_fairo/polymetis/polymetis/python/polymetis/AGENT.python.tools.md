# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/gripper_interface.py

Prompts

```
['create a GripperInterface instance to connect to a gRPC gripper server at a given IP and port', 'get the current state of the gripper by calling get_state on a GripperInterface instance', 'command the gripper to move to a target width with specified speed and force using goto', 'command the gripper to perform a grasp with specified speed, force, and tolerance using grasp', 'send a blocking or non-blocking gripper command through the internal command queue using _send_gripper_command', 'create a RobotInterface instance to connect to a gRPC Polymetis controller server at a given IP and port', 'move the robot to desired joint positions using a JointGoToPolicy with adaptive time-to-go', 'move the robot end-effector to a desired position and orientation using inverse kinematics and operational space interpolation', 'start a non-blocking joint impedance controller for continuous joint position control with updateable desired positions', 'get the current end-effector pose as a 3D position and 4D quaternion orientation via forward kinematics']
```

Usage

```
{'create_gripper_interface': 'create a GripperInterface instance to connect to a gRPC gripper server at a given IP and port', 'get_gripper_state': 'get the current state of the gripper by calling get_state on a GripperInterface instance', 'command_gripper_goto': 'command the gripper to move to a target width with specified speed and force using goto', 'command_gripper_grasp': 'command the gripper to perform a grasp with specified speed, force, and tolerance using grasp', 'send_gripper_command': 'send a blocking or non-blocking gripper command through the internal command queue using _send_gripper_command'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/robot_interface.py

Prompts

```
['create a GripperInterface instance to connect to a gRPC gripper server at a given IP and port', 'get the current state of the gripper by calling get_state on a GripperInterface instance', 'command the gripper to move to a target width with specified speed and force using goto', 'command the gripper to perform a grasp with specified speed, force, and tolerance using grasp', 'send a blocking or non-blocking gripper command through the internal command queue using _send_gripper_command', 'create a RobotInterface instance to connect to a gRPC Polymetis controller server at a given IP and port', 'move the robot to desired joint positions using a JointGoToPolicy with adaptive time-to-go', 'move the robot end-effector to a desired position and orientation using inverse kinematics and operational space interpolation', 'start a non-blocking joint impedance controller for continuous joint position control with updateable desired positions', 'get the current end-effector pose as a 3D position and 4D quaternion orientation via forward kinematics']
```

Usage

```
{'create_robot_interface': 'create a RobotInterface instance to connect to a gRPC Polymetis controller server at a given IP and port', 'move_to_joint_positions': 'move the robot to desired joint positions using a JointGoToPolicy with adaptive time-to-go', 'move_to_ee_pose': 'move the robot end-effector to a desired position and orientation using inverse kinematics and operational space interpolation', 'start_joint_impedance': 'start a non-blocking joint impedance controller for continuous joint position control with updateable desired positions', 'get_ee_pose': 'get the current end-effector pose as a 3D position and 4D quaternion orientation via forward kinematics'}
```

