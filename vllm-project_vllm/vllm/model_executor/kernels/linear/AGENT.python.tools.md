# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/model_executor/kernels/linear/base.py

Prompts

```
['create a Params instance by extracting weight, weight_scale, and input_scale from a PyTorch layer module', 'create an FP8Params instance with weight, scales, and input_scale_ub extracted from a quantized layer', 'create an Int8Params instance with weight, scales, zero_point, and azp_adj extracted from a quantized layer', 'test if an MMLinearKernel subclass is supported on the current GPU hardware via is_supported()', 'review the MMLinearKernel.apply_weights method that performs quantized matrix multiplication on input tensors']
```

Usage

```
{'create_params_from_layer': 'create a Params instance by extracting weight, weight_scale, and input_scale from a PyTorch layer module', 'create_fp8_params_from_layer': 'create an FP8Params instance with weight, scales, and input_scale_ub extracted from a quantized layer', 'create_int8_params_from_layer': 'create an Int8Params instance with weight, scales, zero_point, and azp_adj extracted from a quantized layer', 'test_mm_linear_kernel_support': 'test if an MMLinearKernel subclass is supported on the current GPU hardware via is_supported()', 'review_mm_linear_kernel_apply': 'review the MMLinearKernel.apply_weights method that performs quantized matrix multiplication on input tensors'}
```

