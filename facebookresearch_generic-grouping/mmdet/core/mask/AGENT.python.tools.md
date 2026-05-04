# Agent Python Tools

- repo: facebookresearch/generic-grouping
- repo_uri: https://github.com/facebookresearch/generic-grouping

## File: facebookresearch_generic-grouping/mmdet/core/mask/mask_target.py

Prompts

```
['compute mask targets for positive proposals across multiple images using ground truth masks and config', 'compute mask targets for positive proposals in a single image by cropping and resizing ground truth masks', 'crop and resize ground truth instance masks to a specified size for positive proposals using crop_and_resize', 'clip proposal bounding box coordinates to stay within image width and height boundaries', 'create an empty zero tensor for mask targets when no positive proposals exist in the image', 'create BitmapMasks instance from a numpy ndarray of shape N x H x W with height and width', 'create PolygonMasks instance from a nested list of polygon coordinate arrays with height and width', 'crop and resize BitmapMasks by given bounding boxes using roi_align to a target output shape', 'convert polygon masks to bitmap representation using pycocotools maskUtils frPyObjects and decode', 'rescale BitmapMasks to a target scale using nearest or bilinear interpolation while keeping aspect ratio', 'split combined 1-D polygon tensors into per-image mask lists using poly lengths and polys per mask', 'encode bitmap mask results to RLE code for COCO format using pycocotools mask utility', 'encode bitmap mask results with mask scoring RCNN tuple containing segmentation results and classification scores', 'review the split_combined_polys function to understand how it uses mmcv slice_list to split polygon tensors', 'review the encode_mask_results function to understand RLE encoding of bitmap masks for COCO output']
```

Usage

```
{'compute_mask_target_multi_image': 'compute mask targets for positive proposals across multiple images using ground truth masks and config', 'compute_mask_target_single_image': 'compute mask targets for positive proposals in a single image by cropping and resizing ground truth masks', 'crop_and_resize_gt_masks': 'crop and resize ground truth instance masks to a specified size for positive proposals using crop_and_resize', 'clip_proposal_coordinates': 'clip proposal bounding box coordinates to stay within image width and height boundaries', 'create_empty_mask_targets': 'create an empty zero tensor for mask targets when no positive proposals exist in the image'}
```

## File: facebookresearch_generic-grouping/mmdet/core/mask/structures.py

Prompts

```
['compute mask targets for positive proposals across multiple images using ground truth masks and config', 'compute mask targets for positive proposals in a single image by cropping and resizing ground truth masks', 'crop and resize ground truth instance masks to a specified size for positive proposals using crop_and_resize', 'clip proposal bounding box coordinates to stay within image width and height boundaries', 'create an empty zero tensor for mask targets when no positive proposals exist in the image', 'create BitmapMasks instance from a numpy ndarray of shape N x H x W with height and width', 'create PolygonMasks instance from a nested list of polygon coordinate arrays with height and width', 'crop and resize BitmapMasks by given bounding boxes using roi_align to a target output shape', 'convert polygon masks to bitmap representation using pycocotools maskUtils frPyObjects and decode', 'rescale BitmapMasks to a target scale using nearest or bilinear interpolation while keeping aspect ratio', 'split combined 1-D polygon tensors into per-image mask lists using poly lengths and polys per mask', 'encode bitmap mask results to RLE code for COCO format using pycocotools mask utility', 'encode bitmap mask results with mask scoring RCNN tuple containing segmentation results and classification scores', 'review the split_combined_polys function to understand how it uses mmcv slice_list to split polygon tensors', 'review the encode_mask_results function to understand RLE encoding of bitmap masks for COCO output']
```

Usage

```
{'create_bitmapmasks_from_ndarray': 'create BitmapMasks instance from a numpy ndarray of shape N x H x W with height and width', 'create_polygonmasks_from_list': 'create PolygonMasks instance from a nested list of polygon coordinate arrays with height and width', 'crop_and_resize_bitmapmasks': 'crop and resize BitmapMasks by given bounding boxes using roi_align to a target output shape', 'convert_polygon_to_bitmap': 'convert polygon masks to bitmap representation using pycocotools maskUtils frPyObjects and decode', 'rescale_bitmapmasks_with_interpolation': 'rescale BitmapMasks to a target scale using nearest or bilinear interpolation while keeping aspect ratio'}
```

## File: facebookresearch_generic-grouping/mmdet/core/mask/utils.py

Prompts

```
['compute mask targets for positive proposals across multiple images using ground truth masks and config', 'compute mask targets for positive proposals in a single image by cropping and resizing ground truth masks', 'crop and resize ground truth instance masks to a specified size for positive proposals using crop_and_resize', 'clip proposal bounding box coordinates to stay within image width and height boundaries', 'create an empty zero tensor for mask targets when no positive proposals exist in the image', 'create BitmapMasks instance from a numpy ndarray of shape N x H x W with height and width', 'create PolygonMasks instance from a nested list of polygon coordinate arrays with height and width', 'crop and resize BitmapMasks by given bounding boxes using roi_align to a target output shape', 'convert polygon masks to bitmap representation using pycocotools maskUtils frPyObjects and decode', 'rescale BitmapMasks to a target scale using nearest or bilinear interpolation while keeping aspect ratio', 'split combined 1-D polygon tensors into per-image mask lists using poly lengths and polys per mask', 'encode bitmap mask results to RLE code for COCO format using pycocotools mask utility', 'encode bitmap mask results with mask scoring RCNN tuple containing segmentation results and classification scores', 'review the split_combined_polys function to understand how it uses mmcv slice_list to split polygon tensors', 'review the encode_mask_results function to understand RLE encoding of bitmap masks for COCO output']
```

Usage

```
{'split_combined_polys_into_masks': 'split combined 1-D polygon tensors into per-image mask lists using poly lengths and polys per mask', 'encode_mask_results_to_rle': 'encode bitmap mask results to RLE code for COCO format using pycocotools mask utility', 'encode_mask_results_with_scoring': 'encode bitmap mask results with mask scoring RCNN tuple containing segmentation results and classification scores', 'review_split_combined_polys': 'review the split_combined_polys function to understand how it uses mmcv slice_list to split polygon tensors', 'review_encode_mask_results': 'review the encode_mask_results function to understand RLE encoding of bitmap masks for COCO output'}
```

