# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/t2i_adapter/pipeline_stable_diffusion_adapter.py

Prompts

```
['build a StableDiffusionAdapterPipeline with a T2IAdapter for text-to-image generation with adapter conditioning', 'run the StableDiffusionAdapterPipeline to generate images from a text prompt and adapter conditioning image', 'create prompt embeddings using encode_prompt with optional negative prompts and classifier-free guidance', 'refactor the _preprocess_adapter_image function to resize and normalize PIL or tensor images for the adapter', 'review the prepare_latents method to initialize random latent noise scaled by the scheduler', 'build a StableDiffusionXLAdapterPipeline with T2IAdapter for text-to-image generation with adapter conditioning', 'create a pipeline that generates images from text prompts using a T2IAdapter for sketch conditioning', 'encode text prompts into embeddings using dual text encoders with optional LoRA scaling and clip skip', 'prepare and preprocess adapter input images by resizing and converting PIL or tensor inputs to the correct format', 'run the StableDiffusionXLAdapterPipeline with a prompt, sketch image, and guidance scale to generate conditioned images']
```

Usage

```
{'build_StableDiffusionAdapterPipeline': 'build a StableDiffusionAdapterPipeline with a T2IAdapter for text-to-image generation with adapter conditioning', 'run_StableDiffusionAdapterPipeline_call': 'run the StableDiffusionAdapterPipeline to generate images from a text prompt and adapter conditioning image', 'create_encode_prompt': 'create prompt embeddings using encode_prompt with optional negative prompts and classifier-free guidance', 'refactor_preprocess_adapter_image': 'refactor the _preprocess_adapter_image function to resize and normalize PIL or tensor images for the adapter', 'review_prepare_latents': 'review the prepare_latents method to initialize random latent noise scaled by the scheduler'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/t2i_adapter/pipeline_stable_diffusion_xl_adapter.py

Prompts

```
['build a StableDiffusionAdapterPipeline with a T2IAdapter for text-to-image generation with adapter conditioning', 'run the StableDiffusionAdapterPipeline to generate images from a text prompt and adapter conditioning image', 'create prompt embeddings using encode_prompt with optional negative prompts and classifier-free guidance', 'refactor the _preprocess_adapter_image function to resize and normalize PIL or tensor images for the adapter', 'review the prepare_latents method to initialize random latent noise scaled by the scheduler', 'build a StableDiffusionXLAdapterPipeline with T2IAdapter for text-to-image generation with adapter conditioning', 'create a pipeline that generates images from text prompts using a T2IAdapter for sketch conditioning', 'encode text prompts into embeddings using dual text encoders with optional LoRA scaling and clip skip', 'prepare and preprocess adapter input images by resizing and converting PIL or tensor inputs to the correct format', 'run the StableDiffusionXLAdapterPipeline with a prompt, sketch image, and guidance scale to generate conditioned images']
```

Usage

```
{'build_stable_diffusion_xl_adapter_pipeline': 'build a StableDiffusionXLAdapterPipeline with T2IAdapter for text-to-image generation with adapter conditioning', 'create_t2i_adapter_image_generation': 'create a pipeline that generates images from text prompts using a T2IAdapter for sketch conditioning', 'encode_prompt_with_sdxl_adapters': 'encode text prompts into embeddings using dual text encoders with optional LoRA scaling and clip skip', 'prepare_adapter_image_conditioning': 'prepare and preprocess adapter input images by resizing and converting PIL or tensor inputs to the correct format', 'run_sdxl_adapter_inference': 'run the StableDiffusionXLAdapterPipeline with a prompt, sketch image, and guidance scale to generate conditioned images'}
```

