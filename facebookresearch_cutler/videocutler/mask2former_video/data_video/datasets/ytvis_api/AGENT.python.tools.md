# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/mask2former_video/data_video/datasets/ytvis_api/ytvos.py

Prompts

```
['load a YouTubeVIS dataset annotation JSON file using the YTVOS class constructor', 'get annotation IDs filtered by video IDs, category IDs, area range, or crowd label', 'get category IDs filtered by category names, supercategory names, or category IDs', 'convert a YouTubeVIS annotation segmentation to a binary numpy mask for a given frame', 'load algorithm result annotations from a JSON file and create an indexed YTVOS result API object', 'run YTVOSeval evaluate method to compute per video evaluation results for YouTubeVIS dataset', 'run YTVOSeval accumulate method to aggregate per video results into precision and recall arrays', 'run YTVOSeval summarize method to compute and display AP and AR summary metrics', 'create a YTVOSeval object with ground truth and detection COCO API objects for evaluation', 'review the YTVOSeval computeIoU method that calculates IoU between detection and ground truth mask sequences']
```

Usage

```
{'load_ytvos_dataset': 'load a YouTubeVIS dataset annotation JSON file using the YTVOS class constructor', 'get_ann_ids_by_filter': 'get annotation IDs filtered by video IDs, category IDs, area range, or crowd label', 'get_cat_ids_by_name': 'get category IDs filtered by category names, supercategory names, or category IDs', 'convert_annotation_to_mask': 'convert a YouTubeVIS annotation segmentation to a binary numpy mask for a given frame', 'load_results_and_index': 'load algorithm result annotations from a JSON file and create an indexed YTVOS result API object'}
```

## File: facebookresearch_cutler/videocutler/mask2former_video/data_video/datasets/ytvis_api/ytvoseval.py

Prompts

```
['load a YouTubeVIS dataset annotation JSON file using the YTVOS class constructor', 'get annotation IDs filtered by video IDs, category IDs, area range, or crowd label', 'get category IDs filtered by category names, supercategory names, or category IDs', 'convert a YouTubeVIS annotation segmentation to a binary numpy mask for a given frame', 'load algorithm result annotations from a JSON file and create an indexed YTVOS result API object', 'run YTVOSeval evaluate method to compute per video evaluation results for YouTubeVIS dataset', 'run YTVOSeval accumulate method to aggregate per video results into precision and recall arrays', 'run YTVOSeval summarize method to compute and display AP and AR summary metrics', 'create a YTVOSeval object with ground truth and detection COCO API objects for evaluation', 'review the YTVOSeval computeIoU method that calculates IoU between detection and ground truth mask sequences']
```

Usage

```
{'run_ytvoseval_evaluate': 'run YTVOSeval evaluate method to compute per video evaluation results for YouTubeVIS dataset', 'run_ytvoseval_accumulate': 'run YTVOSeval accumulate method to aggregate per video results into precision and recall arrays', 'run_ytvoseval_summarize': 'run YTVOSeval summarize method to compute and display AP and AR summary metrics', 'create_ytvoseval_instance': 'create a YTVOSeval object with ground truth and detection COCO API objects for evaluation', 'review_ytvoseval_compute_iou': 'review the YTVOSeval computeIoU method that calculates IoU between detection and ground truth mask sequences'}
```

