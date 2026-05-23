# Agent Python Tools

- repo: facebookresearch/torchdim
- repo_uri: https://github.com/facebookresearch/torchdim

## File: facebookresearch_torchdim/third_party/functorch/benchmarks/transformer_fusion_patterns/benchmark.py

Prompts

```
['run the benchmark to profile and time transformer fusion patterns using memory_efficient_fusion', 'run memory_efficient_fusion on a PyTorch function with static argnums to get an optimized fused function', 'run clear_compile_cache to clear the functorch compile cache before benchmarking', 'run profile_cuda_kernels via benchmark_helper to profile eager and AOTAutograd CUDA kernel execution', 'run time_with_torch_timer via benchmark_helper to benchmark eager and AOTAutograd execution time', "profile a PyTorch function's forward and backward CUDA kernel execution times with torch.profiler", 'measure forward and backward latency of a PyTorch function using torch.utils.benchmark.Timer', 'measure forward and backward latency of a PyTorch function using manual time.time calls', 'review the profile_cuda_kernels function to understand CUDA kernel profiling with warmup and backward passes', 'refactor time_with_torch_timer to support custom warmup iterations or different Timer parameters', 'run the bias_gelu_dropout function to apply add, gelu, and dropout on input tensors', 'run the aot_fn function to apply an AOT-optimized gelu approximation with dropout', 'benchmark function execution time using Torch Timer for eager and fused modes', 'benchmark function execution time using a manual timer for eager and fused modes']
```

Usage

```
{'run_benchmark_transformer_fusion_patterns': 'run the benchmark to profile and time transformer fusion patterns using memory_efficient_fusion', 'run_memory_efficient_fusion': 'run memory_efficient_fusion on a PyTorch function with static argnums to get an optimized fused function', 'run_clear_compile_cache': 'run clear_compile_cache to clear the functorch compile cache before benchmarking', 'run_profile_cuda_kernels': 'run profile_cuda_kernels via benchmark_helper to profile eager and AOTAutograd CUDA kernel execution', 'run_time_with_torch_timer': 'run time_with_torch_timer via benchmark_helper to benchmark eager and AOTAutograd execution time'}
```

## File: facebookresearch_torchdim/third_party/functorch/benchmarks/transformer_fusion_patterns/benchmark_helper.py

Prompts

```
['run the benchmark to profile and time transformer fusion patterns using memory_efficient_fusion', 'run memory_efficient_fusion on a PyTorch function with static argnums to get an optimized fused function', 'run clear_compile_cache to clear the functorch compile cache before benchmarking', 'run profile_cuda_kernels via benchmark_helper to profile eager and AOTAutograd CUDA kernel execution', 'run time_with_torch_timer via benchmark_helper to benchmark eager and AOTAutograd execution time', "profile a PyTorch function's forward and backward CUDA kernel execution times with torch.profiler", 'measure forward and backward latency of a PyTorch function using torch.utils.benchmark.Timer', 'measure forward and backward latency of a PyTorch function using manual time.time calls', 'review the profile_cuda_kernels function to understand CUDA kernel profiling with warmup and backward passes', 'refactor time_with_torch_timer to support custom warmup iterations or different Timer parameters', 'run the bias_gelu_dropout function to apply add, gelu, and dropout on input tensors', 'run the aot_fn function to apply an AOT-optimized gelu approximation with dropout', 'benchmark function execution time using Torch Timer for eager and fused modes', 'benchmark function execution time using a manual timer for eager and fused modes']
```

Usage

```
{'profile_cuda_kernels': "profile a PyTorch function's forward and backward CUDA kernel execution times with torch.profiler", 'time_with_torch_timer': 'measure forward and backward latency of a PyTorch function using torch.utils.benchmark.Timer', 'time_with_manual_timer': 'measure forward and backward latency of a PyTorch function using manual time.time calls', 'review_profile_cuda_kernels': 'review the profile_cuda_kernels function to understand CUDA kernel profiling with warmup and backward passes', 'refactor_time_with_torch_timer': 'refactor time_with_torch_timer to support custom warmup iterations or different Timer parameters'}
```

## File: facebookresearch_torchdim/third_party/functorch/benchmarks/transformer_fusion_patterns/bias_gelu_dropout.py

Prompts

```
['run the benchmark to profile and time transformer fusion patterns using memory_efficient_fusion', 'run memory_efficient_fusion on a PyTorch function with static argnums to get an optimized fused function', 'run clear_compile_cache to clear the functorch compile cache before benchmarking', 'run profile_cuda_kernels via benchmark_helper to profile eager and AOTAutograd CUDA kernel execution', 'run time_with_torch_timer via benchmark_helper to benchmark eager and AOTAutograd execution time', "profile a PyTorch function's forward and backward CUDA kernel execution times with torch.profiler", 'measure forward and backward latency of a PyTorch function using torch.utils.benchmark.Timer', 'measure forward and backward latency of a PyTorch function using manual time.time calls', 'review the profile_cuda_kernels function to understand CUDA kernel profiling with warmup and backward passes', 'refactor time_with_torch_timer to support custom warmup iterations or different Timer parameters', 'run the bias_gelu_dropout function to apply add, gelu, and dropout on input tensors', 'run the aot_fn function to apply an AOT-optimized gelu approximation with dropout', 'benchmark function execution time using Torch Timer for eager and fused modes', 'benchmark function execution time using a manual timer for eager and fused modes']
```

Usage

```
{'run_bias_gelu_dropout': 'run the bias_gelu_dropout function to apply add, gelu, and dropout on input tensors', 'run_aot_fn': 'run the aot_fn function to apply an AOT-optimized gelu approximation with dropout', 'profile_cuda_kernels': 'profile CUDA kernels for eager and AOTAutograd modes using benchmark_helper', 'benchmark_with_torch_timer': 'benchmark function execution time using Torch Timer for eager and fused modes', 'benchmark_with_manual_timer': 'benchmark function execution time using a manual timer for eager and fused modes'}
```

