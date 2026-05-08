# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/downstream/semseg/datasets/evaluation/evaluate_semantic_instance.py

Prompts

```
['run the CLI to evaluate semantic instance predictions against ground truth using --pred_path and --gt_path', 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet semantic instance evaluation', 'evaluate matched predictions against ground truth instances and compute average precision scores per class and overlap threshold', 'assign predicted instances to ground truth instances for a given scan by computing vertex-level intersections', 'write prediction instances and masks to a benchmark output directory in the expected ScanNet format', 'run the CLI to evaluate semantic segmentation predictions against ground truth using --pred_path and --gt_path', 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet 20-class semantic segmentation', 'update the confusion matrix by calling update_confusion with predicted and ground truth ID arrays', 'evaluate the accumulated confusion matrix and write IoU scores and confusion matrix to an output file', 'get the IoU score for a specific label_id from the confusion matrix using get_iou']
```

Usage

```
{'run_semantic_instance_evaluation': 'run the CLI to evaluate semantic instance predictions against ground truth using --pred_path and --gt_path', 'create_Evaluator': 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet semantic instance evaluation', 'evaluate_matches': 'evaluate matched predictions against ground truth instances and compute average precision scores per class and overlap threshold', 'assign_instances_for_scan': 'assign predicted instances to ground truth instances for a given scan by computing vertex-level intersections', 'write_to_benchmark': 'write prediction instances and masks to a benchmark output directory in the expected ScanNet format'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/semseg/datasets/evaluation/evaluate_semantic_label.py

Prompts

```
['run the CLI to evaluate semantic instance predictions against ground truth using --pred_path and --gt_path', 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet semantic instance evaluation', 'evaluate matched predictions against ground truth instances and compute average precision scores per class and overlap threshold', 'assign predicted instances to ground truth instances for a given scan by computing vertex-level intersections', 'write prediction instances and masks to a benchmark output directory in the expected ScanNet format', 'run the CLI to evaluate semantic segmentation predictions against ground truth using --pred_path and --gt_path', 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet 20-class semantic segmentation', 'update the confusion matrix by calling update_confusion with predicted and ground truth ID arrays', 'evaluate the accumulated confusion matrix and write IoU scores and confusion matrix to an output file', 'get the IoU score for a specific label_id from the confusion matrix using get_iou']
```

Usage

```
{'run_semantic_label_evaluation': 'run the CLI to evaluate semantic segmentation predictions against ground truth using --pred_path and --gt_path', 'create_evaluator': 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet 20-class semantic segmentation', 'update_confusion_matrix': 'update the confusion matrix by calling update_confusion with predicted and ground truth ID arrays', 'evaluate_confusion_and_write_results': 'evaluate the accumulated confusion matrix and write IoU scores and confusion matrix to an output file', 'get_iou_for_class': 'get the IoU score for a specific label_id from the confusion matrix using get_iou'}
```

