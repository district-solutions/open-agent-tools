# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/aqlm_integration/test_aqlm.py

Prompts

```
['test the AqlmConfig.to_dict method to verify config-to-dict conversion preserves all fields', 'test the AqlmConfig.from_dict method to verify dict-to-config conversion preserves all fields', 'test replace_with_aqlm_linear to convert nn.Linear modules to QuantizedLinear modules', 'test that AutoModelForCausalLM raises ValueError when loading a non-quantized model with AQLM quantization config', 'test torch.compile integration with AQLM quantized model using StaticCache for KV caching']
```

Usage

```
{'test_aqlm_config_to_dict': 'test the AqlmConfig.to_dict method to verify config-to-dict conversion preserves all fields', 'test_aqlm_config_from_dict': 'test the AqlmConfig.from_dict method to verify dict-to-config conversion preserves all fields', 'test_quantized_model_conversion': 'test replace_with_aqlm_linear to convert nn.Linear modules to QuantizedLinear modules', 'test_raise_if_non_quantized': 'test that AutoModelForCausalLM raises ValueError when loading a non-quantized model with AQLM quantization config', 'test_quantized_model_compile': 'test torch.compile integration with AQLM quantized model using StaticCache for KV caching'}
```

