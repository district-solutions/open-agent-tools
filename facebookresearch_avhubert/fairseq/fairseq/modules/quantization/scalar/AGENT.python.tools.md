# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/modules/quantization/scalar/ops.py

Prompts

```
['emulate integer quantization on a tensor using a specified bit width and method', 'quantize a tensor using a given scale and zero point with clamping', 'emulate 8-bit integer quantization using a histogram observer to compute scale and zero point', 'emulate per-channel 8-bit integer quantization using a min-max observer on the last axis', 'emulate per-tensor 8-bit integer quantization using a min-max observer to compute scale and zero point', 'replace all nn.Linear, nn.Embedding, and nn.Conv2d layers in a PyTorch model with scalar quantized counterparts using histogram-based quantization', 'quantize a PyTorch model with configurable noise probability p and bit width to simulate mixed-precision training', 'quantize a model and update quantization parameters every N training steps using the update_step parameter', 'review the MAPPING dictionary that maps nn.Linear to IntLinear, nn.Embedding to IntEmbedding, and nn.Conv2d to IntConv2d for scalar quantization', 'summarize the quantize_model_ function that replaces supported layers with quantized versions and attaches ActivationQuantizer hooks for post-activation quantization']
```

Usage

```
{'emulate_int': 'emulate integer quantization on a tensor using a specified bit width and method', 'quantize': 'quantize a tensor using a given scale and zero point with clamping', 'emulate_int8_histogram': 'emulate 8-bit integer quantization using a histogram observer to compute scale and zero point', 'emulate_int8_channel': 'emulate per-channel 8-bit integer quantization using a min-max observer on the last axis', 'emulate_int8_tensor': 'emulate per-tensor 8-bit integer quantization using a min-max observer to compute scale and zero point'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/modules/quantization/scalar/utils.py

Prompts

```
['emulate integer quantization on a tensor using a specified bit width and method', 'quantize a tensor using a given scale and zero point with clamping', 'emulate 8-bit integer quantization using a histogram observer to compute scale and zero point', 'emulate per-channel 8-bit integer quantization using a min-max observer on the last axis', 'emulate per-tensor 8-bit integer quantization using a min-max observer to compute scale and zero point', 'replace all nn.Linear, nn.Embedding, and nn.Conv2d layers in a PyTorch model with scalar quantized counterparts using histogram-based quantization', 'quantize a PyTorch model with configurable noise probability p and bit width to simulate mixed-precision training', 'quantize a model and update quantization parameters every N training steps using the update_step parameter', 'review the MAPPING dictionary that maps nn.Linear to IntLinear, nn.Embedding to IntEmbedding, and nn.Conv2d to IntConv2d for scalar quantization', 'summarize the quantize_model_ function that replaces supported layers with quantized versions and attaches ActivationQuantizer hooks for post-activation quantization']
```

Usage

```
{'quantize_model_inplace': 'replace all nn.Linear, nn.Embedding, and nn.Conv2d layers in a PyTorch model with scalar quantized counterparts using histogram-based quantization', 'quantize_model_with_noise': 'quantize a PyTorch model with configurable noise probability p and bit width to simulate mixed-precision training', 'quantize_model_periodic_update': 'quantize a model and update quantization parameters every N training steps using the update_step parameter', 'review_MAPPING': 'review the MAPPING dictionary that maps nn.Linear to IntLinear, nn.Embedding to IntEmbedding, and nn.Conv2d to IntConv2d for scalar quantization', 'summarize_quantize_model_': 'summarize the quantize_model_ function that replaces supported layers with quantized versions and attaches ActivationQuantizer hooks for post-activation quantization'}
```

