# Agent Python Tools

- repo: facebookresearch/localrf
- repo_uri: https://github.com/facebookresearch/localrf

## File: facebookresearch_localrf/localTensoRF/local_tensorfs.py

Prompts

```
['create a LocalTensorfs model with fov, n_init_frames, n_overlap, WH, and learning rate parameters for self-calibrating local tensor factorization', 'append a new camera frame with pose parameters and optimizers to the LocalTensorfs model for incremental training', 'append a new radiance field with blending weights to the LocalTensorfs model for multi-view scene reconstruction', 'run optimizer_step on the LocalTensorfs model to optimize camera poses, exposure, and radiance field parameters with loss backward pass', 'render rays through the LocalTensorfs model to get RGB colors, depth maps, and ray directions for given ray and view IDs', 'run the config_parser function to parse default arguments for local TensoRF training', 'run the config_parser function with a custom command list to override default training arguments', 'build a configuration with custom learning rate and voxel settings for TensorVMSplit model training', 'build a configuration with render_only mode enabled to render from a saved checkpoint file', 'review the config_parser function to understand all available training and rendering arguments', 'render RGB and depth map frames from a Local TensoRF model using camera poses and ray IDs', 'render test frames and compute MSE and SSIM metrics against ground truth RGB images', 'render forward and backward optical flow comparisons between predicted and ground truth flow fields', 'render depth error comparison visualizations between predicted and ground truth inverse depth maps', 'render frames and save RGB, depth, and camera pose videos as MP4 files to disk', 'run the local TensoRF reconstruction pipeline with pose optimization and progressive refinement', 'render test frames from a trained checkpoint using the render_test function', 'render a smooth spline camera path from poses using the render_frames function', 'save camera poses and intrinsics to a transforms.json file using save_transforms', 'run the train.py CLI entry point to start reconstruction or rendering via config_parser']
```

Usage

```
{'create_local_tensorfs_model': 'create a LocalTensorfs model with fov, n_init_frames, n_overlap, WH, and learning rate parameters for self-calibrating local tensor factorization', 'append_frame_to_local_tensorfs': 'append a new camera frame with pose parameters and optimizers to the LocalTensorfs model for incremental training', 'append_rf_to_local_tensorfs': 'append a new radiance field with blending weights to the LocalTensorfs model for multi-view scene reconstruction', 'optimize_poses_and_rf': 'run optimizer_step on the LocalTensorfs model to optimize camera poses, exposure, and radiance field parameters with loss backward pass', 'forward_render_rays': 'render rays through the LocalTensorfs model to get RGB colors, depth maps, and ray directions for given ray and view IDs'}
```

## File: facebookresearch_localrf/localTensoRF/opt.py

Prompts

```
['create a LocalTensorfs model with fov, n_init_frames, n_overlap, WH, and learning rate parameters for self-calibrating local tensor factorization', 'append a new camera frame with pose parameters and optimizers to the LocalTensorfs model for incremental training', 'append a new radiance field with blending weights to the LocalTensorfs model for multi-view scene reconstruction', 'run optimizer_step on the LocalTensorfs model to optimize camera poses, exposure, and radiance field parameters with loss backward pass', 'render rays through the LocalTensorfs model to get RGB colors, depth maps, and ray directions for given ray and view IDs', 'run the config_parser function to parse default arguments for local TensoRF training', 'run the config_parser function with a custom command list to override default training arguments', 'build a configuration with custom learning rate and voxel settings for TensorVMSplit model training', 'build a configuration with render_only mode enabled to render from a saved checkpoint file', 'review the config_parser function to understand all available training and rendering arguments', 'render RGB and depth map frames from a Local TensoRF model using camera poses and ray IDs', 'render test frames and compute MSE and SSIM metrics against ground truth RGB images', 'render forward and backward optical flow comparisons between predicted and ground truth flow fields', 'render depth error comparison visualizations between predicted and ground truth inverse depth maps', 'render frames and save RGB, depth, and camera pose videos as MP4 files to disk', 'run the local TensoRF reconstruction pipeline with pose optimization and progressive refinement', 'render test frames from a trained checkpoint using the render_test function', 'render a smooth spline camera path from poses using the render_frames function', 'save camera poses and intrinsics to a transforms.json file using save_transforms', 'run the train.py CLI entry point to start reconstruction or rendering via config_parser']
```

Usage

```
{'run_config_parser_with_defaults': 'run the config_parser function to parse default arguments for local TensoRF training', 'run_config_parser_with_cmd': 'run the config_parser function with a custom command list to override default training arguments', 'build_training_config': 'build a configuration with custom learning rate and voxel settings for TensorVMSplit model training', 'build_rendering_config': 'build a configuration with render_only mode enabled to render from a saved checkpoint file', 'review_config_parser_arguments': 'review the config_parser function to understand all available training and rendering arguments'}
```

## File: facebookresearch_localrf/localTensoRF/renderer.py

Prompts

```
['create a LocalTensorfs model with fov, n_init_frames, n_overlap, WH, and learning rate parameters for self-calibrating local tensor factorization', 'append a new camera frame with pose parameters and optimizers to the LocalTensorfs model for incremental training', 'append a new radiance field with blending weights to the LocalTensorfs model for multi-view scene reconstruction', 'run optimizer_step on the LocalTensorfs model to optimize camera poses, exposure, and radiance field parameters with loss backward pass', 'render rays through the LocalTensorfs model to get RGB colors, depth maps, and ray directions for given ray and view IDs', 'run the config_parser function to parse default arguments for local TensoRF training', 'run the config_parser function with a custom command list to override default training arguments', 'build a configuration with custom learning rate and voxel settings for TensorVMSplit model training', 'build a configuration with render_only mode enabled to render from a saved checkpoint file', 'review the config_parser function to understand all available training and rendering arguments', 'render RGB and depth map frames from a Local TensoRF model using camera poses and ray IDs', 'render test frames and compute MSE and SSIM metrics against ground truth RGB images', 'render forward and backward optical flow comparisons between predicted and ground truth flow fields', 'render depth error comparison visualizations between predicted and ground truth inverse depth maps', 'render frames and save RGB, depth, and camera pose videos as MP4 files to disk', 'run the local TensoRF reconstruction pipeline with pose optimization and progressive refinement', 'render test frames from a trained checkpoint using the render_test function', 'render a smooth spline camera path from poses using the render_frames function', 'save camera poses and intrinsics to a transforms.json file using save_transforms', 'run the train.py CLI entry point to start reconstruction or rendering via config_parser']
```

Usage

```
{'render_rgb_depth_frames': 'render RGB and depth map frames from a Local TensoRF model using camera poses and ray IDs', 'render_test_with_metrics': 'render test frames and compute MSE and SSIM metrics against ground truth RGB images', 'render_optical_flow_comparison': 'render forward and backward optical flow comparisons between predicted and ground truth flow fields', 'render_depth_error_comparison': 'render depth error comparison visualizations between predicted and ground truth inverse depth maps', 'render_save_video_frames': 'render frames and save RGB, depth, and camera pose videos as MP4 files to disk'}
```

## File: facebookresearch_localrf/localTensoRF/train.py

Prompts

```
['create a LocalTensorfs model with fov, n_init_frames, n_overlap, WH, and learning rate parameters for self-calibrating local tensor factorization', 'append a new camera frame with pose parameters and optimizers to the LocalTensorfs model for incremental training', 'append a new radiance field with blending weights to the LocalTensorfs model for multi-view scene reconstruction', 'run optimizer_step on the LocalTensorfs model to optimize camera poses, exposure, and radiance field parameters with loss backward pass', 'render rays through the LocalTensorfs model to get RGB colors, depth maps, and ray directions for given ray and view IDs', 'run the config_parser function to parse default arguments for local TensoRF training', 'run the config_parser function with a custom command list to override default training arguments', 'build a configuration with custom learning rate and voxel settings for TensorVMSplit model training', 'build a configuration with render_only mode enabled to render from a saved checkpoint file', 'review the config_parser function to understand all available training and rendering arguments', 'render RGB and depth map frames from a Local TensoRF model using camera poses and ray IDs', 'render test frames and compute MSE and SSIM metrics against ground truth RGB images', 'render forward and backward optical flow comparisons between predicted and ground truth flow fields', 'render depth error comparison visualizations between predicted and ground truth inverse depth maps', 'render frames and save RGB, depth, and camera pose videos as MP4 files to disk', 'run the local TensoRF reconstruction pipeline with pose optimization and progressive refinement', 'render test frames from a trained checkpoint using the render_test function', 'render a smooth spline camera path from poses using the render_frames function', 'save camera poses and intrinsics to a transforms.json file using save_transforms', 'run the train.py CLI entry point to start reconstruction or rendering via config_parser']
```

Usage

```
{'run_reconstruction': 'run the local TensoRF reconstruction pipeline with pose optimization and progressive refinement', 'render_test_frames': 'render test frames from a trained checkpoint using the render_test function', 'render_smooth_path': 'render a smooth spline camera path from poses using the render_frames function', 'save_transforms_json': 'save camera poses and intrinsics to a transforms.json file using save_transforms', 'run_cli_entry': 'run the train.py CLI entry point to start reconstruction or rendering via config_parser'}
```

