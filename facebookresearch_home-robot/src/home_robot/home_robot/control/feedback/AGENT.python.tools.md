# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/control/feedback/velocity_controllers.py

Prompts

```
['create a DiffDriveVelocityController subclass to compute wheel velocities for a differential drive robot', 'build a DDVelocityControlNoplan controller with a DictConfig to compute velocity commands from pose error', 'test the _velocity_feedback_control static method to compute trapezoidal velocity from position error and acceleration', 'refactor the _turn_rate_limit method to prevent overshooting the goal during heading corrections', 'review the DDVelocityControlNoplan __call__ method to understand how linear and angular velocity commands are computed']
```

Usage

```
{'create_diff_drive_controller': 'create a DiffDriveVelocityController subclass to compute wheel velocities for a differential drive robot', 'build_noplan_velocity_controller': 'build a DDVelocityControlNoplan controller with a DictConfig to compute velocity commands from pose error', 'test_velocity_feedback_control': 'test the _velocity_feedback_control static method to compute trapezoidal velocity from position error and acceleration', 'refactor_turn_rate_limit': 'refactor the _turn_rate_limit method to prevent overshooting the goal during heading corrections', 'review_call_method': 'review the DDVelocityControlNoplan __call__ method to understand how linear and angular velocity commands are computed'}
```

