# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/metal/test_metal.py

Prompts

```
['create a MetalConfig with custom bits, group_size, and modules_to_not_convert for quantization', 'test MetalHfQuantizer validate_environment to check MPS availability and kernel requirements', 'run an affine quantize then dequantize roundtrip test on a random weight tensor', 'test MetalLinear forward pass with prequantized uint32 weights or fallback float weights', 'test replacing all nn.Linear modules with MetalLinear in a model with exclusion support']
```

Usage

```
{'create_MetalConfig': 'create a MetalConfig with custom bits, group_size, and modules_to_not_convert for quantization', 'test_MetalHfQuantizer_validate_environment': 'test MetalHfQuantizer validate_environment to check MPS availability and kernel requirements', 'run_affine_quantize_dequantize_roundtrip': 'run an affine quantize then dequantize roundtrip test on a random weight tensor', 'test_MetalLinear_forward': 'test MetalLinear forward pass with prequantized uint32 weights or fallback float weights', 'test_replace_with_metal_linear': 'test replacing all nn.Linear modules with MetalLinear in a model with exclusion support'}
```

