# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/cortexbench/habitat_vc/habitat_vc/models/freeze_batchnorm.py

Prompts

```
['convert all BatchNorm layers in a PyTorch module to FrozenBatchNorm layers', 'freeze batch normalization layers in a neural network model for inference', 'create a FrozenBatchNorm layer that always uses running statistics instead of batch statistics', 'review the convert_frozen_batchnorm function that recursively replaces BatchNorm layers with FrozenBatchNorm', 'summarize the _FrozenBatchNorm class that disables training mode normalization by always using running mean and variance', 'build a ResNet-18 model with BasicBlock using specified in_channels, base_planes, and ngroups parameters', 'build a ResNet-50 model with Bottleneck blocks using specified in_channels, base_planes, and ngroups parameters', 'build a ResNeXt-50 model with grouped convolutions and cardinality set to half of base_planes', 'build a SE-ResNet-50 model with squeeze-and-excitation Bottleneck blocks for channel attention', 'build a SE-ResNeXt-101 model with squeeze-and-excitation and grouped convolutions for deep feature extraction', 'build a ResNetEncoder module to encode RGB, depth, and semantic observations into compressed feature tensors', 'build a VlnResnetDepthEncoder module to encode depth observations with optional spatial embeddings for vision-and-language navigation', 'review the ResNetEncoder forward method to understand how RGB, depth, and semantic inputs are normalized, pooled, and compressed', 'review the VlnResnetDepthEncoder forward method to understand depth feature extraction with spatial embedding concatenation', 'refactor the ResNetEncoder layer_init method to apply Kaiming normal weight initialization to Conv2d and Linear layers']
```

Usage

```
{'convert_batchnorm_to_frozen': 'convert all BatchNorm layers in a PyTorch module to FrozenBatchNorm layers', 'freeze_batchnorm_in_model': 'freeze batch normalization layers in a neural network model for inference', 'create_frozen_batchnorm_layer': 'create a FrozenBatchNorm layer that always uses running statistics instead of batch statistics', 'review_convert_frozen_batchnorm': 'review the convert_frozen_batchnorm function that recursively replaces BatchNorm layers with FrozenBatchNorm', 'summarize_frozen_batchnorm_class': 'summarize the _FrozenBatchNorm class that disables training mode normalization by always using running mean and variance'}
```

## File: facebookresearch_eai-vc/cortexbench/habitat_vc/habitat_vc/models/resnet.py

Prompts

```
['convert all BatchNorm layers in a PyTorch module to FrozenBatchNorm layers', 'freeze batch normalization layers in a neural network model for inference', 'create a FrozenBatchNorm layer that always uses running statistics instead of batch statistics', 'review the convert_frozen_batchnorm function that recursively replaces BatchNorm layers with FrozenBatchNorm', 'summarize the _FrozenBatchNorm class that disables training mode normalization by always using running mean and variance', 'build a ResNet-18 model with BasicBlock using specified in_channels, base_planes, and ngroups parameters', 'build a ResNet-50 model with Bottleneck blocks using specified in_channels, base_planes, and ngroups parameters', 'build a ResNeXt-50 model with grouped convolutions and cardinality set to half of base_planes', 'build a SE-ResNet-50 model with squeeze-and-excitation Bottleneck blocks for channel attention', 'build a SE-ResNeXt-101 model with squeeze-and-excitation and grouped convolutions for deep feature extraction', 'build a ResNetEncoder module to encode RGB, depth, and semantic observations into compressed feature tensors', 'build a VlnResnetDepthEncoder module to encode depth observations with optional spatial embeddings for vision-and-language navigation', 'review the ResNetEncoder forward method to understand how RGB, depth, and semantic inputs are normalized, pooled, and compressed', 'review the VlnResnetDepthEncoder forward method to understand depth feature extraction with spatial embedding concatenation', 'refactor the ResNetEncoder layer_init method to apply Kaiming normal weight initialization to Conv2d and Linear layers']
```

Usage

```
{'build_resnet18_model': 'build a ResNet-18 model with BasicBlock using specified in_channels, base_planes, and ngroups parameters', 'build_resnet50_model': 'build a ResNet-50 model with Bottleneck blocks using specified in_channels, base_planes, and ngroups parameters', 'build_resnext50_model': 'build a ResNeXt-50 model with grouped convolutions and cardinality set to half of base_planes', 'build_se_resnet50_model': 'build a SE-ResNet-50 model with squeeze-and-excitation Bottleneck blocks for channel attention', 'build_se_resnext101_model': 'build a SE-ResNeXt-101 model with squeeze-and-excitation and grouped convolutions for deep feature extraction'}
```

## File: facebookresearch_eai-vc/cortexbench/habitat_vc/habitat_vc/models/resnet_encoders.py

Prompts

```
['convert all BatchNorm layers in a PyTorch module to FrozenBatchNorm layers', 'freeze batch normalization layers in a neural network model for inference', 'create a FrozenBatchNorm layer that always uses running statistics instead of batch statistics', 'review the convert_frozen_batchnorm function that recursively replaces BatchNorm layers with FrozenBatchNorm', 'summarize the _FrozenBatchNorm class that disables training mode normalization by always using running mean and variance', 'build a ResNet-18 model with BasicBlock using specified in_channels, base_planes, and ngroups parameters', 'build a ResNet-50 model with Bottleneck blocks using specified in_channels, base_planes, and ngroups parameters', 'build a ResNeXt-50 model with grouped convolutions and cardinality set to half of base_planes', 'build a SE-ResNet-50 model with squeeze-and-excitation Bottleneck blocks for channel attention', 'build a SE-ResNeXt-101 model with squeeze-and-excitation and grouped convolutions for deep feature extraction', 'build a ResNetEncoder module to encode RGB, depth, and semantic observations into compressed feature tensors', 'build a VlnResnetDepthEncoder module to encode depth observations with optional spatial embeddings for vision-and-language navigation', 'review the ResNetEncoder forward method to understand how RGB, depth, and semantic inputs are normalized, pooled, and compressed', 'review the VlnResnetDepthEncoder forward method to understand depth feature extraction with spatial embedding concatenation', 'refactor the ResNetEncoder layer_init method to apply Kaiming normal weight initialization to Conv2d and Linear layers']
```

Usage

```
{'build_ResNetEncoder': 'build a ResNetEncoder module to encode RGB, depth, and semantic observations into compressed feature tensors', 'build_VlnResnetDepthEncoder': 'build a VlnResnetDepthEncoder module to encode depth observations with optional spatial embeddings for vision-and-language navigation', 'review_ResNetEncoder_forward': 'review the ResNetEncoder forward method to understand how RGB, depth, and semantic inputs are normalized, pooled, and compressed', 'review_VlnResnetDepthEncoder_forward': 'review the VlnResnetDepthEncoder forward method to understand depth feature extraction with spatial embedding concatenation', 'refactor_ResNetEncoder_layer_init': 'refactor the ResNetEncoder layer_init method to apply Kaiming normal weight initialization to Conv2d and Linear layers'}
```

