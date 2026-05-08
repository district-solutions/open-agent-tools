# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot_hw/home_robot_hw/utils/collector.py

Prompts

```
['create a RosMapDataCollector instance with a robot connection and optional semantic sensor for 3D spatial-semantic map collection', 'step the RosMapDataCollector to capture a single observation and add it to the voxel map', 'get the SparseVoxelMapNavigationSpace from a RosMapDataCollector for motion planning with hardcoded Stretch parameters', 'get the 2D obstacle map from a RosMapDataCollector for low-level motion planning and frontier-based exploration', 'get the XYZ coordinates and RGB colors from the aggregated voxel point cloud in the collector', 'load a config for real world experiments using the default eval.yaml preset path', 'load a config for real world experiments from a custom YAML config file path', 'load a config with visualization enabled for real world robot experiments', 'load a SLAP config for real world experiments from a specified YAML config path', 'review the load_config function to understand how it sets NUM_ENVIRONMENTS and VISUALIZE defaults', 'run a gRPC server on port 8085 for real-world robot pick and place evaluation', 'run the evaluation server with test pick mode enabled for grasping tests', 'run the evaluation server in dry run mode without executing real robot actions', 'run the evaluation server with map visualization enabled for debugging navigation', 'run the evaluation server and reset the robot navigation to origin position', 'detect and grasp a named object like a cup using the GraspPlanner try_grasping method', 'detect an object and place it at a different location using the GraspPlanner try_placing method', 'create a trajectory plan to reach a given SE(3) grasp pose using the plan_to_grasp method', 'execute a predefined grasp trajectory to a 4x4 pose matrix using the try_executing_grasp method', 'compute the theta x and y angles of a grasp pose from vertical using divergence_from_vertical_grasp']
```

Usage

```
{'create_RosMapDataCollector': 'create a RosMapDataCollector instance with a robot connection and optional semantic sensor for 3D spatial-semantic map collection', 'step_RosMapDataCollector': 'step the RosMapDataCollector to capture a single observation and add it to the voxel map', 'get_planning_space_RosMapDataCollector': 'get the SparseVoxelMapNavigationSpace from a RosMapDataCollector for motion planning with hardcoded Stretch parameters', 'get_2d_map_RosMapDataCollector': 'get the 2D obstacle map from a RosMapDataCollector for low-level motion planning and frontier-based exploration', 'get_xyz_rgb_RosMapDataCollector': 'get the XYZ coordinates and RGB colors from the aggregated voxel point cloud in the collector'}
```

## File: facebookresearch_home-robot/src/home_robot_hw/home_robot_hw/utils/config.py

Prompts

```
['create a RosMapDataCollector instance with a robot connection and optional semantic sensor for 3D spatial-semantic map collection', 'step the RosMapDataCollector to capture a single observation and add it to the voxel map', 'get the SparseVoxelMapNavigationSpace from a RosMapDataCollector for motion planning with hardcoded Stretch parameters', 'get the 2D obstacle map from a RosMapDataCollector for low-level motion planning and frontier-based exploration', 'get the XYZ coordinates and RGB colors from the aggregated voxel point cloud in the collector', 'load a config for real world experiments using the default eval.yaml preset path', 'load a config for real world experiments from a custom YAML config file path', 'load a config with visualization enabled for real world robot experiments', 'load a SLAP config for real world experiments from a specified YAML config path', 'review the load_config function to understand how it sets NUM_ENVIRONMENTS and VISUALIZE defaults', 'run a gRPC server on port 8085 for real-world robot pick and place evaluation', 'run the evaluation server with test pick mode enabled for grasping tests', 'run the evaluation server in dry run mode without executing real robot actions', 'run the evaluation server with map visualization enabled for debugging navigation', 'run the evaluation server and reset the robot navigation to origin position', 'detect and grasp a named object like a cup using the GraspPlanner try_grasping method', 'detect an object and place it at a different location using the GraspPlanner try_placing method', 'create a trajectory plan to reach a given SE(3) grasp pose using the plan_to_grasp method', 'execute a predefined grasp trajectory to a 4x4 pose matrix using the try_executing_grasp method', 'compute the theta x and y angles of a grasp pose from vertical using divergence_from_vertical_grasp']
```

Usage

```
{'load_config_default': 'load a config for real world experiments using the default eval.yaml preset path', 'load_config_custom_path': 'load a config for real world experiments from a custom YAML config file path', 'load_config_visualize': 'load a config with visualization enabled for real world robot experiments', 'load_slap_config': 'load a SLAP config for real world experiments from a specified YAML config path', 'review_load_config': 'review the load_config function to understand how it sets NUM_ENVIRONMENTS and VISUALIZE defaults'}
```

## File: facebookresearch_home-robot/src/home_robot_hw/home_robot_hw/utils/eval.py

Prompts

```
['create a RosMapDataCollector instance with a robot connection and optional semantic sensor for 3D spatial-semantic map collection', 'step the RosMapDataCollector to capture a single observation and add it to the voxel map', 'get the SparseVoxelMapNavigationSpace from a RosMapDataCollector for motion planning with hardcoded Stretch parameters', 'get the 2D obstacle map from a RosMapDataCollector for low-level motion planning and frontier-based exploration', 'get the XYZ coordinates and RGB colors from the aggregated voxel point cloud in the collector', 'load a config for real world experiments using the default eval.yaml preset path', 'load a config for real world experiments from a custom YAML config file path', 'load a config with visualization enabled for real world robot experiments', 'load a SLAP config for real world experiments from a specified YAML config path', 'review the load_config function to understand how it sets NUM_ENVIRONMENTS and VISUALIZE defaults', 'run a gRPC server on port 8085 for real-world robot pick and place evaluation', 'run the evaluation server with test pick mode enabled for grasping tests', 'run the evaluation server in dry run mode without executing real robot actions', 'run the evaluation server with map visualization enabled for debugging navigation', 'run the evaluation server and reset the robot navigation to origin position', 'detect and grasp a named object like a cup using the GraspPlanner try_grasping method', 'detect an object and place it at a different location using the GraspPlanner try_placing method', 'create a trajectory plan to reach a given SE(3) grasp pose using the plan_to_grasp method', 'execute a predefined grasp trajectory to a 4x4 pose matrix using the try_executing_grasp method', 'compute the theta x and y angles of a grasp pose from vertical using divergence_from_vertical_grasp']
```

Usage

```
{'run_grpc_eval_server': 'run a gRPC server on port 8085 for real-world robot pick and place evaluation', 'run_eval_with_test_pick': 'run the evaluation server with test pick mode enabled for grasping tests', 'run_eval_with_dry_run': 'run the evaluation server in dry run mode without executing real robot actions', 'run_eval_with_visualize_maps': 'run the evaluation server with map visualization enabled for debugging navigation', 'run_eval_with_reset_nav': 'run the evaluation server and reset the robot navigation to origin position'}
```

## File: facebookresearch_home-robot/src/home_robot_hw/home_robot_hw/utils/grasping.py

Prompts

```
['create a RosMapDataCollector instance with a robot connection and optional semantic sensor for 3D spatial-semantic map collection', 'step the RosMapDataCollector to capture a single observation and add it to the voxel map', 'get the SparseVoxelMapNavigationSpace from a RosMapDataCollector for motion planning with hardcoded Stretch parameters', 'get the 2D obstacle map from a RosMapDataCollector for low-level motion planning and frontier-based exploration', 'get the XYZ coordinates and RGB colors from the aggregated voxel point cloud in the collector', 'load a config for real world experiments using the default eval.yaml preset path', 'load a config for real world experiments from a custom YAML config file path', 'load a config with visualization enabled for real world robot experiments', 'load a SLAP config for real world experiments from a specified YAML config path', 'review the load_config function to understand how it sets NUM_ENVIRONMENTS and VISUALIZE defaults', 'run a gRPC server on port 8085 for real-world robot pick and place evaluation', 'run the evaluation server with test pick mode enabled for grasping tests', 'run the evaluation server in dry run mode without executing real robot actions', 'run the evaluation server with map visualization enabled for debugging navigation', 'run the evaluation server and reset the robot navigation to origin position', 'detect and grasp a named object like a cup using the GraspPlanner try_grasping method', 'detect an object and place it at a different location using the GraspPlanner try_placing method', 'create a trajectory plan to reach a given SE(3) grasp pose using the plan_to_grasp method', 'execute a predefined grasp trajectory to a 4x4 pose matrix using the try_executing_grasp method', 'compute the theta x and y angles of a grasp pose from vertical using divergence_from_vertical_grasp']
```

Usage

```
{'try_grasping_object': 'detect and grasp a named object like a cup using the GraspPlanner try_grasping method', 'try_placing_object': 'detect an object and place it at a different location using the GraspPlanner try_placing method', 'plan_to_grasp_pose': 'create a trajectory plan to reach a given SE(3) grasp pose using the plan_to_grasp method', 'execute_grasp_trajectory': 'execute a predefined grasp trajectory to a 4x4 pose matrix using the try_executing_grasp method', 'compute_divergence_from_vertical': 'compute the theta x and y angles of a grasp pose from vertical using divergence_from_vertical_grasp'}
```

