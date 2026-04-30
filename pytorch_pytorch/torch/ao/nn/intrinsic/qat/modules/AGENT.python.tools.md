# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/nn/intrinsic/qat/modules/conv_fused.py

Prompts

```
['create a ConvBn2d QAT module fused from Conv2d and BatchNorm2d with fake quantization for weight', 'build a ConvBnReLU2d QAT module fused from Conv2d, BatchNorm2d and ReLU with weight fake quantization', 'test the from_float method to convert a float Conv2d+BatchNorm2d module to a QAT ConvBn2d module', 'refactor a QAT ConvBn2d module back to a float fused ConvReLU2d module using the to_float method', 'freeze batch normalization statistics on a ConvBn2d or ConvBnReLU2d QAT module', 'create a LinearBn1d module for quantization aware training with given in_features and out_features', 'build a fused Linear and BatchNorm1d module with fake quantization for QAT', 'convert a float LinearBn1d module to a quantization aware training module using from_float', 'convert a quantization aware training LinearBn1d module back to a float Linear module using to_float', 'freeze batch normalization statistics in a LinearBn1d module to prevent updates during training', 'create a quantization-aware training LinearReLU module with specified input and output features', 'build a forward pass through a fused LinearReLU module with fake quantization on weights', 'test the forward pass of a LinearReLU module with random input tensor and verify output shape']
```

Usage

```
{'create_ConvBn2d_QAT_module': 'create a ConvBn2d QAT module fused from Conv2d and BatchNorm2d with fake quantization for weight', 'build_ConvBnReLU2d_module': 'build a ConvBnReLU2d QAT module fused from Conv2d, BatchNorm2d and ReLU with weight fake quantization', 'test_from_float_conversion': 'test the from_float method to convert a float Conv2d+BatchNorm2d module to a QAT ConvBn2d module', 'refactor_QAT_to_float': 'refactor a QAT ConvBn2d module back to a float fused ConvReLU2d module using the to_float method', 'freeze_bn_stats_module': 'freeze batch normalization statistics on a ConvBn2d or ConvBnReLU2d QAT module'}
```

## File: pytorch_pytorch/torch/ao/nn/intrinsic/qat/modules/linear_fused.py

Prompts

```
['create a ConvBn2d QAT module fused from Conv2d and BatchNorm2d with fake quantization for weight', 'build a ConvBnReLU2d QAT module fused from Conv2d, BatchNorm2d and ReLU with weight fake quantization', 'test the from_float method to convert a float Conv2d+BatchNorm2d module to a QAT ConvBn2d module', 'refactor a QAT ConvBn2d module back to a float fused ConvReLU2d module using the to_float method', 'freeze batch normalization statistics on a ConvBn2d or ConvBnReLU2d QAT module', 'create a LinearBn1d module for quantization aware training with given in_features and out_features', 'build a fused Linear and BatchNorm1d module with fake quantization for QAT', 'convert a float LinearBn1d module to a quantization aware training module using from_float', 'convert a quantization aware training LinearBn1d module back to a float Linear module using to_float', 'freeze batch normalization statistics in a LinearBn1d module to prevent updates during training', 'create a quantization-aware training LinearReLU module with specified input and output features', 'build a forward pass through a fused LinearReLU module with fake quantization on weights', 'test the forward pass of a LinearReLU module with random input tensor and verify output shape']
```

Usage

```
{'create_linearbn1d_module': 'create a LinearBn1d module for quantization aware training with given in_features and out_features', 'build_qat_linear_bn_fused': 'build a fused Linear and BatchNorm1d module with fake quantization for QAT', 'convert_float_to_qat': 'convert a float LinearBn1d module to a quantization aware training module using from_float', 'convert_qat_to_float': 'convert a quantization aware training LinearBn1d module back to a float Linear module using to_float', 'freeze_bn_statistics': 'freeze batch normalization statistics in a LinearBn1d module to prevent updates during training'}
```

## File: pytorch_pytorch/torch/ao/nn/intrinsic/qat/modules/linear_relu.py

Prompts

```
['create a ConvBn2d QAT module fused from Conv2d and BatchNorm2d with fake quantization for weight', 'build a ConvBnReLU2d QAT module fused from Conv2d, BatchNorm2d and ReLU with weight fake quantization', 'test the from_float method to convert a float Conv2d+BatchNorm2d module to a QAT ConvBn2d module', 'refactor a QAT ConvBn2d module back to a float fused ConvReLU2d module using the to_float method', 'freeze batch normalization statistics on a ConvBn2d or ConvBnReLU2d QAT module', 'create a LinearBn1d module for quantization aware training with given in_features and out_features', 'build a fused Linear and BatchNorm1d module with fake quantization for QAT', 'convert a float LinearBn1d module to a quantization aware training module using from_float', 'convert a quantization aware training LinearBn1d module back to a float Linear module using to_float', 'freeze batch normalization statistics in a LinearBn1d module to prevent updates during training', 'create a quantization-aware training LinearReLU module with specified input and output features', 'build a forward pass through a fused LinearReLU module with fake quantization on weights', 'test the forward pass of a LinearReLU module with random input tensor and verify output shape']
```

Usage

```
{'create_LinearReLU_module': 'create a quantization-aware training LinearReLU module with specified input and output features', 'build_qat_linear_forward': 'build a forward pass through a fused LinearReLU module with fake quantization on weights', 'convert_float_to_qat': 'convert a float torch.nn.Linear and torch.nn.ReLU pair into a QAT LinearReLU module', 'convert_qat_to_float': 'convert a QAT LinearReLU module back to its float LinearReLU intrinsic module', 'test_LinearReLU_forward': 'test the forward pass of a LinearReLU module with random input tensor and verify output shape'}
```

