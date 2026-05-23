# Agent Python Tools

- repo: facebookresearch/stablesignature
- repo_uri: https://github.com/facebookresearch/stable_signature

## File: facebookresearch_stablesignature/src/ldm/modules/midas/api.py

Prompts

```
['load a MiDaS preprocessing transform pipeline for a given model type like dpt_large or midas_v21', 'load a MiDaS depth estimation model and its transform by model type such as dpt_hybrid', 'create a MiDaSInference module wrapping a loaded MiDaS model for depth estimation inference', 'run a forward pass through MiDaSInference to predict depth maps from preprocessed image tensors', 'disable model train mode switching by overwriting the train method to always return self', 'read a PFM file and return the image data array and scale factor', 'write a float32 numpy array to a PFM file with a given scale', 'read an image file and return an RGB numpy array normalized to 0-1', 'resize an image to network-compatible dimensions aligned to 32 pixel multiples', 'write a depth map to both PFM and PNG files with configurable bit depth']
```

Usage

```
{'load_midas_transform': 'load a MiDaS preprocessing transform pipeline for a given model type like dpt_large or midas_v21', 'load_model': 'load a MiDaS depth estimation model and its transform by model type such as dpt_hybrid', 'MiDaSInference_init': 'create a MiDaSInference module wrapping a loaded MiDaS model for depth estimation inference', 'MiDaSInference_forward': 'run a forward pass through MiDaSInference to predict depth maps from preprocessed image tensors', 'disabled_train': 'disable model train mode switching by overwriting the train method to always return self'}
```

## File: facebookresearch_stablesignature/src/ldm/modules/midas/utils.py

Prompts

```
['load a MiDaS preprocessing transform pipeline for a given model type like dpt_large or midas_v21', 'load a MiDaS depth estimation model and its transform by model type such as dpt_hybrid', 'create a MiDaSInference module wrapping a loaded MiDaS model for depth estimation inference', 'run a forward pass through MiDaSInference to predict depth maps from preprocessed image tensors', 'disable model train mode switching by overwriting the train method to always return self', 'read a PFM file and return the image data array and scale factor', 'write a float32 numpy array to a PFM file with a given scale', 'read an image file and return an RGB numpy array normalized to 0-1', 'resize an image to network-compatible dimensions aligned to 32 pixel multiples', 'write a depth map to both PFM and PNG files with configurable bit depth']
```

Usage

```
{'read_pfm_file': 'read a PFM file and return the image data array and scale factor', 'write_pfm_file': 'write a float32 numpy array to a PFM file with a given scale', 'read_image_rgb': 'read an image file and return an RGB numpy array normalized to 0-1', 'resize_image_for_network': 'resize an image to network-compatible dimensions aligned to 32 pixel multiples', 'write_depth_map': 'write a depth map to both PFM and PNG files with configurable bit depth'}
```

