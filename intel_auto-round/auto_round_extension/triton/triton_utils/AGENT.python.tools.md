# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round_extension/triton/triton_utils/custom_autotune.py

Prompts

```
['build a triton kernel decorated with autotune to benchmark and select the best config from a list', 'create a CustomizedTritonAutoTuner instance wrapping a kernel function with configurable configs and key arguments', 'run the autotune benchmark on a triton kernel using 40 repetitions and quantile timing measurements', 'refactor the matmul248_kernel_config_pruner to shrink block sizes based on input tensor dimensions M, N, K', 'review the prune_configs method that filters kernel configs using a performance model and top_k selection', 'build triton autotune configs with custom block sizes and warp counts for dequantization kernels', 'run the Triton JIT dequant kernel to unpack 2/4/8-bit quantized weights on GPU using group indices', 'run the dequant248 launcher to dequantize 2/4/8-bit quantized weights on CUDA or XPU devices', 'run a quantized matrix multiplication by dequantizing weights then multiplying with input tensors', 'review the QuantLinearFunction autograd class that provides forward and backward passes for quantized linear layers', 'run a transposed quantized matrix multiplication for backward gradient computation on gpu', 'run an inference-only quantized matrix multiplication that outputs float16 results on gpu', 'review the triton jit kernel that computes quantized matmul with per-group scales and zeros', 'review the autograd function that supports forward and backward passes for quantized linear layers']
```

Usage

```
{'build_autotune_decorator': 'build a triton kernel decorated with autotune to benchmark and select the best config from a list', 'create_customized_triton_autotuner': 'create a CustomizedTritonAutoTuner instance wrapping a kernel function with configurable configs and key arguments', 'run_autotune_bench': 'run the autotune benchmark on a triton kernel using 40 repetitions and quantile timing measurements', 'refactor_matmul248_kernel_config_pruner': 'refactor the matmul248_kernel_config_pruner to shrink block sizes based on input tensor dimensions M, N, K', 'review_prune_configs_method': 'review the prune_configs method that filters kernel configs using a performance model and top_k selection'}
```

## File: intel_auto-round/auto_round_extension/triton/triton_utils/dequant.py

Prompts

```
['build a triton kernel decorated with autotune to benchmark and select the best config from a list', 'create a CustomizedTritonAutoTuner instance wrapping a kernel function with configurable configs and key arguments', 'run the autotune benchmark on a triton kernel using 40 repetitions and quantile timing measurements', 'refactor the matmul248_kernel_config_pruner to shrink block sizes based on input tensor dimensions M, N, K', 'review the prune_configs method that filters kernel configs using a performance model and top_k selection', 'build triton autotune configs with custom block sizes and warp counts for dequantization kernels', 'run the Triton JIT dequant kernel to unpack 2/4/8-bit quantized weights on GPU using group indices', 'run the dequant248 launcher to dequantize 2/4/8-bit quantized weights on CUDA or XPU devices', 'run a quantized matrix multiplication by dequantizing weights then multiplying with input tensors', 'review the QuantLinearFunction autograd class that provides forward and backward passes for quantized linear layers', 'run a transposed quantized matrix multiplication for backward gradient computation on gpu', 'run an inference-only quantized matrix multiplication that outputs float16 results on gpu', 'review the triton jit kernel that computes quantized matmul with per-group scales and zeros', 'review the autograd function that supports forward and backward passes for quantized linear layers']
```

Usage

```
{'build_dequant_configs': 'build triton autotune configs with custom block sizes and warp counts for dequantization kernels', 'run_dequant_kernel_248': 'run the Triton JIT dequant kernel to unpack 2/4/8-bit quantized weights on GPU using group indices', 'run_dequant248': 'run the dequant248 launcher to dequantize 2/4/8-bit quantized weights on CUDA or XPU devices', 'run_quant_matmul_248': 'run a quantized matrix multiplication by dequantizing weights then multiplying with input tensors', 'review_QuantLinearFunction': 'review the QuantLinearFunction autograd class that provides forward and backward passes for quantized linear layers'}
```

## File: intel_auto-round/auto_round_extension/triton/triton_utils/kernels.py

Prompts

```
['build a triton kernel decorated with autotune to benchmark and select the best config from a list', 'create a CustomizedTritonAutoTuner instance wrapping a kernel function with configurable configs and key arguments', 'run the autotune benchmark on a triton kernel using 40 repetitions and quantile timing measurements', 'refactor the matmul248_kernel_config_pruner to shrink block sizes based on input tensor dimensions M, N, K', 'review the prune_configs method that filters kernel configs using a performance model and top_k selection', 'build triton autotune configs with custom block sizes and warp counts for dequantization kernels', 'run the Triton JIT dequant kernel to unpack 2/4/8-bit quantized weights on GPU using group indices', 'run the dequant248 launcher to dequantize 2/4/8-bit quantized weights on CUDA or XPU devices', 'run a quantized matrix multiplication by dequantizing weights then multiplying with input tensors', 'review the QuantLinearFunction autograd class that provides forward and backward passes for quantized linear layers', 'run a transposed quantized matrix multiplication for backward gradient computation on gpu', 'run an inference-only quantized matrix multiplication that outputs float16 results on gpu', 'review the triton jit kernel that computes quantized matmul with per-group scales and zeros', 'review the autograd function that supports forward and backward passes for quantized linear layers']
```

Usage

```
{'run_quant_matmul_248': 'run a quantized matrix multiplication on cuda or xpu devices using packed int32 weights', 'run_transpose_quant_matmul_248': 'run a transposed quantized matrix multiplication for backward gradient computation on gpu', 'run_quant_matmul_inference_only_248': 'run an inference-only quantized matrix multiplication that outputs float16 results on gpu', 'review_quant_matmul_248_kernel': 'review the triton jit kernel that computes quantized matmul with per-group scales and zeros', 'review_quantlinearfunction': 'review the autograd function that supports forward and backward passes for quantized linear layers'}
```

