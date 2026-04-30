# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/quantization/calibration.py

Prompts

```
['initialize observer module and attach it to a quantized torch.nn.Module for weight, input, or output calibration', 'update weight scale and zero point values on a module during quantization calibration by calling its attached observer', 'register a forward hook that calibrates input activations by updating observer scales and zero points before QDQ', 'register a forward hook that calibrates output activations and returns quantized output via observer scales and zero points', "freeze a module's quantization by removing all attached observers and setting quantization status to FROZEN", 'test the get_layers_indivisible_by_group_size function to find model layers with weight columns not divisible by group_size', 'validate group_size divisibility for quantized model layers and raise ValueError if any are indivisible', 'run validate_group_size_divisibility with bypass=True to skip indivisibility checks for runtimes that support non-divisible dimensions', "review the _layer_indivisible helper function that checks if a module's weight columns are not divisible by group_size", "summarize the group_size_validation module's policy for GROUP and TENSOR_GROUP quantization strategies requiring column divisibility"]
```

Usage

```
{'initialize_observer': 'initialize observer module and attach it to a quantized torch.nn.Module for weight, input, or output calibration', 'update_weight_zp_scale': 'update weight scale and zero point values on a module during quantization calibration by calling its attached observer', 'calibrate_input_hook': 'register a forward hook that calibrates input activations by updating observer scales and zero points before QDQ', 'calibrate_output_hook': 'register a forward hook that calibrates output activations and returns quantized output via observer scales and zero points', 'freeze_module_quantization': "freeze a module's quantization by removing all attached observers and setting quantization status to FROZEN"}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/quantization/group_size_validation.py

Prompts

```
['initialize observer module and attach it to a quantized torch.nn.Module for weight, input, or output calibration', 'update weight scale and zero point values on a module during quantization calibration by calling its attached observer', 'register a forward hook that calibrates input activations by updating observer scales and zero points before QDQ', 'register a forward hook that calibrates output activations and returns quantized output via observer scales and zero points', "freeze a module's quantization by removing all attached observers and setting quantization status to FROZEN", 'test the get_layers_indivisible_by_group_size function to find model layers with weight columns not divisible by group_size', 'validate group_size divisibility for quantized model layers and raise ValueError if any are indivisible', 'run validate_group_size_divisibility with bypass=True to skip indivisibility checks for runtimes that support non-divisible dimensions', "review the _layer_indivisible helper function that checks if a module's weight columns are not divisible by group_size", "summarize the group_size_validation module's policy for GROUP and TENSOR_GROUP quantization strategies requiring column divisibility"]
```

Usage

```
{'test_get_layers_indivisible_by_group_size': 'test the get_layers_indivisible_by_group_size function to find model layers with weight columns not divisible by group_size', 'validate_group_size_divisibility': 'validate group_size divisibility for quantized model layers and raise ValueError if any are indivisible', 'run_validate_with_bypass': 'run validate_group_size_divisibility with bypass=True to skip indivisibility checks for runtimes that support non-divisible dimensions', 'review__layer_indivisible': "review the _layer_indivisible helper function that checks if a module's weight columns are not divisible by group_size", 'summarize_group_size_validation': "summarize the group_size_validation module's policy for GROUP and TENSOR_GROUP quantization strategies requiring column divisibility"}
```

