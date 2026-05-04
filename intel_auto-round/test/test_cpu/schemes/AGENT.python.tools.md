# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/test/test_cpu/schemes/test_auto_scheme.py

Prompts

```
['create an AutoScheme with avg_bits 2 and W2A16 options for model quantization', 'create an AutoScheme with avg_bits 4 and mxfp4 options for mixed precision quantization', 'run AutoRound with a scheme to quantize a model and save the result to a directory', 'test AutoRound with a custom layer_config to override bits, group_size, and sym for specific layers', 'compute the average bits per weight for a quantized model using compute_avg_bits_for_model', 'test the OffloadManager class as a context manager that auto-cleans offloaded model weights on exit', 'test the OffloadManager offload and reload methods to save and restore model block weights to disk', 'test the OffloadManager add_offload_hooks and remove_offload_hooks methods to clear and restore all model blocks', 'test the _clear_module_weights function to zero out weight tensors from a PyTorch module while caching original numel', 'test the AutoScheme dataclass with low_cpu_mem_usage enabled to reduce CPU RAM during model quantization', 'create an AutoRound instance with a scheme like W4A16 to quantize a HuggingFace model', 'call quantize_and_save with format gguf:q4_k_m to export a quantized model in GGUF format', 'pass a layer_config dict to AutoRound to set per-layer bit widths for mixed precision quantization', 'use QuantizationScheme.from_dict with bits and group_size keys to build a custom quantization scheme', 'call parse_available_devices with a device string like auto or cuda:0,cuda:1 to get a device list']
```

Usage

```
{'create_autoscheme_w2a16': 'create an AutoScheme with avg_bits 2 and W2A16 options for model quantization', 'create_autoscheme_mxfp4': 'create an AutoScheme with avg_bits 4 and mxfp4 options for mixed precision quantization', 'run_autoround_quantize_and_save': 'run AutoRound with a scheme to quantize a model and save the result to a directory', 'test_layer_config_override': 'test AutoRound with a custom layer_config to override bits, group_size, and sym for specific layers', 'compute_avg_bits_for_model': 'compute the average bits per weight for a quantized model using compute_avg_bits_for_model'}
```

## File: intel_auto-round/test/test_cpu/schemes/test_auto_scheme_low_cpu_mem.py

Prompts

```
['create an AutoScheme with avg_bits 2 and W2A16 options for model quantization', 'create an AutoScheme with avg_bits 4 and mxfp4 options for mixed precision quantization', 'run AutoRound with a scheme to quantize a model and save the result to a directory', 'test AutoRound with a custom layer_config to override bits, group_size, and sym for specific layers', 'compute the average bits per weight for a quantized model using compute_avg_bits_for_model', 'test the OffloadManager class as a context manager that auto-cleans offloaded model weights on exit', 'test the OffloadManager offload and reload methods to save and restore model block weights to disk', 'test the OffloadManager add_offload_hooks and remove_offload_hooks methods to clear and restore all model blocks', 'test the _clear_module_weights function to zero out weight tensors from a PyTorch module while caching original numel', 'test the AutoScheme dataclass with low_cpu_mem_usage enabled to reduce CPU RAM during model quantization', 'create an AutoRound instance with a scheme like W4A16 to quantize a HuggingFace model', 'call quantize_and_save with format gguf:q4_k_m to export a quantized model in GGUF format', 'pass a layer_config dict to AutoRound to set per-layer bit widths for mixed precision quantization', 'use QuantizationScheme.from_dict with bits and group_size keys to build a custom quantization scheme', 'call parse_available_devices with a device string like auto or cuda:0,cuda:1 to get a device list']
```

Usage

```
{'test_OffloadManager_context': 'test the OffloadManager class as a context manager that auto-cleans offloaded model weights on exit', 'test_OffloadManager_offload_reload': 'test the OffloadManager offload and reload methods to save and restore model block weights to disk', 'test_OffloadManager_hooks': 'test the OffloadManager add_offload_hooks and remove_offload_hooks methods to clear and restore all model blocks', 'test_clear_module_weights': 'test the _clear_module_weights function to zero out weight tensors from a PyTorch module while caching original numel', 'test_AutoScheme_low_cpu_mem': 'test the AutoScheme dataclass with low_cpu_mem_usage enabled to reduce CPU RAM during model quantization'}
```

## File: intel_auto-round/test/test_cpu/schemes/test_scheme.py

Prompts

```
['create an AutoScheme with avg_bits 2 and W2A16 options for model quantization', 'create an AutoScheme with avg_bits 4 and mxfp4 options for mixed precision quantization', 'run AutoRound with a scheme to quantize a model and save the result to a directory', 'test AutoRound with a custom layer_config to override bits, group_size, and sym for specific layers', 'compute the average bits per weight for a quantized model using compute_avg_bits_for_model', 'test the OffloadManager class as a context manager that auto-cleans offloaded model weights on exit', 'test the OffloadManager offload and reload methods to save and restore model block weights to disk', 'test the OffloadManager add_offload_hooks and remove_offload_hooks methods to clear and restore all model blocks', 'test the _clear_module_weights function to zero out weight tensors from a PyTorch module while caching original numel', 'test the AutoScheme dataclass with low_cpu_mem_usage enabled to reduce CPU RAM during model quantization', 'create an AutoRound instance with a scheme like W4A16 to quantize a HuggingFace model', 'call quantize_and_save with format gguf:q4_k_m to export a quantized model in GGUF format', 'pass a layer_config dict to AutoRound to set per-layer bit widths for mixed precision quantization', 'use QuantizationScheme.from_dict with bits and group_size keys to build a custom quantization scheme', 'call parse_available_devices with a device string like auto or cuda:0,cuda:1 to get a device list']
```

Usage

```
{'quantize_model_with_autoround': 'create an AutoRound instance with a scheme like W4A16 to quantize a HuggingFace model', 'save_quantized_model_as_gguf': 'call quantize_and_save with format gguf:q4_k_m to export a quantized model in GGUF format', 'configure_mixed_precision_quantization': 'pass a layer_config dict to AutoRound to set per-layer bit widths for mixed precision quantization', 'create_quantization_scheme_from_dict': 'use QuantizationScheme.from_dict with bits and group_size keys to build a custom quantization scheme', 'parse_available_devices': 'call parse_available_devices with a device string like auto or cuda:0,cuda:1 to get a device list'}
```

