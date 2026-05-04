# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/algorithms/quantization/rtn/quantizer.py

Prompts

```
['apply zero-shot RTN quantization to a model block using RTNQuantizer', 'quantize a single layer using round-to-nearest with GPU fallback to CPU', 'apply imatrix-informed RTN quantization to a model block using OptimizedRTNQuantizer', 'quantize a layer outside its block using OptimizedRTNQuantizer', 'pack and save a quantized module to shard writer for GGUF export']
```

Usage

```
{'quantize_block_rtn': 'apply zero-shot RTN quantization to a model block using RTNQuantizer', 'quantize_layer_rtn': 'quantize a single layer using round-to-nearest with GPU fallback to CPU', 'quantize_block_optimized': 'apply imatrix-informed RTN quantization to a model block using OptimizedRTNQuantizer', 'quantize_layer_outside_block': 'quantize a layer outside its block using OptimizedRTNQuantizer', 'immediate_pack_and_save': 'pack and save a quantized module to shard writer for GGUF export'}
```

