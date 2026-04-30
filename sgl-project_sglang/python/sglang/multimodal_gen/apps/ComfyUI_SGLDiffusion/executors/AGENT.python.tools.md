# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/apps/ComfyUI_SGLDiffusion/executors/base.py

Prompts

```
['create an SGLDiffusionExecutor instance with generator, model_path, model, and config arguments', 'set a LoRA adapter on the executor with nickname, path, strength, and optional target', 'unpack latents from packed format to standard batch, channels, height, width tensor format', 'pack latents from standard tensor format into compressed packed layout', 'check whether logging should be suppressed based on a timestep value below 1.0', 'build a FluxExecutor instance for running Flux diffusion models in ComfyUI with a generator, model path, model, and config', 'create SamplingParams using from_user_sampling_params_args with model path, server args, guidance scale, height, width, and inference steps', 'run the FluxExecutor forward pass with latents, timestep, context, pooled projections, and guidance to get noise predictions', 'prepare a scheduler request from SamplingParams and server args, setting latents, timesteps, prompt embeds, and generators', 'review the FluxExecutor forward method that packs latents, builds a request, sends it to the scheduler, and unpacks the noise prediction', 'create a QwenImageExecutor instance for running QwenImage diffusion models in ComfyUI', 'run the QwenImageExecutor forward pass to generate images from latents and context embeddings', 'build a QwenImageEditExecutor forward pass with reference latents for image editing tasks', 'test the QwenImageExecutor _pack_latents method to reshape latents for model input', 'review the QwenImageExecutor _unpack_latents method to convert packed latents back to standard format', 'create a ZImageExecutor instance with generator, model_path, model, and config arguments', 'run the ZImageExecutor forward pass with latents, timesteps, and context tensors', 'build SamplingParams using from_user_sampling_params_args with model_path, prompt, guidance_scale, height, width, and num_inference_steps', 'prepare a Req object from SamplingParams and server_args for ZImage inference', 'send a ZImage request to the scheduler and wait for the noise_pred response']
```

Usage

```
{'create_SGLDiffusionExecutor': 'create an SGLDiffusionExecutor instance with generator, model_path, model, and config arguments', 'set_lora_adapter': 'set a LoRA adapter on the executor with nickname, path, strength, and optional target', 'unpack_latents': 'unpack latents from packed format to standard batch, channels, height, width tensor format', 'pack_latents': 'pack latents from standard tensor format into compressed packed layout', 'should_suppress_logs': 'check whether logging should be suppressed based on a timestep value below 1.0'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/apps/ComfyUI_SGLDiffusion/executors/flux.py

Prompts

```
['create an SGLDiffusionExecutor instance with generator, model_path, model, and config arguments', 'set a LoRA adapter on the executor with nickname, path, strength, and optional target', 'unpack latents from packed format to standard batch, channels, height, width tensor format', 'pack latents from standard tensor format into compressed packed layout', 'check whether logging should be suppressed based on a timestep value below 1.0', 'build a FluxExecutor instance for running Flux diffusion models in ComfyUI with a generator, model path, model, and config', 'create SamplingParams using from_user_sampling_params_args with model path, server args, guidance scale, height, width, and inference steps', 'run the FluxExecutor forward pass with latents, timestep, context, pooled projections, and guidance to get noise predictions', 'prepare a scheduler request from SamplingParams and server args, setting latents, timesteps, prompt embeds, and generators', 'review the FluxExecutor forward method that packs latents, builds a request, sends it to the scheduler, and unpacks the noise prediction', 'create a QwenImageExecutor instance for running QwenImage diffusion models in ComfyUI', 'run the QwenImageExecutor forward pass to generate images from latents and context embeddings', 'build a QwenImageEditExecutor forward pass with reference latents for image editing tasks', 'test the QwenImageExecutor _pack_latents method to reshape latents for model input', 'review the QwenImageExecutor _unpack_latents method to convert packed latents back to standard format', 'create a ZImageExecutor instance with generator, model_path, model, and config arguments', 'run the ZImageExecutor forward pass with latents, timesteps, and context tensors', 'build SamplingParams using from_user_sampling_params_args with model_path, prompt, guidance_scale, height, width, and num_inference_steps', 'prepare a Req object from SamplingParams and server_args for ZImage inference', 'send a ZImage request to the scheduler and wait for the noise_pred response']
```

Usage

```
{'build_flux_executor': 'build a FluxExecutor instance for running Flux diffusion models in ComfyUI with a generator, model path, model, and config', 'create_sampling_params': 'create SamplingParams using from_user_sampling_params_args with model path, server args, guidance scale, height, width, and inference steps', 'run_flux_forward_pass': 'run the FluxExecutor forward pass with latents, timestep, context, pooled projections, and guidance to get noise predictions', 'prepare_scheduler_request': 'prepare a scheduler request from SamplingParams and server args, setting latents, timesteps, prompt embeds, and generators', 'review_flux_executor_forward': 'review the FluxExecutor forward method that packs latents, builds a request, sends it to the scheduler, and unpacks the noise prediction'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/apps/ComfyUI_SGLDiffusion/executors/qwen_image.py

Prompts

```
['create an SGLDiffusionExecutor instance with generator, model_path, model, and config arguments', 'set a LoRA adapter on the executor with nickname, path, strength, and optional target', 'unpack latents from packed format to standard batch, channels, height, width tensor format', 'pack latents from standard tensor format into compressed packed layout', 'check whether logging should be suppressed based on a timestep value below 1.0', 'build a FluxExecutor instance for running Flux diffusion models in ComfyUI with a generator, model path, model, and config', 'create SamplingParams using from_user_sampling_params_args with model path, server args, guidance scale, height, width, and inference steps', 'run the FluxExecutor forward pass with latents, timestep, context, pooled projections, and guidance to get noise predictions', 'prepare a scheduler request from SamplingParams and server args, setting latents, timesteps, prompt embeds, and generators', 'review the FluxExecutor forward method that packs latents, builds a request, sends it to the scheduler, and unpacks the noise prediction', 'create a QwenImageExecutor instance for running QwenImage diffusion models in ComfyUI', 'run the QwenImageExecutor forward pass to generate images from latents and context embeddings', 'build a QwenImageEditExecutor forward pass with reference latents for image editing tasks', 'test the QwenImageExecutor _pack_latents method to reshape latents for model input', 'review the QwenImageExecutor _unpack_latents method to convert packed latents back to standard format', 'create a ZImageExecutor instance with generator, model_path, model, and config arguments', 'run the ZImageExecutor forward pass with latents, timesteps, and context tensors', 'build SamplingParams using from_user_sampling_params_args with model_path, prompt, guidance_scale, height, width, and num_inference_steps', 'prepare a Req object from SamplingParams and server_args for ZImage inference', 'send a ZImage request to the scheduler and wait for the noise_pred response']
```

Usage

```
{'create_QwenImageExecutor': 'create a QwenImageExecutor instance for running QwenImage diffusion models in ComfyUI', 'run_QwenImageExecutor_forward': 'run the QwenImageExecutor forward pass to generate images from latents and context embeddings', 'build_QwenImageEditExecutor_forward': 'build a QwenImageEditExecutor forward pass with reference latents for image editing tasks', 'test_QwenImageExecutor_pack_latents': 'test the QwenImageExecutor _pack_latents method to reshape latents for model input', 'review_QwenImageExecutor_unpack_latents': 'review the QwenImageExecutor _unpack_latents method to convert packed latents back to standard format'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/apps/ComfyUI_SGLDiffusion/executors/zimage.py

Prompts

```
['create an SGLDiffusionExecutor instance with generator, model_path, model, and config arguments', 'set a LoRA adapter on the executor with nickname, path, strength, and optional target', 'unpack latents from packed format to standard batch, channels, height, width tensor format', 'pack latents from standard tensor format into compressed packed layout', 'check whether logging should be suppressed based on a timestep value below 1.0', 'build a FluxExecutor instance for running Flux diffusion models in ComfyUI with a generator, model path, model, and config', 'create SamplingParams using from_user_sampling_params_args with model path, server args, guidance scale, height, width, and inference steps', 'run the FluxExecutor forward pass with latents, timestep, context, pooled projections, and guidance to get noise predictions', 'prepare a scheduler request from SamplingParams and server args, setting latents, timesteps, prompt embeds, and generators', 'review the FluxExecutor forward method that packs latents, builds a request, sends it to the scheduler, and unpacks the noise prediction', 'create a QwenImageExecutor instance for running QwenImage diffusion models in ComfyUI', 'run the QwenImageExecutor forward pass to generate images from latents and context embeddings', 'build a QwenImageEditExecutor forward pass with reference latents for image editing tasks', 'test the QwenImageExecutor _pack_latents method to reshape latents for model input', 'review the QwenImageExecutor _unpack_latents method to convert packed latents back to standard format', 'create a ZImageExecutor instance with generator, model_path, model, and config arguments', 'run the ZImageExecutor forward pass with latents, timesteps, and context tensors', 'build SamplingParams using from_user_sampling_params_args with model_path, prompt, guidance_scale, height, width, and num_inference_steps', 'prepare a Req object from SamplingParams and server_args for ZImage inference', 'send a ZImage request to the scheduler and wait for the noise_pred response']
```

Usage

```
{'create_ZImageExecutor': 'create a ZImageExecutor instance with generator, model_path, model, and config arguments', 'run_ZImageExecutor_forward': 'run the ZImageExecutor forward pass with latents, timesteps, and context tensors', 'build_SamplingParams': 'build SamplingParams using from_user_sampling_params_args with model_path, prompt, guidance_scale, height, width, and num_inference_steps', 'prepare_request_from_params': 'prepare a Req object from SamplingParams and server_args for ZImage inference', 'send_request_to_scheduler': 'send a ZImage request to the scheduler and wait for the noise_pred response'}
```

