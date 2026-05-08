# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/downstream/votenet/models/backbone/sparseconv/models_sparseconv/modules/common.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer with specified kernel size and ConvType for 3D point cloud data', 'create a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features in a 3D backbone', 'create a MinkowskiEngine sparse average pooling layer with configurable kernel size and stride for sparse tensors', 'create a MinkowskiEngine sparse sum pooling layer to aggregate sparse tensor features across spatial regions', 'create a MinkowskiEngine normalization layer using BATCH_NORM, INSTANCE_NORM, or INSTANCE_BATCH_NORM for sparse tensor channels', 'build a BasicBlock sparse convolution residual block with batch normalization for 3D point cloud features', 'build a BasicBlockIN sparse convolution residual block with instance normalization for 3D point cloud features', 'build a Bottleneck sparse convolution residual block with 1x3x1 conv layers and batch normalization', 'build a BottleneckIN sparse convolution residual block with instance normalization for 3D point cloud features', 'review the BasicBlockBase class and its forward pass with conv-norm-relu-residual pattern', 'create a Squeeze-and-Excitation layer for sparse tensor channel attention using MinkowskiEngine', 'build a sparse SE-ResNet basic block with channel attention for 3D point cloud features', 'build a sparse SE-ResNet bottleneck block with channel attention for 3D point cloud features', 'review the SEBasicBlockSN, SEBasicBlockIN, and SEBasicBlockLN subclasses that override NORM_TYPE', 'refactor the SEBottleneckSN, SEBottleneckIN, and SEBottleneckLN subclasses to use a different norm type']
```

Usage

```
{'create_sparse_conv_layer': 'create a MinkowskiEngine sparse convolution layer with specified kernel size and ConvType for 3D point cloud data', 'create_sparse_transpose_conv': 'create a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features in a 3D backbone', 'create_sparse_avg_pool': 'create a MinkowskiEngine sparse average pooling layer with configurable kernel size and stride for sparse tensors', 'create_sparse_sum_pool': 'create a MinkowskiEngine sparse sum pooling layer to aggregate sparse tensor features across spatial regions', 'create_sparse_norm_layer': 'create a MinkowskiEngine normalization layer using BATCH_NORM, INSTANCE_NORM, or INSTANCE_BATCH_NORM for sparse tensor channels'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/votenet/models/backbone/sparseconv/models_sparseconv/modules/resnet_block.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer with specified kernel size and ConvType for 3D point cloud data', 'create a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features in a 3D backbone', 'create a MinkowskiEngine sparse average pooling layer with configurable kernel size and stride for sparse tensors', 'create a MinkowskiEngine sparse sum pooling layer to aggregate sparse tensor features across spatial regions', 'create a MinkowskiEngine normalization layer using BATCH_NORM, INSTANCE_NORM, or INSTANCE_BATCH_NORM for sparse tensor channels', 'build a BasicBlock sparse convolution residual block with batch normalization for 3D point cloud features', 'build a BasicBlockIN sparse convolution residual block with instance normalization for 3D point cloud features', 'build a Bottleneck sparse convolution residual block with 1x3x1 conv layers and batch normalization', 'build a BottleneckIN sparse convolution residual block with instance normalization for 3D point cloud features', 'review the BasicBlockBase class and its forward pass with conv-norm-relu-residual pattern', 'create a Squeeze-and-Excitation layer for sparse tensor channel attention using MinkowskiEngine', 'build a sparse SE-ResNet basic block with channel attention for 3D point cloud features', 'build a sparse SE-ResNet bottleneck block with channel attention for 3D point cloud features', 'review the SEBasicBlockSN, SEBasicBlockIN, and SEBasicBlockLN subclasses that override NORM_TYPE', 'refactor the SEBottleneckSN, SEBottleneckIN, and SEBottleneckLN subclasses to use a different norm type']
```

Usage

```
{'build_basicblock': 'build a BasicBlock sparse convolution residual block with batch normalization for 3D point cloud features', 'build_basicblockin': 'build a BasicBlockIN sparse convolution residual block with instance normalization for 3D point cloud features', 'build_bottleneck': 'build a Bottleneck sparse convolution residual block with 1x3x1 conv layers and batch normalization', 'build_bottleneckin': 'build a BottleneckIN sparse convolution residual block with instance normalization for 3D point cloud features', 'review_basicblockbase': 'review the BasicBlockBase class and its forward pass with conv-norm-relu-residual pattern'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/votenet/models/backbone/sparseconv/models_sparseconv/modules/senet_block.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer with specified kernel size and ConvType for 3D point cloud data', 'create a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features in a 3D backbone', 'create a MinkowskiEngine sparse average pooling layer with configurable kernel size and stride for sparse tensors', 'create a MinkowskiEngine sparse sum pooling layer to aggregate sparse tensor features across spatial regions', 'create a MinkowskiEngine normalization layer using BATCH_NORM, INSTANCE_NORM, or INSTANCE_BATCH_NORM for sparse tensor channels', 'build a BasicBlock sparse convolution residual block with batch normalization for 3D point cloud features', 'build a BasicBlockIN sparse convolution residual block with instance normalization for 3D point cloud features', 'build a Bottleneck sparse convolution residual block with 1x3x1 conv layers and batch normalization', 'build a BottleneckIN sparse convolution residual block with instance normalization for 3D point cloud features', 'review the BasicBlockBase class and its forward pass with conv-norm-relu-residual pattern', 'create a Squeeze-and-Excitation layer for sparse tensor channel attention using MinkowskiEngine', 'build a sparse SE-ResNet basic block with channel attention for 3D point cloud features', 'build a sparse SE-ResNet bottleneck block with channel attention for 3D point cloud features', 'review the SEBasicBlockSN, SEBasicBlockIN, and SEBasicBlockLN subclasses that override NORM_TYPE', 'refactor the SEBottleneckSN, SEBottleneckIN, and SEBottleneckLN subclasses to use a different norm type']
```

Usage

```
{'create_SELayer': 'create a Squeeze-and-Excitation layer for sparse tensor channel attention using MinkowskiEngine', 'build_SEBasicBlock': 'build a sparse SE-ResNet basic block with channel attention for 3D point cloud features', 'build_SEBottleneck': 'build a sparse SE-ResNet bottleneck block with channel attention for 3D point cloud features', 'review_SEBasicBlock_subclasses': 'review the SEBasicBlockSN, SEBasicBlockIN, and SEBasicBlockLN subclasses that override NORM_TYPE', 'refactor_SEBottleneck_subclasses': 'refactor the SEBottleneckSN, SEBottleneckIN, and SEBottleneckLN subclasses to use a different norm type'}
```

