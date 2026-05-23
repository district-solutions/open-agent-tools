# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/RoDynRF/scripts/RAFT/utils/augmentor.py

Prompts

```
['create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'create a SparseFlowAugmentor instance with crop_size to augment sparse optical flow and validity maps', 'run FlowAugmentor on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'run SparseFlowAugmentor on img1, img2, flow, and valid arrays to augment sparse flow data', 'review SparseFlowAugmentor.resize_sparse_flow_map to understand how sparse flow maps are rescaled with fx and fy factors', 'build a python module that generates a 55x3 color wheel array for optical flow visualization', 'create a function that converts horizontal and vertical flow components into a colorized flow image', 'create a function that converts a flow UV array of shape H,W,2 into a colorized visualization image', 'refactor flow_uv_to_colors to support BGR output format via the convert_to_bgr boolean flag', 'summarize the flow_to_image function that normalizes flow values and clips them before color conversion', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'read a PFM file and return the image data as a numpy array', 'write optical flow data to a .flo file in Middlebury format', 'read a KITTI format optical flow PNG file and return flow and validity mask', 'read images or flow files by auto-detecting format from file extension', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'run forward_interpolate on a flow tensor to compute backward flow via nearest neighbor interpolation', 'build a bilinear sampler that wraps grid_sample using pixel coordinates for image warping', 'create a coordinate grid tensor for a given batch size, height, and width using meshgrid', 'run upflow8 to upsample a flow field by 8x and scale flow values accordingly']
```

Usage

```
{'create_flow_augmentor': 'create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'create_sparse_flow_augmentor': 'create a SparseFlowAugmentor instance with crop_size to augment sparse optical flow and validity maps', 'run_flow_augmentor_call': 'run FlowAugmentor on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'run_sparse_flow_augmentor_call': 'run SparseFlowAugmentor on img1, img2, flow, and valid arrays to augment sparse flow data', 'review_resize_sparse_flow_map': 'review SparseFlowAugmentor.resize_sparse_flow_map to understand how sparse flow maps are rescaled with fx and fy factors'}
```

## File: facebookresearch_omnimatterf/third_party/RoDynRF/scripts/RAFT/utils/flow_viz.py

Prompts

```
['create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'create a SparseFlowAugmentor instance with crop_size to augment sparse optical flow and validity maps', 'run FlowAugmentor on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'run SparseFlowAugmentor on img1, img2, flow, and valid arrays to augment sparse flow data', 'review SparseFlowAugmentor.resize_sparse_flow_map to understand how sparse flow maps are rescaled with fx and fy factors', 'build a python module that generates a 55x3 color wheel array for optical flow visualization', 'create a function that converts horizontal and vertical flow components into a colorized flow image', 'create a function that converts a flow UV array of shape H,W,2 into a colorized visualization image', 'refactor flow_uv_to_colors to support BGR output format via the convert_to_bgr boolean flag', 'summarize the flow_to_image function that normalizes flow values and clips them before color conversion', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'read a PFM file and return the image data as a numpy array', 'write optical flow data to a .flo file in Middlebury format', 'read a KITTI format optical flow PNG file and return flow and validity mask', 'read images or flow files by auto-detecting format from file extension', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'run forward_interpolate on a flow tensor to compute backward flow via nearest neighbor interpolation', 'build a bilinear sampler that wraps grid_sample using pixel coordinates for image warping', 'create a coordinate grid tensor for a given batch size, height, and width using meshgrid', 'run upflow8 to upsample a flow field by 8x and scale flow values accordingly']
```

Usage

```
{'build_colorwheel': 'build a python module that generates a 55x3 color wheel array for optical flow visualization', 'create_flow_uv_to_colors': 'create a function that converts horizontal and vertical flow components into a colorized flow image', 'create_flow_to_image': 'create a function that converts a flow UV array of shape H,W,2 into a colorized visualization image', 'refactor_flow_uv_to_colors': 'refactor flow_uv_to_colors to support BGR output format via the convert_to_bgr boolean flag', 'summarize_flow_to_image': 'summarize the flow_to_image function that normalizes flow values and clips them before color conversion'}
```

## File: facebookresearch_omnimatterf/third_party/RoDynRF/scripts/RAFT/utils/frame_utils.py

Prompts

```
['create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'create a SparseFlowAugmentor instance with crop_size to augment sparse optical flow and validity maps', 'run FlowAugmentor on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'run SparseFlowAugmentor on img1, img2, flow, and valid arrays to augment sparse flow data', 'review SparseFlowAugmentor.resize_sparse_flow_map to understand how sparse flow maps are rescaled with fx and fy factors', 'build a python module that generates a 55x3 color wheel array for optical flow visualization', 'create a function that converts horizontal and vertical flow components into a colorized flow image', 'create a function that converts a flow UV array of shape H,W,2 into a colorized visualization image', 'refactor flow_uv_to_colors to support BGR output format via the convert_to_bgr boolean flag', 'summarize the flow_to_image function that normalizes flow values and clips them before color conversion', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'read a PFM file and return the image data as a numpy array', 'write optical flow data to a .flo file in Middlebury format', 'read a KITTI format optical flow PNG file and return flow and validity mask', 'read images or flow files by auto-detecting format from file extension', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'run forward_interpolate on a flow tensor to compute backward flow via nearest neighbor interpolation', 'build a bilinear sampler that wraps grid_sample using pixel coordinates for image warping', 'create a coordinate grid tensor for a given batch size, height, and width using meshgrid', 'run upflow8 to upsample a flow field by 8x and scale flow values accordingly']
```

Usage

```
{'read_flow_middlebury': 'read a .flo optical flow file in Middlebury format and return a numpy array', 'read_pfm_file': 'read a PFM file and return the image data as a numpy array', 'write_flow_middlebury': 'write optical flow data to a .flo file in Middlebury format', 'read_flow_kitti': 'read a KITTI format optical flow PNG file and return flow and validity mask', 'read_generic_file': 'read images or flow files by auto-detecting format from file extension'}
```

## File: facebookresearch_omnimatterf/third_party/RoDynRF/scripts/RAFT/utils/utils.py

Prompts

```
['create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'create a SparseFlowAugmentor instance with crop_size to augment sparse optical flow and validity maps', 'run FlowAugmentor on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'run SparseFlowAugmentor on img1, img2, flow, and valid arrays to augment sparse flow data', 'review SparseFlowAugmentor.resize_sparse_flow_map to understand how sparse flow maps are rescaled with fx and fy factors', 'build a python module that generates a 55x3 color wheel array for optical flow visualization', 'create a function that converts horizontal and vertical flow components into a colorized flow image', 'create a function that converts a flow UV array of shape H,W,2 into a colorized visualization image', 'refactor flow_uv_to_colors to support BGR output format via the convert_to_bgr boolean flag', 'summarize the flow_to_image function that normalizes flow values and clips them before color conversion', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'read a PFM file and return the image data as a numpy array', 'write optical flow data to a .flo file in Middlebury format', 'read a KITTI format optical flow PNG file and return flow and validity mask', 'read images or flow files by auto-detecting format from file extension', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'run forward_interpolate on a flow tensor to compute backward flow via nearest neighbor interpolation', 'build a bilinear sampler that wraps grid_sample using pixel coordinates for image warping', 'create a coordinate grid tensor for a given batch size, height, and width using meshgrid', 'run upflow8 to upsample a flow field by 8x and scale flow values accordingly']
```

Usage

```
{'create_InputPadder_pad_unpad': 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'run_forward_interpolate_flow': 'run forward_interpolate on a flow tensor to compute backward flow via nearest neighbor interpolation', 'build_bilinear_sampler_grid_sample': 'build a bilinear sampler that wraps grid_sample using pixel coordinates for image warping', 'create_coords_grid_meshgrid': 'create a coordinate grid tensor for a given batch size, height, and width using meshgrid', 'run_upflow8_upsample_flow': 'run upflow8 to upsample a flow field by 8x and scale flow values accordingly'}
```

