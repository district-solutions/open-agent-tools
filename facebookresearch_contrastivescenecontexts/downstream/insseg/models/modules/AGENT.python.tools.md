# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/downstream/insseg/models/modules/common.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer with configurable kernel region type and dimension', 'create a MinkowskiEngine transposed convolution layer for upsampling sparse tensor features', 'create a MinkowskiEngine average pooling layer for sparse tensor feature aggregation', 'create a MinkowskiEngine normalization layer supporting batch norm, instance norm, or combined instance-batch norm', 'convert a ConvType enum to its corresponding MinkowskiEngine RegionType with adjusted kernel size', 'build a BasicBlock sparse convolution layer with batch norm for 3D point cloud feature extraction', 'build a Bottleneck sparse convolution layer with 1x3x1 conv pattern and batch norm for 3D features', 'create a BasicBlockIN sparse convolution layer using instance normalization for 3D point cloud data', 'create a BottleneckINBN sparse convolution layer using instance-batch normalization for 3D feature extraction', 'review the BasicBlockBase forward method residual connection logic with conv-norm-relu pattern', 'build a Squeeze-and-Excitation layer using MinkowskiEngine for sparse 3D feature channel attention', 'create an SE BasicBlock with channel attention for sparse convolutional residual networks', 'create an SE Bottleneck block with channel attention for deep sparse convolutional networks', 'review the SEBasicBlockSN, SEBasicBlockIN, and SEBasicBlockLN sparse normalization variants', 'review the SEBottleneckSN, SEBottleneckIN, and SEBottleneckLN sparse normalization variants']
```

Usage

```
{'create_minkowski_conv': 'create a MinkowskiEngine sparse convolution layer with configurable kernel region type and dimension', 'create_minkowski_transpose_conv': 'create a MinkowskiEngine transposed convolution layer for upsampling sparse tensor features', 'create_minkowski_avg_pool': 'create a MinkowskiEngine average pooling layer for sparse tensor feature aggregation', 'create_norm_layer': 'create a MinkowskiEngine normalization layer supporting batch norm, instance norm, or combined instance-batch norm', 'convert_conv_type': 'convert a ConvType enum to its corresponding MinkowskiEngine RegionType with adjusted kernel size'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/insseg/models/modules/resnet_block.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer with configurable kernel region type and dimension', 'create a MinkowskiEngine transposed convolution layer for upsampling sparse tensor features', 'create a MinkowskiEngine average pooling layer for sparse tensor feature aggregation', 'create a MinkowskiEngine normalization layer supporting batch norm, instance norm, or combined instance-batch norm', 'convert a ConvType enum to its corresponding MinkowskiEngine RegionType with adjusted kernel size', 'build a BasicBlock sparse convolution layer with batch norm for 3D point cloud feature extraction', 'build a Bottleneck sparse convolution layer with 1x3x1 conv pattern and batch norm for 3D features', 'create a BasicBlockIN sparse convolution layer using instance normalization for 3D point cloud data', 'create a BottleneckINBN sparse convolution layer using instance-batch normalization for 3D feature extraction', 'review the BasicBlockBase forward method residual connection logic with conv-norm-relu pattern', 'build a Squeeze-and-Excitation layer using MinkowskiEngine for sparse 3D feature channel attention', 'create an SE BasicBlock with channel attention for sparse convolutional residual networks', 'create an SE Bottleneck block with channel attention for deep sparse convolutional networks', 'review the SEBasicBlockSN, SEBasicBlockIN, and SEBasicBlockLN sparse normalization variants', 'review the SEBottleneckSN, SEBottleneckIN, and SEBottleneckLN sparse normalization variants']
```

Usage

```
{'build_basicblock': 'build a BasicBlock sparse convolution layer with batch norm for 3D point cloud feature extraction', 'build_bottleneck': 'build a Bottleneck sparse convolution layer with 1x3x1 conv pattern and batch norm for 3D features', 'create_basicblock_in': 'create a BasicBlockIN sparse convolution layer using instance normalization for 3D point cloud data', 'create_bottleneck_inbn': 'create a BottleneckINBN sparse convolution layer using instance-batch normalization for 3D feature extraction', 'review_basicblockbase_forward': 'review the BasicBlockBase forward method residual connection logic with conv-norm-relu pattern'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/insseg/models/modules/senet_block.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer with configurable kernel region type and dimension', 'create a MinkowskiEngine transposed convolution layer for upsampling sparse tensor features', 'create a MinkowskiEngine average pooling layer for sparse tensor feature aggregation', 'create a MinkowskiEngine normalization layer supporting batch norm, instance norm, or combined instance-batch norm', 'convert a ConvType enum to its corresponding MinkowskiEngine RegionType with adjusted kernel size', 'build a BasicBlock sparse convolution layer with batch norm for 3D point cloud feature extraction', 'build a Bottleneck sparse convolution layer with 1x3x1 conv pattern and batch norm for 3D features', 'create a BasicBlockIN sparse convolution layer using instance normalization for 3D point cloud data', 'create a BottleneckINBN sparse convolution layer using instance-batch normalization for 3D feature extraction', 'review the BasicBlockBase forward method residual connection logic with conv-norm-relu pattern', 'build a Squeeze-and-Excitation layer using MinkowskiEngine for sparse 3D feature channel attention', 'create an SE BasicBlock with channel attention for sparse convolutional residual networks', 'create an SE Bottleneck block with channel attention for deep sparse convolutional networks', 'review the SEBasicBlockSN, SEBasicBlockIN, and SEBasicBlockLN sparse normalization variants', 'review the SEBottleneckSN, SEBottleneckIN, and SEBottleneckLN sparse normalization variants']
```

Usage

```
{'build_SELayer': 'build a Squeeze-and-Excitation layer using MinkowskiEngine for sparse 3D feature channel attention', 'create_SEBasicBlock': 'create an SE BasicBlock with channel attention for sparse convolutional residual networks', 'create_SEBottleneck': 'create an SE Bottleneck block with channel attention for deep sparse convolutional networks', 'review_SEBasicBlock_norm_variants': 'review the SEBasicBlockSN, SEBasicBlockIN, and SEBasicBlockLN sparse normalization variants', 'review_SEBottleneck_norm_variants': 'review the SEBottleneckSN, SEBottleneckIN, and SEBottleneckLN sparse normalization variants'}
```

