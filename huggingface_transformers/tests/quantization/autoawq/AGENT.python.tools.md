# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/autoawq/test_awq.py

Prompts

```
['test that AwqConfig raises ValueError when passed an invalid backend string', 'test that AwqConfig to_dict method returns a dict matching the config attributes', 'test that AwqConfig from_dict method creates a config object from a dictionary', 'test that replace_with_awq_linear converts all Linear layers to BaseQuantLinear modules', 'test that an AWQ quantized model generates correct text output from input prompts']
```

Usage

```
{'test_AwqConfig_wrong_backend': 'test that AwqConfig raises ValueError when passed an invalid backend string', 'test_AwqConfig_to_dict': 'test that AwqConfig to_dict method returns a dict matching the config attributes', 'test_AwqConfig_from_dict': 'test that AwqConfig from_dict method creates a config object from a dictionary', 'test_quantized_model_conversion': 'test that replace_with_awq_linear converts all Linear layers to BaseQuantLinear modules', 'test_quantized_model_generate': 'test that an AWQ quantized model generates correct text output from input prompts'}
```

