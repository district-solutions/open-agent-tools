# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/apps/ComfyUI_SGLDiffusion/nodes.py

Prompts

```
['build SGLang Diffusion runtime options with model type, GPU count, and parallelism settings', 'connect to a SGLang Diffusion server and retrieve model info from the API endpoint', 'generate an image from a text prompt using the SGLang Diffusion server API', 'generate a video from a text prompt with configurable dimensions, frames, and fps via the API', 'load a UNET diffusion model with optional weight dtype and SGLang Diffusion options', 'convert a base64 encoded image string to a ComfyUI torch.Tensor in BHWC format', 'save a ComfyUI image tensor to a PNG file in the temp directory and return its path', 'check if a ComfyUI image tensor is an empty or solid color image', 'convert a video file path to a ComfyUI VideoInput object with specified dimensions', 'build a SGLDVideoInput instance from a video path, height, and width for ComfyUI VIDEO format']
```

Usage

```
{'build_SGLDOptions': 'build SGLang Diffusion runtime options with model type, GPU count, and parallelism settings', 'connect_SGLDiffusionServerModel': 'connect to a SGLang Diffusion server and retrieve model info from the API endpoint', 'generate_SGLDiffusionGenerateImage': 'generate an image from a text prompt using the SGLang Diffusion server API', 'generate_SGLDiffusionGenerateVideo': 'generate a video from a text prompt with configurable dimensions, frames, and fps via the API', 'load_SGLDUNETLoader': 'load a UNET diffusion model with optional weight dtype and SGLang Diffusion options'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/apps/ComfyUI_SGLDiffusion/utils.py

Prompts

```
['build SGLang Diffusion runtime options with model type, GPU count, and parallelism settings', 'connect to a SGLang Diffusion server and retrieve model info from the API endpoint', 'generate an image from a text prompt using the SGLang Diffusion server API', 'generate a video from a text prompt with configurable dimensions, frames, and fps via the API', 'load a UNET diffusion model with optional weight dtype and SGLang Diffusion options', 'convert a base64 encoded image string to a ComfyUI torch.Tensor in BHWC format', 'save a ComfyUI image tensor to a PNG file in the temp directory and return its path', 'check if a ComfyUI image tensor is an empty or solid color image', 'convert a video file path to a ComfyUI VideoInput object with specified dimensions', 'build a SGLDVideoInput instance from a video path, height, and width for ComfyUI VIDEO format']
```

Usage

```
{'convert_b64_to_tensor_image': 'convert a base64 encoded image string to a ComfyUI torch.Tensor in BHWC format', 'get_image_path': 'save a ComfyUI image tensor to a PNG file in the temp directory and return its path', 'is_empty_image': 'check if a ComfyUI image tensor is an empty or solid color image', 'convert_video_to_comfy_video': 'convert a video file path to a ComfyUI VideoInput object with specified dimensions', 'build_SGLDVideoInput': 'build a SGLDVideoInput instance from a video path, height, and width for ComfyUI VIDEO format'}
```

