# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/quantization/modelopt/test_modelopt.py

Prompts

```
['test that all linear layers in a quantized SD3 transformer model are properly quantized by ModelOpt', 'test memory reduction of a quantized model compared to its unquantized counterpart using FP8 quantization', 'test that specified modules remain in float32 precision while the rest of the model is quantized', 'test that modules listed in modules_to_not_convert are excluded from quantization', 'test saving and loading a quantized model and verify output numerical correctness after deserialization']
```

Usage

```
{'test_modelopt_quantization_layers': 'test that all linear layers in a quantized SD3 transformer model are properly quantized by ModelOpt', 'test_modelopt_memory_usage': 'test memory reduction of a quantized model compared to its unquantized counterpart using FP8 quantization', 'test_modelopt_keep_fp32_modules': 'test that specified modules remain in float32 precision while the rest of the model is quantized', 'test_modelopt_modules_to_not_convert': 'test that modules listed in modules_to_not_convert are excluded from quantization', 'test_modelopt_serialization': 'test saving and loading a quantized model and verify output numerical correctness after deserialization'}
```

