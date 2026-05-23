# Agent Python Tools

- repo: facebookresearch/robustcvd
- repo_uri: https://github.com/facebookresearch/robust_cvd

## File: facebookresearch_robustcvd/raft/core/utils/augmentor.py

Prompts

```
['create a FlowAugmentor instance with crop size and scale params to augment optical flow training data', 'run FlowAugmentor on image pairs and flow fields to apply color, eraser, and spatial augmentations', 'create a SparseFlowAugmentor instance with crop size params to augment sparse optical flow data', 'run SparseFlowAugmentor on image pairs with sparse flow and validity masks for data augmentation', 'test the resize_sparse_flow_map method to scale sparse flow coordinates and validity masks', 'build a color wheel for optical flow visualization using the Middlebury standard', 'create a color image from horizontal and vertical flow components u and v', 'convert a 2D flow array of shape H,W,2 to a color-coded RGB image', 'compute an optical flow color map from horizontal and vertical flow maps', 'convert an optical flow map into a Middlebury color-coded image with unknown flow masking', 'read a Middlebury format .flo optical flow file and return a numpy array', 'read a PFM format file and return the image data as a numpy array', 'write optical flow data to a Middlebury format .flo file from a numpy array', 'read a KITTI format optical flow file and return flow and validity mask', 'read image or flow files by extension including png, jpg, flo, pfm, and bin formats', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'build a forward interpolation of an optical flow field using cubic griddata interpolation', 'test the bilinear_sampler function to sample image values at given pixel coordinates with optional mask', 'review the coords_grid function to generate a batch of coordinate grids for a given height and width', 'refactor the upflow8 function to upsample an optical flow tensor by 8x and scale flow values accordingly']
```

Usage

```
{'create_FlowAugmentor': 'create a FlowAugmentor instance with crop size and scale params to augment optical flow training data', 'run_FlowAugmentor_call': 'run FlowAugmentor on image pairs and flow fields to apply color, eraser, and spatial augmentations', 'create_SparseFlowAugmentor': 'create a SparseFlowAugmentor instance with crop size params to augment sparse optical flow data', 'run_SparseFlowAugmentor_call': 'run SparseFlowAugmentor on image pairs with sparse flow and validity masks for data augmentation', 'test_resize_sparse_flow_map': 'test the resize_sparse_flow_map method to scale sparse flow coordinates and validity masks'}
```

## File: facebookresearch_robustcvd/raft/core/utils/flow_viz.py

Prompts

```
['create a FlowAugmentor instance with crop size and scale params to augment optical flow training data', 'run FlowAugmentor on image pairs and flow fields to apply color, eraser, and spatial augmentations', 'create a SparseFlowAugmentor instance with crop size params to augment sparse optical flow data', 'run SparseFlowAugmentor on image pairs with sparse flow and validity masks for data augmentation', 'test the resize_sparse_flow_map method to scale sparse flow coordinates and validity masks', 'build a color wheel for optical flow visualization using the Middlebury standard', 'create a color image from horizontal and vertical flow components u and v', 'convert a 2D flow array of shape H,W,2 to a color-coded RGB image', 'compute an optical flow color map from horizontal and vertical flow maps', 'convert an optical flow map into a Middlebury color-coded image with unknown flow masking', 'read a Middlebury format .flo optical flow file and return a numpy array', 'read a PFM format file and return the image data as a numpy array', 'write optical flow data to a Middlebury format .flo file from a numpy array', 'read a KITTI format optical flow file and return flow and validity mask', 'read image or flow files by extension including png, jpg, flo, pfm, and bin formats', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'build a forward interpolation of an optical flow field using cubic griddata interpolation', 'test the bilinear_sampler function to sample image values at given pixel coordinates with optional mask', 'review the coords_grid function to generate a batch of coordinate grids for a given height and width', 'refactor the upflow8 function to upsample an optical flow tensor by 8x and scale flow values accordingly']
```

Usage

```
{'build_colorwheel': 'build a color wheel for optical flow visualization using the Middlebury standard', 'create_flow_color_image': 'create a color image from horizontal and vertical flow components u and v', 'convert_flow_to_color': 'convert a 2D flow array of shape H,W,2 to a color-coded RGB image', 'compute_optical_flow_color': 'compute an optical flow color map from horizontal and vertical flow maps', 'convert_flow_to_image': 'convert an optical flow map into a Middlebury color-coded image with unknown flow masking'}
```

## File: facebookresearch_robustcvd/raft/core/utils/frame_utils.py

Prompts

```
['create a FlowAugmentor instance with crop size and scale params to augment optical flow training data', 'run FlowAugmentor on image pairs and flow fields to apply color, eraser, and spatial augmentations', 'create a SparseFlowAugmentor instance with crop size params to augment sparse optical flow data', 'run SparseFlowAugmentor on image pairs with sparse flow and validity masks for data augmentation', 'test the resize_sparse_flow_map method to scale sparse flow coordinates and validity masks', 'build a color wheel for optical flow visualization using the Middlebury standard', 'create a color image from horizontal and vertical flow components u and v', 'convert a 2D flow array of shape H,W,2 to a color-coded RGB image', 'compute an optical flow color map from horizontal and vertical flow maps', 'convert an optical flow map into a Middlebury color-coded image with unknown flow masking', 'read a Middlebury format .flo optical flow file and return a numpy array', 'read a PFM format file and return the image data as a numpy array', 'write optical flow data to a Middlebury format .flo file from a numpy array', 'read a KITTI format optical flow file and return flow and validity mask', 'read image or flow files by extension including png, jpg, flo, pfm, and bin formats', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'build a forward interpolation of an optical flow field using cubic griddata interpolation', 'test the bilinear_sampler function to sample image values at given pixel coordinates with optional mask', 'review the coords_grid function to generate a batch of coordinate grids for a given height and width', 'refactor the upflow8 function to upsample an optical flow tensor by 8x and scale flow values accordingly']
```

Usage

```
{'read_flow_middlebury': 'read a Middlebury format .flo optical flow file and return a numpy array', 'read_pfm_file': 'read a PFM format file and return the image data as a numpy array', 'write_flow_middlebury': 'write optical flow data to a Middlebury format .flo file from a numpy array', 'read_flow_kitti': 'read a KITTI format optical flow file and return flow and validity mask', 'read_generic_file': 'read image or flow files by extension including png, jpg, flo, pfm, and bin formats'}
```

## File: facebookresearch_robustcvd/raft/core/utils/utils.py

Prompts

```
['create a FlowAugmentor instance with crop size and scale params to augment optical flow training data', 'run FlowAugmentor on image pairs and flow fields to apply color, eraser, and spatial augmentations', 'create a SparseFlowAugmentor instance with crop size params to augment sparse optical flow data', 'run SparseFlowAugmentor on image pairs with sparse flow and validity masks for data augmentation', 'test the resize_sparse_flow_map method to scale sparse flow coordinates and validity masks', 'build a color wheel for optical flow visualization using the Middlebury standard', 'create a color image from horizontal and vertical flow components u and v', 'convert a 2D flow array of shape H,W,2 to a color-coded RGB image', 'compute an optical flow color map from horizontal and vertical flow maps', 'convert an optical flow map into a Middlebury color-coded image with unknown flow masking', 'read a Middlebury format .flo optical flow file and return a numpy array', 'read a PFM format file and return the image data as a numpy array', 'write optical flow data to a Middlebury format .flo file from a numpy array', 'read a KITTI format optical flow file and return flow and validity mask', 'read image or flow files by extension including png, jpg, flo, pfm, and bin formats', 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'build a forward interpolation of an optical flow field using cubic griddata interpolation', 'test the bilinear_sampler function to sample image values at given pixel coordinates with optional mask', 'review the coords_grid function to generate a batch of coordinate grids for a given height and width', 'refactor the upflow8 function to upsample an optical flow tensor by 8x and scale flow values accordingly']
```

Usage

```
{'create_InputPadder_pad_unpad': 'create an InputPadder instance to pad and unpad image tensors so dimensions are divisible by 8', 'build_forward_interpolate_flow': 'build a forward interpolation of an optical flow field using cubic griddata interpolation', 'test_bilinear_sampler_coords': 'test the bilinear_sampler function to sample image values at given pixel coordinates with optional mask', 'review_coords_grid_batch': 'review the coords_grid function to generate a batch of coordinate grids for a given height and width', 'refactor_upflow8_interpolate': 'refactor the upflow8 function to upsample an optical flow tensor by 8x and scale flow values accordingly'}
```

