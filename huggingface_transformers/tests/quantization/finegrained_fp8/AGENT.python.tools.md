# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/finegrained_fp8/test_fp8.py

Prompts

```
['create a FineGrainedFP8Config quantization configuration with custom weight_block_size and modules_to_not_convert', "test converting a model's Linear layers to FP8Linear modules using replace_with_fp8_linear", 'test generating text from a FineGrainedFP8-quantized causal language model', 'test loading and generating text from a pre-quantized FP8 model with dequantize enabled', 'test FP8Linear forward pass preserves input and output tensor shapes']
```

Usage

```
{'create_finegrained_fp8_config': 'create a FineGrainedFP8Config quantization configuration with custom weight_block_size and modules_to_not_convert', 'test_quantized_model_conversion': "test converting a model's Linear layers to FP8Linear modules using replace_with_fp8_linear", 'test_quantized_model_generation': 'test generating text from a FineGrainedFP8-quantized causal language model', 'test_dequantized_model': 'test loading and generating text from a pre-quantized FP8 model with dequantize enabled', 'test_fp8_linear_forward': 'test FP8Linear forward pass preserves input and output tensor shapes'}
```

