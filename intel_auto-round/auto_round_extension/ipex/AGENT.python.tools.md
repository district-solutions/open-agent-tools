# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round_extension/ipex/qlinear_ipex_awq.py

Prompts

```
['create a QuantLinear module with 4-bit quantization for Intel XPU or CPU inference', 'build a QuantLinear module from an existing nn.Linear layer using the from_linear class method', 'run the forward pass of a QuantLinear module on input tensor x using IPEX quantized kernels', 'review the post_init method that initializes the IPEX weight-only quantized linear layer from quantized weights', 'summarize the QuantLinear registered buffers including qweight, qzeros, scales, and bias tensors', 'create a QuantLinear module with 4-bit GPTQ quantization for Intel IPEX inference', 'pack a linear layer weight into the QuantLinear 4-bit GPTQ quantized format', 'initialize the IPEX weight-only quantized linear backend after packing QuantLinear weights', 'unpack quantized weight and zero tensors to 8-bit signed format using unpack_to_8bit_signed', 'dequantize packed GPTQ weights back to full precision using dequantize_weight']
```

Usage

```
{'create_quantlinear_4bit': 'create a QuantLinear module with 4-bit quantization for Intel XPU or CPU inference', 'build_quantlinear_from_linear': 'build a QuantLinear module from an existing nn.Linear layer using the from_linear class method', 'run_quantlinear_forward': 'run the forward pass of a QuantLinear module on input tensor x using IPEX quantized kernels', 'review_quantlinear_post_init': 'review the post_init method that initializes the IPEX weight-only quantized linear layer from quantized weights', 'summarize_quantlinear_buffers': 'summarize the QuantLinear registered buffers including qweight, qzeros, scales, and bias tensors'}
```

## File: intel_auto-round/auto_round_extension/ipex/qlinear_ipex_gptq.py

Prompts

```
['create a QuantLinear module with 4-bit quantization for Intel XPU or CPU inference', 'build a QuantLinear module from an existing nn.Linear layer using the from_linear class method', 'run the forward pass of a QuantLinear module on input tensor x using IPEX quantized kernels', 'review the post_init method that initializes the IPEX weight-only quantized linear layer from quantized weights', 'summarize the QuantLinear registered buffers including qweight, qzeros, scales, and bias tensors', 'create a QuantLinear module with 4-bit GPTQ quantization for Intel IPEX inference', 'pack a linear layer weight into the QuantLinear 4-bit GPTQ quantized format', 'initialize the IPEX weight-only quantized linear backend after packing QuantLinear weights', 'unpack quantized weight and zero tensors to 8-bit signed format using unpack_to_8bit_signed', 'dequantize packed GPTQ weights back to full precision using dequantize_weight']
```

Usage

```
{'create_quantlinear_layer': 'create a QuantLinear module with 4-bit GPTQ quantization for Intel IPEX inference', 'pack_quantlinear_weights': 'pack a linear layer weight into the QuantLinear 4-bit GPTQ quantized format', 'post_init_quantlinear': 'initialize the IPEX weight-only quantized linear backend after packing QuantLinear weights', 'unpack_quantized_weights': 'unpack quantized weight and zero tensors to 8-bit signed format using unpack_to_8bit_signed', 'dequantize_weight': 'dequantize packed GPTQ weights back to full precision using dequantize_weight'}
```

