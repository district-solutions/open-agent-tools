# Agent Python Tools

- repo: facebookresearch/stablesignature
- repo_uri: https://github.com/facebookresearch/stable_signature

## File: facebookresearch_stablesignature/src/ldm/models/diffusion/ddim.py

Prompts

```
['build a python module to generate images using DDIMSampler sample method with conditioning and guidance scale', 'build a python module to create a DDIM sampling schedule with custom timesteps and eta parameter', 'build a python module to encode an image into latent space using DDIMSampler encode method', 'build a python module to add noise to an image using DDIMSampler stochastic_encode at timestep t', 'build a python module to decode a latent representation back to an image using DDIMSampler decode method', 'build a LatentDiffusion model from config with first stage autoencoder and conditioning stage', 'sample images from a DDPM model using p_sample_loop with specified batch size and timesteps', 'review the DiffusionWrapper forward method to understand concat, crossattn, hybrid, and adm conditioning modes', 'test the LatentInpaintDiffusion get_input method to encode masks and masked images as concat conditions', 'refactor the LatentDiffusion p_losses method to support a new parameterization mode beyond eps, x0, and v', 'create a PLMSSampler instance with a diffusion model and linear noise schedule', 'run PLMS sampling to generate samples from noise using a conditioned diffusion model', 'run the PLMS sampling loop with conditioning and optional callbacks for progress tracking', 'review the p_sample_plms method that computes one PLMS denoising step with multistep integration', 'review the make_schedule method that builds DDIM timesteps and registers diffusion buffers', 'append dimensions to a PyTorch tensor until it reaches the target number of dimensions', 'apply norm thresholding to a tensor by scaling values based on their per-sample norm clamped to a minimum', 'apply spatial norm thresholding to a batch of b c h w tensors by scaling per-channel norms', 'review the append_dims function to understand how it adds trailing dimensions to a PyTorch tensor', 'summarize the norm_thresholding and spatial_norm_thresholding functions used for clamping tensor norms during diffusion sampling']
```

Usage

```
{'sample_ddim_images': 'build a python module to generate images using DDIMSampler sample method with conditioning and guidance scale', 'make_ddim_schedule': 'build a python module to create a DDIM sampling schedule with custom timesteps and eta parameter', 'encode_image_to_latent': 'build a python module to encode an image into latent space using DDIMSampler encode method', 'stochastic_encode_noise': 'build a python module to add noise to an image using DDIMSampler stochastic_encode at timestep t', 'decode_latent_to_image': 'build a python module to decode a latent representation back to an image using DDIMSampler decode method'}
```

## File: facebookresearch_stablesignature/src/ldm/models/diffusion/ddpm.py

Prompts

```
['build a python module to generate images using DDIMSampler sample method with conditioning and guidance scale', 'build a python module to create a DDIM sampling schedule with custom timesteps and eta parameter', 'build a python module to encode an image into latent space using DDIMSampler encode method', 'build a python module to add noise to an image using DDIMSampler stochastic_encode at timestep t', 'build a python module to decode a latent representation back to an image using DDIMSampler decode method', 'build a LatentDiffusion model from config with first stage autoencoder and conditioning stage', 'sample images from a DDPM model using p_sample_loop with specified batch size and timesteps', 'review the DiffusionWrapper forward method to understand concat, crossattn, hybrid, and adm conditioning modes', 'test the LatentInpaintDiffusion get_input method to encode masks and masked images as concat conditions', 'refactor the LatentDiffusion p_losses method to support a new parameterization mode beyond eps, x0, and v', 'create a PLMSSampler instance with a diffusion model and linear noise schedule', 'run PLMS sampling to generate samples from noise using a conditioned diffusion model', 'run the PLMS sampling loop with conditioning and optional callbacks for progress tracking', 'review the p_sample_plms method that computes one PLMS denoising step with multistep integration', 'review the make_schedule method that builds DDIM timesteps and registers diffusion buffers', 'append dimensions to a PyTorch tensor until it reaches the target number of dimensions', 'apply norm thresholding to a tensor by scaling values based on their per-sample norm clamped to a minimum', 'apply spatial norm thresholding to a batch of b c h w tensors by scaling per-channel norms', 'review the append_dims function to understand how it adds trailing dimensions to a PyTorch tensor', 'summarize the norm_thresholding and spatial_norm_thresholding functions used for clamping tensor norms during diffusion sampling']
```

Usage

```
{'build_LatentDiffusion_model': 'build a LatentDiffusion model from config with first stage autoencoder and conditioning stage', 'sample_DDPM': 'sample images from a DDPM model using p_sample_loop with specified batch size and timesteps', 'review_DiffusionWrapper_conditioning': 'review the DiffusionWrapper forward method to understand concat, crossattn, hybrid, and adm conditioning modes', 'test_LatentInpaintDiffusion_get_input': 'test the LatentInpaintDiffusion get_input method to encode masks and masked images as concat conditions', 'refactor_LatentDiffusion_p_losses': 'refactor the LatentDiffusion p_losses method to support a new parameterization mode beyond eps, x0, and v'}
```

## File: facebookresearch_stablesignature/src/ldm/models/diffusion/plms.py

Prompts

```
['build a python module to generate images using DDIMSampler sample method with conditioning and guidance scale', 'build a python module to create a DDIM sampling schedule with custom timesteps and eta parameter', 'build a python module to encode an image into latent space using DDIMSampler encode method', 'build a python module to add noise to an image using DDIMSampler stochastic_encode at timestep t', 'build a python module to decode a latent representation back to an image using DDIMSampler decode method', 'build a LatentDiffusion model from config with first stage autoencoder and conditioning stage', 'sample images from a DDPM model using p_sample_loop with specified batch size and timesteps', 'review the DiffusionWrapper forward method to understand concat, crossattn, hybrid, and adm conditioning modes', 'test the LatentInpaintDiffusion get_input method to encode masks and masked images as concat conditions', 'refactor the LatentDiffusion p_losses method to support a new parameterization mode beyond eps, x0, and v', 'create a PLMSSampler instance with a diffusion model and linear noise schedule', 'run PLMS sampling to generate samples from noise using a conditioned diffusion model', 'run the PLMS sampling loop with conditioning and optional callbacks for progress tracking', 'review the p_sample_plms method that computes one PLMS denoising step with multistep integration', 'review the make_schedule method that builds DDIM timesteps and registers diffusion buffers', 'append dimensions to a PyTorch tensor until it reaches the target number of dimensions', 'apply norm thresholding to a tensor by scaling values based on their per-sample norm clamped to a minimum', 'apply spatial norm thresholding to a batch of b c h w tensors by scaling per-channel norms', 'review the append_dims function to understand how it adds trailing dimensions to a PyTorch tensor', 'summarize the norm_thresholding and spatial_norm_thresholding functions used for clamping tensor norms during diffusion sampling']
```

Usage

```
{'create_PLMSSampler': 'create a PLMSSampler instance with a diffusion model and linear noise schedule', 'run_PLMSSampler_sample': 'run PLMS sampling to generate samples from noise using a conditioned diffusion model', 'run_PLMSSampler_plms_sampling': 'run the PLMS sampling loop with conditioning and optional callbacks for progress tracking', 'review_PLMSSampler_p_sample_plms': 'review the p_sample_plms method that computes one PLMS denoising step with multistep integration', 'review_PLMSSampler_make_schedule': 'review the make_schedule method that builds DDIM timesteps and registers diffusion buffers'}
```

## File: facebookresearch_stablesignature/src/ldm/models/diffusion/sampling_util.py

Prompts

```
['build a python module to generate images using DDIMSampler sample method with conditioning and guidance scale', 'build a python module to create a DDIM sampling schedule with custom timesteps and eta parameter', 'build a python module to encode an image into latent space using DDIMSampler encode method', 'build a python module to add noise to an image using DDIMSampler stochastic_encode at timestep t', 'build a python module to decode a latent representation back to an image using DDIMSampler decode method', 'build a LatentDiffusion model from config with first stage autoencoder and conditioning stage', 'sample images from a DDPM model using p_sample_loop with specified batch size and timesteps', 'review the DiffusionWrapper forward method to understand concat, crossattn, hybrid, and adm conditioning modes', 'test the LatentInpaintDiffusion get_input method to encode masks and masked images as concat conditions', 'refactor the LatentDiffusion p_losses method to support a new parameterization mode beyond eps, x0, and v', 'create a PLMSSampler instance with a diffusion model and linear noise schedule', 'run PLMS sampling to generate samples from noise using a conditioned diffusion model', 'run the PLMS sampling loop with conditioning and optional callbacks for progress tracking', 'review the p_sample_plms method that computes one PLMS denoising step with multistep integration', 'review the make_schedule method that builds DDIM timesteps and registers diffusion buffers', 'append dimensions to a PyTorch tensor until it reaches the target number of dimensions', 'apply norm thresholding to a tensor by scaling values based on their per-sample norm clamped to a minimum', 'apply spatial norm thresholding to a batch of b c h w tensors by scaling per-channel norms', 'review the append_dims function to understand how it adds trailing dimensions to a PyTorch tensor', 'summarize the norm_thresholding and spatial_norm_thresholding functions used for clamping tensor norms during diffusion sampling']
```

Usage

```
{'append_dims_tensor': 'append dimensions to a PyTorch tensor until it reaches the target number of dimensions', 'norm_thresholding_clamp': 'apply norm thresholding to a tensor by scaling values based on their per-sample norm clamped to a minimum', 'spatial_norm_thresholding_clamp': 'apply spatial norm thresholding to a batch of b c h w tensors by scaling per-channel norms', 'review_append_dims': 'review the append_dims function to understand how it adds trailing dimensions to a PyTorch tensor', 'summarize_norm_thresholding': 'summarize the norm_thresholding and spatial_norm_thresholding functions used for clamping tensor norms during diffusion sampling'}
```

