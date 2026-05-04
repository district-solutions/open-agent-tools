# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round_extension/triton/triton_utils_zp/custom_autotune.py

Prompts

```
['build a triton kernel decorated with autotune to benchmark and select the fastest config from a list', 'create a CustomizedTritonAutoTuner instance to autotune a kernel with 40 benchmark runs instead of 100', 'run the autotune benchmark on a triton kernel with configurable block sizes and warp counts', 'refactor the matmul248_kernel_config_pruner to shrink block sizes when M, N, or K dimensions are smaller', 'review the CustomizedTritonAutoTuner prune_configs method to understand how performance models filter candidate configurations', 'build a triton kernel that dequantizes 2/4/8 bit weights using group indices and scales', 'create a function that dequantizes compressed weights on cuda or xpu devices for inference', 'test the quantized matrix multiplication function with dequantized weights and optional transpose', 'refactor the QuantLinearFunction autograd class to support custom backward pass for quantized linear layers', 'review the default dequant kernel autotune configurations with block sizes and warp counts', 'run quant_matmul_248 to multiply input by quantized weights with scales and zeros on cuda or xpu', 'run transpose_quant_matmul_248 to multiply input by transposed quantized weights for gradient computation on cuda or xpu', 'run quant_matmul_inference_only_248 to perform forward-only quantized matrix multiplication returning float16 output on cuda or xpu', 'review the quant_matmul_248_kernel triton JIT kernel that computes C=AxB with 4-bit packed int32 weights and group-wise quantization', 'review QuantLinearFunction autograd class that wraps quant_matmul_248 for forward and transpose_quant_matmul_248 for backward passes']
```

Usage

```
{'build_autotune_decorator': 'build a triton kernel decorated with autotune to benchmark and select the fastest config from a list', 'create_customized_triton_autotuner': 'create a CustomizedTritonAutoTuner instance to autotune a kernel with 40 benchmark runs instead of 100', 'run_autotune_bench': 'run the autotune benchmark on a triton kernel with configurable block sizes and warp counts', 'refactor_matmul248_kernel_config_pruner': 'refactor the matmul248_kernel_config_pruner to shrink block sizes when M, N, or K dimensions are smaller', 'review_customized_triton_autotuner_prune_configs': 'review the CustomizedTritonAutoTuner prune_configs method to understand how performance models filter candidate configurations'}
```

## File: intel_auto-round/auto_round_extension/triton/triton_utils_zp/dequant.py

Prompts

```
['build a triton kernel decorated with autotune to benchmark and select the fastest config from a list', 'create a CustomizedTritonAutoTuner instance to autotune a kernel with 40 benchmark runs instead of 100', 'run the autotune benchmark on a triton kernel with configurable block sizes and warp counts', 'refactor the matmul248_kernel_config_pruner to shrink block sizes when M, N, or K dimensions are smaller', 'review the CustomizedTritonAutoTuner prune_configs method to understand how performance models filter candidate configurations', 'build a triton kernel that dequantizes 2/4/8 bit weights using group indices and scales', 'create a function that dequantizes compressed weights on cuda or xpu devices for inference', 'test the quantized matrix multiplication function with dequantized weights and optional transpose', 'refactor the QuantLinearFunction autograd class to support custom backward pass for quantized linear layers', 'review the default dequant kernel autotune configurations with block sizes and warp counts', 'run quant_matmul_248 to multiply input by quantized weights with scales and zeros on cuda or xpu', 'run transpose_quant_matmul_248 to multiply input by transposed quantized weights for gradient computation on cuda or xpu', 'run quant_matmul_inference_only_248 to perform forward-only quantized matrix multiplication returning float16 output on cuda or xpu', 'review the quant_matmul_248_kernel triton JIT kernel that computes C=AxB with 4-bit packed int32 weights and group-wise quantization', 'review QuantLinearFunction autograd class that wraps quant_matmul_248 for forward and transpose_quant_matmul_248 for backward passes']
```

Usage

```
{'build_dequant_kernel_248': 'build a triton kernel that dequantizes 2/4/8 bit weights using group indices and scales', 'create_dequant248_function': 'create a function that dequantizes compressed weights on cuda or xpu devices for inference', 'test_quant_matmul_248': 'test the quantized matrix multiplication function with dequantized weights and optional transpose', 'refactor_quantlinearfunction': 'refactor the QuantLinearFunction autograd class to support custom backward pass for quantized linear layers', 'review_dequant_configs': 'review the default dequant kernel autotune configurations with block sizes and warp counts'}
```

## File: intel_auto-round/auto_round_extension/triton/triton_utils_zp/kernels.py

Prompts

```
['build a triton kernel decorated with autotune to benchmark and select the fastest config from a list', 'create a CustomizedTritonAutoTuner instance to autotune a kernel with 40 benchmark runs instead of 100', 'run the autotune benchmark on a triton kernel with configurable block sizes and warp counts', 'refactor the matmul248_kernel_config_pruner to shrink block sizes when M, N, or K dimensions are smaller', 'review the CustomizedTritonAutoTuner prune_configs method to understand how performance models filter candidate configurations', 'build a triton kernel that dequantizes 2/4/8 bit weights using group indices and scales', 'create a function that dequantizes compressed weights on cuda or xpu devices for inference', 'test the quantized matrix multiplication function with dequantized weights and optional transpose', 'refactor the QuantLinearFunction autograd class to support custom backward pass for quantized linear layers', 'review the default dequant kernel autotune configurations with block sizes and warp counts', 'run quant_matmul_248 to multiply input by quantized weights with scales and zeros on cuda or xpu', 'run transpose_quant_matmul_248 to multiply input by transposed quantized weights for gradient computation on cuda or xpu', 'run quant_matmul_inference_only_248 to perform forward-only quantized matrix multiplication returning float16 output on cuda or xpu', 'review the quant_matmul_248_kernel triton JIT kernel that computes C=AxB with 4-bit packed int32 weights and group-wise quantization', 'review QuantLinearFunction autograd class that wraps quant_matmul_248 for forward and transpose_quant_matmul_248 for backward passes']
```

Usage

```
{'run_quant_matmul_248': 'run quant_matmul_248 to multiply input by quantized weights with scales and zeros on cuda or xpu', 'run_transpose_quant_matmul_248': 'run transpose_quant_matmul_248 to multiply input by transposed quantized weights for gradient computation on cuda or xpu', 'run_quant_matmul_inference_only_248': 'run quant_matmul_inference_only_248 to perform forward-only quantized matrix multiplication returning float16 output on cuda or xpu', 'review_quant_matmul_248_kernel': 'review the quant_matmul_248_kernel triton JIT kernel that computes C=AxB with 4-bit packed int32 weights and group-wise quantization', 'review_quantlinearfunction': 'review QuantLinearFunction autograd class that wraps quant_matmul_248 for forward and transpose_quant_matmul_248 for backward passes'}
```

