# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/pretrain/contrastive_scene_contexts/model/modules/common.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer with configurable kernel size, stride, and dimension', 'create a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features', 'create a MinkowskiEngine sparse average pooling layer with configurable kernel size and stride', 'create a MinkowskiEngine sparse sum pooling layer for aggregating sparse tensor features', 'create a MinkowskiEngine batch or instance normalization layer for sparse tensor normalization', 'create a BasicBlock sparse convolution residual block with batch normalization for 3D sparse tensor processing', 'create a Bottleneck sparse convolution residual block with 1x3x1 conv layers and expansion factor of 4', 'build a BasicBlockBase subclass with a custom NORM_TYPE for sparse convolution residual processing', 'build a BottleneckBase block with custom stride and dilation for sparse 3D feature extraction', 'review the BasicBlockBase and BottleneckBase forward methods for residual connection and MinkowskiReLU usage']
```

Usage

```
{'create_sparse_conv': 'create a MinkowskiEngine sparse convolution layer with configurable kernel size, stride, and dimension', 'create_sparse_transpose_conv': 'create a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features', 'create_sparse_avg_pool': 'create a MinkowskiEngine sparse average pooling layer with configurable kernel size and stride', 'create_sparse_sum_pool': 'create a MinkowskiEngine sparse sum pooling layer for aggregating sparse tensor features', 'create_sparse_norm': 'create a MinkowskiEngine batch or instance normalization layer for sparse tensor normalization'}
```

## File: facebookresearch_contrastivescenecontexts/pretrain/contrastive_scene_contexts/model/modules/resnet_block.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer with configurable kernel size, stride, and dimension', 'create a MinkowskiEngine sparse transposed convolution layer for upsampling sparse tensor features', 'create a MinkowskiEngine sparse average pooling layer with configurable kernel size and stride', 'create a MinkowskiEngine sparse sum pooling layer for aggregating sparse tensor features', 'create a MinkowskiEngine batch or instance normalization layer for sparse tensor normalization', 'create a BasicBlock sparse convolution residual block with batch normalization for 3D sparse tensor processing', 'create a Bottleneck sparse convolution residual block with 1x3x1 conv layers and expansion factor of 4', 'build a BasicBlockBase subclass with a custom NORM_TYPE for sparse convolution residual processing', 'build a BottleneckBase block with custom stride and dilation for sparse 3D feature extraction', 'review the BasicBlockBase and BottleneckBase forward methods for residual connection and MinkowskiReLU usage']
```

Usage

```
{'create_basic_block': 'create a BasicBlock sparse convolution residual block with batch normalization for 3D sparse tensor processing', 'create_bottleneck_block': 'create a Bottleneck sparse convolution residual block with 1x3x1 conv layers and expansion factor of 4', 'build_basicblockbase_with_custom_norm': 'build a BasicBlockBase subclass with a custom NORM_TYPE for sparse convolution residual processing', 'build_bottleneckbase_with_stride': 'build a BottleneckBase block with custom stride and dilation for sparse 3D feature extraction', 'review_resnet_block_forward': 'review the BasicBlockBase and BottleneckBase forward methods for residual connection and MinkowskiReLU usage'}
```

