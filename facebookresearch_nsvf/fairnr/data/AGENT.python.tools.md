# Agent Python Tools

- repo: facebookresearch/nsvf
- repo_uri: https://github.com/facebookresearch/nsvf

## File: facebookresearch_nsvf/fairnr/data/data_utils.py

Prompts

```
['load an RGB image from a file path with optional alpha compositing and resizing', 'load a depth map image from a file path and resize to the target resolution', 'parse a view arguments string with ranges and steps into a list of view IDs', 'load camera intrinsic matrices from a file supporting multiple matrix formats', 'compute PSNR and SSIM image quality metrics between prediction and ground truth arrays', 'build a module that computes ray directions from UV coordinates, intrinsics, and camera extrinsics', 'create a rotation matrix from camera position, target point, and up direction vectors', 'compute surface normal maps from ray origins, directions, and depth values using finite differences', 'convert 6D rotation representations to 3x3 rotation matrices using Gram-Schmidt orthogonalization', 'build an octree structure from 3D point coordinates and a specified voxel size', 'build a FairseqDataset that loads per-shape data including intrinsics and global features from directory paths', 'create a dataset containing rendered RGB images, depth, masks, and camera extrinsics for 3D object views', 'create a wrapper dataset that samples pixels from rendered images using mask or bounding box strategies', 'create a wrapper dataset that transforms UV coordinates into world space ray directions and origins', 'create a wrapper dataset that enables infinite cyclic sampling from an underlying dataset with no epoch boundaries', 'create a circular camera trajectory function with configurable radius, axis, and rotation speed', 'create a zooming circular camera trajectory that varies radius over time', 'create a zooming linear camera trajectory with configurable min and max radius range', 'register a custom trajectory function in the TRAJECTORY_REGISTRY with a unique name', 'get a registered trajectory function from the registry by its name']
```

Usage

```
{'load_rgb_image': 'load an RGB image from a file path with optional alpha compositing and resizing', 'load_depth_map': 'load a depth map image from a file path and resize to the target resolution', 'parse_view_args': 'parse a view arguments string with ranges and steps into a list of view IDs', 'load_camera_intrinsics': 'load camera intrinsic matrices from a file supporting multiple matrix formats', 'compute_psnr_ssim': 'compute PSNR and SSIM image quality metrics between prediction and ground truth arrays'}
```

## File: facebookresearch_nsvf/fairnr/data/geometry.py

Prompts

```
['load an RGB image from a file path with optional alpha compositing and resizing', 'load a depth map image from a file path and resize to the target resolution', 'parse a view arguments string with ranges and steps into a list of view IDs', 'load camera intrinsic matrices from a file supporting multiple matrix formats', 'compute PSNR and SSIM image quality metrics between prediction and ground truth arrays', 'build a module that computes ray directions from UV coordinates, intrinsics, and camera extrinsics', 'create a rotation matrix from camera position, target point, and up direction vectors', 'compute surface normal maps from ray origins, directions, and depth values using finite differences', 'convert 6D rotation representations to 3x3 rotation matrices using Gram-Schmidt orthogonalization', 'build an octree structure from 3D point coordinates and a specified voxel size', 'build a FairseqDataset that loads per-shape data including intrinsics and global features from directory paths', 'create a dataset containing rendered RGB images, depth, masks, and camera extrinsics for 3D object views', 'create a wrapper dataset that samples pixels from rendered images using mask or bounding box strategies', 'create a wrapper dataset that transforms UV coordinates into world space ray directions and origins', 'create a wrapper dataset that enables infinite cyclic sampling from an underlying dataset with no epoch boundaries', 'create a circular camera trajectory function with configurable radius, axis, and rotation speed', 'create a zooming circular camera trajectory that varies radius over time', 'create a zooming linear camera trajectory with configurable min and max radius range', 'register a custom trajectory function in the TRAJECTORY_REGISTRY with a unique name', 'get a registered trajectory function from the registry by its name']
```

Usage

```
{'build_ray_directions': 'build a module that computes ray directions from UV coordinates, intrinsics, and camera extrinsics', 'create_look_at_rotation': 'create a rotation matrix from camera position, target point, and up direction vectors', 'compute_normal_map_from_depth': 'compute surface normal maps from ray origins, directions, and depth values using finite differences', 'convert_6d_rotation_to_matrix': 'convert 6D rotation representations to 3x3 rotation matrices using Gram-Schmidt orthogonalization', 'build_octree_from_points': 'build an octree structure from 3D point coordinates and a specified voxel size'}
```

## File: facebookresearch_nsvf/fairnr/data/shape_dataset.py

Prompts

```
['load an RGB image from a file path with optional alpha compositing and resizing', 'load a depth map image from a file path and resize to the target resolution', 'parse a view arguments string with ranges and steps into a list of view IDs', 'load camera intrinsic matrices from a file supporting multiple matrix formats', 'compute PSNR and SSIM image quality metrics between prediction and ground truth arrays', 'build a module that computes ray directions from UV coordinates, intrinsics, and camera extrinsics', 'create a rotation matrix from camera position, target point, and up direction vectors', 'compute surface normal maps from ray origins, directions, and depth values using finite differences', 'convert 6D rotation representations to 3x3 rotation matrices using Gram-Schmidt orthogonalization', 'build an octree structure from 3D point coordinates and a specified voxel size', 'build a FairseqDataset that loads per-shape data including intrinsics and global features from directory paths', 'create a dataset containing rendered RGB images, depth, masks, and camera extrinsics for 3D object views', 'create a wrapper dataset that samples pixels from rendered images using mask or bounding box strategies', 'create a wrapper dataset that transforms UV coordinates into world space ray directions and origins', 'create a wrapper dataset that enables infinite cyclic sampling from an underlying dataset with no epoch boundaries', 'create a circular camera trajectory function with configurable radius, axis, and rotation speed', 'create a zooming circular camera trajectory that varies radius over time', 'create a zooming linear camera trajectory with configurable min and max radius range', 'register a custom trajectory function in the TRAJECTORY_REGISTRY with a unique name', 'get a registered trajectory function from the registry by its name']
```

Usage

```
{'build_ShapeDataset': 'build a FairseqDataset that loads per-shape data including intrinsics and global features from directory paths', 'create_ShapeViewDataset': 'create a dataset containing rendered RGB images, depth, masks, and camera extrinsics for 3D object views', 'create_SampledPixelDataset': 'create a wrapper dataset that samples pixels from rendered images using mask or bounding box strategies', 'create_WorldCoordDataset': 'create a wrapper dataset that transforms UV coordinates into world space ray directions and origins', 'create_InfiniteDataset': 'create a wrapper dataset that enables infinite cyclic sampling from an underlying dataset with no epoch boundaries'}
```

## File: facebookresearch_nsvf/fairnr/data/trajectory.py

Prompts

```
['load an RGB image from a file path with optional alpha compositing and resizing', 'load a depth map image from a file path and resize to the target resolution', 'parse a view arguments string with ranges and steps into a list of view IDs', 'load camera intrinsic matrices from a file supporting multiple matrix formats', 'compute PSNR and SSIM image quality metrics between prediction and ground truth arrays', 'build a module that computes ray directions from UV coordinates, intrinsics, and camera extrinsics', 'create a rotation matrix from camera position, target point, and up direction vectors', 'compute surface normal maps from ray origins, directions, and depth values using finite differences', 'convert 6D rotation representations to 3x3 rotation matrices using Gram-Schmidt orthogonalization', 'build an octree structure from 3D point coordinates and a specified voxel size', 'build a FairseqDataset that loads per-shape data including intrinsics and global features from directory paths', 'create a dataset containing rendered RGB images, depth, masks, and camera extrinsics for 3D object views', 'create a wrapper dataset that samples pixels from rendered images using mask or bounding box strategies', 'create a wrapper dataset that transforms UV coordinates into world space ray directions and origins', 'create a wrapper dataset that enables infinite cyclic sampling from an underlying dataset with no epoch boundaries', 'create a circular camera trajectory function with configurable radius, axis, and rotation speed', 'create a zooming circular camera trajectory that varies radius over time', 'create a zooming linear camera trajectory with configurable min and max radius range', 'register a custom trajectory function in the TRAJECTORY_REGISTRY with a unique name', 'get a registered trajectory function from the registry by its name']
```

Usage

```
{'create_circle_trajectory': 'create a circular camera trajectory function with configurable radius, axis, and rotation speed', 'create_zoomin_circle_trajectory': 'create a zooming circular camera trajectory that varies radius over time', 'create_zoomin_line_trajectory': 'create a zooming linear camera trajectory with configurable min and max radius range', 'register_custom_trajectory': 'register a custom trajectory function in the TRAJECTORY_REGISTRY with a unique name', 'get_trajectory_by_name': 'get a registered trajectory function from the registry by its name'}
```

