# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/downstream/semseg/models/modules/common.py

Prompts

```
['create a Minkowski sparse convolution layer with configurable kernel size, stride, and ConvType for sparse tensor operations', 'create a Minkowski transposed convolution layer for upsampling sparse tensors with configurable kernel and stride', 'create a Minkowski average pooling layer for sparse tensors with configurable kernel size, stride, and dilation', 'create a Minkowski normalization layer supporting batch norm, instance norm, or combined instance-batch norm types', 'convert a ConvType enum to its corresponding MinkowskiEngine RegionType, axis types, and adjusted kernel size', 'build a MinkowskiEngine BasicBlock sparse convolution block with batch normalization for 3D point cloud features', 'build a BasicBlockIN sparse convolution block using instance normalization for 3D sparse tensor processing', 'build a MinkowskiEngine Bottleneck sparse convolution block with 1x3x1 conv layers and batch normalization', 'build a BottleneckIN sparse convolution block using instance normalization for 3D sparse tensor processing', 'review the BasicBlockBase forward method residual connection logic with optional downsample and MinkowskiReLU activation', 'create a Squeeze-and-Excitation attention layer for MinkowskiEngine sparse tensors with configurable channel reduction', 'build an SE-enhanced basic ResNet block with two conv layers and channel-wise attention for sparse 3D data', 'create an SE basic block variant using sparse switch normalization for MinkowskiEngine sparse convolutions', 'build an SE-enhanced bottleneck ResNet block with three conv layers and channel-wise attention for sparse 3D data', 'create an SE bottleneck block variant using sparse layer normalization for MinkowskiEngine sparse convolutions']
```

Usage

```
{'create_minkowski_conv': 'create a Minkowski sparse convolution layer with configurable kernel size, stride, and ConvType for sparse tensor operations', 'create_minkowski_transpose_conv': 'create a Minkowski transposed convolution layer for upsampling sparse tensors with configurable kernel and stride', 'create_minkowski_avg_pool': 'create a Minkowski average pooling layer for sparse tensors with configurable kernel size, stride, and dilation', 'create_norm_layer': 'create a Minkowski normalization layer supporting batch norm, instance norm, or combined instance-batch norm types', 'convert_conv_type': 'convert a ConvType enum to its corresponding MinkowskiEngine RegionType, axis types, and adjusted kernel size'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/semseg/models/modules/resnet_block.py

Prompts

```
['create a Minkowski sparse convolution layer with configurable kernel size, stride, and ConvType for sparse tensor operations', 'create a Minkowski transposed convolution layer for upsampling sparse tensors with configurable kernel and stride', 'create a Minkowski average pooling layer for sparse tensors with configurable kernel size, stride, and dilation', 'create a Minkowski normalization layer supporting batch norm, instance norm, or combined instance-batch norm types', 'convert a ConvType enum to its corresponding MinkowskiEngine RegionType, axis types, and adjusted kernel size', 'build a MinkowskiEngine BasicBlock sparse convolution block with batch normalization for 3D point cloud features', 'build a BasicBlockIN sparse convolution block using instance normalization for 3D sparse tensor processing', 'build a MinkowskiEngine Bottleneck sparse convolution block with 1x3x1 conv layers and batch normalization', 'build a BottleneckIN sparse convolution block using instance normalization for 3D sparse tensor processing', 'review the BasicBlockBase forward method residual connection logic with optional downsample and MinkowskiReLU activation', 'create a Squeeze-and-Excitation attention layer for MinkowskiEngine sparse tensors with configurable channel reduction', 'build an SE-enhanced basic ResNet block with two conv layers and channel-wise attention for sparse 3D data', 'create an SE basic block variant using sparse switch normalization for MinkowskiEngine sparse convolutions', 'build an SE-enhanced bottleneck ResNet block with three conv layers and channel-wise attention for sparse 3D data', 'create an SE bottleneck block variant using sparse layer normalization for MinkowskiEngine sparse convolutions']
```

Usage

```
{'build_basicblock': 'build a MinkowskiEngine BasicBlock sparse convolution block with batch normalization for 3D point cloud features', 'build_basicblockin': 'build a BasicBlockIN sparse convolution block using instance normalization for 3D sparse tensor processing', 'build_bottleneck': 'build a MinkowskiEngine Bottleneck sparse convolution block with 1x3x1 conv layers and batch normalization', 'build_bottleneckin': 'build a BottleneckIN sparse convolution block using instance normalization for 3D sparse tensor processing', 'review_basicblockbase_forward': 'review the BasicBlockBase forward method residual connection logic with optional downsample and MinkowskiReLU activation'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/semseg/models/modules/senet_block.py

Prompts

```
['create a Minkowski sparse convolution layer with configurable kernel size, stride, and ConvType for sparse tensor operations', 'create a Minkowski transposed convolution layer for upsampling sparse tensors with configurable kernel and stride', 'create a Minkowski average pooling layer for sparse tensors with configurable kernel size, stride, and dilation', 'create a Minkowski normalization layer supporting batch norm, instance norm, or combined instance-batch norm types', 'convert a ConvType enum to its corresponding MinkowskiEngine RegionType, axis types, and adjusted kernel size', 'build a MinkowskiEngine BasicBlock sparse convolution block with batch normalization for 3D point cloud features', 'build a BasicBlockIN sparse convolution block using instance normalization for 3D sparse tensor processing', 'build a MinkowskiEngine Bottleneck sparse convolution block with 1x3x1 conv layers and batch normalization', 'build a BottleneckIN sparse convolution block using instance normalization for 3D sparse tensor processing', 'review the BasicBlockBase forward method residual connection logic with optional downsample and MinkowskiReLU activation', 'create a Squeeze-and-Excitation attention layer for MinkowskiEngine sparse tensors with configurable channel reduction', 'build an SE-enhanced basic ResNet block with two conv layers and channel-wise attention for sparse 3D data', 'create an SE basic block variant using sparse switch normalization for MinkowskiEngine sparse convolutions', 'build an SE-enhanced bottleneck ResNet block with three conv layers and channel-wise attention for sparse 3D data', 'create an SE bottleneck block variant using sparse layer normalization for MinkowskiEngine sparse convolutions']
```

Usage

```
{'create_SELayer': 'create a Squeeze-and-Excitation attention layer for MinkowskiEngine sparse tensors with configurable channel reduction', 'build_SEBasicBlock': 'build an SE-enhanced basic ResNet block with two conv layers and channel-wise attention for sparse 3D data', 'create_SEBasicBlockSN': 'create an SE basic block variant using sparse switch normalization for MinkowskiEngine sparse convolutions', 'build_SEBottleneck': 'build an SE-enhanced bottleneck ResNet block with three conv layers and channel-wise attention for sparse 3D data', 'create_SEBottleneckLN': 'create an SE bottleneck block variant using sparse layer normalization for MinkowskiEngine sparse convolutions'}
```

