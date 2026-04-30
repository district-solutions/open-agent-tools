# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/latent_consistency_models/pipeline_latent_consistency_img2img.py

Prompts

```
['run image-to-image generation using a latent consistency model pipeline with a prompt and input image', 'encode a text prompt into CLIP text encoder hidden states for image generation', 'prepare initial latents by encoding an input image through the VAE and adding noise', 'encode an image into hidden states or embeddings for use with IP Adapter image conditioning', 'generate sinusoidal guidance scale embedding vectors to enrich timestep embeddings for the UNet', 'run the LatentConsistencyModelPipeline to generate images from a text prompt using LCM distillation', 'build a LatentConsistencyModelPipeline from pretrained weights using DiffusionPipeline.from_pretrained and generate images', 'create a custom timestep schedule by calling retrieve_timesteps with a scheduler and num_inference_steps', 'test the encode_prompt method to convert text prompts into CLIP text encoder hidden states', 'review the get_guidance_scale_embedding method that generates sinusoidal embeddings for the guidance scale']
```

Usage

```
{'run_img2img_generation': 'run image-to-image generation using a latent consistency model pipeline with a prompt and input image', 'encode_prompt_embeddings': 'encode a text prompt into CLIP text encoder hidden states for image generation', 'prepare_latents_from_image': 'prepare initial latents by encoding an input image through the VAE and adding noise', 'encode_image_for_ip_adapter': 'encode an image into hidden states or embeddings for use with IP Adapter image conditioning', 'get_guidance_scale_embedding': 'generate sinusoidal guidance scale embedding vectors to enrich timestep embeddings for the UNet'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/latent_consistency_models/pipeline_latent_consistency_text2img.py

Prompts

```
['run image-to-image generation using a latent consistency model pipeline with a prompt and input image', 'encode a text prompt into CLIP text encoder hidden states for image generation', 'prepare initial latents by encoding an input image through the VAE and adding noise', 'encode an image into hidden states or embeddings for use with IP Adapter image conditioning', 'generate sinusoidal guidance scale embedding vectors to enrich timestep embeddings for the UNet', 'run the LatentConsistencyModelPipeline to generate images from a text prompt using LCM distillation', 'build a LatentConsistencyModelPipeline from pretrained weights using DiffusionPipeline.from_pretrained and generate images', 'create a custom timestep schedule by calling retrieve_timesteps with a scheduler and num_inference_steps', 'test the encode_prompt method to convert text prompts into CLIP text encoder hidden states', 'review the get_guidance_scale_embedding method that generates sinusoidal embeddings for the guidance scale']
```

Usage

```
{'run_LatentConsistencyModelPipeline': 'run the LatentConsistencyModelPipeline to generate images from a text prompt using LCM distillation', 'build_LatentConsistencyModelPipeline': 'build a LatentConsistencyModelPipeline from pretrained weights using DiffusionPipeline.from_pretrained and generate images', 'create_retrieve_timesteps': 'create a custom timestep schedule by calling retrieve_timesteps with a scheduler and num_inference_steps', 'test_encode_prompt': 'test the encode_prompt method to convert text prompts into CLIP text encoder hidden states', 'review_get_guidance_scale_embedding': 'review the get_guidance_scale_embedding method that generates sinusoidal embeddings for the guidance scale'}
```

