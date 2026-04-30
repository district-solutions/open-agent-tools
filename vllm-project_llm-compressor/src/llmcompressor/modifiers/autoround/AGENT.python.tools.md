# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/autoround/base.py

Prompts

```
['build an AutoRoundModifier to quantize a PyTorch model using 4-bit weight quantization with group size 128', 'apply AutoRound quantization tuning on a decoding layer using calibrated input captures and SignSGD optimizer', 'suspend model offloading temporarily during AutoRound tuning and restore it after quantization completes', 'map a LLMCompressor QuantizationScheme to an AutoRound QuantizationScheme with matching bits, symmetry, and group size', 'unwrap WrapperWALayer modules back to their original layers after AutoRound quantization tuning finishes']
```

Usage

```
{'build_autoround_quantization': 'build an AutoRoundModifier to quantize a PyTorch model using 4-bit weight quantization with group size 128', 'apply_autoround_quantization': 'apply AutoRound quantization tuning on a decoding layer using calibrated input captures and SignSGD optimizer', 'suspend_model_offloading': 'suspend model offloading temporarily during AutoRound tuning and restore it after quantization completes', 'map_quantization_config': 'map a LLMCompressor QuantizationScheme to an AutoRound QuantizationScheme with matching bits, symmetry, and group size', 'unwrap_quantized_layers': 'unwrap WrapperWALayer modules back to their original layers after AutoRound quantization tuning finishes'}
```

