# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/vptq_integration/test_vptq.py

Prompts

```
['test the VptqConfig.to_dict method returns a dictionary with quant_method key', 'test a quantized VPTQ model generates expected text output from input', 'test that loading a non-quantized model with VptqConfig raises a ValueError', 'test saving and loading a quantized VPTQ model preserves generation output', 'test replacing linear layers with VQuantLinear via replace_with_vptq_linear']
```

Usage

```
{'test_VptqConfig_to_dict': 'test the VptqConfig.to_dict method returns a dictionary with quant_method key', 'test_VptqConfig_quantized_model': 'test a quantized VPTQ model generates expected text output from input', 'test_VptqConfig_raise_if_non_quantized': 'test that loading a non-quantized model with VptqConfig raises a ValueError', 'test_VptqConfig_save_pretrained': 'test saving and loading a quantized VPTQ model preserves generation output', 'test_VptqConfig_quantized_model_conversion': 'test replacing linear layers with VQuantLinear via replace_with_vptq_linear'}
```

