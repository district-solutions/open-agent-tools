# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot_hw/examples/build_3d_map.py

Prompts

```
['run a fixed robot trajectory with a StretchClient and RosMapDataCollector to navigate waypoints', 'run frontier-based exploration using RRTConnect planning on a Stretch robot with voxel map data', 'collect 3D map data from a Stretch robot via ROS and save point cloud and voxel map files', 'load a pickled SparseVoxelMap from a file and visualize 2D obstacle and explored maps', 'plan RRTConnect paths between frontier goals on a SparseVoxelMapNavigationSpace and visualize the planned trajectories', 'run the Stretch robot demo to explore, find objects, and place them using click CLI options', 'run a manipulation test that switches to manipulation mode and attempts to grasp and place objects', 'run robot exploration with a remote VLM server for visual language model planning via RPC', "save the robot's voxel map as a PCD point cloud and pickle file after exploration completes", 'test grasping functionality by running the demo with the test-grasping flag enabled']
```

Usage

```
{'run_fixed_trajectory': 'run a fixed robot trajectory with a StretchClient and RosMapDataCollector to navigate waypoints', 'run_exploration': 'run frontier-based exploration using RRTConnect planning on a Stretch robot with voxel map data', 'collect_data': 'collect 3D map data from a Stretch robot via ROS and save point cloud and voxel map files', 'load_and_visualize_pkl': 'load a pickled SparseVoxelMap from a file and visualize 2D obstacle and explored maps', 'plan_paths_on_voxel_map': 'plan RRTConnect paths between frontier goals on a SparseVoxelMapNavigationSpace and visualize the planned trajectories'}
```

## File: facebookresearch_home-robot/src/home_robot_hw/examples/demo.py

Prompts

```
['run a fixed robot trajectory with a StretchClient and RosMapDataCollector to navigate waypoints', 'run frontier-based exploration using RRTConnect planning on a Stretch robot with voxel map data', 'collect 3D map data from a Stretch robot via ROS and save point cloud and voxel map files', 'load a pickled SparseVoxelMap from a file and visualize 2D obstacle and explored maps', 'plan RRTConnect paths between frontier goals on a SparseVoxelMapNavigationSpace and visualize the planned trajectories', 'run the Stretch robot demo to explore, find objects, and place them using click CLI options', 'run a manipulation test that switches to manipulation mode and attempts to grasp and place objects', 'run robot exploration with a remote VLM server for visual language model planning via RPC', "save the robot's voxel map as a PCD point cloud and pickle file after exploration completes", 'test grasping functionality by running the demo with the test-grasping flag enabled']
```

Usage

```
{'run_stretch_robot_demo': 'run the Stretch robot demo to explore, find objects, and place them using click CLI options', 'run_manipulation_test': 'run a manipulation test that switches to manipulation mode and attempts to grasp and place objects', 'run_exploration_with_vlm': 'run robot exploration with a remote VLM server for visual language model planning via RPC', 'save_voxel_map': "save the robot's voxel map as a PCD point cloud and pickle file after exploration completes", 'test_grasping': 'test grasping functionality by running the demo with the test-grasping flag enabled'}
```

