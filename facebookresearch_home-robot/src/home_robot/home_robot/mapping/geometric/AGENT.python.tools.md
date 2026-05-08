# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/mapping/geometric/geometric_map_module.py

Prompts

```
['create a GeometricMapModule instance with frame dimensions, camera height, hfov, map size, resolution, and vision range parameters', 'run the forward pass of GeometricMapModule with sequence observations, pose deltas, and initial maps to get map features and updated poses', 'update the local map and agent pose using depth observations, pose deltas, and camera extrinsics via projective geometry', 'update the global map and pose for an environment by copying the local map into the global map at the correct boundaries', 'get combined local and global map features by concatenating local map channels with downsampled global map channels', 'create a GeometricMapState instance with device, num_environments, map_resolution, map_size_cm, and global_downscaling parameters', 'initialize global and local map and sensor pose variables for all environments in GeometricMapState', 'get the local obstacle map as a numpy array for a specific environment index', 'get the 7-dimensional planner pose inputs combining global pose and local map boundaries', 'update the binary goal map for a specific environment with a policy-chosen goal action']
```

Usage

```
{'create_geometric_map_module': 'create a GeometricMapModule instance with frame dimensions, camera height, hfov, map size, resolution, and vision range parameters', 'run_forward_geometric_map': 'run the forward pass of GeometricMapModule with sequence observations, pose deltas, and initial maps to get map features and updated poses', 'update_local_map_and_pose': 'update the local map and agent pose using depth observations, pose deltas, and camera extrinsics via projective geometry', 'update_global_map_and_pose': 'update the global map and pose for an environment by copying the local map into the global map at the correct boundaries', 'get_map_features': 'get combined local and global map features by concatenating local map channels with downsampled global map channels'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/mapping/geometric/geometric_map_state.py

Prompts

```
['create a GeometricMapModule instance with frame dimensions, camera height, hfov, map size, resolution, and vision range parameters', 'run the forward pass of GeometricMapModule with sequence observations, pose deltas, and initial maps to get map features and updated poses', 'update the local map and agent pose using depth observations, pose deltas, and camera extrinsics via projective geometry', 'update the global map and pose for an environment by copying the local map into the global map at the correct boundaries', 'get combined local and global map features by concatenating local map channels with downsampled global map channels', 'create a GeometricMapState instance with device, num_environments, map_resolution, map_size_cm, and global_downscaling parameters', 'initialize global and local map and sensor pose variables for all environments in GeometricMapState', 'get the local obstacle map as a numpy array for a specific environment index', 'get the 7-dimensional planner pose inputs combining global pose and local map boundaries', 'update the binary goal map for a specific environment with a policy-chosen goal action']
```

Usage

```
{'create_geometric_map_state': 'create a GeometricMapState instance with device, num_environments, map_resolution, map_size_cm, and global_downscaling parameters', 'init_map_and_pose': 'initialize global and local map and sensor pose variables for all environments in GeometricMapState', 'get_obstacle_map': 'get the local obstacle map as a numpy array for a specific environment index', 'get_planner_pose_inputs': 'get the 7-dimensional planner pose inputs combining global pose and local map boundaries', 'update_global_goal_for_env': 'update the binary goal map for a specific environment with a policy-chosen goal action'}
```

