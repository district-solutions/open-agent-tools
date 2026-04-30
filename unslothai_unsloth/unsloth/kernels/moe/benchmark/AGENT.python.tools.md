# Agent Python Tools

- repo: unslothai/unsloth
- repo_uri: https://github.com/unslothai/unsloth.git

## File: unslothai_unsloth/unsloth/kernels/moe/benchmark/benchmark_fused_moe.py

Prompts

```
['benchmark the forward pass of a fused MoE model against a reference implementation', 'benchmark the backward pass of a fused MoE model against a reference implementation', 'setup reference and Triton-fused MoE models for Qwen3 or Llama4 configurations', 'run forward or backward benchmark comparing reference and fused MoE kernel implementations', 'benchmark fused MoE kernels via CLI with autotuning for Qwen3 or Llama4 models', 'create kernel configs for grouped gemm forward, dW, and dX modes with block size and warp parameters', 'post process kernel benchmark results into a sorted pandas dataframe with speedup ordering', 'save kernel benchmark results dataframe to timestamped csv file in mode-specific directory', 'get autotuned grouped gemm kernel function for forward, dW, dX, or backward mode', 'postprocess autotune results by printing cache entries and saving best configs to json']
```

Usage

```
{'run_benchmark_forward': 'benchmark the forward pass of a fused MoE model against a reference implementation', 'run_benchmark_backward': 'benchmark the backward pass of a fused MoE model against a reference implementation', 'setup_model': 'setup reference and Triton-fused MoE models for Qwen3 or Llama4 configurations', 'run_benchmark': 'run forward or backward benchmark comparing reference and fused MoE kernel implementations', 'benchmark_cli': 'benchmark fused MoE kernels via CLI with autotuning for Qwen3 or Llama4 models'}
```

## File: unslothai_unsloth/unsloth/kernels/moe/benchmark/utils.py

Prompts

```
['benchmark the forward pass of a fused MoE model against a reference implementation', 'benchmark the backward pass of a fused MoE model against a reference implementation', 'setup reference and Triton-fused MoE models for Qwen3 or Llama4 configurations', 'run forward or backward benchmark comparing reference and fused MoE kernel implementations', 'benchmark fused MoE kernels via CLI with autotuning for Qwen3 or Llama4 models', 'create kernel configs for grouped gemm forward, dW, and dX modes with block size and warp parameters', 'post process kernel benchmark results into a sorted pandas dataframe with speedup ordering', 'save kernel benchmark results dataframe to timestamped csv file in mode-specific directory', 'get autotuned grouped gemm kernel function for forward, dW, dX, or backward mode', 'postprocess autotune results by printing cache entries and saving best configs to json']
```

Usage

```
{'create_kernel_configs': 'create kernel configs for grouped gemm forward, dW, and dX modes with block size and warp parameters', 'post_process_results': 'post process kernel benchmark results into a sorted pandas dataframe with speedup ordering', 'save_results': 'save kernel benchmark results dataframe to timestamped csv file in mode-specific directory', 'get_autotuner': 'get autotuned grouped gemm kernel function for forward, dW, dX, or backward mode', 'postprocess_autotune_results': 'postprocess autotune results by printing cache entries and saving best configs to json'}
```

