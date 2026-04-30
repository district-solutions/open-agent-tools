# Agent Python Tools

- repo: facebookresearch/sam3
- repo_uri: https://github.com/facebookresearch/sam3

## File: facebookresearch_sam3/sam3/eval/hota_eval_toolkit/trackeval/datasets/_base_dataset.py

Prompts

```
['load raw tracking data from a CSV or text file with auto-detected dialect and timestep grouping', 'calculate IoU or IoA between two arrays of bounding boxes in xywh or x0y0x1y1 format', 'calculate IoU or IoA between two arrays of segmentation masks using pycocotools RLE encoding', 'get raw sequence data for a tracker and ground-truth on a single sequence including similarity scores', 'check that tracker and ground-truth IDs are unique per timestep and raise on duplicates', 'create a TAO_OW dataset instance for open-world tracking evaluation with custom config', 'get the default dataset configuration for TAO_OW tracking evaluation', 'load raw ground truth or tracker annotation data for a TAO sequence in TAO format', 'preprocess a raw annotated sequence for a single class ready for HOTA evaluation', 'calculate IoU similarity scores between ground truth and tracker bounding boxes', 'merge TAO categories that share a merged tag into a single category', 'filter ground truth data by known, unknown, or distractor subset for open-world tracking', 'limit the number of tracker detections per image to a maximum count', 'create a YouTubeVIS dataset instance for video object tracking evaluation with configurable GT and tracker JSON objects', 'run YouTubeVIS tracking evaluation with configurable IOU type for segmentation or bounding box metrics', 'build preprocessed sequence data for a single class filtering detections and relabeling track IDs contiguously', 'load raw tracking file for a YouTubeVIS sequence extracting detections, IDs, and classes per timestep', 'prepare ground truth annotations by RLE encoding segmentations and computing average track areas']
```

Usage

```
{'load_tracking_data_from_text': 'load raw tracking data from a CSV or text file with auto-detected dialect and timestep grouping', 'calculate_box_ious': 'calculate IoU or IoA between two arrays of bounding boxes in xywh or x0y0x1y1 format', 'calculate_mask_ious': 'calculate IoU or IoA between two arrays of segmentation masks using pycocotools RLE encoding', 'get_raw_sequence_data': 'get raw sequence data for a tracker and ground-truth on a single sequence including similarity scores', 'check_unique_ids': 'check that tracker and ground-truth IDs are unique per timestep and raise on duplicates'}
```

## File: facebookresearch_sam3/sam3/eval/hota_eval_toolkit/trackeval/datasets/tao_ow.py

Prompts

```
['load raw tracking data from a CSV or text file with auto-detected dialect and timestep grouping', 'calculate IoU or IoA between two arrays of bounding boxes in xywh or x0y0x1y1 format', 'calculate IoU or IoA between two arrays of segmentation masks using pycocotools RLE encoding', 'get raw sequence data for a tracker and ground-truth on a single sequence including similarity scores', 'check that tracker and ground-truth IDs are unique per timestep and raise on duplicates', 'create a TAO_OW dataset instance for open-world tracking evaluation with custom config', 'get the default dataset configuration for TAO_OW tracking evaluation', 'load raw ground truth or tracker annotation data for a TAO sequence in TAO format', 'preprocess a raw annotated sequence for a single class ready for HOTA evaluation', 'calculate IoU similarity scores between ground truth and tracker bounding boxes', 'merge TAO categories that share a merged tag into a single category', 'filter ground truth data by known, unknown, or distractor subset for open-world tracking', 'limit the number of tracker detections per image to a maximum count', 'create a YouTubeVIS dataset instance for video object tracking evaluation with configurable GT and tracker JSON objects', 'run YouTubeVIS tracking evaluation with configurable IOU type for segmentation or bounding box metrics', 'build preprocessed sequence data for a single class filtering detections and relabeling track IDs contiguously', 'load raw tracking file for a YouTubeVIS sequence extracting detections, IDs, and classes per timestep', 'prepare ground truth annotations by RLE encoding segmentations and computing average track areas']
```

Usage

```
{'create_tao_ow_dataset': 'create a TAO_OW dataset instance for open-world tracking evaluation with custom config', 'get_default_dataset_config': 'get the default dataset configuration for TAO_OW tracking evaluation', 'load_raw_file': 'load raw ground truth or tracker annotation data for a TAO sequence in TAO format', 'preprocess_sequence_data': 'preprocess a raw annotated sequence for a single class ready for HOTA evaluation', 'calculate_similarities': 'calculate IoU similarity scores between ground truth and tracker bounding boxes', 'merge_categories': 'merge TAO categories that share a merged tag into a single category', 'filter_gt_data': 'filter ground truth data by known, unknown, or distractor subset for open-world tracking', 'limit_detections_per_image': 'limit the number of tracker detections per image to a maximum count'}
```

## File: facebookresearch_sam3/sam3/eval/hota_eval_toolkit/trackeval/datasets/youtube_vis.py

Prompts

```
['load raw tracking data from a CSV or text file with auto-detected dialect and timestep grouping', 'calculate IoU or IoA between two arrays of bounding boxes in xywh or x0y0x1y1 format', 'calculate IoU or IoA between two arrays of segmentation masks using pycocotools RLE encoding', 'get raw sequence data for a tracker and ground-truth on a single sequence including similarity scores', 'check that tracker and ground-truth IDs are unique per timestep and raise on duplicates', 'create a TAO_OW dataset instance for open-world tracking evaluation with custom config', 'get the default dataset configuration for TAO_OW tracking evaluation', 'load raw ground truth or tracker annotation data for a TAO sequence in TAO format', 'preprocess a raw annotated sequence for a single class ready for HOTA evaluation', 'calculate IoU similarity scores between ground truth and tracker bounding boxes', 'merge TAO categories that share a merged tag into a single category', 'filter ground truth data by known, unknown, or distractor subset for open-world tracking', 'limit the number of tracker detections per image to a maximum count', 'create a YouTubeVIS dataset instance for video object tracking evaluation with configurable GT and tracker JSON objects', 'run YouTubeVIS tracking evaluation with configurable IOU type for segmentation or bounding box metrics', 'build preprocessed sequence data for a single class filtering detections and relabeling track IDs contiguously', 'load raw tracking file for a YouTubeVIS sequence extracting detections, IDs, and classes per timestep', 'prepare ground truth annotations by RLE encoding segmentations and computing average track areas']
```

Usage

```
{'create_youtubevis_dataset': 'create a YouTubeVIS dataset instance for video object tracking evaluation with configurable GT and tracker JSON objects', 'run_youtubevis_iou_evaluation': 'run YouTubeVIS tracking evaluation with configurable IOU type for segmentation or bounding box metrics', 'build_preprocessed_sequence_data': 'build preprocessed sequence data for a single class filtering detections and relabeling track IDs contiguously', 'load_raw_tracking_file': 'load raw tracking file for a YouTubeVIS sequence extracting detections, IDs, and classes per timestep', 'prepare_gt_annotations': 'prepare ground truth annotations by RLE encoding segmentations and computing average track areas'}
```

