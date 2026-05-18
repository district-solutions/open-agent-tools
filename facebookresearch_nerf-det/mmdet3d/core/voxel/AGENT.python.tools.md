# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/core/voxel/builder.py

Prompts

```
['build a VoxelGenerator from a config dict using build_voxel_generator with voxel_size and point_cloud_range', 'build a VoxelGenerator by passing an existing VoxelGenerator instance directly to build_voxel_generator', 'generate voxels from a point cloud numpy array using VoxelGenerator.generate method', 'convert KITTI format points to voxels using the points_to_voxel function with voxel_size and coors_range', 'inspect VoxelGenerator properties like voxel_size, grid_size, max_num_points_per_voxel, and point_cloud_range', 'create a VoxelGenerator with voxel size, point cloud range, and max points per voxel', 'review the numba JIT compiled reverse kernel that converts points to voxels with zyx coordinate order', 'review the numba JIT compiled kernel that converts points to voxels with standard xyz coordinate order']
```

Usage

```
{'build_voxel_generator_from_cfg': 'build a VoxelGenerator from a config dict using build_voxel_generator with voxel_size and point_cloud_range', 'build_voxel_generator_from_instance': 'build a VoxelGenerator by passing an existing VoxelGenerator instance directly to build_voxel_generator', 'generate_voxels_from_points': 'generate voxels from a point cloud numpy array using VoxelGenerator.generate method', 'convert_points_to_voxel': 'convert KITTI format points to voxels using the points_to_voxel function with voxel_size and coors_range', 'inspect_voxel_generator_properties': 'inspect VoxelGenerator properties like voxel_size, grid_size, max_num_points_per_voxel, and point_cloud_range'}
```

## File: facebookresearch_nerf-det/mmdet3d/core/voxel/voxel_generator.py

Prompts

```
['build a VoxelGenerator from a config dict using build_voxel_generator with voxel_size and point_cloud_range', 'build a VoxelGenerator by passing an existing VoxelGenerator instance directly to build_voxel_generator', 'generate voxels from a point cloud numpy array using VoxelGenerator.generate method', 'convert KITTI format points to voxels using the points_to_voxel function with voxel_size and coors_range', 'inspect VoxelGenerator properties like voxel_size, grid_size, max_num_points_per_voxel, and point_cloud_range', 'create a VoxelGenerator with voxel size, point cloud range, and max points per voxel', 'review the numba JIT compiled reverse kernel that converts points to voxels with zyx coordinate order', 'review the numba JIT compiled kernel that converts points to voxels with standard xyz coordinate order']
```

Usage

```
{'create_VoxelGenerator': 'create a VoxelGenerator with voxel size, point cloud range, and max points per voxel', 'generate_voxels_from_points': 'generate voxels from a numpy array of point cloud data using VoxelGenerator.generate', 'convert_points_to_voxel': 'convert KITTI point cloud points to voxels using the points_to_voxel function', 'review_points_to_voxel_reverse_kernel': 'review the numba JIT compiled reverse kernel that converts points to voxels with zyx coordinate order', 'review_points_to_voxel_kernel': 'review the numba JIT compiled kernel that converts points to voxels with standard xyz coordinate order'}
```

