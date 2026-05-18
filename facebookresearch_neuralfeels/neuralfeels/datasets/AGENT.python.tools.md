# Agent Python Tools

- repo: facebookresearch/neuralfeels
- repo_uri: https://github.com/facebookresearch/neuralfeels

## File: facebookresearch_neuralfeels/neuralfeels/datasets/data_util.py

Prompts

```
['create a FrameData object to store image, depth, and camera pose data for optimization frames', 'add new FrameData to an existing FrameData instance by concatenating or replacing frame attributes', 'delete FrameData at specified indices from an existing FrameData instance', 'index into a FrameData object to retrieve a single frame as a new FrameData instance', 'concatenate or replace data in a batch using numpy arrays or torch tensors', 'create a VisionDataset instance to load Realsense RGB and depth data from a directory with optional noise simulation', 'use VisionDataset getitem to retrieve an RGB image and corresponding depth array by index', 'call get_gt_seg on VisionDataset to get a binary segmentation mask for a given sample index', 'call get_avg_seg_area on VisionDataset to compute the average segmentation area across all samples', 'create a TactileDataset instance to load DIGIT tactile RGB images and optional depth with contact masking', 'build a python module to compute a signed distance field from a trimesh mesh with a given voxel size', 'create a function that loads a ground-truth mesh from a URDF file and returns trimesh and open3d representations', 'test the eval_sdf_interp function by evaluating an SDF interpolator on a set of 3D point cloud coordinates', 'refactor the colorize_mesh function to colorize a mesh by interpolating colors from a colored point cloud using a Gaussian kernel', 'summarize the saturate_colors function that increases the saturation of an RGB numpy array by a given factor', 'run the sphere test module to generate synthetic views around a 3D object using argparse', 'create a vision_sim instance that sets up a pyrender scene with cameras and lights on a sphere', 'render color depth and segmentation images from a given camera pose index in the sphere simulation', 'save rendered sphere simulation data including images depths and poses to a pickle file', 'backproject depth images into 3D point clouds using camera intrinsics and poses']
```

Usage

```
{'create_FrameData': 'create a FrameData object to store image, depth, and camera pose data for optimization frames', 'add_frame_data_FrameData': 'add new FrameData to an existing FrameData instance by concatenating or replacing frame attributes', 'delete_frame_data_FrameData': 'delete FrameData at specified indices from an existing FrameData instance', 'getitem_FrameData': 'index into a FrameData object to retrieve a single frame as a new FrameData instance', 'expand_data': 'concatenate or replace data in a batch using numpy arrays or torch tensors'}
```

## File: facebookresearch_neuralfeels/neuralfeels/datasets/dataset.py

Prompts

```
['create a FrameData object to store image, depth, and camera pose data for optimization frames', 'add new FrameData to an existing FrameData instance by concatenating or replacing frame attributes', 'delete FrameData at specified indices from an existing FrameData instance', 'index into a FrameData object to retrieve a single frame as a new FrameData instance', 'concatenate or replace data in a batch using numpy arrays or torch tensors', 'create a VisionDataset instance to load Realsense RGB and depth data from a directory with optional noise simulation', 'use VisionDataset getitem to retrieve an RGB image and corresponding depth array by index', 'call get_gt_seg on VisionDataset to get a binary segmentation mask for a given sample index', 'call get_avg_seg_area on VisionDataset to compute the average segmentation area across all samples', 'create a TactileDataset instance to load DIGIT tactile RGB images and optional depth with contact masking', 'build a python module to compute a signed distance field from a trimesh mesh with a given voxel size', 'create a function that loads a ground-truth mesh from a URDF file and returns trimesh and open3d representations', 'test the eval_sdf_interp function by evaluating an SDF interpolator on a set of 3D point cloud coordinates', 'refactor the colorize_mesh function to colorize a mesh by interpolating colors from a colored point cloud using a Gaussian kernel', 'summarize the saturate_colors function that increases the saturation of an RGB numpy array by a given factor', 'run the sphere test module to generate synthetic views around a 3D object using argparse', 'create a vision_sim instance that sets up a pyrender scene with cameras and lights on a sphere', 'render color depth and segmentation images from a given camera pose index in the sphere simulation', 'save rendered sphere simulation data including images depths and poses to a pickle file', 'backproject depth images into 3D point clouds using camera intrinsics and poses']
```

Usage

```
{'create_VisionDataset': 'create a VisionDataset instance to load Realsense RGB and depth data from a directory with optional noise simulation', 'use_VisionDataset_getitem': 'use VisionDataset getitem to retrieve an RGB image and corresponding depth array by index', 'call_VisionDataset_get_gt_seg': 'call get_gt_seg on VisionDataset to get a binary segmentation mask for a given sample index', 'call_VisionDataset_get_avg_seg_area': 'call get_avg_seg_area on VisionDataset to compute the average segmentation area across all samples', 'create_TactileDataset': 'create a TactileDataset instance to load DIGIT tactile RGB images and optional depth with contact masking'}
```

## File: facebookresearch_neuralfeels/neuralfeels/datasets/sdf_util.py

Prompts

```
['create a FrameData object to store image, depth, and camera pose data for optimization frames', 'add new FrameData to an existing FrameData instance by concatenating or replacing frame attributes', 'delete FrameData at specified indices from an existing FrameData instance', 'index into a FrameData object to retrieve a single frame as a new FrameData instance', 'concatenate or replace data in a batch using numpy arrays or torch tensors', 'create a VisionDataset instance to load Realsense RGB and depth data from a directory with optional noise simulation', 'use VisionDataset getitem to retrieve an RGB image and corresponding depth array by index', 'call get_gt_seg on VisionDataset to get a binary segmentation mask for a given sample index', 'call get_avg_seg_area on VisionDataset to compute the average segmentation area across all samples', 'create a TactileDataset instance to load DIGIT tactile RGB images and optional depth with contact masking', 'build a python module to compute a signed distance field from a trimesh mesh with a given voxel size', 'create a function that loads a ground-truth mesh from a URDF file and returns trimesh and open3d representations', 'test the eval_sdf_interp function by evaluating an SDF interpolator on a set of 3D point cloud coordinates', 'refactor the colorize_mesh function to colorize a mesh by interpolating colors from a colored point cloud using a Gaussian kernel', 'summarize the saturate_colors function that increases the saturation of an RGB numpy array by a given factor', 'run the sphere test module to generate synthetic views around a 3D object using argparse', 'create a vision_sim instance that sets up a pyrender scene with cameras and lights on a sphere', 'render color depth and segmentation images from a given camera pose index in the sphere simulation', 'save rendered sphere simulation data including images depths and poses to a pickle file', 'backproject depth images into 3D point clouds using camera intrinsics and poses']
```

Usage

```
{'build_sdf_from_mesh': 'build a python module to compute a signed distance field from a trimesh mesh with a given voxel size', 'create_load_gt_mesh': 'create a function that loads a ground-truth mesh from a URDF file and returns trimesh and open3d representations', 'test_eval_sdf_interp': 'test the eval_sdf_interp function by evaluating an SDF interpolator on a set of 3D point cloud coordinates', 'refactor_colorize_mesh': 'refactor the colorize_mesh function to colorize a mesh by interpolating colors from a colored point cloud using a Gaussian kernel', 'summarize_saturate_colors': 'summarize the saturate_colors function that increases the saturation of an RGB numpy array by a given factor'}
```

## File: facebookresearch_neuralfeels/neuralfeels/datasets/sphere_test.py

Prompts

```
['create a FrameData object to store image, depth, and camera pose data for optimization frames', 'add new FrameData to an existing FrameData instance by concatenating or replacing frame attributes', 'delete FrameData at specified indices from an existing FrameData instance', 'index into a FrameData object to retrieve a single frame as a new FrameData instance', 'concatenate or replace data in a batch using numpy arrays or torch tensors', 'create a VisionDataset instance to load Realsense RGB and depth data from a directory with optional noise simulation', 'use VisionDataset getitem to retrieve an RGB image and corresponding depth array by index', 'call get_gt_seg on VisionDataset to get a binary segmentation mask for a given sample index', 'call get_avg_seg_area on VisionDataset to compute the average segmentation area across all samples', 'create a TactileDataset instance to load DIGIT tactile RGB images and optional depth with contact masking', 'build a python module to compute a signed distance field from a trimesh mesh with a given voxel size', 'create a function that loads a ground-truth mesh from a URDF file and returns trimesh and open3d representations', 'test the eval_sdf_interp function by evaluating an SDF interpolator on a set of 3D point cloud coordinates', 'refactor the colorize_mesh function to colorize a mesh by interpolating colors from a colored point cloud using a Gaussian kernel', 'summarize the saturate_colors function that increases the saturation of an RGB numpy array by a given factor', 'run the sphere test module to generate synthetic views around a 3D object using argparse', 'create a vision_sim instance that sets up a pyrender scene with cameras and lights on a sphere', 'render color depth and segmentation images from a given camera pose index in the sphere simulation', 'save rendered sphere simulation data including images depths and poses to a pickle file', 'backproject depth images into 3D point clouds using camera intrinsics and poses']
```

Usage

```
{'run_sphere_sim': 'run the sphere test module to generate synthetic views around a 3D object using argparse', 'create_vision_sim': 'create a vision_sim instance that sets up a pyrender scene with cameras and lights on a sphere', 'render_views': 'render color depth and segmentation images from a given camera pose index in the sphere simulation', 'save_dataset': 'save rendered sphere simulation data including images depths and poses to a pickle file', 'backproject_pointcloud': 'backproject depth images into 3D point clouds using camera intrinsics and poses'}
```

