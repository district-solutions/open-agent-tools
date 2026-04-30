# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/quantization/quanto/test_quanto.py

Prompts

```
['test that all linear layers in a quantized FluxTransformer2DModel are converted to QLinear', 'test that a quantized model uses less peak memory than an unquantized model', 'test that specified modules remain in fp32 when loading a quantized model', 'test that specified modules are excluded from quantization when using QuantoConfig', 'test saving and reloading a quantized FluxTransformer2DModel produces matching outputs']
```

Usage

```
{'test_quanto_layers': 'test that all linear layers in a quantized FluxTransformer2DModel are converted to QLinear', 'test_quanto_memory_usage': 'test that a quantized model uses less peak memory than an unquantized model', 'test_keep_modules_in_fp32': 'test that specified modules remain in fp32 when loading a quantized model', 'test_modules_to_not_convert': 'test that specified modules are excluded from quantization when using QuantoConfig', 'test_serialization': 'test saving and reloading a quantized FluxTransformer2DModel produces matching outputs'}
```

