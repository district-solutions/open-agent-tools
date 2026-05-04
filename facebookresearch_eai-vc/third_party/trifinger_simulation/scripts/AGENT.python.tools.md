# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/trifinger_simulation/scripts/playback_data.py

Prompts

```
['run playback of single finger joint position data from a pickle file with pyBullet visualization', 'run playback of three finger joint position data from three pickle files with pyBullet visualization', 'run the CLI tool with a finger type and data file arguments to start playback', 'review the trifinger_goal_space_transforms function that computes rotated tip goals for trifingerone and trifingeredu', 'refactor the main_finger function to support custom reset logic or different visualization backends', 'run cProfile on trifingerone, trifingeredu, and trifingerpro with and without visualization enabled', 'create a SimFinger instance and apply random torque actions over a specified number of timesteps', 'profile a specific TriFinger variant with visualization enabled to measure rendering overhead', 'profile a specific TriFinger variant with visualization disabled to measure pure simulation performance', 'load cProfile stats files and print the top 3 functions sorted by total time', 'run the trifingerpro simulation model with position control and collision visualization', 'visualize collision contact points on the trifingerpro simulation using cube markers', 'create a SimFinger instance with trifingerpro type and visualization enabled', 'append a position-based desired action to the trifingerpro simulation loop', 'get the observation state of the trifingerpro simulation at a given timestamp']
```

Usage

```
{'run_single_finger_playback': 'run playback of single finger joint position data from a pickle file with pyBullet visualization', 'run_trifinger_playback': 'run playback of three finger joint position data from three pickle files with pyBullet visualization', 'run_main_cli': 'run the CLI tool with a finger type and data file arguments to start playback', 'review_trifinger_goal_space_transforms': 'review the trifinger_goal_space_transforms function that computes rotated tip goals for trifingerone and trifingeredu', 'refactor_main_finger': 'refactor the main_finger function to support custom reset logic or different visualization backends'}
```

## File: facebookresearch_eai-vc/third_party/trifinger_simulation/scripts/profiling.py

Prompts

```
['run playback of single finger joint position data from a pickle file with pyBullet visualization', 'run playback of three finger joint position data from three pickle files with pyBullet visualization', 'run the CLI tool with a finger type and data file arguments to start playback', 'review the trifinger_goal_space_transforms function that computes rotated tip goals for trifingerone and trifingeredu', 'refactor the main_finger function to support custom reset logic or different visualization backends', 'run cProfile on trifingerone, trifingeredu, and trifingerpro with and without visualization enabled', 'create a SimFinger instance and apply random torque actions over a specified number of timesteps', 'profile a specific TriFinger variant with visualization enabled to measure rendering overhead', 'profile a specific TriFinger variant with visualization disabled to measure pure simulation performance', 'load cProfile stats files and print the top 3 functions sorted by total time', 'run the trifingerpro simulation model with position control and collision visualization', 'visualize collision contact points on the trifingerpro simulation using cube markers', 'create a SimFinger instance with trifingerpro type and visualization enabled', 'append a position-based desired action to the trifingerpro simulation loop', 'get the observation state of the trifingerpro simulation at a given timestamp']
```

Usage

```
{'run_profiling_all_fingers': 'run cProfile on trifingerone, trifingeredu, and trifingerpro with and without visualization enabled', 'execute_random_motion': 'create a SimFinger instance and apply random torque actions over a specified number of timesteps', 'profile_finger_with_visualization': 'profile a specific TriFinger variant with visualization enabled to measure rendering overhead', 'profile_finger_without_visualization': 'profile a specific TriFinger variant with visualization disabled to measure pure simulation performance', 'print_profile_stats': 'load cProfile stats files and print the top 3 functions sorted by total time'}
```

## File: facebookresearch_eai-vc/third_party/trifinger_simulation/scripts/trifingerpro_model_test.py

Prompts

```
['run playback of single finger joint position data from a pickle file with pyBullet visualization', 'run playback of three finger joint position data from three pickle files with pyBullet visualization', 'run the CLI tool with a finger type and data file arguments to start playback', 'review the trifinger_goal_space_transforms function that computes rotated tip goals for trifingerone and trifingeredu', 'refactor the main_finger function to support custom reset logic or different visualization backends', 'run cProfile on trifingerone, trifingeredu, and trifingerpro with and without visualization enabled', 'create a SimFinger instance and apply random torque actions over a specified number of timesteps', 'profile a specific TriFinger variant with visualization enabled to measure rendering overhead', 'profile a specific TriFinger variant with visualization disabled to measure pure simulation performance', 'load cProfile stats files and print the top 3 functions sorted by total time', 'run the trifingerpro simulation model with position control and collision visualization', 'visualize collision contact points on the trifingerpro simulation using cube markers', 'create a SimFinger instance with trifingerpro type and visualization enabled', 'append a position-based desired action to the trifingerpro simulation loop', 'get the observation state of the trifingerpro simulation at a given timestamp']
```

Usage

```
{'run_trifingerpro_simulation': 'run the trifingerpro simulation model with position control and collision visualization', 'visualize_collisions': 'visualize collision contact points on the trifingerpro simulation using cube markers', 'create_simfinger': 'create a SimFinger instance with trifingerpro type and visualization enabled', 'append_desired_action': 'append a position-based desired action to the trifingerpro simulation loop', 'get_observation': 'get the observation state of the trifingerpro simulation at a given timestamp'}
```

