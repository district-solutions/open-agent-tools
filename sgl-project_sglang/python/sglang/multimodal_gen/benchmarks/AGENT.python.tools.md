# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/benchmarks/bench_offline_throughput.py

Prompts

```
['run offline throughput benchmark for multimodal generation models with CLI arguments for model path, dataset, and resolution', 'test the throughput_test function with server_args and bench_args to benchmark diffusion model generation throughput', 'test the generate_batch function to synchronously generate images or videos from a list of prompts', 'test the calculate_metrics function to compute throughput metrics like frames/sec and megapixels/sec from batch outputs', 'test the save_results function to append benchmark results as JSON to an output file', 'run a benchmark against a sglang diffusion model serving endpoint with vbench dataset', 'test the benchmark module with random dataset and custom concurrency settings', 'build a CLI benchmark runner for text-to-image and text-to-video sglang serving endpoints', 'review the calculate_metrics function that computes throughput latency percentiles and SLO attainment', 'summarize how SLO base latency is inferred from warmup requests and scaled per-prompt', 'compare sglang diffusion benchmark JSON files and print a markdown performance comparison report', 'calculate the absolute and percentage difference between two benchmark performance values', 'determine a performance status emoji based on baseline and new values with configurable tolerances', 'aggregate repeating denoising steps into grouped stages and return durations, names, and counts', 'run the compare_perf CLI to compare two or more sglang diffusion benchmark JSON files', 'create a VBenchDataset that loads text-to-video or image-to-video prompts from the VBench benchmark dataset', 'build a RandomDataset that generates N random prompts for benchmarking diffusion models', 'test the RequestFuncInput dataclass with prompt, dimensions, and image paths for a benchmark request', 'create a RequestFuncOutput capturing latency, success status, and error details from a benchmark request', 'summarize how BaseDataset.get_requests iterates all items and returns a list of RequestFuncInput objects']
```

Usage

```
{'run_bench_offline_throughput': 'run offline throughput benchmark for multimodal generation models with CLI arguments for model path, dataset, and resolution', 'test_throughput_test': 'test the throughput_test function with server_args and bench_args to benchmark diffusion model generation throughput', 'test_generate_batch': 'test the generate_batch function to synchronously generate images or videos from a list of prompts', 'test_calculate_metrics': 'test the calculate_metrics function to compute throughput metrics like frames/sec and megapixels/sec from batch outputs', 'test_save_results': 'test the save_results function to append benchmark results as JSON to an output file'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/benchmarks/bench_serving.py

Prompts

```
['run offline throughput benchmark for multimodal generation models with CLI arguments for model path, dataset, and resolution', 'test the throughput_test function with server_args and bench_args to benchmark diffusion model generation throughput', 'test the generate_batch function to synchronously generate images or videos from a list of prompts', 'test the calculate_metrics function to compute throughput metrics like frames/sec and megapixels/sec from batch outputs', 'test the save_results function to append benchmark results as JSON to an output file', 'run a benchmark against a sglang diffusion model serving endpoint with vbench dataset', 'test the benchmark module with random dataset and custom concurrency settings', 'build a CLI benchmark runner for text-to-image and text-to-video sglang serving endpoints', 'review the calculate_metrics function that computes throughput latency percentiles and SLO attainment', 'summarize how SLO base latency is inferred from warmup requests and scaled per-prompt', 'compare sglang diffusion benchmark JSON files and print a markdown performance comparison report', 'calculate the absolute and percentage difference between two benchmark performance values', 'determine a performance status emoji based on baseline and new values with configurable tolerances', 'aggregate repeating denoising steps into grouped stages and return durations, names, and counts', 'run the compare_perf CLI to compare two or more sglang diffusion benchmark JSON files', 'create a VBenchDataset that loads text-to-video or image-to-video prompts from the VBench benchmark dataset', 'build a RandomDataset that generates N random prompts for benchmarking diffusion models', 'test the RequestFuncInput dataclass with prompt, dimensions, and image paths for a benchmark request', 'create a RequestFuncOutput capturing latency, success status, and error details from a benchmark request', 'summarize how BaseDataset.get_requests iterates all items and returns a list of RequestFuncInput objects']
```

Usage

```
{'run_bench_serving': 'run a benchmark against a sglang diffusion model serving endpoint with vbench dataset', 'test_bench_serving': 'test the benchmark module with random dataset and custom concurrency settings', 'build_bench_cli': 'build a CLI benchmark runner for text-to-image and text-to-video sglang serving endpoints', 'review_calculate_metrics': 'review the calculate_metrics function that computes throughput latency percentiles and SLO attainment', 'summarize_slo_inference': 'summarize how SLO base latency is inferred from warmup requests and scaled per-prompt'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/benchmarks/compare_perf.py

Prompts

```
['run offline throughput benchmark for multimodal generation models with CLI arguments for model path, dataset, and resolution', 'test the throughput_test function with server_args and bench_args to benchmark diffusion model generation throughput', 'test the generate_batch function to synchronously generate images or videos from a list of prompts', 'test the calculate_metrics function to compute throughput metrics like frames/sec and megapixels/sec from batch outputs', 'test the save_results function to append benchmark results as JSON to an output file', 'run a benchmark against a sglang diffusion model serving endpoint with vbench dataset', 'test the benchmark module with random dataset and custom concurrency settings', 'build a CLI benchmark runner for text-to-image and text-to-video sglang serving endpoints', 'review the calculate_metrics function that computes throughput latency percentiles and SLO attainment', 'summarize how SLO base latency is inferred from warmup requests and scaled per-prompt', 'compare sglang diffusion benchmark JSON files and print a markdown performance comparison report', 'calculate the absolute and percentage difference between two benchmark performance values', 'determine a performance status emoji based on baseline and new values with configurable tolerances', 'aggregate repeating denoising steps into grouped stages and return durations, names, and counts', 'run the compare_perf CLI to compare two or more sglang diffusion benchmark JSON files', 'create a VBenchDataset that loads text-to-video or image-to-video prompts from the VBench benchmark dataset', 'build a RandomDataset that generates N random prompts for benchmarking diffusion models', 'test the RequestFuncInput dataclass with prompt, dimensions, and image paths for a benchmark request', 'create a RequestFuncOutput capturing latency, success status, and error details from a benchmark request', 'summarize how BaseDataset.get_requests iterates all items and returns a list of RequestFuncInput objects']
```

Usage

```
{'compare_benchmarks_files': 'compare sglang diffusion benchmark JSON files and print a markdown performance comparison report', 'calculate_diff_base_new': 'calculate the absolute and percentage difference between two benchmark performance values', 'get_perf_status_emoji_baseline_new': 'determine a performance status emoji based on baseline and new values with configurable tolerances', 'consolidate_steps_steps_list': 'aggregate repeating denoising steps into grouped stages and return durations, names, and counts', 'run_compare_perf_cli': 'run the compare_perf CLI to compare two or more sglang diffusion benchmark JSON files'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/benchmarks/datasets.py

Prompts

```
['run offline throughput benchmark for multimodal generation models with CLI arguments for model path, dataset, and resolution', 'test the throughput_test function with server_args and bench_args to benchmark diffusion model generation throughput', 'test the generate_batch function to synchronously generate images or videos from a list of prompts', 'test the calculate_metrics function to compute throughput metrics like frames/sec and megapixels/sec from batch outputs', 'test the save_results function to append benchmark results as JSON to an output file', 'run a benchmark against a sglang diffusion model serving endpoint with vbench dataset', 'test the benchmark module with random dataset and custom concurrency settings', 'build a CLI benchmark runner for text-to-image and text-to-video sglang serving endpoints', 'review the calculate_metrics function that computes throughput latency percentiles and SLO attainment', 'summarize how SLO base latency is inferred from warmup requests and scaled per-prompt', 'compare sglang diffusion benchmark JSON files and print a markdown performance comparison report', 'calculate the absolute and percentage difference between two benchmark performance values', 'determine a performance status emoji based on baseline and new values with configurable tolerances', 'aggregate repeating denoising steps into grouped stages and return durations, names, and counts', 'run the compare_perf CLI to compare two or more sglang diffusion benchmark JSON files', 'create a VBenchDataset that loads text-to-video or image-to-video prompts from the VBench benchmark dataset', 'build a RandomDataset that generates N random prompts for benchmarking diffusion models', 'test the RequestFuncInput dataclass with prompt, dimensions, and image paths for a benchmark request', 'create a RequestFuncOutput capturing latency, success status, and error details from a benchmark request', 'summarize how BaseDataset.get_requests iterates all items and returns a list of RequestFuncInput objects']
```

Usage

```
{'create_vbench_dataset': 'create a VBenchDataset that loads text-to-video or image-to-video prompts from the VBench benchmark dataset', 'build_random_dataset': 'build a RandomDataset that generates N random prompts for benchmarking diffusion models', 'test_request_func_input': 'test the RequestFuncInput dataclass with prompt, dimensions, and image paths for a benchmark request', 'create_request_output': 'create a RequestFuncOutput capturing latency, success status, and error details from a benchmark request', 'summarize_get_requests': 'summarize how BaseDataset.get_requests iterates all items and returns a list of RequestFuncInput objects'}
```

