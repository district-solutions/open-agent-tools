# Agent Python Tools

- repo: facebookresearch/robust-dynrf
- repo_uri: https://github.com/facebookresearch/robust-dynrf

## File: facebookresearch_robust-dynrf/dataLoader/colmap2nerf.py

Prompts

```
['convert COLMAP text export files to a NERF format transforms.json with camera poses and metadata', 'extract images from a video file at a specified FPS using ffmpeg with optional time slicing', 'run the full COLMAP SfM pipeline including feature extraction, matching, mapping, and bundle adjustment', 'compute the sharpness of an image using the variance of the Laplacian for quality assessment', 'convert a COLMAP quaternion vector to a 3x3 rotation matrix for camera pose transformation', 'create a DavisDataset instance to load video frames, optical flow, and foreground masks for dynamic NeRF training', 'calculate the average camera pose from a set of (N, 3, 4) poses using average_poses', 'center camera poses around the average pose for NDC space using center_poses', 'generate a spiral rendering path from camera poses using get_spiral for novel view synthesis', 'warp an image using optical flow with warp_flow to align frames temporally', 'create an NvidiaDataset instance to load NVIDIA dataset images, poses, flows, and masks for training', 'center camera poses around the average pose using center_poses for NDC coordinate conversion', 'resize optical flow tensors to new dimensions using resize_flow while preserving motion vectors', 'get ray directions for all pixels in camera coordinates given image height, width, and focal length', 'get ray origin and normalized directions in world coordinates from camera directions and a camera-to-world matrix', 'sample points along rays using hierarchical PDF-based sampling with optional deterministic or random uniform samples', 'sample 3D points along rays with linear or disparity-space depth sampling and optional perturbation', 'read a PFM image file and return the numpy array data along with its scale value']
```

Usage

```
{'convert_colmap_to_nerf_transforms': 'convert COLMAP text export files to a NERF format transforms.json with camera poses and metadata', 'run_ffmpeg_video_to_images': 'extract images from a video file at a specified FPS using ffmpeg with optional time slicing', 'run_colmap_sfm_pipeline': 'run the full COLMAP SfM pipeline including feature extraction, matching, mapping, and bundle adjustment', 'compute_image_sharpness': 'compute the sharpness of an image using the variance of the Laplacian for quality assessment', 'convert_quaternion_to_rotation_matrix': 'convert a COLMAP quaternion vector to a 3x3 rotation matrix for camera pose transformation'}
```

## File: facebookresearch_robust-dynrf/dataLoader/davis.py

Prompts

```
['convert COLMAP text export files to a NERF format transforms.json with camera poses and metadata', 'extract images from a video file at a specified FPS using ffmpeg with optional time slicing', 'run the full COLMAP SfM pipeline including feature extraction, matching, mapping, and bundle adjustment', 'compute the sharpness of an image using the variance of the Laplacian for quality assessment', 'convert a COLMAP quaternion vector to a 3x3 rotation matrix for camera pose transformation', 'create a DavisDataset instance to load video frames, optical flow, and foreground masks for dynamic NeRF training', 'calculate the average camera pose from a set of (N, 3, 4) poses using average_poses', 'center camera poses around the average pose for NDC space using center_poses', 'generate a spiral rendering path from camera poses using get_spiral for novel view synthesis', 'warp an image using optical flow with warp_flow to align frames temporally', 'create an NvidiaDataset instance to load NVIDIA dataset images, poses, flows, and masks for training', 'center camera poses around the average pose using center_poses for NDC coordinate conversion', 'resize optical flow tensors to new dimensions using resize_flow while preserving motion vectors', 'get ray directions for all pixels in camera coordinates given image height, width, and focal length', 'get ray origin and normalized directions in world coordinates from camera directions and a camera-to-world matrix', 'sample points along rays using hierarchical PDF-based sampling with optional deterministic or random uniform samples', 'sample 3D points along rays with linear or disparity-space depth sampling and optional perturbation', 'read a PFM image file and return the numpy array data along with its scale value']
```

Usage

```
{'create_davis_dataset': 'create a DavisDataset instance to load video frames, optical flow, and foreground masks for dynamic NeRF training', 'calculate_average_poses': 'calculate the average camera pose from a set of (N, 3, 4) poses using average_poses', 'center_poses_for_ndc': 'center camera poses around the average pose for NDC space using center_poses', 'generate_spiral_render_path': 'generate a spiral rendering path from camera poses using get_spiral for novel view synthesis', 'warp_image_with_flow': 'warp an image using optical flow with warp_flow to align frames temporally'}
```

## File: facebookresearch_robust-dynrf/dataLoader/nvidia.py

Prompts

```
['convert COLMAP text export files to a NERF format transforms.json with camera poses and metadata', 'extract images from a video file at a specified FPS using ffmpeg with optional time slicing', 'run the full COLMAP SfM pipeline including feature extraction, matching, mapping, and bundle adjustment', 'compute the sharpness of an image using the variance of the Laplacian for quality assessment', 'convert a COLMAP quaternion vector to a 3x3 rotation matrix for camera pose transformation', 'create a DavisDataset instance to load video frames, optical flow, and foreground masks for dynamic NeRF training', 'calculate the average camera pose from a set of (N, 3, 4) poses using average_poses', 'center camera poses around the average pose for NDC space using center_poses', 'generate a spiral rendering path from camera poses using get_spiral for novel view synthesis', 'warp an image using optical flow with warp_flow to align frames temporally', 'create an NvidiaDataset instance to load NVIDIA dataset images, poses, flows, and masks for training', 'center camera poses around the average pose using center_poses for NDC coordinate conversion', 'resize optical flow tensors to new dimensions using resize_flow while preserving motion vectors', 'get ray directions for all pixels in camera coordinates given image height, width, and focal length', 'get ray origin and normalized directions in world coordinates from camera directions and a camera-to-world matrix', 'sample points along rays using hierarchical PDF-based sampling with optional deterministic or random uniform samples', 'sample 3D points along rays with linear or disparity-space depth sampling and optional perturbation', 'read a PFM image file and return the numpy array data along with its scale value']
```

Usage

```
{'create_dataset_loader': 'create an NvidiaDataset instance to load NVIDIA dataset images, poses, flows, and masks for training', 'calculate_average_poses': 'calculate the average camera pose from a set of poses using average_poses function', 'center_camera_poses': 'center camera poses around the average pose using center_poses for NDC coordinate conversion', 'generate_spiral_render_path': 'generate a spiral rendering path from camera poses using get_spiral for novel view synthesis', 'resize_optical_flow': 'resize optical flow tensors to new dimensions using resize_flow while preserving motion vectors'}
```

## File: facebookresearch_robust-dynrf/dataLoader/ray_utils.py

Prompts

```
['convert COLMAP text export files to a NERF format transforms.json with camera poses and metadata', 'extract images from a video file at a specified FPS using ffmpeg with optional time slicing', 'run the full COLMAP SfM pipeline including feature extraction, matching, mapping, and bundle adjustment', 'compute the sharpness of an image using the variance of the Laplacian for quality assessment', 'convert a COLMAP quaternion vector to a 3x3 rotation matrix for camera pose transformation', 'create a DavisDataset instance to load video frames, optical flow, and foreground masks for dynamic NeRF training', 'calculate the average camera pose from a set of (N, 3, 4) poses using average_poses', 'center camera poses around the average pose for NDC space using center_poses', 'generate a spiral rendering path from camera poses using get_spiral for novel view synthesis', 'warp an image using optical flow with warp_flow to align frames temporally', 'create an NvidiaDataset instance to load NVIDIA dataset images, poses, flows, and masks for training', 'center camera poses around the average pose using center_poses for NDC coordinate conversion', 'resize optical flow tensors to new dimensions using resize_flow while preserving motion vectors', 'get ray directions for all pixels in camera coordinates given image height, width, and focal length', 'get ray origin and normalized directions in world coordinates from camera directions and a camera-to-world matrix', 'sample points along rays using hierarchical PDF-based sampling with optional deterministic or random uniform samples', 'sample 3D points along rays with linear or disparity-space depth sampling and optional perturbation', 'read a PFM image file and return the numpy array data along with its scale value']
```

Usage

```
{'get_ray_directions': 'get ray directions for all pixels in camera coordinates given image height, width, and focal length', 'get_rays': 'get ray origin and normalized directions in world coordinates from camera directions and a camera-to-world matrix', 'sample_pdf': 'sample points along rays using hierarchical PDF-based sampling with optional deterministic or random uniform samples', 'ray_marcher': 'sample 3D points along rays with linear or disparity-space depth sampling and optional perturbation', 'read_pfm': 'read a PFM image file and return the numpy array data along with its scale value'}
```

