# Agent Python Tools

- repo: facebookresearch/spot-sim2real
- repo_uri: https://github.com/facebookresearch/spot-sim2real

## File: facebookresearch_spot-sim2real/spot_rl_experiments/spot_rl/examples/run_navigation.py

Prompts

```
['run the robot to navigate to a single goal specified by x,y,theta coordinates', 'run the robot to navigate through multiple waypoints from a YAML config file', 'run the robot to navigate to waypoints then dock automatically after completion', 'run the robot navigation and save trajectory data to a timestamped JSON file', 'parse command line arguments for goal coordinates, waypoints, docking, and trajectory save path', 'run the pick script to make a Spot robot pick up target objects by name', 'parse command line arguments for target object, dont_pick_up, max_episode_steps, and mobile_gaze flags', 'run a Spot robot pick task using RealGazeEnv and the Pick atomic skill controller', 'execute the Pick atomic skill on a Spot robot with a target object goal dictionary', 'construct a gaze configuration for the Pick skill using opts, dont_pick_up, and max_episode_steps', 'run the place skill on a Spot robot by specifying a target x,y,z coordinate in meters', 'run the place skill on a Spot robot using comma-separated waypoint names from a YAML config', "run the place skill with target coordinates relative to the robot's local base frame", 'run the place skill using learned RL policies instead of the Boston Dynamics API', 'parse command-line arguments for place target coordinates, waypoints, local frame flag, and policy usage']
```

Usage

```
{'run_navigation_to_goal': 'run the robot to navigate to a single goal specified by x,y,theta coordinates', 'run_navigation_to_waypoints': 'run the robot to navigate through multiple waypoints from a YAML config file', 'run_navigation_and_dock': 'run the robot to navigate to waypoints then dock automatically after completion', 'run_navigation_save_trajectories': 'run the robot navigation and save trajectory data to a timestamped JSON file', 'parse_arguments': 'parse command line arguments for goal coordinates, waypoints, docking, and trajectory save path'}
```

## File: facebookresearch_spot-sim2real/spot_rl_experiments/spot_rl/examples/run_pick.py

Prompts

```
['run the robot to navigate to a single goal specified by x,y,theta coordinates', 'run the robot to navigate through multiple waypoints from a YAML config file', 'run the robot to navigate to waypoints then dock automatically after completion', 'run the robot navigation and save trajectory data to a timestamped JSON file', 'parse command line arguments for goal coordinates, waypoints, docking, and trajectory save path', 'run the pick script to make a Spot robot pick up target objects by name', 'parse command line arguments for target object, dont_pick_up, max_episode_steps, and mobile_gaze flags', 'run a Spot robot pick task using RealGazeEnv and the Pick atomic skill controller', 'execute the Pick atomic skill on a Spot robot with a target object goal dictionary', 'construct a gaze configuration for the Pick skill using opts, dont_pick_up, and max_episode_steps', 'run the place skill on a Spot robot by specifying a target x,y,z coordinate in meters', 'run the place skill on a Spot robot using comma-separated waypoint names from a YAML config', "run the place skill with target coordinates relative to the robot's local base frame", 'run the place skill using learned RL policies instead of the Boston Dynamics API', 'parse command-line arguments for place target coordinates, waypoints, local frame flag, and policy usage']
```

Usage

```
{'run_pick_script': 'run the pick script to make a Spot robot pick up target objects by name', 'parse_arguments_parse_arguments': 'parse command line arguments for target object, dont_pick_up, max_episode_steps, and mobile_gaze flags', 'run_pick_with_Spot': 'run a Spot robot pick task using RealGazeEnv and the Pick atomic skill controller', 'execute_Pick_skill': 'execute the Pick atomic skill on a Spot robot with a target object goal dictionary', 'construct_config_for_gaze': 'construct a gaze configuration for the Pick skill using opts, dont_pick_up, and max_episode_steps'}
```

## File: facebookresearch_spot-sim2real/spot_rl_experiments/spot_rl/examples/run_place.py

Prompts

```
['run the robot to navigate to a single goal specified by x,y,theta coordinates', 'run the robot to navigate through multiple waypoints from a YAML config file', 'run the robot to navigate to waypoints then dock automatically after completion', 'run the robot navigation and save trajectory data to a timestamped JSON file', 'parse command line arguments for goal coordinates, waypoints, docking, and trajectory save path', 'run the pick script to make a Spot robot pick up target objects by name', 'parse command line arguments for target object, dont_pick_up, max_episode_steps, and mobile_gaze flags', 'run a Spot robot pick task using RealGazeEnv and the Pick atomic skill controller', 'execute the Pick atomic skill on a Spot robot with a target object goal dictionary', 'construct a gaze configuration for the Pick skill using opts, dont_pick_up, and max_episode_steps', 'run the place skill on a Spot robot by specifying a target x,y,z coordinate in meters', 'run the place skill on a Spot robot using comma-separated waypoint names from a YAML config', "run the place skill with target coordinates relative to the robot's local base frame", 'run the place skill using learned RL policies instead of the Boston Dynamics API', 'parse command-line arguments for place target coordinates, waypoints, local frame flag, and policy usage']
```

Usage

```
{'run_place_with_target': 'run the place skill on a Spot robot by specifying a target x,y,z coordinate in meters', 'run_place_with_waypoints': 'run the place skill on a Spot robot using comma-separated waypoint names from a YAML config', 'run_place_local_frame': "run the place skill with target coordinates relative to the robot's local base frame", 'run_place_with_policies': 'run the place skill using learned RL policies instead of the Boston Dynamics API', 'parse_arguments_place': 'parse command-line arguments for place target coordinates, waypoints, local frame flag, and policy usage'}
```

