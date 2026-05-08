# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/manipulation/grasping.py

Prompts

```
['build a SimpleGraspMotionPlanner instance with a HelloStretchKinematics robot and pregrasp height', 'plan a full grasp trajectory from a grasp pose and initial robot configuration', 'create a pregrasp waypoint at the top of the robot arc using initial config', 'solve inverse kinematics for a grasp pose using the robot manip_ik method', 'compute a standoff position above the grasp pose with configurable z standoff distance', 'build a HeuristicPickPolicy agent that picks objects using semantic segmentation and point cloud analysis', 'create a function that finds the highest voxel on an object using semantic masks and point clouds', 'test the HeuristicPickPolicy generate_plan method to verify hardcoded pick sequence timestep scheduling', 'refactor the get_action method to support dynamic timestep adjustment for arm lift and extension', 'review the HeuristicPickPolicy forward method that orchestrates plan generation and action execution per timestep', 'build a heuristic place policy module that uses depth and point cloud heuristics to place objects on receptacles', 'create a function that computes a 3D placement point on a receptacle from semantic masks and point cloud data', 'test the method that converts depth observations into point cloud coordinates in the robot base frame', 'refactor the forward method to adjust the multi-step navigation and arm placement sequence for object placement', 'review the HeuristicPlacePolicy reset method and timestep state management for policy reinitialization', 'build a python module using VoxelGraspGenerator to generate top-down grasps from a point cloud and segmentation map', 'create a function that computes x and y grasp scores from an occupancy map and center point', 'create a function that filters a 2D grasp score map by neighboring scores and threshold', 'create a function that generates a 4x4 vertical grasp pose matrix from xyz position and z rotation', 'create a function that visualizes 3D point cloud with highlighted points and grasp pose arrows']
```

Usage

```
{'build_grasp_motion_planner': 'build a SimpleGraspMotionPlanner instance with a HelloStretchKinematics robot and pregrasp height', 'plan_to_grasp_trajectory': 'plan a full grasp trajectory from a grasp pose and initial robot configuration', 'create_pregrasp_waypoint': 'create a pregrasp waypoint at the top of the robot arc using initial config', 'solve_inverse_kinematics_grasp': 'solve inverse kinematics for a grasp pose using the robot manip_ik method', 'compute_standoff_position': 'compute a standoff position above the grasp pose with configurable z standoff distance'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/manipulation/heuristic_pick_policy.py

Prompts

```
['build a SimpleGraspMotionPlanner instance with a HelloStretchKinematics robot and pregrasp height', 'plan a full grasp trajectory from a grasp pose and initial robot configuration', 'create a pregrasp waypoint at the top of the robot arc using initial config', 'solve inverse kinematics for a grasp pose using the robot manip_ik method', 'compute a standoff position above the grasp pose with configurable z standoff distance', 'build a HeuristicPickPolicy agent that picks objects using semantic segmentation and point cloud analysis', 'create a function that finds the highest voxel on an object using semantic masks and point clouds', 'test the HeuristicPickPolicy generate_plan method to verify hardcoded pick sequence timestep scheduling', 'refactor the get_action method to support dynamic timestep adjustment for arm lift and extension', 'review the HeuristicPickPolicy forward method that orchestrates plan generation and action execution per timestep', 'build a heuristic place policy module that uses depth and point cloud heuristics to place objects on receptacles', 'create a function that computes a 3D placement point on a receptacle from semantic masks and point cloud data', 'test the method that converts depth observations into point cloud coordinates in the robot base frame', 'refactor the forward method to adjust the multi-step navigation and arm placement sequence for object placement', 'review the HeuristicPlacePolicy reset method and timestep state management for policy reinitialization', 'build a python module using VoxelGraspGenerator to generate top-down grasps from a point cloud and segmentation map', 'create a function that computes x and y grasp scores from an occupancy map and center point', 'create a function that filters a 2D grasp score map by neighboring scores and threshold', 'create a function that generates a 4x4 vertical grasp pose matrix from xyz position and z rotation', 'create a function that visualizes 3D point cloud with highlighted points and grasp pose arrows']
```

Usage

```
{'build_heuristic_pick_policy': 'build a HeuristicPickPolicy agent that picks objects using semantic segmentation and point cloud analysis', 'create_get_object_pick_point': 'create a function that finds the highest voxel on an object using semantic masks and point clouds', 'test_generate_plan': 'test the HeuristicPickPolicy generate_plan method to verify hardcoded pick sequence timestep scheduling', 'refactor_get_action': 'refactor the get_action method to support dynamic timestep adjustment for arm lift and extension', 'review_forward': 'review the HeuristicPickPolicy forward method that orchestrates plan generation and action execution per timestep'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/manipulation/heuristic_place_policy.py

Prompts

```
['build a SimpleGraspMotionPlanner instance with a HelloStretchKinematics robot and pregrasp height', 'plan a full grasp trajectory from a grasp pose and initial robot configuration', 'create a pregrasp waypoint at the top of the robot arc using initial config', 'solve inverse kinematics for a grasp pose using the robot manip_ik method', 'compute a standoff position above the grasp pose with configurable z standoff distance', 'build a HeuristicPickPolicy agent that picks objects using semantic segmentation and point cloud analysis', 'create a function that finds the highest voxel on an object using semantic masks and point clouds', 'test the HeuristicPickPolicy generate_plan method to verify hardcoded pick sequence timestep scheduling', 'refactor the get_action method to support dynamic timestep adjustment for arm lift and extension', 'review the HeuristicPickPolicy forward method that orchestrates plan generation and action execution per timestep', 'build a heuristic place policy module that uses depth and point cloud heuristics to place objects on receptacles', 'create a function that computes a 3D placement point on a receptacle from semantic masks and point cloud data', 'test the method that converts depth observations into point cloud coordinates in the robot base frame', 'refactor the forward method to adjust the multi-step navigation and arm placement sequence for object placement', 'review the HeuristicPlacePolicy reset method and timestep state management for policy reinitialization', 'build a python module using VoxelGraspGenerator to generate top-down grasps from a point cloud and segmentation map', 'create a function that computes x and y grasp scores from an occupancy map and center point', 'create a function that filters a 2D grasp score map by neighboring scores and threshold', 'create a function that generates a 4x4 vertical grasp pose matrix from xyz position and z rotation', 'create a function that visualizes 3D point cloud with highlighted points and grasp pose arrows']
```

Usage

```
{'build_HeuristicPlacePolicy': 'build a heuristic place policy module that uses depth and point cloud heuristics to place objects on receptacles', 'create_get_receptacle_placement_point': 'create a function that computes a 3D placement point on a receptacle from semantic masks and point cloud data', 'test_get_target_point_cloud_base_coords': 'test the method that converts depth observations into point cloud coordinates in the robot base frame', 'refactor_forward': 'refactor the forward method to adjust the multi-step navigation and arm placement sequence for object placement', 'review_HeuristicPlacePolicy_reset': 'review the HeuristicPlacePolicy reset method and timestep state management for policy reinitialization'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/manipulation/voxel_grasps.py

Prompts

```
['build a SimpleGraspMotionPlanner instance with a HelloStretchKinematics robot and pregrasp height', 'plan a full grasp trajectory from a grasp pose and initial robot configuration', 'create a pregrasp waypoint at the top of the robot arc using initial config', 'solve inverse kinematics for a grasp pose using the robot manip_ik method', 'compute a standoff position above the grasp pose with configurable z standoff distance', 'build a HeuristicPickPolicy agent that picks objects using semantic segmentation and point cloud analysis', 'create a function that finds the highest voxel on an object using semantic masks and point clouds', 'test the HeuristicPickPolicy generate_plan method to verify hardcoded pick sequence timestep scheduling', 'refactor the get_action method to support dynamic timestep adjustment for arm lift and extension', 'review the HeuristicPickPolicy forward method that orchestrates plan generation and action execution per timestep', 'build a heuristic place policy module that uses depth and point cloud heuristics to place objects on receptacles', 'create a function that computes a 3D placement point on a receptacle from semantic masks and point cloud data', 'test the method that converts depth observations into point cloud coordinates in the robot base frame', 'refactor the forward method to adjust the multi-step navigation and arm placement sequence for object placement', 'review the HeuristicPlacePolicy reset method and timestep state management for policy reinitialization', 'build a python module using VoxelGraspGenerator to generate top-down grasps from a point cloud and segmentation map', 'create a function that computes x and y grasp scores from an occupancy map and center point', 'create a function that filters a 2D grasp score map by neighboring scores and threshold', 'create a function that generates a 4x4 vertical grasp pose matrix from xyz position and z rotation', 'create a function that visualizes 3D point cloud with highlighted points and grasp pose arrows']
```

Usage

```
{'build_VoxelGraspGenerator': 'build a python module using VoxelGraspGenerator to generate top-down grasps from a point cloud and segmentation map', 'create_compute_grasp_scores': 'create a function that computes x and y grasp scores from an occupancy map and center point', 'create_filter_grasps': 'create a function that filters a 2D grasp score map by neighboring scores and threshold', 'create_generate_grasp': 'create a function that generates a 4x4 vertical grasp pose matrix from xyz position and z rotation', 'create_visualize_grasps': 'create a function that visualizes 3D point cloud with highlighted points and grasp pose arrows'}
```

