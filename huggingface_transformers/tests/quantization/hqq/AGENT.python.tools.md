# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/hqq/test_hqq.py

Prompts

```
['create an HqqConfig with nbits and group_size to quantize a model', 'build an HQQLLMRunner to load a quantized LLM model with HQQ config', 'test an HQQ layer by dequantizing weights and verifying output shape and dtype', 'test a model forward pass and verify output logits shape matches batch and context size', 'run HQQ model serialization by saving and reloading a quantized model and comparing logits']
```

Usage

```
{'create_HQQConfig_quantization': 'create an HqqConfig with nbits and group_size to quantize a model', 'build_HQQLLMRunner_quantized_model': 'build an HQQLLMRunner to load a quantized LLM model with HQQ config', 'test_check_hqqlayer_outputs': 'test an HQQ layer by dequantizing weights and verifying output shape and dtype', 'test_check_forward_pass': 'test a model forward pass and verify output logits shape matches batch and context size', 'run_HQQ_serialization_save_load': 'run HQQ model serialization by saving and reloading a quantized model and comparing logits'}
```

