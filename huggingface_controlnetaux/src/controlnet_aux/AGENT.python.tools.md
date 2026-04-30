# Agent Python Tools

- repo: huggingface/controlnetaux
- repo_uri: https://github.com/huggingface/controlnet_aux

## File: huggingface_controlnetaux/src/controlnet_aux/processor.py

Prompts

```
['create a Processor instance with canny edge detection for an input image', 'create a Processor instance with openpose full body, hand, and face detection', 'create a Processor instance with depth estimation using midas, zoe, or leres models', 'process a PIL Image or bytes input through a loaded Processor and return the result', 'load a checkpoint-based processor from lllyasviel/Annotators or instantiate a non-checkpoint processor', 'convert a grayscale or RGBA numpy array image to a 3-channel HWC format', 'generate a normalized noise disk array with given height, width, channels, and frequency', 'apply non-maximum suppression with Gaussian blur and thresholding to a numpy array image', 'resize an input image to a target resolution while keeping aspect ratio and rounding to 64', 'clear the PyTorch CUDA cache and collect IPC resources when GPU is available']
```

Usage

```
{'create_processor_canny': 'create a Processor instance with canny edge detection for an input image', 'create_processor_openpose': 'create a Processor instance with openpose full body, hand, and face detection', 'create_processor_depth': 'create a Processor instance with depth estimation using midas, zoe, or leres models', 'process_image_with_processor': 'process a PIL Image or bytes input through a loaded Processor and return the result', 'load_processor_from_checkpoint': 'load a checkpoint-based processor from lllyasviel/Annotators or instantiate a non-checkpoint processor'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/util.py

Prompts

```
['create a Processor instance with canny edge detection for an input image', 'create a Processor instance with openpose full body, hand, and face detection', 'create a Processor instance with depth estimation using midas, zoe, or leres models', 'process a PIL Image or bytes input through a loaded Processor and return the result', 'load a checkpoint-based processor from lllyasviel/Annotators or instantiate a non-checkpoint processor', 'convert a grayscale or RGBA numpy array image to a 3-channel HWC format', 'generate a normalized noise disk array with given height, width, channels, and frequency', 'apply non-maximum suppression with Gaussian blur and thresholding to a numpy array image', 'resize an input image to a target resolution while keeping aspect ratio and rounding to 64', 'clear the PyTorch CUDA cache and collect IPC resources when GPU is available']
```

Usage

```
{'convert_image_to_hwc3': 'convert a grayscale or RGBA numpy array image to a 3-channel HWC format', 'generate_noise_disk': 'generate a normalized noise disk array with given height, width, channels, and frequency', 'apply_nms_to_image': 'apply non-maximum suppression with Gaussian blur and thresholding to a numpy array image', 'resize_image_to_resolution': 'resize an input image to a target resolution while keeping aspect ratio and rounding to 64', 'clear_torch_gpu_cache': 'clear the PyTorch CUDA cache and collect IPC resources when GPU is available'}
```

