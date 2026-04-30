# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/postprocess/realesrgan_upscaler.py

Prompts

```
['create an ImageUpscaler instance to lazily load Real-ESRGAN weights and upscale image frames', 'upscale a list of HWC uint8 numpy frames using Real-ESRGAN with configurable scale and precision', 'build a Real-ESRGAN network from a checkpoint by auto-detecting SRVGGNetCompact or RRDBNet architecture', 'resolve a model path from a local file or download Real-ESRGAN weights from HuggingFace', 'create an UpscalerModel wrapping a Real-ESRGAN network for single-frame upscaling inference', 'interpolate video frames using RIFE to double the frame rate with exp=1', 'interpolate a list of numpy frames using RIFE with custom interpolation exponent and scale', 'lazy-load and cache RIFE model weights from a local path or HuggingFace repo', 'generate a single intermediate frame between two image tensors using RIFE', 'load RIFE model weights from a directory containing flownet.pkl']
```

Usage

```
{'create_imageupscaler': 'create an ImageUpscaler instance to lazily load Real-ESRGAN weights and upscale image frames', 'upscale_frames': 'upscale a list of HWC uint8 numpy frames using Real-ESRGAN with configurable scale and precision', 'build_net_from_state_dict': 'build a Real-ESRGAN network from a checkpoint by auto-detecting SRVGGNetCompact or RRDBNet architecture', 'resolve_model_path': 'resolve a model path from a local file or download Real-ESRGAN weights from HuggingFace', 'create_upscaler_model': 'create an UpscalerModel wrapping a Real-ESRGAN network for single-frame upscaling inference'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/postprocess/rife_interpolator.py

Prompts

```
['create an ImageUpscaler instance to lazily load Real-ESRGAN weights and upscale image frames', 'upscale a list of HWC uint8 numpy frames using Real-ESRGAN with configurable scale and precision', 'build a Real-ESRGAN network from a checkpoint by auto-detecting SRVGGNetCompact or RRDBNet architecture', 'resolve a model path from a local file or download Real-ESRGAN weights from HuggingFace', 'create an UpscalerModel wrapping a Real-ESRGAN network for single-frame upscaling inference', 'interpolate video frames using RIFE to double the frame rate with exp=1', 'interpolate a list of numpy frames using RIFE with custom interpolation exponent and scale', 'lazy-load and cache RIFE model weights from a local path or HuggingFace repo', 'generate a single intermediate frame between two image tensors using RIFE', 'load RIFE model weights from a directory containing flownet.pkl']
```

Usage

```
{'interpolate_video_frames': 'interpolate video frames using RIFE to double the frame rate with exp=1', 'FrameInterpolator_interpolate': 'interpolate a list of numpy frames using RIFE with custom interpolation exponent and scale', 'FrameInterpolator__ensure_model_loaded': 'lazy-load and cache RIFE model weights from a local path or HuggingFace repo', 'Model_inference': 'generate a single intermediate frame between two image tensors using RIFE', 'Model_load_model': 'load RIFE model weights from a directory containing flownet.pkl'}
```

