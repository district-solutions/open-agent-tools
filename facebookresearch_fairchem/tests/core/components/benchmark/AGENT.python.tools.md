# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/core/components/benchmark/test_perf_check.py

Prompts

```
['run the PerfCheckRunner to benchmark a checkpoint against fp64 baseline and save a JSON report', 'run inference on a benchmark system with a checkpoint and measure QPS and GPU memory', 'test the compare_results function to compute energy, force, and stress error metrics between baseline and candidate', 'test the format_report_table function to format benchmark results as a human-readable table string', 'test the PerfCheckRunner to verify OOM errors are caught and non-OOM errors propagate correctly', 'create a benchmark system with an FCC lattice of 200 atoms for the omat task', 'create a water box benchmark system with 20 molecules for the omol task', 'test a slab adsorbate benchmark system with OC20-style tags and FixAtoms constraints', 'get the default list of benchmark systems including small molecule and bulk variants', 'create a batch of benchmark systems with variable atom counts like 10, 50, and 100', 'run a training benchmark comparing fp32 baseline against bf16 candidate settings and return fidelity metrics', 'test the training benchmark smoke test that validates run_training_benchmark returns positive steps per second', 'create a TrainingBenchmarkResult dataclass with loss error, gradient norm error, throughput, and memory metrics', 'review the BenchmarkTrainCallback class that captures per-step losses, grad norms, and timing during training', 'run the TrainingBenchmarkRunner via fairchem CLI to benchmark training fidelity and save a JSON report']
```

Usage

```
{'run_PerfCheckRunner': 'run the PerfCheckRunner to benchmark a checkpoint against fp64 baseline and save a JSON report', 'run_run_inference': 'run inference on a benchmark system with a checkpoint and measure QPS and GPU memory', 'test_compare_results': 'test the compare_results function to compute energy, force, and stress error metrics between baseline and candidate', 'test_format_report_table': 'test the format_report_table function to format benchmark results as a human-readable table string', 'test_PerfCheckRunner_OOM': 'test the PerfCheckRunner to verify OOM errors are caught and non-OOM errors propagate correctly'}
```

## File: facebookresearch_fairchem/tests/core/components/benchmark/test_systems.py

Prompts

```
['run the PerfCheckRunner to benchmark a checkpoint against fp64 baseline and save a JSON report', 'run inference on a benchmark system with a checkpoint and measure QPS and GPU memory', 'test the compare_results function to compute energy, force, and stress error metrics between baseline and candidate', 'test the format_report_table function to format benchmark results as a human-readable table string', 'test the PerfCheckRunner to verify OOM errors are caught and non-OOM errors propagate correctly', 'create a benchmark system with an FCC lattice of 200 atoms for the omat task', 'create a water box benchmark system with 20 molecules for the omol task', 'test a slab adsorbate benchmark system with OC20-style tags and FixAtoms constraints', 'get the default list of benchmark systems including small molecule and bulk variants', 'create a batch of benchmark systems with variable atom counts like 10, 50, and 100', 'run a training benchmark comparing fp32 baseline against bf16 candidate settings and return fidelity metrics', 'test the training benchmark smoke test that validates run_training_benchmark returns positive steps per second', 'create a TrainingBenchmarkResult dataclass with loss error, gradient norm error, throughput, and memory metrics', 'review the BenchmarkTrainCallback class that captures per-step losses, grad norms, and timing during training', 'run the TrainingBenchmarkRunner via fairchem CLI to benchmark training fidelity and save a JSON report']
```

Usage

```
{'create_benchmark_system_fcc': 'create a benchmark system with an FCC lattice of 200 atoms for the omat task', 'create_benchmark_system_water': 'create a water box benchmark system with 20 molecules for the omol task', 'test_slab_adsorbate_system': 'test a slab adsorbate benchmark system with OC20-style tags and FixAtoms constraints', 'get_default_benchmark_systems': 'get the default list of benchmark systems including small molecule and bulk variants', 'create_variable_size_batch': 'create a batch of benchmark systems with variable atom counts like 10, 50, and 100'}
```

## File: facebookresearch_fairchem/tests/core/components/benchmark/test_training.py

Prompts

```
['run the PerfCheckRunner to benchmark a checkpoint against fp64 baseline and save a JSON report', 'run inference on a benchmark system with a checkpoint and measure QPS and GPU memory', 'test the compare_results function to compute energy, force, and stress error metrics between baseline and candidate', 'test the format_report_table function to format benchmark results as a human-readable table string', 'test the PerfCheckRunner to verify OOM errors are caught and non-OOM errors propagate correctly', 'create a benchmark system with an FCC lattice of 200 atoms for the omat task', 'create a water box benchmark system with 20 molecules for the omol task', 'test a slab adsorbate benchmark system with OC20-style tags and FixAtoms constraints', 'get the default list of benchmark systems including small molecule and bulk variants', 'create a batch of benchmark systems with variable atom counts like 10, 50, and 100', 'run a training benchmark comparing fp32 baseline against bf16 candidate settings and return fidelity metrics', 'test the training benchmark smoke test that validates run_training_benchmark returns positive steps per second', 'create a TrainingBenchmarkResult dataclass with loss error, gradient norm error, throughput, and memory metrics', 'review the BenchmarkTrainCallback class that captures per-step losses, grad norms, and timing during training', 'run the TrainingBenchmarkRunner via fairchem CLI to benchmark training fidelity and save a JSON report']
```

Usage

```
{'run_training_benchmark': 'run a training benchmark comparing fp32 baseline against bf16 candidate settings and return fidelity metrics', 'test_training_benchmark_smoke': 'test the training benchmark smoke test that validates run_training_benchmark returns positive steps per second', 'create_TrainingBenchmarkResult': 'create a TrainingBenchmarkResult dataclass with loss error, gradient norm error, throughput, and memory metrics', 'review_BenchmarkTrainCallback': 'review the BenchmarkTrainCallback class that captures per-step losses, grad norms, and timing during training', 'run_TrainingBenchmarkRunner': 'run the TrainingBenchmarkRunner via fairchem CLI to benchmark training fidelity and save a JSON report'}
```

