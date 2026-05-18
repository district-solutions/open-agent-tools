# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/third_party/stable-diffusion/ldm/models/diffusion/classifier.py

Prompts

```
['create a NoisyLatentImageClassifier with diffusion path, num classes, and optional checkpoint path', 'test loading model weights from a checkpoint file with optional ignored keys', 'review the get_x_noisy method that adds noise to latent inputs at timestep t', 'build a classifier model from diffusion UNet config with pooled attention or segmentation output', 'summarize the compute_top_k method that calculates top-k accuracy for classification logits', 'create a DDIM sampler to generate images from noise using denoising diffusion implicit models', 'build a DDIM sampling schedule with configurable timesteps and eta noise parameters', 'run the DDIM sampling loop to iteratively denoise latent representations step by step', 'apply classifier-free guidance scaling to steer unconditional and conditional noise predictions', 'encode an input image with stochastic noise at a specified timestep for inpainting', 'build a DDPM diffusion model with configurable beta schedule, timesteps, and loss type for image generation', 'create a LatentDiffusion model with first stage autoencoder and conditioning stage for latent space diffusion', 'run the DDPM p_sample_loop method to iteratively denoise random noise into generated images', 'test the LatentDiffusion apply_model method to verify noisy latent processing with conditioning inputs', 'review the DiffusionWrapper forward method to understand concat, crossattn, hybrid, and adm conditioning modes', 'create a PLMSSampler instance with a diffusion model and linear schedule for image sampling', 'run PLMS sampling to generate images from noise using a conditioned diffusion model', 'run the PLMS sampling loop with conditioning and optional callbacks for progress tracking', 'run a single PLMS denoising step using Adams-Bashforth multistep estimation for noise prediction', 'run make_schedule to compute DDIM timesteps and register diffusion sampling parameters as buffers']
```

Usage

```
{'create_NoisyLatentImageClassifier': 'create a NoisyLatentImageClassifier with diffusion path, num classes, and optional checkpoint path', 'test_init_from_ckpt': 'test loading model weights from a checkpoint file with optional ignored keys', 'review_get_x_noisy': 'review the get_x_noisy method that adds noise to latent inputs at timestep t', 'build_load_classifier': 'build a classifier model from diffusion UNet config with pooled attention or segmentation output', 'summarize_compute_top_k': 'summarize the compute_top_k method that calculates top-k accuracy for classification logits'}
```

## File: facebookresearch_metaseq/third_party/stable-diffusion/ldm/models/diffusion/ddim.py

Prompts

```
['create a NoisyLatentImageClassifier with diffusion path, num classes, and optional checkpoint path', 'test loading model weights from a checkpoint file with optional ignored keys', 'review the get_x_noisy method that adds noise to latent inputs at timestep t', 'build a classifier model from diffusion UNet config with pooled attention or segmentation output', 'summarize the compute_top_k method that calculates top-k accuracy for classification logits', 'create a DDIM sampler to generate images from noise using denoising diffusion implicit models', 'build a DDIM sampling schedule with configurable timesteps and eta noise parameters', 'run the DDIM sampling loop to iteratively denoise latent representations step by step', 'apply classifier-free guidance scaling to steer unconditional and conditional noise predictions', 'encode an input image with stochastic noise at a specified timestep for inpainting', 'build a DDPM diffusion model with configurable beta schedule, timesteps, and loss type for image generation', 'create a LatentDiffusion model with first stage autoencoder and conditioning stage for latent space diffusion', 'run the DDPM p_sample_loop method to iteratively denoise random noise into generated images', 'test the LatentDiffusion apply_model method to verify noisy latent processing with conditioning inputs', 'review the DiffusionWrapper forward method to understand concat, crossattn, hybrid, and adm conditioning modes', 'create a PLMSSampler instance with a diffusion model and linear schedule for image sampling', 'run PLMS sampling to generate images from noise using a conditioned diffusion model', 'run the PLMS sampling loop with conditioning and optional callbacks for progress tracking', 'run a single PLMS denoising step using Adams-Bashforth multistep estimation for noise prediction', 'run make_schedule to compute DDIM timesteps and register diffusion sampling parameters as buffers']
```

Usage

```
{'sample_ddim_images': 'create a DDIM sampler to generate images from noise using denoising diffusion implicit models', 'build_ddim_schedule': 'build a DDIM sampling schedule with configurable timesteps and eta noise parameters', 'run_ddim_sampling_loop': 'run the DDIM sampling loop to iteratively denoise latent representations step by step', 'apply_classifier_free_guidance': 'apply classifier-free guidance scaling to steer unconditional and conditional noise predictions', 'encode_with_stochastic_noise': 'encode an input image with stochastic noise at a specified timestep for inpainting'}
```

## File: facebookresearch_metaseq/third_party/stable-diffusion/ldm/models/diffusion/ddpm.py

Prompts

```
['create a NoisyLatentImageClassifier with diffusion path, num classes, and optional checkpoint path', 'test loading model weights from a checkpoint file with optional ignored keys', 'review the get_x_noisy method that adds noise to latent inputs at timestep t', 'build a classifier model from diffusion UNet config with pooled attention or segmentation output', 'summarize the compute_top_k method that calculates top-k accuracy for classification logits', 'create a DDIM sampler to generate images from noise using denoising diffusion implicit models', 'build a DDIM sampling schedule with configurable timesteps and eta noise parameters', 'run the DDIM sampling loop to iteratively denoise latent representations step by step', 'apply classifier-free guidance scaling to steer unconditional and conditional noise predictions', 'encode an input image with stochastic noise at a specified timestep for inpainting', 'build a DDPM diffusion model with configurable beta schedule, timesteps, and loss type for image generation', 'create a LatentDiffusion model with first stage autoencoder and conditioning stage for latent space diffusion', 'run the DDPM p_sample_loop method to iteratively denoise random noise into generated images', 'test the LatentDiffusion apply_model method to verify noisy latent processing with conditioning inputs', 'review the DiffusionWrapper forward method to understand concat, crossattn, hybrid, and adm conditioning modes', 'create a PLMSSampler instance with a diffusion model and linear schedule for image sampling', 'run PLMS sampling to generate images from noise using a conditioned diffusion model', 'run the PLMS sampling loop with conditioning and optional callbacks for progress tracking', 'run a single PLMS denoising step using Adams-Bashforth multistep estimation for noise prediction', 'run make_schedule to compute DDIM timesteps and register diffusion sampling parameters as buffers']
```

Usage

```
{'build_DDPM_model': 'build a DDPM diffusion model with configurable beta schedule, timesteps, and loss type for image generation', 'create_LatentDiffusion_model': 'create a LatentDiffusion model with first stage autoencoder and conditioning stage for latent space diffusion', 'sample_DDPM_p_sample_loop': 'run the DDPM p_sample_loop method to iteratively denoise random noise into generated images', 'test_LatentDiffusion_apply_model': 'test the LatentDiffusion apply_model method to verify noisy latent processing with conditioning inputs', 'review_DiffusionWrapper_forward': 'review the DiffusionWrapper forward method to understand concat, crossattn, hybrid, and adm conditioning modes'}
```

## File: facebookresearch_metaseq/third_party/stable-diffusion/ldm/models/diffusion/plms.py

Prompts

```
['create a NoisyLatentImageClassifier with diffusion path, num classes, and optional checkpoint path', 'test loading model weights from a checkpoint file with optional ignored keys', 'review the get_x_noisy method that adds noise to latent inputs at timestep t', 'build a classifier model from diffusion UNet config with pooled attention or segmentation output', 'summarize the compute_top_k method that calculates top-k accuracy for classification logits', 'create a DDIM sampler to generate images from noise using denoising diffusion implicit models', 'build a DDIM sampling schedule with configurable timesteps and eta noise parameters', 'run the DDIM sampling loop to iteratively denoise latent representations step by step', 'apply classifier-free guidance scaling to steer unconditional and conditional noise predictions', 'encode an input image with stochastic noise at a specified timestep for inpainting', 'build a DDPM diffusion model with configurable beta schedule, timesteps, and loss type for image generation', 'create a LatentDiffusion model with first stage autoencoder and conditioning stage for latent space diffusion', 'run the DDPM p_sample_loop method to iteratively denoise random noise into generated images', 'test the LatentDiffusion apply_model method to verify noisy latent processing with conditioning inputs', 'review the DiffusionWrapper forward method to understand concat, crossattn, hybrid, and adm conditioning modes', 'create a PLMSSampler instance with a diffusion model and linear schedule for image sampling', 'run PLMS sampling to generate images from noise using a conditioned diffusion model', 'run the PLMS sampling loop with conditioning and optional callbacks for progress tracking', 'run a single PLMS denoising step using Adams-Bashforth multistep estimation for noise prediction', 'run make_schedule to compute DDIM timesteps and register diffusion sampling parameters as buffers']
```

Usage

```
{'create_PLMSSampler': 'create a PLMSSampler instance with a diffusion model and linear schedule for image sampling', 'run_PLMSSampler_sample': 'run PLMS sampling to generate images from noise using a conditioned diffusion model', 'run_PLMSSampler_plms_sampling': 'run the PLMS sampling loop with conditioning and optional callbacks for progress tracking', 'run_PLMSSampler_p_sample_plms': 'run a single PLMS denoising step using Adams-Bashforth multistep estimation for noise prediction', 'run_PLMSSampler_make_schedule': 'run make_schedule to compute DDIM timesteps and register diffusion sampling parameters as buffers'}
```

