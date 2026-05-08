# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/perf/performance_report.py

Prompts

```
['use PerformanceReport as a context manager to measure wall, CPU, and CUDA time for a named block of code', 'run the compare CLI command to diff a target performance report JSON against a baseline report JSON', 'create an Environment dataclass to capture PyTorch version, GPU/CPU info, and installed library versions', 'use MeasurementStats to collect samples and compute min, max, mean, median, and standard deviation', 'call Environment.compare to find added, removed, changed, and unchanged attributes between two environment snapshots', 'run the pytest test_pretrained_models to benchmark inference performance across all pretrained MLIP models', 'generate a list of InferenceTestCase objects for each pretrained model and available device combination', 'create a MeanConvergenceChecker instance to track convergence of mean measurement values over repeated samples', 'check if a MeanConvergenceChecker has converged by calling is_converged after adding measurements', 'review the InferenceTestCase dataclass that stores model name, device, and ASE atoms structures for inference tests']
```

Usage

```
{'measure_performance_with_context_manager': 'use PerformanceReport as a context manager to measure wall, CPU, and CUDA time for a named block of code', 'compare_two_performance_reports': 'run the compare CLI command to diff a target performance report JSON against a baseline report JSON', 'get_environment_snapshot': 'create an Environment dataclass to capture PyTorch version, GPU/CPU info, and installed library versions', 'calculate_measurement_statistics': 'use MeasurementStats to collect samples and compute min, max, mean, median, and standard deviation', 'compare_environment_changes': 'call Environment.compare to find added, removed, changed, and unchanged attributes between two environment snapshots'}
```

## File: facebookresearch_fairchem/tests/perf/test_inference.py

Prompts

```
['use PerformanceReport as a context manager to measure wall, CPU, and CUDA time for a named block of code', 'run the compare CLI command to diff a target performance report JSON against a baseline report JSON', 'create an Environment dataclass to capture PyTorch version, GPU/CPU info, and installed library versions', 'use MeasurementStats to collect samples and compute min, max, mean, median, and standard deviation', 'call Environment.compare to find added, removed, changed, and unchanged attributes between two environment snapshots', 'run the pytest test_pretrained_models to benchmark inference performance across all pretrained MLIP models', 'generate a list of InferenceTestCase objects for each pretrained model and available device combination', 'create a MeanConvergenceChecker instance to track convergence of mean measurement values over repeated samples', 'check if a MeanConvergenceChecker has converged by calling is_converged after adding measurements', 'review the InferenceTestCase dataclass that stores model name, device, and ASE atoms structures for inference tests']
```

Usage

```
{'run_pretrained_model_inference_tests': 'run the pytest test_pretrained_models to benchmark inference performance across all pretrained MLIP models', 'generate_inference_test_cases': 'generate a list of InferenceTestCase objects for each pretrained model and available device combination', 'create_mean_convergence_checker': 'create a MeanConvergenceChecker instance to track convergence of mean measurement values over repeated samples', 'check_convergence_with_mean_convergence_checker': 'check if a MeanConvergenceChecker has converged by calling is_converged after adding measurements', 'review_inference_test_case_dataclass': 'review the InferenceTestCase dataclass that stores model name, device, and ASE atoms structures for inference tests'}
```

