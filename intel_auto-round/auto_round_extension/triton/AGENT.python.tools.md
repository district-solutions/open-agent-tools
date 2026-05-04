# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round_extension/triton/qlinear_tritonv2.py

Prompts

```
['create a QuantLinear layer with 4-bit quantization, group size 128, and 512 input and output features', "pack a linear layer's weights into the QuantLinear module using provided scales and zeros", 'run a forward pass through a QuantLinear layer with a float16 input tensor', 'warm up the autotune cache for all QuantLinear layers in a model with sequence length 2048', 'review the QuantLinear __init__ method to verify bit width and feature divisibility constraints', 'create a QuantLinear module with 4-bit quantization and group size 128 for a given input and output feature size', 'run a forward pass through a QuantLinear layer with a float16 input tensor to get quantized output', 'warmup the autotune cache for all QuantLinear layers in a model with a specified sequence length', 'refactor the QuantLinear forward method to support additional input shapes or dtype conversions']
```

Usage

```
{'create_quantlinear_layer': 'create a QuantLinear layer with 4-bit quantization, group size 128, and 512 input and output features', 'pack_quantlinear_weights': "pack a linear layer's weights into the QuantLinear module using provided scales and zeros", 'run_quantlinear_forward': 'run a forward pass through a QuantLinear layer with a float16 input tensor', 'warmup_quantlinear_autotune': 'warm up the autotune cache for all QuantLinear layers in a model with sequence length 2048', 'review_quantlinear_init': 'review the QuantLinear __init__ method to verify bit width and feature divisibility constraints'}
```

## File: intel_auto-round/auto_round_extension/triton/qlinear_tritonv2_zp.py

Prompts

```
['create a QuantLinear layer with 4-bit quantization, group size 128, and 512 input and output features', "pack a linear layer's weights into the QuantLinear module using provided scales and zeros", 'run a forward pass through a QuantLinear layer with a float16 input tensor', 'warm up the autotune cache for all QuantLinear layers in a model with sequence length 2048', 'review the QuantLinear __init__ method to verify bit width and feature divisibility constraints', 'create a QuantLinear module with 4-bit quantization and group size 128 for a given input and output feature size', 'run a forward pass through a QuantLinear layer with a float16 input tensor to get quantized output', 'warmup the autotune cache for all QuantLinear layers in a model with a specified sequence length', 'refactor the QuantLinear forward method to support additional input shapes or dtype conversions']
```

Usage

```
{'create_quantized_linear_layer': 'create a QuantLinear module with 4-bit quantization and group size 128 for a given input and output feature size', 'run_quantized_forward_pass': 'run a forward pass through a QuantLinear layer with a float16 input tensor to get quantized output', 'warmup_quantized_kernel_cache': 'warmup the autotune cache for all QuantLinear layers in a model with a specified sequence length', 'review_quantlinear_init': 'review the QuantLinear __init__ method to understand buffer registration for qweight, qzeros, and scales', 'refactor_quantlinear_forward': 'refactor the QuantLinear forward method to support additional input shapes or dtype conversions'}
```

