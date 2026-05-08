# Agent Python Tools

- repo: facebookresearch/pointcontrast
- repo_uri: https://github.com/facebookresearch/pointcontrast

## File: facebookresearch_pointcontrast/pretrain/pointcontrast/model/modules/common.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer using conv with specified in/out planes and kernel size', 'create a MinkowskiEngine sparse transposed convolution layer using conv_tr for upsampling sparse tensor features', 'create a MinkowskiEngine sparse average pooling layer using avg_pool with configurable kernel size and stride', 'create a MinkowskiEngine sparse sum pooling layer using sum_pool to aggregate sparse tensor features', 'create a MinkowskiEngine normalization layer using get_norm with BATCH_NORM or SPARSE_INSTANCE_NORM type', 'build a MinkowskiEngine BasicBlock for sparse 3D convolutional residual layers with batch norm', 'build a MinkowskiEngine Bottleneck block with 1x3x1 conv pattern and 4x channel expansion', 'create a subclass of BasicBlockBase to customize the NORM_TYPE for sparse conv blocks', 'create a subclass of BottleneckBase to customize the NORM_TYPE for sparse conv blocks', 'review the BasicBlockBase forward pass with conv-norm-relu-residual pattern for sparse tensors']
```

Usage

```
{'create_sparse_conv': 'create a MinkowskiEngine sparse convolution layer using conv with specified in/out planes and kernel size', 'create_sparse_transpose_conv': 'create a MinkowskiEngine sparse transposed convolution layer using conv_tr for upsampling sparse tensor features', 'create_sparse_avg_pool': 'create a MinkowskiEngine sparse average pooling layer using avg_pool with configurable kernel size and stride', 'create_sparse_sum_pool': 'create a MinkowskiEngine sparse sum pooling layer using sum_pool to aggregate sparse tensor features', 'create_sparse_norm': 'create a MinkowskiEngine normalization layer using get_norm with BATCH_NORM or SPARSE_INSTANCE_NORM type'}
```

## File: facebookresearch_pointcontrast/pretrain/pointcontrast/model/modules/resnet_block.py

Prompts

```
['create a MinkowskiEngine sparse convolution layer using conv with specified in/out planes and kernel size', 'create a MinkowskiEngine sparse transposed convolution layer using conv_tr for upsampling sparse tensor features', 'create a MinkowskiEngine sparse average pooling layer using avg_pool with configurable kernel size and stride', 'create a MinkowskiEngine sparse sum pooling layer using sum_pool to aggregate sparse tensor features', 'create a MinkowskiEngine normalization layer using get_norm with BATCH_NORM or SPARSE_INSTANCE_NORM type', 'build a MinkowskiEngine BasicBlock for sparse 3D convolutional residual layers with batch norm', 'build a MinkowskiEngine Bottleneck block with 1x3x1 conv pattern and 4x channel expansion', 'create a subclass of BasicBlockBase to customize the NORM_TYPE for sparse conv blocks', 'create a subclass of BottleneckBase to customize the NORM_TYPE for sparse conv blocks', 'review the BasicBlockBase forward pass with conv-norm-relu-residual pattern for sparse tensors']
```

Usage

```
{'build_basicblock': 'build a MinkowskiEngine BasicBlock for sparse 3D convolutional residual layers with batch norm', 'build_bottleneck': 'build a MinkowskiEngine Bottleneck block with 1x3x1 conv pattern and 4x channel expansion', 'create_basicblockbase_subclass': 'create a subclass of BasicBlockBase to customize the NORM_TYPE for sparse conv blocks', 'create_bottleneckbase_subclass': 'create a subclass of BottleneckBase to customize the NORM_TYPE for sparse conv blocks', 'review_basicblock_forward': 'review the BasicBlockBase forward pass with conv-norm-relu-residual pattern for sparse tensors'}
```

