# Agent Python Tools

- repo: facebookresearch/map-anything
- repo_uri: https://github.com/facebookresearch/map-anything

## File: facebookresearch_map-anything/benchmarking/calibration/benchmark.py

Prompts

```
['run the image calibration benchmark script with hydra config to evaluate model performance', 'build a PyTorch data loader for testing using get_test_many_ar_data_loader with batch size and workers', 'extract ground truth and predicted ray directions from batch and predictions for metric computation', 'compute the L2 distance of unit ray directions and convert it to angular error in degrees', 'aggregate per scene and per dataset benchmark results and save them as JSON files']
```

Usage

```
{'run_calibration_benchmark': 'run the image calibration benchmark script with hydra config to evaluate model performance', 'build_test_dataset_loader': 'build a PyTorch data loader for testing using get_test_many_ar_data_loader with batch size and workers', 'extract_metric_info': 'extract ground truth and predicted ray directions from batch and predictions for metric computation', 'compute_angular_error': 'compute the L2 distance of unit ray directions and convert it to angular error in degrees', 'aggregate_benchmark_results': 'aggregate per scene and per dataset benchmark results and save them as JSON files'}
```

