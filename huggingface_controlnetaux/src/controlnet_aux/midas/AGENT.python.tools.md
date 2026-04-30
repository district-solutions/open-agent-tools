# Agent Python Tools

- repo: huggingface/controlnetaux
- repo_uri: https://github.com/huggingface/controlnet_aux

## File: huggingface_controlnetaux/src/controlnet_aux/midas/api.py

Prompts

```
['load a MiDaS image transform pipeline for a given model type like dpt_hybrid', 'load a MiDaS depth estimation model and its transform by model type', 'create a MiDaSInference module wrapping a loaded depth model for inference', 'run a forward pass on an input tensor through the MiDaS depth model', 'disable model train mode changes by overwriting the train method', 'read a PFM file and return the image data array and scale value', 'write a float32 numpy array to a PFM file with an optional scale', 'read an image file and return an RGB numpy array normalized to 0-1', 'resize an image to network-compatible dimensions aligned to 32 pixel multiples', 'write a depth map to both PFM and PNG files with configurable bit depth']
```

Usage

```
{'load_midas_transform': 'load a MiDaS image transform pipeline for a given model type like dpt_hybrid', 'load_model': 'load a MiDaS depth estimation model and its transform by model type', 'midas_inference_init': 'create a MiDaSInference module wrapping a loaded depth model for inference', 'midas_inference_forward': 'run a forward pass on an input tensor through the MiDaS depth model', 'disabled_train': 'disable model train mode changes by overwriting the train method'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/midas/utils.py

Prompts

```
['load a MiDaS image transform pipeline for a given model type like dpt_hybrid', 'load a MiDaS depth estimation model and its transform by model type', 'create a MiDaSInference module wrapping a loaded depth model for inference', 'run a forward pass on an input tensor through the MiDaS depth model', 'disable model train mode changes by overwriting the train method', 'read a PFM file and return the image data array and scale value', 'write a float32 numpy array to a PFM file with an optional scale', 'read an image file and return an RGB numpy array normalized to 0-1', 'resize an image to network-compatible dimensions aligned to 32 pixel multiples', 'write a depth map to both PFM and PNG files with configurable bit depth']
```

Usage

```
{'read_pfm_file': 'read a PFM file and return the image data array and scale value', 'write_pfm_file': 'write a float32 numpy array to a PFM file with an optional scale', 'read_image_as_rgb': 'read an image file and return an RGB numpy array normalized to 0-1', 'resize_image_for_network': 'resize an image to network-compatible dimensions aligned to 32 pixel multiples', 'write_depth_map': 'write a depth map to both PFM and PNG files with configurable bit depth'}
```

