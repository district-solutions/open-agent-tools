# Agent Python Tools

- repo: facebookresearch/pointcontrast
- repo_uri: https://github.com/facebookresearch/pointcontrast

## File: facebookresearch_pointcontrast/downstream/semseg/models/modules/common.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer with configurable kernel region type and dimension', 'create a MinkowskiEngine transposed convolution layer for upsampling sparse tensor features', 'create a MinkowskiEngine batch norm, instance norm, or combined normalization layer', 'create a MinkowskiEngine average pooling layer for sparse tensor feature aggregation', 'convert a ConvType enum to MinkowskiEngine region type with adjusted kernel size', 'build a BasicBlockBase sparse convolution block with configurable stride, dilation, and downsampling for MinkowskiEngine', 'build a BottleneckBase sparse convolution block with 1x3x1 bottleneck structure and expansion factor of 4', 'create a BasicBlock with batch normalization for sparse 3D convolutional residual learning', 'create a Bottleneck with batch normalization for deeper sparse 3D convolutional residual networks', 'review the BasicBlockIN class that uses instance normalization instead of batch normalization']
```

Usage

```
{'create_minkowski_conv': 'create a MinkowskiEngine sparse convolution layer with configurable kernel region type and dimension', 'create_transpose_conv': 'create a MinkowskiEngine transposed convolution layer for upsampling sparse tensor features', 'create_norm_layer': 'create a MinkowskiEngine batch norm, instance norm, or combined normalization layer', 'create_avg_pool': 'create a MinkowskiEngine average pooling layer for sparse tensor feature aggregation', 'convert_conv_type': 'convert a ConvType enum to MinkowskiEngine region type with adjusted kernel size'}
```

## File: facebookresearch_pointcontrast/downstream/semseg/models/modules/resnet_block.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer with configurable kernel region type and dimension', 'create a MinkowskiEngine transposed convolution layer for upsampling sparse tensor features', 'create a MinkowskiEngine batch norm, instance norm, or combined normalization layer', 'create a MinkowskiEngine average pooling layer for sparse tensor feature aggregation', 'convert a ConvType enum to MinkowskiEngine region type with adjusted kernel size', 'build a BasicBlockBase sparse convolution block with configurable stride, dilation, and downsampling for MinkowskiEngine', 'build a BottleneckBase sparse convolution block with 1x3x1 bottleneck structure and expansion factor of 4', 'create a BasicBlock with batch normalization for sparse 3D convolutional residual learning', 'create a Bottleneck with batch normalization for deeper sparse 3D convolutional residual networks', 'review the BasicBlockIN class that uses instance normalization instead of batch normalization']
```

Usage

```
{'build_BasicBlockBase': 'build a BasicBlockBase sparse convolution block with configurable stride, dilation, and downsampling for MinkowskiEngine', 'build_BottleneckBase': 'build a BottleneckBase sparse convolution block with 1x3x1 bottleneck structure and expansion factor of 4', 'create_BasicBlock': 'create a BasicBlock with batch normalization for sparse 3D convolutional residual learning', 'create_Bottleneck': 'create a Bottleneck with batch normalization for deeper sparse 3D convolutional residual networks', 'review_BasicBlockIN': 'review the BasicBlockIN class that uses instance normalization instead of batch normalization'}
```

