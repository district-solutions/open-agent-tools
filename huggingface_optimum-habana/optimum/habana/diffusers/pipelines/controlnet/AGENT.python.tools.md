# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/diffusers/pipelines/controlnet/pipeline_controlnet.py

Prompts

```
['run the GaudiStableDiffusionControlNetPipeline to generate images from a text prompt and control image on HPU', 'prepare initial noise latents for the diffusion process with HPU-aware random generation', 'run the UNet forward pass through the unet_hpu method with optional HPU graph capture and replay', 'run the ControlNet forward pass through the controlnet_hpu method with optional HPU graph capture and replay', 'capture and cache the UNet computation graph for replay with updated inputs using unet_capture_replay', 'run the GaudiStableVideoDiffusionControlNetPipeline to generate a video from an image with ControlNet conditioning on HPU', 'encode an input image into CLIP image embeddings using the pipeline _encode_image method', 'split latents, image embeddings, and ControlNet conditions into batches for HPU batched inference', 'capture and replay a cached HPU graph for the ControlNet model to accelerate inference']
```

Usage

```
{'run_controlnet_image_generation': 'run the GaudiStableDiffusionControlNetPipeline to generate images from a text prompt and control image on HPU', 'prepare_latents_for_diffusion': 'prepare initial noise latents for the diffusion process with HPU-aware random generation', 'run_unet_forward_hpu': 'run the UNet forward pass through the unet_hpu method with optional HPU graph capture and replay', 'run_controlnet_forward_hpu': 'run the ControlNet forward pass through the controlnet_hpu method with optional HPU graph capture and replay', 'capture_unet_hpu_graph': 'capture and cache the UNet computation graph for replay with updated inputs using unet_capture_replay'}
```

## File: huggingface_optimum-habana/optimum/habana/diffusers/pipelines/controlnet/pipeline_stable_video_diffusion_controlnet.py

Prompts

```
['run the GaudiStableDiffusionControlNetPipeline to generate images from a text prompt and control image on HPU', 'prepare initial noise latents for the diffusion process with HPU-aware random generation', 'run the UNet forward pass through the unet_hpu method with optional HPU graph capture and replay', 'run the ControlNet forward pass through the controlnet_hpu method with optional HPU graph capture and replay', 'capture and cache the UNet computation graph for replay with updated inputs using unet_capture_replay', 'run the GaudiStableVideoDiffusionControlNetPipeline to generate a video from an image with ControlNet conditioning on HPU', 'encode an input image into CLIP image embeddings using the pipeline _encode_image method', 'split latents, image embeddings, and ControlNet conditions into batches for HPU batched inference', 'capture and replay a cached HPU graph for the ControlNet model to accelerate inference']
```

Usage

```
{'run_svd_controlnet_pipeline': 'run the GaudiStableVideoDiffusionControlNetPipeline to generate a video from an image with ControlNet conditioning on HPU', 'encode_image_with_clip': 'encode an input image into CLIP image embeddings using the pipeline _encode_image method', 'split_inputs_into_batches': 'split latents, image embeddings, and ControlNet conditions into batches for HPU batched inference', 'capture_controlnet_hpu_graph': 'capture and replay a cached HPU graph for the ControlNet model to accelerate inference', 'capture_unet_hpu_graph': 'capture and replay a cached HPU graph for the UNet spatio-temporal model to accelerate inference'}
```

