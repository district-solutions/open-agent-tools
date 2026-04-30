# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/gptq/test_gptq.py

Prompts

```
['create a GPTQConfig with 4-bit quantization, group size 128, and a calibration dataset', 'test GPTQConfig validates bits, dataset, and damp_percent parameters correctly', 'quantize a causal language model using GPTQConfig with exllamav2 backend on GPU', 'test quantized model generates expected text outputs with matching generation quality', 'test saving and reloading a quantized GPTQ model with correct quantized layer types']
```

Usage

```
{'create_gptq_quantization_config': 'create a GPTQConfig with 4-bit quantization, group size 128, and a calibration dataset', 'test_gptq_config_validation': 'test GPTQConfig validates bits, dataset, and damp_percent parameters correctly', 'quantize_model_gptq': 'quantize a causal language model using GPTQConfig with exllamav2 backend on GPU', 'test_quantized_model_inference': 'test quantized model generates expected text outputs with matching generation quality', 'test_gptq_serialization': 'test saving and reloading a quantized GPTQ model with correct quantized layer types'}
```

