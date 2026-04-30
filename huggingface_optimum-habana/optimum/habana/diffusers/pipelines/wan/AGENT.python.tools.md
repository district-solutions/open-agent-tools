# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/diffusers/pipelines/wan/pipeline_wan.py

Prompts

```
['build a GaudiWanPipeline from pretrained Wan2.2 model with habana and hpu_graphs enabled for video generation', 'run the GaudiWanPipeline to generate a video from a text prompt with guidance scale and frame count', 'prepare latent tensors for the Wan pipeline with specified batch size, height, width, and frame count', 'configure distributed classifier-free guidance across multiple HPU devices for faster inference with Wan pipeline', 'review the GaudiWanPipeline constructor to understand habana-specific initialization with transformer and VAE forward method patching', 'generate a video from an input image using GaudiWanImageToVideoPipeline with Habana HPU acceleration', 'initialize a GaudiWanImageToVideoPipeline with a pretrained Wan2.2 model and HPU graph optimization', 'prepare latent variables and image conditions for the Wan image-to-video diffusion pipeline', 'encode text prompts and image embeddings using the UMT5 text encoder and CLIP image encoder']
```

Usage

```
{'build_gaudi_wan_pipeline': 'build a GaudiWanPipeline from pretrained Wan2.2 model with habana and hpu_graphs enabled for video generation', 'run_gaudi_wan_video_generation': 'run the GaudiWanPipeline to generate a video from a text prompt with guidance scale and frame count', 'prepare_latents_for_wan': 'prepare latent tensors for the Wan pipeline with specified batch size, height, width, and frame count', 'configure_distributed_cfg': 'configure distributed classifier-free guidance across multiple HPU devices for faster inference with Wan pipeline', 'review_gaudi_wan_init': 'review the GaudiWanPipeline constructor to understand habana-specific initialization with transformer and VAE forward method patching'}
```

## File: huggingface_optimum-habana/optimum/habana/diffusers/pipelines/wan/pipeline_wan_i2v.py

Prompts

```
['build a GaudiWanPipeline from pretrained Wan2.2 model with habana and hpu_graphs enabled for video generation', 'run the GaudiWanPipeline to generate a video from a text prompt with guidance scale and frame count', 'prepare latent tensors for the Wan pipeline with specified batch size, height, width, and frame count', 'configure distributed classifier-free guidance across multiple HPU devices for faster inference with Wan pipeline', 'review the GaudiWanPipeline constructor to understand habana-specific initialization with transformer and VAE forward method patching', 'generate a video from an input image using GaudiWanImageToVideoPipeline with Habana HPU acceleration', 'initialize a GaudiWanImageToVideoPipeline with a pretrained Wan2.2 model and HPU graph optimization', 'prepare latent variables and image conditions for the Wan image-to-video diffusion pipeline', 'encode text prompts and image embeddings using the UMT5 text encoder and CLIP image encoder']
```

Usage

```
{'generate_video_from_image': 'generate a video from an input image using GaudiWanImageToVideoPipeline with Habana HPU acceleration', 'initialize_pipeline': 'initialize a GaudiWanImageToVideoPipeline with a pretrained Wan2.2 model and HPU graph optimization', 'prepare_latents': 'prepare latent variables and image conditions for the Wan image-to-video diffusion pipeline', 'configure_distributed_cfg': 'configure distributed classifier-free guidance across multiple HPU devices for faster inference', 'encode_prompt_and_image': 'encode text prompts and image embeddings using the UMT5 text encoder and CLIP image encoder'}
```

