# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/models/trunks/spconv/models/modules/common.py

Prompts

```
['build a MinkowskiEngine sparse convolution layer with configurable kernel region type and dimension', 'build a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features', 'create a MinkowskiEngine normalization layer supporting batch norm, instance norm, or combined instance-batch norm', 'build a MinkowskiEngine sparse average pooling, average unpooling, or sum pooling layer with configurable kernel', 'convert a ConvType enum to its corresponding MinkowskiEngine RegionType with adjusted kernel size and axis types', 'build a BasicBlock with batch norm for a sparse convolutional ResNet using MinkowskiEngine', 'build a Bottleneck block with 1x3x1 conv pattern for a sparse ResNet trunk', 'create a BasicBlockIN block using instance normalization instead of batch norm', 'create a BottleneckINBN block using instance-batch normalization for sparse features', 'review the BasicBlockBase forward pass with conv-norm-relu and residual skip connection', 'build a python module that creates an SELayer with MinkowskiEngine global pooling and channel-wise attention', 'build a python module that creates an SEBasicBlock with squeeze-and-excitation on sparse tensor features', 'build a python module that creates an SEBottleneck with three conv layers and squeeze-and-excitation attention', 'review the SEBasicBlockSN, SEBasicBlockIN, and SEBasicBlockLN subclasses that override NORM_TYPE for different normalization', 'review the SEBottleneckSN, SEBottleneckIN, and SEBottleneckLN subclasses that override NORM_TYPE for different normalization']
```

Usage

```
{'build_minkowski_conv_layer': 'build a MinkowskiEngine sparse convolution layer with configurable kernel region type and dimension', 'build_minkowski_transpose_conv': 'build a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features', 'create_norm_layer': 'create a MinkowskiEngine normalization layer supporting batch norm, instance norm, or combined instance-batch norm', 'build_sparse_pooling_layer': 'build a MinkowskiEngine sparse average pooling, average unpooling, or sum pooling layer with configurable kernel', 'convert_conv_type': 'convert a ConvType enum to its corresponding MinkowskiEngine RegionType with adjusted kernel size and axis types'}
```

## File: facebookresearch_depthcontrast/models/trunks/spconv/models/modules/resnet_block.py

Prompts

```
['build a MinkowskiEngine sparse convolution layer with configurable kernel region type and dimension', 'build a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features', 'create a MinkowskiEngine normalization layer supporting batch norm, instance norm, or combined instance-batch norm', 'build a MinkowskiEngine sparse average pooling, average unpooling, or sum pooling layer with configurable kernel', 'convert a ConvType enum to its corresponding MinkowskiEngine RegionType with adjusted kernel size and axis types', 'build a BasicBlock with batch norm for a sparse convolutional ResNet using MinkowskiEngine', 'build a Bottleneck block with 1x3x1 conv pattern for a sparse ResNet trunk', 'create a BasicBlockIN block using instance normalization instead of batch norm', 'create a BottleneckINBN block using instance-batch normalization for sparse features', 'review the BasicBlockBase forward pass with conv-norm-relu and residual skip connection', 'build a python module that creates an SELayer with MinkowskiEngine global pooling and channel-wise attention', 'build a python module that creates an SEBasicBlock with squeeze-and-excitation on sparse tensor features', 'build a python module that creates an SEBottleneck with three conv layers and squeeze-and-excitation attention', 'review the SEBasicBlockSN, SEBasicBlockIN, and SEBasicBlockLN subclasses that override NORM_TYPE for different normalization', 'review the SEBottleneckSN, SEBottleneckIN, and SEBottleneckLN subclasses that override NORM_TYPE for different normalization']
```

Usage

```
{'build_basicblock_for_sparse_resnet': 'build a BasicBlock with batch norm for a sparse convolutional ResNet using MinkowskiEngine', 'build_bottleneck_for_sparse_resnet': 'build a Bottleneck block with 1x3x1 conv pattern for a sparse ResNet trunk', 'create_basicblock_with_instance_norm': 'create a BasicBlockIN block using instance normalization instead of batch norm', 'create_bottleneck_with_instance_batch_norm': 'create a BottleneckINBN block using instance-batch normalization for sparse features', 'review_basicblockbase_forward': 'review the BasicBlockBase forward pass with conv-norm-relu and residual skip connection'}
```

## File: facebookresearch_depthcontrast/models/trunks/spconv/models/modules/senet_block.py

Prompts

```
['build a MinkowskiEngine sparse convolution layer with configurable kernel region type and dimension', 'build a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features', 'create a MinkowskiEngine normalization layer supporting batch norm, instance norm, or combined instance-batch norm', 'build a MinkowskiEngine sparse average pooling, average unpooling, or sum pooling layer with configurable kernel', 'convert a ConvType enum to its corresponding MinkowskiEngine RegionType with adjusted kernel size and axis types', 'build a BasicBlock with batch norm for a sparse convolutional ResNet using MinkowskiEngine', 'build a Bottleneck block with 1x3x1 conv pattern for a sparse ResNet trunk', 'create a BasicBlockIN block using instance normalization instead of batch norm', 'create a BottleneckINBN block using instance-batch normalization for sparse features', 'review the BasicBlockBase forward pass with conv-norm-relu and residual skip connection', 'build a python module that creates an SELayer with MinkowskiEngine global pooling and channel-wise attention', 'build a python module that creates an SEBasicBlock with squeeze-and-excitation on sparse tensor features', 'build a python module that creates an SEBottleneck with three conv layers and squeeze-and-excitation attention', 'review the SEBasicBlockSN, SEBasicBlockIN, and SEBasicBlockLN subclasses that override NORM_TYPE for different normalization', 'review the SEBottleneckSN, SEBottleneckIN, and SEBottleneckLN subclasses that override NORM_TYPE for different normalization']
```

Usage

```
{'build_SELayer_module': 'build a python module that creates an SELayer with MinkowskiEngine global pooling and channel-wise attention', 'build_SEBasicBlock_module': 'build a python module that creates an SEBasicBlock with squeeze-and-excitation on sparse tensor features', 'build_SEBottleneck_module': 'build a python module that creates an SEBottleneck with three conv layers and squeeze-and-excitation attention', 'review_SEBasicBlock_subclasses': 'review the SEBasicBlockSN, SEBasicBlockIN, and SEBasicBlockLN subclasses that override NORM_TYPE for different normalization', 'review_SEBottleneck_subclasses': 'review the SEBottleneckSN, SEBottleneckIN, and SEBottleneckLN subclasses that override NORM_TYPE for different normalization'}
```

