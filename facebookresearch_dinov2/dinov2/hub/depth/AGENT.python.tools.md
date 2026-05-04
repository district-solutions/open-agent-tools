# Agent Python Tools

- repo: facebookresearch/dinov2
- repo_uri: https://github.com/facebookresearch/dinov2.git

## File: facebookresearch_dinov2/dinov2/hub/depth/decode_heads.py

Prompts

```
['build a DPTHead module to predict depth maps from ViT backbone multi-scale feature inputs', 'create a BNHead decode head that concatenates multi-level features and predicts depth via a single conv layer', 'use ConvModule to bundle convolution, normalization, and activation layers with configurable ordering', 'build ReassembleBlocks to process ViT cls tokens and rearrange feature vectors into spatial feature maps', 'use FeatureFusionBlock to merge and upsample feature maps from different ViT stages with residual units', 'build a depth estimation model using a backbone network and decode head for monocular depth prediction', 'run the training forward pass on input images with ground truth depth to compute loss components', 'run inference on images with optional test-time augmentations to produce depth prediction maps', 'run sliding window inference with configurable stride and crop size for high resolution depth estimation', 'review the add_prefix utility function that prepends a string prefix to all keys in a dictionary', 'resize a PyTorch tensor to a specified height and width using nearest neighbor interpolation', 'resize a PyTorch tensor by a given scale factor using bilinear interpolation', 'resize a PyTorch tensor with align_corners enabled and optional alignment warnings', 'resize a PyTorch tensor using a custom interpolation mode like bicubic or area', 'review the resize function warning logic that checks input and output dimension alignment']
```

Usage

```
{'build_DPTHead_for_depth_prediction': 'build a DPTHead module to predict depth maps from ViT backbone multi-scale feature inputs', 'create_BNHead_for_simple_depth': 'create a BNHead decode head that concatenates multi-level features and predicts depth via a single conv layer', 'use_ConvModule_for_conv_blocks': 'use ConvModule to bundle convolution, normalization, and activation layers with configurable ordering', 'build_ReassembleBlocks_for_ViT_features': 'build ReassembleBlocks to process ViT cls tokens and rearrange feature vectors into spatial feature maps', 'use_FeatureFusionBlock_for_multi_scale_fusion': 'use FeatureFusionBlock to merge and upsample feature maps from different ViT stages with residual units'}
```

## File: facebookresearch_dinov2/dinov2/hub/depth/encoder_decoder.py

Prompts

```
['build a DPTHead module to predict depth maps from ViT backbone multi-scale feature inputs', 'create a BNHead decode head that concatenates multi-level features and predicts depth via a single conv layer', 'use ConvModule to bundle convolution, normalization, and activation layers with configurable ordering', 'build ReassembleBlocks to process ViT cls tokens and rearrange feature vectors into spatial feature maps', 'use FeatureFusionBlock to merge and upsample feature maps from different ViT stages with residual units', 'build a depth estimation model using a backbone network and decode head for monocular depth prediction', 'run the training forward pass on input images with ground truth depth to compute loss components', 'run inference on images with optional test-time augmentations to produce depth prediction maps', 'run sliding window inference with configurable stride and crop size for high resolution depth estimation', 'review the add_prefix utility function that prepends a string prefix to all keys in a dictionary', 'resize a PyTorch tensor to a specified height and width using nearest neighbor interpolation', 'resize a PyTorch tensor by a given scale factor using bilinear interpolation', 'resize a PyTorch tensor with align_corners enabled and optional alignment warnings', 'resize a PyTorch tensor using a custom interpolation mode like bicubic or area', 'review the resize function warning logic that checks input and output dimension alignment']
```

Usage

```
{'build_DepthEncoderDecoder': 'build a depth estimation model using a backbone network and decode head for monocular depth prediction', 'run_forward_train': 'run the training forward pass on input images with ground truth depth to compute loss components', 'run_forward_test': 'run inference on images with optional test-time augmentations to produce depth prediction maps', 'run_slide_inference': 'run sliding window inference with configurable stride and crop size for high resolution depth estimation', 'review_add_prefix': 'review the add_prefix utility function that prepends a string prefix to all keys in a dictionary'}
```

## File: facebookresearch_dinov2/dinov2/hub/depth/ops.py

Prompts

```
['build a DPTHead module to predict depth maps from ViT backbone multi-scale feature inputs', 'create a BNHead decode head that concatenates multi-level features and predicts depth via a single conv layer', 'use ConvModule to bundle convolution, normalization, and activation layers with configurable ordering', 'build ReassembleBlocks to process ViT cls tokens and rearrange feature vectors into spatial feature maps', 'use FeatureFusionBlock to merge and upsample feature maps from different ViT stages with residual units', 'build a depth estimation model using a backbone network and decode head for monocular depth prediction', 'run the training forward pass on input images with ground truth depth to compute loss components', 'run inference on images with optional test-time augmentations to produce depth prediction maps', 'run sliding window inference with configurable stride and crop size for high resolution depth estimation', 'review the add_prefix utility function that prepends a string prefix to all keys in a dictionary', 'resize a PyTorch tensor to a specified height and width using nearest neighbor interpolation', 'resize a PyTorch tensor by a given scale factor using bilinear interpolation', 'resize a PyTorch tensor with align_corners enabled and optional alignment warnings', 'resize a PyTorch tensor using a custom interpolation mode like bicubic or area', 'review the resize function warning logic that checks input and output dimension alignment']
```

Usage

```
{'resize_tensor_by_size': 'resize a PyTorch tensor to a specified height and width using nearest neighbor interpolation', 'resize_tensor_by_scale': 'resize a PyTorch tensor by a given scale factor using bilinear interpolation', 'resize_tensor_align_corners': 'resize a PyTorch tensor with align_corners enabled and optional alignment warnings', 'resize_tensor_custom_mode': 'resize a PyTorch tensor using a custom interpolation mode like bicubic or area', 'review_resize_warning_logic': 'review the resize function warning logic that checks input and output dimension alignment'}
```

