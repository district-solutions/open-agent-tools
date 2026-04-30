# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/nn/intrinsic/quantized/modules/bn_relu.py

Prompts

```
['create a quantized BNReLU2d module fused from BatchNorm2d and ReLU for 2D convolutional networks', 'create a quantized BNReLU3d module fused from BatchNorm3d and ReLU for 3D convolutional networks', 'build a forward pass with BNReLU2d using 4D input tensor (N, C, H, W) and quantized parameters', 'build a forward pass with BNReLU3d using 5D input tensor (N, C, D, H, W) and quantized parameters', 'convert a float BNReLU2d or BNReLU3d module to quantized form using from_float or from_reference', 'create a QuantizedConvAdd2d module with given in_channels, out_channels, and kernel_size', 'build a QuantizedConvAdd2d module from a float ConvAdd2d module via from_float', 'create a QuantizedConvAddReLU2d module with given in_channels, out_channels, and kernel_size', 'build a QuantizedConvAddReLU2d module from a reference quantized conv with output scale and zero point', 'test the ConvAdd2d forward pass with 4D input tensor and extra_input tensor', 'create a quantized ConvReLU1d fused module for 1D convolution with ReLU activation', 'create a quantized ConvReLU2d fused module for 2D convolution with ReLU activation', 'create a quantized ConvReLU3d fused module for 3D convolution with ReLU activation', 'build a quantized ConvReLU module from a float intrinsic module using from_float factory method', 'test the quantized ConvReLU forward pass with proper input tensor shape validation', 'create a quantized LinearReLU module fused from Linear and ReLU for inference', 'create a quantized LinearLeakyReLU module fused from Linear and LeakyReLU for onednn backend', 'create a quantized LinearTanh module fused from Linear and Tanh for inference', 'build a quantized LinearReLU module from a reference float model with output scale and zero point']
```

Usage

```
{'create_BNReLU2d_module': 'create a quantized BNReLU2d module fused from BatchNorm2d and ReLU for 2D convolutional networks', 'create_BNReLU3d_module': 'create a quantized BNReLU3d module fused from BatchNorm3d and ReLU for 3D convolutional networks', 'build_quantized_forward_2d': 'build a forward pass with BNReLU2d using 4D input tensor (N, C, H, W) and quantized parameters', 'build_quantized_forward_3d': 'build a forward pass with BNReLU3d using 5D input tensor (N, C, D, H, W) and quantized parameters', 'convert_float_to_quantized': 'convert a float BNReLU2d or BNReLU3d module to quantized form using from_float or from_reference'}
```

## File: pytorch_pytorch/torch/ao/nn/intrinsic/quantized/modules/conv_add.py

Prompts

```
['create a quantized BNReLU2d module fused from BatchNorm2d and ReLU for 2D convolutional networks', 'create a quantized BNReLU3d module fused from BatchNorm3d and ReLU for 3D convolutional networks', 'build a forward pass with BNReLU2d using 4D input tensor (N, C, H, W) and quantized parameters', 'build a forward pass with BNReLU3d using 5D input tensor (N, C, D, H, W) and quantized parameters', 'convert a float BNReLU2d or BNReLU3d module to quantized form using from_float or from_reference', 'create a QuantizedConvAdd2d module with given in_channels, out_channels, and kernel_size', 'build a QuantizedConvAdd2d module from a float ConvAdd2d module via from_float', 'create a QuantizedConvAddReLU2d module with given in_channels, out_channels, and kernel_size', 'build a QuantizedConvAddReLU2d module from a reference quantized conv with output scale and zero point', 'test the ConvAdd2d forward pass with 4D input tensor and extra_input tensor', 'create a quantized ConvReLU1d fused module for 1D convolution with ReLU activation', 'create a quantized ConvReLU2d fused module for 2D convolution with ReLU activation', 'create a quantized ConvReLU3d fused module for 3D convolution with ReLU activation', 'build a quantized ConvReLU module from a float intrinsic module using from_float factory method', 'test the quantized ConvReLU forward pass with proper input tensor shape validation', 'create a quantized LinearReLU module fused from Linear and ReLU for inference', 'create a quantized LinearLeakyReLU module fused from Linear and LeakyReLU for onednn backend', 'create a quantized LinearTanh module fused from Linear and Tanh for inference', 'build a quantized LinearReLU module from a reference float model with output scale and zero point']
```

Usage

```
{'create_ConvAdd2d_module': 'create a QuantizedConvAdd2d module with given in_channels, out_channels, and kernel_size', 'build_ConvAdd2d_from_float': 'build a QuantizedConvAdd2d module from a float ConvAdd2d module via from_float', 'create_ConvAddReLU2d_module': 'create a QuantizedConvAddReLU2d module with given in_channels, out_channels, and kernel_size', 'build_ConvAddReLU2d_from_reference': 'build a QuantizedConvAddReLU2d module from a reference quantized conv with output scale and zero point', 'test_ConvAdd2d_forward': 'test the ConvAdd2d forward pass with 4D input tensor and extra_input tensor'}
```

## File: pytorch_pytorch/torch/ao/nn/intrinsic/quantized/modules/conv_relu.py

Prompts

```
['create a quantized BNReLU2d module fused from BatchNorm2d and ReLU for 2D convolutional networks', 'create a quantized BNReLU3d module fused from BatchNorm3d and ReLU for 3D convolutional networks', 'build a forward pass with BNReLU2d using 4D input tensor (N, C, H, W) and quantized parameters', 'build a forward pass with BNReLU3d using 5D input tensor (N, C, D, H, W) and quantized parameters', 'convert a float BNReLU2d or BNReLU3d module to quantized form using from_float or from_reference', 'create a QuantizedConvAdd2d module with given in_channels, out_channels, and kernel_size', 'build a QuantizedConvAdd2d module from a float ConvAdd2d module via from_float', 'create a QuantizedConvAddReLU2d module with given in_channels, out_channels, and kernel_size', 'build a QuantizedConvAddReLU2d module from a reference quantized conv with output scale and zero point', 'test the ConvAdd2d forward pass with 4D input tensor and extra_input tensor', 'create a quantized ConvReLU1d fused module for 1D convolution with ReLU activation', 'create a quantized ConvReLU2d fused module for 2D convolution with ReLU activation', 'create a quantized ConvReLU3d fused module for 3D convolution with ReLU activation', 'build a quantized ConvReLU module from a float intrinsic module using from_float factory method', 'test the quantized ConvReLU forward pass with proper input tensor shape validation', 'create a quantized LinearReLU module fused from Linear and ReLU for inference', 'create a quantized LinearLeakyReLU module fused from Linear and LeakyReLU for onednn backend', 'create a quantized LinearTanh module fused from Linear and Tanh for inference', 'build a quantized LinearReLU module from a reference float model with output scale and zero point']
```

Usage

```
{'create_ConvReLU1d': 'create a quantized ConvReLU1d fused module for 1D convolution with ReLU activation', 'create_ConvReLU2d': 'create a quantized ConvReLU2d fused module for 2D convolution with ReLU activation', 'create_ConvReLU3d': 'create a quantized ConvReLU3d fused module for 3D convolution with ReLU activation', 'build_ConvReLU_from_float': 'build a quantized ConvReLU module from a float intrinsic module using from_float factory method', 'test_ConvReLU_forward': 'test the quantized ConvReLU forward pass with proper input tensor shape validation'}
```

## File: pytorch_pytorch/torch/ao/nn/intrinsic/quantized/modules/linear_relu.py

Prompts

```
['create a quantized BNReLU2d module fused from BatchNorm2d and ReLU for 2D convolutional networks', 'create a quantized BNReLU3d module fused from BatchNorm3d and ReLU for 3D convolutional networks', 'build a forward pass with BNReLU2d using 4D input tensor (N, C, H, W) and quantized parameters', 'build a forward pass with BNReLU3d using 5D input tensor (N, C, D, H, W) and quantized parameters', 'convert a float BNReLU2d or BNReLU3d module to quantized form using from_float or from_reference', 'create a QuantizedConvAdd2d module with given in_channels, out_channels, and kernel_size', 'build a QuantizedConvAdd2d module from a float ConvAdd2d module via from_float', 'create a QuantizedConvAddReLU2d module with given in_channels, out_channels, and kernel_size', 'build a QuantizedConvAddReLU2d module from a reference quantized conv with output scale and zero point', 'test the ConvAdd2d forward pass with 4D input tensor and extra_input tensor', 'create a quantized ConvReLU1d fused module for 1D convolution with ReLU activation', 'create a quantized ConvReLU2d fused module for 2D convolution with ReLU activation', 'create a quantized ConvReLU3d fused module for 3D convolution with ReLU activation', 'build a quantized ConvReLU module from a float intrinsic module using from_float factory method', 'test the quantized ConvReLU forward pass with proper input tensor shape validation', 'create a quantized LinearReLU module fused from Linear and ReLU for inference', 'create a quantized LinearLeakyReLU module fused from Linear and LeakyReLU for onednn backend', 'create a quantized LinearTanh module fused from Linear and Tanh for inference', 'build a quantized LinearReLU module from a reference float model with output scale and zero point']
```

Usage

```
{'create_quantized_linear_relu': 'create a quantized LinearReLU module fused from Linear and ReLU for inference', 'create_quantized_linear_leaky_relu': 'create a quantized LinearLeakyReLU module fused from Linear and LeakyReLU for onednn backend', 'create_quantized_linear_tanh': 'create a quantized LinearTanh module fused from Linear and Tanh for inference', 'convert_float_to_quantized': 'convert a float LinearReLU module to a quantized LinearReLU using from_float', 'build_quantized_linear_from_reference': 'build a quantized LinearReLU module from a reference float model with output scale and zero point'}
```

