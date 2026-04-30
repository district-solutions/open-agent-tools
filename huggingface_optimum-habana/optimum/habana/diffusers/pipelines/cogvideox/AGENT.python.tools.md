# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/diffusers/pipelines/cogvideox/pipeline_cogvideox.py

Prompts

```
['build a GaudiCogVideoXPipeline for text-to-video generation on Intel Gaudi HPU accelerators', 'run the GaudiCogVideoXPipeline call method to generate a video from a text prompt', 'prepare initial latent noise tensors for the CogVideoX diffusion pipeline with HPU support', 'capture and replay an HPU graph for the transformer forward pass to accelerate inference', 'run the transformer forward pass on HPU using either direct execution or HPU graph capture and replay', 'run the GaudiCogVideoXImageToVideoPipeline to generate a video from an input image and text prompt on HPU', 'configure HPU graph capture and replay in the capture_replay method to accelerate transformer forward passes', 'initialize a GaudiCogVideoXImageToVideoPipeline with tokenizer, text encoder, VAE, transformer, and scheduler components', 'apply dynamic classifier-free guidance using cosine scheduling to adjust guidance scale during denoising steps', 'review the transformer_hpu method that routes through HPU graph capture or direct transformer forward pass']
```

Usage

```
{'build_cogvideox_pipeline': 'build a GaudiCogVideoXPipeline for text-to-video generation on Intel Gaudi HPU accelerators', 'run_text_to_video': 'run the GaudiCogVideoXPipeline call method to generate a video from a text prompt', 'prepare_latents': 'prepare initial latent noise tensors for the CogVideoX diffusion pipeline with HPU support', 'capture_replay_hpu_graph': 'capture and replay an HPU graph for the transformer forward pass to accelerate inference', 'transformer_hpu_forward': 'run the transformer forward pass on HPU using either direct execution or HPU graph capture and replay'}
```

## File: huggingface_optimum-habana/optimum/habana/diffusers/pipelines/cogvideox/pipeline_cogvideox_image2video.py

Prompts

```
['build a GaudiCogVideoXPipeline for text-to-video generation on Intel Gaudi HPU accelerators', 'run the GaudiCogVideoXPipeline call method to generate a video from a text prompt', 'prepare initial latent noise tensors for the CogVideoX diffusion pipeline with HPU support', 'capture and replay an HPU graph for the transformer forward pass to accelerate inference', 'run the transformer forward pass on HPU using either direct execution or HPU graph capture and replay', 'run the GaudiCogVideoXImageToVideoPipeline to generate a video from an input image and text prompt on HPU', 'configure HPU graph capture and replay in the capture_replay method to accelerate transformer forward passes', 'initialize a GaudiCogVideoXImageToVideoPipeline with tokenizer, text encoder, VAE, transformer, and scheduler components', 'apply dynamic classifier-free guidance using cosine scheduling to adjust guidance scale during denoising steps', 'review the transformer_hpu method that routes through HPU graph capture or direct transformer forward pass']
```

Usage

```
{'run_image_to_video_generation': 'run the GaudiCogVideoXImageToVideoPipeline to generate a video from an input image and text prompt on HPU', 'configure_hpu_graph_capture': 'configure HPU graph capture and replay in the capture_replay method to accelerate transformer forward passes', 'setup_gaudi_pipeline': 'initialize a GaudiCogVideoXImageToVideoPipeline with tokenizer, text encoder, VAE, transformer, and scheduler components', 'apply_dynamic_cfg_guidance': 'apply dynamic classifier-free guidance using cosine scheduling to adjust guidance scale during denoising steps', 'review_transformer_hpu_forward': 'review the transformer_hpu method that routes through HPU graph capture or direct transformer forward pass'}
```

