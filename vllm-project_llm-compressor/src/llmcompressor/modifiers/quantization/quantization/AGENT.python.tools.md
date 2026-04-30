# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/quantization/quantization/base.py

Prompts

```
['enable post training quantization and quantization aware training for model modules using QuantizationModifier', 'calibrate model weights and activations by running on_start and on_end lifecycle methods of QuantizationModifier', 'apply quantization schemes from config_groups to target modules like Linear layers in a PyTorch model', 'sync activation observer statistics across DDP ranks at epoch boundaries using QuantizationMixin', 'quantize the kv cache of transformer models by specifying a kv_cache_scheme for q_proj and k_proj outputs', 'build a QuantizationMixin to attach quantization schemes, observers, and compression wrappers to a torch model', 'run initialize_quantization on a torch model to attach schemes, observers, and disable quantization until calibration', 'run start_calibration on a torch model to attach calibration hooks, apply calibration status, and enable quantization', 'run end_calibration on a torch model to remove calibration hooks, freeze module quantization, and keep quantization enabled', 'run sync_activation_observers to all-reduce activation observer min/max values across DDP ranks and recompute scale and zero-point']
```

Usage

```
{'enable_ptq_qat_quantization': 'enable post training quantization and quantization aware training for model modules using QuantizationModifier', 'calibrate_model_weights': 'calibrate model weights and activations by running on_start and on_end lifecycle methods of QuantizationModifier', 'apply_quantization_schemes': 'apply quantization schemes from config_groups to target modules like Linear layers in a PyTorch model', 'sync_activation_observers': 'sync activation observer statistics across DDP ranks at epoch boundaries using QuantizationMixin', 'quantize_kv_cache': 'quantize the kv cache of transformer models by specifying a kv_cache_scheme for q_proj and k_proj outputs'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/quantization/quantization/mixin.py

Prompts

```
['enable post training quantization and quantization aware training for model modules using QuantizationModifier', 'calibrate model weights and activations by running on_start and on_end lifecycle methods of QuantizationModifier', 'apply quantization schemes from config_groups to target modules like Linear layers in a PyTorch model', 'sync activation observer statistics across DDP ranks at epoch boundaries using QuantizationMixin', 'quantize the kv cache of transformer models by specifying a kv_cache_scheme for q_proj and k_proj outputs', 'build a QuantizationMixin to attach quantization schemes, observers, and compression wrappers to a torch model', 'run initialize_quantization on a torch model to attach schemes, observers, and disable quantization until calibration', 'run start_calibration on a torch model to attach calibration hooks, apply calibration status, and enable quantization', 'run end_calibration on a torch model to remove calibration hooks, freeze module quantization, and keep quantization enabled', 'run sync_activation_observers to all-reduce activation observer min/max values across DDP ranks and recompute scale and zero-point']
```

Usage

```
{'build_quantization_mixin': 'build a QuantizationMixin to attach quantization schemes, observers, and compression wrappers to a torch model', 'run_initialize_quantization': 'run initialize_quantization on a torch model to attach schemes, observers, and disable quantization until calibration', 'run_start_calibration': 'run start_calibration on a torch model to attach calibration hooks, apply calibration status, and enable quantization', 'run_end_calibration': 'run end_calibration on a torch model to remove calibration hooks, freeze module quantization, and keep quantization enabled', 'run_sync_activation_observers': 'run sync_activation_observers to all-reduce activation observer min/max values across DDP ranks and recompute scale and zero-point'}
```

