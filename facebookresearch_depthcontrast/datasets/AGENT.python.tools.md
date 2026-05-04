# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/datasets/depth_dataset.py

Prompts

```
['create a DepthContrastDataset instance with a config dict containing DATA_PATHS, BATCHSIZE_PER_REPLICA, and DATASET_NAMES keys', 'load a point cloud from the dataset by index using the load_data method and return the point array', 'voxelize point cloud coordinates and features using toVox with spconv VoxelGenerator or minkowski Voxelizer', 'apply 3D point transformations to data using get_transform3d with POINT_TRANSFORMS config before voxelization', 'get the global batch size by multiplying batchsize_per_replica with the distributed world size']
```

Usage

```
{'create_DepthContrastDataset': 'create a DepthContrastDataset instance with a config dict containing DATA_PATHS, BATCHSIZE_PER_REPLICA, and DATASET_NAMES keys', 'load_data_from_index': 'load a point cloud from the dataset by index using the load_data method and return the point array', 'voxelize_point_cloud': 'voxelize point cloud coordinates and features using toVox with spconv VoxelGenerator or minkowski Voxelizer', 'get_transform3d_on_points': 'apply 3D point transformations to data using get_transform3d with POINT_TRANSFORMS config before voxelization', 'get_global_batchsize': 'get the global batch size by multiplying batchsize_per_replica with the distributed world size'}
```

