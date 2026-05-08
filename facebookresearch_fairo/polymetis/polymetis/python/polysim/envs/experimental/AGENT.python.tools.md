# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/polysim/envs/experimental/bullet_manipulator.py

Prompts

```
['run the BulletManipulator PyBullet simulation with a URDF robot model and Hydra config', 'create a BulletManipulator instance that loads a robot URDF and initializes joint states', 'get the current arm joint positions and velocities as a RobotState protobuf message', 'apply torque commands to the robot arm with gravity compensation via inverse dynamics', 'apply position control commands to the robot gripper to set target width']
```

Usage

```
{'run_bullet_manipulator_sim': 'run the BulletManipulator PyBullet simulation with a URDF robot model and Hydra config', 'create_bullet_manipulator_instance': 'create a BulletManipulator instance that loads a robot URDF and initializes joint states', 'get_arm_state_callback': 'get the current arm joint positions and velocities as a RobotState protobuf message', 'apply_arm_control_torque': 'apply torque commands to the robot arm with gravity compensation via inverse dynamics', 'apply_gripper_control_position': 'apply position control commands to the robot gripper to set target width'}
```

