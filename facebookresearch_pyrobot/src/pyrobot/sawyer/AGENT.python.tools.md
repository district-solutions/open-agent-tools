# Agent Python Tools

- repo: facebookresearch/pyrobot
- repo_uri: https://github.com/facebookresearch/pyrobot

## File: facebookresearch_pyrobot/src/pyrobot/sawyer/arm.py

Prompts

```
['create a SawyerArm instance with configs and an optional moveit planner name', 'command the Sawyer robot arm to move to its home zero position', 'move the Sawyer robot arm to its predefined neutral pose configuration', 'get the current collision detection state of the Sawyer robot arm', 'publish joint position commands to the Sawyer robot arm via ROS', 'initialize a SawyerGripper with configs, gripper name, calibration, and wait time settings', 'open the Sawyer robot gripper to a specified position with optional blocking wait', 'close the Sawyer robot gripper to a specified position with optional blocking wait', 'reset a stuck Sawyer gripper by opening, closing, and reopening it sequentially', 'review the SawyerGripper class and its open, close, and reset gripper control methods']
```

Usage

```
{'init_sawyer_arm': 'create a SawyerArm instance with configs and an optional moveit planner name', 'go_home_sawyer': 'command the Sawyer robot arm to move to its home zero position', 'move_to_neutral_sawyer': 'move the Sawyer robot arm to its predefined neutral pose configuration', 'get_collision_state_sawyer': 'get the current collision detection state of the Sawyer robot arm', 'pub_joint_positions_sawyer': 'publish joint position commands to the Sawyer robot arm via ROS'}
```

## File: facebookresearch_pyrobot/src/pyrobot/sawyer/gripper.py

Prompts

```
['create a SawyerArm instance with configs and an optional moveit planner name', 'command the Sawyer robot arm to move to its home zero position', 'move the Sawyer robot arm to its predefined neutral pose configuration', 'get the current collision detection state of the Sawyer robot arm', 'publish joint position commands to the Sawyer robot arm via ROS', 'initialize a SawyerGripper with configs, gripper name, calibration, and wait time settings', 'open the Sawyer robot gripper to a specified position with optional blocking wait', 'close the Sawyer robot gripper to a specified position with optional blocking wait', 'reset a stuck Sawyer gripper by opening, closing, and reopening it sequentially', 'review the SawyerGripper class and its open, close, and reset gripper control methods']
```

Usage

```
{'init_SawyerGripper': 'initialize a SawyerGripper with configs, gripper name, calibration, and wait time settings', 'open_gripper': 'open the Sawyer robot gripper to a specified position with optional blocking wait', 'close_gripper': 'close the Sawyer robot gripper to a specified position with optional blocking wait', 'reset_gripper': 'reset a stuck Sawyer gripper by opening, closing, and reopening it sequentially', 'review_SawyerGripper': 'review the SawyerGripper class and its open, close, and reset gripper control methods'}
```

