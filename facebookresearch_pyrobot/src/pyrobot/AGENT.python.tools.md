# Agent Python Tools

- repo: facebookresearch/pyrobot
- repo_uri: https://github.com/facebookresearch/pyrobot

## File: facebookresearch_pyrobot/src/pyrobot/core.py

Prompts

```
['create a Robot instance with a given robot name and optional arm, base, camera, gripper configs', 'command the robot arm to move its end effector to a target position and orientation', 'set the robot arm joint angles with optional MoveIt motion planning and collision checking', 'retrieve synchronized RGB and depth images from the robot camera as numpy arrays', 'compute inverse kinematics to find joint positions for a desired end effector pose']
```

Usage

```
{'init_robot': 'create a Robot instance with a given robot name and optional arm, base, camera, gripper configs', 'set_ee_pose': 'command the robot arm to move its end effector to a target position and orientation', 'set_joint_positions': 'set the robot arm joint angles with optional MoveIt motion planning and collision checking', 'get_rgb_depth': 'retrieve synchronized RGB and depth images from the robot camera as numpy arrays', 'compute_ik': 'compute inverse kinematics to find joint positions for a desired end effector pose'}
```

