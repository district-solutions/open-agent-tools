# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/theseus/third_party/easyaug.py

Prompts

```
['create a RandomGeoAug instance and call forward on a BxCxHxW image tensor to apply random geometric augmentations', 'create a RandomPhotoAug instance and call forward on a BxCxHxW image tensor to apply random photometric distortions', 'call perspective_grid with transform coefficients and image size to generate a grid of sample locations for perspective warps', 'call truncated_normal_ with N samples, mean, and std to draw from a truncated normal distribution', 'call check_input on a tensor to verify it is 4D with 1 or 3 channels, float32 dtype, and values in [0,1]', 'create an LML module with N top-k selection and configurable convergence parameters', 'run the LML forward pass on a PyTorch tensor to compute soft top-k selection', 'test the LML backward pass gradient computation using finite difference verification', 'review the LML_Function autograd Function class for forward and backward implementations', 'refactor the bdot batch dot product helper to use a different tensor operation', 'build a custom grid_sample function that performs bilinear interpolation on image tensors using optical flow', 'create a grid sampling utility that avoids the grid_sampler_2d_backward derivative RuntimeError in PyTorch', 'test the grid_sample function with a batch of image tensors and optical flow coordinates', 'refactor the grid_sample function to use a different boundary handling strategy than clamp', 'summarize the grid_sample implementation that computes NW NE SW SE bilinear weights for image warping']
```

Usage

```
{'apply_random_geometric_augmentation': 'create a RandomGeoAug instance and call forward on a BxCxHxW image tensor to apply random geometric augmentations', 'apply_random_photometric_augmentation': 'create a RandomPhotoAug instance and call forward on a BxCxHxW image tensor to apply random photometric distortions', 'generate_perspective_grid': 'call perspective_grid with transform coefficients and image size to generate a grid of sample locations for perspective warps', 'draw_truncated_normal_samples': 'call truncated_normal_ with N samples, mean, and std to draw from a truncated normal distribution', 'validate_image_tensor_input': 'call check_input on a tensor to verify it is 4D with 1 or 3 channels, float32 dtype, and values in [0,1]'}
```

## File: facebookresearch_theseus/theseus/third_party/lml.py

Prompts

```
['create a RandomGeoAug instance and call forward on a BxCxHxW image tensor to apply random geometric augmentations', 'create a RandomPhotoAug instance and call forward on a BxCxHxW image tensor to apply random photometric distortions', 'call perspective_grid with transform coefficients and image size to generate a grid of sample locations for perspective warps', 'call truncated_normal_ with N samples, mean, and std to draw from a truncated normal distribution', 'call check_input on a tensor to verify it is 4D with 1 or 3 channels, float32 dtype, and values in [0,1]', 'create an LML module with N top-k selection and configurable convergence parameters', 'run the LML forward pass on a PyTorch tensor to compute soft top-k selection', 'test the LML backward pass gradient computation using finite difference verification', 'review the LML_Function autograd Function class for forward and backward implementations', 'refactor the bdot batch dot product helper to use a different tensor operation', 'build a custom grid_sample function that performs bilinear interpolation on image tensors using optical flow', 'create a grid sampling utility that avoids the grid_sampler_2d_backward derivative RuntimeError in PyTorch', 'test the grid_sample function with a batch of image tensors and optical flow coordinates', 'refactor the grid_sample function to use a different boundary handling strategy than clamp', 'summarize the grid_sample implementation that computes NW NE SW SE bilinear weights for image warping']
```

Usage

```
{'create_LML_module': 'create an LML module with N top-k selection and configurable convergence parameters', 'run_LML_forward': 'run the LML forward pass on a PyTorch tensor to compute soft top-k selection', 'test_LML_backward': 'test the LML backward pass gradient computation using finite difference verification', 'review_LML_Function': 'review the LML_Function autograd Function class for forward and backward implementations', 'refactor_bdot': 'refactor the bdot batch dot product helper to use a different tensor operation'}
```

## File: facebookresearch_theseus/theseus/third_party/utils.py

Prompts

```
['create a RandomGeoAug instance and call forward on a BxCxHxW image tensor to apply random geometric augmentations', 'create a RandomPhotoAug instance and call forward on a BxCxHxW image tensor to apply random photometric distortions', 'call perspective_grid with transform coefficients and image size to generate a grid of sample locations for perspective warps', 'call truncated_normal_ with N samples, mean, and std to draw from a truncated normal distribution', 'call check_input on a tensor to verify it is 4D with 1 or 3 channels, float32 dtype, and values in [0,1]', 'create an LML module with N top-k selection and configurable convergence parameters', 'run the LML forward pass on a PyTorch tensor to compute soft top-k selection', 'test the LML backward pass gradient computation using finite difference verification', 'review the LML_Function autograd Function class for forward and backward implementations', 'refactor the bdot batch dot product helper to use a different tensor operation', 'build a custom grid_sample function that performs bilinear interpolation on image tensors using optical flow', 'create a grid sampling utility that avoids the grid_sampler_2d_backward derivative RuntimeError in PyTorch', 'test the grid_sample function with a batch of image tensors and optical flow coordinates', 'refactor the grid_sample function to use a different boundary handling strategy than clamp', 'summarize the grid_sample implementation that computes NW NE SW SE bilinear weights for image warping']
```

Usage

```
{'build_grid_sample_custom': 'build a custom grid_sample function that performs bilinear interpolation on image tensors using optical flow', 'create_grid_sample_bilinear': 'create a grid sampling utility that avoids the grid_sampler_2d_backward derivative RuntimeError in PyTorch', 'test_grid_sample_function': 'test the grid_sample function with a batch of image tensors and optical flow coordinates', 'refactor_grid_sample_clamp': 'refactor the grid_sample function to use a different boundary handling strategy than clamp', 'summarize_grid_sample_impl': 'summarize the grid_sample implementation that computes NW NE SW SE bilinear weights for image warping'}
```

