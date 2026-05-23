# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/mmpose/datasets/datasets/hand/freihand_dataset.py

Prompts

```
['instantiate FreiHandDataset with ann_file and data_prefix to load hand pose annotations', 'call parse_data_info on FreiHandDataset to extract keypoints and bbox from raw COCO annotation', 'load FreiHandDataset in topdown mode with pipeline config for single instance hand pose samples', 'access FreiHandDataset METAINFO dict to get 21 keypoint names for hand pose estimation', 'filter FreiHandDataset data by bbox_score threshold using filter_cfg in topdown mode', 'build a PanopticHand2DDataset instance for hand pose estimation with 21 keypoints from COCO annotations', 'parse raw COCO annotation data into structured instance info with bbox and keypoints for PanopticHand2DDataset', 'review the PanopticHand2DDataset class and its 21 hand keypoint definitions for hand pose estimation', 'refactor the parse_data_info method to support custom keypoint formats beyond the default 21 Panoptic hand keypoints', 'test the PanopticHand2DDataset class by instantiating it with a COCO annotation file and verifying parsed data output']
```

Usage

```
{'instantiate_FreiHandDataset': 'instantiate FreiHandDataset with ann_file and data_prefix to load hand pose annotations', 'parse_data_info_FreiHandDataset': 'call parse_data_info on FreiHandDataset to extract keypoints and bbox from raw COCO annotation', 'load_FreiHandDataset_topdown': 'load FreiHandDataset in topdown mode with pipeline config for single instance hand pose samples', 'access_FreiHandDataset_metainfo': 'access FreiHandDataset METAINFO dict to get 21 keypoint names for hand pose estimation', 'filter_FreiHandDataset_bbox_score': 'filter FreiHandDataset data by bbox_score threshold using filter_cfg in topdown mode'}
```

## File: facebookresearch_sapiens/pose/mmpose/datasets/datasets/hand/panoptic_hand2d_dataset.py

Prompts

```
['instantiate FreiHandDataset with ann_file and data_prefix to load hand pose annotations', 'call parse_data_info on FreiHandDataset to extract keypoints and bbox from raw COCO annotation', 'load FreiHandDataset in topdown mode with pipeline config for single instance hand pose samples', 'access FreiHandDataset METAINFO dict to get 21 keypoint names for hand pose estimation', 'filter FreiHandDataset data by bbox_score threshold using filter_cfg in topdown mode', 'build a PanopticHand2DDataset instance for hand pose estimation with 21 keypoints from COCO annotations', 'parse raw COCO annotation data into structured instance info with bbox and keypoints for PanopticHand2DDataset', 'review the PanopticHand2DDataset class and its 21 hand keypoint definitions for hand pose estimation', 'refactor the parse_data_info method to support custom keypoint formats beyond the default 21 Panoptic hand keypoints', 'test the PanopticHand2DDataset class by instantiating it with a COCO annotation file and verifying parsed data output']
```

Usage

```
{'build_PanopticHand2DDataset': 'build a PanopticHand2DDataset instance for hand pose estimation with 21 keypoints from COCO annotations', 'parse_data_info_PanopticHand2DDataset': 'parse raw COCO annotation data into structured instance info with bbox and keypoints for PanopticHand2DDataset', 'review_PanopticHand2DDataset': 'review the PanopticHand2DDataset class and its 21 hand keypoint definitions for hand pose estimation', 'refactor_parse_data_info': 'refactor the parse_data_info method to support custom keypoint formats beyond the default 21 Panoptic hand keypoints', 'test_PanopticHand2DDataset': 'test the PanopticHand2DDataset class by instantiating it with a COCO annotation file and verifying parsed data output'}
```

