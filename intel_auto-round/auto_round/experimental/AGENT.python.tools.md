# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/experimental/attention.py

Prompts

```
['initialize a QuantizedAttentionImpl submodule on an attention module for FP8 query calibration', 'use a context manager to prepare all attention modules for FP8 quantization calibration on a model', 'run the quantized attention forward pass that tracks query max and scale before delegating to the original implementation', 'prepare an attention module for calibration by registering hooked attention with the given config', 'clean up hooked attention parameters and restore the original attention implementation after calibration', 'use the kvcache_quant_context manager to run FP8 KV cache quantization on a PyTorch model', 'initialize a quantized KV cache on an attention module with fp8_e4m3fn dtype', 'freeze module quantization by deleting observers and removing the quantized KV cache', 'register forward pre and output hooks on an attention module for KV cache calibration', 'review the singleton QuantizedKVParameterCache class that extends DynamicCache for FP8 quantized key value caching', 'quantize a PyTorch tensor to FP8 format and return the quantized tensor with its scale', 'update or create a named parameter on a PyTorch module with new tensor data', 'convert a dtype string or torch dtype to a normalized torch dtype for static KV cache', 'check if a PyTorch module is an attention layer by inspecting its class name and attributes', 'remove specified parameters and buffers from all modules in a PyTorch model']
```

Usage

```
{'init_hooked_attention': 'initialize a QuantizedAttentionImpl submodule on an attention module for FP8 query calibration', 'attention_quant_ctx': 'use a context manager to prepare all attention modules for FP8 quantization calibration on a model', 'QuantizedAttentionImpl_forward': 'run the quantized attention forward pass that tracks query max and scale before delegating to the original implementation', 'prep_attention_module_for_calibration': 'prepare an attention module for calibration by registering hooked attention with the given config', 'clean_up_hooked_attention': 'clean up hooked attention parameters and restore the original attention implementation after calibration'}
```

## File: intel_auto-round/auto_round/experimental/kv_cache.py

Prompts

```
['initialize a QuantizedAttentionImpl submodule on an attention module for FP8 query calibration', 'use a context manager to prepare all attention modules for FP8 quantization calibration on a model', 'run the quantized attention forward pass that tracks query max and scale before delegating to the original implementation', 'prepare an attention module for calibration by registering hooked attention with the given config', 'clean up hooked attention parameters and restore the original attention implementation after calibration', 'use the kvcache_quant_context manager to run FP8 KV cache quantization on a PyTorch model', 'initialize a quantized KV cache on an attention module with fp8_e4m3fn dtype', 'freeze module quantization by deleting observers and removing the quantized KV cache', 'register forward pre and output hooks on an attention module for KV cache calibration', 'review the singleton QuantizedKVParameterCache class that extends DynamicCache for FP8 quantized key value caching', 'quantize a PyTorch tensor to FP8 format and return the quantized tensor with its scale', 'update or create a named parameter on a PyTorch module with new tensor data', 'convert a dtype string or torch dtype to a normalized torch dtype for static KV cache', 'check if a PyTorch module is an attention layer by inspecting its class name and attributes', 'remove specified parameters and buffers from all modules in a PyTorch model']
```

Usage

```
{'build_kvcache_quant_context': 'use the kvcache_quant_context manager to run FP8 KV cache quantization on a PyTorch model', 'create_initialize_quantized_kv_cache': 'initialize a quantized KV cache on an attention module with fp8_e4m3fn dtype', 'run_freeze_module_quantization': 'freeze module quantization by deleting observers and removing the quantized KV cache', 'test_prep_attention_module_for_calibration': 'register forward pre and output hooks on an attention module for KV cache calibration', 'review_QuantizedKVParameterCache': 'review the singleton QuantizedKVParameterCache class that extends DynamicCache for FP8 quantized key value caching'}
```

## File: intel_auto-round/auto_round/experimental/utils.py

Prompts

```
['initialize a QuantizedAttentionImpl submodule on an attention module for FP8 query calibration', 'use a context manager to prepare all attention modules for FP8 quantization calibration on a model', 'run the quantized attention forward pass that tracks query max and scale before delegating to the original implementation', 'prepare an attention module for calibration by registering hooked attention with the given config', 'clean up hooked attention parameters and restore the original attention implementation after calibration', 'use the kvcache_quant_context manager to run FP8 KV cache quantization on a PyTorch model', 'initialize a quantized KV cache on an attention module with fp8_e4m3fn dtype', 'freeze module quantization by deleting observers and removing the quantized KV cache', 'register forward pre and output hooks on an attention module for KV cache calibration', 'review the singleton QuantizedKVParameterCache class that extends DynamicCache for FP8 quantized key value caching', 'quantize a PyTorch tensor to FP8 format and return the quantized tensor with its scale', 'update or create a named parameter on a PyTorch module with new tensor data', 'convert a dtype string or torch dtype to a normalized torch dtype for static KV cache', 'check if a PyTorch module is an attention layer by inspecting its class name and attributes', 'remove specified parameters and buffers from all modules in a PyTorch model']
```

Usage

```
{'per_tensor_fp8_qdq': 'quantize a PyTorch tensor to FP8 format and return the quantized tensor with its scale', 'update_parameter_data': 'update or create a named parameter on a PyTorch module with new tensor data', 'normalize_static_kv_dtype': 'convert a dtype string or torch dtype to a normalized torch dtype for static KV cache', 'is_attention_module': 'check if a PyTorch module is an attention layer by inspecting its class name and attributes', 'clean_model_parameters_and_buffers': 'remove specified parameters and buffers from all modules in a PyTorch model'}
```

