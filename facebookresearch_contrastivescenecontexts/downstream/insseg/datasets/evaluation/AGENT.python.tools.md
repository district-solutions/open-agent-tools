# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/downstream/insseg/datasets/evaluation/evaluate_semantic_instance.py

Prompts

```
['run the CLI to evaluate semantic instance predictions against ground truth using --pred_path and --gt_path', 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet semantic instance evaluation', 'evaluate matched prediction and ground truth instances to compute average precision across overlap thresholds', 'assign and match predicted instances to ground truth instances for a given scan scene ID', 'write prediction instances and masks to benchmark format files in the specified output directory', 'run the semantic label evaluation CLI with --pred_path and --gt_path to compute IoU scores', 'update the confusion matrix by calling update_confusion with predicted and ground truth ID arrays', 'evaluate the accumulated confusion matrix and write per-class IoU scores to an output file', 'get the IoU score for a specific label_id from the confusion matrix using get_iou']
```

Usage

```
{'run_semantic_instance_evaluation': 'run the CLI to evaluate semantic instance predictions against ground truth using --pred_path and --gt_path', 'create_evaluator': 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet semantic instance evaluation', 'evaluate_matches': 'evaluate matched prediction and ground truth instances to compute average precision across overlap thresholds', 'assign_instances_for_scan': 'assign and match predicted instances to ground truth instances for a given scan scene ID', 'write_to_benchmark': 'write prediction instances and masks to benchmark format files in the specified output directory'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/insseg/datasets/evaluation/evaluate_semantic_label.py

Prompts

```
['run the CLI to evaluate semantic instance predictions against ground truth using --pred_path and --gt_path', 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet semantic instance evaluation', 'evaluate matched prediction and ground truth instances to compute average precision across overlap thresholds', 'assign and match predicted instances to ground truth instances for a given scan scene ID', 'write prediction instances and masks to benchmark format files in the specified output directory', 'run the semantic label evaluation CLI with --pred_path and --gt_path to compute IoU scores', 'update the confusion matrix by calling update_confusion with predicted and ground truth ID arrays', 'evaluate the accumulated confusion matrix and write per-class IoU scores to an output file', 'get the IoU score for a specific label_id from the confusion matrix using get_iou']
```

Usage

```
{'run_semantic_label_evaluation': 'run the semantic label evaluation CLI with --pred_path and --gt_path to compute IoU scores', 'create_evaluator': 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet semantic segmentation evaluation', 'update_confusion_matrix': 'update the confusion matrix by calling update_confusion with predicted and ground truth ID arrays', 'evaluate_confusion_and_write_results': 'evaluate the accumulated confusion matrix and write per-class IoU scores to an output file', 'get_iou_for_class': 'get the IoU score for a specific label_id from the confusion matrix using get_iou'}
```

