# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/tools/analyze_model.py

Prompts

```
['run the analyze_model.py script with --tasks flop to compute GFlops for a Mask2Former model', 'run the analyze_model.py script with --tasks activation to count activations per operator type', 'run the analyze_model.py script with --tasks parameter to display the model parameter count table', 'run the analyze_model.py script with --tasks structure to print the full model structure', 'run the analyze_model.py script with --tasks flop parameter to compute flops and parameters together', 'run the script to evaluate PQ metric for semantic segmentation predictions on a dataset like ADE20K', 'compute PQ statistics for a single image by comparing ground truth and predicted segmentation masks', 'create an argument parser with dataset name and JSON file path options for PQ evaluation', 'calculate mean IoU from the confusion matrix between ground truth and predicted semantic segmentation labels', 'compute average PQ, SQ, and RQ metrics across all categories using the PQStat object']
```

Usage

```
{'run_flop_analysis': 'run the analyze_model.py script with --tasks flop to compute GFlops for a Mask2Former model', 'run_activation_analysis': 'run the analyze_model.py script with --tasks activation to count activations per operator type', 'run_parameter_analysis': 'run the analyze_model.py script with --tasks parameter to display the model parameter count table', 'run_structure_analysis': 'run the analyze_model.py script with --tasks structure to print the full model structure', 'run_multiple_analysis_tasks': 'run the analyze_model.py script with --tasks flop parameter to compute flops and parameters together'}
```

## File: facebookresearch_mask2former/tools/evaluate_pq_for_semantic_segmentation.py

Prompts

```
['run the analyze_model.py script with --tasks flop to compute GFlops for a Mask2Former model', 'run the analyze_model.py script with --tasks activation to count activations per operator type', 'run the analyze_model.py script with --tasks parameter to display the model parameter count table', 'run the analyze_model.py script with --tasks structure to print the full model structure', 'run the analyze_model.py script with --tasks flop parameter to compute flops and parameters together', 'run the script to evaluate PQ metric for semantic segmentation predictions on a dataset like ADE20K', 'compute PQ statistics for a single image by comparing ground truth and predicted segmentation masks', 'create an argument parser with dataset name and JSON file path options for PQ evaluation', 'calculate mean IoU from the confusion matrix between ground truth and predicted semantic segmentation labels', 'compute average PQ, SQ, and RQ metrics across all categories using the PQStat object']
```

Usage

```
{'run_evaluate_pq_for_semantic_segmentation': 'run the script to evaluate PQ metric for semantic segmentation predictions on a dataset like ADE20K', 'pq_compute_single_image': 'compute PQ statistics for a single image by comparing ground truth and predicted segmentation masks', 'default_argument_parser': 'create an argument parser with dataset name and JSON file path options for PQ evaluation', 'calculate_miou': 'calculate mean IoU from the confusion matrix between ground truth and predicted semantic segmentation labels', 'pq_stat_pq_average': 'compute average PQ, SQ, and RQ metrics across all categories using the PQStat object'}
```

