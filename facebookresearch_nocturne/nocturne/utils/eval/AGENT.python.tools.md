# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/nocturne/utils/eval/average_displacement.py

Prompts

```
['run compute_average_displacement to evaluate a model against ground truth trajectories in parallel', 'run _average_displacement_impl to compute displacement error for a single trajectory file', 'test compute_average_displacement by loading a model and configs then evaluating on validation trajectories', 'refactor _average_displacement_impl to change the number of simulation steps or goal tolerance threshold', 'review compute_average_displacement to understand how ADE, FDE, collisions, and goal rates are aggregated', 'compute the average collision rate for a model across a directory of trajectory JSON files', 'run the collision rate computation for a single trajectory file using _collision_rate_impl with an optional model', 'run the module as a CLI script to print average collision rates with vehicles and road lines', 'test the collision rate computation by passing a loaded PyTorch model to compute_average_collision_rate', 'review the _collision_rate_impl function to understand how vehicle and edge collisions are detected during simulation', 'compute the number of trajectory segment intersections between pairs of vehicles from a JSON trajectory file', 'run intersection metrics evaluation for a single trajectory file using a loaded model and config', 'compute collision and goal rates binned by intersection count across multiple trajectory files in parallel', 'review the segment intersection detection algorithm that uses bounding box filtering and CCW cross product checks', 'refactor the intersection metrics implementation to support controlling a configurable number of vehicles', 'compute the average goal reaching rate for a model across trajectory files in a directory', 'run the goal reaching rate evaluation on a directory of tfrecord JSON trajectory files', 'test the internal goal reaching rate implementation for a single trajectory path with an optional model', 'review the compute_average_goal_reaching_rate function that accepts a directory path or list of paths and returns the mean rate', 'refactor the _goal_reaching_rate_impl function to customize simulation steps, step time, or goal proximity threshold']
```

Usage

```
{'run_compute_average_displacement': 'run compute_average_displacement to evaluate a model against ground truth trajectories in parallel', 'run_average_displacement_impl': 'run _average_displacement_impl to compute displacement error for a single trajectory file', 'test_compute_average_displacement': 'test compute_average_displacement by loading a model and configs then evaluating on validation trajectories', 'refactor_average_displacement_impl': 'refactor _average_displacement_impl to change the number of simulation steps or goal tolerance threshold', 'review_compute_average_displacement': 'review compute_average_displacement to understand how ADE, FDE, collisions, and goal rates are aggregated'}
```

## File: facebookresearch_nocturne/nocturne/utils/eval/collision_rate.py

Prompts

```
['run compute_average_displacement to evaluate a model against ground truth trajectories in parallel', 'run _average_displacement_impl to compute displacement error for a single trajectory file', 'test compute_average_displacement by loading a model and configs then evaluating on validation trajectories', 'refactor _average_displacement_impl to change the number of simulation steps or goal tolerance threshold', 'review compute_average_displacement to understand how ADE, FDE, collisions, and goal rates are aggregated', 'compute the average collision rate for a model across a directory of trajectory JSON files', 'run the collision rate computation for a single trajectory file using _collision_rate_impl with an optional model', 'run the module as a CLI script to print average collision rates with vehicles and road lines', 'test the collision rate computation by passing a loaded PyTorch model to compute_average_collision_rate', 'review the _collision_rate_impl function to understand how vehicle and edge collisions are detected during simulation', 'compute the number of trajectory segment intersections between pairs of vehicles from a JSON trajectory file', 'run intersection metrics evaluation for a single trajectory file using a loaded model and config', 'compute collision and goal rates binned by intersection count across multiple trajectory files in parallel', 'review the segment intersection detection algorithm that uses bounding box filtering and CCW cross product checks', 'refactor the intersection metrics implementation to support controlling a configurable number of vehicles', 'compute the average goal reaching rate for a model across trajectory files in a directory', 'run the goal reaching rate evaluation on a directory of tfrecord JSON trajectory files', 'test the internal goal reaching rate implementation for a single trajectory path with an optional model', 'review the compute_average_goal_reaching_rate function that accepts a directory path or list of paths and returns the mean rate', 'refactor the _goal_reaching_rate_impl function to customize simulation steps, step time, or goal proximity threshold']
```

Usage

```
{'compute_average_collision_rate': 'compute the average collision rate for a model across a directory of trajectory JSON files', 'run_collision_rate_single_trajectory': 'run the collision rate computation for a single trajectory file using _collision_rate_impl with an optional model', 'run_collision_rate_cli': 'run the module as a CLI script to print average collision rates with vehicles and road lines', 'test_collision_rate_with_model': 'test the collision rate computation by passing a loaded PyTorch model to compute_average_collision_rate', 'review_collision_rate_impl': 'review the _collision_rate_impl function to understand how vehicle and edge collisions are detected during simulation'}
```

## File: facebookresearch_nocturne/nocturne/utils/eval/goal_by_intersection.py

Prompts

```
['run compute_average_displacement to evaluate a model against ground truth trajectories in parallel', 'run _average_displacement_impl to compute displacement error for a single trajectory file', 'test compute_average_displacement by loading a model and configs then evaluating on validation trajectories', 'refactor _average_displacement_impl to change the number of simulation steps or goal tolerance threshold', 'review compute_average_displacement to understand how ADE, FDE, collisions, and goal rates are aggregated', 'compute the average collision rate for a model across a directory of trajectory JSON files', 'run the collision rate computation for a single trajectory file using _collision_rate_impl with an optional model', 'run the module as a CLI script to print average collision rates with vehicles and road lines', 'test the collision rate computation by passing a loaded PyTorch model to compute_average_collision_rate', 'review the _collision_rate_impl function to understand how vehicle and edge collisions are detected during simulation', 'compute the number of trajectory segment intersections between pairs of vehicles from a JSON trajectory file', 'run intersection metrics evaluation for a single trajectory file using a loaded model and config', 'compute collision and goal rates binned by intersection count across multiple trajectory files in parallel', 'review the segment intersection detection algorithm that uses bounding box filtering and CCW cross product checks', 'refactor the intersection metrics implementation to support controlling a configurable number of vehicles', 'compute the average goal reaching rate for a model across trajectory files in a directory', 'run the goal reaching rate evaluation on a directory of tfrecord JSON trajectory files', 'test the internal goal reaching rate implementation for a single trajectory path with an optional model', 'review the compute_average_goal_reaching_rate function that accepts a directory path or list of paths and returns the mean rate', 'refactor the _goal_reaching_rate_impl function to customize simulation steps, step time, or goal proximity threshold']
```

Usage

```
{'compute_expert_intersections': 'compute the number of trajectory segment intersections between pairs of vehicles from a JSON trajectory file', 'run_intersection_metrics': 'run intersection metrics evaluation for a single trajectory file using a loaded model and config', 'compute_metrics_by_intersection': 'compute collision and goal rates binned by intersection count across multiple trajectory files in parallel', 'review_compute_expert_intersections': 'review the segment intersection detection algorithm that uses bounding box filtering and CCW cross product checks', 'refactor_intersection_metrics_impl': 'refactor the intersection metrics implementation to support controlling a configurable number of vehicles'}
```

## File: facebookresearch_nocturne/nocturne/utils/eval/goal_reaching_rate.py

Prompts

```
['run compute_average_displacement to evaluate a model against ground truth trajectories in parallel', 'run _average_displacement_impl to compute displacement error for a single trajectory file', 'test compute_average_displacement by loading a model and configs then evaluating on validation trajectories', 'refactor _average_displacement_impl to change the number of simulation steps or goal tolerance threshold', 'review compute_average_displacement to understand how ADE, FDE, collisions, and goal rates are aggregated', 'compute the average collision rate for a model across a directory of trajectory JSON files', 'run the collision rate computation for a single trajectory file using _collision_rate_impl with an optional model', 'run the module as a CLI script to print average collision rates with vehicles and road lines', 'test the collision rate computation by passing a loaded PyTorch model to compute_average_collision_rate', 'review the _collision_rate_impl function to understand how vehicle and edge collisions are detected during simulation', 'compute the number of trajectory segment intersections between pairs of vehicles from a JSON trajectory file', 'run intersection metrics evaluation for a single trajectory file using a loaded model and config', 'compute collision and goal rates binned by intersection count across multiple trajectory files in parallel', 'review the segment intersection detection algorithm that uses bounding box filtering and CCW cross product checks', 'refactor the intersection metrics implementation to support controlling a configurable number of vehicles', 'compute the average goal reaching rate for a model across trajectory files in a directory', 'run the goal reaching rate evaluation on a directory of tfrecord JSON trajectory files', 'test the internal goal reaching rate implementation for a single trajectory path with an optional model', 'review the compute_average_goal_reaching_rate function that accepts a directory path or list of paths and returns the mean rate', 'refactor the _goal_reaching_rate_impl function to customize simulation steps, step time, or goal proximity threshold']
```

Usage

```
{'compute_goal_reaching_rate': 'compute the average goal reaching rate for a model across trajectory files in a directory', 'run_goal_reaching_evaluation': 'run the goal reaching rate evaluation on a directory of tfrecord JSON trajectory files', 'test_goal_reaching_rate_impl': 'test the internal goal reaching rate implementation for a single trajectory path with an optional model', 'review_compute_average_goal_reaching_rate': 'review the compute_average_goal_reaching_rate function that accepts a directory path or list of paths and returns the mean rate', 'refactor_goal_reaching_rate_impl': 'refactor the _goal_reaching_rate_impl function to customize simulation steps, step time, or goal proximity threshold'}
```

