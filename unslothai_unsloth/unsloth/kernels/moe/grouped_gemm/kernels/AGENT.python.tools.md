# Agent Python Tools

- repo: unslothai/unsloth
- repo_uri: https://github.com/unslothai/unsloth.git

## File: unslothai_unsloth/unsloth/kernels/moe/grouped_gemm/kernels/autotuning.py

Prompts

```
['build triton kernel configs for grouped GEMM forward pass with block sizes, TMA options, warps, stages, and CTAs', 'build triton kernel configs for grouped GEMM dX backward pass with block sizes, TMA options, warps, stages, and CTAs', 'build triton kernel configs for grouped GEMM dW backward pass with block sizes, TMA options, warps, stages, and CTAs', 'test pruning forward kernel configs using SMEM capacity, block size, and permute criteria', 'test pruning dX backward kernel configs using SMEM capacity, block size, and permute criteria', 'test pruning dW backward kernel configs using SMEM capacity, block size, and permute criteria', 'summarize estimating shared memory requirements for a given block size, num_stages, and dtype', 'review the common pruning criteria for triton kernel configs including SMEM capacity and block size heuristics', 'get the GPU device properties including number of SMs, registers, shared memory, and warp size', 'get autotuning kernel configurations for forward and backward passes with block sizes, warps, and stages', 'convert a list of kernel tuning results into a sorted pandas DataFrame by speedup or other metrics', 'write a list of kernel tuning results to a CSV file sorted by speedup', 'print the top N kernel tuning results as a formatted table sorted by speedup']
```

Usage

```
{'build_get_forward_configs': 'build triton kernel configs for grouped GEMM forward pass with block sizes, TMA options, warps, stages, and CTAs', 'build_get_dX_kernel_configs': 'build triton kernel configs for grouped GEMM dX backward pass with block sizes, TMA options, warps, stages, and CTAs', 'build_get_dW_kernel_configs': 'build triton kernel configs for grouped GEMM dW backward pass with block sizes, TMA options, warps, stages, and CTAs', 'test_prune_kernel_configs_fwd': 'test pruning forward kernel configs using SMEM capacity, block size, and permute criteria', 'test_prune_dX_configs': 'test pruning dX backward kernel configs using SMEM capacity, block size, and permute criteria', 'test_prune_kernel_configs_backward_dW': 'test pruning dW backward kernel configs using SMEM capacity, block size, and permute criteria', 'summarize_estimate_smem_reqs': 'summarize estimating shared memory requirements for a given block size, num_stages, and dtype', 'review_common_prune_criteria': 'review the common pruning criteria for triton kernel configs including SMEM capacity and block size heuristics'}
```

## File: unslothai_unsloth/unsloth/kernels/moe/grouped_gemm/kernels/tuning.py

Prompts

```
['build triton kernel configs for grouped GEMM forward pass with block sizes, TMA options, warps, stages, and CTAs', 'build triton kernel configs for grouped GEMM dX backward pass with block sizes, TMA options, warps, stages, and CTAs', 'build triton kernel configs for grouped GEMM dW backward pass with block sizes, TMA options, warps, stages, and CTAs', 'test pruning forward kernel configs using SMEM capacity, block size, and permute criteria', 'test pruning dX backward kernel configs using SMEM capacity, block size, and permute criteria', 'test pruning dW backward kernel configs using SMEM capacity, block size, and permute criteria', 'summarize estimating shared memory requirements for a given block size, num_stages, and dtype', 'review the common pruning criteria for triton kernel configs including SMEM capacity and block size heuristics', 'get the GPU device properties including number of SMs, registers, shared memory, and warp size', 'get autotuning kernel configurations for forward and backward passes with block sizes, warps, and stages', 'convert a list of kernel tuning results into a sorted pandas DataFrame by speedup or other metrics', 'write a list of kernel tuning results to a CSV file sorted by speedup', 'print the top N kernel tuning results as a formatted table sorted by speedup']
```

Usage

```
{'get_device_properties': 'get the GPU device properties including number of SMs, registers, shared memory, and warp size', 'get_kernel_configs': 'get autotuning kernel configurations for forward and backward passes with block sizes, warps, and stages', 'KernelResult_to_dataframe': 'convert a list of kernel tuning results into a sorted pandas DataFrame by speedup or other metrics', 'KernelResult_to_csv': 'write a list of kernel tuning results to a CSV file sorted by speedup', 'KernelResult_print_table': 'print the top N kernel tuning results as a formatted table sorted by speedup'}
```

