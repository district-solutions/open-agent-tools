# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/layers/quantization/awq/awq.py

Prompts

```
['create an AWQConfig instance with 4-bit weights, group size 128, and zero point enabled', 'create an AWQMarlinConfig instance with 4-bit weights and group size 128 for faster inference', 'create an AWQCPUConfig instance using Intel AMX linear scheme for CPU-based AWQ quantization', 'check if a layer prefix should be skipped from AWQ quantization using modules_to_not_convert list', 'apply the AWQLinearMethod to a linear layer with input tensor and optional bias for forward pass', 'run awq_dequantize_triton to dequantize AWQ 4-bit weights using a Triton kernel', 'run awq_gemm_triton to perform matrix multiplication with on-the-fly AWQ dequantization', 'run awq_dequantize_decomposition to dequantize AWQ weights using pure PyTorch operations', 'review the awq_dequantize_kernel Triton JIT kernel that unpacks 4-bit packed weights', 'review the awq_gemm_kernel Triton JIT kernel that fuses dequantization with matrix multiply']
```

Usage

```
{'create_awq_config': 'create an AWQConfig instance with 4-bit weights, group size 128, and zero point enabled', 'create_awq_marlin_config': 'create an AWQMarlinConfig instance with 4-bit weights and group size 128 for faster inference', 'create_awq_cpu_config': 'create an AWQCPUConfig instance using Intel AMX linear scheme for CPU-based AWQ quantization', 'check_layer_skipped_awq': 'check if a layer prefix should be skipped from AWQ quantization using modules_to_not_convert list', 'apply_awq_linear_method': 'apply the AWQLinearMethod to a linear layer with input tensor and optional bias for forward pass'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/quantization/awq/awq_triton.py

Prompts

```
['create an AWQConfig instance with 4-bit weights, group size 128, and zero point enabled', 'create an AWQMarlinConfig instance with 4-bit weights and group size 128 for faster inference', 'create an AWQCPUConfig instance using Intel AMX linear scheme for CPU-based AWQ quantization', 'check if a layer prefix should be skipped from AWQ quantization using modules_to_not_convert list', 'apply the AWQLinearMethod to a linear layer with input tensor and optional bias for forward pass', 'run awq_dequantize_triton to dequantize AWQ 4-bit weights using a Triton kernel', 'run awq_gemm_triton to perform matrix multiplication with on-the-fly AWQ dequantization', 'run awq_dequantize_decomposition to dequantize AWQ weights using pure PyTorch operations', 'review the awq_dequantize_kernel Triton JIT kernel that unpacks 4-bit packed weights', 'review the awq_gemm_kernel Triton JIT kernel that fuses dequantization with matrix multiply']
```

Usage

```
{'run_awq_dequantize_triton': 'run awq_dequantize_triton to dequantize AWQ 4-bit weights using a Triton kernel', 'run_awq_gemm_triton': 'run awq_gemm_triton to perform matrix multiplication with on-the-fly AWQ dequantization', 'run_awq_dequantize_decomposition': 'run awq_dequantize_decomposition to dequantize AWQ weights using pure PyTorch operations', 'review_awq_dequantize_kernel': 'review the awq_dequantize_kernel Triton JIT kernel that unpacks 4-bit packed weights', 'review_awq_gemm_kernel': 'review the awq_gemm_kernel Triton JIT kernel that fuses dequantization with matrix multiply'}
```

