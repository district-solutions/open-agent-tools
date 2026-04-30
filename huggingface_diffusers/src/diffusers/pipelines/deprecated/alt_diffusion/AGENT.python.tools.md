# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/alt_diffusion/modeling_roberta_series.py

Prompts

```
['create a RobertaSeriesConfig with custom project_dim and pooler_fn for text embedding projection', 'build a RobertaSeriesModelWithTransformation model from a config to project text embeddings into a lower dimension', 'run a forward pass on RobertaSeriesModelWithTransformation with input_ids to get projection_state and hidden states', 'review the TransformationModelOutput dataclass fields including projection_state last_hidden_state hidden_states and attentions', 'refactor RobertaSeriesModelWithTransformation to add or remove the optional pre_transformation linear layer and layer norm', 'run the AltDiffusionPipeline to generate images from a Chinese or English text prompt', 'encode a text prompt into embeddings using the text encoder with optional clip skip layers', 'encode an image into embeddings for use with IP Adapter image conditioning', 'rescale the noise configuration tensor to fix overexposure in classifier-free guidance', 'retrieve and configure custom timesteps or sigmas from a diffusion scheduler', 'run the AltDiffusionImg2ImgPipeline to generate images from a prompt and input image using text-guided image-to-image generation', 'encode a text prompt into text encoder hidden states using the encode_prompt method with optional negative prompts and LoRA scaling', 'prepare initial latents from an input image by encoding through VAE and adding noise at a given timestep for img2img generation', 'run the safety checker on generated images to detect NSFW content using the StableDiffusionSafetyChecker']
```

Usage

```
{'create_RobertaSeriesConfig': 'create a RobertaSeriesConfig with custom project_dim and pooler_fn for text embedding projection', 'build_RobertaSeriesModelWithTransformation': 'build a RobertaSeriesModelWithTransformation model from a config to project text embeddings into a lower dimension', 'run_forward_RobertaSeriesModelWithTransformation': 'run a forward pass on RobertaSeriesModelWithTransformation with input_ids to get projection_state and hidden states', 'review_TransformationModelOutput': 'review the TransformationModelOutput dataclass fields including projection_state last_hidden_state hidden_states and attentions', 'refactor_RobertaSeriesModelWithTransformation': 'refactor RobertaSeriesModelWithTransformation to add or remove the optional pre_transformation linear layer and layer norm'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/alt_diffusion/pipeline_alt_diffusion.py

Prompts

```
['create a RobertaSeriesConfig with custom project_dim and pooler_fn for text embedding projection', 'build a RobertaSeriesModelWithTransformation model from a config to project text embeddings into a lower dimension', 'run a forward pass on RobertaSeriesModelWithTransformation with input_ids to get projection_state and hidden states', 'review the TransformationModelOutput dataclass fields including projection_state last_hidden_state hidden_states and attentions', 'refactor RobertaSeriesModelWithTransformation to add or remove the optional pre_transformation linear layer and layer norm', 'run the AltDiffusionPipeline to generate images from a Chinese or English text prompt', 'encode a text prompt into embeddings using the text encoder with optional clip skip layers', 'encode an image into embeddings for use with IP Adapter image conditioning', 'rescale the noise configuration tensor to fix overexposure in classifier-free guidance', 'retrieve and configure custom timesteps or sigmas from a diffusion scheduler', 'run the AltDiffusionImg2ImgPipeline to generate images from a prompt and input image using text-guided image-to-image generation', 'encode a text prompt into text encoder hidden states using the encode_prompt method with optional negative prompts and LoRA scaling', 'prepare initial latents from an input image by encoding through VAE and adding noise at a given timestep for img2img generation', 'run the safety checker on generated images to detect NSFW content using the StableDiffusionSafetyChecker']
```

Usage

```
{'run_alt_diffusion_pipeline': 'run the AltDiffusionPipeline to generate images from a Chinese or English text prompt', 'encode_prompt_with_clip_skip': 'encode a text prompt into embeddings using the text encoder with optional clip skip layers', 'encode_image_for_ip_adapter': 'encode an image into embeddings for use with IP Adapter image conditioning', 'rescale_noise_cfg_overexposure': 'rescale the noise configuration tensor to fix overexposure in classifier-free guidance', 'retrieve_timesteps_from_scheduler': 'retrieve and configure custom timesteps or sigmas from a diffusion scheduler'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/alt_diffusion/pipeline_alt_diffusion_img2img.py

Prompts

```
['create a RobertaSeriesConfig with custom project_dim and pooler_fn for text embedding projection', 'build a RobertaSeriesModelWithTransformation model from a config to project text embeddings into a lower dimension', 'run a forward pass on RobertaSeriesModelWithTransformation with input_ids to get projection_state and hidden states', 'review the TransformationModelOutput dataclass fields including projection_state last_hidden_state hidden_states and attentions', 'refactor RobertaSeriesModelWithTransformation to add or remove the optional pre_transformation linear layer and layer norm', 'run the AltDiffusionPipeline to generate images from a Chinese or English text prompt', 'encode a text prompt into embeddings using the text encoder with optional clip skip layers', 'encode an image into embeddings for use with IP Adapter image conditioning', 'rescale the noise configuration tensor to fix overexposure in classifier-free guidance', 'retrieve and configure custom timesteps or sigmas from a diffusion scheduler', 'run the AltDiffusionImg2ImgPipeline to generate images from a prompt and input image using text-guided image-to-image generation', 'encode a text prompt into text encoder hidden states using the encode_prompt method with optional negative prompts and LoRA scaling', 'prepare initial latents from an input image by encoding through VAE and adding noise at a given timestep for img2img generation', 'run the safety checker on generated images to detect NSFW content using the StableDiffusionSafetyChecker']
```

Usage

```
{'run_img2img_pipeline': 'run the AltDiffusionImg2ImgPipeline to generate images from a prompt and input image using text-guided image-to-image generation', 'encode_prompt_embeddings': 'encode a text prompt into text encoder hidden states using the encode_prompt method with optional negative prompts and LoRA scaling', 'prepare_latents_for_img2img': 'prepare initial latents from an input image by encoding through VAE and adding noise at a given timestep for img2img generation', 'encode_image_for_ip_adapter': 'encode an image into hidden states or embeddings using the image encoder for IP Adapter conditional generation', 'run_safety_checker_on_images': 'run the safety checker on generated images to detect NSFW content using the StableDiffusionSafetyChecker'}
```

