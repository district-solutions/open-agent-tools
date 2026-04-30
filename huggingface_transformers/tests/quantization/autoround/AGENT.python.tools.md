# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/autoround/test_auto_round.py

Prompts

```
['test that a pre-quantized AutoRound model generates correct text output', 'test that loading a non-quantized model with AutoRoundConfig raises a ValueError', 'test loading a quantized model with bfloat16 dtype and triton backend', 'test saving and reloading a quantized model preserves generation output', 'quantize a model with per-layer mixed bit configuration using AutoRound']
```

Usage

```
{'test_autoround_quantized_model': 'test that a pre-quantized AutoRound model generates correct text output', 'test_autoround_non_quantized_error': 'test that loading a non-quantized model with AutoRoundConfig raises a ValueError', 'test_autoround_bf16_backend': 'test loading a quantized model with bfloat16 dtype and triton backend', 'test_autoround_save_and_reload': 'test saving and reloading a quantized model preserves generation output', 'quantize_with_mixed_bits': 'quantize a model with per-layer mixed bit configuration using AutoRound'}
```

