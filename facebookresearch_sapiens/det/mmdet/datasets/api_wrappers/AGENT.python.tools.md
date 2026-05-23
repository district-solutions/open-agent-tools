# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/mmdet/datasets/api_wrappers/coco_api.py

Prompts

```
['create a COCO instance from an annotation JSON file to query image and category data', 'get annotation IDs filtered by image IDs, category IDs, area range, and iscrowd flag', 'load annotation objects by their integer IDs from the COCO dataset', 'create an index for panoptic segmentation annotations mapping segment IDs to annotations', 'load panoptic segmentation annotations by segment ID from the COCOPanoptic dataset', 'run multi-process COCO evaluation on detection results using 8 worker processes', 'evaluate a single image for a given category, area range, and max detections', 'prepare ground truth and detection annotations indexed by image and category ID', 'summarize AP and AR stats for bbox or segmentation across IoU thresholds and area ranges', 'summarize AP and AR stats for keypoints across IoU thresholds and area ranges']
```

Usage

```
{'create_coco_api_wrapper': 'create a COCO instance from an annotation JSON file to query image and category data', 'get_ann_ids_coco': 'get annotation IDs filtered by image IDs, category IDs, area range, and iscrowd flag', 'load_anns_coco': 'load annotation objects by their integer IDs from the COCO dataset', 'create_cocopanoptic_index': 'create an index for panoptic segmentation annotations mapping segment IDs to annotations', 'load_anns_cocopanoptic': 'load panoptic segmentation annotations by segment ID from the COCOPanoptic dataset'}
```

## File: facebookresearch_sapiens/det/mmdet/datasets/api_wrappers/cocoeval_mp.py

Prompts

```
['create a COCO instance from an annotation JSON file to query image and category data', 'get annotation IDs filtered by image IDs, category IDs, area range, and iscrowd flag', 'load annotation objects by their integer IDs from the COCO dataset', 'create an index for panoptic segmentation annotations mapping segment IDs to annotations', 'load panoptic segmentation annotations by segment ID from the COCOPanoptic dataset', 'run multi-process COCO evaluation on detection results using 8 worker processes', 'evaluate a single image for a given category, area range, and max detections', 'prepare ground truth and detection annotations indexed by image and category ID', 'summarize AP and AR stats for bbox or segmentation across IoU thresholds and area ranges', 'summarize AP and AR stats for keypoints across IoU thresholds and area ranges']
```

Usage

```
{'run_multiprocess_coco_evaluation': 'run multi-process COCO evaluation on detection results using 8 worker processes', 'evaluate_single_image': 'evaluate a single image for a given category, area range, and max detections', 'prepare_gt_dt_annotations': 'prepare ground truth and detection annotations indexed by image and category ID', 'summarize_detection_stats': 'summarize AP and AR stats for bbox or segmentation across IoU thresholds and area ranges', 'summarize_keypoint_stats': 'summarize AP and AR stats for keypoints across IoU thresholds and area ranges'}
```

