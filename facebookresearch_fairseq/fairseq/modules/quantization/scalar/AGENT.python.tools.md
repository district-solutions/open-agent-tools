# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/modules/quantization/scalar/ops.py

Prompts

```
['emulate integer quantization on a tensor using a specified method like histogram, channel, or tensor', 'quantize a tensor using a given scale, zero point, and bit width with clamping', 'emulate 8-bit integer quantization using a histogram observer to compute scale and zero point', 'emulate per-channel 8-bit integer quantization using a per-channel min-max observer', 'emulate 8-bit integer quantization using a min-max observer to compute scale and zero point', 'quantize a PyTorch model in-place by replacing Linear, Embedding, and Conv2d layers with scalar quantized counterparts', 'quantize a model with configurable noise probability p and bit width for weight and activation quantization', 'quantize a model using the histogram method to compute quantization parameters every update_step training steps', 'review the MAPPING dict that maps nn.Linear, nn.Embedding, and nn.Conv2d to their IntLinear, IntEmbedding, and IntConv2d quantized counterparts', 'summarize the quantize_model_ function that replaces supported layers with quantized modules and registers ActivationQuantizer hooks for post-activation quantization']
```

Usage

```
{'emulate_int': 'emulate integer quantization on a tensor using a specified method like histogram, channel, or tensor', 'quantize': 'quantize a tensor using a given scale, zero point, and bit width with clamping', 'emulate_int8_histogram': 'emulate 8-bit integer quantization using a histogram observer to compute scale and zero point', 'emulate_int8_channel': 'emulate per-channel 8-bit integer quantization using a per-channel min-max observer', 'emulate_int8_tensor': 'emulate 8-bit integer quantization using a min-max observer to compute scale and zero point'}
```

## File: facebookresearch_fairseq/fairseq/modules/quantization/scalar/utils.py

Prompts

```
['emulate integer quantization on a tensor using a specified method like histogram, channel, or tensor', 'quantize a tensor using a given scale, zero point, and bit width with clamping', 'emulate 8-bit integer quantization using a histogram observer to compute scale and zero point', 'emulate per-channel 8-bit integer quantization using a per-channel min-max observer', 'emulate 8-bit integer quantization using a min-max observer to compute scale and zero point', 'quantize a PyTorch model in-place by replacing Linear, Embedding, and Conv2d layers with scalar quantized counterparts', 'quantize a model with configurable noise probability p and bit width for weight and activation quantization', 'quantize a model using the histogram method to compute quantization parameters every update_step training steps', 'review the MAPPING dict that maps nn.Linear, nn.Embedding, and nn.Conv2d to their IntLinear, IntEmbedding, and IntConv2d quantized counterparts', 'summarize the quantize_model_ function that replaces supported layers with quantized modules and registers ActivationQuantizer hooks for post-activation quantization']
```

Usage

```
{'quantize_model_inplace': 'quantize a PyTorch model in-place by replacing Linear, Embedding, and Conv2d layers with scalar quantized counterparts', 'quantize_model_with_noise': 'quantize a model with configurable noise probability p and bit width for weight and activation quantization', 'quantize_model_histogram_method': 'quantize a model using the histogram method to compute quantization parameters every update_step training steps', 'review_MAPPING': 'review the MAPPING dict that maps nn.Linear, nn.Embedding, and nn.Conv2d to their IntLinear, IntEmbedding, and IntConv2d quantized counterparts', 'summarize_quantize_model_': 'summarize the quantize_model_ function that replaces supported layers with quantized modules and registers ActivationQuantizer hooks for post-activation quantization'}
```

