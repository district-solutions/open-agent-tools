# Agent Python Tools

- repo: facebookresearch/maskrcnn-benchmark
- repo_uri: https://github.com/facebookresearch/maskrcnn-benchmark

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/data/datasets/evaluation/cityscapes/cityscapes_eval.py

Prompts

```
['run the do_cityscapes_evaluation function to evaluate predictions against Cityscapes ground truth', 'evaluate bounding box matches using eval_instances.evaluateBoxMatches with computed IoU scores', 'evaluate segmentation mask matches using eval_instances.evaluateMaskMatches with computed IoU scores', 'compute average AP scores using eval_instances.computeAverages on box or mask match results', 'match ground truth instances with predictions using eval_instances.matchGtsWithPreds for IoU computation', 'run matchGtsWithPreds to match ground truth instances with predictions across a dataset', 'run evaluateBoxMatches to compute bounding box AP scores for Cityscapes instance evaluation', 'run evaluateMaskMatches to compute mask-level AP scores for Cityscapes instance segmentation', 'run computeAverages to compute average AP, AP50, and AP75 metrics from evaluation results', 'run printResults to print a formatted table of per-class and average AP metrics']
```

Usage

```
{'run_cityscapes_evaluation': 'run the do_cityscapes_evaluation function to evaluate predictions against Cityscapes ground truth', 'evaluate_bbox_matches': 'evaluate bounding box matches using eval_instances.evaluateBoxMatches with computed IoU scores', 'evaluate_mask_matches': 'evaluate segmentation mask matches using eval_instances.evaluateMaskMatches with computed IoU scores', 'compute_averages': 'compute average AP scores using eval_instances.computeAverages on box or mask match results', 'match_gts_with_preds': 'match ground truth instances with predictions using eval_instances.matchGtsWithPreds for IoU computation'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/data/datasets/evaluation/cityscapes/eval_instances.py

Prompts

```
['run the do_cityscapes_evaluation function to evaluate predictions against Cityscapes ground truth', 'evaluate bounding box matches using eval_instances.evaluateBoxMatches with computed IoU scores', 'evaluate segmentation mask matches using eval_instances.evaluateMaskMatches with computed IoU scores', 'compute average AP scores using eval_instances.computeAverages on box or mask match results', 'match ground truth instances with predictions using eval_instances.matchGtsWithPreds for IoU computation', 'run matchGtsWithPreds to match ground truth instances with predictions across a dataset', 'run evaluateBoxMatches to compute bounding box AP scores for Cityscapes instance evaluation', 'run evaluateMaskMatches to compute mask-level AP scores for Cityscapes instance segmentation', 'run computeAverages to compute average AP, AP50, and AP75 metrics from evaluation results', 'run printResults to print a formatted table of per-class and average AP metrics']
```

Usage

```
{'run_matchGtsWithPreds': 'run matchGtsWithPreds to match ground truth instances with predictions across a dataset', 'run_evaluateBoxMatches': 'run evaluateBoxMatches to compute bounding box AP scores for Cityscapes instance evaluation', 'run_evaluateMaskMatches': 'run evaluateMaskMatches to compute mask-level AP scores for Cityscapes instance segmentation', 'run_computeAverages': 'run computeAverages to compute average AP, AP50, and AP75 metrics from evaluation results', 'run_printResults': 'run printResults to print a formatted table of per-class and average AP metrics'}
```

