# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/pytorch3d/datasets/r2n2/r2n2.py

Prompts

```
['create an R2N2 dataset object from a ShapeNet directory with train split and voxel loading enabled', 'load a specific 3D model from the R2N2 dataset by index with its camera views and renderings', 'render a batch of R2N2 models using BlenderCamera with HardPhongShader at specified view orientations', 'compute rotation and translation matrices from an R2N2 extrinsic matrix for PyTorch3D world space', 'review the R2N2 class to understand how it loads ShapeNet models with 24-view renderings and voxel data', 'collate a list of R2N2 dataset dictionaries into stacked tensors for images, camera matrices, and voxels', 'compute a 4x4 extrinsic camera matrix from azimuth, elevation, and distance parameters', 'read a binvox file and return nonzero voxel coordinates as a PyTorch tensor', 'align source 3D points to a target coordinate system using per-axis scale and shift', 'convert voxel grids to meshes using cubify and render them with a Phong shader']
```

Usage

```
{'create_R2N2_dataset': 'create an R2N2 dataset object from a ShapeNet directory with train split and voxel loading enabled', 'load_R2N2_model_by_index': 'load a specific 3D model from the R2N2 dataset by index with its camera views and renderings', 'render_R2N2_models': 'render a batch of R2N2 models using BlenderCamera with HardPhongShader at specified view orientations', 'compute_R2N2_camera_calibration': 'compute rotation and translation matrices from an R2N2 extrinsic matrix for PyTorch3D world space', 'review_R2N2_class': 'review the R2N2 class to understand how it loads ShapeNet models with 24-view renderings and voxel data'}
```

## File: facebookresearch_pytorch3d/pytorch3d/datasets/r2n2/utils.py

Prompts

```
['create an R2N2 dataset object from a ShapeNet directory with train split and voxel loading enabled', 'load a specific 3D model from the R2N2 dataset by index with its camera views and renderings', 'render a batch of R2N2 models using BlenderCamera with HardPhongShader at specified view orientations', 'compute rotation and translation matrices from an R2N2 extrinsic matrix for PyTorch3D world space', 'review the R2N2 class to understand how it loads ShapeNet models with 24-view renderings and voxel data', 'collate a list of R2N2 dataset dictionaries into stacked tensors for images, camera matrices, and voxels', 'compute a 4x4 extrinsic camera matrix from azimuth, elevation, and distance parameters', 'read a binvox file and return nonzero voxel coordinates as a PyTorch tensor', 'align source 3D points to a target coordinate system using per-axis scale and shift', 'convert voxel grids to meshes using cubify and render them with a Phong shader']
```

Usage

```
{'collate_batched_R2N2': 'collate a list of R2N2 dataset dictionaries into stacked tensors for images, camera matrices, and voxels', 'compute_extrinsic_matrix': 'compute a 4x4 extrinsic camera matrix from azimuth, elevation, and distance parameters', 'read_binvox_coords': 'read a binvox file and return nonzero voxel coordinates as a PyTorch tensor', 'align_bbox': 'align source 3D points to a target coordinate system using per-axis scale and shift', 'render_cubified_voxels': 'convert voxel grids to meshes using cubify and render them with a Phong shader'}
```

