# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/kandinsky3/convert_kandinsky3_unet.py

Prompts

```
['convert a U-Net PyTorch model to Kandinsky3UNet format using the CLI with --model_path and --output_path', 'convert a U-Net state dictionary to match the key format expected by Kandinsky3UNet', 'load a safetensors U-Net model, convert its state dict, and save as Kandinsky3UNet', 'remap U-Net state dict keys using static and dynamic pattern matching for Kandinsky3UNet compatibility', 'save a converted Kandinsky3UNet model to a pretrained directory using save_pretrained', 'generate an image from a text prompt using the Kandinsky3Pipeline with classifier-free guidance', 'encode a text prompt into T5 text embeddings with optional negative prompt support', 'prepare initial random noise latents scaled by the scheduler init noise sigma', 'process and trim text embeddings by cutting unused context based on the attention mask', 'downscale height and width dimensions by a given scale factor for latent space resolution', 'run the Kandinsky3Img2ImgPipeline to generate an image from a prompt and input image with strength control', 'prepare latent representations from an input image by encoding with MoVQ and adding scheduler noise', 'compute the denoising timesteps and adjusted step count based on the strength parameter for img2img', 'validate all input arguments including prompt, embeddings, attention masks, and callback settings']
```

Usage

```
{'convert_unet_to_kandinsky3': 'convert a U-Net PyTorch model to Kandinsky3UNet format using the CLI with --model_path and --output_path', 'convert_state_dict_function': 'convert a U-Net state dictionary to match the key format expected by Kandinsky3UNet', 'load_and_convert_unet': 'load a safetensors U-Net model, convert its state dict, and save as Kandinsky3UNet', 'remap_unet_keys': 'remap U-Net state dict keys using static and dynamic pattern matching for Kandinsky3UNet compatibility', 'save_kandinsky3_unet': 'save a converted Kandinsky3UNet model to a pretrained directory using save_pretrained'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/kandinsky3/pipeline_kandinsky3.py

Prompts

```
['convert a U-Net PyTorch model to Kandinsky3UNet format using the CLI with --model_path and --output_path', 'convert a U-Net state dictionary to match the key format expected by Kandinsky3UNet', 'load a safetensors U-Net model, convert its state dict, and save as Kandinsky3UNet', 'remap U-Net state dict keys using static and dynamic pattern matching for Kandinsky3UNet compatibility', 'save a converted Kandinsky3UNet model to a pretrained directory using save_pretrained', 'generate an image from a text prompt using the Kandinsky3Pipeline with classifier-free guidance', 'encode a text prompt into T5 text embeddings with optional negative prompt support', 'prepare initial random noise latents scaled by the scheduler init noise sigma', 'process and trim text embeddings by cutting unused context based on the attention mask', 'downscale height and width dimensions by a given scale factor for latent space resolution', 'run the Kandinsky3Img2ImgPipeline to generate an image from a prompt and input image with strength control', 'prepare latent representations from an input image by encoding with MoVQ and adding scheduler noise', 'compute the denoising timesteps and adjusted step count based on the strength parameter for img2img', 'validate all input arguments including prompt, embeddings, attention masks, and callback settings']
```

Usage

```
{'generate_image_from_prompt': 'generate an image from a text prompt using the Kandinsky3Pipeline with classifier-free guidance', 'encode_prompt_embeddings': 'encode a text prompt into T5 text embeddings with optional negative prompt support', 'prepare_diffusion_latents': 'prepare initial random noise latents scaled by the scheduler init noise sigma', 'process_and_trim_embeds': 'process and trim text embeddings by cutting unused context based on the attention mask', 'downscale_image_dimensions': 'downscale height and width dimensions by a given scale factor for latent space resolution'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/kandinsky3/pipeline_kandinsky3_img2img.py

Prompts

```
['convert a U-Net PyTorch model to Kandinsky3UNet format using the CLI with --model_path and --output_path', 'convert a U-Net state dictionary to match the key format expected by Kandinsky3UNet', 'load a safetensors U-Net model, convert its state dict, and save as Kandinsky3UNet', 'remap U-Net state dict keys using static and dynamic pattern matching for Kandinsky3UNet compatibility', 'save a converted Kandinsky3UNet model to a pretrained directory using save_pretrained', 'generate an image from a text prompt using the Kandinsky3Pipeline with classifier-free guidance', 'encode a text prompt into T5 text embeddings with optional negative prompt support', 'prepare initial random noise latents scaled by the scheduler init noise sigma', 'process and trim text embeddings by cutting unused context based on the attention mask', 'downscale height and width dimensions by a given scale factor for latent space resolution', 'run the Kandinsky3Img2ImgPipeline to generate an image from a prompt and input image with strength control', 'prepare latent representations from an input image by encoding with MoVQ and adding scheduler noise', 'compute the denoising timesteps and adjusted step count based on the strength parameter for img2img', 'validate all input arguments including prompt, embeddings, attention masks, and callback settings']
```

Usage

```
{'run_img2img_pipeline': 'run the Kandinsky3Img2ImgPipeline to generate an image from a prompt and input image with strength control', 'encode_prompt_embeddings': 'encode a text prompt into T5 text embeddings with optional negative prompt and classifier-free guidance', 'prepare_latents_from_image': 'prepare latent representations from an input image by encoding with MoVQ and adding scheduler noise', 'compute_timesteps_for_strength': 'compute the denoising timesteps and adjusted step count based on the strength parameter for img2img', 'validate_pipeline_inputs': 'validate all input arguments including prompt, embeddings, attention masks, and callback settings'}
```

