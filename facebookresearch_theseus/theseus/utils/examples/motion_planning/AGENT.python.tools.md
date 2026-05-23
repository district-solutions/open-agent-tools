# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/theseus/utils/examples/motion_planning/misc.py

Prompts

```
['create a TrajectoryDataset to load motion planning trajectory data from a dataset directory with SDF and image files', 'use get_all_files to retrieve a dictionary of file paths organized by map type from the dataset', 'use __getitem__ to load a single sample with map tensor, SDF data, and expert trajectory tensors', 'generate trajectory figures to visualize multiple robot paths overlaid on environment maps with optional SDF plots', 'use _add_robot_to_trajectory to overlay robot shapes as circles or triangles along a trajectory path', 'build a ScalarCollisionWeightModel to predict collision weights for motion planning using an order of magnitude neural network', 'build a ScalarCollisionWeightAndCostEpstModel to predict collision weights and safety distance given a robot radius', 'build an InitialTrajectoryModel to generate initial robot trajectories using a learned parabola bend and Gaussian Process sample', 'review the InitialTrajectoryModel forward method that generates curved trajectories from start and goal positions using GP sampling', 'refactor the InitialTrajectoryModel to replace file ID one-hot encoding with a CNN encoder for better generalization across maps', 'create a MotionPlanner with optimizer config and objective parameters for robot trajectory optimization', 'run the motion planner forward pass with input tensors to compute an optimized trajectory', 'get variable values for a straight line trajectory from start to goal pose', 'get the optimized trajectory as a tensor from the motion planner objective variables', 'get the total squared GP and collision errors from the motion planner objective cost functions']
```

Usage

```
{'create_TrajectoryDataset': 'create a TrajectoryDataset to load motion planning trajectory data from a dataset directory with SDF and image files', 'use_TrajectoryDataset_get_all_files': 'use get_all_files to retrieve a dictionary of file paths organized by map type from the dataset', 'use_TrajectoryDataset_getitem': 'use __getitem__ to load a single sample with map tensor, SDF data, and expert trajectory tensors', 'generate_trajectory_figs': 'generate trajectory figures to visualize multiple robot paths overlaid on environment maps with optional SDF plots', 'use_add_robot_to_trajectory': 'use _add_robot_to_trajectory to overlay robot shapes as circles or triangles along a trajectory path'}
```

## File: facebookresearch_theseus/theseus/utils/examples/motion_planning/models.py

Prompts

```
['create a TrajectoryDataset to load motion planning trajectory data from a dataset directory with SDF and image files', 'use get_all_files to retrieve a dictionary of file paths organized by map type from the dataset', 'use __getitem__ to load a single sample with map tensor, SDF data, and expert trajectory tensors', 'generate trajectory figures to visualize multiple robot paths overlaid on environment maps with optional SDF plots', 'use _add_robot_to_trajectory to overlay robot shapes as circles or triangles along a trajectory path', 'build a ScalarCollisionWeightModel to predict collision weights for motion planning using an order of magnitude neural network', 'build a ScalarCollisionWeightAndCostEpstModel to predict collision weights and safety distance given a robot radius', 'build an InitialTrajectoryModel to generate initial robot trajectories using a learned parabola bend and Gaussian Process sample', 'review the InitialTrajectoryModel forward method that generates curved trajectories from start and goal positions using GP sampling', 'refactor the InitialTrajectoryModel to replace file ID one-hot encoding with a CNN encoder for better generalization across maps', 'create a MotionPlanner with optimizer config and objective parameters for robot trajectory optimization', 'run the motion planner forward pass with input tensors to compute an optimized trajectory', 'get variable values for a straight line trajectory from start to goal pose', 'get the optimized trajectory as a tensor from the motion planner objective variables', 'get the total squared GP and collision errors from the motion planner objective cost functions']
```

Usage

```
{'build_ScalarCollisionWeightModel': 'build a ScalarCollisionWeightModel to predict collision weights for motion planning using an order of magnitude neural network', 'build_ScalarCollisionWeightAndCostEpstModel': 'build a ScalarCollisionWeightAndCostEpstModel to predict collision weights and safety distance given a robot radius', 'build_InitialTrajectoryModel': 'build an InitialTrajectoryModel to generate initial robot trajectories using a learned parabola bend and Gaussian Process sample', 'review_InitialTrajectoryModel_forward': 'review the InitialTrajectoryModel forward method that generates curved trajectories from start and goal positions using GP sampling', 'refactor_InitialTrajectoryModel': 'refactor the InitialTrajectoryModel to replace file ID one-hot encoding with a CNN encoder for better generalization across maps'}
```

## File: facebookresearch_theseus/theseus/utils/examples/motion_planning/motion_planner.py

Prompts

```
['create a TrajectoryDataset to load motion planning trajectory data from a dataset directory with SDF and image files', 'use get_all_files to retrieve a dictionary of file paths organized by map type from the dataset', 'use __getitem__ to load a single sample with map tensor, SDF data, and expert trajectory tensors', 'generate trajectory figures to visualize multiple robot paths overlaid on environment maps with optional SDF plots', 'use _add_robot_to_trajectory to overlay robot shapes as circles or triangles along a trajectory path', 'build a ScalarCollisionWeightModel to predict collision weights for motion planning using an order of magnitude neural network', 'build a ScalarCollisionWeightAndCostEpstModel to predict collision weights and safety distance given a robot radius', 'build an InitialTrajectoryModel to generate initial robot trajectories using a learned parabola bend and Gaussian Process sample', 'review the InitialTrajectoryModel forward method that generates curved trajectories from start and goal positions using GP sampling', 'refactor the InitialTrajectoryModel to replace file ID one-hot encoding with a CNN encoder for better generalization across maps', 'create a MotionPlanner with optimizer config and objective parameters for robot trajectory optimization', 'run the motion planner forward pass with input tensors to compute an optimized trajectory', 'get variable values for a straight line trajectory from start to goal pose', 'get the optimized trajectory as a tensor from the motion planner objective variables', 'get the total squared GP and collision errors from the motion planner objective cost functions']
```

Usage

```
{'create_motion_planner': 'create a MotionPlanner with optimizer config and objective parameters for robot trajectory optimization', 'run_motion_planner_forward': 'run the motion planner forward pass with input tensors to compute an optimized trajectory', 'get_straight_line_trajectory': 'get variable values for a straight line trajectory from start to goal pose', 'get_trajectory_tensor': 'get the optimized trajectory as a tensor from the motion planner objective variables', 'get_total_squared_errors': 'get the total squared GP and collision errors from the motion planner objective cost functions'}
```

