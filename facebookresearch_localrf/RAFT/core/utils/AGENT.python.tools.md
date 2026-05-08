# Agent Python Tools

- repo: facebookresearch/localrf
- repo_uri: https://github.com/facebookresearch/localrf

## File: facebookresearch_localrf/RAFT/core/utils/augmentor.py

Prompts

```
['create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'run the FlowAugmentor call method on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'create a SparseFlowAugmentor instance with crop_size and scale params to augment sparse optical flow data', 'run the SparseFlowAugmentor call method on img1, img2, flow, and valid arrays to apply augmentations with validity masks', 'review the SparseFlowAugmentor resize_sparse_flow_map method that resizes sparse flow coordinates and values by fx and fy scale factors', 'build a color wheel for optical flow visualization using the make_colorwheel function', 'convert horizontal and vertical flow components u and v into a color-coded flow image', 'convert a flow UV numpy array of shape H,W,2 into a color visualization image', 'review the flow_uv_to_colors function to understand how it applies the color wheel to flow components', 'summarize the flow_to_image function which normalizes flow values and converts them to a color image', 'read a Middlebury format .flo optical flow file and return a numpy array', 'write optical flow data to a Middlebury format .flo file', 'read a KITTI format optical flow image and return flow and validity arrays', 'write optical flow data to a KITTI format PNG image file', 'read image or flow files by extension including .png, .flo, .pfm, and .bin', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'run forward_interpolate on a flow tensor to warp and interpolate optical flow using nearest neighbor', 'build a bilinear sampler that wraps grid_sample to sample an image at pixel coordinates with optional mask', 'create a coordinate grid tensor for a given batch size, height, width, and device', 'run upflow8 to upsample a flow field by 8x and scale the flow values accordingly']
```

Usage

```
{'create_flow_augmentor': 'create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'run_flow_augmentor_call': 'run the FlowAugmentor call method on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'create_sparse_flow_augmentor': 'create a SparseFlowAugmentor instance with crop_size and scale params to augment sparse optical flow data', 'run_sparse_flow_augmentor_call': 'run the SparseFlowAugmentor call method on img1, img2, flow, and valid arrays to apply augmentations with validity masks', 'review_resize_sparse_flow_map': 'review the SparseFlowAugmentor resize_sparse_flow_map method that resizes sparse flow coordinates and values by fx and fy scale factors'}
```

## File: facebookresearch_localrf/RAFT/core/utils/flow_viz.py

Prompts

```
['create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'run the FlowAugmentor call method on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'create a SparseFlowAugmentor instance with crop_size and scale params to augment sparse optical flow data', 'run the SparseFlowAugmentor call method on img1, img2, flow, and valid arrays to apply augmentations with validity masks', 'review the SparseFlowAugmentor resize_sparse_flow_map method that resizes sparse flow coordinates and values by fx and fy scale factors', 'build a color wheel for optical flow visualization using the make_colorwheel function', 'convert horizontal and vertical flow components u and v into a color-coded flow image', 'convert a flow UV numpy array of shape H,W,2 into a color visualization image', 'review the flow_uv_to_colors function to understand how it applies the color wheel to flow components', 'summarize the flow_to_image function which normalizes flow values and converts them to a color image', 'read a Middlebury format .flo optical flow file and return a numpy array', 'write optical flow data to a Middlebury format .flo file', 'read a KITTI format optical flow image and return flow and validity arrays', 'write optical flow data to a KITTI format PNG image file', 'read image or flow files by extension including .png, .flo, .pfm, and .bin', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'run forward_interpolate on a flow tensor to warp and interpolate optical flow using nearest neighbor', 'build a bilinear sampler that wraps grid_sample to sample an image at pixel coordinates with optional mask', 'create a coordinate grid tensor for a given batch size, height, width, and device', 'run upflow8 to upsample a flow field by 8x and scale the flow values accordingly']
```

Usage

```
{'build_colorwheel': 'build a color wheel for optical flow visualization using the make_colorwheel function', 'convert_flow_uv_to_colors': 'convert horizontal and vertical flow components u and v into a color-coded flow image', 'convert_flow_to_image': 'convert a flow UV numpy array of shape H,W,2 into a color visualization image', 'review_flow_uv_to_colors': 'review the flow_uv_to_colors function to understand how it applies the color wheel to flow components', 'summarize_flow_to_image': 'summarize the flow_to_image function which normalizes flow values and converts them to a color image'}
```

## File: facebookresearch_localrf/RAFT/core/utils/frame_utils.py

Prompts

```
['create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'run the FlowAugmentor call method on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'create a SparseFlowAugmentor instance with crop_size and scale params to augment sparse optical flow data', 'run the SparseFlowAugmentor call method on img1, img2, flow, and valid arrays to apply augmentations with validity masks', 'review the SparseFlowAugmentor resize_sparse_flow_map method that resizes sparse flow coordinates and values by fx and fy scale factors', 'build a color wheel for optical flow visualization using the make_colorwheel function', 'convert horizontal and vertical flow components u and v into a color-coded flow image', 'convert a flow UV numpy array of shape H,W,2 into a color visualization image', 'review the flow_uv_to_colors function to understand how it applies the color wheel to flow components', 'summarize the flow_to_image function which normalizes flow values and converts them to a color image', 'read a Middlebury format .flo optical flow file and return a numpy array', 'write optical flow data to a Middlebury format .flo file', 'read a KITTI format optical flow image and return flow and validity arrays', 'write optical flow data to a KITTI format PNG image file', 'read image or flow files by extension including .png, .flo, .pfm, and .bin', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'run forward_interpolate on a flow tensor to warp and interpolate optical flow using nearest neighbor', 'build a bilinear sampler that wraps grid_sample to sample an image at pixel coordinates with optional mask', 'create a coordinate grid tensor for a given batch size, height, width, and device', 'run upflow8 to upsample a flow field by 8x and scale the flow values accordingly']
```

Usage

```
{'read_flow_middlebury': 'read a Middlebury format .flo optical flow file and return a numpy array', 'write_flow_middlebury': 'write optical flow data to a Middlebury format .flo file', 'read_flow_kitti': 'read a KITTI format optical flow image and return flow and validity arrays', 'write_flow_kitti': 'write optical flow data to a KITTI format PNG image file', 'read_gen_generic': 'read image or flow files by extension including .png, .flo, .pfm, and .bin'}
```

## File: facebookresearch_localrf/RAFT/core/utils/utils.py

Prompts

```
['create a FlowAugmentor instance with crop_size and scale params to augment optical flow training data', 'run the FlowAugmentor call method on img1, img2, and flow arrays to apply color, eraser, and spatial augmentations', 'create a SparseFlowAugmentor instance with crop_size and scale params to augment sparse optical flow data', 'run the SparseFlowAugmentor call method on img1, img2, flow, and valid arrays to apply augmentations with validity masks', 'review the SparseFlowAugmentor resize_sparse_flow_map method that resizes sparse flow coordinates and values by fx and fy scale factors', 'build a color wheel for optical flow visualization using the make_colorwheel function', 'convert horizontal and vertical flow components u and v into a color-coded flow image', 'convert a flow UV numpy array of shape H,W,2 into a color visualization image', 'review the flow_uv_to_colors function to understand how it applies the color wheel to flow components', 'summarize the flow_to_image function which normalizes flow values and converts them to a color image', 'read a Middlebury format .flo optical flow file and return a numpy array', 'write optical flow data to a Middlebury format .flo file', 'read a KITTI format optical flow image and return flow and validity arrays', 'write optical flow data to a KITTI format PNG image file', 'read image or flow files by extension including .png, .flo, .pfm, and .bin', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'run forward_interpolate on a flow tensor to warp and interpolate optical flow using nearest neighbor', 'build a bilinear sampler that wraps grid_sample to sample an image at pixel coordinates with optional mask', 'create a coordinate grid tensor for a given batch size, height, width, and device', 'run upflow8 to upsample a flow field by 8x and scale the flow values accordingly']
```

Usage

```
{'create_InputPadder_pad_unpad': 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'run_forward_interpolate_flow': 'run forward_interpolate on a flow tensor to warp and interpolate optical flow using nearest neighbor', 'build_bilinear_sampler_grid_sample': 'build a bilinear sampler that wraps grid_sample to sample an image at pixel coordinates with optional mask', 'create_coords_grid_batch': 'create a coordinate grid tensor for a given batch size, height, width, and device', 'run_upflow8_upsample_flow': 'run upflow8 to upsample a flow field by 8x and scale the flow values accordingly'}
```

