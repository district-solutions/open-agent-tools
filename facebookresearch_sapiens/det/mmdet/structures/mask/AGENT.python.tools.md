# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/mmdet/structures/mask/mask_target.py

Prompts

```
['compute mask targets for positive proposals across multiple images using ground truth masks and config', 'compute mask targets for positive proposals in a single image by cropping and resizing ground truth masks', 'test the mask_target function with positive proposals lists and ground truth masks across multiple images', 'test the mask_target_single function with positive proposals and ground truth masks for one image', 'review the mask_target and mask_target_single functions for mask cropping and resizing logic', 'create BitmapMasks from a numpy array of shape (N, H, W) with height and width', 'create PolygonMasks from a nested list of polygon coordinate arrays with height and width', 'crop and resize BitmapMasks by bounding boxes using ROI align for mask target computation', 'convert polygon masks to bitmap representation using pycocotools mask utilities', 'convert bitmap masks to polygon representation using OpenCV findContours', 'split combined 1-D polygon tensors into per-mask polygon lists using poly lengths and counts', 'encode a list of bitmap masks into RLE format using pycocotools for compact storage', 'compute tight bounding boxes from binary mask tensors of shape n by h by w', 'review the split_combined_polys function to understand how it slices concatenated polygon data per image', 'refactor encode_mask_results to move it to a more appropriate module location']
```

Usage

```
{'compute_mask_target_multi_image': 'compute mask targets for positive proposals across multiple images using ground truth masks and config', 'compute_mask_target_single_image': 'compute mask targets for positive proposals in a single image by cropping and resizing ground truth masks', 'test_mask_target': 'test the mask_target function with positive proposals lists and ground truth masks across multiple images', 'test_mask_target_single': 'test the mask_target_single function with positive proposals and ground truth masks for one image', 'review_mask_target_functions': 'review the mask_target and mask_target_single functions for mask cropping and resizing logic'}
```

## File: facebookresearch_sapiens/det/mmdet/structures/mask/structures.py

Prompts

```
['compute mask targets for positive proposals across multiple images using ground truth masks and config', 'compute mask targets for positive proposals in a single image by cropping and resizing ground truth masks', 'test the mask_target function with positive proposals lists and ground truth masks across multiple images', 'test the mask_target_single function with positive proposals and ground truth masks for one image', 'review the mask_target and mask_target_single functions for mask cropping and resizing logic', 'create BitmapMasks from a numpy array of shape (N, H, W) with height and width', 'create PolygonMasks from a nested list of polygon coordinate arrays with height and width', 'crop and resize BitmapMasks by bounding boxes using ROI align for mask target computation', 'convert polygon masks to bitmap representation using pycocotools mask utilities', 'convert bitmap masks to polygon representation using OpenCV findContours', 'split combined 1-D polygon tensors into per-mask polygon lists using poly lengths and counts', 'encode a list of bitmap masks into RLE format using pycocotools for compact storage', 'compute tight bounding boxes from binary mask tensors of shape n by h by w', 'review the split_combined_polys function to understand how it slices concatenated polygon data per image', 'refactor encode_mask_results to move it to a more appropriate module location']
```

Usage

```
{'create_BitmapMasks': 'create BitmapMasks from a numpy array of shape (N, H, W) with height and width', 'create_PolygonMasks': 'create PolygonMasks from a nested list of polygon coordinate arrays with height and width', 'crop_and_resize_BitmapMasks': 'crop and resize BitmapMasks by bounding boxes using ROI align for mask target computation', 'convert_polygon_to_bitmap': 'convert polygon masks to bitmap representation using pycocotools mask utilities', 'convert_bitmap_to_polygon': 'convert bitmap masks to polygon representation using OpenCV findContours'}
```

## File: facebookresearch_sapiens/det/mmdet/structures/mask/utils.py

Prompts

```
['compute mask targets for positive proposals across multiple images using ground truth masks and config', 'compute mask targets for positive proposals in a single image by cropping and resizing ground truth masks', 'test the mask_target function with positive proposals lists and ground truth masks across multiple images', 'test the mask_target_single function with positive proposals and ground truth masks for one image', 'review the mask_target and mask_target_single functions for mask cropping and resizing logic', 'create BitmapMasks from a numpy array of shape (N, H, W) with height and width', 'create PolygonMasks from a nested list of polygon coordinate arrays with height and width', 'crop and resize BitmapMasks by bounding boxes using ROI align for mask target computation', 'convert polygon masks to bitmap representation using pycocotools mask utilities', 'convert bitmap masks to polygon representation using OpenCV findContours', 'split combined 1-D polygon tensors into per-mask polygon lists using poly lengths and counts', 'encode a list of bitmap masks into RLE format using pycocotools for compact storage', 'compute tight bounding boxes from binary mask tensors of shape n by h by w', 'review the split_combined_polys function to understand how it slices concatenated polygon data per image', 'refactor encode_mask_results to move it to a more appropriate module location']
```

Usage

```
{'split_combined_polys': 'split combined 1-D polygon tensors into per-mask polygon lists using poly lengths and counts', 'encode_mask_results': 'encode a list of bitmap masks into RLE format using pycocotools for compact storage', 'mask2bbox': 'compute tight bounding boxes from binary mask tensors of shape n by h by w', 'review_split_combined_polys': 'review the split_combined_polys function to understand how it slices concatenated polygon data per image', 'refactor_encode_mask_results': 'refactor encode_mask_results to move it to a more appropriate module location'}
```

