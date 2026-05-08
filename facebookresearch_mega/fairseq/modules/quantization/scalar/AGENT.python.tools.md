# Agent Python Tools

- repo: facebookresearch/mega
- repo_uri: https://github.com/facebookresearch/mega

## File: facebookresearch_mega/fairseq/modules/quantization/scalar/ops.py

Prompts

```
['quantize a PyTorch tensor using histogram-based int8 quantization with auto-computed scale and zero point', 'quantize a PyTorch tensor using per-channel symmetric int8 quantization with auto-computed scale and zero point', 'quantize a PyTorch tensor using min-max int8 quantization with auto-computed scale and zero point', 'quantize a PyTorch tensor with a provided scale and zero point using clamp and round', 'dispatch to a specific int quantization emulation function by bits and method name', 'replace all Linear, Embedding, and Conv2d layers in a PyTorch model with scalar quantized counterparts using quantize_model_', 'review the quantize_model_ function parameters p, bits, and update_step to tune quantization noise and precision', 'inspect the MAPPING dictionary to see which PyTorch modules map to IntLinear, IntEmbedding, and IntConv2d quantized variants', 'test quantize_model_ on a model and verify the returned list of quantized layer names', 'refactor quantize_model_ to customize the ActivationQuantizer parameters for post-activation quantization']
```

Usage

```
{'emulate_int8_histogram_quantize': 'quantize a PyTorch tensor using histogram-based int8 quantization with auto-computed scale and zero point', 'emulate_int8_channel_quantize': 'quantize a PyTorch tensor using per-channel symmetric int8 quantization with auto-computed scale and zero point', 'emulate_int8_tensor_quantize': 'quantize a PyTorch tensor using min-max int8 quantization with auto-computed scale and zero point', 'quantize_tensor_manual': 'quantize a PyTorch tensor with a provided scale and zero point using clamp and round', 'emulate_int_dispatch': 'dispatch to a specific int quantization emulation function by bits and method name'}
```

## File: facebookresearch_mega/fairseq/modules/quantization/scalar/utils.py

Prompts

```
['quantize a PyTorch tensor using histogram-based int8 quantization with auto-computed scale and zero point', 'quantize a PyTorch tensor using per-channel symmetric int8 quantization with auto-computed scale and zero point', 'quantize a PyTorch tensor using min-max int8 quantization with auto-computed scale and zero point', 'quantize a PyTorch tensor with a provided scale and zero point using clamp and round', 'dispatch to a specific int quantization emulation function by bits and method name', 'replace all Linear, Embedding, and Conv2d layers in a PyTorch model with scalar quantized counterparts using quantize_model_', 'review the quantize_model_ function parameters p, bits, and update_step to tune quantization noise and precision', 'inspect the MAPPING dictionary to see which PyTorch modules map to IntLinear, IntEmbedding, and IntConv2d quantized variants', 'test quantize_model_ on a model and verify the returned list of quantized layer names', 'refactor quantize_model_ to customize the ActivationQuantizer parameters for post-activation quantization']
```

Usage

```
{'quantize_model_inplace': 'replace all Linear, Embedding, and Conv2d layers in a PyTorch model with scalar quantized counterparts using quantize_model_', 'review_quantize_model_params': 'review the quantize_model_ function parameters p, bits, and update_step to tune quantization noise and precision', 'inspect_MAPPING_dict': 'inspect the MAPPING dictionary to see which PyTorch modules map to IntLinear, IntEmbedding, and IntConv2d quantized variants', 'test_quantize_model_layers': 'test quantize_model_ on a model and verify the returned list of quantized layer names', 'refactor_quantize_model_activation': 'refactor quantize_model_ to customize the ActivationQuantizer parameters for post-activation quantization'}
```

