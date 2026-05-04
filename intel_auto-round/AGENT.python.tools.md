# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/benchmark_both.py

Prompts

```
['run the A/B benchmark comparing old and new auto_round compressor architectures with interleaved trials', 'run a single auto_round subprocess with custom environment variables and return the elapsed time', 'review the main function that orchestrates warmup runs and interleaved old vs new architecture trials', 'refactor the benchmark command template constants to support a different model or quantization scheme', 'summarize the benchmark results saved to benchmark_results/latest.json with average times and pass fail status', 'run the per-block RSS profiling script to diagnose peak RAM regression during quantization', 'run the per-block RSS profiling script with AR_DISABLE_NEW_ARCH=1 to profile the old architecture', 'measure the current process RSS in MB using psutil without garbage collection', 'measure the current process RSS in MB after running gc.collect and malloc_trim', 'review the per-block RSS log entries showing delta_return and delta_trim memory changes per quantization block', 'build the auto-round package by running python setup.py install from the project root', 'build the auto-round-hpu package by running python setup.py hpu install from the project root', 'get the build version from git tags or PKG-INFO using get_build_version', 'check if HPU hardware is available by calling is_hpu_available in the setup script', 'fetch requirements from a text file by calling fetch_requirements with a file path', 'run the test_mlx_export function to quantize Qwen3-0.6B with W4A16 and save in MLX format', 'run the test_mlx_export_w3a16 function to quantize Qwen3-0.6B with W3A16 and save in MLX format', 'run AutoRound with quantize_and_save to export a model in MLX format with W4A16 quantization', 'verify the quantization_config.json output file contains correct bits group_size and sym settings', 'test loading a quantized MLX model with AutoModelForCausalLM and run a generation inference']
```

Usage

```
{'run_benchmark_old_vs_new_architecture': 'run the A/B benchmark comparing old and new auto_round compressor architectures with interleaved trials', 'run_run_once_subprocess': 'run a single auto_round subprocess with custom environment variables and return the elapsed time', 'review_main_benchmark_orchestration': 'review the main function that orchestrates warmup runs and interleaved old vs new architecture trials', 'refactor_CMD_TEMPLATE_constants': 'refactor the benchmark command template constants to support a different model or quantization scheme', 'summarize_benchmark_results_json': 'summarize the benchmark results saved to benchmark_results/latest.json with average times and pass fail status'}
```

## File: intel_auto-round/profile_rss_per_block.py

Prompts

```
['run the A/B benchmark comparing old and new auto_round compressor architectures with interleaved trials', 'run a single auto_round subprocess with custom environment variables and return the elapsed time', 'review the main function that orchestrates warmup runs and interleaved old vs new architecture trials', 'refactor the benchmark command template constants to support a different model or quantization scheme', 'summarize the benchmark results saved to benchmark_results/latest.json with average times and pass fail status', 'run the per-block RSS profiling script to diagnose peak RAM regression during quantization', 'run the per-block RSS profiling script with AR_DISABLE_NEW_ARCH=1 to profile the old architecture', 'measure the current process RSS in MB using psutil without garbage collection', 'measure the current process RSS in MB after running gc.collect and malloc_trim', 'review the per-block RSS log entries showing delta_return and delta_trim memory changes per quantization block', 'build the auto-round package by running python setup.py install from the project root', 'build the auto-round-hpu package by running python setup.py hpu install from the project root', 'get the build version from git tags or PKG-INFO using get_build_version', 'check if HPU hardware is available by calling is_hpu_available in the setup script', 'fetch requirements from a text file by calling fetch_requirements with a file path', 'run the test_mlx_export function to quantize Qwen3-0.6B with W4A16 and save in MLX format', 'run the test_mlx_export_w3a16 function to quantize Qwen3-0.6B with W3A16 and save in MLX format', 'run AutoRound with quantize_and_save to export a model in MLX format with W4A16 quantization', 'verify the quantization_config.json output file contains correct bits group_size and sym settings', 'test loading a quantized MLX model with AutoModelForCausalLM and run a generation inference']
```

Usage

```
{'run_per_block_rss_profiling': 'run the per-block RSS profiling script to diagnose peak RAM regression during quantization', 'run_rss_profiling_old_arch': 'run the per-block RSS profiling script with AR_DISABLE_NEW_ARCH=1 to profile the old architecture', 'measure_live_rss_mb': 'measure the current process RSS in MB using psutil without garbage collection', 'measure_rss_mb_clean': 'measure the current process RSS in MB after running gc.collect and malloc_trim', 'review_block_rss_log': 'review the per-block RSS log entries showing delta_return and delta_trim memory changes per quantization block'}
```

## File: intel_auto-round/setup.py

Prompts

```
['run the A/B benchmark comparing old and new auto_round compressor architectures with interleaved trials', 'run a single auto_round subprocess with custom environment variables and return the elapsed time', 'review the main function that orchestrates warmup runs and interleaved old vs new architecture trials', 'refactor the benchmark command template constants to support a different model or quantization scheme', 'summarize the benchmark results saved to benchmark_results/latest.json with average times and pass fail status', 'run the per-block RSS profiling script to diagnose peak RAM regression during quantization', 'run the per-block RSS profiling script with AR_DISABLE_NEW_ARCH=1 to profile the old architecture', 'measure the current process RSS in MB using psutil without garbage collection', 'measure the current process RSS in MB after running gc.collect and malloc_trim', 'review the per-block RSS log entries showing delta_return and delta_trim memory changes per quantization block', 'build the auto-round package by running python setup.py install from the project root', 'build the auto-round-hpu package by running python setup.py hpu install from the project root', 'get the build version from git tags or PKG-INFO using get_build_version', 'check if HPU hardware is available by calling is_hpu_available in the setup script', 'fetch requirements from a text file by calling fetch_requirements with a file path', 'run the test_mlx_export function to quantize Qwen3-0.6B with W4A16 and save in MLX format', 'run the test_mlx_export_w3a16 function to quantize Qwen3-0.6B with W3A16 and save in MLX format', 'run AutoRound with quantize_and_save to export a model in MLX format with W4A16 quantization', 'verify the quantization_config.json output file contains correct bits group_size and sym settings', 'test loading a quantized MLX model with AutoModelForCausalLM and run a generation inference']
```

Usage

```
{'build_autoround_package': 'build the auto-round package by running python setup.py install from the project root', 'build_autoround_hpu_package': 'build the auto-round-hpu package by running python setup.py hpu install from the project root', 'get_build_version': 'get the build version from git tags or PKG-INFO using get_build_version', 'check_hpu_availability': 'check if HPU hardware is available by calling is_hpu_available in the setup script', 'fetch_requirements_from_file': 'fetch requirements from a text file by calling fetch_requirements with a file path'}
```

## File: intel_auto-round/test_mlx_export.py

Prompts

```
['run the A/B benchmark comparing old and new auto_round compressor architectures with interleaved trials', 'run a single auto_round subprocess with custom environment variables and return the elapsed time', 'review the main function that orchestrates warmup runs and interleaved old vs new architecture trials', 'refactor the benchmark command template constants to support a different model or quantization scheme', 'summarize the benchmark results saved to benchmark_results/latest.json with average times and pass fail status', 'run the per-block RSS profiling script to diagnose peak RAM regression during quantization', 'run the per-block RSS profiling script with AR_DISABLE_NEW_ARCH=1 to profile the old architecture', 'measure the current process RSS in MB using psutil without garbage collection', 'measure the current process RSS in MB after running gc.collect and malloc_trim', 'review the per-block RSS log entries showing delta_return and delta_trim memory changes per quantization block', 'build the auto-round package by running python setup.py install from the project root', 'build the auto-round-hpu package by running python setup.py hpu install from the project root', 'get the build version from git tags or PKG-INFO using get_build_version', 'check if HPU hardware is available by calling is_hpu_available in the setup script', 'fetch requirements from a text file by calling fetch_requirements with a file path', 'run the test_mlx_export function to quantize Qwen3-0.6B with W4A16 and save in MLX format', 'run the test_mlx_export_w3a16 function to quantize Qwen3-0.6B with W3A16 and save in MLX format', 'run AutoRound with quantize_and_save to export a model in MLX format with W4A16 quantization', 'verify the quantization_config.json output file contains correct bits group_size and sym settings', 'test loading a quantized MLX model with AutoModelForCausalLM and run a generation inference']
```

Usage

```
{'test_mlx_export_w4a16': 'run the test_mlx_export function to quantize Qwen3-0.6B with W4A16 and save in MLX format', 'test_mlx_export_w3a16': 'run the test_mlx_export_w3a16 function to quantize Qwen3-0.6B with W3A16 and save in MLX format', 'run_autoround_quantize_and_save': 'run AutoRound with quantize_and_save to export a model in MLX format with W4A16 quantization', 'verify_mlx_quantization_config': 'verify the quantization_config.json output file contains correct bits group_size and sym settings', 'test_mlx_model_inference': 'test loading a quantized MLX model with AutoModelForCausalLM and run a generation inference'}
```

