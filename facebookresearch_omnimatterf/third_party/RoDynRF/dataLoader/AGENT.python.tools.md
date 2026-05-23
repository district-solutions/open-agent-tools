# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/RoDynRF/dataLoader/colmap2nerf.py

Prompts

```
['convert COLMAP text export files to a NeRF format transforms.json with camera poses and metadata', 'extract images from a video file at a specified FPS using ffmpeg with optional time slicing', 'run the full COLMAP SfM pipeline including feature extraction, matching, mapping, and bundle adjustment', 'compute the sharpness score of an image using the variance of the Laplacian method', 'convert a 4-element quaternion vector into a 3x3 rotation matrix using standard quaternion-to-matrix math', 'create a NvidiaPoseDataset instance to load RGB images, optical flow, and disparity data for NeRF training', 'load RGB images from rgb_1x directory and resize them using LANCZOS interpolation with configurable downsample factor', 'load forward and backward optical flow data from npz files and resize flow vectors with proper scaling', 'compute centered camera poses from poses_bounds.npy using average pose calculation and spiral rendering path generation', 'resize disparity maps using bilinear interpolation to match the target image dimensions', 'build a python module to compute ray directions for all pixels in camera coordinates given image height, width, and focal length', 'build a python module to compute ray origins and directions in world coordinates from camera directions and a camera-to-world transform', 'build a python module to perform hierarchical PDF sampling along ray bins using weights for NeRF-style volume rendering', 'build a python module to sample 3D points along rays with linear or disparity-space depth sampling and optional perturbation', 'create a function that reads a PFM image file and returns the pixel data array and scale factor']
```

Usage

```
{'convert_colmap_to_nerf_transforms': 'convert COLMAP text export files to a NeRF format transforms.json with camera poses and metadata', 'run_ffmpeg_video_to_images': 'extract images from a video file at a specified FPS using ffmpeg with optional time slicing', 'run_colmap_sfm_pipeline': 'run the full COLMAP SfM pipeline including feature extraction, matching, mapping, and bundle adjustment', 'compute_image_sharpness': 'compute the sharpness score of an image using the variance of the Laplacian method', 'convert_quaternion_to_rotation_matrix': 'convert a 4-element quaternion vector into a 3x3 rotation matrix using standard quaternion-to-matrix math'}
```

## File: facebookresearch_omnimatterf/third_party/RoDynRF/dataLoader/nvidia_pose.py

Prompts

```
['convert COLMAP text export files to a NeRF format transforms.json with camera poses and metadata', 'extract images from a video file at a specified FPS using ffmpeg with optional time slicing', 'run the full COLMAP SfM pipeline including feature extraction, matching, mapping, and bundle adjustment', 'compute the sharpness score of an image using the variance of the Laplacian method', 'convert a 4-element quaternion vector into a 3x3 rotation matrix using standard quaternion-to-matrix math', 'create a NvidiaPoseDataset instance to load RGB images, optical flow, and disparity data for NeRF training', 'load RGB images from rgb_1x directory and resize them using LANCZOS interpolation with configurable downsample factor', 'load forward and backward optical flow data from npz files and resize flow vectors with proper scaling', 'compute centered camera poses from poses_bounds.npy using average pose calculation and spiral rendering path generation', 'resize disparity maps using bilinear interpolation to match the target image dimensions', 'build a python module to compute ray directions for all pixels in camera coordinates given image height, width, and focal length', 'build a python module to compute ray origins and directions in world coordinates from camera directions and a camera-to-world transform', 'build a python module to perform hierarchical PDF sampling along ray bins using weights for NeRF-style volume rendering', 'build a python module to sample 3D points along rays with linear or disparity-space depth sampling and optional perturbation', 'create a function that reads a PFM image file and returns the pixel data array and scale factor']
```

Usage

```
{'create_nvidia_pose_dataset': 'create a NvidiaPoseDataset instance to load RGB images, optical flow, and disparity data for NeRF training', 'load_and_preprocess_images': 'load RGB images from rgb_1x directory and resize them using LANCZOS interpolation with configurable downsample factor', 'load_optical_flow_data': 'load forward and backward optical flow data from npz files and resize flow vectors with proper scaling', 'compute_camera_poses': 'compute centered camera poses from poses_bounds.npy using average pose calculation and spiral rendering path generation', 'resize_disparity_maps': 'resize disparity maps using bilinear interpolation to match the target image dimensions'}
```

## File: facebookresearch_omnimatterf/third_party/RoDynRF/dataLoader/ray_utils.py

Prompts

```
['convert COLMAP text export files to a NeRF format transforms.json with camera poses and metadata', 'extract images from a video file at a specified FPS using ffmpeg with optional time slicing', 'run the full COLMAP SfM pipeline including feature extraction, matching, mapping, and bundle adjustment', 'compute the sharpness score of an image using the variance of the Laplacian method', 'convert a 4-element quaternion vector into a 3x3 rotation matrix using standard quaternion-to-matrix math', 'create a NvidiaPoseDataset instance to load RGB images, optical flow, and disparity data for NeRF training', 'load RGB images from rgb_1x directory and resize them using LANCZOS interpolation with configurable downsample factor', 'load forward and backward optical flow data from npz files and resize flow vectors with proper scaling', 'compute centered camera poses from poses_bounds.npy using average pose calculation and spiral rendering path generation', 'resize disparity maps using bilinear interpolation to match the target image dimensions', 'build a python module to compute ray directions for all pixels in camera coordinates given image height, width, and focal length', 'build a python module to compute ray origins and directions in world coordinates from camera directions and a camera-to-world transform', 'build a python module to perform hierarchical PDF sampling along ray bins using weights for NeRF-style volume rendering', 'build a python module to sample 3D points along rays with linear or disparity-space depth sampling and optional perturbation', 'create a function that reads a PFM image file and returns the pixel data array and scale factor']
```

Usage

```
{'get_ray_directions': 'build a python module to compute ray directions for all pixels in camera coordinates given image height, width, and focal length', 'get_rays': 'build a python module to compute ray origins and directions in world coordinates from camera directions and a camera-to-world transform', 'sample_pdf': 'build a python module to perform hierarchical PDF sampling along ray bins using weights for NeRF-style volume rendering', 'ray_marcher': 'build a python module to sample 3D points along rays with linear or disparity-space depth sampling and optional perturbation', 'read_pfm': 'create a function that reads a PFM image file and returns the pixel data array and scale factor'}
```

