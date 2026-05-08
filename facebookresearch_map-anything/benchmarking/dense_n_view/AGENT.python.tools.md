# Agent Python Tools

- repo: facebookresearch/map-anything
- repo_uri: https://github.com/facebookresearch/map-anything

## File: facebookresearch_map-anything/benchmarking/dense_n_view/benchmark.py

Prompts

```
['run the dense multi-view metric reconstruction benchmark using hydra config', 'build a test data loader for a specified dataset with batch size and workers', 'compute normalized ground truth and prediction info for metric evaluation across views', 'evaluate and save per-scene and per-dataset benchmark results as JSON files', 'review the benchmark function that runs inference and computes reconstruction metrics', 'run the benchmark script to evaluate predicted metric global pointmaps across multiple datasets using Hydra config', 'build a test data loader for a specified dataset with configurable batch size and worker count', 'get normalized ground truth and predicted point cloud information for metric computation across all views', 'review the benchmark function that computes metric scale absolute relative error and pointmap inlier thresholds', 'summarize the Hydra entry point that redirects stdout to logger and runs the benchmark with structured config']
```

Usage

```
{'run_dense_n_view_benchmark': 'run the dense multi-view metric reconstruction benchmark using hydra config', 'build_test_dataset_loader': 'build a test data loader for a specified dataset with batch size and workers', 'compute_metric_info': 'compute normalized ground truth and prediction info for metric evaluation across views', 'evaluate_benchmark_results': 'evaluate and save per-scene and per-dataset benchmark results as JSON files', 'review_benchmark_function': 'review the benchmark function that runs inference and computes reconstruction metrics'}
```

## File: facebookresearch_map-anything/benchmarking/dense_n_view/benchmark_global_pm_only.py

Prompts

```
['run the dense multi-view metric reconstruction benchmark using hydra config', 'build a test data loader for a specified dataset with batch size and workers', 'compute normalized ground truth and prediction info for metric evaluation across views', 'evaluate and save per-scene and per-dataset benchmark results as JSON files', 'review the benchmark function that runs inference and computes reconstruction metrics', 'run the benchmark script to evaluate predicted metric global pointmaps across multiple datasets using Hydra config', 'build a test data loader for a specified dataset with configurable batch size and worker count', 'get normalized ground truth and predicted point cloud information for metric computation across all views', 'review the benchmark function that computes metric scale absolute relative error and pointmap inlier thresholds', 'summarize the Hydra entry point that redirects stdout to logger and runs the benchmark with structured config']
```

Usage

```
{'run_benchmark_global_pm_only': 'run the benchmark script to evaluate predicted metric global pointmaps across multiple datasets using Hydra config', 'build_dataset_loader': 'build a test data loader for a specified dataset with configurable batch size and worker count', 'get_all_info_for_metric_computation': 'get normalized ground truth and predicted point cloud information for metric computation across all views', 'review_benchmark_metrics': 'review the benchmark function that computes metric scale absolute relative error and pointmap inlier thresholds', 'summarize_execute_benchmarking': 'summarize the Hydra entry point that redirects stdout to logger and runs the benchmark with structured config'}
```

