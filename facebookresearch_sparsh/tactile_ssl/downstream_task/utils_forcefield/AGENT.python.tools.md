# Agent Python Tools

- repo: facebookresearch/sparsh
- repo_uri: https://github.com/facebookresearch/sparsh

## File: facebookresearch_sparsh/tactile_ssl/downstream_task/utils_forcefield/ssl_flow_loss.py

Prompts

```
['build a Python module to instantiate SSL_loss with config and frame_ids for computing normal and shear force losses', 'create a PyTorch SSIM module that computes structural similarity loss between pairs of images using AvgPool2d', 'compute reprojection and edge-aware smoothness losses for normal force disparity predictions across multiple frames', 'compute photometric and first-order smoothness optical flow losses for shear force predictions using warp and robust loss', 'compute the combined L1 and SSIM reprojection loss between predicted and target image batches', 'create camera intrinsics matrix and inverse for a 224x224 image with 60 degree field of view', 'warp an image tensor back using optical flow via grid sampling and masking', 'calculate robust loss between original and warped image tensors using configurable norm parameters', 'compute spatial gradients of a tensor along x and y axes with configurable stride', 'calculate first order smoothness loss for optical flow weighted by image gradients']
```

Usage

```
{'build_SSL_loss': 'build a Python module to instantiate SSL_loss with config and frame_ids for computing normal and shear force losses', 'create_SSIM': 'create a PyTorch SSIM module that computes structural similarity loss between pairs of images using AvgPool2d', 'compute_losses_normal': 'compute reprojection and edge-aware smoothness losses for normal force disparity predictions across multiple frames', 'compute_losses_shear': 'compute photometric and first-order smoothness optical flow losses for shear force predictions using warp and robust loss', 'compute_reprojection_loss': 'compute the combined L1 and SSIM reprojection loss between predicted and target image batches'}
```

## File: facebookresearch_sparsh/tactile_ssl/downstream_task/utils_forcefield/ssl_utils.py

Prompts

```
['build a Python module to instantiate SSL_loss with config and frame_ids for computing normal and shear force losses', 'create a PyTorch SSIM module that computes structural similarity loss between pairs of images using AvgPool2d', 'compute reprojection and edge-aware smoothness losses for normal force disparity predictions across multiple frames', 'compute photometric and first-order smoothness optical flow losses for shear force predictions using warp and robust loss', 'compute the combined L1 and SSIM reprojection loss between predicted and target image batches', 'create camera intrinsics matrix and inverse for a 224x224 image with 60 degree field of view', 'warp an image tensor back using optical flow via grid sampling and masking', 'calculate robust loss between original and warped image tensors using configurable norm parameters', 'compute spatial gradients of a tensor along x and y axes with configurable stride', 'calculate first order smoothness loss for optical flow weighted by image gradients']
```

Usage

```
{'create_camera_intrinsics': 'create camera intrinsics matrix and inverse for a 224x224 image with 60 degree field of view', 'warp_image_with_flow': 'warp an image tensor back using optical flow via grid sampling and masking', 'calculate_robust_loss': 'calculate robust loss between original and warped image tensors using configurable norm parameters', 'compute_gradient': 'compute spatial gradients of a tensor along x and y axes with configurable stride', 'calculate_smoothness_loss': 'calculate first order smoothness loss for optical flow weighted by image gradients'}
```

