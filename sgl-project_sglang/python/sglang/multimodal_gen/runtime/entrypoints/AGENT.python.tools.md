# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/entrypoints/diffusion_generator.py

Prompts

```
['create a DiffGenerator instance from a pretrained diffusion model with local or remote mode', 'generate images or videos from text prompts using the DiffGenerator with sampling parameters', 'set a LoRA adapter on the DiffGenerator with nickname, path, target, and strength', 'merge LoRA weights into the base model with configurable target and strength', 'shutdown the DiffGenerator and its local scheduler server gracefully', 'create a FastAPI application with health, vertex, OpenAI-compatible, and post-training API routers for diffusion model generation', 'build a Vertex AI batch generation endpoint that processes multimodal instances and returns predictions via the scheduler', 'run a request through the async scheduler client and return serialized generation output with optional video base64 encoding', 'encode a video file to base64 string for inclusion in API responses', 'make a Python object recursively serializable by converting torch Tensors to None for JSON output', 'build a function to save video or image outputs to files with optional audio muxing and frame interpolation', 'create a function to process tensor or numpy video samples into frames and save as video or image files', 'test the function that creates a Req object from ServerArgs and SamplingParams with validation', 'refactor the function to attach per-sample audio to video outputs when available', 'summarize the function that saves outputs to files with optional audio, upscaling, and frame interpolation']
```

Usage

```
{'create_diffgenerator_from_pretrained': 'create a DiffGenerator instance from a pretrained diffusion model with local or remote mode', 'generate_image_video': 'generate images or videos from text prompts using the DiffGenerator with sampling parameters', 'set_lora_adapter': 'set a LoRA adapter on the DiffGenerator with nickname, path, target, and strength', 'merge_lora_weights': 'merge LoRA weights into the base model with configurable target and strength', 'shutdown_generator': 'shutdown the DiffGenerator and its local scheduler server gracefully'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/entrypoints/http_server.py

Prompts

```
['create a DiffGenerator instance from a pretrained diffusion model with local or remote mode', 'generate images or videos from text prompts using the DiffGenerator with sampling parameters', 'set a LoRA adapter on the DiffGenerator with nickname, path, target, and strength', 'merge LoRA weights into the base model with configurable target and strength', 'shutdown the DiffGenerator and its local scheduler server gracefully', 'create a FastAPI application with health, vertex, OpenAI-compatible, and post-training API routers for diffusion model generation', 'build a Vertex AI batch generation endpoint that processes multimodal instances and returns predictions via the scheduler', 'run a request through the async scheduler client and return serialized generation output with optional video base64 encoding', 'encode a video file to base64 string for inclusion in API responses', 'make a Python object recursively serializable by converting torch Tensors to None for JSON output', 'build a function to save video or image outputs to files with optional audio muxing and frame interpolation', 'create a function to process tensor or numpy video samples into frames and save as video or image files', 'test the function that creates a Req object from ServerArgs and SamplingParams with validation', 'refactor the function to attach per-sample audio to video outputs when available', 'summarize the function that saves outputs to files with optional audio, upscaling, and frame interpolation']
```

Usage

```
{'create_http_server_app': 'create a FastAPI application with health, vertex, OpenAI-compatible, and post-training API routers for diffusion model generation', 'build_vertex_generate_endpoint': 'build a Vertex AI batch generation endpoint that processes multimodal instances and returns predictions via the scheduler', 'run_scheduler_forward_request': 'run a request through the async scheduler client and return serialized generation output with optional video base64 encoding', 'encode_video_base64': 'encode a video file to base64 string for inclusion in API responses', 'make_serializable_json': 'make a Python object recursively serializable by converting torch Tensors to None for JSON output'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/entrypoints/utils.py

Prompts

```
['create a DiffGenerator instance from a pretrained diffusion model with local or remote mode', 'generate images or videos from text prompts using the DiffGenerator with sampling parameters', 'set a LoRA adapter on the DiffGenerator with nickname, path, target, and strength', 'merge LoRA weights into the base model with configurable target and strength', 'shutdown the DiffGenerator and its local scheduler server gracefully', 'create a FastAPI application with health, vertex, OpenAI-compatible, and post-training API routers for diffusion model generation', 'build a Vertex AI batch generation endpoint that processes multimodal instances and returns predictions via the scheduler', 'run a request through the async scheduler client and return serialized generation output with optional video base64 encoding', 'encode a video file to base64 string for inclusion in API responses', 'make a Python object recursively serializable by converting torch Tensors to None for JSON output', 'build a function to save video or image outputs to files with optional audio muxing and frame interpolation', 'create a function to process tensor or numpy video samples into frames and save as video or image files', 'test the function that creates a Req object from ServerArgs and SamplingParams with validation', 'refactor the function to attach per-sample audio to video outputs when available', 'summarize the function that saves outputs to files with optional audio, upscaling, and frame interpolation']
```

Usage

```
{'build_save_outputs': 'build a function to save video or image outputs to files with optional audio muxing and frame interpolation', 'create_post_process_sample': 'create a function to process tensor or numpy video samples into frames and save as video or image files', 'test_prepare_request': 'test the function that creates a Req object from ServerArgs and SamplingParams with validation', 'refactor_attach_audio_to_video_sample': 'refactor the function to attach per-sample audio to video outputs when available', 'summarize_save_outputs': 'summarize the function that saves outputs to files with optional audio, upscaling, and frame interpolation'}
```

