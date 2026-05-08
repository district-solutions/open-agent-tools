# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/robot_client/robotiq_gripper/robotiq_gripper_client.py

Prompts

```
['create a RobotiqGripperClient instance that connects to a gripper on a serial port and gRPC server', 'run the gripper control loop that polls state and applies commands at a fixed hz rate', 'get the current gripper state including width, grasp detection, and moving status as a protobuf message', 'apply a gripper command to move the gripper to a target width with specified speed and force', 'initialize a RobotiqGripperClient by activating the gripper and registering metadata with the Polymetis gRPC server']
```

Usage

```
{'create_robotiq_gripper_client': 'create a RobotiqGripperClient instance that connects to a gripper on a serial port and gRPC server', 'run_gripper_control_loop': 'run the gripper control loop that polls state and applies commands at a fixed hz rate', 'get_gripper_state': 'get the current gripper state including width, grasp detection, and moving status as a protobuf message', 'apply_gripper_command': 'apply a gripper command to move the gripper to a target width with specified speed and force', 'init_robotiq_gripper_client': 'initialize a RobotiqGripperClient by activating the gripper and registering metadata with the Polymetis gRPC server'}
```

