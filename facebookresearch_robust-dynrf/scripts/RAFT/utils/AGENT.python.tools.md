# Agent Python Tools

- repo: facebookresearch/robust-dynrf
- repo_uri: https://github.com/facebookresearch/robust-dynrf

## File: facebookresearch_robust-dynrf/scripts/RAFT/utils/augmentor.py

Prompts

```
['create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'create a SparseFlowAugmentor instance with crop_size to augment sparse flow maps with validity masks', 'run FlowAugmentor on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'run SparseFlowAugmentor on img1, img2, flow, and valid arrays to augment sparse flow data with masks', 'review SparseFlowAugmentor.resize_sparse_flow_map to understand how sparse flow coordinates are rescaled and remapped', 'build a python module that generates a 55x3 color wheel array for optical flow visualization', 'create a function that converts horizontal and vertical flow components into a colored flow visualization image', 'create a function that converts a flow UV array of shape H,W,2 into a color-coded visualization image', 'refactor flow_uv_to_colors to support BGR output format for OpenCV compatibility', 'review flow_to_image to understand how it normalizes flow magnitudes before color mapping', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'read a PFM format file and return the image data as a numpy array', 'write optical flow data to a .flo file in Middlebury format', 'read a KITTI format optical flow file and return flow and validity mask', 'write optical flow data to a KITTI format .png file', 'create an InputPadder instance to pad and unpad images so dimensions are divisible by 8', 'build a forward interpolation of optical flow using nearest neighbor griddata on valid coordinates', 'test the bilinear_sampler wrapper for grid_sample using pixel coordinates with optional mask output', 'refactor the coords_grid function to generate a batched coordinate meshgrid tensor for optical flow', 'summarize the upflow8 function that upsamples optical flow by 8x and scales values accordingly']
```

Usage

```
{'create_flow_augmentor': 'create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'create_sparse_flow_augmentor': 'create a SparseFlowAugmentor instance with crop_size to augment sparse flow maps with validity masks', 'run_flow_augmentor_call': 'run FlowAugmentor on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'run_sparse_flow_augmentor_call': 'run SparseFlowAugmentor on img1, img2, flow, and valid arrays to augment sparse flow data with masks', 'review_resize_sparse_flow_map': 'review SparseFlowAugmentor.resize_sparse_flow_map to understand how sparse flow coordinates are rescaled and remapped'}
```

## File: facebookresearch_robust-dynrf/scripts/RAFT/utils/flow_viz.py

Prompts

```
['create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'create a SparseFlowAugmentor instance with crop_size to augment sparse flow maps with validity masks', 'run FlowAugmentor on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'run SparseFlowAugmentor on img1, img2, flow, and valid arrays to augment sparse flow data with masks', 'review SparseFlowAugmentor.resize_sparse_flow_map to understand how sparse flow coordinates are rescaled and remapped', 'build a python module that generates a 55x3 color wheel array for optical flow visualization', 'create a function that converts horizontal and vertical flow components into a colored flow visualization image', 'create a function that converts a flow UV array of shape H,W,2 into a color-coded visualization image', 'refactor flow_uv_to_colors to support BGR output format for OpenCV compatibility', 'review flow_to_image to understand how it normalizes flow magnitudes before color mapping', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'read a PFM format file and return the image data as a numpy array', 'write optical flow data to a .flo file in Middlebury format', 'read a KITTI format optical flow file and return flow and validity mask', 'write optical flow data to a KITTI format .png file', 'create an InputPadder instance to pad and unpad images so dimensions are divisible by 8', 'build a forward interpolation of optical flow using nearest neighbor griddata on valid coordinates', 'test the bilinear_sampler wrapper for grid_sample using pixel coordinates with optional mask output', 'refactor the coords_grid function to generate a batched coordinate meshgrid tensor for optical flow', 'summarize the upflow8 function that upsamples optical flow by 8x and scales values accordingly']
```

Usage

```
{'build_colorwheel': 'build a python module that generates a 55x3 color wheel array for optical flow visualization', 'create_flow_uv_to_colors': 'create a function that converts horizontal and vertical flow components into a colored flow visualization image', 'create_flow_to_image': 'create a function that converts a flow UV array of shape H,W,2 into a color-coded visualization image', 'refactor_flow_uv_to_colors': 'refactor flow_uv_to_colors to support BGR output format for OpenCV compatibility', 'review_flow_to_image': 'review flow_to_image to understand how it normalizes flow magnitudes before color mapping'}
```

## File: facebookresearch_robust-dynrf/scripts/RAFT/utils/frame_utils.py

Prompts

```
['create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'create a SparseFlowAugmentor instance with crop_size to augment sparse flow maps with validity masks', 'run FlowAugmentor on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'run SparseFlowAugmentor on img1, img2, flow, and valid arrays to augment sparse flow data with masks', 'review SparseFlowAugmentor.resize_sparse_flow_map to understand how sparse flow coordinates are rescaled and remapped', 'build a python module that generates a 55x3 color wheel array for optical flow visualization', 'create a function that converts horizontal and vertical flow components into a colored flow visualization image', 'create a function that converts a flow UV array of shape H,W,2 into a color-coded visualization image', 'refactor flow_uv_to_colors to support BGR output format for OpenCV compatibility', 'review flow_to_image to understand how it normalizes flow magnitudes before color mapping', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'read a PFM format file and return the image data as a numpy array', 'write optical flow data to a .flo file in Middlebury format', 'read a KITTI format optical flow file and return flow and validity mask', 'write optical flow data to a KITTI format .png file', 'create an InputPadder instance to pad and unpad images so dimensions are divisible by 8', 'build a forward interpolation of optical flow using nearest neighbor griddata on valid coordinates', 'test the bilinear_sampler wrapper for grid_sample using pixel coordinates with optional mask output', 'refactor the coords_grid function to generate a batched coordinate meshgrid tensor for optical flow', 'summarize the upflow8 function that upsamples optical flow by 8x and scales values accordingly']
```

Usage

```
{'read_flow_middlebury': 'read a .flo optical flow file in Middlebury format and return a numpy array', 'read_pfm_file': 'read a PFM format file and return the image data as a numpy array', 'write_flow_middlebury': 'write optical flow data to a .flo file in Middlebury format', 'read_flow_kitti': 'read a KITTI format optical flow file and return flow and validity mask', 'write_flow_kitti': 'write optical flow data to a KITTI format .png file'}
```

## File: facebookresearch_robust-dynrf/scripts/RAFT/utils/utils.py

Prompts

```
['create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'create a SparseFlowAugmentor instance with crop_size to augment sparse flow maps with validity masks', 'run FlowAugmentor on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'run SparseFlowAugmentor on img1, img2, flow, and valid arrays to augment sparse flow data with masks', 'review SparseFlowAugmentor.resize_sparse_flow_map to understand how sparse flow coordinates are rescaled and remapped', 'build a python module that generates a 55x3 color wheel array for optical flow visualization', 'create a function that converts horizontal and vertical flow components into a colored flow visualization image', 'create a function that converts a flow UV array of shape H,W,2 into a color-coded visualization image', 'refactor flow_uv_to_colors to support BGR output format for OpenCV compatibility', 'review flow_to_image to understand how it normalizes flow magnitudes before color mapping', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'read a PFM format file and return the image data as a numpy array', 'write optical flow data to a .flo file in Middlebury format', 'read a KITTI format optical flow file and return flow and validity mask', 'write optical flow data to a KITTI format .png file', 'create an InputPadder instance to pad and unpad images so dimensions are divisible by 8', 'build a forward interpolation of optical flow using nearest neighbor griddata on valid coordinates', 'test the bilinear_sampler wrapper for grid_sample using pixel coordinates with optional mask output', 'refactor the coords_grid function to generate a batched coordinate meshgrid tensor for optical flow', 'summarize the upflow8 function that upsamples optical flow by 8x and scales values accordingly']
```

Usage

```
{'create_InputPadder_pad_unpad': 'create an InputPadder instance to pad and unpad images so dimensions are divisible by 8', 'build_forward_interpolate_flow': 'build a forward interpolation of optical flow using nearest neighbor griddata on valid coordinates', 'test_bilinear_sampler_grid_sample': 'test the bilinear_sampler wrapper for grid_sample using pixel coordinates with optional mask output', 'refactor_coords_grid_meshgrid': 'refactor the coords_grid function to generate a batched coordinate meshgrid tensor for optical flow', 'summarize_upflow8_interpolate': 'summarize the upflow8 function that upsamples optical flow by 8x and scales values accordingly'}
```

