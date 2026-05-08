# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/lowlevel/locobot/remote/slam_pkg/utils/depth_util.py

Prompts

```
['transform a point cloud into the geocentric frame using the camera pose with transform_pose', 'bin 3D point cloud data into xy-z occupancy grid bins using bin_points', 'calculate the relative state of a robot pose with respect to an initial state using get_relative_state', 'splat feature vectors into an N-dimensional grid using trilinear interpolation with splat_feat_nd', 'review the depth_util module functions for point cloud transformation, binning, and feature splatting', 'create an FMMPlanner instance with a traversable 2D boolean map and step size', 'set a single goal coordinate on the FMMPlanner to compute fast marching method distances', 'set multiple goal regions on the FMMPlanner using a binary goal map for object navigation', 'get the next short-term goal coordinates for the robot based on current state and FMM distances', 'visualize the traversable map, goal map, and FMM distance field as a saved image', 'create a MapBuilder instance with configurable map size, resolution, and obstacle thresholds for SLAM mapping', 'update the obstacle map using a point cloud in global frame and return binary obstacle map', 'update the semantic map with point cloud, semantic channels, and pose to build multi-channel semantic representation', 'reset the map to unknown state with configurable map size, z bins, and obstacle threshold', 'convert real world metric location to map pixel coordinates using the real2map method']
```

Usage

```
{'transform_point_cloud_to_geocentric': 'transform a point cloud into the geocentric frame using the camera pose with transform_pose', 'bin_points_into_occupancy_grid': 'bin 3D point cloud data into xy-z occupancy grid bins using bin_points', 'calculate_relative_robot_state': 'calculate the relative state of a robot pose with respect to an initial state using get_relative_state', 'splat_features_into_nd_grid': 'splat feature vectors into an N-dimensional grid using trilinear interpolation with splat_feat_nd', 'review_depth_util_functions': 'review the depth_util module functions for point cloud transformation, binning, and feature splatting'}
```

## File: facebookresearch_fairo/droidlet/lowlevel/locobot/remote/slam_pkg/utils/fmm_planner.py

Prompts

```
['transform a point cloud into the geocentric frame using the camera pose with transform_pose', 'bin 3D point cloud data into xy-z occupancy grid bins using bin_points', 'calculate the relative state of a robot pose with respect to an initial state using get_relative_state', 'splat feature vectors into an N-dimensional grid using trilinear interpolation with splat_feat_nd', 'review the depth_util module functions for point cloud transformation, binning, and feature splatting', 'create an FMMPlanner instance with a traversable 2D boolean map and step size', 'set a single goal coordinate on the FMMPlanner to compute fast marching method distances', 'set multiple goal regions on the FMMPlanner using a binary goal map for object navigation', 'get the next short-term goal coordinates for the robot based on current state and FMM distances', 'visualize the traversable map, goal map, and FMM distance field as a saved image', 'create a MapBuilder instance with configurable map size, resolution, and obstacle thresholds for SLAM mapping', 'update the obstacle map using a point cloud in global frame and return binary obstacle map', 'update the semantic map with point cloud, semantic channels, and pose to build multi-channel semantic representation', 'reset the map to unknown state with configurable map size, z bins, and obstacle threshold', 'convert real world metric location to map pixel coordinates using the real2map method']
```

Usage

```
{'create_fmm_planner': 'create an FMMPlanner instance with a traversable 2D boolean map and step size', 'set_goal_single': 'set a single goal coordinate on the FMMPlanner to compute fast marching method distances', 'set_goal_multi': 'set multiple goal regions on the FMMPlanner using a binary goal map for object navigation', 'get_short_term_goal': 'get the next short-term goal coordinates for the robot based on current state and FMM distances', 'visualize_fmm_distance': 'visualize the traversable map, goal map, and FMM distance field as a saved image'}
```

## File: facebookresearch_fairo/droidlet/lowlevel/locobot/remote/slam_pkg/utils/map_builder.py

Prompts

```
['transform a point cloud into the geocentric frame using the camera pose with transform_pose', 'bin 3D point cloud data into xy-z occupancy grid bins using bin_points', 'calculate the relative state of a robot pose with respect to an initial state using get_relative_state', 'splat feature vectors into an N-dimensional grid using trilinear interpolation with splat_feat_nd', 'review the depth_util module functions for point cloud transformation, binning, and feature splatting', 'create an FMMPlanner instance with a traversable 2D boolean map and step size', 'set a single goal coordinate on the FMMPlanner to compute fast marching method distances', 'set multiple goal regions on the FMMPlanner using a binary goal map for object navigation', 'get the next short-term goal coordinates for the robot based on current state and FMM distances', 'visualize the traversable map, goal map, and FMM distance field as a saved image', 'create a MapBuilder instance with configurable map size, resolution, and obstacle thresholds for SLAM mapping', 'update the obstacle map using a point cloud in global frame and return binary obstacle map', 'update the semantic map with point cloud, semantic channels, and pose to build multi-channel semantic representation', 'reset the map to unknown state with configurable map size, z bins, and obstacle threshold', 'convert real world metric location to map pixel coordinates using the real2map method']
```

Usage

```
{'create_map_builder': 'create a MapBuilder instance with configurable map size, resolution, and obstacle thresholds for SLAM mapping', 'update_map_with_point_cloud': 'update the obstacle map using a point cloud in global frame and return binary obstacle map', 'update_semantic_map': 'update the semantic map with point cloud, semantic channels, and pose to build multi-channel semantic representation', 'reset_map': 'reset the map to unknown state with configurable map size, z bins, and obstacle threshold', 'convert_real_to_map_coordinates': 'convert real world metric location to map pixel coordinates using the real2map method'}
```

