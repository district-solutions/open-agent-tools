# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/benchmark_v2/framework/benchmark_config.py

Prompts

```
['create a BenchmarkConfig with custom batch size, sequence length, and attention implementation', 'build a suite of benchmark configs using get_config_by_level with different optimization levels', 'adapt a list of benchmark configs by varying batch size, sequence length, and iteration counts', 'test a BenchmarkConfig and verify its validity with automatic fallbacks for unsupported combinations', 'summarize a BenchmarkConfig by converting it to a dictionary or inferred human-readable name', 'create a HardwareInfo instance to retrieve GPU name, memory, Python version, Torch version, CPU count, and RAM', 'get the device name and total memory in GB of GPU 0 using PyTorch accelerator properties', 'get NVIDIA GPU utilization percentage and memory used in GB using pynvml device handle', 'get AMD GPU utilization percentage and VRAM used in GB using amdsmi device handle', 'run a GPUMonitor to collect GPU utilization and memory samples in a separate process during benchmark execution']
```

Usage

```
{'create_benchmark_config': 'create a BenchmarkConfig with custom batch size, sequence length, and attention implementation', 'build_benchmark_suite': 'build a suite of benchmark configs using get_config_by_level with different optimization levels', 'adapt_benchmark_configs': 'adapt a list of benchmark configs by varying batch size, sequence length, and iteration counts', 'test_benchmark_validity': 'test a BenchmarkConfig and verify its validity with automatic fallbacks for unsupported combinations', 'summarize_benchmark_config': 'summarize a BenchmarkConfig by converting it to a dictionary or inferred human-readable name'}
```

## File: huggingface_transformers/benchmark_v2/framework/hardware_metrics.py

Prompts

```
['create a BenchmarkConfig with custom batch size, sequence length, and attention implementation', 'build a suite of benchmark configs using get_config_by_level with different optimization levels', 'adapt a list of benchmark configs by varying batch size, sequence length, and iteration counts', 'test a BenchmarkConfig and verify its validity with automatic fallbacks for unsupported combinations', 'summarize a BenchmarkConfig by converting it to a dictionary or inferred human-readable name', 'create a HardwareInfo instance to retrieve GPU name, memory, Python version, Torch version, CPU count, and RAM', 'get the device name and total memory in GB of GPU 0 using PyTorch accelerator properties', 'get NVIDIA GPU utilization percentage and memory used in GB using pynvml device handle', 'get AMD GPU utilization percentage and VRAM used in GB using amdsmi device handle', 'run a GPUMonitor to collect GPU utilization and memory samples in a separate process during benchmark execution']
```

Usage

```
{'create_hardware_info': 'create a HardwareInfo instance to retrieve GPU name, memory, Python version, Torch version, CPU count, and RAM', 'get_device_name_and_memory': 'get the device name and total memory in GB of GPU 0 using PyTorch accelerator properties', 'get_nvidia_gpu_stats': 'get NVIDIA GPU utilization percentage and memory used in GB using pynvml device handle', 'get_amd_gpu_stats': 'get AMD GPU utilization percentage and VRAM used in GB using amdsmi device handle', 'run_gpu_monitoring': 'run a GPUMonitor to collect GPU utilization and memory samples in a separate process during benchmark execution'}
```

