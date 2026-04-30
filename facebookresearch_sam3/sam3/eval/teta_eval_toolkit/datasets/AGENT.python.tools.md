# Agent Python Tools

- repo: facebookresearch/sam3
- repo_uri: https://github.com/facebookresearch/sam3

## File: facebookresearch_sam3/sam3/eval/teta_eval_toolkit/datasets/_base_dataset.py

Prompts

```
['build a subclass of _BaseDataset implementing _load_raw_file, get_preprocessed_seq_data, and _calculate_similarities for a new evaluation dataset', 'create a function that loads CSV or text detection files with auto-dialect detection, timestep grouping, and crowd-ignore filtering', 'calculate IoU or IoA between two sets of segmentation masks using pycocotools RLE encoding or raw numpy arrays', 'calculate IoU or IoA between two sets of 2D bounding boxes supporting xywh and x0y0x1y1 formats', 'calculate euclidean distance-based similarity between sets of 2D or 3D point detections with configurable zero_distance threshold', 'create a COCO dataset instance for tracking evaluation from ground truth and tracker JSON files', 'run get_preprocessed_seq_data to preprocess tracking data for a sequence and class with IoU thresholds', 'build raw tracking or ground truth file data into timestep-aligned detections, IDs, and classes', 'test compute similarity scores between ground truth and tracker detections using masks or bounding boxes', 'review make track IDs unique across videos to avoid ID collisions in multi-video annotation sets', 'create a TAO dataset instance for video object tracking evaluation with ground truth and tracker JSON files', 'run TAO preprocessed sequence data evaluation for a specific class with optional assignment thresholds', 'load raw TAO tracking data for a sequence in ground truth or tracker format', 'merge TAO dataset categories marked with a merged tag across annotations', 'make track IDs unique across the whole annotation set for TAO evaluation']
```

Usage

```
{'build_base_dataset_subclass': 'build a subclass of _BaseDataset implementing _load_raw_file, get_preprocessed_seq_data, and _calculate_similarities for a new evaluation dataset', 'create_load_simple_text_file': 'create a function that loads CSV or text detection files with auto-dialect detection, timestep grouping, and crowd-ignore filtering', 'calculate_mask_ious': 'calculate IoU or IoA between two sets of segmentation masks using pycocotools RLE encoding or raw numpy arrays', 'calculate_box_ious': 'calculate IoU or IoA between two sets of 2D bounding boxes supporting xywh and x0y0x1y1 formats', 'calculate_euclidean_similarity': 'calculate euclidean distance-based similarity between sets of 2D or 3D point detections with configurable zero_distance threshold'}
```

## File: facebookresearch_sam3/sam3/eval/teta_eval_toolkit/datasets/coco.py

Prompts

```
['build a subclass of _BaseDataset implementing _load_raw_file, get_preprocessed_seq_data, and _calculate_similarities for a new evaluation dataset', 'create a function that loads CSV or text detection files with auto-dialect detection, timestep grouping, and crowd-ignore filtering', 'calculate IoU or IoA between two sets of segmentation masks using pycocotools RLE encoding or raw numpy arrays', 'calculate IoU or IoA between two sets of 2D bounding boxes supporting xywh and x0y0x1y1 formats', 'calculate euclidean distance-based similarity between sets of 2D or 3D point detections with configurable zero_distance threshold', 'create a COCO dataset instance for tracking evaluation from ground truth and tracker JSON files', 'run get_preprocessed_seq_data to preprocess tracking data for a sequence and class with IoU thresholds', 'build raw tracking or ground truth file data into timestep-aligned detections, IDs, and classes', 'test compute similarity scores between ground truth and tracker detections using masks or bounding boxes', 'review make track IDs unique across videos to avoid ID collisions in multi-video annotation sets', 'create a TAO dataset instance for video object tracking evaluation with ground truth and tracker JSON files', 'run TAO preprocessed sequence data evaluation for a specific class with optional assignment thresholds', 'load raw TAO tracking data for a sequence in ground truth or tracker format', 'merge TAO dataset categories marked with a merged tag across annotations', 'make track IDs unique across the whole annotation set for TAO evaluation']
```

Usage

```
{'create_COCO_dataset': 'create a COCO dataset instance for tracking evaluation from ground truth and tracker JSON files', 'run_get_preprocessed_seq_data': 'run get_preprocessed_seq_data to preprocess tracking data for a sequence and class with IoU thresholds', 'build_load_raw_file': 'build raw tracking or ground truth file data into timestep-aligned detections, IDs, and classes', 'test_calculate_similarities': 'test compute similarity scores between ground truth and tracker detections using masks or bounding boxes', 'review_make_tk_ids_unique': 'review make track IDs unique across videos to avoid ID collisions in multi-video annotation sets'}
```

## File: facebookresearch_sam3/sam3/eval/teta_eval_toolkit/datasets/tao.py

Prompts

```
['build a subclass of _BaseDataset implementing _load_raw_file, get_preprocessed_seq_data, and _calculate_similarities for a new evaluation dataset', 'create a function that loads CSV or text detection files with auto-dialect detection, timestep grouping, and crowd-ignore filtering', 'calculate IoU or IoA between two sets of segmentation masks using pycocotools RLE encoding or raw numpy arrays', 'calculate IoU or IoA between two sets of 2D bounding boxes supporting xywh and x0y0x1y1 formats', 'calculate euclidean distance-based similarity between sets of 2D or 3D point detections with configurable zero_distance threshold', 'create a COCO dataset instance for tracking evaluation from ground truth and tracker JSON files', 'run get_preprocessed_seq_data to preprocess tracking data for a sequence and class with IoU thresholds', 'build raw tracking or ground truth file data into timestep-aligned detections, IDs, and classes', 'test compute similarity scores between ground truth and tracker detections using masks or bounding boxes', 'review make track IDs unique across videos to avoid ID collisions in multi-video annotation sets', 'create a TAO dataset instance for video object tracking evaluation with ground truth and tracker JSON files', 'run TAO preprocessed sequence data evaluation for a specific class with optional assignment thresholds', 'load raw TAO tracking data for a sequence in ground truth or tracker format', 'merge TAO dataset categories marked with a merged tag across annotations', 'make track IDs unique across the whole annotation set for TAO evaluation']
```

Usage

```
{'create_TAO_dataset': 'create a TAO dataset instance for video object tracking evaluation with ground truth and tracker JSON files', 'run_tao_preprocessed_seq_data': 'run TAO preprocessed sequence data evaluation for a specific class with optional assignment thresholds', 'load_raw_tao_file': 'load raw TAO tracking data for a sequence in ground truth or tracker format', 'merge_tao_categories': 'merge TAO dataset categories marked with a merged tag across annotations', 'make_tao_track_ids_unique': 'make track IDs unique across the whole annotation set for TAO evaluation'}
```

