# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/helios/pipeline_helios.py

Prompts

```
['generate a video from a text prompt using the HeliosPipeline with custom height, width, and frame count', 'generate a video from an input image using HeliosPipeline with image latents and noise sigma parameters', 'generate a transformed video from an input video using HeliosPipeline with video latents and chunked encoding', 'encode a text prompt into T5 embeddings using the HeliosPipeline encode_prompt method with classifier-free guidance', 'prepare random noisy latent tensors for video generation with configurable batch size, frames, and spatial dimensions', 'run the HeliosPyramidPipeline to generate a video from a text prompt with configurable height, width, and frames', 'run the HeliosPyramidPipeline with an input image to generate a video using image-to-video mode', 'run the HeliosPyramidPipeline with an input video to generate a modified video using video-to-video mode', 'encode a text prompt into T5 embeddings using the encode_prompt method with optional negative prompt support', 'prepare random or custom latent tensors for video generation using the prepare_latents method']
```

Usage

```
{'generate_text_to_video': 'generate a video from a text prompt using the HeliosPipeline with custom height, width, and frame count', 'generate_image_to_video': 'generate a video from an input image using HeliosPipeline with image latents and noise sigma parameters', 'generate_video_to_video': 'generate a transformed video from an input video using HeliosPipeline with video latents and chunked encoding', 'encode_prompt_t5': 'encode a text prompt into T5 embeddings using the HeliosPipeline encode_prompt method with classifier-free guidance', 'prepare_latents': 'prepare random noisy latent tensors for video generation with configurable batch size, frames, and spatial dimensions'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/helios/pipeline_helios_pyramid.py

Prompts

```
['generate a video from a text prompt using the HeliosPipeline with custom height, width, and frame count', 'generate a video from an input image using HeliosPipeline with image latents and noise sigma parameters', 'generate a transformed video from an input video using HeliosPipeline with video latents and chunked encoding', 'encode a text prompt into T5 embeddings using the HeliosPipeline encode_prompt method with classifier-free guidance', 'prepare random noisy latent tensors for video generation with configurable batch size, frames, and spatial dimensions', 'run the HeliosPyramidPipeline to generate a video from a text prompt with configurable height, width, and frames', 'run the HeliosPyramidPipeline with an input image to generate a video using image-to-video mode', 'run the HeliosPyramidPipeline with an input video to generate a modified video using video-to-video mode', 'encode a text prompt into T5 embeddings using the encode_prompt method with optional negative prompt support', 'prepare random or custom latent tensors for video generation using the prepare_latents method']
```

Usage

```
{'run_text_to_video_generation': 'run the HeliosPyramidPipeline to generate a video from a text prompt with configurable height, width, and frames', 'run_image_to_video_generation': 'run the HeliosPyramidPipeline with an input image to generate a video using image-to-video mode', 'run_video_to_video_generation': 'run the HeliosPyramidPipeline with an input video to generate a modified video using video-to-video mode', 'encode_prompt_with_t5': 'encode a text prompt into T5 embeddings using the encode_prompt method with optional negative prompt support', 'prepare_latents_for_generation': 'prepare random or custom latent tensors for video generation using the prepare_latents method'}
```

