# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/mask2former_video/data_video/datasets/ytvis_api/ytvos.py

Prompts

```
['load a YouTubeVIS annotation JSON file into a YTVOS API object for querying videos, categories, and annotations', 'get annotation IDs filtered by video IDs, category IDs, area range, or crowd label using getAnnIds', 'get category IDs filtered by category names, supercategory names, or existing category IDs using getCatIds', 'convert a YouTubeVIS annotation segmentation to a binary numpy mask for a specific frame using annToMask', 'load algorithm result annotations from a JSON file into a YTVOS result object for evaluation using loadRes', 'run YTVOSeval.evaluate() to evaluate video instance segmentation detections against ground truth annotations', 'run YTVOSeval.accumulate() to accumulate per-video per-category evaluation results into precision and recall arrays', 'run YTVOSeval.summarize() to compute and display AP and AR summary metrics for YouTubeVIS evaluation', 'create a YTVOSeval object with ground truth and detection COCO API objects for video instance segmentation evaluation', 'review YTVOSeval.computeIoU() to understand how sequence-level IoU is computed between detection and ground truth mask sequences']
```

Usage

```
{'load_ytvos_dataset': 'load a YouTubeVIS annotation JSON file into a YTVOS API object for querying videos, categories, and annotations', 'get_ann_ids_by_filter': 'get annotation IDs filtered by video IDs, category IDs, area range, or crowd label using getAnnIds', 'get_cat_ids_by_name': 'get category IDs filtered by category names, supercategory names, or existing category IDs using getCatIds', 'convert_annotation_to_mask': 'convert a YouTubeVIS annotation segmentation to a binary numpy mask for a specific frame using annToMask', 'load_results_and_evaluate': 'load algorithm result annotations from a JSON file into a YTVOS result object for evaluation using loadRes'}
```

## File: facebookresearch_mask2former/mask2former_video/data_video/datasets/ytvis_api/ytvoseval.py

Prompts

```
['load a YouTubeVIS annotation JSON file into a YTVOS API object for querying videos, categories, and annotations', 'get annotation IDs filtered by video IDs, category IDs, area range, or crowd label using getAnnIds', 'get category IDs filtered by category names, supercategory names, or existing category IDs using getCatIds', 'convert a YouTubeVIS annotation segmentation to a binary numpy mask for a specific frame using annToMask', 'load algorithm result annotations from a JSON file into a YTVOS result object for evaluation using loadRes', 'run YTVOSeval.evaluate() to evaluate video instance segmentation detections against ground truth annotations', 'run YTVOSeval.accumulate() to accumulate per-video per-category evaluation results into precision and recall arrays', 'run YTVOSeval.summarize() to compute and display AP and AR summary metrics for YouTubeVIS evaluation', 'create a YTVOSeval object with ground truth and detection COCO API objects for video instance segmentation evaluation', 'review YTVOSeval.computeIoU() to understand how sequence-level IoU is computed between detection and ground truth mask sequences']
```

Usage

```
{'run_ytvoseval_evaluate': 'run YTVOSeval.evaluate() to evaluate video instance segmentation detections against ground truth annotations', 'run_ytvoseval_accumulate': 'run YTVOSeval.accumulate() to accumulate per-video per-category evaluation results into precision and recall arrays', 'run_ytvoseval_summarize': 'run YTVOSeval.summarize() to compute and display AP and AR summary metrics for YouTubeVIS evaluation', 'create_ytvoseval_instance': 'create a YTVOSeval object with ground truth and detection COCO API objects for video instance segmentation evaluation', 'review_ytvoseval_compute_iou': 'review YTVOSeval.computeIoU() to understand how sequence-level IoU is computed between detection and ground truth mask sequences'}
```

