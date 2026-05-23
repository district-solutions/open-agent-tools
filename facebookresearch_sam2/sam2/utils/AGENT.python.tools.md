# Agent Python Tools

- repo: facebookresearch/sam2
- repo_uri: https://github.com/facebookresearch/sam2

## File: facebookresearch_sam2/sam2/utils/amg.py

Prompts

```
['create a MaskData object to store masks and related data in batched format with filtering and concatenation support', 'generate a list of crop boxes of different sizes for an image with configurable layers and overlap ratio', 'encode a batch of binary mask tensors to uncompressed RLE format expected by pycoco tools', 'calculate the stability score for a batch of masks by computing IoU between high and low thresholded masks', 'compute bounding boxes in XYXY format around a batch of binary masks returning zero boxes for empty masks', 'build a python module to compute bounding box coordinates from binary mask tensors', 'create a function to find connected components and their areas in binary masks', 'test the fill_holes_in_mask_scores function to fill small holes in mask score tensors', 'refactor the concat_points function to accumulate new point coordinates and labels into existing point inputs', 'review the load_video_frames function to load and normalize video frames from MP4 or JPEG folders', 'build a SAM2Transforms instance with resolution, mask threshold, and optional hole and sprinkle area parameters', 'create a tensor from an image by calling SAM2Transforms to resize and normalize it', 'test the forward_batch method to transform a list of images into a stacked batch tensor', 'refactor the transform_coords method to convert absolute or normalized coordinates to SAM2 model input format', 'review the postprocess_masks method to fill small holes and remove sprinkles from output segmentation masks']
```

Usage

```
{'create_MaskData_store_masks': 'create a MaskData object to store masks and related data in batched format with filtering and concatenation support', 'generate_crop_boxes_for_image': 'generate a list of crop boxes of different sizes for an image with configurable layers and overlap ratio', 'encode_masks_to_rle': 'encode a batch of binary mask tensors to uncompressed RLE format expected by pycoco tools', 'calculate_stability_score_for_masks': 'calculate the stability score for a batch of masks by computing IoU between high and low thresholded masks', 'compute_bounding_boxes_from_masks': 'compute bounding boxes in XYXY format around a batch of binary masks returning zero boxes for empty masks'}
```

## File: facebookresearch_sam2/sam2/utils/misc.py

Prompts

```
['create a MaskData object to store masks and related data in batched format with filtering and concatenation support', 'generate a list of crop boxes of different sizes for an image with configurable layers and overlap ratio', 'encode a batch of binary mask tensors to uncompressed RLE format expected by pycoco tools', 'calculate the stability score for a batch of masks by computing IoU between high and low thresholded masks', 'compute bounding boxes in XYXY format around a batch of binary masks returning zero boxes for empty masks', 'build a python module to compute bounding box coordinates from binary mask tensors', 'create a function to find connected components and their areas in binary masks', 'test the fill_holes_in_mask_scores function to fill small holes in mask score tensors', 'refactor the concat_points function to accumulate new point coordinates and labels into existing point inputs', 'review the load_video_frames function to load and normalize video frames from MP4 or JPEG folders', 'build a SAM2Transforms instance with resolution, mask threshold, and optional hole and sprinkle area parameters', 'create a tensor from an image by calling SAM2Transforms to resize and normalize it', 'test the forward_batch method to transform a list of images into a stacked batch tensor', 'refactor the transform_coords method to convert absolute or normalized coordinates to SAM2 model input format', 'review the postprocess_masks method to fill small holes and remove sprinkles from output segmentation masks']
```

Usage

```
{'build_mask_to_box': 'build a python module to compute bounding box coordinates from binary mask tensors', 'create_connected_components': 'create a function to find connected components and their areas in binary masks', 'test_fill_holes_in_mask_scores': 'test the fill_holes_in_mask_scores function to fill small holes in mask score tensors', 'refactor_concat_points': 'refactor the concat_points function to accumulate new point coordinates and labels into existing point inputs', 'review_load_video_frames': 'review the load_video_frames function to load and normalize video frames from MP4 or JPEG folders'}
```

## File: facebookresearch_sam2/sam2/utils/transforms.py

Prompts

```
['create a MaskData object to store masks and related data in batched format with filtering and concatenation support', 'generate a list of crop boxes of different sizes for an image with configurable layers and overlap ratio', 'encode a batch of binary mask tensors to uncompressed RLE format expected by pycoco tools', 'calculate the stability score for a batch of masks by computing IoU between high and low thresholded masks', 'compute bounding boxes in XYXY format around a batch of binary masks returning zero boxes for empty masks', 'build a python module to compute bounding box coordinates from binary mask tensors', 'create a function to find connected components and their areas in binary masks', 'test the fill_holes_in_mask_scores function to fill small holes in mask score tensors', 'refactor the concat_points function to accumulate new point coordinates and labels into existing point inputs', 'review the load_video_frames function to load and normalize video frames from MP4 or JPEG folders', 'build a SAM2Transforms instance with resolution, mask threshold, and optional hole and sprinkle area parameters', 'create a tensor from an image by calling SAM2Transforms to resize and normalize it', 'test the forward_batch method to transform a list of images into a stacked batch tensor', 'refactor the transform_coords method to convert absolute or normalized coordinates to SAM2 model input format', 'review the postprocess_masks method to fill small holes and remove sprinkles from output segmentation masks']
```

Usage

```
{'build_SAM2Transforms': 'build a SAM2Transforms instance with resolution, mask threshold, and optional hole and sprinkle area parameters', 'create_transform_image': 'create a tensor from an image by calling SAM2Transforms to resize and normalize it', 'test_forward_batch': 'test the forward_batch method to transform a list of images into a stacked batch tensor', 'refactor_transform_coords': 'refactor the transform_coords method to convert absolute or normalized coordinates to SAM2 model input format', 'review_postprocess_masks': 'review the postprocess_masks method to fill small holes and remove sprinkles from output segmentation masks'}
```

