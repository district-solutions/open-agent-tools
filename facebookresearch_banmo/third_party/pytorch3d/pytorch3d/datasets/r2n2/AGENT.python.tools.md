# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/pytorch3d/pytorch3d/datasets/r2n2/r2n2.py

Prompts

```
['create an R2N2 dataset object with train split, shapenet directory, r2n2 directory, and splits file', 'load a 3D model by index from the R2N2 dataset with optional view indices and voxels', 'render R2N2 dataset models using BlenderCamera with specified view indices and HardPhongShader', 'compute rotation and translation matrices from an extrinsic ShapeNet to PyTorch3D transformation matrix', 'review the R2N2 class that loads 3D models, renderings, and voxelized data from the R2N2 dataset', 'collate a list of R2N2 dataset dictionaries into stacked tensors for images, camera matrices, and voxels', 'compute a 4x4 camera extrinsic matrix from azimuth, elevation, and distance parameters', 'read a binvox file and return the coordinates of all nonzero voxels as a tensor', 'align source 3D points to a target coordinate system by applying per-axis scale and shift', 'convert a batch of voxel grids to meshes using cubify and render images with a shader']
```

Usage

```
{'create_R2N2_dataset': 'create an R2N2 dataset object with train split, shapenet directory, r2n2 directory, and splits file', 'load_model_by_index': 'load a 3D model by index from the R2N2 dataset with optional view indices and voxels', 'render_R2N2_models': 'render R2N2 dataset models using BlenderCamera with specified view indices and HardPhongShader', 'compute_camera_calibration': 'compute rotation and translation matrices from an extrinsic ShapeNet to PyTorch3D transformation matrix', 'review_R2N2_class': 'review the R2N2 class that loads 3D models, renderings, and voxelized data from the R2N2 dataset'}
```

## File: facebookresearch_banmo/third_party/pytorch3d/pytorch3d/datasets/r2n2/utils.py

Prompts

```
['create an R2N2 dataset object with train split, shapenet directory, r2n2 directory, and splits file', 'load a 3D model by index from the R2N2 dataset with optional view indices and voxels', 'render R2N2 dataset models using BlenderCamera with specified view indices and HardPhongShader', 'compute rotation and translation matrices from an extrinsic ShapeNet to PyTorch3D transformation matrix', 'review the R2N2 class that loads 3D models, renderings, and voxelized data from the R2N2 dataset', 'collate a list of R2N2 dataset dictionaries into stacked tensors for images, camera matrices, and voxels', 'compute a 4x4 camera extrinsic matrix from azimuth, elevation, and distance parameters', 'read a binvox file and return the coordinates of all nonzero voxels as a tensor', 'align source 3D points to a target coordinate system by applying per-axis scale and shift', 'convert a batch of voxel grids to meshes using cubify and render images with a shader']
```

Usage

```
{'collate_batched_R2N2': 'collate a list of R2N2 dataset dictionaries into stacked tensors for images, camera matrices, and voxels', 'compute_extrinsic_matrix': 'compute a 4x4 camera extrinsic matrix from azimuth, elevation, and distance parameters', 'read_binvox_coords': 'read a binvox file and return the coordinates of all nonzero voxels as a tensor', 'align_bbox': 'align source 3D points to a target coordinate system by applying per-axis scale and shift', 'render_cubified_voxels': 'convert a batch of voxel grids to meshes using cubify and render images with a shader'}
```

