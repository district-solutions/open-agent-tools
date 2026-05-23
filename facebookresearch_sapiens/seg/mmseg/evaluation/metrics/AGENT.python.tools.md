# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/seg/mmseg/evaluation/metrics/citys_metric.py

Prompts

```
['build a CityscapesMetric evaluator instance with output_dir and format_only settings for semantic segmentation evaluation', 'run the process method to save predicted segmentation labels as PNG files for Cityscapes evaluation', 'test the compute_metrics method to evaluate segmentation results using official Cityscapes evaluation scripts', 'review the _convert_to_label_id static method that converts trainId labels to Cityscapes label IDs', 'refactor the CityscapesMetric constructor to customize ignore_index, keep_results, and collect_device parameters', 'create a DepthMetric instance to evaluate monocular depth estimation predictions against ground truth', 'compute d1, d2, d3, abs_rel, sq_rel, rmse, rmse_log, log10, and silog metrics from depth results', 'process a batch of predicted and ground truth depth maps and store masked results for evaluation', 'generate an evaluation mask using min/max depth bounds and optional NYU crop region', 'save predicted depth maps as 16-bit PNG files to an output directory with configurable scale factor', 'build an IoUMetric evaluator to calculate mIoU, mDice, and mFscore for semantic segmentation', 'process a batch of model predictions and ground truth labels to compute intersection and union', 'compute per class and overall segmentation metrics including accuracy, IoU, Dice, and F-score', 'calculate intersection and union histograms between predicted and ground truth segmentation masks', 'convert total area intersect, union, and label arrays into IoU, Dice, and F-score metrics']
```

Usage

```
{'build_CityscapesMetric': 'build a CityscapesMetric evaluator instance with output_dir and format_only settings for semantic segmentation evaluation', 'run_process_batch': 'run the process method to save predicted segmentation labels as PNG files for Cityscapes evaluation', 'test_compute_metrics': 'test the compute_metrics method to evaluate segmentation results using official Cityscapes evaluation scripts', 'review_convert_to_label_id': 'review the _convert_to_label_id static method that converts trainId labels to Cityscapes label IDs', 'refactor_CityscapesMetric_init': 'refactor the CityscapesMetric constructor to customize ignore_index, keep_results, and collect_device parameters'}
```

## File: facebookresearch_sapiens/seg/mmseg/evaluation/metrics/depth_metric.py

Prompts

```
['build a CityscapesMetric evaluator instance with output_dir and format_only settings for semantic segmentation evaluation', 'run the process method to save predicted segmentation labels as PNG files for Cityscapes evaluation', 'test the compute_metrics method to evaluate segmentation results using official Cityscapes evaluation scripts', 'review the _convert_to_label_id static method that converts trainId labels to Cityscapes label IDs', 'refactor the CityscapesMetric constructor to customize ignore_index, keep_results, and collect_device parameters', 'create a DepthMetric instance to evaluate monocular depth estimation predictions against ground truth', 'compute d1, d2, d3, abs_rel, sq_rel, rmse, rmse_log, log10, and silog metrics from depth results', 'process a batch of predicted and ground truth depth maps and store masked results for evaluation', 'generate an evaluation mask using min/max depth bounds and optional NYU crop region', 'save predicted depth maps as 16-bit PNG files to an output directory with configurable scale factor', 'build an IoUMetric evaluator to calculate mIoU, mDice, and mFscore for semantic segmentation', 'process a batch of model predictions and ground truth labels to compute intersection and union', 'compute per class and overall segmentation metrics including accuracy, IoU, Dice, and F-score', 'calculate intersection and union histograms between predicted and ground truth segmentation masks', 'convert total area intersect, union, and label arrays into IoU, Dice, and F-score metrics']
```

Usage

```
{'create_depth_metric_evaluator': 'create a DepthMetric instance to evaluate monocular depth estimation predictions against ground truth', 'compute_depth_metrics': 'compute d1, d2, d3, abs_rel, sq_rel, rmse, rmse_log, log10, and silog metrics from depth results', 'process_depth_batch': 'process a batch of predicted and ground truth depth maps and store masked results for evaluation', 'generate_eval_mask': 'generate an evaluation mask using min/max depth bounds and optional NYU crop region', 'save_depth_predictions': 'save predicted depth maps as 16-bit PNG files to an output directory with configurable scale factor'}
```

## File: facebookresearch_sapiens/seg/mmseg/evaluation/metrics/iou_metric.py

Prompts

```
['build a CityscapesMetric evaluator instance with output_dir and format_only settings for semantic segmentation evaluation', 'run the process method to save predicted segmentation labels as PNG files for Cityscapes evaluation', 'test the compute_metrics method to evaluate segmentation results using official Cityscapes evaluation scripts', 'review the _convert_to_label_id static method that converts trainId labels to Cityscapes label IDs', 'refactor the CityscapesMetric constructor to customize ignore_index, keep_results, and collect_device parameters', 'create a DepthMetric instance to evaluate monocular depth estimation predictions against ground truth', 'compute d1, d2, d3, abs_rel, sq_rel, rmse, rmse_log, log10, and silog metrics from depth results', 'process a batch of predicted and ground truth depth maps and store masked results for evaluation', 'generate an evaluation mask using min/max depth bounds and optional NYU crop region', 'save predicted depth maps as 16-bit PNG files to an output directory with configurable scale factor', 'build an IoUMetric evaluator to calculate mIoU, mDice, and mFscore for semantic segmentation', 'process a batch of model predictions and ground truth labels to compute intersection and union', 'compute per class and overall segmentation metrics including accuracy, IoU, Dice, and F-score', 'calculate intersection and union histograms between predicted and ground truth segmentation masks', 'convert total area intersect, union, and label arrays into IoU, Dice, and F-score metrics']
```

Usage

```
{'build_iou_metric_evaluator': 'build an IoUMetric evaluator to calculate mIoU, mDice, and mFscore for semantic segmentation', 'process_batch_predictions': 'process a batch of model predictions and ground truth labels to compute intersection and union', 'compute_segmentation_metrics': 'compute per class and overall segmentation metrics including accuracy, IoU, Dice, and F-score', 'calculate_intersect_and_union': 'calculate intersection and union histograms between predicted and ground truth segmentation masks', 'convert_areas_to_metrics': 'convert total area intersect, union, and label arrays into IoU, Dice, and F-score metrics'}
```

