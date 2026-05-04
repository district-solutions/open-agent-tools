# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/algorithms/quantization/base.py

Prompts

```
['create a BaseQuantizers instance from a QuantizationConfig using the from_config class method', 'quantize embedding layers in a PyTorch model by calling the _quantize_embedding_layer method', 'register forward hooks on model modules to track activation maximum values with _register_act_max_hook', 'compute block outputs for calibration inputs by calling _get_block_outputs with batch size and save flags', 'sample a mini-batch of calibration inputs by indices using the _sampling_inputs class method', 'create a QuantizationConfig with bits, group_size, sym, and data_type parameters for model quantization', 'call check_config on a QuantizationConfig instance to validate bits, group_size, and data_type settings', 'use the _is_valid_group_size static method to verify if a group_size value is valid', 'use BackendDataType enum values to check if a config uses fp, mx_fp, nv_fp, or fp8_static', 'review QuantizationConfig properties like is_act_quantize, is_mx_fp, is_nv_fp, and is_wfp8afp8 to inspect quantization mode']
```

Usage

```
{'create_quantizer_from_config': 'create a BaseQuantizers instance from a QuantizationConfig using the from_config class method', 'quantize_embedding_layer': 'quantize embedding layers in a PyTorch model by calling the _quantize_embedding_layer method', 'register_act_max_hook': 'register forward hooks on model modules to track activation maximum values with _register_act_max_hook', 'get_block_outputs': 'compute block outputs for calibration inputs by calling _get_block_outputs with batch size and save flags', 'sampling_inputs': 'sample a mini-batch of calibration inputs by indices using the _sampling_inputs class method'}
```

## File: intel_auto-round/auto_round/algorithms/quantization/config.py

Prompts

```
['create a BaseQuantizers instance from a QuantizationConfig using the from_config class method', 'quantize embedding layers in a PyTorch model by calling the _quantize_embedding_layer method', 'register forward hooks on model modules to track activation maximum values with _register_act_max_hook', 'compute block outputs for calibration inputs by calling _get_block_outputs with batch size and save flags', 'sample a mini-batch of calibration inputs by indices using the _sampling_inputs class method', 'create a QuantizationConfig with bits, group_size, sym, and data_type parameters for model quantization', 'call check_config on a QuantizationConfig instance to validate bits, group_size, and data_type settings', 'use the _is_valid_group_size static method to verify if a group_size value is valid', 'use BackendDataType enum values to check if a config uses fp, mx_fp, nv_fp, or fp8_static', 'review QuantizationConfig properties like is_act_quantize, is_mx_fp, is_nv_fp, and is_wfp8afp8 to inspect quantization mode']
```

Usage

```
{'create_quantization_config': 'create a QuantizationConfig with bits, group_size, sym, and data_type parameters for model quantization', 'validate_quantization_config': 'call check_config on a QuantizationConfig instance to validate bits, group_size, and data_type settings', 'check_valid_group_size': 'use the _is_valid_group_size static method to verify if a group_size value is valid', 'inspect_backend_data_type': 'use BackendDataType enum values to check if a config uses fp, mx_fp, nv_fp, or fp8_static', 'review_quantization_properties': 'review QuantizationConfig properties like is_act_quantize, is_mx_fp, is_nv_fp, and is_wfp8afp8 to inspect quantization mode'}
```

