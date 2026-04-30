# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/pixart_alpha/pipeline_pixart_alpha.py

Prompts

```
['generate an image from a text prompt using the PixArtAlphaPipeline with classifier-free guidance', 'encode a text prompt into T5 text embeddings and attention masks for image generation', 'clean and normalize a caption string by removing URLs, HTML, special characters, and artifacts', 'prepare initial random noise latents scaled by the scheduler sigma for a given batch size and shape', 'retrieve the timestep schedule from a diffusion scheduler given custom timesteps, sigmas, or inference steps', 'run PixArtSigmaPipeline to generate an image from a text prompt using from_pretrained', 'encode a text prompt into T5 text embeddings using PixArtSigmaPipeline encode_prompt method', 'prepare random noise latents scaled by init_noise_sigma using PixArtSigmaPipeline prepare_latents method', 'clean and preprocess a caption string by removing URLs, HTML, and special characters using _clean_caption', 'validate prompt, height, width, and embedding inputs using PixArtSigmaPipeline check_inputs method']
```

Usage

```
{'generate_image_from_prompt': 'generate an image from a text prompt using the PixArtAlphaPipeline with classifier-free guidance', 'encode_prompt_embeddings': 'encode a text prompt into T5 text embeddings and attention masks for image generation', 'clean_caption_text': 'clean and normalize a caption string by removing URLs, HTML, special characters, and artifacts', 'prepare_noise_latents': 'prepare initial random noise latents scaled by the scheduler sigma for a given batch size and shape', 'retrieve_scheduler_timesteps': 'retrieve the timestep schedule from a diffusion scheduler given custom timesteps, sigmas, or inference steps'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/pixart_alpha/pipeline_pixart_sigma.py

Prompts

```
['generate an image from a text prompt using the PixArtAlphaPipeline with classifier-free guidance', 'encode a text prompt into T5 text embeddings and attention masks for image generation', 'clean and normalize a caption string by removing URLs, HTML, special characters, and artifacts', 'prepare initial random noise latents scaled by the scheduler sigma for a given batch size and shape', 'retrieve the timestep schedule from a diffusion scheduler given custom timesteps, sigmas, or inference steps', 'run PixArtSigmaPipeline to generate an image from a text prompt using from_pretrained', 'encode a text prompt into T5 text embeddings using PixArtSigmaPipeline encode_prompt method', 'prepare random noise latents scaled by init_noise_sigma using PixArtSigmaPipeline prepare_latents method', 'clean and preprocess a caption string by removing URLs, HTML, and special characters using _clean_caption', 'validate prompt, height, width, and embedding inputs using PixArtSigmaPipeline check_inputs method']
```

Usage

```
{'generate_image_pixart_sigma': 'run PixArtSigmaPipeline to generate an image from a text prompt using from_pretrained', 'encode_prompt_pixart_sigma': 'encode a text prompt into T5 text embeddings using PixArtSigmaPipeline encode_prompt method', 'prepare_latents_pixart_sigma': 'prepare random noise latents scaled by init_noise_sigma using PixArtSigmaPipeline prepare_latents method', 'clean_caption_pixart_sigma': 'clean and preprocess a caption string by removing URLs, HTML, and special characters using _clean_caption', 'check_inputs_pixart_sigma': 'validate prompt, height, width, and embedding inputs using PixArtSigmaPipeline check_inputs method'}
```

