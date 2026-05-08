# Agent Python Tools

- repo: facebookresearch/maskformer
- repo_uri: https://github.com/facebookresearch/maskformer

## File: facebookresearch_maskformer/tools/analyze_model.py

Prompts

```
['run flop count analysis on a detectron2 model using a config file and test data', 'run activation count analysis on a detectron2 model to measure operator activations across inputs', 'run parameter count analysis on a detectron2 model and print the parameter count table', 'run model structure analysis on a detectron2 model and print the full model architecture', 'setup and load a detectron2 config from a YAML or LazyConfig file with mask former support', 'run the PQ evaluation CLI tool to compute panoptic quality metrics for semantic segmentation predictions on a dataset', 'run the evaluation script to calculate mean IoU from a COCO-style JSON predictions file against ground truth', 'compute panoptic quality statistics for a single image by comparing ground truth and predicted segmentation masks', 'create an argument parser with dataset name and JSON file path options for semantic segmentation evaluation', 'calculate a confusion matrix from ground truth and predicted segmentations and derive per-class and mean IoU']
```

Usage

```
{'run_flop_analysis': 'run flop count analysis on a detectron2 model using a config file and test data', 'run_activation_analysis': 'run activation count analysis on a detectron2 model to measure operator activations across inputs', 'run_parameter_count': 'run parameter count analysis on a detectron2 model and print the parameter count table', 'run_structure_analysis': 'run model structure analysis on a detectron2 model and print the full model architecture', 'setup_config': 'setup and load a detectron2 config from a YAML or LazyConfig file with mask former support'}
```

## File: facebookresearch_maskformer/tools/evaluate_pq_for_semantic_segmentation.py

Prompts

```
['run flop count analysis on a detectron2 model using a config file and test data', 'run activation count analysis on a detectron2 model to measure operator activations across inputs', 'run parameter count analysis on a detectron2 model and print the parameter count table', 'run model structure analysis on a detectron2 model and print the full model architecture', 'setup and load a detectron2 config from a YAML or LazyConfig file with mask former support', 'run the PQ evaluation CLI tool to compute panoptic quality metrics for semantic segmentation predictions on a dataset', 'run the evaluation script to calculate mean IoU from a COCO-style JSON predictions file against ground truth', 'compute panoptic quality statistics for a single image by comparing ground truth and predicted segmentation masks', 'create an argument parser with dataset name and JSON file path options for semantic segmentation evaluation', 'calculate a confusion matrix from ground truth and predicted segmentations and derive per-class and mean IoU']
```

Usage

```
{'run_pq_evaluation_cli': 'run the PQ evaluation CLI tool to compute panoptic quality metrics for semantic segmentation predictions on a dataset', 'run_mIoU_evaluation': 'run the evaluation script to calculate mean IoU from a COCO-style JSON predictions file against ground truth', 'compute_pq_single_image': 'compute panoptic quality statistics for a single image by comparing ground truth and predicted segmentation masks', 'create_argparse_parser': 'create an argument parser with dataset name and JSON file path options for semantic segmentation evaluation', 'calculate_confusion_matrix_miou': 'calculate a confusion matrix from ground truth and predicted segmentations and derive per-class and mean IoU'}
```

