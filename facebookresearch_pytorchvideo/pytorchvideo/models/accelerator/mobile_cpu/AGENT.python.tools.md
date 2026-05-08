# Agent Python Tools

- repo: facebookresearch/pytorchvideo
- repo_uri: https://github.com/facebookresearch/pytorchvideo

## File: facebookresearch_pytorchvideo/pytorchvideo/models/accelerator/mobile_cpu/efficient_x3d.py

Prompts

```
['create an EfficientX3d model with default XS expansion for 400 class video classification', 'create an EfficientX3d model with L expansion for deeper video classification network', 'create an EfficientX3d feature extractor model without the classification head enabled', 'create an EfficientX3d model with a custom number of output classes for classification', 'create an EfficientX3d model with a custom dropout rate for training regularization', 'create an X3D style residual block with configurable channels, stride, and squeeze-excite ratio', 'run a forward pass through an X3D bottleneck block with optional residual connection', 'convert an X3D bottleneck block for quantization with native conv3d QNNPACK support', 'review the X3D bottleneck block residual projection logic for stride or channel mismatch', 'refactor the X3D bottleneck block to use a different activation function like swish or hardswish']
```

Usage

```
{'create_x3d_model': 'create an EfficientX3d model with default XS expansion for 400 class video classification', 'create_x3d_large_model': 'create an EfficientX3d model with L expansion for deeper video classification network', 'create_x3d_no_head': 'create an EfficientX3d feature extractor model without the classification head enabled', 'create_x3d_custom_classes': 'create an EfficientX3d model with a custom number of output classes for classification', 'create_x3d_custom_dropout': 'create an EfficientX3d model with a custom dropout rate for training regularization'}
```

## File: facebookresearch_pytorchvideo/pytorchvideo/models/accelerator/mobile_cpu/residual_blocks.py

Prompts

```
['create an EfficientX3d model with default XS expansion for 400 class video classification', 'create an EfficientX3d model with L expansion for deeper video classification network', 'create an EfficientX3d feature extractor model without the classification head enabled', 'create an EfficientX3d model with a custom number of output classes for classification', 'create an EfficientX3d model with a custom dropout rate for training regularization', 'create an X3D style residual block with configurable channels, stride, and squeeze-excite ratio', 'run a forward pass through an X3D bottleneck block with optional residual connection', 'convert an X3D bottleneck block for quantization with native conv3d QNNPACK support', 'review the X3D bottleneck block residual projection logic for stride or channel mismatch', 'refactor the X3D bottleneck block to use a different activation function like swish or hardswish']
```

Usage

```
{'create_X3dBottleneckBlock': 'create an X3D style residual block with configurable channels, stride, and squeeze-excite ratio', 'run_X3dBottleneckBlock_forward': 'run a forward pass through an X3D bottleneck block with optional residual connection', 'convert_X3dBottleneckBlock_for_quantize': 'convert an X3D bottleneck block for quantization with native conv3d QNNPACK support', 'review_X3dBottleneckBlock_residual_projection': 'review the X3D bottleneck block residual projection logic for stride or channel mismatch', 'refactor_X3dBottleneckBlock_activation': 'refactor the X3D bottleneck block to use a different activation function like swish or hardswish'}
```

