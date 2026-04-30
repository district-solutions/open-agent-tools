# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/fp_quant_integration/test_fp_quant.py

Prompts

```
['create an FPQuantConfig object from a dictionary with modules_to_not_convert and quant_method keys', 'test FPQuantConfig.to_dict returns a dict with values matching the config object attributes', 'test FPQuantConfig.from_dict creates a config object matching the input dictionary values', 'test a quantized Llama-3.2-1B model with FPQuantConfig generates expected output text', 'test saving and reloading a quantized FPQuantConfig model from a temporary directory']
```

Usage

```
{'create_FPQuantConfig_from_dict': 'create an FPQuantConfig object from a dictionary with modules_to_not_convert and quant_method keys', 'test_FPQuantConfig_to_dict': 'test FPQuantConfig.to_dict returns a dict with values matching the config object attributes', 'test_FPQuantConfig_from_dict': 'test FPQuantConfig.from_dict creates a config object matching the input dictionary values', 'test_FPQuant_quantized_model': 'test a quantized Llama-3.2-1B model with FPQuantConfig generates expected output text', 'test_FPQuant_save_pretrained': 'test saving and reloading a quantized FPQuantConfig model from a temporary directory'}
```

