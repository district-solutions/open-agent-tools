# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/TensoRF/opt.py

Prompts

```
['run config_parser with default arguments to get TensoRF training defaults', 'run config_parser with a custom command list to override training parameters', 'build a TensorVMSplit training config by passing model_name and dataset_name arguments', 'build a TensorCP training config by passing model_name TensorCP and dataset arguments', 'render test set by passing render_test flag to config_parser command arguments', 'render rays through a TensoRF model in chunks to produce RGB and depth maps', 'evaluate a TensoRF model on a test dataset computing PSNR SSIM and LPIPS metrics', 'render a novel view path from camera-to-world matrices using a TensoRF model', 'review the OctreeRender_trilinear_fast function that chunks rays and calls tensorf for RGB and depth', 'summarize the evaluation function that renders test images and saves metrics to disk', 'run the TensoRF reconstruction pipeline to train a 3D scene representation from input data', 'render test set images using a trained TensoRF checkpoint for evaluation', 'export a trained TensoRF model as a PLY mesh file using density alpha thresholding', 'review the SimpleSampler class that manages batch sampling of training rays for TensoRF', 'review the reconstruction function training loop with adaptive resolution upsampling and regularization', 'convert a depth tensor to a colorized PIL image using a colormap for visualization', 'compute the structural similarity index between two RGB numpy images with configurable filter parameters', 'compute the LPIPS perceptual distance between two RGB numpy images using alex or vgg networks', 'extract a mesh from a 3D SDF tensor using marching cubes and save it as a PLY file', 'apply total variation loss to a batch of feature maps to encourage spatial smoothness']
```

Usage

```
{'run_config_parser_default': 'run config_parser with default arguments to get TensoRF training defaults', 'run_config_parser_custom_cmd': 'run config_parser with a custom command list to override training parameters', 'build_tensorvm_training_config': 'build a TensorVMSplit training config by passing model_name and dataset_name arguments', 'build_tensorcp_training_config': 'build a TensorCP training config by passing model_name TensorCP and dataset arguments', 'render_with_config_parser': 'render test set by passing render_test flag to config_parser command arguments'}
```

## File: facebookresearch_omnimatterf/third_party/TensoRF/renderer.py

Prompts

```
['run config_parser with default arguments to get TensoRF training defaults', 'run config_parser with a custom command list to override training parameters', 'build a TensorVMSplit training config by passing model_name and dataset_name arguments', 'build a TensorCP training config by passing model_name TensorCP and dataset arguments', 'render test set by passing render_test flag to config_parser command arguments', 'render rays through a TensoRF model in chunks to produce RGB and depth maps', 'evaluate a TensoRF model on a test dataset computing PSNR SSIM and LPIPS metrics', 'render a novel view path from camera-to-world matrices using a TensoRF model', 'review the OctreeRender_trilinear_fast function that chunks rays and calls tensorf for RGB and depth', 'summarize the evaluation function that renders test images and saves metrics to disk', 'run the TensoRF reconstruction pipeline to train a 3D scene representation from input data', 'render test set images using a trained TensoRF checkpoint for evaluation', 'export a trained TensoRF model as a PLY mesh file using density alpha thresholding', 'review the SimpleSampler class that manages batch sampling of training rays for TensoRF', 'review the reconstruction function training loop with adaptive resolution upsampling and regularization', 'convert a depth tensor to a colorized PIL image using a colormap for visualization', 'compute the structural similarity index between two RGB numpy images with configurable filter parameters', 'compute the LPIPS perceptual distance between two RGB numpy images using alex or vgg networks', 'extract a mesh from a 3D SDF tensor using marching cubes and save it as a PLY file', 'apply total variation loss to a batch of feature maps to encourage spatial smoothness']
```

Usage

```
{'render_rays_with_tensoRF': 'render rays through a TensoRF model in chunks to produce RGB and depth maps', 'evaluate_tensoRF_on_test_dataset': 'evaluate a TensoRF model on a test dataset computing PSNR SSIM and LPIPS metrics', 'render_novel_view_path': 'render a novel view path from camera-to-world matrices using a TensoRF model', 'review_OctreeRender_trilinear_fast': 'review the OctreeRender_trilinear_fast function that chunks rays and calls tensorf for RGB and depth', 'summarize_evaluation': 'summarize the evaluation function that renders test images and saves metrics to disk'}
```

## File: facebookresearch_omnimatterf/third_party/TensoRF/train.py

Prompts

```
['run config_parser with default arguments to get TensoRF training defaults', 'run config_parser with a custom command list to override training parameters', 'build a TensorVMSplit training config by passing model_name and dataset_name arguments', 'build a TensorCP training config by passing model_name TensorCP and dataset arguments', 'render test set by passing render_test flag to config_parser command arguments', 'render rays through a TensoRF model in chunks to produce RGB and depth maps', 'evaluate a TensoRF model on a test dataset computing PSNR SSIM and LPIPS metrics', 'render a novel view path from camera-to-world matrices using a TensoRF model', 'review the OctreeRender_trilinear_fast function that chunks rays and calls tensorf for RGB and depth', 'summarize the evaluation function that renders test images and saves metrics to disk', 'run the TensoRF reconstruction pipeline to train a 3D scene representation from input data', 'render test set images using a trained TensoRF checkpoint for evaluation', 'export a trained TensoRF model as a PLY mesh file using density alpha thresholding', 'review the SimpleSampler class that manages batch sampling of training rays for TensoRF', 'review the reconstruction function training loop with adaptive resolution upsampling and regularization', 'convert a depth tensor to a colorized PIL image using a colormap for visualization', 'compute the structural similarity index between two RGB numpy images with configurable filter parameters', 'compute the LPIPS perceptual distance between two RGB numpy images using alex or vgg networks', 'extract a mesh from a 3D SDF tensor using marching cubes and save it as a PLY file', 'apply total variation loss to a batch of feature maps to encourage spatial smoothness']
```

Usage

```
{'run_reconstruction': 'run the TensoRF reconstruction pipeline to train a 3D scene representation from input data', 'render_test_images': 'render test set images using a trained TensoRF checkpoint for evaluation', 'export_mesh_ply': 'export a trained TensoRF model as a PLY mesh file using density alpha thresholding', 'review_SimpleSampler': 'review the SimpleSampler class that manages batch sampling of training rays for TensoRF', 'review_reconstruction_loop': 'review the reconstruction function training loop with adaptive resolution upsampling and regularization'}
```

## File: facebookresearch_omnimatterf/third_party/TensoRF/utils.py

Prompts

```
['run config_parser with default arguments to get TensoRF training defaults', 'run config_parser with a custom command list to override training parameters', 'build a TensorVMSplit training config by passing model_name and dataset_name arguments', 'build a TensorCP training config by passing model_name TensorCP and dataset arguments', 'render test set by passing render_test flag to config_parser command arguments', 'render rays through a TensoRF model in chunks to produce RGB and depth maps', 'evaluate a TensoRF model on a test dataset computing PSNR SSIM and LPIPS metrics', 'render a novel view path from camera-to-world matrices using a TensoRF model', 'review the OctreeRender_trilinear_fast function that chunks rays and calls tensorf for RGB and depth', 'summarize the evaluation function that renders test images and saves metrics to disk', 'run the TensoRF reconstruction pipeline to train a 3D scene representation from input data', 'render test set images using a trained TensoRF checkpoint for evaluation', 'export a trained TensoRF model as a PLY mesh file using density alpha thresholding', 'review the SimpleSampler class that manages batch sampling of training rays for TensoRF', 'review the reconstruction function training loop with adaptive resolution upsampling and regularization', 'convert a depth tensor to a colorized PIL image using a colormap for visualization', 'compute the structural similarity index between two RGB numpy images with configurable filter parameters', 'compute the LPIPS perceptual distance between two RGB numpy images using alex or vgg networks', 'extract a mesh from a 3D SDF tensor using marching cubes and save it as a PLY file', 'apply total variation loss to a batch of feature maps to encourage spatial smoothness']
```

Usage

```
{'visualize_depth_tensor': 'convert a depth tensor to a colorized PIL image using a colormap for visualization', 'compute_rgb_ssim': 'compute the structural similarity index between two RGB numpy images with configurable filter parameters', 'compute_rgb_lpips': 'compute the LPIPS perceptual distance between two RGB numpy images using alex or vgg networks', 'export_sdf_to_ply': 'extract a mesh from a 3D SDF tensor using marching cubes and save it as a PLY file', 'apply_tvloss': 'apply total variation loss to a batch of feature maps to encourage spatial smoothness'}
```

