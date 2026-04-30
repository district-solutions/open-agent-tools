# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/layers/quantization/configs/base_config.py

Prompts

```
['create weights for a quantized layer using QuantizeMethodBase.create_weights with layer and weight arguments', 'apply quantized layer weights to an input tensor using QuantizeMethodBase.apply', "create a QuantizationConfig instance from a model's quantization config dictionary using from_config", 'get the QuantizeMethodBase for a specific layer using QuantizationConfig.get_quant_method', 'test if a quantization method class has a custom embedding implementation using method_has_implemented_embedding', 'test if the nunchaku package is available in the current environment', 'create a NunchakuConfig instance with int4 precision and rank 32 for SVDQuant W4A4 quantization', 'build a NunchakuConfig from a dictionary containing precision, rank, and group_size settings', 'build a NunchakuConfig by loading quantization settings from a pretrained model directory', 'run patching of wtscale and wcscales tensors from safetensors weights onto a model for NVFP4 correctness']
```

Usage

```
{'create_weights_QuantizeMethodBase': 'create weights for a quantized layer using QuantizeMethodBase.create_weights with layer and weight arguments', 'apply_QuantizeMethodBase': 'apply quantized layer weights to an input tensor using QuantizeMethodBase.apply', 'from_config_QuantizationConfig': "create a QuantizationConfig instance from a model's quantization config dictionary using from_config", 'get_quant_method_QuantizationConfig': 'get the QuantizeMethodBase for a specific layer using QuantizationConfig.get_quant_method', 'method_has_implemented_embedding': 'test if a quantization method class has a custom embedding implementation using method_has_implemented_embedding'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/layers/quantization/configs/nunchaku_config.py

Prompts

```
['create weights for a quantized layer using QuantizeMethodBase.create_weights with layer and weight arguments', 'apply quantized layer weights to an input tensor using QuantizeMethodBase.apply', "create a QuantizationConfig instance from a model's quantization config dictionary using from_config", 'get the QuantizeMethodBase for a specific layer using QuantizationConfig.get_quant_method', 'test if a quantization method class has a custom embedding implementation using method_has_implemented_embedding', 'test if the nunchaku package is available in the current environment', 'create a NunchakuConfig instance with int4 precision and rank 32 for SVDQuant W4A4 quantization', 'build a NunchakuConfig from a dictionary containing precision, rank, and group_size settings', 'build a NunchakuConfig by loading quantization settings from a pretrained model directory', 'run patching of wtscale and wcscales tensors from safetensors weights onto a model for NVFP4 correctness']
```

Usage

```
{'test_is_nunchaku_available': 'test if the nunchaku package is available in the current environment', 'create_nunchaku_config': 'create a NunchakuConfig instance with int4 precision and rank 32 for SVDQuant W4A4 quantization', 'build_nunchaku_config_from_dict': 'build a NunchakuConfig from a dictionary containing precision, rank, and group_size settings', 'build_nunchaku_config_from_pretrained': 'build a NunchakuConfig by loading quantization settings from a pretrained model directory', 'run_patch_nunchaku_scales': 'run patching of wtscale and wcscales tensors from safetensors weights onto a model for NVFP4 correctness'}
```

