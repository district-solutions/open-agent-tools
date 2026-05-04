# Agent Python Tools

- repo: facebookresearch/edgetam
- repo_uri: https://github.com/facebookresearch/edgetam

## File: facebookresearch_edgetam/sam2/utils/amg.py

Prompts

```
['create a MaskData object to store and filter batched segmentation masks and related data', 'encode a batch of binary mask tensors to uncompressed RLE format for pycoco tools', 'calculate the stability score as IoU between high and low thresholded mask logits', 'generate a list of overlapping crop boxes across multiple layers for image tiling', 'compute XYXY bounding boxes around a batch of binary segmentation masks', 'get the GPU flash attention and PyTorch math kernel settings for the current CUDA device', 'compute bounding box coordinates from a batch of binary segmentation masks', 'load and normalize video frames from an MP4 file or JPEG image folder', 'fill small holes in mask scores by connected component analysis with a max area threshold', 'concatenate new click point coordinates and labels to existing point inputs for interactive segmentation', 'create a SAM2Transforms instance with resolution, mask threshold, and hole filling parameters', 'call SAM2Transforms on an image to resize and normalize it for the SAM2 model', 'transform a batch of images into a stacked tensor using SAM2Transforms forward_batch', 'transform coordinates to SAM2 model space using transform_coords with optional normalization', 'postprocess SAM2 output masks to fill holes and remove sprinkles with postprocess_masks']
```

Usage

```
{'create_maskdata_store_masks': 'create a MaskData object to store and filter batched segmentation masks and related data', 'encode_masks_to_rle': 'encode a batch of binary mask tensors to uncompressed RLE format for pycoco tools', 'calculate_mask_stability_score': 'calculate the stability score as IoU between high and low thresholded mask logits', 'generate_crop_boxes_for_tiling': 'generate a list of overlapping crop boxes across multiple layers for image tiling', 'compute_bounding_boxes_from_masks': 'compute XYXY bounding boxes around a batch of binary segmentation masks'}
```

## File: facebookresearch_edgetam/sam2/utils/misc.py

Prompts

```
['create a MaskData object to store and filter batched segmentation masks and related data', 'encode a batch of binary mask tensors to uncompressed RLE format for pycoco tools', 'calculate the stability score as IoU between high and low thresholded mask logits', 'generate a list of overlapping crop boxes across multiple layers for image tiling', 'compute XYXY bounding boxes around a batch of binary segmentation masks', 'get the GPU flash attention and PyTorch math kernel settings for the current CUDA device', 'compute bounding box coordinates from a batch of binary segmentation masks', 'load and normalize video frames from an MP4 file or JPEG image folder', 'fill small holes in mask scores by connected component analysis with a max area threshold', 'concatenate new click point coordinates and labels to existing point inputs for interactive segmentation', 'create a SAM2Transforms instance with resolution, mask threshold, and hole filling parameters', 'call SAM2Transforms on an image to resize and normalize it for the SAM2 model', 'transform a batch of images into a stacked tensor using SAM2Transforms forward_batch', 'transform coordinates to SAM2 model space using transform_coords with optional normalization', 'postprocess SAM2 output masks to fill holes and remove sprinkles with postprocess_masks']
```

Usage

```
{'get_sdpa_settings': 'get the GPU flash attention and PyTorch math kernel settings for the current CUDA device', 'mask_to_box': 'compute bounding box coordinates from a batch of binary segmentation masks', 'load_video_frames': 'load and normalize video frames from an MP4 file or JPEG image folder', 'fill_holes_in_mask_scores': 'fill small holes in mask scores by connected component analysis with a max area threshold', 'concat_points': 'concatenate new click point coordinates and labels to existing point inputs for interactive segmentation'}
```

## File: facebookresearch_edgetam/sam2/utils/transforms.py

Prompts

```
['create a MaskData object to store and filter batched segmentation masks and related data', 'encode a batch of binary mask tensors to uncompressed RLE format for pycoco tools', 'calculate the stability score as IoU between high and low thresholded mask logits', 'generate a list of overlapping crop boxes across multiple layers for image tiling', 'compute XYXY bounding boxes around a batch of binary segmentation masks', 'get the GPU flash attention and PyTorch math kernel settings for the current CUDA device', 'compute bounding box coordinates from a batch of binary segmentation masks', 'load and normalize video frames from an MP4 file or JPEG image folder', 'fill small holes in mask scores by connected component analysis with a max area threshold', 'concatenate new click point coordinates and labels to existing point inputs for interactive segmentation', 'create a SAM2Transforms instance with resolution, mask threshold, and hole filling parameters', 'call SAM2Transforms on an image to resize and normalize it for the SAM2 model', 'transform a batch of images into a stacked tensor using SAM2Transforms forward_batch', 'transform coordinates to SAM2 model space using transform_coords with optional normalization', 'postprocess SAM2 output masks to fill holes and remove sprinkles with postprocess_masks']
```

Usage

```
{'create_SAM2Transforms': 'create a SAM2Transforms instance with resolution, mask threshold, and hole filling parameters', 'call_SAM2Transforms': 'call SAM2Transforms on an image to resize and normalize it for the SAM2 model', 'forward_batch_SAM2Transforms': 'transform a batch of images into a stacked tensor using SAM2Transforms forward_batch', 'transform_coords_SAM2Transforms': 'transform coordinates to SAM2 model space using transform_coords with optional normalization', 'postprocess_masks_SAM2Transforms': 'postprocess SAM2 output masks to fill holes and remove sprinkles with postprocess_masks'}
```

