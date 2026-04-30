# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/sinq/test_sinq.py

Prompts

```
['create a SinqConfig with custom nbits, group_size, tiling_mode, and method parameters', 'test that SinqConfig defaults to 4-bit quantization with group size 64 and 1D tiling', 'load a causal LM model quantized with SinqConfig and bfloat16 dtype', 'save a SINQ quantized model to disk and reload it for inference', 'verify that Linear modules were converted to SINQLinear and lm_head was excluded']
```

Usage

```
{'create_SinqConfig': 'create a SinqConfig with custom nbits, group_size, tiling_mode, and method parameters', 'test_SinqConfig_default_values': 'test that SinqConfig defaults to 4-bit quantization with group size 64 and 1D tiling', 'load_quantized_model_with_SinqConfig': 'load a causal LM model quantized with SinqConfig and bfloat16 dtype', 'save_and_reload_quantized_model': 'save a SINQ quantized model to disk and reload it for inference', 'verify_SinqLinear_conversion': 'verify that Linear modules were converted to SINQLinear and lm_head was excluded'}
```

