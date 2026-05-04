# Agent Python Tools

- repo: facebookresearch/adaptiveteacher
- repo_uri: https://github.com/facebookresearch/adaptive_teacher

## File: facebookresearch_adaptiveteacher/adapteacher/evaluation/coco_evaluation.py

Prompts

```
['convert a detectron2 registered dataset to COCO format JSON and save to an output file', 'create a COCOEvaluator instance to evaluate bbox, segmentation, or keypoint detection tasks on a dataset', 'run the COCOEvaluator evaluate method to compute AP metrics and return results as an OrderedDict', 'convert detectron2 Instances objects to COCO-format JSON annotations for a given image ID', 'evaluate detection proposal recall metrics using pairwise IoU against ground truth boxes with area filtering', 'create a PascalVOCDetectionEvaluator instance for a given dataset name to evaluate object detection results', 'run the voc_eval function to compute recall, precision, and AP for a detection class', 'compute the VOC average precision from precision and recall arrays using the voc_ap function', 'parse a PASCAL VOC XML annotation file into a list of object structures using parse_rec', 'evaluate object detection predictions against Pascal VOC ground truth annotations using the evaluate method']
```

Usage

```
{'convert_dataset_to_coco_json': 'convert a detectron2 registered dataset to COCO format JSON and save to an output file', 'create_COCOEvaluator_for_bbox_segm_keypoints': 'create a COCOEvaluator instance to evaluate bbox, segmentation, or keypoint detection tasks on a dataset', 'run_COCOEvaluator_evaluate': 'run the COCOEvaluator evaluate method to compute AP metrics and return results as an OrderedDict', 'convert_instances_to_coco_json': 'convert detectron2 Instances objects to COCO-format JSON annotations for a given image ID', 'evaluate_box_proposals_recall': 'evaluate detection proposal recall metrics using pairwise IoU against ground truth boxes with area filtering'}
```

## File: facebookresearch_adaptiveteacher/adapteacher/evaluation/pascal_voc_evaluation.py

Prompts

```
['convert a detectron2 registered dataset to COCO format JSON and save to an output file', 'create a COCOEvaluator instance to evaluate bbox, segmentation, or keypoint detection tasks on a dataset', 'run the COCOEvaluator evaluate method to compute AP metrics and return results as an OrderedDict', 'convert detectron2 Instances objects to COCO-format JSON annotations for a given image ID', 'evaluate detection proposal recall metrics using pairwise IoU against ground truth boxes with area filtering', 'create a PascalVOCDetectionEvaluator instance for a given dataset name to evaluate object detection results', 'run the voc_eval function to compute recall, precision, and AP for a detection class', 'compute the VOC average precision from precision and recall arrays using the voc_ap function', 'parse a PASCAL VOC XML annotation file into a list of object structures using parse_rec', 'evaluate object detection predictions against Pascal VOC ground truth annotations using the evaluate method']
```

Usage

```
{'create_PascalVOCDetectionEvaluator': 'create a PascalVOCDetectionEvaluator instance for a given dataset name to evaluate object detection results', 'run_voc_eval': 'run the voc_eval function to compute recall, precision, and AP for a detection class', 'compute_voc_ap': 'compute the VOC average precision from precision and recall arrays using the voc_ap function', 'parse_rec_xml': 'parse a PASCAL VOC XML annotation file into a list of object structures using parse_rec', 'evaluate_PascalVOC_predictions': 'evaluate object detection predictions against Pascal VOC ground truth annotations using the evaluate method'}
```

