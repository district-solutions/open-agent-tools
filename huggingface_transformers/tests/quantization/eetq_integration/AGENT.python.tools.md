# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/eetq_integration/test_eetq.py

Prompts

```
['test the EetqConfig to_dict method converts config object to matching dictionary', 'test the EetqConfig from_dict method converts dictionary to matching config object', 'test replace_with_eetq_linear replaces torch.nn.Linear modules with EetqLinear and respects modules_to_not_convert', 'test the quantized EETQ model generates expected text output from input tokens', 'test saving and loading a quantized EETQ model preserves generation output']
```

Usage

```
{'test_eetq_config_to_dict': 'test the EetqConfig to_dict method converts config object to matching dictionary', 'test_eetq_config_from_dict': 'test the EetqConfig from_dict method converts dictionary to matching config object', 'test_quantized_model_conversion': 'test replace_with_eetq_linear replaces torch.nn.Linear modules with EetqLinear and respects modules_to_not_convert', 'test_quantized_model_generation': 'test the quantized EETQ model generates expected text output from input tokens', 'test_save_pretrained_quantized_model': 'test saving and loading a quantized EETQ model preserves generation output'}
```

