# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/diffusers/pipelines/stable_diffusion_xl/pipeline_stable_diffusion_xl.py

Prompts

```
['build a GaudiStableDiffusionXLPipeline for text-to-image generation on Intel Gaudi HPU devices', 'run the GaudiStableDiffusionXLPipeline call method to generate images from text prompts with batching support', 'create initial latent variables using prepare_latents for Stable Diffusion XL image generation', 'split prompt embeddings and latents into batches using _split_inputs_into_batches for HPU batched inference', 'capture and replay HPU graphs for the UNet forward pass using capture_replay to accelerate inference', 'run the GaudiStableDiffusionXLImg2ImgPipeline to generate images from a prompt and input image on HPU', 'run the UNet forward pass on HPU using either direct inference or HPU graph capture and replay', 'capture and cache an HPU graph for the UNet forward pass to accelerate repeated inference steps', 'initialize a GaudiStableDiffusionXLImg2ImgPipeline with VAE, text encoders, UNet, scheduler, and Gaudi config', 'run GaudiStableDiffusionXLInpaintPipeline to inpaint masked regions of an image using a text prompt on HPU', 'create a GaudiStableDiffusionXLInpaintPipeline from a pretrained model like stabilityai/stable-diffusion-xl-base-1.0 with fp16', 'run the capture_replay method to capture and replay HPU graphs for cached UNet inference', 'split and concatenate tensors into batches with optional padding for classifier-free guidance', 'run the StableDiffusionXLPipeline_HPU to generate images from text prompts on Habana Gaudi accelerators', 'create a StableDiffusionXLPipeline_HPU instance from pretrained model weights using from_pretrained for HPU inference', 'run a single UNet denoising step with classifier-free guidance and scheduler stepping in the HPU pipeline', 'set the attention processor on a UNet2DConditionModel to use HPU-optimized ScaledDotProductAttention or AttnProcessor2_0']
```

Usage

```
{'build_stable_diffusion_xl_pipeline': 'build a GaudiStableDiffusionXLPipeline for text-to-image generation on Intel Gaudi HPU devices', 'run_text_to_image_generation': 'run the GaudiStableDiffusionXLPipeline call method to generate images from text prompts with batching support', 'create_latents_for_generation': 'create initial latent variables using prepare_latents for Stable Diffusion XL image generation', 'split_inputs_into_batches': 'split prompt embeddings and latents into batches using _split_inputs_into_batches for HPU batched inference', 'capture_hpu_graph_for_unet': 'capture and replay HPU graphs for the UNet forward pass using capture_replay to accelerate inference'}
```

## File: huggingface_optimum-habana/optimum/habana/diffusers/pipelines/stable_diffusion_xl/pipeline_stable_diffusion_xl_img2img.py

Prompts

```
['build a GaudiStableDiffusionXLPipeline for text-to-image generation on Intel Gaudi HPU devices', 'run the GaudiStableDiffusionXLPipeline call method to generate images from text prompts with batching support', 'create initial latent variables using prepare_latents for Stable Diffusion XL image generation', 'split prompt embeddings and latents into batches using _split_inputs_into_batches for HPU batched inference', 'capture and replay HPU graphs for the UNet forward pass using capture_replay to accelerate inference', 'run the GaudiStableDiffusionXLImg2ImgPipeline to generate images from a prompt and input image on HPU', 'run the UNet forward pass on HPU using either direct inference or HPU graph capture and replay', 'capture and cache an HPU graph for the UNet forward pass to accelerate repeated inference steps', 'initialize a GaudiStableDiffusionXLImg2ImgPipeline with VAE, text encoders, UNet, scheduler, and Gaudi config', 'run GaudiStableDiffusionXLInpaintPipeline to inpaint masked regions of an image using a text prompt on HPU', 'create a GaudiStableDiffusionXLInpaintPipeline from a pretrained model like stabilityai/stable-diffusion-xl-base-1.0 with fp16', 'run the capture_replay method to capture and replay HPU graphs for cached UNet inference', 'split and concatenate tensors into batches with optional padding for classifier-free guidance', 'run the StableDiffusionXLPipeline_HPU to generate images from text prompts on Habana Gaudi accelerators', 'create a StableDiffusionXLPipeline_HPU instance from pretrained model weights using from_pretrained for HPU inference', 'run a single UNet denoising step with classifier-free guidance and scheduler stepping in the HPU pipeline', 'set the attention processor on a UNet2DConditionModel to use HPU-optimized ScaledDotProductAttention or AttnProcessor2_0']
```

Usage

```
{'run_img2img_pipeline': 'run the GaudiStableDiffusionXLImg2ImgPipeline to generate images from a prompt and input image on HPU', 'split_inputs_into_batches': 'split latents and prompt embeddings into padded batches for HPU batched generation', 'run_unet_hpu_forward': 'run the UNet forward pass on HPU using either direct inference or HPU graph capture and replay', 'capture_hpu_graph': 'capture and cache an HPU graph for the UNet forward pass to accelerate repeated inference steps', 'initialize_pipeline': 'initialize a GaudiStableDiffusionXLImg2ImgPipeline with VAE, text encoders, UNet, scheduler, and Gaudi config'}
```

## File: huggingface_optimum-habana/optimum/habana/diffusers/pipelines/stable_diffusion_xl/pipeline_stable_diffusion_xl_inpaint.py

Prompts

```
['build a GaudiStableDiffusionXLPipeline for text-to-image generation on Intel Gaudi HPU devices', 'run the GaudiStableDiffusionXLPipeline call method to generate images from text prompts with batching support', 'create initial latent variables using prepare_latents for Stable Diffusion XL image generation', 'split prompt embeddings and latents into batches using _split_inputs_into_batches for HPU batched inference', 'capture and replay HPU graphs for the UNet forward pass using capture_replay to accelerate inference', 'run the GaudiStableDiffusionXLImg2ImgPipeline to generate images from a prompt and input image on HPU', 'run the UNet forward pass on HPU using either direct inference or HPU graph capture and replay', 'capture and cache an HPU graph for the UNet forward pass to accelerate repeated inference steps', 'initialize a GaudiStableDiffusionXLImg2ImgPipeline with VAE, text encoders, UNet, scheduler, and Gaudi config', 'run GaudiStableDiffusionXLInpaintPipeline to inpaint masked regions of an image using a text prompt on HPU', 'create a GaudiStableDiffusionXLInpaintPipeline from a pretrained model like stabilityai/stable-diffusion-xl-base-1.0 with fp16', 'run the capture_replay method to capture and replay HPU graphs for cached UNet inference', 'split and concatenate tensors into batches with optional padding for classifier-free guidance', 'run the StableDiffusionXLPipeline_HPU to generate images from text prompts on Habana Gaudi accelerators', 'create a StableDiffusionXLPipeline_HPU instance from pretrained model weights using from_pretrained for HPU inference', 'run a single UNet denoising step with classifier-free guidance and scheduler stepping in the HPU pipeline', 'set the attention processor on a UNet2DConditionModel to use HPU-optimized ScaledDotProductAttention or AttnProcessor2_0']
```

Usage

```
{'run_sd_xl_inpaint_pipeline': 'run GaudiStableDiffusionXLInpaintPipeline to inpaint masked regions of an image using a text prompt on HPU', 'create_inpaint_pipeline_from_pretrained': 'create a GaudiStableDiffusionXLInpaintPipeline from a pretrained model like stabilityai/stable-diffusion-xl-base-1.0 with fp16', 'run_unet_hpu_forward': 'run the unet_hpu method to perform a forward pass with HPU graph capture or direct inference', 'run_capture_replay_hpu_graph': 'run the capture_replay method to capture and replay HPU graphs for cached UNet inference', 'split_and_cat_tensors': 'split and concatenate tensors into batches with optional padding for classifier-free guidance'}
```

## File: huggingface_optimum-habana/optimum/habana/diffusers/pipelines/stable_diffusion_xl/pipeline_stable_diffusion_xl_mlperf.py

Prompts

```
['build a GaudiStableDiffusionXLPipeline for text-to-image generation on Intel Gaudi HPU devices', 'run the GaudiStableDiffusionXLPipeline call method to generate images from text prompts with batching support', 'create initial latent variables using prepare_latents for Stable Diffusion XL image generation', 'split prompt embeddings and latents into batches using _split_inputs_into_batches for HPU batched inference', 'capture and replay HPU graphs for the UNet forward pass using capture_replay to accelerate inference', 'run the GaudiStableDiffusionXLImg2ImgPipeline to generate images from a prompt and input image on HPU', 'run the UNet forward pass on HPU using either direct inference or HPU graph capture and replay', 'capture and cache an HPU graph for the UNet forward pass to accelerate repeated inference steps', 'initialize a GaudiStableDiffusionXLImg2ImgPipeline with VAE, text encoders, UNet, scheduler, and Gaudi config', 'run GaudiStableDiffusionXLInpaintPipeline to inpaint masked regions of an image using a text prompt on HPU', 'create a GaudiStableDiffusionXLInpaintPipeline from a pretrained model like stabilityai/stable-diffusion-xl-base-1.0 with fp16', 'run the capture_replay method to capture and replay HPU graphs for cached UNet inference', 'split and concatenate tensors into batches with optional padding for classifier-free guidance', 'run the StableDiffusionXLPipeline_HPU to generate images from text prompts on Habana Gaudi accelerators', 'create a StableDiffusionXLPipeline_HPU instance from pretrained model weights using from_pretrained for HPU inference', 'run a single UNet denoising step with classifier-free guidance and scheduler stepping in the HPU pipeline', 'set the attention processor on a UNet2DConditionModel to use HPU-optimized ScaledDotProductAttention or AttnProcessor2_0']
```

Usage

```
{'run_stable_diffusion_xl_hpu_pipeline': 'run the StableDiffusionXLPipeline_HPU to generate images from text prompts on Habana Gaudi accelerators', 'create_stable_diffusion_xl_hpu_pipeline': 'create a StableDiffusionXLPipeline_HPU instance from pretrained model weights using from_pretrained for HPU inference', 'run_unet_denoising_step': 'run a single UNet denoising step with classifier-free guidance and scheduler stepping in the HPU pipeline', 'split_inputs_into_batches': 'split latents, prompt embeddings, and time IDs into batches for batched HPU inference with padding support', 'set_attn_processor_hpu': 'set the attention processor on a UNet2DConditionModel to use HPU-optimized ScaledDotProductAttention or AttnProcessor2_0'}
```

