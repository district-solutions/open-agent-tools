# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/bitnet_integration/test_bitnet.py

Prompts

```
['test that BitNetQuantConfig serializes to a dict with matching attribute values', 'test packing ternary weights into uint8 and unpacking back to original values', 'test replacing all nn.Linear layers in a model with BitLinear layers', 'test that BitLinear activation_quant quantizes input tensor and returns correct scale', 'test saving and reloading a quantized BitNet model produces identical logits']
```

Usage

```
{'test_bitnet_quant_config': 'test that BitNetQuantConfig serializes to a dict with matching attribute values', 'test_pack_unpack_weights': 'test packing ternary weights into uint8 and unpacking back to original values', 'test_replace_with_bitnet_linear': 'test replacing all nn.Linear layers in a model with BitLinear layers', 'test_bitlinear_activation_quant': 'test that BitLinear activation_quant quantizes input tensor and returns correct scale', 'test_bitnet_model_serialization': 'test saving and reloading a quantized BitNet model produces identical logits'}
```

