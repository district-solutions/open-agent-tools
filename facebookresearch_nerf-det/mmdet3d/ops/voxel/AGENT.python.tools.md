# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/ops/voxel/scatter_points.py

Prompts

```
['build a PyTorch module that scatters KITTI point cloud data into 3D voxels using dynamic voxelization', 'create a DynamicScatter nn.Module instance that uses average pooling to aggregate points into voxels', 'test the dynamic_scatter autograd Function forward and backward pass with point cloud tensors', 'refactor the DynamicScatter forward method to handle batched coordinates with batch index padding', 'review the _dynamic_scatter class that converts N-dimensional point clouds to voxel tensors with coordinate mapping', 'build a Voxelization nn.Module to convert KITTI point clouds into 3D voxels with configurable voxel size', 'run the voxelization function to convert N-dimensional point tensors into hard or dynamic voxels', 'create dynamic voxels from points by calling voxelization with max_points set to negative one', 'test the Voxelization forward pass by passing NC points and checking returned voxels and coordinates', 'review the Voxelization constructor to understand grid size and point cloud range configuration']
```

Usage

```
{'build_dynamic_scatter_module': 'build a PyTorch module that scatters KITTI point cloud data into 3D voxels using dynamic voxelization', 'create_DynamicScatter_with_avg_pooling': 'create a DynamicScatter nn.Module instance that uses average pooling to aggregate points into voxels', 'test_dynamic_scatter_forward_backward': 'test the dynamic_scatter autograd Function forward and backward pass with point cloud tensors', 'refactor_DynamicScatter_forward_batched': 'refactor the DynamicScatter forward method to handle batched coordinates with batch index padding', 'review_dynamic_scatter_voxel_conversion': 'review the _dynamic_scatter class that converts N-dimensional point clouds to voxel tensors with coordinate mapping'}
```

## File: facebookresearch_nerf-det/mmdet3d/ops/voxel/voxelize.py

Prompts

```
['build a PyTorch module that scatters KITTI point cloud data into 3D voxels using dynamic voxelization', 'create a DynamicScatter nn.Module instance that uses average pooling to aggregate points into voxels', 'test the dynamic_scatter autograd Function forward and backward pass with point cloud tensors', 'refactor the DynamicScatter forward method to handle batched coordinates with batch index padding', 'review the _dynamic_scatter class that converts N-dimensional point clouds to voxel tensors with coordinate mapping', 'build a Voxelization nn.Module to convert KITTI point clouds into 3D voxels with configurable voxel size', 'run the voxelization function to convert N-dimensional point tensors into hard or dynamic voxels', 'create dynamic voxels from points by calling voxelization with max_points set to negative one', 'test the Voxelization forward pass by passing NC points and checking returned voxels and coordinates', 'review the Voxelization constructor to understand grid size and point cloud range configuration']
```

Usage

```
{'build_voxelization_module': 'build a Voxelization nn.Module to convert KITTI point clouds into 3D voxels with configurable voxel size', 'run_voxelization_function': 'run the voxelization function to convert N-dimensional point tensors into hard or dynamic voxels', 'create_dynamic_voxelize': 'create dynamic voxels from points by calling voxelization with max_points set to negative one', 'test_Voxelization_forward': 'test the Voxelization forward pass by passing NC points and checking returned voxels and coordinates', 'review_Voxelization_init': 'review the Voxelization constructor to understand grid size and point cloud range configuration'}
```

