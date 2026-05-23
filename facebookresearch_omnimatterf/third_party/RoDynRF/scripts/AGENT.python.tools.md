# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/RoDynRF/scripts/flow_utils.py

Prompts

```
['convert an optical flow numpy array into a Middlebury color-coded image for visualization', 'resize an optical flow tensor to new dimensions while scaling flow values proportionally', 'warp an image using an optical flow field via cv2.remap with cubic interpolation', 'compute forward-backward consistency error between forward and backward optical flow fields', 'compute geometric epipolar distance between point correspondences given camera pose and intrinsics', 'run the script to compute depth maps for images in a dataset folder using a MidasNet model', 'run the MidasNet model to predict depth maps from RGB images in an input directory', 'create output directories for saving depth map numpy files and PNG images', 'read an image file and convert it to an RGB array normalized to 0-1 range', 'generate depth map outputs as both numpy arrays and normalized uint16 PNG images', 'run the RAFT model to generate forward and backward optical flow for a sequence of images', 'compute forward and backward consistency masks from optical flow fields using the warp consistency check', 'warp an image using a given optical flow field with cubic interpolation via OpenCV remap', 'load an image file and convert it to a normalized PyTorch tensor on the GPU device', 'create a directory if it does not already exist using os.makedirs', 'run the script to compute epipolar error-based motion masks for a dataset using optical flow', 'compute the Sampson error between two sets of 2D points given a fundamental matrix', 'generate a normalized UV coordinate grid for an image with optional homogeneous coordinates', 'compute mean and scale statistics for a batch of image tensors using L1 or L2 norm']
```

Usage

```
{'convert_flow_to_color_image': 'convert an optical flow numpy array into a Middlebury color-coded image for visualization', 'resize_optical_flow': 'resize an optical flow tensor to new dimensions while scaling flow values proportionally', 'warp_image_with_flow': 'warp an image using an optical flow field via cv2.remap with cubic interpolation', 'check_flow_consistency': 'compute forward-backward consistency error between forward and backward optical flow fields', 'compute_epipolar_distance': 'compute geometric epipolar distance between point correspondences given camera pose and intrinsics'}
```

## File: facebookresearch_omnimatterf/third_party/RoDynRF/scripts/generate_depth.py

Prompts

```
['convert an optical flow numpy array into a Middlebury color-coded image for visualization', 'resize an optical flow tensor to new dimensions while scaling flow values proportionally', 'warp an image using an optical flow field via cv2.remap with cubic interpolation', 'compute forward-backward consistency error between forward and backward optical flow fields', 'compute geometric epipolar distance between point correspondences given camera pose and intrinsics', 'run the script to compute depth maps for images in a dataset folder using a MidasNet model', 'run the MidasNet model to predict depth maps from RGB images in an input directory', 'create output directories for saving depth map numpy files and PNG images', 'read an image file and convert it to an RGB array normalized to 0-1 range', 'generate depth map outputs as both numpy arrays and normalized uint16 PNG images', 'run the RAFT model to generate forward and backward optical flow for a sequence of images', 'compute forward and backward consistency masks from optical flow fields using the warp consistency check', 'warp an image using a given optical flow field with cubic interpolation via OpenCV remap', 'load an image file and convert it to a normalized PyTorch tensor on the GPU device', 'create a directory if it does not already exist using os.makedirs', 'run the script to compute epipolar error-based motion masks for a dataset using optical flow', 'compute the Sampson error between two sets of 2D points given a fundamental matrix', 'generate a normalized UV coordinate grid for an image with optional homogeneous coordinates', 'compute mean and scale statistics for a batch of image tensors using L1 or L2 norm']
```

Usage

```
{'run_depth_generation': 'run the script to compute depth maps for images in a dataset folder using a MidasNet model', 'run_MidasNet_inference': 'run the MidasNet model to predict depth maps from RGB images in an input directory', 'create_dir_output_folders': 'create output directories for saving depth map numpy files and PNG images', 'read_image_RGB': 'read an image file and convert it to an RGB array normalized to 0-1 range', 'generate_depth_numpy_png': 'generate depth map outputs as both numpy arrays and normalized uint16 PNG images'}
```

## File: facebookresearch_omnimatterf/third_party/RoDynRF/scripts/generate_flow.py

Prompts

```
['convert an optical flow numpy array into a Middlebury color-coded image for visualization', 'resize an optical flow tensor to new dimensions while scaling flow values proportionally', 'warp an image using an optical flow field via cv2.remap with cubic interpolation', 'compute forward-backward consistency error between forward and backward optical flow fields', 'compute geometric epipolar distance between point correspondences given camera pose and intrinsics', 'run the script to compute depth maps for images in a dataset folder using a MidasNet model', 'run the MidasNet model to predict depth maps from RGB images in an input directory', 'create output directories for saving depth map numpy files and PNG images', 'read an image file and convert it to an RGB array normalized to 0-1 range', 'generate depth map outputs as both numpy arrays and normalized uint16 PNG images', 'run the RAFT model to generate forward and backward optical flow for a sequence of images', 'compute forward and backward consistency masks from optical flow fields using the warp consistency check', 'warp an image using a given optical flow field with cubic interpolation via OpenCV remap', 'load an image file and convert it to a normalized PyTorch tensor on the GPU device', 'create a directory if it does not already exist using os.makedirs', 'run the script to compute epipolar error-based motion masks for a dataset using optical flow', 'compute the Sampson error between two sets of 2D points given a fundamental matrix', 'generate a normalized UV coordinate grid for an image with optional homogeneous coordinates', 'compute mean and scale statistics for a batch of image tensors using L1 or L2 norm']
```

Usage

```
{'run_optical_flow_generation': 'run the RAFT model to generate forward and backward optical flow for a sequence of images', 'compute_fwdbwd_mask': 'compute forward and backward consistency masks from optical flow fields using the warp consistency check', 'warp_flow': 'warp an image using a given optical flow field with cubic interpolation via OpenCV remap', 'load_image': 'load an image file and convert it to a normalized PyTorch tensor on the GPU device', 'create_dir': 'create a directory if it does not already exist using os.makedirs'}
```

## File: facebookresearch_omnimatterf/third_party/RoDynRF/scripts/our_mask.py

Prompts

```
['convert an optical flow numpy array into a Middlebury color-coded image for visualization', 'resize an optical flow tensor to new dimensions while scaling flow values proportionally', 'warp an image using an optical flow field via cv2.remap with cubic interpolation', 'compute forward-backward consistency error between forward and backward optical flow fields', 'compute geometric epipolar distance between point correspondences given camera pose and intrinsics', 'run the script to compute depth maps for images in a dataset folder using a MidasNet model', 'run the MidasNet model to predict depth maps from RGB images in an input directory', 'create output directories for saving depth map numpy files and PNG images', 'read an image file and convert it to an RGB array normalized to 0-1 range', 'generate depth map outputs as both numpy arrays and normalized uint16 PNG images', 'run the RAFT model to generate forward and backward optical flow for a sequence of images', 'compute forward and backward consistency masks from optical flow fields using the warp consistency check', 'warp an image using a given optical flow field with cubic interpolation via OpenCV remap', 'load an image file and convert it to a normalized PyTorch tensor on the GPU device', 'create a directory if it does not already exist using os.makedirs', 'run the script to compute epipolar error-based motion masks for a dataset using optical flow', 'compute the Sampson error between two sets of 2D points given a fundamental matrix', 'generate a normalized UV coordinate grid for an image with optional homogeneous coordinates', 'compute mean and scale statistics for a batch of image tensors using L1 or L2 norm']
```

Usage

```
{'run_epipolar_motion_mask': 'run the script to compute epipolar error-based motion masks for a dataset using optical flow', 'compute_sampson_error': 'compute the Sampson error between two sets of 2D points given a fundamental matrix', 'get_uv_grid': 'generate a normalized UV coordinate grid for an image with optional homogeneous coordinates', 'warp_flow': 'warp an image using an optical flow field with OpenCV remapping', 'get_stats': 'compute mean and scale statistics for a batch of image tensors using L1 or L2 norm'}
```

