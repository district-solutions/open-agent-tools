# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/higgs/test_higgs.py

Prompts

```
['test the HiggsConfig class to_dict method converts config object to matching dictionary', 'test the HiggsConfig class from_dict method converts dictionary to matching config object', 'test replacing nn.Linear modules with HiggsLinear modules using replace_with_higgs_linear', 'test the quantized model generates expected text output from input tokens', 'test saving and loading a quantized model preserves generation accuracy']
```

Usage

```
{'test_higgs_config_to_dict': 'test the HiggsConfig class to_dict method converts config object to matching dictionary', 'test_higgs_config_from_dict': 'test the HiggsConfig class from_dict method converts dictionary to matching config object', 'test_quantized_model_conversion': 'test replacing nn.Linear modules with HiggsLinear modules using replace_with_higgs_linear', 'test_quantized_model_generation': 'test the quantized model generates expected text output from input tokens', 'test_quantized_model_save_load': 'test saving and loading a quantized model preserves generation accuracy'}
```

