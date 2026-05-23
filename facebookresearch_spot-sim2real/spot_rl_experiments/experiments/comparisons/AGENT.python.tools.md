# Agent Python Tools

- repo: facebookresearch/spot-sim2real
- repo_uri: https://github.com/facebookresearch/spot-sim2real

## File: facebookresearch_spot-sim2real/spot_rl_experiments/experiments/comparisons/nav_compare.py

Prompts

```
['run the navigation comparison script with a route index to compare learned vs BD API navigation', 'run baseline navigation using BD API set_base_position to move the robot to a goal waypoint', 'run learned navigation using a trained policy to navigate the robot to a goal waypoint', 'run the return to start function to move the robot back to its starting waypoint', 'run the main comparison loop that executes 3 episodes each of learned and baseline navigation']
```

Usage

```
{'run_nav_compare': 'run the navigation comparison script with a route index to compare learned vs BD API navigation', 'run_baseline_navigate': 'run baseline navigation using BD API set_base_position to move the robot to a goal waypoint', 'run_learned_navigate': 'run learned navigation using a trained policy to navigate the robot to a goal waypoint', 'run_return_to_start': 'run the return to start function to move the robot back to its starting waypoint', 'run_main': 'run the main comparison loop that executes 3 episodes each of learned and baseline navigation'}
```

