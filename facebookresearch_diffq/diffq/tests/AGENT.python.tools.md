# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/diffq/tests/base.py

Prompts

```
['test a quantizer factory can save and restore quantized model state across zeroed parameters', 'test a quantizer factory compressed model size estimates match true and packed model sizes', 'test a quantizer factory correctly excludes bias weight or regex matched parameters from quantization', 'review the cached setup function that creates small Conv1d and big LSTM test models', 'refactor the QuantizeTest base class to add new quantizer factory test methods', 'create a DiffQuantizer for a PyTorch model with configurable init_bits, group_size, and min_size parameters', 'quantize model parameters using DiffQuantizer.quantize() to apply differentiable quantization noise injection at training time', 'setup an optimizer with DiffQuantizer.setup_optimizer() to learn optimal bit-widths during training', 'export a quantized model to TorchScript using ts_export.export() for efficient serialization and inference', 'restore a quantized model state using diffq.restore_quantized_state() from a saved state dictionary', 'test LSQ quantizer save and restore quantized state across different min_size and float16 configurations', 'test LSQ float16 quantization by verifying quantized parameters match original half-precision values', 'test LSQ model size estimation across various bit widths and min_size configurations', 'test LSQ quantizer exclude parameter functionality to skip specific model parameters from quantization', 'test LSQ forward pass behavior verifying quantized model output differs from original and stabilizes in eval mode', 'test UniformQuantizer save and restore state with different min_size and float16 configurations', 'test UniformQuantizer float16 quantization on PyTorch model parameters with high min_size threshold', 'test UniformQuantizer quantization delta accuracy across multiple bit widths from 1 to 15 bits', 'test UniformQuantizer quantization-aware training on a Sequential model with Linear layers', 'test UniformQuantizer true_model_size calculation with various bits, float16, and min_size combinations']
```

Usage

```
{'test_quantize_save_restore_state': 'test a quantizer factory can save and restore quantized model state across zeroed parameters', 'test_quantize_true_model_size': 'test a quantizer factory compressed model size estimates match true and packed model sizes', 'test_quantize_exclude_params': 'test a quantizer factory correctly excludes bias weight or regex matched parameters from quantization', 'review_cached_setup_models': 'review the cached setup function that creates small Conv1d and big LSTM test models', 'refactor_quantize_test_base': 'refactor the QuantizeTest base class to add new quantizer factory test methods'}
```

## File: facebookresearch_diffq/diffq/tests/test_diffq.py

Prompts

```
['test a quantizer factory can save and restore quantized model state across zeroed parameters', 'test a quantizer factory compressed model size estimates match true and packed model sizes', 'test a quantizer factory correctly excludes bias weight or regex matched parameters from quantization', 'review the cached setup function that creates small Conv1d and big LSTM test models', 'refactor the QuantizeTest base class to add new quantizer factory test methods', 'create a DiffQuantizer for a PyTorch model with configurable init_bits, group_size, and min_size parameters', 'quantize model parameters using DiffQuantizer.quantize() to apply differentiable quantization noise injection at training time', 'setup an optimizer with DiffQuantizer.setup_optimizer() to learn optimal bit-widths during training', 'export a quantized model to TorchScript using ts_export.export() for efficient serialization and inference', 'restore a quantized model state using diffq.restore_quantized_state() from a saved state dictionary', 'test LSQ quantizer save and restore quantized state across different min_size and float16 configurations', 'test LSQ float16 quantization by verifying quantized parameters match original half-precision values', 'test LSQ model size estimation across various bit widths and min_size configurations', 'test LSQ quantizer exclude parameter functionality to skip specific model parameters from quantization', 'test LSQ forward pass behavior verifying quantized model output differs from original and stabilizes in eval mode', 'test UniformQuantizer save and restore state with different min_size and float16 configurations', 'test UniformQuantizer float16 quantization on PyTorch model parameters with high min_size threshold', 'test UniformQuantizer quantization delta accuracy across multiple bit widths from 1 to 15 bits', 'test UniformQuantizer quantization-aware training on a Sequential model with Linear layers', 'test UniformQuantizer true_model_size calculation with various bits, float16, and min_size combinations']
```

Usage

```
{'create_diffquantizer_for_model': 'create a DiffQuantizer for a PyTorch model with configurable init_bits, group_size, and min_size parameters', 'quantize_model_parameters': 'quantize model parameters using DiffQuantizer.quantize() to apply differentiable quantization noise injection at training time', 'setup_optimizer_for_bits': 'setup an optimizer with DiffQuantizer.setup_optimizer() to learn optimal bit-widths during training', 'export_torchscript_model': 'export a quantized model to TorchScript using ts_export.export() for efficient serialization and inference', 'restore_quantized_state': 'restore a quantized model state using diffq.restore_quantized_state() from a saved state dictionary'}
```

## File: facebookresearch_diffq/diffq/tests/test_lsq.py

Prompts

```
['test a quantizer factory can save and restore quantized model state across zeroed parameters', 'test a quantizer factory compressed model size estimates match true and packed model sizes', 'test a quantizer factory correctly excludes bias weight or regex matched parameters from quantization', 'review the cached setup function that creates small Conv1d and big LSTM test models', 'refactor the QuantizeTest base class to add new quantizer factory test methods', 'create a DiffQuantizer for a PyTorch model with configurable init_bits, group_size, and min_size parameters', 'quantize model parameters using DiffQuantizer.quantize() to apply differentiable quantization noise injection at training time', 'setup an optimizer with DiffQuantizer.setup_optimizer() to learn optimal bit-widths during training', 'export a quantized model to TorchScript using ts_export.export() for efficient serialization and inference', 'restore a quantized model state using diffq.restore_quantized_state() from a saved state dictionary', 'test LSQ quantizer save and restore quantized state across different min_size and float16 configurations', 'test LSQ float16 quantization by verifying quantized parameters match original half-precision values', 'test LSQ model size estimation across various bit widths and min_size configurations', 'test LSQ quantizer exclude parameter functionality to skip specific model parameters from quantization', 'test LSQ forward pass behavior verifying quantized model output differs from original and stabilizes in eval mode', 'test UniformQuantizer save and restore state with different min_size and float16 configurations', 'test UniformQuantizer float16 quantization on PyTorch model parameters with high min_size threshold', 'test UniformQuantizer quantization delta accuracy across multiple bit widths from 1 to 15 bits', 'test UniformQuantizer quantization-aware training on a Sequential model with Linear layers', 'test UniformQuantizer true_model_size calculation with various bits, float16, and min_size combinations']
```

Usage

```
{'test_LSQ_save_restore_state': 'test LSQ quantizer save and restore quantized state across different min_size and float16 configurations', 'test_LSQ_float16_quantization': 'test LSQ float16 quantization by verifying quantized parameters match original half-precision values', 'test_LSQ_model_size_estimates': 'test LSQ model size estimation across various bit widths and min_size configurations', 'test_LSQ_exclude_params': 'test LSQ quantizer exclude parameter functionality to skip specific model parameters from quantization', 'test_LSQ_forward_pass': 'test LSQ forward pass behavior verifying quantized model output differs from original and stabilizes in eval mode'}
```

## File: facebookresearch_diffq/diffq/tests/test_uniform.py

Prompts

```
['test a quantizer factory can save and restore quantized model state across zeroed parameters', 'test a quantizer factory compressed model size estimates match true and packed model sizes', 'test a quantizer factory correctly excludes bias weight or regex matched parameters from quantization', 'review the cached setup function that creates small Conv1d and big LSTM test models', 'refactor the QuantizeTest base class to add new quantizer factory test methods', 'create a DiffQuantizer for a PyTorch model with configurable init_bits, group_size, and min_size parameters', 'quantize model parameters using DiffQuantizer.quantize() to apply differentiable quantization noise injection at training time', 'setup an optimizer with DiffQuantizer.setup_optimizer() to learn optimal bit-widths during training', 'export a quantized model to TorchScript using ts_export.export() for efficient serialization and inference', 'restore a quantized model state using diffq.restore_quantized_state() from a saved state dictionary', 'test LSQ quantizer save and restore quantized state across different min_size and float16 configurations', 'test LSQ float16 quantization by verifying quantized parameters match original half-precision values', 'test LSQ model size estimation across various bit widths and min_size configurations', 'test LSQ quantizer exclude parameter functionality to skip specific model parameters from quantization', 'test LSQ forward pass behavior verifying quantized model output differs from original and stabilizes in eval mode', 'test UniformQuantizer save and restore state with different min_size and float16 configurations', 'test UniformQuantizer float16 quantization on PyTorch model parameters with high min_size threshold', 'test UniformQuantizer quantization delta accuracy across multiple bit widths from 1 to 15 bits', 'test UniformQuantizer quantization-aware training on a Sequential model with Linear layers', 'test UniformQuantizer true_model_size calculation with various bits, float16, and min_size combinations']
```

Usage

```
{'test_uniform_quantizer_save_restore': 'test UniformQuantizer save and restore state with different min_size and float16 configurations', 'test_uniform_quantizer_float16': 'test UniformQuantizer float16 quantization on PyTorch model parameters with high min_size threshold', 'test_uniform_quantizer_delta': 'test UniformQuantizer quantization delta accuracy across multiple bit widths from 1 to 15 bits', 'test_uniform_quantizer_qat': 'test UniformQuantizer quantization-aware training on a Sequential model with Linear layers', 'test_uniform_quantizer_model_size': 'test UniformQuantizer true_model_size calculation with various bits, float16, and min_size combinations'}
```

