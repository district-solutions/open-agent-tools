# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/export/export_to_awq/export.py

Prompts

```
['save a quantized PyTorch model to AWQ format with tokenizer and processor in an output directory', 'pack a single model layer into WQLinear_GEMM format using its quantization scale and zero point', 'collect all module names that should not be quantized based on layer config and regex rules', 'check if a PyTorch module is a supported quantizable layer type for AWQ export', 'review the save_quantized_as_autoawq function to understand how it packs layers and saves the quantized model', 'dequantize packed AWQ GEMM weights by unpacking, reversing order, and applying scales', 'unpack packed AWQ qweight and qzeros tensors using bitwise right shift operations', 'reverse the AWQ column ordering of unpacked weight and zero tensors', 'create a 4-bit AWQ quantized linear module from an existing PyTorch linear layer', 'run a quantized linear matrix multiplication using packed AWQ weights and scales']
```

Usage

```
{'export_model_to_awq_format': 'save a quantized PyTorch model to AWQ format with tokenizer and processor in an output directory', 'pack_layer_to_wqlinear_gemm': 'pack a single model layer into WQLinear_GEMM format using its quantization scale and zero point', 'collect_modules_to_not_convert': 'collect all module names that should not be quantized based on layer config and regex rules', 'check_supported_layer_type': 'check if a PyTorch module is a supported quantizable layer type for AWQ export', 'review_save_quantized_as_autoawq': 'review the save_quantized_as_autoawq function to understand how it packs layers and saves the quantized model'}
```

## File: intel_auto-round/auto_round/export/export_to_awq/utils.py

Prompts

```
['save a quantized PyTorch model to AWQ format with tokenizer and processor in an output directory', 'pack a single model layer into WQLinear_GEMM format using its quantization scale and zero point', 'collect all module names that should not be quantized based on layer config and regex rules', 'check if a PyTorch module is a supported quantizable layer type for AWQ export', 'review the save_quantized_as_autoawq function to understand how it packs layers and saves the quantized model', 'dequantize packed AWQ GEMM weights by unpacking, reversing order, and applying scales', 'unpack packed AWQ qweight and qzeros tensors using bitwise right shift operations', 'reverse the AWQ column ordering of unpacked weight and zero tensors', 'create a 4-bit AWQ quantized linear module from an existing PyTorch linear layer', 'run a quantized linear matrix multiplication using packed AWQ weights and scales']
```

Usage

```
{'dequantize_gemm': 'dequantize packed AWQ GEMM weights by unpacking, reversing order, and applying scales', 'unpack_awq': 'unpack packed AWQ qweight and qzeros tensors using bitwise right shift operations', 'reverse_awq_order': 'reverse the AWQ column ordering of unpacked weight and zero tensors', 'WQLinear_GEMM_from_linear': 'create a 4-bit AWQ quantized linear module from an existing PyTorch linear layer', 'WQLinearMMFunction_forward': 'run a quantized linear matrix multiplication using packed AWQ weights and scales'}
```

