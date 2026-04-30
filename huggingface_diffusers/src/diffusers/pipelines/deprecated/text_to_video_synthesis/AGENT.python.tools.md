# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/text_to_video_synthesis/pipeline_text_to_video_synth.py

Prompts

```
['run the TextToVideoSDPipeline to generate video frames from a text prompt using a pretrained model', 'encode a text prompt into CLIP text embeddings using the encode_prompt method with optional negative prompt', 'decode video latents back to pixel space frames using the decode_latents method and VAE', 'prepare initial noisy latents with a given shape and scheduler sigma using the prepare_latents method', 'validate prompt height width and callback inputs using the check_inputs method before generation', 'run the VideoToVideoSDPipeline to generate a text-guided video from an input video using diffusion', 'encode a text prompt into CLIP text embeddings using the encode_prompt method', 'prepare noisy latents from an input video using the prepare_latents method with a given timestep', 'retrieve latents from a VAE encoder output using the retrieve_latents function', 'build a zero-shot text-to-video generation pipeline using TextToVideoZeroPipeline with a text prompt', 'create a CrossFrameAttnProcessor to make each video frame attend only to the first frame', 'warp video latents using create_motion_field_and_warp_latents with x and y motion strength', 'run the backward denoising loop on latents using backward_loop with prompt embeddings and guidance scale', 'encode a text prompt into CLIP text embeddings using encode_prompt for classifier-free guidance', 'run the TextToVideoZeroSDXLPipeline to generate a video from a text prompt using SDXL', 'build a CrossFrameAttnProcessor that makes each video frame attend only to the first frame', 'create a translation motion field and warp video latents along x and y axes', 'encode a text prompt into CLIP text embeddings using the SDXL dual text encoders', 'review the backward_loop method that performs the DDPM denoising process across specified timesteps']
```

Usage

```
{'run_text_to_video_generation': 'run the TextToVideoSDPipeline to generate video frames from a text prompt using a pretrained model', 'encode_prompt_embeddings': 'encode a text prompt into CLIP text embeddings using the encode_prompt method with optional negative prompt', 'decode_latents_to_video': 'decode video latents back to pixel space frames using the decode_latents method and VAE', 'prepare_latents_for_generation': 'prepare initial noisy latents with a given shape and scheduler sigma using the prepare_latents method', 'check_pipeline_inputs': 'validate prompt height width and callback inputs using the check_inputs method before generation'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/text_to_video_synthesis/pipeline_text_to_video_synth_img2img.py

Prompts

```
['run the TextToVideoSDPipeline to generate video frames from a text prompt using a pretrained model', 'encode a text prompt into CLIP text embeddings using the encode_prompt method with optional negative prompt', 'decode video latents back to pixel space frames using the decode_latents method and VAE', 'prepare initial noisy latents with a given shape and scheduler sigma using the prepare_latents method', 'validate prompt height width and callback inputs using the check_inputs method before generation', 'run the VideoToVideoSDPipeline to generate a text-guided video from an input video using diffusion', 'encode a text prompt into CLIP text embeddings using the encode_prompt method', 'prepare noisy latents from an input video using the prepare_latents method with a given timestep', 'retrieve latents from a VAE encoder output using the retrieve_latents function', 'build a zero-shot text-to-video generation pipeline using TextToVideoZeroPipeline with a text prompt', 'create a CrossFrameAttnProcessor to make each video frame attend only to the first frame', 'warp video latents using create_motion_field_and_warp_latents with x and y motion strength', 'run the backward denoising loop on latents using backward_loop with prompt embeddings and guidance scale', 'encode a text prompt into CLIP text embeddings using encode_prompt for classifier-free guidance', 'run the TextToVideoZeroSDXLPipeline to generate a video from a text prompt using SDXL', 'build a CrossFrameAttnProcessor that makes each video frame attend only to the first frame', 'create a translation motion field and warp video latents along x and y axes', 'encode a text prompt into CLIP text embeddings using the SDXL dual text encoders', 'review the backward_loop method that performs the DDPM denoising process across specified timesteps']
```

Usage

```
{'run_video_to_video_generation': 'run the VideoToVideoSDPipeline to generate a text-guided video from an input video using diffusion', 'encode_prompt_with_clip': 'encode a text prompt into CLIP text embeddings using the encode_prompt method', 'decode_latents_to_video': 'decode latent tensors back into video frames using the decode_latents method', 'prepare_noisy_latents': 'prepare noisy latents from an input video using the prepare_latents method with a given timestep', 'retrieve_latents_from_encoder': 'retrieve latents from a VAE encoder output using the retrieve_latents function'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/text_to_video_synthesis/pipeline_text_to_video_zero.py

Prompts

```
['run the TextToVideoSDPipeline to generate video frames from a text prompt using a pretrained model', 'encode a text prompt into CLIP text embeddings using the encode_prompt method with optional negative prompt', 'decode video latents back to pixel space frames using the decode_latents method and VAE', 'prepare initial noisy latents with a given shape and scheduler sigma using the prepare_latents method', 'validate prompt height width and callback inputs using the check_inputs method before generation', 'run the VideoToVideoSDPipeline to generate a text-guided video from an input video using diffusion', 'encode a text prompt into CLIP text embeddings using the encode_prompt method', 'prepare noisy latents from an input video using the prepare_latents method with a given timestep', 'retrieve latents from a VAE encoder output using the retrieve_latents function', 'build a zero-shot text-to-video generation pipeline using TextToVideoZeroPipeline with a text prompt', 'create a CrossFrameAttnProcessor to make each video frame attend only to the first frame', 'warp video latents using create_motion_field_and_warp_latents with x and y motion strength', 'run the backward denoising loop on latents using backward_loop with prompt embeddings and guidance scale', 'encode a text prompt into CLIP text embeddings using encode_prompt for classifier-free guidance', 'run the TextToVideoZeroSDXLPipeline to generate a video from a text prompt using SDXL', 'build a CrossFrameAttnProcessor that makes each video frame attend only to the first frame', 'create a translation motion field and warp video latents along x and y axes', 'encode a text prompt into CLIP text embeddings using the SDXL dual text encoders', 'review the backward_loop method that performs the DDPM denoising process across specified timesteps']
```

Usage

```
{'build_text_to_video_pipeline': 'build a zero-shot text-to-video generation pipeline using TextToVideoZeroPipeline with a text prompt', 'create_cross_frame_attention_processor': 'create a CrossFrameAttnProcessor to make each video frame attend only to the first frame', 'warp_latents_with_motion_field': 'warp video latents using create_motion_field_and_warp_latents with x and y motion strength', 'run_backward_denoising_loop': 'run the backward denoising loop on latents using backward_loop with prompt embeddings and guidance scale', 'encode_text_prompt': 'encode a text prompt into CLIP text embeddings using encode_prompt for classifier-free guidance'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/text_to_video_synthesis/pipeline_text_to_video_zero_sdxl.py

Prompts

```
['run the TextToVideoSDPipeline to generate video frames from a text prompt using a pretrained model', 'encode a text prompt into CLIP text embeddings using the encode_prompt method with optional negative prompt', 'decode video latents back to pixel space frames using the decode_latents method and VAE', 'prepare initial noisy latents with a given shape and scheduler sigma using the prepare_latents method', 'validate prompt height width and callback inputs using the check_inputs method before generation', 'run the VideoToVideoSDPipeline to generate a text-guided video from an input video using diffusion', 'encode a text prompt into CLIP text embeddings using the encode_prompt method', 'prepare noisy latents from an input video using the prepare_latents method with a given timestep', 'retrieve latents from a VAE encoder output using the retrieve_latents function', 'build a zero-shot text-to-video generation pipeline using TextToVideoZeroPipeline with a text prompt', 'create a CrossFrameAttnProcessor to make each video frame attend only to the first frame', 'warp video latents using create_motion_field_and_warp_latents with x and y motion strength', 'run the backward denoising loop on latents using backward_loop with prompt embeddings and guidance scale', 'encode a text prompt into CLIP text embeddings using encode_prompt for classifier-free guidance', 'run the TextToVideoZeroSDXLPipeline to generate a video from a text prompt using SDXL', 'build a CrossFrameAttnProcessor that makes each video frame attend only to the first frame', 'create a translation motion field and warp video latents along x and y axes', 'encode a text prompt into CLIP text embeddings using the SDXL dual text encoders', 'review the backward_loop method that performs the DDPM denoising process across specified timesteps']
```

Usage

```
{'run_TextToVideoZeroSDXLPipeline': 'run the TextToVideoZeroSDXLPipeline to generate a video from a text prompt using SDXL', 'build_CrossFrameAttnProcessor': 'build a CrossFrameAttnProcessor that makes each video frame attend only to the first frame', 'create_motion_field_and_warp_latents': 'create a translation motion field and warp video latents along x and y axes', 'encode_prompt_TextToVideoZeroSDXLPipeline': 'encode a text prompt into CLIP text embeddings using the SDXL dual text encoders', 'review_backward_loop': 'review the backward_loop method that performs the DDPM denoising process across specified timesteps'}
```

