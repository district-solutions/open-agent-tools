# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/chroma/pipeline_chroma.py

Prompts

```
['build a ChromaPipeline for text-to-image generation using T5 text encoder and ChromaTransformer2DModel', 'run the ChromaPipeline with a prompt and negative prompt to generate an image', 'create T5 prompt embeddings with attention masks for the Chroma transformer forward pass', 'encode prompt and negative prompt embeddings with classifier-free guidance support', 'prepare packed latent tensors and latent image IDs for the Chroma denoising loop', 'run the ChromaImg2ImgPipeline to generate an image from a prompt and input image', 'build a ChromaImg2ImgPipeline from pretrained Chroma1-HD model with CPU offloading enabled', 'encode a text prompt into T5 prompt embeddings and attention mask for the Chroma pipeline', 'prepare noisy latents from an input image using VAE encoding and scheduler noise scaling', 'calculate the shift mu value for the scheduler based on image sequence length', 'run the ChromaInpaintPipeline to inpaint masked regions of an image using a text prompt', 'encode a text prompt into T5 prompt embeddings and attention masks for the Chroma pipeline', 'prepare noisy latents from an input image by encoding, scaling noise, and packing for Chroma', 'prepare mask and masked-image latents by encoding, resizing, and packing for the Chroma transformer', 'calculate the linear shift mu for the scheduler based on image sequence length and base max parameters']
```

Usage

```
{'build_chroma_pipeline': 'build a ChromaPipeline for text-to-image generation using T5 text encoder and ChromaTransformer2DModel', 'run_chroma_text_to_image': 'run the ChromaPipeline with a prompt and negative prompt to generate an image', 'create_t5_prompt_embeds': 'create T5 prompt embeddings with attention masks for the Chroma transformer forward pass', 'encode_prompt_with_cfg': 'encode prompt and negative prompt embeddings with classifier-free guidance support', 'prepare_latents_for_chroma': 'prepare packed latent tensors and latent image IDs for the Chroma denoising loop'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/chroma/pipeline_chroma_img2img.py

Prompts

```
['build a ChromaPipeline for text-to-image generation using T5 text encoder and ChromaTransformer2DModel', 'run the ChromaPipeline with a prompt and negative prompt to generate an image', 'create T5 prompt embeddings with attention masks for the Chroma transformer forward pass', 'encode prompt and negative prompt embeddings with classifier-free guidance support', 'prepare packed latent tensors and latent image IDs for the Chroma denoising loop', 'run the ChromaImg2ImgPipeline to generate an image from a prompt and input image', 'build a ChromaImg2ImgPipeline from pretrained Chroma1-HD model with CPU offloading enabled', 'encode a text prompt into T5 prompt embeddings and attention mask for the Chroma pipeline', 'prepare noisy latents from an input image using VAE encoding and scheduler noise scaling', 'calculate the shift mu value for the scheduler based on image sequence length', 'run the ChromaInpaintPipeline to inpaint masked regions of an image using a text prompt', 'encode a text prompt into T5 prompt embeddings and attention masks for the Chroma pipeline', 'prepare noisy latents from an input image by encoding, scaling noise, and packing for Chroma', 'prepare mask and masked-image latents by encoding, resizing, and packing for the Chroma transformer', 'calculate the linear shift mu for the scheduler based on image sequence length and base max parameters']
```

Usage

```
{'run_chroma_img2img_pipeline': 'run the ChromaImg2ImgPipeline to generate an image from a prompt and input image', 'build_chroma_img2img_pipeline': 'build a ChromaImg2ImgPipeline from pretrained Chroma1-HD model with CPU offloading enabled', 'encode_prompt_t5_embeds': 'encode a text prompt into T5 prompt embeddings and attention mask for the Chroma pipeline', 'prepare_latents_img2img': 'prepare noisy latents from an input image using VAE encoding and scheduler noise scaling', 'calculate_shift_scheduler': 'calculate the shift mu value for the scheduler based on image sequence length'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/chroma/pipeline_chroma_inpainting.py

Prompts

```
['build a ChromaPipeline for text-to-image generation using T5 text encoder and ChromaTransformer2DModel', 'run the ChromaPipeline with a prompt and negative prompt to generate an image', 'create T5 prompt embeddings with attention masks for the Chroma transformer forward pass', 'encode prompt and negative prompt embeddings with classifier-free guidance support', 'prepare packed latent tensors and latent image IDs for the Chroma denoising loop', 'run the ChromaImg2ImgPipeline to generate an image from a prompt and input image', 'build a ChromaImg2ImgPipeline from pretrained Chroma1-HD model with CPU offloading enabled', 'encode a text prompt into T5 prompt embeddings and attention mask for the Chroma pipeline', 'prepare noisy latents from an input image using VAE encoding and scheduler noise scaling', 'calculate the shift mu value for the scheduler based on image sequence length', 'run the ChromaInpaintPipeline to inpaint masked regions of an image using a text prompt', 'encode a text prompt into T5 prompt embeddings and attention masks for the Chroma pipeline', 'prepare noisy latents from an input image by encoding, scaling noise, and packing for Chroma', 'prepare mask and masked-image latents by encoding, resizing, and packing for the Chroma transformer', 'calculate the linear shift mu for the scheduler based on image sequence length and base max parameters']
```

Usage

```
{'run_chroma_inpainting': 'run the ChromaInpaintPipeline to inpaint masked regions of an image using a text prompt', 'encode_prompt_chroma': 'encode a text prompt into T5 prompt embeddings and attention masks for the Chroma pipeline', 'prepare_latents_chroma': 'prepare noisy latents from an input image by encoding, scaling noise, and packing for Chroma', 'prepare_mask_latents_chroma': 'prepare mask and masked-image latents by encoding, resizing, and packing for the Chroma transformer', 'calculate_shift_chroma': 'calculate the linear shift mu for the scheduler based on image sequence length and base max parameters'}
```

