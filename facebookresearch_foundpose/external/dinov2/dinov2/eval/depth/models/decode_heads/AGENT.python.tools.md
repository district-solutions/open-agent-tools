# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/depth/models/decode_heads/decode_head.py

Prompts

```
['build a DepthBaseDecodeHead subclass to predict depth maps from image features', 'create depth predictions from feature tensors using the depth_pred method with classify or regression mode', 'run forward_train to compute depth losses and log images during training', 'compute depth prediction losses against ground truth using the losses method with SigLoss', 'log normalized RGB images and depth predictions for visualization using log_images', 'build a DPTHead module for monocular depth estimation using ViT backbone features', 'create ReassembleBlocks to process ViT cls tokens and rearrange feature vectors to feature maps', 'build a FeatureFusionBlock to merge feature maps from different stages with residual conv units', 'create a HeadDepth module that predicts depth maps from feature tensors using conv layers', 'review the PreActResidualConvUnit pre-activate residual block for use in feature fusion pipelines', 'build a BNHead depth decode head with resize_concat input transform and multi-level feature indices', 'create a BNHead that uses classify mode with n_bins for classification-regression depth prediction', 'test the BNHead forward pass with multi-level image feature tensors and img_metas', 'review the BNHead _transform_inputs method for resize_concat and multiple_select input transform modes', 'refactor the BNHead _forward_feature method to handle cls token concatenation with feature maps']
```

Usage

```
{'build_depth_decode_head': 'build a DepthBaseDecodeHead subclass to predict depth maps from image features', 'create_depth_prediction': 'create depth predictions from feature tensors using the depth_pred method with classify or regression mode', 'run_forward_train': 'run forward_train to compute depth losses and log images during training', 'compute_depth_losses': 'compute depth prediction losses against ground truth using the losses method with SigLoss', 'log_depth_images': 'log normalized RGB images and depth predictions for visualization using log_images'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/depth/models/decode_heads/dpt_head.py

Prompts

```
['build a DepthBaseDecodeHead subclass to predict depth maps from image features', 'create depth predictions from feature tensors using the depth_pred method with classify or regression mode', 'run forward_train to compute depth losses and log images during training', 'compute depth prediction losses against ground truth using the losses method with SigLoss', 'log normalized RGB images and depth predictions for visualization using log_images', 'build a DPTHead module for monocular depth estimation using ViT backbone features', 'create ReassembleBlocks to process ViT cls tokens and rearrange feature vectors to feature maps', 'build a FeatureFusionBlock to merge feature maps from different stages with residual conv units', 'create a HeadDepth module that predicts depth maps from feature tensors using conv layers', 'review the PreActResidualConvUnit pre-activate residual block for use in feature fusion pipelines', 'build a BNHead depth decode head with resize_concat input transform and multi-level feature indices', 'create a BNHead that uses classify mode with n_bins for classification-regression depth prediction', 'test the BNHead forward pass with multi-level image feature tensors and img_metas', 'review the BNHead _transform_inputs method for resize_concat and multiple_select input transform modes', 'refactor the BNHead _forward_feature method to handle cls token concatenation with feature maps']
```

Usage

```
{'build_DPTHead_for_depth_estimation': 'build a DPTHead module for monocular depth estimation using ViT backbone features', 'create_ReassembleBlocks_for_ViT_features': 'create ReassembleBlocks to process ViT cls tokens and rearrange feature vectors to feature maps', 'build_FeatureFusionBlock_for_multi_stage_fusion': 'build a FeatureFusionBlock to merge feature maps from different stages with residual conv units', 'create_HeadDepth_for_depth_prediction': 'create a HeadDepth module that predicts depth maps from feature tensors using conv layers', 'review_PreActResidualConvUnit_architecture': 'review the PreActResidualConvUnit pre-activate residual block for use in feature fusion pipelines'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/depth/models/decode_heads/linear_head.py

Prompts

```
['build a DepthBaseDecodeHead subclass to predict depth maps from image features', 'create depth predictions from feature tensors using the depth_pred method with classify or regression mode', 'run forward_train to compute depth losses and log images during training', 'compute depth prediction losses against ground truth using the losses method with SigLoss', 'log normalized RGB images and depth predictions for visualization using log_images', 'build a DPTHead module for monocular depth estimation using ViT backbone features', 'create ReassembleBlocks to process ViT cls tokens and rearrange feature vectors to feature maps', 'build a FeatureFusionBlock to merge feature maps from different stages with residual conv units', 'create a HeadDepth module that predicts depth maps from feature tensors using conv layers', 'review the PreActResidualConvUnit pre-activate residual block for use in feature fusion pipelines', 'build a BNHead depth decode head with resize_concat input transform and multi-level feature indices', 'create a BNHead that uses classify mode with n_bins for classification-regression depth prediction', 'test the BNHead forward pass with multi-level image feature tensors and img_metas', 'review the BNHead _transform_inputs method for resize_concat and multiple_select input transform modes', 'refactor the BNHead _forward_feature method to handle cls token concatenation with feature maps']
```

Usage

```
{'build_BNHead_for_depth_estimation': 'build a BNHead depth decode head with resize_concat input transform and multi-level feature indices', 'create_BNHead_with_classification': 'create a BNHead that uses classify mode with n_bins for classification-regression depth prediction', 'test_BNHead_forward': 'test the BNHead forward pass with multi-level image feature tensors and img_metas', 'review_BNHead_transform_inputs': 'review the BNHead _transform_inputs method for resize_concat and multiple_select input transform modes', 'refactor_BNHead_forward_feature': 'refactor the BNHead _forward_feature method to handle cls token concatenation with feature maps'}
```

