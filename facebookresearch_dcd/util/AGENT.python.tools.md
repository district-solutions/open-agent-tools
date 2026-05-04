# Agent Python Tools

- repo: facebookresearch/dcd
- repo_uri: https://github.com/facebookresearch/dcd

## File: facebookresearch_dcd/util/filewriter.py

Prompts

```
['create a FileWriter instance to log experiment metrics to CSV files in a specified directory', 'log a dictionary of key-value metrics to the experiment CSV log file with automatic tick tracking', 'gather git commit info, branch, slurm environment variables, and system env into a metadata dictionary', 'log level weight arrays and track new seed indices to CSV when recording seed diffs is enabled', 'close the FileWriter, update end date and success status, and persist metadata to a JSON file', 'calculate polygon complexity metrics from a list of coordinate points using default coefficients', 'calculate polygon complexity with custom amplitude and convexity coefficients from coordinate points', 'get the normalized notch count for a Shapely Polygon object to measure angular complexity', 'get polygon complexity statistics including area, perimeter, amplitude, convexity, and notches from a GeoDataFrame', 'review the complexity function that computes polygon complexity metrics from coordinate points', 'create a PPO RL agent with actor-critic model and rollout storage for a given environment', 'create a neural network model for a MultiGrid, CarRacing, or BipedalWalker environment agent', 'create a MultigridNetwork model for a MultiGrid environment with optional global critic or policy', 'create a CarRacingNetwork or CarRacingBezierAdversaryEnvNetwork model for a CarRacing environment', 'create a BipedalWalker student or adversary policy model with optional LSTM recurrence', 'create a UnionFind instance with an initial list of elements to manage disjoint sets', 'union two elements in a UnionFind instance to merge their disjoint sets into one', 'find the root index of the disjoint set containing a given element in a UnionFind', 'check whether two elements are connected and belong to the same component in a UnionFind', 'get all connected components as a list of sets from a UnionFind instance']
```

Usage

```
{'create_FileWriter': 'create a FileWriter instance to log experiment metrics to CSV files in a specified directory', 'log_metrics_with_FileWriter': 'log a dictionary of key-value metrics to the experiment CSV log file with automatic tick tracking', 'gather_git_and_slurm_metadata': 'gather git commit info, branch, slurm environment variables, and system env into a metadata dictionary', 'log_level_weights_and_seeds': 'log level weight arrays and track new seed indices to CSV when recording seed diffs is enabled', 'close_FileWriter_and_save_metadata': 'close the FileWriter, update end date and success status, and persist metadata to a JSON file'}
```

## File: facebookresearch_dcd/util/geo_complexity.py

Prompts

```
['create a FileWriter instance to log experiment metrics to CSV files in a specified directory', 'log a dictionary of key-value metrics to the experiment CSV log file with automatic tick tracking', 'gather git commit info, branch, slurm environment variables, and system env into a metadata dictionary', 'log level weight arrays and track new seed indices to CSV when recording seed diffs is enabled', 'close the FileWriter, update end date and success status, and persist metadata to a JSON file', 'calculate polygon complexity metrics from a list of coordinate points using default coefficients', 'calculate polygon complexity with custom amplitude and convexity coefficients from coordinate points', 'get the normalized notch count for a Shapely Polygon object to measure angular complexity', 'get polygon complexity statistics including area, perimeter, amplitude, convexity, and notches from a GeoDataFrame', 'review the complexity function that computes polygon complexity metrics from coordinate points', 'create a PPO RL agent with actor-critic model and rollout storage for a given environment', 'create a neural network model for a MultiGrid, CarRacing, or BipedalWalker environment agent', 'create a MultigridNetwork model for a MultiGrid environment with optional global critic or policy', 'create a CarRacingNetwork or CarRacingBezierAdversaryEnvNetwork model for a CarRacing environment', 'create a BipedalWalker student or adversary policy model with optional LSTM recurrence', 'create a UnionFind instance with an initial list of elements to manage disjoint sets', 'union two elements in a UnionFind instance to merge their disjoint sets into one', 'find the root index of the disjoint set containing a given element in a UnionFind', 'check whether two elements are connected and belong to the same component in a UnionFind', 'get all connected components as a list of sets from a UnionFind instance']
```

Usage

```
{'calculate_complexity_from_points': 'calculate polygon complexity metrics from a list of coordinate points using default coefficients', 'calculate_complexity_custom_coefficients': 'calculate polygon complexity with custom amplitude and convexity coefficients from coordinate points', 'get_notches_normalized': 'get the normalized notch count for a Shapely Polygon object to measure angular complexity', 'get_stats_geodataframe': 'get polygon complexity statistics including area, perimeter, amplitude, convexity, and notches from a GeoDataFrame', 'review_complexity_function': 'review the complexity function that computes polygon complexity metrics from coordinate points'}
```

## File: facebookresearch_dcd/util/make_agent.py

Prompts

```
['create a FileWriter instance to log experiment metrics to CSV files in a specified directory', 'log a dictionary of key-value metrics to the experiment CSV log file with automatic tick tracking', 'gather git commit info, branch, slurm environment variables, and system env into a metadata dictionary', 'log level weight arrays and track new seed indices to CSV when recording seed diffs is enabled', 'close the FileWriter, update end date and success status, and persist metadata to a JSON file', 'calculate polygon complexity metrics from a list of coordinate points using default coefficients', 'calculate polygon complexity with custom amplitude and convexity coefficients from coordinate points', 'get the normalized notch count for a Shapely Polygon object to measure angular complexity', 'get polygon complexity statistics including area, perimeter, amplitude, convexity, and notches from a GeoDataFrame', 'review the complexity function that computes polygon complexity metrics from coordinate points', 'create a PPO RL agent with actor-critic model and rollout storage for a given environment', 'create a neural network model for a MultiGrid, CarRacing, or BipedalWalker environment agent', 'create a MultigridNetwork model for a MultiGrid environment with optional global critic or policy', 'create a CarRacingNetwork or CarRacingBezierAdversaryEnvNetwork model for a CarRacing environment', 'create a BipedalWalker student or adversary policy model with optional LSTM recurrence', 'create a UnionFind instance with an initial list of elements to manage disjoint sets', 'union two elements in a UnionFind instance to merge their disjoint sets into one', 'find the root index of the disjoint set containing a given element in a UnionFind', 'check whether two elements are connected and belong to the same component in a UnionFind', 'get all connected components as a list of sets from a UnionFind instance']
```

Usage

```
{'create_make_agent': 'create a PPO RL agent with actor-critic model and rollout storage for a given environment', 'create_model_for_env_agent': 'create a neural network model for a MultiGrid, CarRacing, or BipedalWalker environment agent', 'create_model_for_multigrid_agent': 'create a MultigridNetwork model for a MultiGrid environment with optional global critic or policy', 'create_model_for_car_racing_agent': 'create a CarRacingNetwork or CarRacingBezierAdversaryEnvNetwork model for a CarRacing environment', 'create_model_for_bipedalwalker_agent': 'create a BipedalWalker student or adversary policy model with optional LSTM recurrence'}
```

## File: facebookresearch_dcd/util/unionfind.py

Prompts

```
['create a FileWriter instance to log experiment metrics to CSV files in a specified directory', 'log a dictionary of key-value metrics to the experiment CSV log file with automatic tick tracking', 'gather git commit info, branch, slurm environment variables, and system env into a metadata dictionary', 'log level weight arrays and track new seed indices to CSV when recording seed diffs is enabled', 'close the FileWriter, update end date and success status, and persist metadata to a JSON file', 'calculate polygon complexity metrics from a list of coordinate points using default coefficients', 'calculate polygon complexity with custom amplitude and convexity coefficients from coordinate points', 'get the normalized notch count for a Shapely Polygon object to measure angular complexity', 'get polygon complexity statistics including area, perimeter, amplitude, convexity, and notches from a GeoDataFrame', 'review the complexity function that computes polygon complexity metrics from coordinate points', 'create a PPO RL agent with actor-critic model and rollout storage for a given environment', 'create a neural network model for a MultiGrid, CarRacing, or BipedalWalker environment agent', 'create a MultigridNetwork model for a MultiGrid environment with optional global critic or policy', 'create a CarRacingNetwork or CarRacingBezierAdversaryEnvNetwork model for a CarRacing environment', 'create a BipedalWalker student or adversary policy model with optional LSTM recurrence', 'create a UnionFind instance with an initial list of elements to manage disjoint sets', 'union two elements in a UnionFind instance to merge their disjoint sets into one', 'find the root index of the disjoint set containing a given element in a UnionFind', 'check whether two elements are connected and belong to the same component in a UnionFind', 'get all connected components as a list of sets from a UnionFind instance']
```

Usage

```
{'create_unionfind_instance': 'create a UnionFind instance with an initial list of elements to manage disjoint sets', 'union_two_elements': 'union two elements in a UnionFind instance to merge their disjoint sets into one', 'find_root_of_element': 'find the root index of the disjoint set containing a given element in a UnionFind', 'check_connected_elements': 'check whether two elements are connected and belong to the same component in a UnionFind', 'get_all_components': 'get all connected components as a list of sets from a UnionFind instance'}
```

