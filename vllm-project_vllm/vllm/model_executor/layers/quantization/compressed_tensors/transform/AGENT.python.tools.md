# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/model_executor/layers/quantization/compressed_tensors/transform/linear.py

Prompts

```
['create a CompressedTensorsLinearTransformMethod wrapping a quant method with input and output Hadamard transforms', 'build a CompressedTensorsLinearTransformMethod from a quant method and transform schemes via from_schemes factory', 'run input and output transforms on tensor activations before and after the quantized linear layer apply', 'test that input and output transform schemes are consistent across all partitions', "create a function to extract input and output transform schemes from a layer's TransformConfig", 'create a HadamardTransform module with transforms config, layer, weight loader, and partition sizes', 'run the HadamardTransform forward pass to apply hadamard or dense transform to input tensors', 'test the HadamardTransform process_weights_after_loading method to precompute scales after weight loading', 'build the HadamardTransform _get_weight_size helper to determine weight size from scheme and layer type', 'review the HadamardTransform _validate_input_transforms method to validate shared tensor partitions']
```

Usage

```
{'create_CompressedTensorsLinearTransformMethod': 'create a CompressedTensorsLinearTransformMethod wrapping a quant method with input and output Hadamard transforms', 'build_from_schemes': 'build a CompressedTensorsLinearTransformMethod from a quant method and transform schemes via from_schemes factory', 'run_apply_transforms': 'run input and output transforms on tensor activations before and after the quantized linear layer apply', 'test_validate_tfm_schemes': 'test that input and output transform schemes are consistent across all partitions', 'create_get_linear_transform_schemes': "create a function to extract input and output transform schemes from a layer's TransformConfig"}
```

## File: vllm-project_vllm/vllm/model_executor/layers/quantization/compressed_tensors/transform/module.py

Prompts

```
['create a CompressedTensorsLinearTransformMethod wrapping a quant method with input and output Hadamard transforms', 'build a CompressedTensorsLinearTransformMethod from a quant method and transform schemes via from_schemes factory', 'run input and output transforms on tensor activations before and after the quantized linear layer apply', 'test that input and output transform schemes are consistent across all partitions', "create a function to extract input and output transform schemes from a layer's TransformConfig", 'create a HadamardTransform module with transforms config, layer, weight loader, and partition sizes', 'run the HadamardTransform forward pass to apply hadamard or dense transform to input tensors', 'test the HadamardTransform process_weights_after_loading method to precompute scales after weight loading', 'build the HadamardTransform _get_weight_size helper to determine weight size from scheme and layer type', 'review the HadamardTransform _validate_input_transforms method to validate shared tensor partitions']
```

Usage

```
{'create_HadamardTransform': 'create a HadamardTransform module with transforms config, layer, weight loader, and partition sizes', 'run_HadamardTransform_forward': 'run the HadamardTransform forward pass to apply hadamard or dense transform to input tensors', 'test_HadamardTransform_process_weights_after_loading': 'test the HadamardTransform process_weights_after_loading method to precompute scales after weight loading', 'build_HadamardTransform_get_weight_size': 'build the HadamardTransform _get_weight_size helper to determine weight size from scheme and layer type', 'review_HadamardTransform_validate_input_transforms': 'review the HadamardTransform _validate_input_transforms method to validate shared tensor partitions'}
```

