# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/inference/backend.py

Prompts

```
['check if a quantization configuration is compatible with a specified backend for a given device and packing format', 'select the most suitable backend for a model layer based on compatibility and priority ranking', 'dynamically import the correct QuantLinear class for a given backend and quantization configuration', 'find the highest priority backend that supports a given quantization config and device', 'check and log missing library requirements for a backend and display pip install commands', 'convert a HuggingFace model into an AutoRound quantized model by replacing linear layers with quantized layers', 'get a layer-wise quantization configuration dictionary for a given model and quantization config', 'perform post-initialization for quantization backends including AutoGPTQ, GPTQModel, and IPEX layers', 'get a list of available compute devices like cuda, hpu, xpu, mps, and cpu', 'infer the target device from a device_map argument that can be a dict, int, or string']
```

Usage

```
{'check_compatible': 'check if a quantization configuration is compatible with a specified backend for a given device and packing format', 'get_layer_backend': 'select the most suitable backend for a model layer based on compatibility and priority ranking', 'dynamic_import_inference_linear': 'dynamically import the correct QuantLinear class for a given backend and quantization configuration', 'get_highest_priority_backend': 'find the highest priority backend that supports a given quantization config and device', 'process_requirement': 'check and log missing library requirements for a backend and display pip install commands'}
```

## File: intel_auto-round/auto_round/inference/convert_model.py

Prompts

```
['check if a quantization configuration is compatible with a specified backend for a given device and packing format', 'select the most suitable backend for a model layer based on compatibility and priority ranking', 'dynamically import the correct QuantLinear class for a given backend and quantization configuration', 'find the highest priority backend that supports a given quantization config and device', 'check and log missing library requirements for a backend and display pip install commands', 'convert a HuggingFace model into an AutoRound quantized model by replacing linear layers with quantized layers', 'get a layer-wise quantization configuration dictionary for a given model and quantization config', 'perform post-initialization for quantization backends including AutoGPTQ, GPTQModel, and IPEX layers', 'get a list of available compute devices like cuda, hpu, xpu, mps, and cpu', 'infer the target device from a device_map argument that can be a dict, int, or string']
```

Usage

```
{'convert_hf_model': 'convert a HuggingFace model into an AutoRound quantized model by replacing linear layers with quantized layers', 'get_layer_config': 'get a layer-wise quantization configuration dictionary for a given model and quantization config', 'post_init': 'perform post-initialization for quantization backends including AutoGPTQ, GPTQModel, and IPEX layers', 'get_available_devices': 'get a list of available compute devices like cuda, hpu, xpu, mps, and cpu', 'infer_target_device': 'infer the target device from a device_map argument that can be a dict, int, or string'}
```

