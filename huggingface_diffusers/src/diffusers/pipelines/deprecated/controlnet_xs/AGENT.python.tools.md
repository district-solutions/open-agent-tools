# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/controlnet_xs/pipeline_controlnet_xs.py

Prompts

```
['run the StableDiffusionControlNetXSPipeline to generate images from a text prompt and a canny edge control image', 'encode a text prompt into CLIP text embeddings using the encode_prompt method with optional clip skip', 'prepare and preprocess a control image tensor for the ControlNet XS adapter with classifier free guidance', 'load and apply LoRA weights to the StableDiffusionControlNetXSPipeline using the StableDiffusionLoraLoaderMixin', 'decode VAE latents into a postprocessed PIL image using the image processor', 'build a StableDiffusionXLControlNetXSPipeline with ControlNetXSAdapter for text-to-image generation with control guidance', 'create prompt embeddings using encode_prompt with dual text encoders and classifier-free guidance support', 'run prepare_image to preprocess control images with VaeImageProcessor for the ControlNet conditioning input', 'test the check_inputs method to validate prompt, image, and ControlNet conditioning parameters before generation', 'refactor the __call__ method to customize the denoising loop with ControlNet guidance start and end parameters']
```

Usage

```
{'run_controlnet_xs_pipeline': 'run the StableDiffusionControlNetXSPipeline to generate images from a text prompt and a canny edge control image', 'encode_prompt_with_clip': 'encode a text prompt into CLIP text embeddings using the encode_prompt method with optional clip skip', 'prepare_controlnet_image': 'prepare and preprocess a control image tensor for the ControlNet XS adapter with classifier free guidance', 'apply_lora_weights': 'load and apply LoRA weights to the StableDiffusionControlNetXSPipeline using the StableDiffusionLoraLoaderMixin', 'decode_latents_to_image': 'decode VAE latents into a postprocessed PIL image using the image processor'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/controlnet_xs/pipeline_controlnet_xs_sd_xl.py

Prompts

```
['run the StableDiffusionControlNetXSPipeline to generate images from a text prompt and a canny edge control image', 'encode a text prompt into CLIP text embeddings using the encode_prompt method with optional clip skip', 'prepare and preprocess a control image tensor for the ControlNet XS adapter with classifier free guidance', 'load and apply LoRA weights to the StableDiffusionControlNetXSPipeline using the StableDiffusionLoraLoaderMixin', 'decode VAE latents into a postprocessed PIL image using the image processor', 'build a StableDiffusionXLControlNetXSPipeline with ControlNetXSAdapter for text-to-image generation with control guidance', 'create prompt embeddings using encode_prompt with dual text encoders and classifier-free guidance support', 'run prepare_image to preprocess control images with VaeImageProcessor for the ControlNet conditioning input', 'test the check_inputs method to validate prompt, image, and ControlNet conditioning parameters before generation', 'refactor the __call__ method to customize the denoising loop with ControlNet guidance start and end parameters']
```

Usage

```
{'build_StableDiffusionXLControlNetXSPipeline': 'build a StableDiffusionXLControlNetXSPipeline with ControlNetXSAdapter for text-to-image generation with control guidance', 'create_encode_prompt': 'create prompt embeddings using encode_prompt with dual text encoders and classifier-free guidance support', 'run_prepare_image': 'run prepare_image to preprocess control images with VaeImageProcessor for the ControlNet conditioning input', 'test_check_inputs': 'test the check_inputs method to validate prompt, image, and ControlNet conditioning parameters before generation', 'refactor_call_method': 'refactor the __call__ method to customize the denoising loop with ControlNet guidance start and end parameters'}
```

