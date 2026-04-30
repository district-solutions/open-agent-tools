# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/layers/quantization/compressed_tensors/compressed_tensors.py

Prompts

```
['create a CompressedTensorsConfig from a quantization config dictionary with format, config_groups, and ignore lists', 'get the linear quantization scheme for a torch.nn.Module layer using CompressedTensorsConfig', 'get the MoE quantization scheme for a FusedMoE layer using CompressedTensorsConfig', 'apply the quantized forward pass for a linear layer using CompressedTensorsLinearMethod', 'get the quant method for a linear or FusedMoE layer using CompressedTensorsConfig', 'test the is_activation_quantization_format function to check if a compression format uses activation quantization', 'test the should_ignore_layer function to determine whether a layer should be skipped during quantization', 'test the check_equal_or_regex_match function to verify layer name matching with exact or regex patterns', 'test the find_matched_target function to find the matching config target for a given layer and module', 'test the _match_fused_layer function to map a fused layer name to its individual component targets']
```

Usage

```
{'create_CompressedTensorsConfig_from_config': 'create a CompressedTensorsConfig from a quantization config dictionary with format, config_groups, and ignore lists', 'get_linear_quantization_scheme': 'get the linear quantization scheme for a torch.nn.Module layer using CompressedTensorsConfig', 'get_moe_quantization_scheme': 'get the MoE quantization scheme for a FusedMoE layer using CompressedTensorsConfig', 'apply_quantized_linear_forward': 'apply the quantized forward pass for a linear layer using CompressedTensorsLinearMethod', 'get_quant_method_for_layer': 'get the quant method for a linear or FusedMoE layer using CompressedTensorsConfig'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/quantization/compressed_tensors/utils.py

Prompts

```
['create a CompressedTensorsConfig from a quantization config dictionary with format, config_groups, and ignore lists', 'get the linear quantization scheme for a torch.nn.Module layer using CompressedTensorsConfig', 'get the MoE quantization scheme for a FusedMoE layer using CompressedTensorsConfig', 'apply the quantized forward pass for a linear layer using CompressedTensorsLinearMethod', 'get the quant method for a linear or FusedMoE layer using CompressedTensorsConfig', 'test the is_activation_quantization_format function to check if a compression format uses activation quantization', 'test the should_ignore_layer function to determine whether a layer should be skipped during quantization', 'test the check_equal_or_regex_match function to verify layer name matching with exact or regex patterns', 'test the find_matched_target function to find the matching config target for a given layer and module', 'test the _match_fused_layer function to map a fused layer name to its individual component targets']
```

Usage

```
{'test_is_activation_quantization_format': 'test the is_activation_quantization_format function to check if a compression format uses activation quantization', 'test_should_ignore_layer': 'test the should_ignore_layer function to determine whether a layer should be skipped during quantization', 'test_check_equal_or_regex_match': 'test the check_equal_or_regex_match function to verify layer name matching with exact or regex patterns', 'test_find_matched_target': 'test the find_matched_target function to find the matching config target for a given layer and module', 'test_match_fused_layer': 'test the _match_fused_layer function to map a fused layer name to its individual component targets'}
```

