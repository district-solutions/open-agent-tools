# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/apps/ComfyUI_SGLDiffusion/test/test_flux_pipeline.py

Prompts

```
['test the ComfyUIFluxPipeline with custom latent inputs and pass-through scheduler', 'build a DiffGenerator from pretrained model path with ComfyUIFluxPipeline and multi-GPU support', 'create SamplingParams from user arguments including prompt, height, width, and inference steps', 'run prepare_request to build a request object from server args and sampling params', 'test sending a prepared request to the scheduler and retrieving noise_pred output', 'build a DiffGenerator from pretrained Qwen Image Edit model with ComfyUI mode enabled', 'create SamplingParams with guidance scale, height, width, and inference steps for image editing', 'prepare a diffusion request with latents, timesteps, and encoder hidden states for edit mode', 'run inference on the ComfyUI Qwen image edit pipeline and retrieve noise predictions', 'test the ComfyUI Qwen image edit pipeline end-to-end with pass-through scheduler', 'test the test_comfyui_qwen_image_pipeline_direct function with custom inputs and assertions on noise_pred', 'create SamplingParams from user arguments with guidance scale, dimensions, and inference settings', 'test sending a prepared request to the scheduler and retrieving noise_pred from the output batch', 'test the ComfyUIZImagePipeline with custom latent inputs and pass-through scheduler']
```

Usage

```
{'test_comfyui_flux_pipeline_direct': 'test the ComfyUIFluxPipeline with custom latent inputs and pass-through scheduler', 'build_DiffGenerator_from_pretrained': 'build a DiffGenerator from pretrained model path with ComfyUIFluxPipeline and multi-GPU support', 'create_SamplingParams_from_user_args': 'create SamplingParams from user arguments including prompt, height, width, and inference steps', 'run_prepare_request': 'run prepare_request to build a request object from server args and sampling params', 'test_DiffGenerator_send_to_scheduler': 'test sending a prepared request to the scheduler and retrieving noise_pred output'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/apps/ComfyUI_SGLDiffusion/test/test_qwen_image_edit_pipeline.py

Prompts

```
['test the ComfyUIFluxPipeline with custom latent inputs and pass-through scheduler', 'build a DiffGenerator from pretrained model path with ComfyUIFluxPipeline and multi-GPU support', 'create SamplingParams from user arguments including prompt, height, width, and inference steps', 'run prepare_request to build a request object from server args and sampling params', 'test sending a prepared request to the scheduler and retrieving noise_pred output', 'build a DiffGenerator from pretrained Qwen Image Edit model with ComfyUI mode enabled', 'create SamplingParams with guidance scale, height, width, and inference steps for image editing', 'prepare a diffusion request with latents, timesteps, and encoder hidden states for edit mode', 'run inference on the ComfyUI Qwen image edit pipeline and retrieve noise predictions', 'test the ComfyUI Qwen image edit pipeline end-to-end with pass-through scheduler', 'test the test_comfyui_qwen_image_pipeline_direct function with custom inputs and assertions on noise_pred', 'create SamplingParams from user arguments with guidance scale, dimensions, and inference settings', 'test sending a prepared request to the scheduler and retrieving noise_pred from the output batch', 'test the ComfyUIZImagePipeline with custom latent inputs and pass-through scheduler']
```

Usage

```
{'build_DiffGenerator': 'build a DiffGenerator from pretrained Qwen Image Edit model with ComfyUI mode enabled', 'create_SamplingParams': 'create SamplingParams with guidance scale, height, width, and inference steps for image editing', 'prepare_diffusion_request': 'prepare a diffusion request with latents, timesteps, and encoder hidden states for edit mode', 'run_inference_edit_pipeline': 'run inference on the ComfyUI Qwen image edit pipeline and retrieve noise predictions', 'test_qwen_image_edit_pipeline': 'test the ComfyUI Qwen image edit pipeline end-to-end with pass-through scheduler'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/apps/ComfyUI_SGLDiffusion/test/test_qwen_image_pipeline.py

Prompts

```
['test the ComfyUIFluxPipeline with custom latent inputs and pass-through scheduler', 'build a DiffGenerator from pretrained model path with ComfyUIFluxPipeline and multi-GPU support', 'create SamplingParams from user arguments including prompt, height, width, and inference steps', 'run prepare_request to build a request object from server args and sampling params', 'test sending a prepared request to the scheduler and retrieving noise_pred output', 'build a DiffGenerator from pretrained Qwen Image Edit model with ComfyUI mode enabled', 'create SamplingParams with guidance scale, height, width, and inference steps for image editing', 'prepare a diffusion request with latents, timesteps, and encoder hidden states for edit mode', 'run inference on the ComfyUI Qwen image edit pipeline and retrieve noise predictions', 'test the ComfyUI Qwen image edit pipeline end-to-end with pass-through scheduler', 'test the test_comfyui_qwen_image_pipeline_direct function with custom inputs and assertions on noise_pred', 'create SamplingParams from user arguments with guidance scale, dimensions, and inference settings', 'test sending a prepared request to the scheduler and retrieving noise_pred from the output batch', 'test the ComfyUIZImagePipeline with custom latent inputs and pass-through scheduler']
```

Usage

```
{'test_comfyui_qwen_image_pipeline_direct': 'test the test_comfyui_qwen_image_pipeline_direct function with custom inputs and assertions on noise_pred', 'build_DiffGenerator_from_pretrained': 'build a DiffGenerator instance from pretrained model with ComfyUI pipeline and multi-GPU support', 'create_SamplingParams_from_user_sampling_params_args': 'create SamplingParams from user arguments with guidance scale, dimensions, and inference settings', 'run_prepare_request': 'run prepare_request to build a request from server args and sampling params for the diffusion generator', 'test_send_to_scheduler_and_wait_for_response': 'test sending a prepared request to the scheduler and retrieving noise_pred from the output batch'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/apps/ComfyUI_SGLDiffusion/test/test_zimage_pipeline.py

Prompts

```
['test the ComfyUIFluxPipeline with custom latent inputs and pass-through scheduler', 'build a DiffGenerator from pretrained model path with ComfyUIFluxPipeline and multi-GPU support', 'create SamplingParams from user arguments including prompt, height, width, and inference steps', 'run prepare_request to build a request object from server args and sampling params', 'test sending a prepared request to the scheduler and retrieving noise_pred output', 'build a DiffGenerator from pretrained Qwen Image Edit model with ComfyUI mode enabled', 'create SamplingParams with guidance scale, height, width, and inference steps for image editing', 'prepare a diffusion request with latents, timesteps, and encoder hidden states for edit mode', 'run inference on the ComfyUI Qwen image edit pipeline and retrieve noise predictions', 'test the ComfyUI Qwen image edit pipeline end-to-end with pass-through scheduler', 'test the test_comfyui_qwen_image_pipeline_direct function with custom inputs and assertions on noise_pred', 'create SamplingParams from user arguments with guidance scale, dimensions, and inference settings', 'test sending a prepared request to the scheduler and retrieving noise_pred from the output batch', 'test the ComfyUIZImagePipeline with custom latent inputs and pass-through scheduler']
```

Usage

```
{'test_comfyui_zimage_pipeline_direct': 'test the ComfyUIZImagePipeline with custom latent inputs and pass-through scheduler', 'build_DiffGenerator_from_pretrained': 'build a DiffGenerator from pretrained model path with ComfyUIZImagePipeline and single-GPU support', 'create_SamplingParams_from_user_args': 'create SamplingParams from user arguments including prompt, guidance scale, height, width, and inference steps', 'run_prepare_request': 'run prepare_request to build a request object from server args and sampling params', 'test_DiffGenerator_send_to_scheduler': 'test sending a prepared request to the scheduler and retrieving noise_pred output'}
```

