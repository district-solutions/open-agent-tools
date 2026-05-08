# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/control/goto_controller.py

Prompts

```
['create a GotoVelocityController instance to navigate a diff drive robot to a target goal pose', 'compute linear and angular velocity commands for the robot to reach its current goal', 'update the robot target goal pose in global or relative coordinates for the controller', 'transform SE2 coordinates from the global world frame to the robot local base frame', 'transform SE2 coordinates from the robot local base frame to the global world frame', 'create a TrajFollower instance with default or custom DictConfig for trajectory following control', 'update the TrajFollower trajectory with a callable that returns desired state, derivative, and done flag', 'call forward on TrajFollower with current xyt pose and time to get linear and angular velocity commands', 'check if the TrajFollower has finished executing its current trajectory using the is_done method', 'review the TrajFollower feedback controller PI control logic for computing velocity commands from pose error']
```

Usage

```
{'create_GotoVelocityController': 'create a GotoVelocityController instance to navigate a diff drive robot to a target goal pose', 'compute_control_GotoVelocityController': 'compute linear and angular velocity commands for the robot to reach its current goal', 'update_goal_GotoVelocityController': 'update the robot target goal pose in global or relative coordinates for the controller', 'transform_xyt_global_to_base': 'transform SE2 coordinates from the global world frame to the robot local base frame', 'transform_xyt_base_to_global': 'transform SE2 coordinates from the robot local base frame to the global world frame'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/control/traj_following_controller.py

Prompts

```
['create a GotoVelocityController instance to navigate a diff drive robot to a target goal pose', 'compute linear and angular velocity commands for the robot to reach its current goal', 'update the robot target goal pose in global or relative coordinates for the controller', 'transform SE2 coordinates from the global world frame to the robot local base frame', 'transform SE2 coordinates from the robot local base frame to the global world frame', 'create a TrajFollower instance with default or custom DictConfig for trajectory following control', 'update the TrajFollower trajectory with a callable that returns desired state, derivative, and done flag', 'call forward on TrajFollower with current xyt pose and time to get linear and angular velocity commands', 'check if the TrajFollower has finished executing its current trajectory using the is_done method', 'review the TrajFollower feedback controller PI control logic for computing velocity commands from pose error']
```

Usage

```
{'create_traj_follower': 'create a TrajFollower instance with default or custom DictConfig for trajectory following control', 'update_trajectory_callable': 'update the TrajFollower trajectory with a callable that returns desired state, derivative, and done flag', 'forward_velocity_command': 'call forward on TrajFollower with current xyt pose and time to get linear and angular velocity commands', 'check_traj_done': 'check if the TrajFollower has finished executing its current trajectory using the is_done method', 'review_feedback_controller': 'review the TrajFollower feedback controller PI control logic for computing velocity commands from pose error'}
```

