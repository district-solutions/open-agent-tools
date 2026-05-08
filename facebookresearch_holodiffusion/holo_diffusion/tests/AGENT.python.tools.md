# Agent Python Tools

- repo: facebookresearch/holodiffusion
- repo_uri: https://github.com/facebookresearch/holo_diffusion

## File: facebookresearch_holodiffusion/holo_diffusion/tests/test_diffusion_utils.py

Prompts

```
['test the SimpleUnet3D forward pass with a 32x32x32 voxel grid input and random timesteps', 'test the SimpleUnet3D backward pass to verify gradients are computed without NaNs', 'create a SimpleUnet3D model with dummy 3D input tensor and timestep tensor for testing', 'run a SimpleUnet3D model on a 3D voxel grid input with specified diffusion timesteps', 'review the SimpleUnet3D backward pass to confirm no NaN gradients in model weights', 'test the RenderMLP forward pass to verify no NaNs in densities, radiance, and view-dependent outputs', 'test the RenderMLP backward pass to verify no NaNs in the computed gradients of MLP weights', 'test the HoloVoxelGridImplicitFunction forward pass to verify no NaNs in densities and features outputs', 'test the HoloVoxelGridImplicitFunction backward pass to verify no NaNs in the computed gradients of weights', 'create a RenderMLP instance with dummy feature tensors and normalized view direction tensors for testing']
```

Usage

```
{'test_SimpleUnet3D_forward_pass': 'test the SimpleUnet3D forward pass with a 32x32x32 voxel grid input and random timesteps', 'test_SimpleUnet3D_backward_pass': 'test the SimpleUnet3D backward pass to verify gradients are computed without NaNs', 'setup_SimpleUnet3D_for_testing': 'create a SimpleUnet3D model with dummy 3D input tensor and timestep tensor for testing', 'run_SimpleUnet3D_inference': 'run a SimpleUnet3D model on a 3D voxel grid input with specified diffusion timesteps', 'review_SimpleUnet3D_gradient_check': 'review the SimpleUnet3D backward pass to confirm no NaN gradients in model weights'}
```

## File: facebookresearch_holodiffusion/holo_diffusion/tests/test_voxel_grid_implicit_function.py

Prompts

```
['test the SimpleUnet3D forward pass with a 32x32x32 voxel grid input and random timesteps', 'test the SimpleUnet3D backward pass to verify gradients are computed without NaNs', 'create a SimpleUnet3D model with dummy 3D input tensor and timestep tensor for testing', 'run a SimpleUnet3D model on a 3D voxel grid input with specified diffusion timesteps', 'review the SimpleUnet3D backward pass to confirm no NaN gradients in model weights', 'test the RenderMLP forward pass to verify no NaNs in densities, radiance, and view-dependent outputs', 'test the RenderMLP backward pass to verify no NaNs in the computed gradients of MLP weights', 'test the HoloVoxelGridImplicitFunction forward pass to verify no NaNs in densities and features outputs', 'test the HoloVoxelGridImplicitFunction backward pass to verify no NaNs in the computed gradients of weights', 'create a RenderMLP instance with dummy feature tensors and normalized view direction tensors for testing']
```

Usage

```
{'test_RenderMLP_forward': 'test the RenderMLP forward pass to verify no NaNs in densities, radiance, and view-dependent outputs', 'test_RenderMLP_backward': 'test the RenderMLP backward pass to verify no NaNs in the computed gradients of MLP weights', 'test_VoxelGridImplicitFunction_forward': 'test the HoloVoxelGridImplicitFunction forward pass to verify no NaNs in densities and features outputs', 'test_VoxelGridImplicitFunction_backward': 'test the HoloVoxelGridImplicitFunction backward pass to verify no NaNs in the computed gradients of weights', 'setup_render_mlp': 'create a RenderMLP instance with dummy feature tensors and normalized view direction tensors for testing'}
```

