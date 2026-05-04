# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/dinov2/dinov2/hub/depth/decode_heads.py

Prompts

```
['build a DPTHead module to predict depth maps from ViT backbone multi-scale feature inputs', 'create a BNHead module to predict depth from concatenated multi-level image features', 'build a ConvModule that bundles convolution, normalization, and activation layers in configurable order', 'create ReassembleBlocks to process ViT cls tokens and rearrange feature vectors into feature maps', 'test the FeatureFusionBlock to merge and upsample feature maps from different network stages', 'build a DepthEncoderDecoder model with a backbone and decode_head for monocular depth estimation', 'run forward_train on the DepthEncoderDecoder to compute loss from images and ground truth depth', 'run forward_test on the DepthEncoderDecoder to perform inference with optional test-time augmentations', 'run slide_inference on the DepthEncoderDecoder to predict depth using overlapping sliding window crops', 'run extract_feat on the DepthEncoderDecoder to extract multi-scale features from input images', 'resize a PyTorch tensor to a target size using nearest neighbor interpolation', 'resize a PyTorch tensor to a target size using bilinear interpolation with align corners', 'resize a PyTorch tensor by a given scale factor using the default nearest mode', 'resize a PyTorch tensor with an alignment warning when upscaling with align corners enabled', 'review the resize function that wraps F.interpolate with optional alignment corner warnings']
```

Usage

```
{'build_DPTHead_for_depth_estimation': 'build a DPTHead module to predict depth maps from ViT backbone multi-scale feature inputs', 'create_BNHead_for_simple_depth': 'create a BNHead module to predict depth from concatenated multi-level image features', 'build_ConvModule_with_norm_and_act': 'build a ConvModule that bundles convolution, normalization, and activation layers in configurable order', 'create_ReassembleBlocks_for_ViT_features': 'create ReassembleBlocks to process ViT cls tokens and rearrange feature vectors into feature maps', 'test_FeatureFusionBlock_for_multi_stage_fusion': 'test the FeatureFusionBlock to merge and upsample feature maps from different network stages'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/hub/depth/encoder_decoder.py

Prompts

```
['build a DPTHead module to predict depth maps from ViT backbone multi-scale feature inputs', 'create a BNHead module to predict depth from concatenated multi-level image features', 'build a ConvModule that bundles convolution, normalization, and activation layers in configurable order', 'create ReassembleBlocks to process ViT cls tokens and rearrange feature vectors into feature maps', 'test the FeatureFusionBlock to merge and upsample feature maps from different network stages', 'build a DepthEncoderDecoder model with a backbone and decode_head for monocular depth estimation', 'run forward_train on the DepthEncoderDecoder to compute loss from images and ground truth depth', 'run forward_test on the DepthEncoderDecoder to perform inference with optional test-time augmentations', 'run slide_inference on the DepthEncoderDecoder to predict depth using overlapping sliding window crops', 'run extract_feat on the DepthEncoderDecoder to extract multi-scale features from input images', 'resize a PyTorch tensor to a target size using nearest neighbor interpolation', 'resize a PyTorch tensor to a target size using bilinear interpolation with align corners', 'resize a PyTorch tensor by a given scale factor using the default nearest mode', 'resize a PyTorch tensor with an alignment warning when upscaling with align corners enabled', 'review the resize function that wraps F.interpolate with optional alignment corner warnings']
```

Usage

```
{'build_depth_encoder_decoder': 'build a DepthEncoderDecoder model with a backbone and decode_head for monocular depth estimation', 'run_forward_train': 'run forward_train on the DepthEncoderDecoder to compute loss from images and ground truth depth', 'run_forward_test': 'run forward_test on the DepthEncoderDecoder to perform inference with optional test-time augmentations', 'run_slide_inference': 'run slide_inference on the DepthEncoderDecoder to predict depth using overlapping sliding window crops', 'run_extract_feat': 'run extract_feat on the DepthEncoderDecoder to extract multi-scale features from input images'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/hub/depth/ops.py

Prompts

```
['build a DPTHead module to predict depth maps from ViT backbone multi-scale feature inputs', 'create a BNHead module to predict depth from concatenated multi-level image features', 'build a ConvModule that bundles convolution, normalization, and activation layers in configurable order', 'create ReassembleBlocks to process ViT cls tokens and rearrange feature vectors into feature maps', 'test the FeatureFusionBlock to merge and upsample feature maps from different network stages', 'build a DepthEncoderDecoder model with a backbone and decode_head for monocular depth estimation', 'run forward_train on the DepthEncoderDecoder to compute loss from images and ground truth depth', 'run forward_test on the DepthEncoderDecoder to perform inference with optional test-time augmentations', 'run slide_inference on the DepthEncoderDecoder to predict depth using overlapping sliding window crops', 'run extract_feat on the DepthEncoderDecoder to extract multi-scale features from input images', 'resize a PyTorch tensor to a target size using nearest neighbor interpolation', 'resize a PyTorch tensor to a target size using bilinear interpolation with align corners', 'resize a PyTorch tensor by a given scale factor using the default nearest mode', 'resize a PyTorch tensor with an alignment warning when upscaling with align corners enabled', 'review the resize function that wraps F.interpolate with optional alignment corner warnings']
```

Usage

```
{'resize_tensor_nearest': 'resize a PyTorch tensor to a target size using nearest neighbor interpolation', 'resize_tensor_bilinear': 'resize a PyTorch tensor to a target size using bilinear interpolation with align corners', 'resize_tensor_scale_factor': 'resize a PyTorch tensor by a given scale factor using the default nearest mode', 'resize_tensor_with_warning': 'resize a PyTorch tensor with an alignment warning when upscaling with align corners enabled', 'review_resize_wrapper': 'review the resize function that wraps F.interpolate with optional alignment corner warnings'}
```

