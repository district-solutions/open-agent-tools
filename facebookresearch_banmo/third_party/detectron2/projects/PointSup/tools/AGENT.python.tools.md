# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/projects/PointSup/tools/prepare_coco_point_annotations_without_masks.py

Prompts

```
['run the script to generate point-based supervision annotations for the COCO dataset with a specified number of points per instance', 'run get_point_annotations to convert COCO segmentation masks into sampled point coordinates and labels within bounding boxes', 'build a point-supervised COCO dataset by sampling random points inside object bounding boxes and labeling them using decoded segmentation masks', 'refactor get_point_annotations to support custom input output paths and configurable point sampling density per instance', 'review the mask conversion logic that handles polygon, uncompressed RLE, and compressed RLE segmentation formats using pycocotools']
```

Usage

```
{'run_prepare_coco_point_annotations': 'run the script to generate point-based supervision annotations for the COCO dataset with a specified number of points per instance', 'run_get_point_annotations': 'run get_point_annotations to convert COCO segmentation masks into sampled point coordinates and labels within bounding boxes', 'build_point_supervision_dataset': 'build a point-supervised COCO dataset by sampling random points inside object bounding boxes and labeling them using decoded segmentation masks', 'refactor_get_point_annotations': 'refactor get_point_annotations to support custom input output paths and configurable point sampling density per instance', 'review_mask_conversion_logic': 'review the mask conversion logic that handles polygon, uncompressed RLE, and compressed RLE segmentation formats using pycocotools'}
```

