# Agent Python Tools

- repo: facebookresearch/pointcontrast
- repo_uri: https://github.com/facebookresearch/pointcontrast

## File: facebookresearch_pointcontrast/downstream/votenet_det_new/models/backbone/sparseconv/models/modules/common.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer with specified kernel size, stride, and dimension', 'create a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features', 'create a MinkowskiEngine sparse average pooling layer with configurable kernel size and stride', 'create a MinkowskiEngine sparse sum pooling layer to aggregate sparse tensor features', 'create a MinkowskiEngine normalization layer supporting batch norm, instance norm, or combined instance-batch norm', 'create a BasicBlock sparse convolution residual block with batch normalization for MinkowskiEngine', 'create a BottleneckBlock sparse convolution residual block with 1x3x1 conv layers and batch norm', 'build a BasicBlockIN sparse residual block using instance normalization instead of batch norm', 'build a BottleneckINBN sparse residual block using instance batch normalization for MinkowskiEngine', 'review the BasicBlockBase and BottleneckBase classes and their normalization type subclasses', 'create a Squeeze-Excitation layer for sparse tensor channel attention using MinkowskiEngine', 'build a sparse SE BasicBlock with channel attention for 3D point cloud feature extraction', 'build a sparse SE Bottleneck block with channel attention for deeper 3D feature extraction', 'review the SEBasicBlockSN, SEBasicBlockIN, SEBasicBlockLN subclasses that override NORM_TYPE for different normalization', 'review the SEBottleneckSN, SEBottleneckIN, SEBottleneckLN subclasses that override NORM_TYPE for different normalization']
```

Usage

```
{'create_sparse_conv': 'create a MinkowskiEngine sparse convolution layer with specified kernel size, stride, and dimension', 'create_sparse_transpose_conv': 'create a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features', 'create_sparse_avg_pool': 'create a MinkowskiEngine sparse average pooling layer with configurable kernel size and stride', 'create_sparse_sum_pool': 'create a MinkowskiEngine sparse sum pooling layer to aggregate sparse tensor features', 'create_sparse_norm': 'create a MinkowskiEngine normalization layer supporting batch norm, instance norm, or combined instance-batch norm'}
```

## File: facebookresearch_pointcontrast/downstream/votenet_det_new/models/backbone/sparseconv/models/modules/resnet_block.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer with specified kernel size, stride, and dimension', 'create a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features', 'create a MinkowskiEngine sparse average pooling layer with configurable kernel size and stride', 'create a MinkowskiEngine sparse sum pooling layer to aggregate sparse tensor features', 'create a MinkowskiEngine normalization layer supporting batch norm, instance norm, or combined instance-batch norm', 'create a BasicBlock sparse convolution residual block with batch normalization for MinkowskiEngine', 'create a BottleneckBlock sparse convolution residual block with 1x3x1 conv layers and batch norm', 'build a BasicBlockIN sparse residual block using instance normalization instead of batch norm', 'build a BottleneckINBN sparse residual block using instance batch normalization for MinkowskiEngine', 'review the BasicBlockBase and BottleneckBase classes and their normalization type subclasses', 'create a Squeeze-Excitation layer for sparse tensor channel attention using MinkowskiEngine', 'build a sparse SE BasicBlock with channel attention for 3D point cloud feature extraction', 'build a sparse SE Bottleneck block with channel attention for deeper 3D feature extraction', 'review the SEBasicBlockSN, SEBasicBlockIN, SEBasicBlockLN subclasses that override NORM_TYPE for different normalization', 'review the SEBottleneckSN, SEBottleneckIN, SEBottleneckLN subclasses that override NORM_TYPE for different normalization']
```

Usage

```
{'create_basic_block': 'create a BasicBlock sparse convolution residual block with batch normalization for MinkowskiEngine', 'create_bottleneck_block': 'create a BottleneckBlock sparse convolution residual block with 1x3x1 conv layers and batch norm', 'build_basic_block_with_instance_norm': 'build a BasicBlockIN sparse residual block using instance normalization instead of batch norm', 'build_bottleneck_with_instance_batch_norm': 'build a BottleneckINBN sparse residual block using instance batch normalization for MinkowskiEngine', 'review_resnet_block_classes': 'review the BasicBlockBase and BottleneckBase classes and their normalization type subclasses'}
```

## File: facebookresearch_pointcontrast/downstream/votenet_det_new/models/backbone/sparseconv/models/modules/senet_block.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer with specified kernel size, stride, and dimension', 'create a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features', 'create a MinkowskiEngine sparse average pooling layer with configurable kernel size and stride', 'create a MinkowskiEngine sparse sum pooling layer to aggregate sparse tensor features', 'create a MinkowskiEngine normalization layer supporting batch norm, instance norm, or combined instance-batch norm', 'create a BasicBlock sparse convolution residual block with batch normalization for MinkowskiEngine', 'create a BottleneckBlock sparse convolution residual block with 1x3x1 conv layers and batch norm', 'build a BasicBlockIN sparse residual block using instance normalization instead of batch norm', 'build a BottleneckINBN sparse residual block using instance batch normalization for MinkowskiEngine', 'review the BasicBlockBase and BottleneckBase classes and their normalization type subclasses', 'create a Squeeze-Excitation layer for sparse tensor channel attention using MinkowskiEngine', 'build a sparse SE BasicBlock with channel attention for 3D point cloud feature extraction', 'build a sparse SE Bottleneck block with channel attention for deeper 3D feature extraction', 'review the SEBasicBlockSN, SEBasicBlockIN, SEBasicBlockLN subclasses that override NORM_TYPE for different normalization', 'review the SEBottleneckSN, SEBottleneckIN, SEBottleneckLN subclasses that override NORM_TYPE for different normalization']
```

Usage

```
{'create_SELayer': 'create a Squeeze-Excitation layer for sparse tensor channel attention using MinkowskiEngine', 'build_SEBasicBlock': 'build a sparse SE BasicBlock with channel attention for 3D point cloud feature extraction', 'build_SEBottleneck': 'build a sparse SE Bottleneck block with channel attention for deeper 3D feature extraction', 'review_SEBasicBlock_subclasses': 'review the SEBasicBlockSN, SEBasicBlockIN, SEBasicBlockLN subclasses that override NORM_TYPE for different normalization', 'review_SEBottleneck_subclasses': 'review the SEBottleneckSN, SEBottleneckIN, SEBottleneckLN subclasses that override NORM_TYPE for different normalization'}
```

