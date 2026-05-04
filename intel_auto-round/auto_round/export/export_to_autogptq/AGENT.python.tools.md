# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/export/export_to_autogptq/export.py

Prompts

```
['export a quantized PyTorch model to AutoGPTQ format with GPTQ-compatible quantization config and save to output directory', 'convert an AutoRound regex config dict into AutoGPTQ dynamic config with positive and negative regex match entries', 'convert an AutoGPTQ dynamic config dict back into AutoRound extra config with bits and group size keys', 'pack a single model layer into a QuantLinear module using the specified backend and device for GPTQ inference', 'review the pack_layer function to understand how it handles Linear, Conv2d, and Conv1D layer types for quantization packing', 'create a QuantLinear module with 2-bit quantization for a given input and output feature size', 'create a QuantLinear module with 4-bit quantization and custom group size for compressed inference', 'pack a standard linear layer weight into the QuantLinear module using scales and zeros', 'warm up a Triton-based quantized model before inference with a specified sequence length', 'review the QuantLinear pack method to understand how weights are quantized and bit-packed']
```

Usage

```
{'export_model_to_autogptq': 'export a quantized PyTorch model to AutoGPTQ format with GPTQ-compatible quantization config and save to output directory', 'convert_to_autogptq_dynamic': 'convert an AutoRound regex config dict into AutoGPTQ dynamic config with positive and negative regex match entries', 'convert_from_autogptq_dynamic': 'convert an AutoGPTQ dynamic config dict back into AutoRound extra config with bits and group size keys', 'pack_layer': 'pack a single model layer into a QuantLinear module using the specified backend and device for GPTQ inference', 'review_pack_layer': 'review the pack_layer function to understand how it handles Linear, Conv2d, and Conv1D layer types for quantization packing'}
```

## File: intel_auto-round/auto_round/export/export_to_autogptq/qlinear_triton.py

Prompts

```
['export a quantized PyTorch model to AutoGPTQ format with GPTQ-compatible quantization config and save to output directory', 'convert an AutoRound regex config dict into AutoGPTQ dynamic config with positive and negative regex match entries', 'convert an AutoGPTQ dynamic config dict back into AutoRound extra config with bits and group size keys', 'pack a single model layer into a QuantLinear module using the specified backend and device for GPTQ inference', 'review the pack_layer function to understand how it handles Linear, Conv2d, and Conv1D layer types for quantization packing', 'create a QuantLinear module with 2-bit quantization for a given input and output feature size', 'create a QuantLinear module with 4-bit quantization and custom group size for compressed inference', 'pack a standard linear layer weight into the QuantLinear module using scales and zeros', 'warm up a Triton-based quantized model before inference with a specified sequence length', 'review the QuantLinear pack method to understand how weights are quantized and bit-packed']
```

Usage

```
{'create_quantlinear_2bit': 'create a QuantLinear module with 2-bit quantization for a given input and output feature size', 'create_quantlinear_4bit': 'create a QuantLinear module with 4-bit quantization and custom group size for compressed inference', 'pack_quantlinear_weights': 'pack a standard linear layer weight into the QuantLinear module using scales and zeros', 'warmup_quantlinear_model': 'warm up a Triton-based quantized model before inference with a specified sequence length', 'review_quantlinear_pack': 'review the QuantLinear pack method to understand how weights are quantized and bit-packed'}
```

