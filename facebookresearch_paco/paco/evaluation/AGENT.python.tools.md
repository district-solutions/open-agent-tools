# Agent Python Tools

- repo: facebookresearch/paco
- repo_uri: https://github.com/facebookresearch/paco

## File: facebookresearch_paco/paco/evaluation/ac_dumper.py

Prompts

```
['create an ACDumper evaluator instance for a dataset with distributed evaluation and output directory', 'run get_matches to compute boolean overlap matrix between object masks and part masks with a threshold', 'process detection instances to extract object-part features, bounding boxes, and attributes for an image', 'evaluate and save AC predictions to a pth file across distributed processes using ACDumper', 'reset the ACDumper predictions list to clear accumulated results before a new evaluation run', 'review the COCOEvaluator class that extends detectron2 to support attribute predictions', 'summarize the instances_to_coco_json function that converts Instances objects to COCO-format JSON', 'test the instances_to_coco_json function with Instances containing boxes, masks, keypoints, and attributes', 'refactor instances_to_coco_json to add support for additional prediction types beyond attributes', 'build a COCOEvaluator subclass that evaluates attribute predictions alongside standard COCO metrics', 'create a PACOEvaluator instance to evaluate object detection and segmentation on a PACO dataset', 'run the PACOEvaluator process method to collect model predictions for evaluation', 'run the evaluate predictions on LVIS function to compute AP metrics for bbox or segm tasks', 'run the PACOEvaluator _eval_predictions method to evaluate collected predictions and save results', 'review the PACOEvaluator class to understand how it extends LVISEvaluator for PACO attribute evaluation', 'run the PACOQueryPredictionEvaluator to evaluate query detection predictions against a dataset and print AR results', 'run the PACOQueryEvaluator to evaluate query detections from atomic construct predictions using detectron2 model outputs', 'run the PACOQueryEvalAPI to process per-image detections and calculate average recall across IoU thresholds and query levels', 'run extract_query_gt_from_dataset to extract per-image ground truth bounding boxes and query IDs from a dataset dictionary', 'run get_bbox_ious static method to calculate intersection over union between two sets of XYXY bounding boxes']
```

Usage

```
{'create_ACDumper_evaluator': 'create an ACDumper evaluator instance for a dataset with distributed evaluation and output directory', 'run_get_matches': 'run get_matches to compute boolean overlap matrix between object masks and part masks with a threshold', 'process_instances_AC': 'process detection instances to extract object-part features, bounding boxes, and attributes for an image', 'evaluate_AC_predictions': 'evaluate and save AC predictions to a pth file across distributed processes using ACDumper', 'reset_ACDumper': 'reset the ACDumper predictions list to clear accumulated results before a new evaluation run'}
```

## File: facebookresearch_paco/paco/evaluation/coco_evaluation.py

Prompts

```
['create an ACDumper evaluator instance for a dataset with distributed evaluation and output directory', 'run get_matches to compute boolean overlap matrix between object masks and part masks with a threshold', 'process detection instances to extract object-part features, bounding boxes, and attributes for an image', 'evaluate and save AC predictions to a pth file across distributed processes using ACDumper', 'reset the ACDumper predictions list to clear accumulated results before a new evaluation run', 'review the COCOEvaluator class that extends detectron2 to support attribute predictions', 'summarize the instances_to_coco_json function that converts Instances objects to COCO-format JSON', 'test the instances_to_coco_json function with Instances containing boxes, masks, keypoints, and attributes', 'refactor instances_to_coco_json to add support for additional prediction types beyond attributes', 'build a COCOEvaluator subclass that evaluates attribute predictions alongside standard COCO metrics', 'create a PACOEvaluator instance to evaluate object detection and segmentation on a PACO dataset', 'run the PACOEvaluator process method to collect model predictions for evaluation', 'run the evaluate predictions on LVIS function to compute AP metrics for bbox or segm tasks', 'run the PACOEvaluator _eval_predictions method to evaluate collected predictions and save results', 'review the PACOEvaluator class to understand how it extends LVISEvaluator for PACO attribute evaluation', 'run the PACOQueryPredictionEvaluator to evaluate query detection predictions against a dataset and print AR results', 'run the PACOQueryEvaluator to evaluate query detections from atomic construct predictions using detectron2 model outputs', 'run the PACOQueryEvalAPI to process per-image detections and calculate average recall across IoU thresholds and query levels', 'run extract_query_gt_from_dataset to extract per-image ground truth bounding boxes and query IDs from a dataset dictionary', 'run get_bbox_ious static method to calculate intersection over union between two sets of XYXY bounding boxes']
```

Usage

```
{'review_COCOEvaluator_class': 'review the COCOEvaluator class that extends detectron2 to support attribute predictions', 'summarize_instances_to_coco_json': 'summarize the instances_to_coco_json function that converts Instances objects to COCO-format JSON', 'test_instances_to_coco_json': 'test the instances_to_coco_json function with Instances containing boxes, masks, keypoints, and attributes', 'refactor_instances_to_coco_json': 'refactor instances_to_coco_json to add support for additional prediction types beyond attributes', 'build_coco_evaluator_with_attrs': 'build a COCOEvaluator subclass that evaluates attribute predictions alongside standard COCO metrics'}
```

## File: facebookresearch_paco/paco/evaluation/paco_evaluation.py

Prompts

```
['create an ACDumper evaluator instance for a dataset with distributed evaluation and output directory', 'run get_matches to compute boolean overlap matrix between object masks and part masks with a threshold', 'process detection instances to extract object-part features, bounding boxes, and attributes for an image', 'evaluate and save AC predictions to a pth file across distributed processes using ACDumper', 'reset the ACDumper predictions list to clear accumulated results before a new evaluation run', 'review the COCOEvaluator class that extends detectron2 to support attribute predictions', 'summarize the instances_to_coco_json function that converts Instances objects to COCO-format JSON', 'test the instances_to_coco_json function with Instances containing boxes, masks, keypoints, and attributes', 'refactor instances_to_coco_json to add support for additional prediction types beyond attributes', 'build a COCOEvaluator subclass that evaluates attribute predictions alongside standard COCO metrics', 'create a PACOEvaluator instance to evaluate object detection and segmentation on a PACO dataset', 'run the PACOEvaluator process method to collect model predictions for evaluation', 'run the evaluate predictions on LVIS function to compute AP metrics for bbox or segm tasks', 'run the PACOEvaluator _eval_predictions method to evaluate collected predictions and save results', 'review the PACOEvaluator class to understand how it extends LVISEvaluator for PACO attribute evaluation', 'run the PACOQueryPredictionEvaluator to evaluate query detection predictions against a dataset and print AR results', 'run the PACOQueryEvaluator to evaluate query detections from atomic construct predictions using detectron2 model outputs', 'run the PACOQueryEvalAPI to process per-image detections and calculate average recall across IoU thresholds and query levels', 'run extract_query_gt_from_dataset to extract per-image ground truth bounding boxes and query IDs from a dataset dictionary', 'run get_bbox_ious static method to calculate intersection over union between two sets of XYXY bounding boxes']
```

Usage

```
{'create_PACOEvaluator': 'create a PACOEvaluator instance to evaluate object detection and segmentation on a PACO dataset', 'run_PACOEvaluator_process': 'run the PACOEvaluator process method to collect model predictions for evaluation', 'run_evaluate_predictions_on_lvis': 'run the evaluate predictions on LVIS function to compute AP metrics for bbox or segm tasks', 'run_PACOEvaluator_eval_predictions': 'run the PACOEvaluator _eval_predictions method to evaluate collected predictions and save results', 'review_PACOEvaluator_class': 'review the PACOEvaluator class to understand how it extends LVISEvaluator for PACO attribute evaluation'}
```

## File: facebookresearch_paco/paco/evaluation/paco_query_evaluation.py

Prompts

```
['create an ACDumper evaluator instance for a dataset with distributed evaluation and output directory', 'run get_matches to compute boolean overlap matrix between object masks and part masks with a threshold', 'process detection instances to extract object-part features, bounding boxes, and attributes for an image', 'evaluate and save AC predictions to a pth file across distributed processes using ACDumper', 'reset the ACDumper predictions list to clear accumulated results before a new evaluation run', 'review the COCOEvaluator class that extends detectron2 to support attribute predictions', 'summarize the instances_to_coco_json function that converts Instances objects to COCO-format JSON', 'test the instances_to_coco_json function with Instances containing boxes, masks, keypoints, and attributes', 'refactor instances_to_coco_json to add support for additional prediction types beyond attributes', 'build a COCOEvaluator subclass that evaluates attribute predictions alongside standard COCO metrics', 'create a PACOEvaluator instance to evaluate object detection and segmentation on a PACO dataset', 'run the PACOEvaluator process method to collect model predictions for evaluation', 'run the evaluate predictions on LVIS function to compute AP metrics for bbox or segm tasks', 'run the PACOEvaluator _eval_predictions method to evaluate collected predictions and save results', 'review the PACOEvaluator class to understand how it extends LVISEvaluator for PACO attribute evaluation', 'run the PACOQueryPredictionEvaluator to evaluate query detection predictions against a dataset and print AR results', 'run the PACOQueryEvaluator to evaluate query detections from atomic construct predictions using detectron2 model outputs', 'run the PACOQueryEvalAPI to process per-image detections and calculate average recall across IoU thresholds and query levels', 'run extract_query_gt_from_dataset to extract per-image ground truth bounding boxes and query IDs from a dataset dictionary', 'run get_bbox_ious static method to calculate intersection over union between two sets of XYXY bounding boxes']
```

Usage

```
{'run_PACOQueryPredictionEvaluator': 'run the PACOQueryPredictionEvaluator to evaluate query detection predictions against a dataset and print AR results', 'run_PACOQueryEvaluator': 'run the PACOQueryEvaluator to evaluate query detections from atomic construct predictions using detectron2 model outputs', 'run_PACOQueryEvalAPI': 'run the PACOQueryEvalAPI to process per-image detections and calculate average recall across IoU thresholds and query levels', 'run_extract_query_gt_from_dataset': 'run extract_query_gt_from_dataset to extract per-image ground truth bounding boxes and query IDs from a dataset dictionary', 'run_get_bbox_ious': 'run get_bbox_ious static method to calculate intersection over union between two sets of XYXY bounding boxes'}
```

