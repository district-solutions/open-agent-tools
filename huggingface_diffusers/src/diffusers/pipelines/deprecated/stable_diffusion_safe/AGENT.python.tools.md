# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/stable_diffusion_safe/pipeline_stable_diffusion_safe.py

Prompts

```
['run StableDiffusionPipelineSafe to generate safe images from text prompts using Safe Latent Diffusion', 'configure SLD parameters like sld_guidance_scale, sld_threshold, and sld_warmup_steps for safety guidance', 'encode prompts with safety concept embeddings using the _encode_prompt method for classifier-free guidance', 'run the safety checker on generated images to detect and flag NSFW content', 'set a custom safety concept string to define what content the pipeline should avoid generating', 'build a python module that initializes SafeStableDiffusionSafetyChecker with a CLIPConfig to detect NSFW content', 'run the SafeStableDiffusionSafetyChecker forward method with clip_input and images to check for NSFW concepts', 'run the SafeStableDiffusionSafetyChecker forward_onnx method with clip_input and images tensors for ONNX-compatible NSFW detection', 'create a function that computes cosine distance between image embeddings and text embeddings using normalized vectors', 'review the SafeStableDiffusionSafetyChecker class concept_embeds and special_care_embeds parameters for NSFW filtering thresholds']
```

Usage

```
{'run_pipeline_safe': 'run StableDiffusionPipelineSafe to generate safe images from text prompts using Safe Latent Diffusion', 'configure_safety_guidance': 'configure SLD parameters like sld_guidance_scale, sld_threshold, and sld_warmup_steps for safety guidance', 'encode_prompt_safety': 'encode prompts with safety concept embeddings using the _encode_prompt method for classifier-free guidance', 'run_safety_checker': 'run the safety checker on generated images to detect and flag NSFW content', 'set_safety_concept': 'set a custom safety concept string to define what content the pipeline should avoid generating'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/stable_diffusion_safe/safety_checker.py

Prompts

```
['run StableDiffusionPipelineSafe to generate safe images from text prompts using Safe Latent Diffusion', 'configure SLD parameters like sld_guidance_scale, sld_threshold, and sld_warmup_steps for safety guidance', 'encode prompts with safety concept embeddings using the _encode_prompt method for classifier-free guidance', 'run the safety checker on generated images to detect and flag NSFW content', 'set a custom safety concept string to define what content the pipeline should avoid generating', 'build a python module that initializes SafeStableDiffusionSafetyChecker with a CLIPConfig to detect NSFW content', 'run the SafeStableDiffusionSafetyChecker forward method with clip_input and images to check for NSFW concepts', 'run the SafeStableDiffusionSafetyChecker forward_onnx method with clip_input and images tensors for ONNX-compatible NSFW detection', 'create a function that computes cosine distance between image embeddings and text embeddings using normalized vectors', 'review the SafeStableDiffusionSafetyChecker class concept_embeds and special_care_embeds parameters for NSFW filtering thresholds']
```

Usage

```
{'build_safety_checker': 'build a python module that initializes SafeStableDiffusionSafetyChecker with a CLIPConfig to detect NSFW content', 'run_forward_nsfw_check': 'run the SafeStableDiffusionSafetyChecker forward method with clip_input and images to check for NSFW concepts', 'run_forward_onnx_nsfw_check': 'run the SafeStableDiffusionSafetyChecker forward_onnx method with clip_input and images tensors for ONNX-compatible NSFW detection', 'create_cosine_distance': 'create a function that computes cosine distance between image embeddings and text embeddings using normalized vectors', 'review_safety_checker_concepts': 'review the SafeStableDiffusionSafetyChecker class concept_embeds and special_care_embeds parameters for NSFW filtering thresholds'}
```

