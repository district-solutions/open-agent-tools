# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/MiDaS/hubconf.py

Prompts

```
['build a monocular depth estimation model using the DPT_BEiT_L_512 backbone with pretrained weights', 'build a MiDaS DPT-Large model for monocular depth estimation with pretrained ViT-L/16 weights', 'build a MiDaS v2.1 model for monocular depth estimation with pretrained weights', 'build a lightweight MiDaS small model for depth estimation on resource-constrained devices', 'run the transforms function to get image preprocessing pipelines for various MiDaS model variants', 'run MiDaS depth estimation on all images in an input folder and save depth maps to an output folder', 'run MiDaS depth estimation in real time from a webcam and display results in a window', 'process a single image through the MiDaS model and interpolate the prediction to the target size', 'create a side by side image combining an RGB image and its normalized depth map with a colormap', 'run MiDaS depth estimation with half-float CUDA optimization for faster inference on supported models', 'read a PFM file from disk and return the numpy data array and scale factor', 'write a float32 numpy image array to a PFM file with an optional scale value', 'read an image file and return an RGB numpy array normalized to 0-1 range', 'resize an image to network-compatible dimensions and return a PyTorch tensor batch', 'write a depth map array to a PNG file with optional colormap and bit depth']
```

Usage

```
{'build_DPT_BEiT_L_512': 'build a monocular depth estimation model using the DPT_BEiT_L_512 backbone with pretrained weights', 'build_DPT_Large': 'build a MiDaS DPT-Large model for monocular depth estimation with pretrained ViT-L/16 weights', 'build_MiDaS': 'build a MiDaS v2.1 model for monocular depth estimation with pretrained weights', 'build_MiDaS_small': 'build a lightweight MiDaS small model for depth estimation on resource-constrained devices', 'run_transforms': 'run the transforms function to get image preprocessing pipelines for various MiDaS model variants'}
```

## File: facebookresearch_omnimatterf/third_party/MiDaS/run.py

Prompts

```
['build a monocular depth estimation model using the DPT_BEiT_L_512 backbone with pretrained weights', 'build a MiDaS DPT-Large model for monocular depth estimation with pretrained ViT-L/16 weights', 'build a MiDaS v2.1 model for monocular depth estimation with pretrained weights', 'build a lightweight MiDaS small model for depth estimation on resource-constrained devices', 'run the transforms function to get image preprocessing pipelines for various MiDaS model variants', 'run MiDaS depth estimation on all images in an input folder and save depth maps to an output folder', 'run MiDaS depth estimation in real time from a webcam and display results in a window', 'process a single image through the MiDaS model and interpolate the prediction to the target size', 'create a side by side image combining an RGB image and its normalized depth map with a colormap', 'run MiDaS depth estimation with half-float CUDA optimization for faster inference on supported models', 'read a PFM file from disk and return the numpy data array and scale factor', 'write a float32 numpy image array to a PFM file with an optional scale value', 'read an image file and return an RGB numpy array normalized to 0-1 range', 'resize an image to network-compatible dimensions and return a PyTorch tensor batch', 'write a depth map array to a PNG file with optional colormap and bit depth']
```

Usage

```
{'run_depth_estimation_on_images': 'run MiDaS depth estimation on all images in an input folder and save depth maps to an output folder', 'run_depth_estimation_from_camera': 'run MiDaS depth estimation in real time from a webcam and display results in a window', 'process_inference_and_interpolate': 'process a single image through the MiDaS model and interpolate the prediction to the target size', 'create_side_by_side_depth_image': 'create a side by side image combining an RGB image and its normalized depth map with a colormap', 'run_depth_estimation_with_half_float_optimization': 'run MiDaS depth estimation with half-float CUDA optimization for faster inference on supported models'}
```

## File: facebookresearch_omnimatterf/third_party/MiDaS/utils.py

Prompts

```
['build a monocular depth estimation model using the DPT_BEiT_L_512 backbone with pretrained weights', 'build a MiDaS DPT-Large model for monocular depth estimation with pretrained ViT-L/16 weights', 'build a MiDaS v2.1 model for monocular depth estimation with pretrained weights', 'build a lightweight MiDaS small model for depth estimation on resource-constrained devices', 'run the transforms function to get image preprocessing pipelines for various MiDaS model variants', 'run MiDaS depth estimation on all images in an input folder and save depth maps to an output folder', 'run MiDaS depth estimation in real time from a webcam and display results in a window', 'process a single image through the MiDaS model and interpolate the prediction to the target size', 'create a side by side image combining an RGB image and its normalized depth map with a colormap', 'run MiDaS depth estimation with half-float CUDA optimization for faster inference on supported models', 'read a PFM file from disk and return the numpy data array and scale factor', 'write a float32 numpy image array to a PFM file with an optional scale value', 'read an image file and return an RGB numpy array normalized to 0-1 range', 'resize an image to network-compatible dimensions and return a PyTorch tensor batch', 'write a depth map array to a PNG file with optional colormap and bit depth']
```

Usage

```
{'read_pfm_file': 'read a PFM file from disk and return the numpy data array and scale factor', 'write_pfm_file': 'write a float32 numpy image array to a PFM file with an optional scale value', 'read_image_rgb': 'read an image file and return an RGB numpy array normalized to 0-1 range', 'resize_image_for_network': 'resize an image to network-compatible dimensions and return a PyTorch tensor batch', 'write_depth_map': 'write a depth map array to a PNG file with optional colormap and bit depth'}
```

