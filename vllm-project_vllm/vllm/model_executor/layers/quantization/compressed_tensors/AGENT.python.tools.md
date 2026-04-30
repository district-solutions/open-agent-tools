# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/model_executor/layers/quantization/compressed_tensors/compressed_tensors.py

Prompts

```
['create a CompressedTensorsConfig from a quantization config dictionary containing config_groups and format', 'create a CompressedTensorsLinearMethod to apply quantization weights and forward pass on linear layers', 'build a CompressedTensorsKVCacheMethod to load and validate kv-cache scaling factors from compressed-tensors checkpoints', 'test the CompressedTensorsConfig.get_scheme method to select the correct quantization scheme for a given layer', 'review the CompressedTensorsConfig.supports_cutlass_24 method to check if a layer is supported by the Cutlass 2:4 kernel', 'run triton_scaled_mm to perform matrix multiplication with per-row and per-column scaling on quantized tensors', 'test is_weak_contiguous to check if a PyTorch tensor has a weakly contiguous memory layout', 'review the scaled_mm_kernel triton JIT kernel that computes scaled matrix multiplication with bias support', 'build a quantized matrix multiply using triton_scaled_mm with input, weight, scale_a, and scale_b tensors', 'summarize triton_scaled_mm and its block tiling strategy for GPU-accelerated scaled matrix multiplication', 'test the is_activation_quantization_format function to check if a compression format is an activation quantization format', 'test the should_ignore_layer function to determine if a layer should be skipped based on ignore patterns and fused mappings', 'test the check_equal_or_regex_match function to verify layer names against exact strings or re: prefixed regex patterns', 'test the find_matched_target function to locate the matching compressed-tensors config target for a layer name or module', 'test the _match_fused_layer function to match a fused layer name like qkv_proj to its individual component targets']
```

Usage

```
{'create_CompressedTensorsConfig': 'create a CompressedTensorsConfig from a quantization config dictionary containing config_groups and format', 'create_CompressedTensorsLinearMethod': 'create a CompressedTensorsLinearMethod to apply quantization weights and forward pass on linear layers', 'build_CompressedTensorsKVCacheMethod': 'build a CompressedTensorsKVCacheMethod to load and validate kv-cache scaling factors from compressed-tensors checkpoints', 'test_CompressedTensorsConfig_scheme': 'test the CompressedTensorsConfig.get_scheme method to select the correct quantization scheme for a given layer', 'review_CompressedTensorsConfig_supports_cutlass_24': 'review the CompressedTensorsConfig.supports_cutlass_24 method to check if a layer is supported by the Cutlass 2:4 kernel'}
```

## File: vllm-project_vllm/vllm/model_executor/layers/quantization/compressed_tensors/triton_scaled_mm.py

Prompts

```
['create a CompressedTensorsConfig from a quantization config dictionary containing config_groups and format', 'create a CompressedTensorsLinearMethod to apply quantization weights and forward pass on linear layers', 'build a CompressedTensorsKVCacheMethod to load and validate kv-cache scaling factors from compressed-tensors checkpoints', 'test the CompressedTensorsConfig.get_scheme method to select the correct quantization scheme for a given layer', 'review the CompressedTensorsConfig.supports_cutlass_24 method to check if a layer is supported by the Cutlass 2:4 kernel', 'run triton_scaled_mm to perform matrix multiplication with per-row and per-column scaling on quantized tensors', 'test is_weak_contiguous to check if a PyTorch tensor has a weakly contiguous memory layout', 'review the scaled_mm_kernel triton JIT kernel that computes scaled matrix multiplication with bias support', 'build a quantized matrix multiply using triton_scaled_mm with input, weight, scale_a, and scale_b tensors', 'summarize triton_scaled_mm and its block tiling strategy for GPU-accelerated scaled matrix multiplication', 'test the is_activation_quantization_format function to check if a compression format is an activation quantization format', 'test the should_ignore_layer function to determine if a layer should be skipped based on ignore patterns and fused mappings', 'test the check_equal_or_regex_match function to verify layer names against exact strings or re: prefixed regex patterns', 'test the find_matched_target function to locate the matching compressed-tensors config target for a layer name or module', 'test the _match_fused_layer function to match a fused layer name like qkv_proj to its individual component targets']
```

Usage

```
{'run_triton_scaled_mm': 'run triton_scaled_mm to perform matrix multiplication with per-row and per-column scaling on quantized tensors', 'test_is_weak_contiguous': 'test is_weak_contiguous to check if a PyTorch tensor has a weakly contiguous memory layout', 'review_scaled_mm_kernel': 'review the scaled_mm_kernel triton JIT kernel that computes scaled matrix multiplication with bias support', 'build_scaled_mm_quantized': 'build a quantized matrix multiply using triton_scaled_mm with input, weight, scale_a, and scale_b tensors', 'summarize_triton_scaled_mm': 'summarize triton_scaled_mm and its block tiling strategy for GPU-accelerated scaled matrix multiplication'}
```

## File: vllm-project_vllm/vllm/model_executor/layers/quantization/compressed_tensors/utils.py

Prompts

```
['create a CompressedTensorsConfig from a quantization config dictionary containing config_groups and format', 'create a CompressedTensorsLinearMethod to apply quantization weights and forward pass on linear layers', 'build a CompressedTensorsKVCacheMethod to load and validate kv-cache scaling factors from compressed-tensors checkpoints', 'test the CompressedTensorsConfig.get_scheme method to select the correct quantization scheme for a given layer', 'review the CompressedTensorsConfig.supports_cutlass_24 method to check if a layer is supported by the Cutlass 2:4 kernel', 'run triton_scaled_mm to perform matrix multiplication with per-row and per-column scaling on quantized tensors', 'test is_weak_contiguous to check if a PyTorch tensor has a weakly contiguous memory layout', 'review the scaled_mm_kernel triton JIT kernel that computes scaled matrix multiplication with bias support', 'build a quantized matrix multiply using triton_scaled_mm with input, weight, scale_a, and scale_b tensors', 'summarize triton_scaled_mm and its block tiling strategy for GPU-accelerated scaled matrix multiplication', 'test the is_activation_quantization_format function to check if a compression format is an activation quantization format', 'test the should_ignore_layer function to determine if a layer should be skipped based on ignore patterns and fused mappings', 'test the check_equal_or_regex_match function to verify layer names against exact strings or re: prefixed regex patterns', 'test the find_matched_target function to locate the matching compressed-tensors config target for a layer name or module', 'test the _match_fused_layer function to match a fused layer name like qkv_proj to its individual component targets']
```

Usage

```
{'test_is_activation_quantization_format': 'test the is_activation_quantization_format function to check if a compression format is an activation quantization format', 'test_should_ignore_layer': 'test the should_ignore_layer function to determine if a layer should be skipped based on ignore patterns and fused mappings', 'test_check_equal_or_regex_match': 'test the check_equal_or_regex_match function to verify layer names against exact strings or re: prefixed regex patterns', 'test_find_matched_target': 'test the find_matched_target function to locate the matching compressed-tensors config target for a layer name or module', 'test_match_fused_layer': 'test the _match_fused_layer function to match a fused layer name like qkv_proj to its individual component targets'}
```

