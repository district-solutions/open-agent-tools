# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/fouroversix_integration/test_fouroversix.py

Prompts

```
['test FourOverSixConfig serialization by converting a config object to a dictionary and verifying all keys match', 'test FourOverSixConfig deserialization by creating a config from a dictionary with scale_rule and quant_method', 'test a quantized Llama model by generating text tokens using the fouroversix quantization config', 'test saving and reloading a quantized model to verify generation output remains consistent after persistence', 'test a quantized model across multiple GPU accelerators with custom memory limits per device']
```

Usage

```
{'test_FourOverSixConfig_to_dict': 'test FourOverSixConfig serialization by converting a config object to a dictionary and verifying all keys match', 'test_FourOverSixConfig_from_dict': 'test FourOverSixConfig deserialization by creating a config from a dictionary with scale_rule and quant_method', 'test_quantized_model_generate': 'test a quantized Llama model by generating text tokens using the fouroversix quantization config', 'test_save_and_load_quantized_model': 'test saving and reloading a quantized model to verify generation output remains consistent after persistence', 'test_quantized_model_multi_accelerator': 'test a quantized model across multiple GPU accelerators with custom memory limits per device'}
```

