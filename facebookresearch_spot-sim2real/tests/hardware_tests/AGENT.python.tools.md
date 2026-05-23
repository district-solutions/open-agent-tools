# Agent Python Tools

- repo: facebookresearch/spot-sim2real
- repo_uri: https://github.com/facebookresearch/spot-sim2real

## File: facebookresearch_spot-sim2real/tests/hardware_tests/test_gaze_env.py

Prompts

```
['test the static gaze Pick skill execution on a Spot robot for target objects', 'test the mobile gaze Pick skill execution on a Spot robot for target objects', 'run init_test_config to construct a gaze config with dont_pick_up and max_episode_steps', 'run validate_pick_feedbacks to assert all pick feedbacks returned success status and correct message', 'review the test_gaze_env module to understand static and mobile gaze hardware test patterns', 'test robot navigation along a square path with three waypoints using the Spot hardware', 'compute average and standard deviation of time taken to reach each waypoint across trajectories', 'compute average and standard deviation of steps taken to reach each waypoint across trajectories', 'extract robot poses, timestamps, and step counts from navigation trajectory data', 'validate navigation trajectories against reference data using spatial, temporal, and step-based assertions', 'test the Place skill with policy-based execution on hardware robot using global waypoints', 'test the Place skill without policy execution on hardware robot using multiple waypoints', 'test the Place skill with policy-based execution on hardware robot using local waypoints', 'test the Place skill without policy execution on hardware robot using local waypoints', 'validate that all place feedback tuples return success status and correct message']
```

Usage

```
{'test_gaze': 'test the static gaze Pick skill execution on a Spot robot for target objects', 'test_mobile_gaze': 'test the mobile gaze Pick skill execution on a Spot robot for target objects', 'run_init_test_config': 'run init_test_config to construct a gaze config with dont_pick_up and max_episode_steps', 'run_validate_pick_feedbacks': 'run validate_pick_feedbacks to assert all pick feedbacks returned success status and correct message', 'review_test_gaze_env': 'review the test_gaze_env module to understand static and mobile gaze hardware test patterns'}
```

## File: facebookresearch_spot-sim2real/tests/hardware_tests/test_nav_env.py

Prompts

```
['test the static gaze Pick skill execution on a Spot robot for target objects', 'test the mobile gaze Pick skill execution on a Spot robot for target objects', 'run init_test_config to construct a gaze config with dont_pick_up and max_episode_steps', 'run validate_pick_feedbacks to assert all pick feedbacks returned success status and correct message', 'review the test_gaze_env module to understand static and mobile gaze hardware test patterns', 'test robot navigation along a square path with three waypoints using the Spot hardware', 'compute average and standard deviation of time taken to reach each waypoint across trajectories', 'compute average and standard deviation of steps taken to reach each waypoint across trajectories', 'extract robot poses, timestamps, and step counts from navigation trajectory data', 'validate navigation trajectories against reference data using spatial, temporal, and step-based assertions', 'test the Place skill with policy-based execution on hardware robot using global waypoints', 'test the Place skill without policy execution on hardware robot using multiple waypoints', 'test the Place skill with policy-based execution on hardware robot using local waypoints', 'test the Place skill without policy execution on hardware robot using local waypoints', 'validate that all place feedback tuples return success status and correct message']
```

Usage

```
{'test_nav_square': 'test robot navigation along a square path with three waypoints using the Spot hardware', 'compute_avg_and_std_time': 'compute average and standard deviation of time taken to reach each waypoint across trajectories', 'compute_avg_and_std_steps': 'compute average and standard deviation of steps taken to reach each waypoint across trajectories', 'extract_goal_poses_timestamps_steps_from_traj': 'extract robot poses, timestamps, and step counts from navigation trajectory data', 'validate_nav_trajectories': 'validate navigation trajectories against reference data using spatial, temporal, and step-based assertions'}
```

## File: facebookresearch_spot-sim2real/tests/hardware_tests/test_place_env.py

Prompts

```
['test the static gaze Pick skill execution on a Spot robot for target objects', 'test the mobile gaze Pick skill execution on a Spot robot for target objects', 'run init_test_config to construct a gaze config with dont_pick_up and max_episode_steps', 'run validate_pick_feedbacks to assert all pick feedbacks returned success status and correct message', 'review the test_gaze_env module to understand static and mobile gaze hardware test patterns', 'test robot navigation along a square path with three waypoints using the Spot hardware', 'compute average and standard deviation of time taken to reach each waypoint across trajectories', 'compute average and standard deviation of steps taken to reach each waypoint across trajectories', 'extract robot poses, timestamps, and step counts from navigation trajectory data', 'validate navigation trajectories against reference data using spatial, temporal, and step-based assertions', 'test the Place skill with policy-based execution on hardware robot using global waypoints', 'test the Place skill without policy execution on hardware robot using multiple waypoints', 'test the Place skill with policy-based execution on hardware robot using local waypoints', 'test the Place skill without policy execution on hardware robot using local waypoints', 'validate that all place feedback tuples return success status and correct message']
```

Usage

```
{'test_place_with_policy': 'test the Place skill with policy-based execution on hardware robot using global waypoints', 'test_place_without_policy': 'test the Place skill without policy execution on hardware robot using multiple waypoints', 'test_place_local_with_policy': 'test the Place skill with policy-based execution on hardware robot using local waypoints', 'test_place_local_without_policy': 'test the Place skill without policy execution on hardware robot using local waypoints', 'validate_place_feedbacks': 'validate that all place feedback tuples return success status and correct message'}
```

