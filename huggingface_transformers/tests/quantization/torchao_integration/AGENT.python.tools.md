# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/torchao_integration/test_torchao.py

Prompts

```
['test the TorchAoConfig class to verify to_dict, repr, and JSON serialization methods work correctly', 'test Int4 weight-only quantization on a causal LM model with tile_packed_to_4d format and verify generation output', 'test FqnToConfig regex and exact module matching precedence for per-module quantization configuration', 'test quantized model save and reload round-trip serialization for multiple TorchAo quantization configs across CPU and accelerator devices', 'test Int4 weight-only quantization with explicit CPU offload device map on accelerator devices']
```

Usage

```
{'test_torchao_config_serialization': 'test the TorchAoConfig class to verify to_dict, repr, and JSON serialization methods work correctly', 'test_int4_weight_only_quantization': 'test Int4 weight-only quantization on a causal LM model with tile_packed_to_4d format and verify generation output', 'test_fqn_to_config_module_matching': 'test FqnToConfig regex and exact module matching precedence for per-module quantization configuration', 'test_quantized_model_serialization': 'test quantized model save and reload round-trip serialization for multiple TorchAo quantization configs across CPU and accelerator devices', 'test_int4_cpu_offload_quantization': 'test Int4 weight-only quantization with explicit CPU offload device map on accelerator devices'}
```

