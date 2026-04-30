# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/latent_diffusion/test_latent_diffusion.py

Prompts

```
['test the LDMTextToImagePipeline with dummy components and verify output image shape and pixel values', 'test the LDMTextToImagePipeline loaded from pretrained CompVis model with DDIM scheduler on GPU', 'test the LDMTextToImagePipeline nightly regression against expected numpy array from HuggingFace datasets', 'create dummy UNet, VAE, DDIMScheduler, and CLIP text encoder components for LDM pipeline testing', 'create dummy input dictionary with prompt, generator, inference steps, and guidance scale for LDM pipeline', 'run the LDMSuperResolutionPipeline with a dummy UNet, VQModel, and DDIMScheduler to upscale an image', 'run the LDMSuperResolutionPipeline inference with FP16 precision on an accelerator device', 'run the LDMSuperResolutionPipeline integration test using a pretrained model from HuggingFace Hub', 'test that the LDMSuperResolutionPipeline output image has the expected shape and pixel values', 'review the LDMSuperResolutionPipeline fast and integration test classes for correctness']
```

Usage

```
{'test_ldm_text2img_fast': 'test the LDMTextToImagePipeline with dummy components and verify output image shape and pixel values', 'test_ldm_default_ddim_slow': 'test the LDMTextToImagePipeline loaded from pretrained CompVis model with DDIM scheduler on GPU', 'test_ldm_nightly_regression': 'test the LDMTextToImagePipeline nightly regression against expected numpy array from HuggingFace datasets', 'create_dummy_ldm_components': 'create dummy UNet, VAE, DDIMScheduler, and CLIP text encoder components for LDM pipeline testing', 'create_dummy_ldm_inputs': 'create dummy input dictionary with prompt, generator, inference steps, and guidance scale for LDM pipeline'}
```

## File: huggingface_diffusers/tests/pipelines/latent_diffusion/test_latent_diffusion_superresolution.py

Prompts

```
['test the LDMTextToImagePipeline with dummy components and verify output image shape and pixel values', 'test the LDMTextToImagePipeline loaded from pretrained CompVis model with DDIM scheduler on GPU', 'test the LDMTextToImagePipeline nightly regression against expected numpy array from HuggingFace datasets', 'create dummy UNet, VAE, DDIMScheduler, and CLIP text encoder components for LDM pipeline testing', 'create dummy input dictionary with prompt, generator, inference steps, and guidance scale for LDM pipeline', 'run the LDMSuperResolutionPipeline with a dummy UNet, VQModel, and DDIMScheduler to upscale an image', 'run the LDMSuperResolutionPipeline inference with FP16 precision on an accelerator device', 'run the LDMSuperResolutionPipeline integration test using a pretrained model from HuggingFace Hub', 'test that the LDMSuperResolutionPipeline output image has the expected shape and pixel values', 'review the LDMSuperResolutionPipeline fast and integration test classes for correctness']
```

Usage

```
{'run_ldm_super_resolution_inference': 'run the LDMSuperResolutionPipeline with a dummy UNet, VQModel, and DDIMScheduler to upscale an image', 'run_ldm_super_resolution_fp16': 'run the LDMSuperResolutionPipeline inference with FP16 precision on an accelerator device', 'run_ldm_super_resolution_integration': 'run the LDMSuperResolutionPipeline integration test using a pretrained model from HuggingFace Hub', 'test_ldm_super_resolution_output_shape': 'test that the LDMSuperResolutionPipeline output image has the expected shape and pixel values', 'review_ldm_super_resolution_tests': 'review the LDMSuperResolutionPipeline fast and integration test classes for correctness'}
```

