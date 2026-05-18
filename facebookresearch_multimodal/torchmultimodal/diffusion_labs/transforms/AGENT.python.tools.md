# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/transforms/diffusion_transform.py

Prompts

```
['create a RandomDiffusionSteps transform with a DiffusionSchedule to sample noised data for diffusion training', 'use the forward method of RandomDiffusionSteps to transform input data dict with sampled timesteps and noise', 'configure RandomDiffusionSteps with batched false to process single unbatched tensor inputs', 'customize RandomDiffusionSteps field names for data time noise and noised data keys', 'integrate a DiffusionSchedule into RandomDiffusionSteps to define noise diffusion through time steps', 'create a random rectangular inpainting mask for a PyTorch image tensor with configurable margins', 'create a random outpainting mask on a random side of a PyTorch image tensor', 'create a brush stroke style inpainting mask for a PyTorch image tensor', 'create a mask covering the entire image for a PyTorch image tensor', 'build a PyTorch nn.Module that randomly generates inpainting, outpainting, brush stroke, or full masks for batched image data', 'create a SuperResolutionTransform to downsample then upsample image tensors for training data augmentation', 'configure the transform with bicubic or bilinear interpolation mode for resizing image tensors', 'apply min and max value clamping to downsampled and upsampled tensor data', 'add a custom augmentation function to apply extra transforms on the downsampled tensor', 'create a ComputeV transform with a DiscreteGaussianSchedule to compute v prediction targets from x0 and noise', 'run the ComputeV forward pass on a dict containing x, t, and noise tensors to compute v', 'build a diffusion model training pipeline using ComputeV to transform data into v prediction targets', 'test ComputeV with custom data_field, time_field, and noise_field keys for flexible tensor naming', 'review how ComputeV uses sqrt_alphas_cumprod and sqrt_compliment_alphas_cumprod from the schedule to compute v']
```

Usage

```
{'create_diffusion_transform': 'create a RandomDiffusionSteps transform with a DiffusionSchedule to sample noised data for diffusion training', 'use_forward_method': 'use the forward method of RandomDiffusionSteps to transform input data dict with sampled timesteps and noise', 'configure_batched_transform': 'configure RandomDiffusionSteps with batched false to process single unbatched tensor inputs', 'customize_field_names': 'customize RandomDiffusionSteps field names for data time noise and noised data keys', 'integrate_diffusion_schedule': 'integrate a DiffusionSchedule into RandomDiffusionSteps to define noise diffusion through time steps'}
```

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/transforms/inpainting_transform.py

Prompts

```
['create a RandomDiffusionSteps transform with a DiffusionSchedule to sample noised data for diffusion training', 'use the forward method of RandomDiffusionSteps to transform input data dict with sampled timesteps and noise', 'configure RandomDiffusionSteps with batched false to process single unbatched tensor inputs', 'customize RandomDiffusionSteps field names for data time noise and noised data keys', 'integrate a DiffusionSchedule into RandomDiffusionSteps to define noise diffusion through time steps', 'create a random rectangular inpainting mask for a PyTorch image tensor with configurable margins', 'create a random outpainting mask on a random side of a PyTorch image tensor', 'create a brush stroke style inpainting mask for a PyTorch image tensor', 'create a mask covering the entire image for a PyTorch image tensor', 'build a PyTorch nn.Module that randomly generates inpainting, outpainting, brush stroke, or full masks for batched image data', 'create a SuperResolutionTransform to downsample then upsample image tensors for training data augmentation', 'configure the transform with bicubic or bilinear interpolation mode for resizing image tensors', 'apply min and max value clamping to downsampled and upsampled tensor data', 'add a custom augmentation function to apply extra transforms on the downsampled tensor', 'create a ComputeV transform with a DiscreteGaussianSchedule to compute v prediction targets from x0 and noise', 'run the ComputeV forward pass on a dict containing x, t, and noise tensors to compute v', 'build a diffusion model training pipeline using ComputeV to transform data into v prediction targets', 'test ComputeV with custom data_field, time_field, and noise_field keys for flexible tensor naming', 'review how ComputeV uses sqrt_alphas_cumprod and sqrt_compliment_alphas_cumprod from the schedule to compute v']
```

Usage

```
{'create_random_inpaint_mask': 'create a random rectangular inpainting mask for a PyTorch image tensor with configurable margins', 'create_random_outpaint_mask': 'create a random outpainting mask on a random side of a PyTorch image tensor', 'create_brush_stroke_mask': 'create a brush stroke style inpainting mask for a PyTorch image tensor', 'create_full_image_mask': 'create a mask covering the entire image for a PyTorch image tensor', 'build_random_inpainting_transform': 'build a PyTorch nn.Module that randomly generates inpainting, outpainting, brush stroke, or full masks for batched image data'}
```

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/transforms/super_resolution_transform.py

Prompts

```
['create a RandomDiffusionSteps transform with a DiffusionSchedule to sample noised data for diffusion training', 'use the forward method of RandomDiffusionSteps to transform input data dict with sampled timesteps and noise', 'configure RandomDiffusionSteps with batched false to process single unbatched tensor inputs', 'customize RandomDiffusionSteps field names for data time noise and noised data keys', 'integrate a DiffusionSchedule into RandomDiffusionSteps to define noise diffusion through time steps', 'create a random rectangular inpainting mask for a PyTorch image tensor with configurable margins', 'create a random outpainting mask on a random side of a PyTorch image tensor', 'create a brush stroke style inpainting mask for a PyTorch image tensor', 'create a mask covering the entire image for a PyTorch image tensor', 'build a PyTorch nn.Module that randomly generates inpainting, outpainting, brush stroke, or full masks for batched image data', 'create a SuperResolutionTransform to downsample then upsample image tensors for training data augmentation', 'configure the transform with bicubic or bilinear interpolation mode for resizing image tensors', 'apply min and max value clamping to downsampled and upsampled tensor data', 'add a custom augmentation function to apply extra transforms on the downsampled tensor', 'create a ComputeV transform with a DiscreteGaussianSchedule to compute v prediction targets from x0 and noise', 'run the ComputeV forward pass on a dict containing x, t, and noise tensors to compute v', 'build a diffusion model training pipeline using ComputeV to transform data into v prediction targets', 'test ComputeV with custom data_field, time_field, and noise_field keys for flexible tensor naming', 'review how ComputeV uses sqrt_alphas_cumprod and sqrt_compliment_alphas_cumprod from the schedule to compute v']
```

Usage

```
{'create_super_resolution_transform': 'create a SuperResolutionTransform to downsample then upsample image tensors for training data augmentation', 'use_forward_method': 'use the forward method to pass a dict with image data and get low-res augmented output', 'configure_interpolation_mode': 'configure the transform with bicubic or bilinear interpolation mode for resizing image tensors', 'apply_value_clamping': 'apply min and max value clamping to downsampled and upsampled tensor data', 'add_augmentation_function': 'add a custom augmentation function to apply extra transforms on the downsampled tensor'}
```

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/transforms/v_transform.py

Prompts

```
['create a RandomDiffusionSteps transform with a DiffusionSchedule to sample noised data for diffusion training', 'use the forward method of RandomDiffusionSteps to transform input data dict with sampled timesteps and noise', 'configure RandomDiffusionSteps with batched false to process single unbatched tensor inputs', 'customize RandomDiffusionSteps field names for data time noise and noised data keys', 'integrate a DiffusionSchedule into RandomDiffusionSteps to define noise diffusion through time steps', 'create a random rectangular inpainting mask for a PyTorch image tensor with configurable margins', 'create a random outpainting mask on a random side of a PyTorch image tensor', 'create a brush stroke style inpainting mask for a PyTorch image tensor', 'create a mask covering the entire image for a PyTorch image tensor', 'build a PyTorch nn.Module that randomly generates inpainting, outpainting, brush stroke, or full masks for batched image data', 'create a SuperResolutionTransform to downsample then upsample image tensors for training data augmentation', 'configure the transform with bicubic or bilinear interpolation mode for resizing image tensors', 'apply min and max value clamping to downsampled and upsampled tensor data', 'add a custom augmentation function to apply extra transforms on the downsampled tensor', 'create a ComputeV transform with a DiscreteGaussianSchedule to compute v prediction targets from x0 and noise', 'run the ComputeV forward pass on a dict containing x, t, and noise tensors to compute v', 'build a diffusion model training pipeline using ComputeV to transform data into v prediction targets', 'test ComputeV with custom data_field, time_field, and noise_field keys for flexible tensor naming', 'review how ComputeV uses sqrt_alphas_cumprod and sqrt_compliment_alphas_cumprod from the schedule to compute v']
```

Usage

```
{'create_ComputeV_instance': 'create a ComputeV transform with a DiscreteGaussianSchedule to compute v prediction targets from x0 and noise', 'run_ComputeV_forward': 'run the ComputeV forward pass on a dict containing x, t, and noise tensors to compute v', 'build_v_transform_pipeline': 'build a diffusion model training pipeline using ComputeV to transform data into v prediction targets', 'test_ComputeV_with_custom_fields': 'test ComputeV with custom data_field, time_field, and noise_field keys for flexible tensor naming', 'review_ComputeV_schedule_usage': 'review how ComputeV uses sqrt_alphas_cumprod and sqrt_compliment_alphas_cumprod from the schedule to compute v'}
```

