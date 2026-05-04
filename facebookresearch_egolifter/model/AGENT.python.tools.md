# Agent Python Tools

- repo: facebookresearch/egolifter
- repo_uri: https://github.com/facebookresearch/egolifter

## File: facebookresearch_egolifter/model/deform.py

Prompts

```
['build a DeformGaussian model with a DeformNetwork to warp 3D Gaussians by time frame id', 'review the forward_deform method that computes deformation offsets for xyz, rotation, and scale given a frame id', 'test the forward method to render a deformed 3D Gaussian frame given a camera viewpoint and frame id', 'refactor the training_step method to adjust noisy fid training or manual optimization logic for the deform network', 'summarize the configure_optimizers method that returns both the Gaussian and deform network optimizers', 'create a GaussianGrouping LightningModule from a DictConfig and optional Scene to load pretrained Gaussian splatting checkpoints', 'render a 3D Gaussian splatting scene from a viewpoint camera and return the render package with object features', 'compute the combined L1 and SSIM reconstruction loss between a rendered image and ground truth image', 'run a forward pass on a batch, render the scene, and compute reconstruction loss with PSNR metrics', 'evaluate a batch during testing by computing reconstruction metrics for dynamic and static pixel masks', 'build a python module to initialize Unc2DUnet with a config object and scene for uncertainty-guided 3D reconstruction', 'create a function that computes NeRF-W style reconstruction loss with uncertainty regularization using softplus or sigmoid activation', 'build a python module to generate an uncertainty mask from a batch image using a U-Net backbone network', 'create a function that renders a viewpoint camera image and computes reconstruction loss with optional contrastive weighting', 'build a python module to perform a manual optimization training step with backward pass and optimizer updates', 'create a VanillaGaussian LightningModule with a DictConfig and optional Scene for 3D Gaussian splatting', 'build a method to initialize Gaussians from a point cloud or load from a saved PLY iteration', 'test the compute_recon_metrics function to calculate L1, L2, and PSNR between rendered and ground truth images', 'run a training step that computes reconstruction loss and logs metrics for Gaussian splatting optimization', 'review the density_control method that handles densification and pruning of 3D Gaussians during training']
```

Usage

```
{'build_DeformGaussian': 'build a DeformGaussian model with a DeformNetwork to warp 3D Gaussians by time frame id', 'review_forward_deform': 'review the forward_deform method that computes deformation offsets for xyz, rotation, and scale given a frame id', 'test_forward': 'test the forward method to render a deformed 3D Gaussian frame given a camera viewpoint and frame id', 'refactor_training_step': 'refactor the training_step method to adjust noisy fid training or manual optimization logic for the deform network', 'summarize_configure_optimizers': 'summarize the configure_optimizers method that returns both the Gaussian and deform network optimizers'}
```

## File: facebookresearch_egolifter/model/gaussian_grouping.py

Prompts

```
['build a DeformGaussian model with a DeformNetwork to warp 3D Gaussians by time frame id', 'review the forward_deform method that computes deformation offsets for xyz, rotation, and scale given a frame id', 'test the forward method to render a deformed 3D Gaussian frame given a camera viewpoint and frame id', 'refactor the training_step method to adjust noisy fid training or manual optimization logic for the deform network', 'summarize the configure_optimizers method that returns both the Gaussian and deform network optimizers', 'create a GaussianGrouping LightningModule from a DictConfig and optional Scene to load pretrained Gaussian splatting checkpoints', 'render a 3D Gaussian splatting scene from a viewpoint camera and return the render package with object features', 'compute the combined L1 and SSIM reconstruction loss between a rendered image and ground truth image', 'run a forward pass on a batch, render the scene, and compute reconstruction loss with PSNR metrics', 'evaluate a batch during testing by computing reconstruction metrics for dynamic and static pixel masks', 'build a python module to initialize Unc2DUnet with a config object and scene for uncertainty-guided 3D reconstruction', 'create a function that computes NeRF-W style reconstruction loss with uncertainty regularization using softplus or sigmoid activation', 'build a python module to generate an uncertainty mask from a batch image using a U-Net backbone network', 'create a function that renders a viewpoint camera image and computes reconstruction loss with optional contrastive weighting', 'build a python module to perform a manual optimization training step with backward pass and optimizer updates', 'create a VanillaGaussian LightningModule with a DictConfig and optional Scene for 3D Gaussian splatting', 'build a method to initialize Gaussians from a point cloud or load from a saved PLY iteration', 'test the compute_recon_metrics function to calculate L1, L2, and PSNR between rendered and ground truth images', 'run a training step that computes reconstruction loss and logs metrics for Gaussian splatting optimization', 'review the density_control method that handles densification and pruning of 3D Gaussians during training']
```

Usage

```
{'init_GaussianGrouping': 'create a GaussianGrouping LightningModule from a DictConfig and optional Scene to load pretrained Gaussian splatting checkpoints', 'forward_GaussianGrouping': 'render a 3D Gaussian splatting scene from a viewpoint camera and return the render package with object features', 'compute_recon_loss_GaussianGrouping': 'compute the combined L1 and SSIM reconstruction loss between a rendered image and ground truth image', 'forward_and_compute_loss_GaussianGrouping': 'run a forward pass on a batch, render the scene, and compute reconstruction loss with PSNR metrics', 'test_step_GaussianGrouping': 'evaluate a batch during testing by computing reconstruction metrics for dynamic and static pixel masks'}
```

## File: facebookresearch_egolifter/model/unc_2d_unet.py

Prompts

```
['build a DeformGaussian model with a DeformNetwork to warp 3D Gaussians by time frame id', 'review the forward_deform method that computes deformation offsets for xyz, rotation, and scale given a frame id', 'test the forward method to render a deformed 3D Gaussian frame given a camera viewpoint and frame id', 'refactor the training_step method to adjust noisy fid training or manual optimization logic for the deform network', 'summarize the configure_optimizers method that returns both the Gaussian and deform network optimizers', 'create a GaussianGrouping LightningModule from a DictConfig and optional Scene to load pretrained Gaussian splatting checkpoints', 'render a 3D Gaussian splatting scene from a viewpoint camera and return the render package with object features', 'compute the combined L1 and SSIM reconstruction loss between a rendered image and ground truth image', 'run a forward pass on a batch, render the scene, and compute reconstruction loss with PSNR metrics', 'evaluate a batch during testing by computing reconstruction metrics for dynamic and static pixel masks', 'build a python module to initialize Unc2DUnet with a config object and scene for uncertainty-guided 3D reconstruction', 'create a function that computes NeRF-W style reconstruction loss with uncertainty regularization using softplus or sigmoid activation', 'build a python module to generate an uncertainty mask from a batch image using a U-Net backbone network', 'create a function that renders a viewpoint camera image and computes reconstruction loss with optional contrastive weighting', 'build a python module to perform a manual optimization training step with backward pass and optimizer updates', 'create a VanillaGaussian LightningModule with a DictConfig and optional Scene for 3D Gaussian splatting', 'build a method to initialize Gaussians from a point cloud or load from a saved PLY iteration', 'test the compute_recon_metrics function to calculate L1, L2, and PSNR between rendered and ground truth images', 'run a training step that computes reconstruction loss and logs metrics for Gaussian splatting optimization', 'review the density_control method that handles densification and pruning of 3D Gaussians during training']
```

Usage

```
{'init_Unc2DUnet': 'build a python module to initialize Unc2DUnet with a config object and scene for uncertainty-guided 3D reconstruction', 'compute_recon_loss': 'create a function that computes NeRF-W style reconstruction loss with uncertainty regularization using softplus or sigmoid activation', 'get_unc_mask': 'build a python module to generate an uncertainty mask from a batch image using a U-Net backbone network', 'forward_and_compute_loss': 'create a function that renders a viewpoint camera image and computes reconstruction loss with optional contrastive weighting', 'training_step': 'build a python module to perform a manual optimization training step with backward pass and optimizer updates'}
```

## File: facebookresearch_egolifter/model/vanilla.py

Prompts

```
['build a DeformGaussian model with a DeformNetwork to warp 3D Gaussians by time frame id', 'review the forward_deform method that computes deformation offsets for xyz, rotation, and scale given a frame id', 'test the forward method to render a deformed 3D Gaussian frame given a camera viewpoint and frame id', 'refactor the training_step method to adjust noisy fid training or manual optimization logic for the deform network', 'summarize the configure_optimizers method that returns both the Gaussian and deform network optimizers', 'create a GaussianGrouping LightningModule from a DictConfig and optional Scene to load pretrained Gaussian splatting checkpoints', 'render a 3D Gaussian splatting scene from a viewpoint camera and return the render package with object features', 'compute the combined L1 and SSIM reconstruction loss between a rendered image and ground truth image', 'run a forward pass on a batch, render the scene, and compute reconstruction loss with PSNR metrics', 'evaluate a batch during testing by computing reconstruction metrics for dynamic and static pixel masks', 'build a python module to initialize Unc2DUnet with a config object and scene for uncertainty-guided 3D reconstruction', 'create a function that computes NeRF-W style reconstruction loss with uncertainty regularization using softplus or sigmoid activation', 'build a python module to generate an uncertainty mask from a batch image using a U-Net backbone network', 'create a function that renders a viewpoint camera image and computes reconstruction loss with optional contrastive weighting', 'build a python module to perform a manual optimization training step with backward pass and optimizer updates', 'create a VanillaGaussian LightningModule with a DictConfig and optional Scene for 3D Gaussian splatting', 'build a method to initialize Gaussians from a point cloud or load from a saved PLY iteration', 'test the compute_recon_metrics function to calculate L1, L2, and PSNR between rendered and ground truth images', 'run a training step that computes reconstruction loss and logs metrics for Gaussian splatting optimization', 'review the density_control method that handles densification and pruning of 3D Gaussians during training']
```

Usage

```
{'create_VanillaGaussian_module': 'create a VanillaGaussian LightningModule with a DictConfig and optional Scene for 3D Gaussian splatting', 'build_init_or_load_gaussians': 'build a method to initialize Gaussians from a point cloud or load from a saved PLY iteration', 'test_compute_recon_metrics': 'test the compute_recon_metrics function to calculate L1, L2, and PSNR between rendered and ground truth images', 'run_training_step': 'run a training step that computes reconstruction loss and logs metrics for Gaussian splatting optimization', 'review_density_control': 'review the density_control method that handles densification and pruning of 3D Gaussians during training'}
```

