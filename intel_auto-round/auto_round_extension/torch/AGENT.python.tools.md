# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round_extension/torch/qlinear_torch.py

Prompts

```
['create a QuantLinear layer with 4-bit quantization for a given input and output feature size', 'pack linear layer weights into 2, 4, or 8-bit quantized format using pack_248_bits method', 'pack linear layer weights into 3-bit quantized format using pack_3bits method', 'run a forward pass through a QuantLinear layer to compute quantized output from input tensor', 'get or create a device-specific 3-bit weight format tensor for quantized unpacking operations', 'create a QuantLinear module with 2-bit quantization for a given infeatures and outfeatures size', 'create a QuantLinear module with 4-bit quantization and custom group size for model compression', 'run forward pass through a QuantLinear module to compute quantized linear layer output']
```

Usage

```
{'create_quantlinear_layer': 'create a QuantLinear layer with 4-bit quantization for a given input and output feature size', 'pack_weights_248_bits': 'pack linear layer weights into 2, 4, or 8-bit quantized format using pack_248_bits method', 'pack_weights_3bits': 'pack linear layer weights into 3-bit quantized format using pack_3bits method', 'run_quantized_forward': 'run a forward pass through a QuantLinear layer to compute quantized output from input tensor', 'get_wf_3bits_tensor': 'get or create a device-specific 3-bit weight format tensor for quantized unpacking operations'}
```

## File: intel_auto-round/auto_round_extension/torch/qlinear_torch_zp.py

Prompts

```
['create a QuantLinear layer with 4-bit quantization for a given input and output feature size', 'pack linear layer weights into 2, 4, or 8-bit quantized format using pack_248_bits method', 'pack linear layer weights into 3-bit quantized format using pack_3bits method', 'run a forward pass through a QuantLinear layer to compute quantized output from input tensor', 'get or create a device-specific 3-bit weight format tensor for quantized unpacking operations', 'create a QuantLinear module with 2-bit quantization for a given infeatures and outfeatures size', 'create a QuantLinear module with 4-bit quantization and custom group size for model compression', 'run forward pass through a QuantLinear module to compute quantized linear layer output']
```

Usage

```
{'create_quantlinear_2bit': 'create a QuantLinear module with 2-bit quantization for a given infeatures and outfeatures size', 'create_quantlinear_4bit': 'create a QuantLinear module with 4-bit quantization and custom group size for model compression', 'pack_weights_248_bits': 'pack linear layer weights into 2, 4, or 8-bit quantized format using pack_248_bits method', 'pack_weights_3bits': 'pack linear layer weights into 3-bit quantized format using pack_3bits method with scales and zeros', 'run_quantlinear_forward': 'run forward pass through a QuantLinear module to compute quantized linear layer output'}
```

