# Agent Python Tools

- repo: facebookresearch/adaptiveteacher
- repo_uri: https://github.com/facebookresearch/adaptive_teacher

## File: facebookresearch_adaptiveteacher/prod_lib/evaluation/coco_evaluation.py

Prompts

```
['convert a detectron2 dataset to COCO JSON format and save it to a specified output file', 'create a COCOEvaluator instance to evaluate bbox, segmentation, and keypoint detection metrics on a dataset', 'run the COCOEvaluator evaluate method to compute AP and AR metrics on collected predictions', 'convert detectron2 Instances objects into a COCO-format JSON list for evaluation', 'review the box proposal recall evaluation function that computes AR metrics across area ranges and limits', 'run PascalVOCDetectionEvaluator on a dataset to compute Pascal VOC style AP metrics for object detection', 'run voc_eval to compute recall, precision, and AP for a specific class against ground truth annotations', 'run voc_ap to compute average precision from precision and recall arrays using VOC 07 or 12 metric', 'run parse_rec to parse a PASCAL VOC XML annotation file and extract object bounding box data', 'review the PascalVOCDetectionEvaluator evaluate method to understand how mAP, AP50, and AP75 are computed']
```

Usage

```
{'convert_to_coco_json': 'convert a detectron2 dataset to COCO JSON format and save it to a specified output file', 'create_COCOEvaluator': 'create a COCOEvaluator instance to evaluate bbox, segmentation, and keypoint detection metrics on a dataset', 'run_COCOEvaluator_evaluate': 'run the COCOEvaluator evaluate method to compute AP and AR metrics on collected predictions', 'instances_to_coco_json': 'convert detectron2 Instances objects into a COCO-format JSON list for evaluation', 'review__evaluate_box_proposals': 'review the box proposal recall evaluation function that computes AR metrics across area ranges and limits'}
```

## File: facebookresearch_adaptiveteacher/prod_lib/evaluation/pascal_voc_evaluation.py

Prompts

```
['convert a detectron2 dataset to COCO JSON format and save it to a specified output file', 'create a COCOEvaluator instance to evaluate bbox, segmentation, and keypoint detection metrics on a dataset', 'run the COCOEvaluator evaluate method to compute AP and AR metrics on collected predictions', 'convert detectron2 Instances objects into a COCO-format JSON list for evaluation', 'review the box proposal recall evaluation function that computes AR metrics across area ranges and limits', 'run PascalVOCDetectionEvaluator on a dataset to compute Pascal VOC style AP metrics for object detection', 'run voc_eval to compute recall, precision, and AP for a specific class against ground truth annotations', 'run voc_ap to compute average precision from precision and recall arrays using VOC 07 or 12 metric', 'run parse_rec to parse a PASCAL VOC XML annotation file and extract object bounding box data', 'review the PascalVOCDetectionEvaluator evaluate method to understand how mAP, AP50, and AP75 are computed']
```

Usage

```
{'run_PascalVOCDetectionEvaluator': 'run PascalVOCDetectionEvaluator on a dataset to compute Pascal VOC style AP metrics for object detection', 'run_voc_eval': 'run voc_eval to compute recall, precision, and AP for a specific class against ground truth annotations', 'run_voc_ap': 'run voc_ap to compute average precision from precision and recall arrays using VOC 07 or 12 metric', 'run_parse_rec': 'run parse_rec to parse a PASCAL VOC XML annotation file and extract object bounding box data', 'review_PascalVOCDetectionEvaluator_evaluate': 'review the PascalVOCDetectionEvaluator evaluate method to understand how mAP, AP50, and AP75 are computed'}
```

