# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/quantization/scalar/ops.py

Prompts

```
['quantize a PyTorch tensor to int8 using a histogram observer for scale and zero point calculation', 'quantize a PyTorch tensor to int8 using per-channel min-max observer for scale and zero point calculation', 'quantize a PyTorch tensor to int8 using a min-max observer for scale and zero point calculation', 'quantize a PyTorch tensor using provided scale and zero point parameters with clamping to 0-255 range', 'dispatch to a specific int quantization function by bits and method name using dynamic lookup', 'replace all linear, embedding, and conv2d layers in a PyTorch model with scalar quantized counterparts', 'quantize a PyTorch model using 4-bit scalar quantization with histogram method for all supported layers', 'quantize a PyTorch model with zero quantization noise for inference-only scalar quantization of all layers', 'review the MAPPING dictionary that maps nn.Linear, nn.Embedding, and nn.Conv2d to their IntQuantized counterparts', 'summarize the quantize_model_ function that replaces model layers with scalar quantized modules and registers activation quantizer hooks']
```

Usage

```
{'emulate_int8_histogram_quantize': 'quantize a PyTorch tensor to int8 using a histogram observer for scale and zero point calculation', 'emulate_int8_channel_quantize': 'quantize a PyTorch tensor to int8 using per-channel min-max observer for scale and zero point calculation', 'emulate_int8_tensor_quantize': 'quantize a PyTorch tensor to int8 using a min-max observer for scale and zero point calculation', 'quantize_with_params': 'quantize a PyTorch tensor using provided scale and zero point parameters with clamping to 0-255 range', 'emulate_int_dispatch': 'dispatch to a specific int quantization function by bits and method name using dynamic lookup'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/quantization/scalar/utils.py

Prompts

```
['quantize a PyTorch tensor to int8 using a histogram observer for scale and zero point calculation', 'quantize a PyTorch tensor to int8 using per-channel min-max observer for scale and zero point calculation', 'quantize a PyTorch tensor to int8 using a min-max observer for scale and zero point calculation', 'quantize a PyTorch tensor using provided scale and zero point parameters with clamping to 0-255 range', 'dispatch to a specific int quantization function by bits and method name using dynamic lookup', 'replace all linear, embedding, and conv2d layers in a PyTorch model with scalar quantized counterparts', 'quantize a PyTorch model using 4-bit scalar quantization with histogram method for all supported layers', 'quantize a PyTorch model with zero quantization noise for inference-only scalar quantization of all layers', 'review the MAPPING dictionary that maps nn.Linear, nn.Embedding, and nn.Conv2d to their IntQuantized counterparts', 'summarize the quantize_model_ function that replaces model layers with scalar quantized modules and registers activation quantizer hooks']
```

Usage

```
{'quantize_model_inplace': 'replace all linear, embedding, and conv2d layers in a PyTorch model with scalar quantized counterparts', 'quantize_model_with_custom_bits': 'quantize a PyTorch model using 4-bit scalar quantization with histogram method for all supported layers', 'quantize_model_no_noise': 'quantize a PyTorch model with zero quantization noise for inference-only scalar quantization of all layers', 'review_MAPPING': 'review the MAPPING dictionary that maps nn.Linear, nn.Embedding, and nn.Conv2d to their IntQuantized counterparts', 'summarize_quantize_model_': 'summarize the quantize_model_ function that replaces model layers with scalar quantized modules and registers activation quantizer hooks'}
```

