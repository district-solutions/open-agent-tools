# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/mapping/semantic/categorical_2d_semantic_map_module.py

Prompts

```
['create a Categorical2DSemanticMapModule instance with frame dimensions, camera height, hfov, and map resolution parameters', 'run the forward pass to update local and global semantic maps from a sequence of observations and poses', 'review the _update_local_map_and_pose method that projects depth observations into a 2D voxel grid and aggregates into the local map', 'review the _update_global_map_instances method that associates local instance IDs with global instance IDs using map overlap', 'review the _get_map_features method that combines local and downsampled global map channels into map feature tensors', 'create a Categorical2DSemanticMapState instance with device, num_environments, num_sem_categories, map_resolution, map_size_cm, and global_downscaling parameters', 'initialize global and local map and sensor pose variables for all environments in the semantic map state', 'get the local semantic category map for a specific environment as a numpy array', 'get the local obstacle map for a specific environment as a numpy array', 'convert local map row and column coordinates to global map coordinates for a given environment', 'create a VisionLanguage2DSemanticMapModule with LSeg checkpoint path, frame dimensions, camera height, and map resolution parameters', 'run the forward pass to update local and global semantic maps with a sequence of RGB-D observations and pose deltas', 'update the local 2D semantic map and agent pose using a new RGB-D observation and pose delta via projective geometry', 'update the global map with the local map contents and re-center the local map and pose for an environment', 'get combined local and global map features by pooling the global map and extracting CLIP features from the local map', 'create a VisionLanguage2DSemanticMapState instance with device, num_environments, lseg_features_dim, map_resolution, map_size_cm, and global_downscaling parameters', 'get local planner pose inputs combining global pose and local map boundaries for a specific environment', 'update the global goal map for a specific environment with a binary goal map chosen by the policy']
```

Usage

```
{'create_Categorical2DSemanticMapModule': 'create a Categorical2DSemanticMapModule instance with frame dimensions, camera height, hfov, and map resolution parameters', 'run_forward_update_maps': 'run the forward pass to update local and global semantic maps from a sequence of observations and poses', 'review_update_local_map_and_pose': 'review the _update_local_map_and_pose method that projects depth observations into a 2D voxel grid and aggregates into the local map', 'review_update_global_map_instances': 'review the _update_global_map_instances method that associates local instance IDs with global instance IDs using map overlap', 'review_get_map_features': 'review the _get_map_features method that combines local and downsampled global map channels into map feature tensors'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/mapping/semantic/categorical_2d_semantic_map_state.py

Prompts

```
['create a Categorical2DSemanticMapModule instance with frame dimensions, camera height, hfov, and map resolution parameters', 'run the forward pass to update local and global semantic maps from a sequence of observations and poses', 'review the _update_local_map_and_pose method that projects depth observations into a 2D voxel grid and aggregates into the local map', 'review the _update_global_map_instances method that associates local instance IDs with global instance IDs using map overlap', 'review the _get_map_features method that combines local and downsampled global map channels into map feature tensors', 'create a Categorical2DSemanticMapState instance with device, num_environments, num_sem_categories, map_resolution, map_size_cm, and global_downscaling parameters', 'initialize global and local map and sensor pose variables for all environments in the semantic map state', 'get the local semantic category map for a specific environment as a numpy array', 'get the local obstacle map for a specific environment as a numpy array', 'convert local map row and column coordinates to global map coordinates for a given environment', 'create a VisionLanguage2DSemanticMapModule with LSeg checkpoint path, frame dimensions, camera height, and map resolution parameters', 'run the forward pass to update local and global semantic maps with a sequence of RGB-D observations and pose deltas', 'update the local 2D semantic map and agent pose using a new RGB-D observation and pose delta via projective geometry', 'update the global map with the local map contents and re-center the local map and pose for an environment', 'get combined local and global map features by pooling the global map and extracting CLIP features from the local map', 'create a VisionLanguage2DSemanticMapState instance with device, num_environments, lseg_features_dim, map_resolution, map_size_cm, and global_downscaling parameters', 'get local planner pose inputs combining global pose and local map boundaries for a specific environment', 'update the global goal map for a specific environment with a binary goal map chosen by the policy']
```

Usage

```
{'create_Categorical2DSemanticMapState': 'create a Categorical2DSemanticMapState instance with device, num_environments, num_sem_categories, map_resolution, map_size_cm, and global_downscaling parameters', 'init_map_and_pose': 'initialize global and local map and sensor pose variables for all environments in the semantic map state', 'get_semantic_map': 'get the local semantic category map for a specific environment as a numpy array', 'get_obstacle_map': 'get the local obstacle map for a specific environment as a numpy array', 'local_to_global': 'convert local map row and column coordinates to global map coordinates for a given environment'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/mapping/semantic/vision_language_2d_semantic_map_module.py

Prompts

```
['create a Categorical2DSemanticMapModule instance with frame dimensions, camera height, hfov, and map resolution parameters', 'run the forward pass to update local and global semantic maps from a sequence of observations and poses', 'review the _update_local_map_and_pose method that projects depth observations into a 2D voxel grid and aggregates into the local map', 'review the _update_global_map_instances method that associates local instance IDs with global instance IDs using map overlap', 'review the _get_map_features method that combines local and downsampled global map channels into map feature tensors', 'create a Categorical2DSemanticMapState instance with device, num_environments, num_sem_categories, map_resolution, map_size_cm, and global_downscaling parameters', 'initialize global and local map and sensor pose variables for all environments in the semantic map state', 'get the local semantic category map for a specific environment as a numpy array', 'get the local obstacle map for a specific environment as a numpy array', 'convert local map row and column coordinates to global map coordinates for a given environment', 'create a VisionLanguage2DSemanticMapModule with LSeg checkpoint path, frame dimensions, camera height, and map resolution parameters', 'run the forward pass to update local and global semantic maps with a sequence of RGB-D observations and pose deltas', 'update the local 2D semantic map and agent pose using a new RGB-D observation and pose delta via projective geometry', 'update the global map with the local map contents and re-center the local map and pose for an environment', 'get combined local and global map features by pooling the global map and extracting CLIP features from the local map', 'create a VisionLanguage2DSemanticMapState instance with device, num_environments, lseg_features_dim, map_resolution, map_size_cm, and global_downscaling parameters', 'get local planner pose inputs combining global pose and local map boundaries for a specific environment', 'update the global goal map for a specific environment with a binary goal map chosen by the policy']
```

Usage

```
{'create_VisionLanguage2DSemanticMapModule': 'create a VisionLanguage2DSemanticMapModule with LSeg checkpoint path, frame dimensions, camera height, and map resolution parameters', 'run_forward_VisionLanguage2DSemanticMapModule': 'run the forward pass to update local and global semantic maps with a sequence of RGB-D observations and pose deltas', 'update_local_map_and_pose': 'update the local 2D semantic map and agent pose using a new RGB-D observation and pose delta via projective geometry', 'update_global_map_and_pose': 'update the global map with the local map contents and re-center the local map and pose for an environment', 'get_map_features': 'get combined local and global map features by pooling the global map and extracting CLIP features from the local map'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/mapping/semantic/vision_language_2d_semantic_map_state.py

Prompts

```
['create a Categorical2DSemanticMapModule instance with frame dimensions, camera height, hfov, and map resolution parameters', 'run the forward pass to update local and global semantic maps from a sequence of observations and poses', 'review the _update_local_map_and_pose method that projects depth observations into a 2D voxel grid and aggregates into the local map', 'review the _update_global_map_instances method that associates local instance IDs with global instance IDs using map overlap', 'review the _get_map_features method that combines local and downsampled global map channels into map feature tensors', 'create a Categorical2DSemanticMapState instance with device, num_environments, num_sem_categories, map_resolution, map_size_cm, and global_downscaling parameters', 'initialize global and local map and sensor pose variables for all environments in the semantic map state', 'get the local semantic category map for a specific environment as a numpy array', 'get the local obstacle map for a specific environment as a numpy array', 'convert local map row and column coordinates to global map coordinates for a given environment', 'create a VisionLanguage2DSemanticMapModule with LSeg checkpoint path, frame dimensions, camera height, and map resolution parameters', 'run the forward pass to update local and global semantic maps with a sequence of RGB-D observations and pose deltas', 'update the local 2D semantic map and agent pose using a new RGB-D observation and pose delta via projective geometry', 'update the global map with the local map contents and re-center the local map and pose for an environment', 'get combined local and global map features by pooling the global map and extracting CLIP features from the local map', 'create a VisionLanguage2DSemanticMapState instance with device, num_environments, lseg_features_dim, map_resolution, map_size_cm, and global_downscaling parameters', 'get local planner pose inputs combining global pose and local map boundaries for a specific environment', 'update the global goal map for a specific environment with a binary goal map chosen by the policy']
```

Usage

```
{'create_VisionLanguage2DSemanticMapState': 'create a VisionLanguage2DSemanticMapState instance with device, num_environments, lseg_features_dim, map_resolution, map_size_cm, and global_downscaling parameters', 'init_map_and_pose': 'initialize global and local map and sensor pose variables for all environments in the VisionLanguage2DSemanticMapState', 'get_semantic_map': 'get a local map of semantic categories by decoding CLIP features to a label set using an LSegEncDecNet model', 'get_planner_pose_inputs': 'get local planner pose inputs combining global pose and local map boundaries for a specific environment', 'update_global_goal_for_env': 'update the global goal map for a specific environment with a binary goal map chosen by the policy'}
```

