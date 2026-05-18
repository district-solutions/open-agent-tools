# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/core/post_processing/box3d_nms.py

Prompts

```
['run multi-class NMS on 3D bounding boxes with score thresholding and max box limiting', 'run aligned 3D NMS on axis-aligned boxes using IoU threshold and class-aware suppression', 'run circular NMS on 2D detections using bird-eye view center distance suppression', 'refactor box3d_multiclass_nms to support a custom NMS function beyond rotate and normal GPU variants', 'review aligned_3d_nms to verify class-aware IoU suppression logic and edge cases with empty inputs', 'merge augmented 3D detection bounding boxes and scores from multiple test augmentations into consolidated results', 'apply rotated or standard NMS to 3D bounding box detections per class using configurable threshold', 'reverse augmentation transforms on 3D bounding boxes using scale factor and flip metadata from img_metas', 'sort merged 3D detection results by score in descending order and limit to max_num predictions', 'convert 3D bounding boxes from xywhr to xyxyr format for NMS processing using xywhr2xyxyr utility']
```

Usage

```
{'run_box3d_multiclass_nms': 'run multi-class NMS on 3D bounding boxes with score thresholding and max box limiting', 'run_aligned_3d_nms': 'run aligned 3D NMS on axis-aligned boxes using IoU threshold and class-aware suppression', 'run_circle_nms': 'run circular NMS on 2D detections using bird-eye view center distance suppression', 'refactor_box3d_multiclass_nms': 'refactor box3d_multiclass_nms to support a custom NMS function beyond rotate and normal GPU variants', 'review_aligned_3d_nms': 'review aligned_3d_nms to verify class-aware IoU suppression logic and edge cases with empty inputs'}
```

## File: facebookresearch_nerf-det/mmdet3d/core/post_processing/merge_augs.py

Prompts

```
['run multi-class NMS on 3D bounding boxes with score thresholding and max box limiting', 'run aligned 3D NMS on axis-aligned boxes using IoU threshold and class-aware suppression', 'run circular NMS on 2D detections using bird-eye view center distance suppression', 'refactor box3d_multiclass_nms to support a custom NMS function beyond rotate and normal GPU variants', 'review aligned_3d_nms to verify class-aware IoU suppression logic and edge cases with empty inputs', 'merge augmented 3D detection bounding boxes and scores from multiple test augmentations into consolidated results', 'apply rotated or standard NMS to 3D bounding box detections per class using configurable threshold', 'reverse augmentation transforms on 3D bounding boxes using scale factor and flip metadata from img_metas', 'sort merged 3D detection results by score in descending order and limit to max_num predictions', 'convert 3D bounding boxes from xywhr to xyxyr format for NMS processing using xywhr2xyxyr utility']
```

Usage

```
{'merge_augmented_3d_bboxes': 'merge augmented 3D detection bounding boxes and scores from multiple test augmentations into consolidated results', 'apply_nms_to_3d_detections': 'apply rotated or standard NMS to 3D bounding box detections per class using configurable threshold', 'recover_augmented_bboxes': 'reverse augmentation transforms on 3D bounding boxes using scale factor and flip metadata from img_metas', 'sort_and_limit_merged_detections': 'sort merged 3D detection results by score in descending order and limit to max_num predictions', 'convert_3d_bbox_format': 'convert 3D bounding boxes from xywhr to xyxyr format for NMS processing using xywhr2xyxyr utility'}
```

