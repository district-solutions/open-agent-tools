# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/mapping/voxel/planners.py

Prompts

```
["plan a robot's motion to the nearest frontier point in a voxel map using a planner", 'review the plan_to_frontier function for frontier sampling and planning logic during exploration', 'test the plan_to_frontier function with a mock planner and configuration space', 'refactor plan_to_frontier to support headless visualization without matplotlib plt.show calls', 'summarize the plan_to_frontier function that plans robot motion to frontier points with retry logic', 'create a SparseVoxelMap instance with configurable resolution, grid size, and instance memory settings', 'add a robot observation with camera pose, RGB, depth, and instance data to the voxel map', 'get the 2D obstacle and explored area masks from the voxel map for navigation planning', 'sample an obstacle-free XY point from the explored region of the voxel map', 'display the aggregated point cloud with instance bounding boxes using open3d or pytorch3d backend', 'create a SparseVoxelMapNavigationSpace with a voxel map, robot model, step size, and orientation resolution', 'sample the closest frontier point using FMM geodesic distance from the current robot XYT state', 'sample a random valid frontier location by expanding explored edges and rejection sampling', 'check if an XYT state is valid by verifying no collisions and sufficient explored coverage', 'extend from one XYT configuration toward another using separate move-then-rotate or joint interpolation', 'publish a single timestep observation from a SparseVoxelMap to a pickle file in the given directory', 'create a FilePublisher instance to build and publish SparseVoxelMap observations to a directory at a target FPS', 'build a voxel map representation from observations and publish each timestep as a pickle file to disk', 'publish RGB, depth, instance segmentation, camera pose, and bounding box data for a given timestep', 'publish observations one at a time waiting for user keypress input between each write operation']
```

Usage

```
{'plan_to_frontier': "plan a robot's motion to the nearest frontier point in a voxel map using a planner", 'review_plan_to_frontier': 'review the plan_to_frontier function for frontier sampling and planning logic during exploration', 'test_plan_to_frontier': 'test the plan_to_frontier function with a mock planner and configuration space', 'refactor_plan_to_frontier_visualize': 'refactor plan_to_frontier to support headless visualization without matplotlib plt.show calls', 'summarize_plan_to_frontier': 'summarize the plan_to_frontier function that plans robot motion to frontier points with retry logic'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/mapping/voxel/voxel.py

Prompts

```
["plan a robot's motion to the nearest frontier point in a voxel map using a planner", 'review the plan_to_frontier function for frontier sampling and planning logic during exploration', 'test the plan_to_frontier function with a mock planner and configuration space', 'refactor plan_to_frontier to support headless visualization without matplotlib plt.show calls', 'summarize the plan_to_frontier function that plans robot motion to frontier points with retry logic', 'create a SparseVoxelMap instance with configurable resolution, grid size, and instance memory settings', 'add a robot observation with camera pose, RGB, depth, and instance data to the voxel map', 'get the 2D obstacle and explored area masks from the voxel map for navigation planning', 'sample an obstacle-free XY point from the explored region of the voxel map', 'display the aggregated point cloud with instance bounding boxes using open3d or pytorch3d backend', 'create a SparseVoxelMapNavigationSpace with a voxel map, robot model, step size, and orientation resolution', 'sample the closest frontier point using FMM geodesic distance from the current robot XYT state', 'sample a random valid frontier location by expanding explored edges and rejection sampling', 'check if an XYT state is valid by verifying no collisions and sufficient explored coverage', 'extend from one XYT configuration toward another using separate move-then-rotate or joint interpolation', 'publish a single timestep observation from a SparseVoxelMap to a pickle file in the given directory', 'create a FilePublisher instance to build and publish SparseVoxelMap observations to a directory at a target FPS', 'build a voxel map representation from observations and publish each timestep as a pickle file to disk', 'publish RGB, depth, instance segmentation, camera pose, and bounding box data for a given timestep', 'publish observations one at a time waiting for user keypress input between each write operation']
```

Usage

```
{'create_sparse_voxel_map': 'create a SparseVoxelMap instance with configurable resolution, grid size, and instance memory settings', 'add_observation_to_voxel_map': 'add a robot observation with camera pose, RGB, depth, and instance data to the voxel map', 'get_2d_map_obstacles_explored': 'get the 2D obstacle and explored area masks from the voxel map for navigation planning', 'sample_explored_safe_point': 'sample an obstacle-free XY point from the explored region of the voxel map', 'show_voxel_map_with_instances': 'display the aggregated point cloud with instance bounding boxes using open3d or pytorch3d backend'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/mapping/voxel/voxel_map.py

Prompts

```
["plan a robot's motion to the nearest frontier point in a voxel map using a planner", 'review the plan_to_frontier function for frontier sampling and planning logic during exploration', 'test the plan_to_frontier function with a mock planner and configuration space', 'refactor plan_to_frontier to support headless visualization without matplotlib plt.show calls', 'summarize the plan_to_frontier function that plans robot motion to frontier points with retry logic', 'create a SparseVoxelMap instance with configurable resolution, grid size, and instance memory settings', 'add a robot observation with camera pose, RGB, depth, and instance data to the voxel map', 'get the 2D obstacle and explored area masks from the voxel map for navigation planning', 'sample an obstacle-free XY point from the explored region of the voxel map', 'display the aggregated point cloud with instance bounding boxes using open3d or pytorch3d backend', 'create a SparseVoxelMapNavigationSpace with a voxel map, robot model, step size, and orientation resolution', 'sample the closest frontier point using FMM geodesic distance from the current robot XYT state', 'sample a random valid frontier location by expanding explored edges and rejection sampling', 'check if an XYT state is valid by verifying no collisions and sufficient explored coverage', 'extend from one XYT configuration toward another using separate move-then-rotate or joint interpolation', 'publish a single timestep observation from a SparseVoxelMap to a pickle file in the given directory', 'create a FilePublisher instance to build and publish SparseVoxelMap observations to a directory at a target FPS', 'build a voxel map representation from observations and publish each timestep as a pickle file to disk', 'publish RGB, depth, instance segmentation, camera pose, and bounding box data for a given timestep', 'publish observations one at a time waiting for user keypress input between each write operation']
```

Usage

```
{'create_SparseVoxelMapNavigationSpace': 'create a SparseVoxelMapNavigationSpace with a voxel map, robot model, step size, and orientation resolution', 'sample_frontier_closest': 'sample the closest frontier point using FMM geodesic distance from the current robot XYT state', 'sample_frontier_random': 'sample a random valid frontier location by expanding explored edges and rejection sampling', 'check_state_validity': 'check if an XYT state is valid by verifying no collisions and sufficient explored coverage', 'extend_configuration': 'extend from one XYT configuration toward another using separate move-then-rotate or joint interpolation'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/mapping/voxel/voxel_publisher.py

Prompts

```
["plan a robot's motion to the nearest frontier point in a voxel map using a planner", 'review the plan_to_frontier function for frontier sampling and planning logic during exploration', 'test the plan_to_frontier function with a mock planner and configuration space', 'refactor plan_to_frontier to support headless visualization without matplotlib plt.show calls', 'summarize the plan_to_frontier function that plans robot motion to frontier points with retry logic', 'create a SparseVoxelMap instance with configurable resolution, grid size, and instance memory settings', 'add a robot observation with camera pose, RGB, depth, and instance data to the voxel map', 'get the 2D obstacle and explored area masks from the voxel map for navigation planning', 'sample an obstacle-free XY point from the explored region of the voxel map', 'display the aggregated point cloud with instance bounding boxes using open3d or pytorch3d backend', 'create a SparseVoxelMapNavigationSpace with a voxel map, robot model, step size, and orientation resolution', 'sample the closest frontier point using FMM geodesic distance from the current robot XYT state', 'sample a random valid frontier location by expanding explored edges and rejection sampling', 'check if an XYT state is valid by verifying no collisions and sufficient explored coverage', 'extend from one XYT configuration toward another using separate move-then-rotate or joint interpolation', 'publish a single timestep observation from a SparseVoxelMap to a pickle file in the given directory', 'create a FilePublisher instance to build and publish SparseVoxelMap observations to a directory at a target FPS', 'build a voxel map representation from observations and publish each timestep as a pickle file to disk', 'publish RGB, depth, instance segmentation, camera pose, and bounding box data for a given timestep', 'publish observations one at a time waiting for user keypress input between each write operation']
```

Usage

```
{'publish_obs_timestep': 'publish a single timestep observation from a SparseVoxelMap to a pickle file in the given directory', 'create_file_publisher': 'create a FilePublisher instance to build and publish SparseVoxelMap observations to a directory at a target FPS', 'build_representation_and_publish': 'build a voxel map representation from observations and publish each timestep as a pickle file to disk', 'publish_obs_with_instances': 'publish RGB, depth, instance segmentation, camera pose, and bounding box data for a given timestep', 'publish_with_keypress_control': 'publish observations one at a time waiting for user keypress input between each write operation'}
```

