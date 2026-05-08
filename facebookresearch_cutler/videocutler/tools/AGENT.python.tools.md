# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/tools/analyze_model.py

Prompts

```
['run flop count analysis on a Detectron2 model using a config file and test data', 'run activation count analysis on a Detectron2 model to measure operator activations', 'run parameter count analysis on a Detectron2 model to show total parameters', 'run model structure analysis to print the Detectron2 model architecture', 'setup a Detectron2 configuration from a YAML or LazyConfig file with overrides', 'run the CLI tool to evaluate PQ and mIoU metrics for semantic segmentation predictions on ADE20K or COCO datasets', 'run pq_compute_single_image to compute panoptic quality statistics for a single ground truth and prediction segmentation pair', 'run default_argument_parser to create an argparse parser with dataset-name and json-file arguments for PQ evaluation', 'review pq_compute_single_image to understand how it calculates true positives, false positives, and false negatives using IoU matching', 'refactor the main evaluation loop to support additional datasets beyond ADE20K and COCO stuff segmentation']
```

Usage

```
{'run_flop_analysis': 'run flop count analysis on a Detectron2 model using a config file and test data', 'run_activation_analysis': 'run activation count analysis on a Detectron2 model to measure operator activations', 'run_parameter_analysis': 'run parameter count analysis on a Detectron2 model to show total parameters', 'run_structure_analysis': 'run model structure analysis to print the Detectron2 model architecture', 'setup_config': 'setup a Detectron2 configuration from a YAML or LazyConfig file with overrides'}
```

## File: facebookresearch_cutler/videocutler/tools/evaluate_pq_for_semantic_segmentation.py

Prompts

```
['run flop count analysis on a Detectron2 model using a config file and test data', 'run activation count analysis on a Detectron2 model to measure operator activations', 'run parameter count analysis on a Detectron2 model to show total parameters', 'run model structure analysis to print the Detectron2 model architecture', 'setup a Detectron2 configuration from a YAML or LazyConfig file with overrides', 'run the CLI tool to evaluate PQ and mIoU metrics for semantic segmentation predictions on ADE20K or COCO datasets', 'run pq_compute_single_image to compute panoptic quality statistics for a single ground truth and prediction segmentation pair', 'run default_argument_parser to create an argparse parser with dataset-name and json-file arguments for PQ evaluation', 'review pq_compute_single_image to understand how it calculates true positives, false positives, and false negatives using IoU matching', 'refactor the main evaluation loop to support additional datasets beyond ADE20K and COCO stuff segmentation']
```

Usage

```
{'run_evaluate_pq_semantic_segmentation': 'run the CLI tool to evaluate PQ and mIoU metrics for semantic segmentation predictions on ADE20K or COCO datasets', 'run_pq_compute_single_image': 'run pq_compute_single_image to compute panoptic quality statistics for a single ground truth and prediction segmentation pair', 'run_default_argument_parser': 'run default_argument_parser to create an argparse parser with dataset-name and json-file arguments for PQ evaluation', 'review_pq_compute_single_image': 'review pq_compute_single_image to understand how it calculates true positives, false positives, and false negatives using IoU matching', 'refactor_evaluate_pq_semantic_segmentation': 'refactor the main evaluation loop to support additional datasets beyond ADE20K and COCO stuff segmentation'}
```

