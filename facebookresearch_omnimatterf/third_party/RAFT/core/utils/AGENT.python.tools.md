# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/RAFT/core/utils/augmentor.py

Prompts

```
['build a FlowAugmentor instance to apply color, eraser, and spatial augmentations on image pairs with flow', 'create a SparseFlowAugmentor instance to augment image pairs with sparse flow and validity masks', 'test the FlowAugmentor __call__ method by passing two images and a flow field for augmentation', 'refactor the SparseFlowAugmentor resize_sparse_flow_map method to scale sparse flow coordinates and validity masks', 'review the FlowAugmentor spatial_transform method for random scaling, stretching, flipping, and cropping logic', 'generate a color wheel numpy array for optical flow visualization using make_colorwheel', 'convert horizontal and vertical flow components u and v into a colorized flow image', 'convert a flow UV numpy array of shape H,W,2 into a colorized visualization image', 'convert a flow UV array to an image while clipping flow values to a maximum threshold', 'convert a flow UV array to a BGR colorized image for OpenCV compatibility', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'write optical flow data to a .flo file in Middlebury format with u and v channels', 'read a KITTI format optical flow PNG file and return the flow array and validity mask', 'write optical flow data to a KITTI format PNG file with validity mask', 'read image or flow files by extension including .png .flo .pfm .bin and .raw formats', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'build a forward interpolation of an optical flow field using nearest-neighbor griddata and return a tensor', 'create a bilinear sampler that wraps grid_sample to sample an image at pixel coordinates with optional mask', 'build a coordinate grid tensor for a given batch size, height, width, and device using meshgrid', 'create an upsampled optical flow tensor by 8x using bilinear interpolation and scale the flow values by 8']
```

Usage

```
{'build_FlowAugmentor': 'build a FlowAugmentor instance to apply color, eraser, and spatial augmentations on image pairs with flow', 'create_SparseFlowAugmentor': 'create a SparseFlowAugmentor instance to augment image pairs with sparse flow and validity masks', 'test_FlowAugmentor_call': 'test the FlowAugmentor __call__ method by passing two images and a flow field for augmentation', 'refactor_resize_sparse_flow_map': 'refactor the SparseFlowAugmentor resize_sparse_flow_map method to scale sparse flow coordinates and validity masks', 'review_spatial_transform': 'review the FlowAugmentor spatial_transform method for random scaling, stretching, flipping, and cropping logic'}
```

## File: facebookresearch_omnimatterf/third_party/RAFT/core/utils/flow_viz.py

Prompts

```
['build a FlowAugmentor instance to apply color, eraser, and spatial augmentations on image pairs with flow', 'create a SparseFlowAugmentor instance to augment image pairs with sparse flow and validity masks', 'test the FlowAugmentor __call__ method by passing two images and a flow field for augmentation', 'refactor the SparseFlowAugmentor resize_sparse_flow_map method to scale sparse flow coordinates and validity masks', 'review the FlowAugmentor spatial_transform method for random scaling, stretching, flipping, and cropping logic', 'generate a color wheel numpy array for optical flow visualization using make_colorwheel', 'convert horizontal and vertical flow components u and v into a colorized flow image', 'convert a flow UV numpy array of shape H,W,2 into a colorized visualization image', 'convert a flow UV array to an image while clipping flow values to a maximum threshold', 'convert a flow UV array to a BGR colorized image for OpenCV compatibility', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'write optical flow data to a .flo file in Middlebury format with u and v channels', 'read a KITTI format optical flow PNG file and return the flow array and validity mask', 'write optical flow data to a KITTI format PNG file with validity mask', 'read image or flow files by extension including .png .flo .pfm .bin and .raw formats', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'build a forward interpolation of an optical flow field using nearest-neighbor griddata and return a tensor', 'create a bilinear sampler that wraps grid_sample to sample an image at pixel coordinates with optional mask', 'build a coordinate grid tensor for a given batch size, height, width, and device using meshgrid', 'create an upsampled optical flow tensor by 8x using bilinear interpolation and scale the flow values by 8']
```

Usage

```
{'generate_colorwheel': 'generate a color wheel numpy array for optical flow visualization using make_colorwheel', 'convert_flow_uv_to_colors': 'convert horizontal and vertical flow components u and v into a colorized flow image', 'convert_flow_to_image': 'convert a flow UV numpy array of shape H,W,2 into a colorized visualization image', 'clip_flow_values': 'convert a flow UV array to an image while clipping flow values to a maximum threshold', 'convert_flow_to_bgr': 'convert a flow UV array to a BGR colorized image for OpenCV compatibility'}
```

## File: facebookresearch_omnimatterf/third_party/RAFT/core/utils/frame_utils.py

Prompts

```
['build a FlowAugmentor instance to apply color, eraser, and spatial augmentations on image pairs with flow', 'create a SparseFlowAugmentor instance to augment image pairs with sparse flow and validity masks', 'test the FlowAugmentor __call__ method by passing two images and a flow field for augmentation', 'refactor the SparseFlowAugmentor resize_sparse_flow_map method to scale sparse flow coordinates and validity masks', 'review the FlowAugmentor spatial_transform method for random scaling, stretching, flipping, and cropping logic', 'generate a color wheel numpy array for optical flow visualization using make_colorwheel', 'convert horizontal and vertical flow components u and v into a colorized flow image', 'convert a flow UV numpy array of shape H,W,2 into a colorized visualization image', 'convert a flow UV array to an image while clipping flow values to a maximum threshold', 'convert a flow UV array to a BGR colorized image for OpenCV compatibility', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'write optical flow data to a .flo file in Middlebury format with u and v channels', 'read a KITTI format optical flow PNG file and return the flow array and validity mask', 'write optical flow data to a KITTI format PNG file with validity mask', 'read image or flow files by extension including .png .flo .pfm .bin and .raw formats', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'build a forward interpolation of an optical flow field using nearest-neighbor griddata and return a tensor', 'create a bilinear sampler that wraps grid_sample to sample an image at pixel coordinates with optional mask', 'build a coordinate grid tensor for a given batch size, height, width, and device using meshgrid', 'create an upsampled optical flow tensor by 8x using bilinear interpolation and scale the flow values by 8']
```

Usage

```
{'read_flow_middlebury': 'read a .flo optical flow file in Middlebury format and return a numpy array', 'write_flow_middlebury': 'write optical flow data to a .flo file in Middlebury format with u and v channels', 'read_flow_kitti': 'read a KITTI format optical flow PNG file and return the flow array and validity mask', 'write_flow_kitti': 'write optical flow data to a KITTI format PNG file with validity mask', 'read_gen_generic': 'read image or flow files by extension including .png .flo .pfm .bin and .raw formats'}
```

## File: facebookresearch_omnimatterf/third_party/RAFT/core/utils/utils.py

Prompts

```
['build a FlowAugmentor instance to apply color, eraser, and spatial augmentations on image pairs with flow', 'create a SparseFlowAugmentor instance to augment image pairs with sparse flow and validity masks', 'test the FlowAugmentor __call__ method by passing two images and a flow field for augmentation', 'refactor the SparseFlowAugmentor resize_sparse_flow_map method to scale sparse flow coordinates and validity masks', 'review the FlowAugmentor spatial_transform method for random scaling, stretching, flipping, and cropping logic', 'generate a color wheel numpy array for optical flow visualization using make_colorwheel', 'convert horizontal and vertical flow components u and v into a colorized flow image', 'convert a flow UV numpy array of shape H,W,2 into a colorized visualization image', 'convert a flow UV array to an image while clipping flow values to a maximum threshold', 'convert a flow UV array to a BGR colorized image for OpenCV compatibility', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'write optical flow data to a .flo file in Middlebury format with u and v channels', 'read a KITTI format optical flow PNG file and return the flow array and validity mask', 'write optical flow data to a KITTI format PNG file with validity mask', 'read image or flow files by extension including .png .flo .pfm .bin and .raw formats', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'build a forward interpolation of an optical flow field using nearest-neighbor griddata and return a tensor', 'create a bilinear sampler that wraps grid_sample to sample an image at pixel coordinates with optional mask', 'build a coordinate grid tensor for a given batch size, height, width, and device using meshgrid', 'create an upsampled optical flow tensor by 8x using bilinear interpolation and scale the flow values by 8']
```

Usage

```
{'create_InputPadder_pad_unpad': 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'build_forward_interpolate_flow': 'build a forward interpolation of an optical flow field using nearest-neighbor griddata and return a tensor', 'create_bilinear_sampler_grid_sample': 'create a bilinear sampler that wraps grid_sample to sample an image at pixel coordinates with optional mask', 'build_coords_grid_meshgrid': 'build a coordinate grid tensor for a given batch size, height, width, and device using meshgrid', 'create_upflow8_upsample_flow': 'create an upsampled optical flow tensor by 8x using bilinear interpolation and scale the flow values by 8'}
```

