# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/datasets/pipelines/data_augment_utils.py

Prompts

```
['build a python module that runs box_collision_test to detect collisions between two sets of 2D bounding box corners', 'create a function that adds location and rotation noise to 2D boxes while avoiding collisions with other boxes', 'test the noise_per_object_v3_ function to randomly perturb 3D ground truth boxes and transform associated point clouds', 'refactor the get_dtu_raydir function to compute normalized camera ray directions from pixel coordinates and intrinsics', 'summarize the noise_per_box_v2_ function that augments 2D boxes with global rotation noise and collision checks', 'build a DataBaseSampler to sample ground truth objects from a 3D detection database with collision avoidance', 'create a BatchSampler to sample specific categories of ground truths with shuffling and index management', 'filter database infos by removing ground truths with specified difficulty levels', 'filter database infos by minimum number of points required in each ground truth bounding box', 'sample all categories of 3D bounding boxes with collision testing and point cloud translation', 'build a RandomFlip3D pipeline to randomly flip 3D point clouds and bounding boxes horizontally or vertically', 'build an ObjectSample pipeline to sample GT objects from a database and paste them into the scene', 'build a GlobalRotScaleTrans pipeline to apply random rotation, scaling, and translation to 3D scenes', 'build an ObjectNoise pipeline to apply per-object translation and rotation noise to 3D bounding boxes and points', 'build a VoxelBasedPointSampler pipeline to voxel-sample points from current and previous LiDAR sweeps']
```

Usage

```
{'build_box_collision_test': 'build a python module that runs box_collision_test to detect collisions between two sets of 2D bounding box corners', 'create_noise_per_box': 'create a function that adds location and rotation noise to 2D boxes while avoiding collisions with other boxes', 'test_noise_per_object_v3': 'test the noise_per_object_v3_ function to randomly perturb 3D ground truth boxes and transform associated point clouds', 'refactor_get_dtu_raydir': 'refactor the get_dtu_raydir function to compute normalized camera ray directions from pixel coordinates and intrinsics', 'summarize_noise_per_box_v2': 'summarize the noise_per_box_v2_ function that augments 2D boxes with global rotation noise and collision checks'}
```

## File: facebookresearch_nerf-det/mmdet3d/datasets/pipelines/dbsampler.py

Prompts

```
['build a python module that runs box_collision_test to detect collisions between two sets of 2D bounding box corners', 'create a function that adds location and rotation noise to 2D boxes while avoiding collisions with other boxes', 'test the noise_per_object_v3_ function to randomly perturb 3D ground truth boxes and transform associated point clouds', 'refactor the get_dtu_raydir function to compute normalized camera ray directions from pixel coordinates and intrinsics', 'summarize the noise_per_box_v2_ function that augments 2D boxes with global rotation noise and collision checks', 'build a DataBaseSampler to sample ground truth objects from a 3D detection database with collision avoidance', 'create a BatchSampler to sample specific categories of ground truths with shuffling and index management', 'filter database infos by removing ground truths with specified difficulty levels', 'filter database infos by minimum number of points required in each ground truth bounding box', 'sample all categories of 3D bounding boxes with collision testing and point cloud translation', 'build a RandomFlip3D pipeline to randomly flip 3D point clouds and bounding boxes horizontally or vertically', 'build an ObjectSample pipeline to sample GT objects from a database and paste them into the scene', 'build a GlobalRotScaleTrans pipeline to apply random rotation, scaling, and translation to 3D scenes', 'build an ObjectNoise pipeline to apply per-object translation and rotation noise to 3D bounding boxes and points', 'build a VoxelBasedPointSampler pipeline to voxel-sample points from current and previous LiDAR sweeps']
```

Usage

```
{'build_dbsampler': 'build a DataBaseSampler to sample ground truth objects from a 3D detection database with collision avoidance', 'create_batchsampler': 'create a BatchSampler to sample specific categories of ground truths with shuffling and index management', 'filter_by_difficulty': 'filter database infos by removing ground truths with specified difficulty levels', 'filter_by_min_points': 'filter database infos by minimum number of points required in each ground truth bounding box', 'sample_all_classes': 'sample all categories of 3D bounding boxes with collision testing and point cloud translation'}
```

## File: facebookresearch_nerf-det/mmdet3d/datasets/pipelines/transforms_3d.py

Prompts

```
['build a python module that runs box_collision_test to detect collisions between two sets of 2D bounding box corners', 'create a function that adds location and rotation noise to 2D boxes while avoiding collisions with other boxes', 'test the noise_per_object_v3_ function to randomly perturb 3D ground truth boxes and transform associated point clouds', 'refactor the get_dtu_raydir function to compute normalized camera ray directions from pixel coordinates and intrinsics', 'summarize the noise_per_box_v2_ function that augments 2D boxes with global rotation noise and collision checks', 'build a DataBaseSampler to sample ground truth objects from a 3D detection database with collision avoidance', 'create a BatchSampler to sample specific categories of ground truths with shuffling and index management', 'filter database infos by removing ground truths with specified difficulty levels', 'filter database infos by minimum number of points required in each ground truth bounding box', 'sample all categories of 3D bounding boxes with collision testing and point cloud translation', 'build a RandomFlip3D pipeline to randomly flip 3D point clouds and bounding boxes horizontally or vertically', 'build an ObjectSample pipeline to sample GT objects from a database and paste them into the scene', 'build a GlobalRotScaleTrans pipeline to apply random rotation, scaling, and translation to 3D scenes', 'build an ObjectNoise pipeline to apply per-object translation and rotation noise to 3D bounding boxes and points', 'build a VoxelBasedPointSampler pipeline to voxel-sample points from current and previous LiDAR sweeps']
```

Usage

```
{'build_RandomFlip3D': 'build a RandomFlip3D pipeline to randomly flip 3D point clouds and bounding boxes horizontally or vertically', 'build_ObjectSample': 'build an ObjectSample pipeline to sample GT objects from a database and paste them into the scene', 'build_GlobalRotScaleTrans': 'build a GlobalRotScaleTrans pipeline to apply random rotation, scaling, and translation to 3D scenes', 'build_ObjectNoise': 'build an ObjectNoise pipeline to apply per-object translation and rotation noise to 3D bounding boxes and points', 'build_VoxelBasedPointSampler': 'build a VoxelBasedPointSampler pipeline to voxel-sample points from current and previous LiDAR sweeps'}
```

