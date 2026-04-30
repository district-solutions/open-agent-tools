# Agent Python Tools

- repo: facebookresearch/sam3
- repo_uri: https://github.com/facebookresearch/sam3

## File: facebookresearch_sam3/sam3/perflib/tests/tests.py

Prompts

```
['test the masks_to_boxes function that converts binary mask tensors to bounding box coordinates', 'test masks_to_boxes with float16, float32, and float64 mask tensor dtypes', 'test masks_to_boxes with a multi-frame TIFF mask image containing 7 segmentation masks', 'test masks_to_boxes returns a float tensor with shape (N, 4) bounding boxes', 'test masks_to_boxes produces expected bounding box coordinates from mask image assets']
```

Usage

```
{'test_masks_to_boxes': 'test the masks_to_boxes function that converts binary mask tensors to bounding box coordinates', 'test_masks_to_boxes_dtypes': 'test masks_to_boxes with float16, float32, and float64 mask tensor dtypes', 'test_masks_to_boxes_multiframe': 'test masks_to_boxes with a multi-frame TIFF mask image containing 7 segmentation masks', 'test_masks_to_boxes_output_dtype': 'test masks_to_boxes returns a float tensor with shape (N, 4) bounding boxes', 'test_masks_to_boxes_expected_values': 'test masks_to_boxes produces expected bounding box coordinates from mask image assets'}
```

