# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/apps/ComfyUI_SGLDiffusion/core/generator.py

Prompts

```
['create an SGLDiffusionGenerator instance to initialize SGLang Diffusion models for ComfyUI integration', 'load a diffusion model from a checkpoint file and return an SGLDModelPatcher for ComfyUI', 'initialize a diffusion generator from a pretrained model path with a specified pipeline class name', 'get a ComfyUI model from a checkpoint file by detecting the UNET config and model type', 'close and cleanup the generator and kill associated worker processes', 'create an SGLDModelPatcher instance with model, load_device, offload_device, and optional model_type', 'clone an SGLDModelPatcher instance preserving patches, object_patches, model_options, and lora_cache', 'get the model size in bytes for a given model_type like flux or lumina2', 'load an SGLDModelPatcher model (no-op for SGLang Diffusion)', 'patch an SGLDModelPatcher model with device and lowvram options (no-op for SGLang Diffusion)', 'create an SGLDiffusionServerAPI client and generate an image from a text prompt with size and style options', 'edit an existing image using SGLDiffusionServerAPI with an input image and optional mask path', 'generate a video from a text prompt using SGLDiffusionServerAPI with configurable size and duration', 'get model information from an SGLDiffusionServerAPI including task type and GPU count', 'set or unset a LoRA adapter on an SGLDiffusionServerAPI with target transformer selection']
```

Usage

```
{'create_SGLDiffusionGenerator': 'create an SGLDiffusionGenerator instance to initialize SGLang Diffusion models for ComfyUI integration', 'load_model_SGLDiffusionGenerator': 'load a diffusion model from a checkpoint file and return an SGLDModelPatcher for ComfyUI', 'init_generator_SGLDiffusionGenerator': 'initialize a diffusion generator from a pretrained model path with a specified pipeline class name', 'get_comfyui_model_SGLDiffusionGenerator': 'get a ComfyUI model from a checkpoint file by detecting the UNET config and model type', 'close_generator_SGLDiffusionGenerator': 'close and cleanup the generator and kill associated worker processes'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/apps/ComfyUI_SGLDiffusion/core/model_patcher.py

Prompts

```
['create an SGLDiffusionGenerator instance to initialize SGLang Diffusion models for ComfyUI integration', 'load a diffusion model from a checkpoint file and return an SGLDModelPatcher for ComfyUI', 'initialize a diffusion generator from a pretrained model path with a specified pipeline class name', 'get a ComfyUI model from a checkpoint file by detecting the UNET config and model type', 'close and cleanup the generator and kill associated worker processes', 'create an SGLDModelPatcher instance with model, load_device, offload_device, and optional model_type', 'clone an SGLDModelPatcher instance preserving patches, object_patches, model_options, and lora_cache', 'get the model size in bytes for a given model_type like flux or lumina2', 'load an SGLDModelPatcher model (no-op for SGLang Diffusion)', 'patch an SGLDModelPatcher model with device and lowvram options (no-op for SGLang Diffusion)', 'create an SGLDiffusionServerAPI client and generate an image from a text prompt with size and style options', 'edit an existing image using SGLDiffusionServerAPI with an input image and optional mask path', 'generate a video from a text prompt using SGLDiffusionServerAPI with configurable size and duration', 'get model information from an SGLDiffusionServerAPI including task type and GPU count', 'set or unset a LoRA adapter on an SGLDiffusionServerAPI with target transformer selection']
```

Usage

```
{'create_SGLDModelPatcher': 'create an SGLDModelPatcher instance with model, load_device, offload_device, and optional model_type', 'clone_SGLDModelPatcher': 'clone an SGLDModelPatcher instance preserving patches, object_patches, model_options, and lora_cache', 'get_SGLDModelPatcher_model_size': 'get the model size in bytes for a given model_type like flux or lumina2', 'load_SGLDModelPatcher': 'load an SGLDModelPatcher model (no-op for SGLang Diffusion)', 'patch_model_SGLDModelPatcher': 'patch an SGLDModelPatcher model with device and lowvram options (no-op for SGLang Diffusion)'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/apps/ComfyUI_SGLDiffusion/core/server_api.py

Prompts

```
['create an SGLDiffusionGenerator instance to initialize SGLang Diffusion models for ComfyUI integration', 'load a diffusion model from a checkpoint file and return an SGLDModelPatcher for ComfyUI', 'initialize a diffusion generator from a pretrained model path with a specified pipeline class name', 'get a ComfyUI model from a checkpoint file by detecting the UNET config and model type', 'close and cleanup the generator and kill associated worker processes', 'create an SGLDModelPatcher instance with model, load_device, offload_device, and optional model_type', 'clone an SGLDModelPatcher instance preserving patches, object_patches, model_options, and lora_cache', 'get the model size in bytes for a given model_type like flux or lumina2', 'load an SGLDModelPatcher model (no-op for SGLang Diffusion)', 'patch an SGLDModelPatcher model with device and lowvram options (no-op for SGLang Diffusion)', 'create an SGLDiffusionServerAPI client and generate an image from a text prompt with size and style options', 'edit an existing image using SGLDiffusionServerAPI with an input image and optional mask path', 'generate a video from a text prompt using SGLDiffusionServerAPI with configurable size and duration', 'get model information from an SGLDiffusionServerAPI including task type and GPU count', 'set or unset a LoRA adapter on an SGLDiffusionServerAPI with target transformer selection']
```

Usage

```
{'create_image_generation': 'create an SGLDiffusionServerAPI client and generate an image from a text prompt with size and style options', 'edit_image_with_mask': 'edit an existing image using SGLDiffusionServerAPI with an input image and optional mask path', 'generate_video_from_prompt': 'generate a video from a text prompt using SGLDiffusionServerAPI with configurable size and duration', 'get_server_model_info': 'get model information from an SGLDiffusionServerAPI including task type and GPU count', 'set_and_unset_lora': 'set or unset a LoRA adapter on an SGLDiffusionServerAPI with target transformer selection'}
```

