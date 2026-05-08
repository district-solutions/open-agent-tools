# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/robot_drivers/psyonic_gripper/gripper_server.py

Prompts

```
['run the GripperServerLauncher to start a gRPC server for the Psyonic Ability Hand gripper', 'create a PsyonicGripperServer instance to expose hand controls via the PolymetisControllerServer gRPC interface', 'get the current robot state including joint positions and velocities from the PsyonicGripperServer', 'set the gripper controller to execute a TorchScript policy with joint position waypoints', 'grasp an object by calling the OriginalPsyonicGripperServer Grasp method with width and speed parameters', 'run the psyonic hand demo to test robot arm joint movements via RobotInterface', 'test the do_grasps function to perform n iterations of basic grasping motion on the robot', 'create a RobotInterface instance with an IP address and port to control the robot', 'move the robot to target joint positions using move_to_joint_positions with a time_to_go parameter', 'run the psyonic gripper demo that cycles through grasps, sine waves, and hand poses', 'do n iterations of a basic grasping motion with the psyonic robot hand', 'move the psyonic robot hand fingers through a sine wave for n steps', 'move the psyonic robot hand into a peace sign pose', 'move the psyonic robot hand into a rock on gesture pose']
```

Usage

```
{'run_gripper_server': 'run the GripperServerLauncher to start a gRPC server for the Psyonic Ability Hand gripper', 'create_psyonic_gripper_server': 'create a PsyonicGripperServer instance to expose hand controls via the PolymetisControllerServer gRPC interface', 'get_robot_state': 'get the current robot state including joint positions and velocities from the PsyonicGripperServer', 'set_controller_waypoints': 'set the gripper controller to execute a TorchScript policy with joint position waypoints', 'grasp_with_gripper': 'grasp an object by calling the OriginalPsyonicGripperServer Grasp method with width and speed parameters'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/robot_drivers/psyonic_gripper/psyonic-hand-demo.py

Prompts

```
['run the GripperServerLauncher to start a gRPC server for the Psyonic Ability Hand gripper', 'create a PsyonicGripperServer instance to expose hand controls via the PolymetisControllerServer gRPC interface', 'get the current robot state including joint positions and velocities from the PsyonicGripperServer', 'set the gripper controller to execute a TorchScript policy with joint position waypoints', 'grasp an object by calling the OriginalPsyonicGripperServer Grasp method with width and speed parameters', 'run the psyonic hand demo to test robot arm joint movements via RobotInterface', 'test the do_grasps function to perform n iterations of basic grasping motion on the robot', 'create a RobotInterface instance with an IP address and port to control the robot', 'move the robot to target joint positions using move_to_joint_positions with a time_to_go parameter', 'run the psyonic gripper demo that cycles through grasps, sine waves, and hand poses', 'do n iterations of a basic grasping motion with the psyonic robot hand', 'move the psyonic robot hand fingers through a sine wave for n steps', 'move the psyonic robot hand into a peace sign pose', 'move the psyonic robot hand into a rock on gesture pose']
```

Usage

```
{'run_robot_interface_demo': 'run the psyonic hand demo to test robot arm joint movements via RobotInterface', 'test_do_grasps': 'test the do_grasps function to perform n iterations of basic grasping motion on the robot', 'create_robot_interface': 'create a RobotInterface instance with an IP address and port to control the robot', 'move_to_joint_positions': 'move the robot to target joint positions using move_to_joint_positions with a time_to_go parameter', 'get_robot_state': 'get the robot state, joint positions, and joint velocities using RobotInterface methods'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/robot_drivers/psyonic_gripper/psyonic-hand-only.py

Prompts

```
['run the GripperServerLauncher to start a gRPC server for the Psyonic Ability Hand gripper', 'create a PsyonicGripperServer instance to expose hand controls via the PolymetisControllerServer gRPC interface', 'get the current robot state including joint positions and velocities from the PsyonicGripperServer', 'set the gripper controller to execute a TorchScript policy with joint position waypoints', 'grasp an object by calling the OriginalPsyonicGripperServer Grasp method with width and speed parameters', 'run the psyonic hand demo to test robot arm joint movements via RobotInterface', 'test the do_grasps function to perform n iterations of basic grasping motion on the robot', 'create a RobotInterface instance with an IP address and port to control the robot', 'move the robot to target joint positions using move_to_joint_positions with a time_to_go parameter', 'run the psyonic gripper demo that cycles through grasps, sine waves, and hand poses', 'do n iterations of a basic grasping motion with the psyonic robot hand', 'move the psyonic robot hand fingers through a sine wave for n steps', 'move the psyonic robot hand into a peace sign pose', 'move the psyonic robot hand into a rock on gesture pose']
```

Usage

```
{'run_psyonic_gripper_demo': 'run the psyonic gripper demo that cycles through grasps, sine waves, and hand poses', 'do_grasps_n_iterations': 'do n iterations of a basic grasping motion with the psyonic robot hand', 'do_sine_wave_steps': 'move the psyonic robot hand fingers through a sine wave for n steps', 'do_peace_sign_pose': 'move the psyonic robot hand into a peace sign pose', 'do_rock_on_pose': 'move the psyonic robot hand into a rock on gesture pose'}
```

