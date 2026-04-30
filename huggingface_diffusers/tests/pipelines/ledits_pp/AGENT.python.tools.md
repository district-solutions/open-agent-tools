# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/ledits_pp/test_ledits_pp_stable_diffusion.py

Prompts

```
['test the LEditsPPPipelineStableDiffusion invert method to verify latent shape and expected slice values', 'test the LEditsPPPipelineStableDiffusion invert method with batched images to verify latent outputs', 'test the LEditsPPPipelineStableDiffusion pipeline with various edit warmup step configurations', 'test the LEditsPPPipelineStableDiffusion editing pipeline with a pretrained Stable Diffusion model', 'create dummy UNet, VAE, scheduler, and text encoder components for LEditsPP pipeline testing', 'test the LEditsPPPipelineStableDiffusionXL edit pipeline using a pretrained SDXL model and verify output pixel values']
```

Usage

```
{'test_ledits_pp_inversion': 'test the LEditsPPPipelineStableDiffusion invert method to verify latent shape and expected slice values', 'test_ledits_pp_inversion_batch': 'test the LEditsPPPipelineStableDiffusion invert method with batched images to verify latent outputs', 'test_ledits_pp_warmup_steps': 'test the LEditsPPPipelineStableDiffusion pipeline with various edit warmup step configurations', 'test_ledits_pp_editing': 'test the LEditsPPPipelineStableDiffusion editing pipeline with a pretrained Stable Diffusion model', 'get_dummy_components': 'create dummy UNet, VAE, scheduler, and text encoder components for LEditsPP pipeline testing'}
```

## File: huggingface_diffusers/tests/pipelines/ledits_pp/test_ledits_pp_stable_diffusion_xl.py

Prompts

```
['test the LEditsPPPipelineStableDiffusion invert method to verify latent shape and expected slice values', 'test the LEditsPPPipelineStableDiffusion invert method with batched images to verify latent outputs', 'test the LEditsPPPipelineStableDiffusion pipeline with various edit warmup step configurations', 'test the LEditsPPPipelineStableDiffusion editing pipeline with a pretrained Stable Diffusion model', 'create dummy UNet, VAE, scheduler, and text encoder components for LEditsPP pipeline testing', 'test the LEditsPPPipelineStableDiffusionXL edit pipeline using a pretrained SDXL model and verify output pixel values']
```

Usage

```
{'test_ledits_pp_inversion': 'test the LEditsPPPipelineStableDiffusionXL inversion method with a single image and verify latent shape and values', 'test_ledits_pp_inversion_batch': 'test the LEditsPPPipelineStableDiffusionXL inversion method with a batch of images and verify latent outputs', 'test_ledits_pp_warmup_steps': 'test the LEditsPPPipelineStableDiffusionXL pipeline with various edit warmup step configurations', 'test_ledits_pp_edit': 'test the LEditsPPPipelineStableDiffusionXL edit pipeline using a pretrained SDXL model and verify output pixel values', 'get_dummy_components': 'create dummy UNet, VAE, CLIP text and vision encoders for testing LEditsPPPipelineStableDiffusionXL'}
```

