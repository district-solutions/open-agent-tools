# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/layers/deep_gemm_wrapper/compile_utils.py

Prompts

```
['update DeepGEMM JIT compilation config based on GPU ID and server arguments for optimal kernel precompilation', 'create a warmup executor for a specified DeepGEMM kernel type with given M, N, K, and group dimensions', 'test the GPU memory requirement estimation for a DeepGEMM kernel type with given dimensions', 'run a DeepGEMM execution hook that triggers JIT precompilation for a kernel type with given M, N, K, and group count', 'review the DeepGEMM kernel type enum supporting grouped F8 GEMM masked, grouped F8 GEMM contiguous, F8 GEMM, and BF16 GEMM', 'run grouped FP8 matrix multiplication with masking and optional overlap arguments', 'run grouped contiguous FP8 matrix multiplication with m_indices mapping', 'run standard FP8 matrix multiplication with lhs scale-tensor pairs and output tensor', 'run bf16 matrix multiplication producing f32 output with lhs and rhs tensors']
```

Usage

```
{'update_deep_gemm_config': 'update DeepGEMM JIT compilation config based on GPU ID and server arguments for optimal kernel precompilation', 'create_deep_gemm_warmup_executor': 'create a warmup executor for a specified DeepGEMM kernel type with given M, N, K, and group dimensions', 'test_deep_gemm_memory_requirement': 'test the GPU memory requirement estimation for a DeepGEMM kernel type with given dimensions', 'run_deep_gemm_execution_hook': 'run a DeepGEMM execution hook that triggers JIT precompilation for a kernel type with given M, N, K, and group count', 'review_deep_gemm_kernel_types': 'review the DeepGEMM kernel type enum supporting grouped F8 GEMM masked, grouped F8 GEMM contiguous, F8 GEMM, and BF16 GEMM'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/deep_gemm_wrapper/entrypoint.py

Prompts

```
['update DeepGEMM JIT compilation config based on GPU ID and server arguments for optimal kernel precompilation', 'create a warmup executor for a specified DeepGEMM kernel type with given M, N, K, and group dimensions', 'test the GPU memory requirement estimation for a DeepGEMM kernel type with given dimensions', 'run a DeepGEMM execution hook that triggers JIT precompilation for a kernel type with given M, N, K, and group count', 'review the DeepGEMM kernel type enum supporting grouped F8 GEMM masked, grouped F8 GEMM contiguous, F8 GEMM, and BF16 GEMM', 'run grouped FP8 matrix multiplication with masking and optional overlap arguments', 'run grouped contiguous FP8 matrix multiplication with m_indices mapping', 'run standard FP8 matrix multiplication with lhs scale-tensor pairs and output tensor', 'run bf16 matrix multiplication producing f32 output with lhs and rhs tensors']
```

Usage

```
{'run_grouped_gemm_nt_f8f8bf16_masked': 'run grouped FP8 matrix multiplication with masking and optional overlap arguments', 'run_grouped_gemm_nt_f8f8bf16_contig': 'run grouped contiguous FP8 matrix multiplication with m_indices mapping', 'run_gemm_nt_f8f8bf16': 'run standard FP8 matrix multiplication with lhs scale-tensor pairs and output tensor', 'run_gemm_nt_bf16bf16f32': 'run bf16 matrix multiplication producing f32 output with lhs and rhs tensors', 'update_deep_gemm_config': 'update deep gemm configuration for a given gpu_id and server_args'}
```

