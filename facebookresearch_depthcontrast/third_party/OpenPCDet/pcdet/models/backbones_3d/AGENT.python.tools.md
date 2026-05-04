# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/models/backbones_3d/pointnet2_backbone.py

Prompts

```
['build a PointNet2MSG backbone with SA and FP modules for 3D point cloud feature extraction', 'run the PointNet2MSG forward pass on a batch_dict containing 3D point cloud data', 'review the PointNet2MSG break_up_pc method that splits point clouds into batch indices, xyz, and features', 'refactor the PointNet2MSG SA modules to customize set abstraction layer configuration and MLP architecture', 'summarize the deprecated PointNet2Backbone class and its potential bugs noted in the 20200723 warning', 'build a VoxelBackBone8x sparse 3D convolution backbone for LiDAR voxel feature encoding with 8x stride', 'build a VoxelResBackBone8x sparse 3D backbone with residual blocks for LiDAR voxel feature encoding', 'create a sparse convolution block with configurable subm, spconv, or inverse conv types and normalization', 'create a SparseBasicBlock residual module with two submanifold convolutions and batch normalization for sparse tensors', 'review the VoxelBackBone8x forward pass that encodes voxel features into multi-scale 3D sparse tensors', 'build a sparse convolution UNet backbone for 3D point cloud feature learning with encoder-decoder architecture', 'create a sparse residual block using SubMConv3d layers with batch norm and ReLU activation', 'run the UNetV2 forward pass on voxel features to extract point-wise features and coordinates', 'refactor the channel_reduction static method to reduce feature channels via view and sum pooling', 'review the UR_block_forward method that merges lateral and bottom features with inverse convolution']
```

Usage

```
{'build_PointNet2MSG_backbone': 'build a PointNet2MSG backbone with SA and FP modules for 3D point cloud feature extraction', 'run_PointNet2MSG_forward': 'run the PointNet2MSG forward pass on a batch_dict containing 3D point cloud data', 'review_PointNet2MSG_break_up_pc': 'review the PointNet2MSG break_up_pc method that splits point clouds into batch indices, xyz, and features', 'refactor_PointNet2MSG_SA_modules': 'refactor the PointNet2MSG SA modules to customize set abstraction layer configuration and MLP architecture', 'summarize_PointNet2Backbone': 'summarize the deprecated PointNet2Backbone class and its potential bugs noted in the 20200723 warning'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/models/backbones_3d/spconv_backbone.py

Prompts

```
['build a PointNet2MSG backbone with SA and FP modules for 3D point cloud feature extraction', 'run the PointNet2MSG forward pass on a batch_dict containing 3D point cloud data', 'review the PointNet2MSG break_up_pc method that splits point clouds into batch indices, xyz, and features', 'refactor the PointNet2MSG SA modules to customize set abstraction layer configuration and MLP architecture', 'summarize the deprecated PointNet2Backbone class and its potential bugs noted in the 20200723 warning', 'build a VoxelBackBone8x sparse 3D convolution backbone for LiDAR voxel feature encoding with 8x stride', 'build a VoxelResBackBone8x sparse 3D backbone with residual blocks for LiDAR voxel feature encoding', 'create a sparse convolution block with configurable subm, spconv, or inverse conv types and normalization', 'create a SparseBasicBlock residual module with two submanifold convolutions and batch normalization for sparse tensors', 'review the VoxelBackBone8x forward pass that encodes voxel features into multi-scale 3D sparse tensors', 'build a sparse convolution UNet backbone for 3D point cloud feature learning with encoder-decoder architecture', 'create a sparse residual block using SubMConv3d layers with batch norm and ReLU activation', 'run the UNetV2 forward pass on voxel features to extract point-wise features and coordinates', 'refactor the channel_reduction static method to reduce feature channels via view and sum pooling', 'review the UR_block_forward method that merges lateral and bottom features with inverse convolution']
```

Usage

```
{'build_VoxelBackBone8x': 'build a VoxelBackBone8x sparse 3D convolution backbone for LiDAR voxel feature encoding with 8x stride', 'build_VoxelResBackBone8x': 'build a VoxelResBackBone8x sparse 3D backbone with residual blocks for LiDAR voxel feature encoding', 'create_post_act_block': 'create a sparse convolution block with configurable subm, spconv, or inverse conv types and normalization', 'create_SparseBasicBlock': 'create a SparseBasicBlock residual module with two submanifold convolutions and batch normalization for sparse tensors', 'review_VoxelBackBone8x_forward': 'review the VoxelBackBone8x forward pass that encodes voxel features into multi-scale 3D sparse tensors'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/models/backbones_3d/spconv_unet.py

Prompts

```
['build a PointNet2MSG backbone with SA and FP modules for 3D point cloud feature extraction', 'run the PointNet2MSG forward pass on a batch_dict containing 3D point cloud data', 'review the PointNet2MSG break_up_pc method that splits point clouds into batch indices, xyz, and features', 'refactor the PointNet2MSG SA modules to customize set abstraction layer configuration and MLP architecture', 'summarize the deprecated PointNet2Backbone class and its potential bugs noted in the 20200723 warning', 'build a VoxelBackBone8x sparse 3D convolution backbone for LiDAR voxel feature encoding with 8x stride', 'build a VoxelResBackBone8x sparse 3D backbone with residual blocks for LiDAR voxel feature encoding', 'create a sparse convolution block with configurable subm, spconv, or inverse conv types and normalization', 'create a SparseBasicBlock residual module with two submanifold convolutions and batch normalization for sparse tensors', 'review the VoxelBackBone8x forward pass that encodes voxel features into multi-scale 3D sparse tensors', 'build a sparse convolution UNet backbone for 3D point cloud feature learning with encoder-decoder architecture', 'create a sparse residual block using SubMConv3d layers with batch norm and ReLU activation', 'run the UNetV2 forward pass on voxel features to extract point-wise features and coordinates', 'refactor the channel_reduction static method to reduce feature channels via view and sum pooling', 'review the UR_block_forward method that merges lateral and bottom features with inverse convolution']
```

Usage

```
{'build_UNetV2_sparse_conv_unet': 'build a sparse convolution UNet backbone for 3D point cloud feature learning with encoder-decoder architecture', 'create_SparseBasicBlock_residual': 'create a sparse residual block using SubMConv3d layers with batch norm and ReLU activation', 'run_UNetV2_forward_pass': 'run the UNetV2 forward pass on voxel features to extract point-wise features and coordinates', 'refactor_UNetV2_channel_reduction': 'refactor the channel_reduction static method to reduce feature channels via view and sum pooling', 'review_UNetV2_UR_block_forward': 'review the UR_block_forward method that merges lateral and bottom features with inverse convolution'}
```

