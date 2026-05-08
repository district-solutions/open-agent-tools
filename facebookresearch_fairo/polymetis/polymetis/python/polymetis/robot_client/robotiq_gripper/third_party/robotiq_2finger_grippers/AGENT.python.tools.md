# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/robot_client/robotiq_gripper/third_party/robotiq_2finger_grippers/robotiq_2f_gripper.py

Prompts

```
['create a Robotiq2FingerGripper instance connected to a serial port with configurable device ID, stroke, and baud rate', 'activate or deactivate the Robotiq 2-finger gripper by setting the rACT command variable and updating the command', 'move the gripper to a target position with specified velocity and grip force using the goto method', 'read the gripper status including position, current, fault code, and object detection flags via getStatus', 'check if the gripper is ready, moving, stopped, reset, or has detected an object using state query methods']
```

Usage

```
{'create_gripper_instance': 'create a Robotiq2FingerGripper instance connected to a serial port with configurable device ID, stroke, and baud rate', 'activate_and_deactivate_gripper': 'activate or deactivate the Robotiq 2-finger gripper by setting the rACT command variable and updating the command', 'move_gripper_to_position': 'move the gripper to a target position with specified velocity and grip force using the goto method', 'read_gripper_status': 'read the gripper status including position, current, fault code, and object detection flags via getStatus', 'check_gripper_state': 'check if the gripper is ready, moving, stopped, reset, or has detected an object using state query methods'}
```

