# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/quantization/pt2e/representation/rewrite.py

Prompts

```
['refactor a GraphModule to rewrite quantized linear patterns into reference representations', 'refactor a GraphModule to rewrite quantized conv2d patterns into reference representations', 'refactor a GraphModule to rewrite quantized add and add relu patterns into reference representations', 'refactor a GraphModule to rewrite quantized max pool2d patterns into reference representations', 'refactor a GraphModule to rewrite quantize and dequantize per tensor and per channel patterns into reference representations', 'test the reference_representation_rewrite function on a GraphModule to apply all quantization pattern rewrites', 'build a quantized linear pattern by pairing QDQ operations with their reference int8 computation representation', 'build a quantized conv2d pattern by pairing QDQ operations with their reference int8 computation representation', 'build a quantize per tensor int8 pattern with its reference rounded computation representation', 'build a list of _RewriteInfo objects containing example inputs, patterns, replacements, and post-transform functions']
```

Usage

```
{'refactor_model_quantized_linear': 'refactor a GraphModule to rewrite quantized linear patterns into reference representations', 'refactor_model_quantized_conv2d': 'refactor a GraphModule to rewrite quantized conv2d patterns into reference representations', 'refactor_model_quantized_add': 'refactor a GraphModule to rewrite quantized add and add relu patterns into reference representations', 'refactor_model_quantized_max_pool2d': 'refactor a GraphModule to rewrite quantized max pool2d patterns into reference representations', 'refactor_model_quantize_ops': 'refactor a GraphModule to rewrite quantize and dequantize per tensor and per channel patterns into reference representations', 'test_reference_representation_rewrite': 'test the reference_representation_rewrite function on a GraphModule to apply all quantization pattern rewrites', 'build_quantized_linear_pattern': 'build a quantized linear pattern by pairing QDQ operations with their reference int8 computation representation', 'build_quantized_conv2d_pattern': 'build a quantized conv2d pattern by pairing QDQ operations with their reference int8 computation representation', 'build_quantize_per_tensor_pattern': 'build a quantize per tensor int8 pattern with its reference rounded computation representation', 'build_rewrite_info_list': 'build a list of _RewriteInfo objects containing example inputs, patterns, replacements, and post-transform functions'}
```

