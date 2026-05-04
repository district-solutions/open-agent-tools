# Agent Python Tools

- repo: facebookresearch/egocentricsplats
- repo_uri: https://github.com/facebookresearch/egocentric_splats

## File: facebookresearch_egocentricsplats/model/GS2D_gsplat.py

Prompts

```
['create a Gaussians2D instance with a DictConfig and SceneInfo for 2D Gaussian Splatting training', 'render a scene from a Camera viewpoint using Gaussians2D with scaling modifier and sh degree', 'run the forward pass of Gaussians2D with intrinsics and view matrices to render RGB and depth', 'execute a training step for Gaussians2D computing image depth normal and distortion losses', 'compute a valid mask filtering NaN Inf and out-of-range values from tensor data', 'calculate the inverse depth loss from a rendered depth map using sparse 2D point coordinates and huber or l1 loss', 'create an ImageLoss instance with rgb or luminance color space and alex or vgg lpips network for computing image losses', 'run the ImageLoss callable to compute l1, huber, ssim, dssim, psnr, or lpips losses between a captured and ground truth image', 'compute the structural similarity index between two images using a gaussian window and configurable window size', 'compute the KL divergence between a target occupancy density rho and a predicted sigmoid rho_hat tensor', 'create Gaussian splats with optimizers from a point cloud for 3D scene reconstruction', 'render a 3D Gaussian splat scene from a specified camera viewpoint with depth and normals', 'save trained Gaussian splats parameters including means, scales, rotations, and colors to a PLY file', 'load Gaussian splats parameters from a PLY file to resume training or inference', 'apply a view-dependent 3D Gaussian filter based on minimum depth for smoother rendering']
```

Usage

```
{'create_Gaussians2D': 'create a Gaussians2D instance with a DictConfig and SceneInfo for 2D Gaussian Splatting training', 'render_Gaussians2D': 'render a scene from a Camera viewpoint using Gaussians2D with scaling modifier and sh degree', 'forward_Gaussians2D': 'run the forward pass of Gaussians2D with intrinsics and view matrices to render RGB and depth', 'training_step_Gaussians2D': 'execute a training step for Gaussians2D computing image depth normal and distortion losses', 'get_valid_mask': 'compute a valid mask filtering NaN Inf and out-of-range values from tensor data'}
```

## File: facebookresearch_egocentricsplats/model/loss.py

Prompts

```
['create a Gaussians2D instance with a DictConfig and SceneInfo for 2D Gaussian Splatting training', 'render a scene from a Camera viewpoint using Gaussians2D with scaling modifier and sh degree', 'run the forward pass of Gaussians2D with intrinsics and view matrices to render RGB and depth', 'execute a training step for Gaussians2D computing image depth normal and distortion losses', 'compute a valid mask filtering NaN Inf and out-of-range values from tensor data', 'calculate the inverse depth loss from a rendered depth map using sparse 2D point coordinates and huber or l1 loss', 'create an ImageLoss instance with rgb or luminance color space and alex or vgg lpips network for computing image losses', 'run the ImageLoss callable to compute l1, huber, ssim, dssim, psnr, or lpips losses between a captured and ground truth image', 'compute the structural similarity index between two images using a gaussian window and configurable window size', 'compute the KL divergence between a target occupancy density rho and a predicted sigmoid rho_hat tensor', 'create Gaussian splats with optimizers from a point cloud for 3D scene reconstruction', 'render a 3D Gaussian splat scene from a specified camera viewpoint with depth and normals', 'save trained Gaussian splats parameters including means, scales, rotations, and colors to a PLY file', 'load Gaussian splats parameters from a PLY file to resume training or inference', 'apply a view-dependent 3D Gaussian filter based on minimum depth for smoother rendering']
```

Usage

```
{'calculate_inverse_depth_loss': 'calculate the inverse depth loss from a rendered depth map using sparse 2D point coordinates and huber or l1 loss', 'create_ImageLoss': 'create an ImageLoss instance with rgb or luminance color space and alex or vgg lpips network for computing image losses', 'run_ImageLoss_call': 'run the ImageLoss callable to compute l1, huber, ssim, dssim, psnr, or lpips losses between a captured and ground truth image', 'compute_ssim': 'compute the structural similarity index between two images using a gaussian window and configurable window size', 'compute_kl_divergence': 'compute the KL divergence between a target occupancy density rho and a predicted sigmoid rho_hat tensor'}
```

## File: facebookresearch_egocentricsplats/model/vanilla_gsplat.py

Prompts

```
['create a Gaussians2D instance with a DictConfig and SceneInfo for 2D Gaussian Splatting training', 'render a scene from a Camera viewpoint using Gaussians2D with scaling modifier and sh degree', 'run the forward pass of Gaussians2D with intrinsics and view matrices to render RGB and depth', 'execute a training step for Gaussians2D computing image depth normal and distortion losses', 'compute a valid mask filtering NaN Inf and out-of-range values from tensor data', 'calculate the inverse depth loss from a rendered depth map using sparse 2D point coordinates and huber or l1 loss', 'create an ImageLoss instance with rgb or luminance color space and alex or vgg lpips network for computing image losses', 'run the ImageLoss callable to compute l1, huber, ssim, dssim, psnr, or lpips losses between a captured and ground truth image', 'compute the structural similarity index between two images using a gaussian window and configurable window size', 'compute the KL divergence between a target occupancy density rho and a predicted sigmoid rho_hat tensor', 'create Gaussian splats with optimizers from a point cloud for 3D scene reconstruction', 'render a 3D Gaussian splat scene from a specified camera viewpoint with depth and normals', 'save trained Gaussian splats parameters including means, scales, rotations, and colors to a PLY file', 'load Gaussian splats parameters from a PLY file to resume training or inference', 'apply a view-dependent 3D Gaussian filter based on minimum depth for smoother rendering']
```

Usage

```
{'create_gaussian_splats_with_optimizers': 'create Gaussian splats with optimizers from a point cloud for 3D scene reconstruction', 'render_scene_from_camera': 'render a 3D Gaussian splat scene from a specified camera viewpoint with depth and normals', 'save_gaussian_splats_to_ply': 'save trained Gaussian splats parameters including means, scales, rotations, and colors to a PLY file', 'load_gaussian_splats_from_ply': 'load Gaussian splats parameters from a PLY file to resume training or inference', 'apply_3d_depth_based_filter': 'apply a view-dependent 3D Gaussian filter based on minimum depth for smoother rendering'}
```

