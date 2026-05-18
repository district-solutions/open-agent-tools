# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/core/evaluation/indoor_eval.py

Prompts

```
['calculate average precision from recall and precision arrays using area or 11points mode', 'evaluate precision recall and average precision for a single object detection class against ground truth', 'evaluate mean average precision and recall across multiple object detection classes and IoU thresholds', 'run indoor 3D object detection evaluation and print an ASCII table of AP and AR metrics', 'refactor the average_precision function to support additional precision calculation modes beyond area and 11points', 'run the lyft_eval function to evaluate 3D detection results against Lyft dataset ground truth annotations', 'load ground truth bounding box annotations from the Lyft dataset for a specified evaluation split', 'load Lyft detection predictions from a JSON result file and return a flat list of prediction dicts', 'compute per-class average precision across multiple IoU thresholds for 3D object detection on Lyft data', 'compute recall, precision, and average precision for a single class across multiple IoU thresholds']
```

Usage

```
{'calculate_average_precision': 'calculate average precision from recall and precision arrays using area or 11points mode', 'evaluate_detection_per_class': 'evaluate precision recall and average precision for a single object detection class against ground truth', 'evaluate_map_recall': 'evaluate mean average precision and recall across multiple object detection classes and IoU thresholds', 'run_indoor_evaluation': 'run indoor 3D object detection evaluation and print an ASCII table of AP and AR metrics', 'refactor_average_precision': 'refactor the average_precision function to support additional precision calculation modes beyond area and 11points'}
```

## File: facebookresearch_nerf-det/mmdet3d/core/evaluation/lyft_eval.py

Prompts

```
['calculate average precision from recall and precision arrays using area or 11points mode', 'evaluate precision recall and average precision for a single object detection class against ground truth', 'evaluate mean average precision and recall across multiple object detection classes and IoU thresholds', 'run indoor 3D object detection evaluation and print an ASCII table of AP and AR metrics', 'refactor the average_precision function to support additional precision calculation modes beyond area and 11points', 'run the lyft_eval function to evaluate 3D detection results against Lyft dataset ground truth annotations', 'load ground truth bounding box annotations from the Lyft dataset for a specified evaluation split', 'load Lyft detection predictions from a JSON result file and return a flat list of prediction dicts', 'compute per-class average precision across multiple IoU thresholds for 3D object detection on Lyft data', 'compute recall, precision, and average precision for a single class across multiple IoU thresholds']
```

Usage

```
{'run_lyft_eval': 'run the lyft_eval function to evaluate 3D detection results against Lyft dataset ground truth annotations', 'load_lyft_gts': 'load ground truth bounding box annotations from the Lyft dataset for a specified evaluation split', 'load_lyft_predictions': 'load Lyft detection predictions from a JSON result file and return a flat list of prediction dicts', 'get_classwise_aps': 'compute per-class average precision across multiple IoU thresholds for 3D object detection on Lyft data', 'get_single_class_aps': 'compute recall, precision, and average precision for a single class across multiple IoU thresholds'}
```

