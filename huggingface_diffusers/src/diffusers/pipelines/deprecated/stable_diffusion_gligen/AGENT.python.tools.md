# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/stable_diffusion_gligen/pipeline_stable_diffusion_gligen.py

Prompts

```
['generate an image with grounded text-to-image using StableDiffusionGLIGENPipeline with bounding boxes and phrases', 'inpaint objects into an existing image using StableDiffusionGLIGENPipeline with gligen_inpaint_image and bounding boxes', 'encode a text prompt into CLIP text embeddings using the encode_prompt method of StableDiffusionGLIGENPipeline', 'enable or disable the GatedSelfAttentionDense fuser modules in the UNet using enable_fuser method', 'prepare initial noisy latent variables for diffusion using the prepare_latents method of StableDiffusionGLIGENPipeline', 'generate an image using StableDiffusionGLIGENTextImagePipeline with grounded text phrases and bounding boxes', 'encode a text prompt into CLIP text encoder hidden states using encode_prompt', 'prepare cross-attention kwargs with grounded boxes phrases and image embeddings for GLIGEN', 'extract CLIP image or phrase embeddings using get_clip_feature with normalization', 'create an inpainting mask tensor from a list of bounding box coordinates']
```

Usage

```
{'generate_gligen_image': 'generate an image with grounded text-to-image using StableDiffusionGLIGENPipeline with bounding boxes and phrases', 'inpaint_gligen_image': 'inpaint objects into an existing image using StableDiffusionGLIGENPipeline with gligen_inpaint_image and bounding boxes', 'encode_prompt_gligen': 'encode a text prompt into CLIP text embeddings using the encode_prompt method of StableDiffusionGLIGENPipeline', 'enable_fuser_gligen': 'enable or disable the GatedSelfAttentionDense fuser modules in the UNet using enable_fuser method', 'prepare_latents_gligen': 'prepare initial noisy latent variables for diffusion using the prepare_latents method of StableDiffusionGLIGENPipeline'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/stable_diffusion_gligen/pipeline_stable_diffusion_gligen_text_image.py

Prompts

```
['generate an image with grounded text-to-image using StableDiffusionGLIGENPipeline with bounding boxes and phrases', 'inpaint objects into an existing image using StableDiffusionGLIGENPipeline with gligen_inpaint_image and bounding boxes', 'encode a text prompt into CLIP text embeddings using the encode_prompt method of StableDiffusionGLIGENPipeline', 'enable or disable the GatedSelfAttentionDense fuser modules in the UNet using enable_fuser method', 'prepare initial noisy latent variables for diffusion using the prepare_latents method of StableDiffusionGLIGENPipeline', 'generate an image using StableDiffusionGLIGENTextImagePipeline with grounded text phrases and bounding boxes', 'encode a text prompt into CLIP text encoder hidden states using encode_prompt', 'prepare cross-attention kwargs with grounded boxes phrases and image embeddings for GLIGEN', 'extract CLIP image or phrase embeddings using get_clip_feature with normalization', 'create an inpainting mask tensor from a list of bounding box coordinates']
```

Usage

```
{'generate_image_with_gligen': 'generate an image using StableDiffusionGLIGENTextImagePipeline with grounded text phrases and bounding boxes', 'encode_prompt_embeddings': 'encode a text prompt into CLIP text encoder hidden states using encode_prompt', 'prepare_grounded_cross_attention_kwargs': 'prepare cross-attention kwargs with grounded boxes phrases and image embeddings for GLIGEN', 'extract_clip_feature': 'extract CLIP image or phrase embeddings using get_clip_feature with normalization', 'create_inpaint_mask_from_boxes': 'create an inpainting mask tensor from a list of bounding box coordinates'}
```

