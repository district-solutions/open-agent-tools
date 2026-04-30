# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/cogvideo/pipeline_cogvideox.py

Prompts

```
['generate a video from a text prompt using the CogVideoXPipeline with guidance_scale and num_inference_steps', 'encode a text prompt into T5 prompt embeddings using CogVideoXPipeline.encode_prompt with classifier-free guidance', 'prepare initial noisy latents for diffusion using CogVideoXPipeline.prepare_latents with a given shape and generator', 'decode latent tensors back to video frames using CogVideoXPipeline.decode_latents and the VAE', 'prepare 3D rotary positional embeddings for the transformer using CogVideoXPipeline._prepare_rotary_positional_embeddings', 'run the CogVideoXFunControlPipeline to generate a controlled video from a text prompt and control video', 'encode a text prompt into T5 text embeddings using the CogVideoXFunControlPipeline encode_prompt method', 'prepare initial noisy latents for video generation using the prepare_latents method with given shape and dtype', 'prepare control video latents by encoding a control video through the VAE using prepare_control_latents']
```

Usage

```
{'generate_video_from_prompt': 'generate a video from a text prompt using the CogVideoXPipeline with guidance_scale and num_inference_steps', 'encode_prompt_embeddings': 'encode a text prompt into T5 prompt embeddings using CogVideoXPipeline.encode_prompt with classifier-free guidance', 'prepare_noisy_latents': 'prepare initial noisy latents for diffusion using CogVideoXPipeline.prepare_latents with a given shape and generator', 'decode_latents_to_video': 'decode latent tensors back to video frames using CogVideoXPipeline.decode_latents and the VAE', 'prepare_rotary_embeddings': 'prepare 3D rotary positional embeddings for the transformer using CogVideoXPipeline._prepare_rotary_positional_embeddings'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/cogvideo/pipeline_cogvideox_fun_control.py

Prompts

```
['generate a video from a text prompt using the CogVideoXPipeline with guidance_scale and num_inference_steps', 'encode a text prompt into T5 prompt embeddings using CogVideoXPipeline.encode_prompt with classifier-free guidance', 'prepare initial noisy latents for diffusion using CogVideoXPipeline.prepare_latents with a given shape and generator', 'decode latent tensors back to video frames using CogVideoXPipeline.decode_latents and the VAE', 'prepare 3D rotary positional embeddings for the transformer using CogVideoXPipeline._prepare_rotary_positional_embeddings', 'run the CogVideoXFunControlPipeline to generate a controlled video from a text prompt and control video', 'encode a text prompt into T5 text embeddings using the CogVideoXFunControlPipeline encode_prompt method', 'prepare initial noisy latents for video generation using the prepare_latents method with given shape and dtype', 'prepare control video latents by encoding a control video through the VAE using prepare_control_latents']
```

Usage

```
{'run_controlled_text_to_video': 'run the CogVideoXFunControlPipeline to generate a controlled video from a text prompt and control video', 'encode_prompt_t5_embeds': 'encode a text prompt into T5 text embeddings using the CogVideoXFunControlPipeline encode_prompt method', 'prepare_latents_for_generation': 'prepare initial noisy latents for video generation using the prepare_latents method with given shape and dtype', 'prepare_control_latents_from_video': 'prepare control video latents by encoding a control video through the VAE using prepare_control_latents', 'decode_latents_to_video': 'decode latent tensors back to video frames using the decode_latents method and VAE decoder'}
```

