# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/mmpose/datasets/datasets/base/base_coco_style_dataset.py

Prompts

```
['build a COCO-style pose dataset by instantiating BaseCocoStyleDataset with an annotation file and data prefix', 'load COCO annotations in topdown mode where each sample contains one person instance with keypoints', 'load COCO annotations in bottomup mode grouping all instances per image into a single data sample', 'parse raw COCO annotation dicts into structured data info with bbox, keypoints, and visibility arrays', 'filter dataset annotations by bbox_score threshold using filter_cfg to remove low-confidence detections', 'build a 3D body mocap dataset by instantiating BaseMocapDataset with an annotation file and sequence length', 'review the get_sequence_indices method to understand how frame indices are built for single or multi-frame samples', 'test the load_data_list method to verify it returns topdown or bottomup data infos from annotations', 'refactor the _load_annotations method to support additional annotation keys like depth or velocity data', 'summarize the get_data_info method that merges metainfo keys like flip_pairs and skeleton_links into data samples']
```

Usage

```
{'build_coco_dataset': 'build a COCO-style pose dataset by instantiating BaseCocoStyleDataset with an annotation file and data prefix', 'load_annotations_topdown': 'load COCO annotations in topdown mode where each sample contains one person instance with keypoints', 'load_annotations_bottomup': 'load COCO annotations in bottomup mode grouping all instances per image into a single data sample', 'parse_data_info': 'parse raw COCO annotation dicts into structured data info with bbox, keypoints, and visibility arrays', 'filter_data_bbox_score': 'filter dataset annotations by bbox_score threshold using filter_cfg to remove low-confidence detections'}
```

## File: facebookresearch_sapiens/pose/mmpose/datasets/datasets/base/base_mocap_dataset.py

Prompts

```
['build a COCO-style pose dataset by instantiating BaseCocoStyleDataset with an annotation file and data prefix', 'load COCO annotations in topdown mode where each sample contains one person instance with keypoints', 'load COCO annotations in bottomup mode grouping all instances per image into a single data sample', 'parse raw COCO annotation dicts into structured data info with bbox, keypoints, and visibility arrays', 'filter dataset annotations by bbox_score threshold using filter_cfg to remove low-confidence detections', 'build a 3D body mocap dataset by instantiating BaseMocapDataset with an annotation file and sequence length', 'review the get_sequence_indices method to understand how frame indices are built for single or multi-frame samples', 'test the load_data_list method to verify it returns topdown or bottomup data infos from annotations', 'refactor the _load_annotations method to support additional annotation keys like depth or velocity data', 'summarize the get_data_info method that merges metainfo keys like flip_pairs and skeleton_links into data samples']
```

Usage

```
{'build_BaseMocapDataset': 'build a 3D body mocap dataset by instantiating BaseMocapDataset with an annotation file and sequence length', 'review_get_sequence_indices': 'review the get_sequence_indices method to understand how frame indices are built for single or multi-frame samples', 'test_load_data_list': 'test the load_data_list method to verify it returns topdown or bottomup data infos from annotations', 'refactor_load_annotations': 'refactor the _load_annotations method to support additional annotation keys like depth or velocity data', 'summarize_get_data_info': 'summarize the get_data_info method that merges metainfo keys like flip_pairs and skeleton_links into data samples'}
```

