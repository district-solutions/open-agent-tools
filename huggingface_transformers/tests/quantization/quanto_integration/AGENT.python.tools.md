# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/quanto_integration/test_quanto.py

Prompts

```
['test weight-only int8 quantization conversion of linear layers to QLinear modules', 'test weight and activation int8 quantization conversion of linear and layer norm modules to quanto layers', 'test quantization conversion while excluding specific modules like lm_head from being quantized', 'test inference generation quality of a quantized int8 model on CPU against expected output', 'test that quantized quanto models raise ValueError when attempting to save with save_pretrained']
```

Usage

```
{'test_weight_only_quantization_conversion': 'test weight-only int8 quantization conversion of linear layers to QLinear modules', 'test_weight_and_activation_quantization_conversion': 'test weight and activation int8 quantization conversion of linear and layer norm modules to quanto layers', 'test_conversion_with_modules_to_not_convert': 'test quantization conversion while excluding specific modules like lm_head from being quantized', 'test_generate_quality_cpu': 'test inference generation quality of a quantized int8 model on CPU against expected output', 'test_serialization_safetensors': 'test that quantized quanto models raise ValueError when attempting to save with save_pretrained'}
```

