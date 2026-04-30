# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/nn/intrinsic/quantized/dynamic/modules/linear_relu.py

Prompts

```
['create a DynamicQuantizedLinearReLU module with specified input and output features for dynamic quantization', 'run a forward pass on a DynamicQuantizedLinearReLU module with a float tensor input and return quantized output', 'build a DynamicQuantizedLinearReLU from a float LinearReLU module using the from_float class method', 'test the DynamicQuantizedLinearReLU module supports both qint8 and float16 quantization dtypes', 'refactor the forward method of DynamicQuantizedLinearReLU to dispatch to quantized linear_relu_dynamic ops based on dtype']
```

Usage

```
{'create_linear_relu_module': 'create a DynamicQuantizedLinearReLU module with specified input and output features for dynamic quantization', 'run_linear_relu_forward': 'run a forward pass on a DynamicQuantizedLinearReLU module with a float tensor input and return quantized output', 'build_from_float_module': 'build a DynamicQuantizedLinearReLU from a float LinearReLU module using the from_float class method', 'test_quantized_dtype_support': 'test the DynamicQuantizedLinearReLU module supports both qint8 and float16 quantization dtypes', 'refactor_linear_relu_forward': 'refactor the forward method of DynamicQuantizedLinearReLU to dispatch to quantized linear_relu_dynamic ops based on dtype'}
```

