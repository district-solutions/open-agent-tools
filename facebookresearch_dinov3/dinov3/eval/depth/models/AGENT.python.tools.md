# Agent Python Tools

- repo: facebookresearch/dinov3
- repo_uri: https://github.com/facebookresearch/dinov3

## File: facebookresearch_dinov3/dinov3/eval/depth/models/dpt_head.py

Prompts

```
['build a DPTHead module for monocular depth estimation from ViT backbone features', 'create a ConvModule that bundles conv, batch norm, and ReLU activation layers', 'build ReassembleBlocks to project and resize ViT multi-scale feature maps with cls token readout', 'create a FeatureFusionBlock to merge and upsample multi-scale features with residual conv units', 'test the DPTHead forward_features method with a list of ViT feature tensors', 'create a CenterPadding module that pads tensor dimensions to a specified multiple', 'use CenterPadding forward pass to pad a PyTorch tensor to even multiples', 'create a StretchToMultiple module that interpolates tensor dimensions to a specified multiple', 'use StretchToMultiple forward pass to bilinearly interpolate a tensor to even multiples', 'compare CenterPadding zero-padding versus StretchToMultiple bilinear interpolation for tensor dimension alignment', 'create a DinoVisionTransformerWrapper to extract intermediate layers from a ViT backbone model', 'get output layer indices for a ViT backbone using FOUR_EVEN_INTERVALS strategy', 'configure DinoVisionTransformerWrapper to extract the last 4 layers from a backbone model', 'create a DinoVisionTransformerWrapper with center padding to adapt input images to patch size', 'create a DinoVisionTransformerWrapper that freezes the backbone model gradients for inference', 'create a LinearHead module with specified input channels and output channels for depth estimation', 'build a LinearHead with SyncBatchNorm enabled for multi-level image feature processing', 'run a forward pass through the LinearHead to transform multi-level feature inputs into depth predictions', 'predict a depth map by running forward and bilinear interpolation to a target resolution', 'review the LinearHead class and how it concatenates CLS tokens with patch tokens']
```

Usage

```
{'build_DPTHead_for_depth_estimation': 'build a DPTHead module for monocular depth estimation from ViT backbone features', 'create_ConvModule_with_norm_and_activation': 'create a ConvModule that bundles conv, batch norm, and ReLU activation layers', 'build_ReassembleBlocks_for_ViT_features': 'build ReassembleBlocks to project and resize ViT multi-scale feature maps with cls token readout', 'create_FeatureFusionBlock_for_multi_scale_fusion': 'create a FeatureFusionBlock to merge and upsample multi-scale features with residual conv units', 'test_DPTHead_forward_features': 'test the DPTHead forward_features method with a list of ViT feature tensors'}
```

## File: facebookresearch_dinov3/dinov3/eval/depth/models/embed.py

Prompts

```
['build a DPTHead module for monocular depth estimation from ViT backbone features', 'create a ConvModule that bundles conv, batch norm, and ReLU activation layers', 'build ReassembleBlocks to project and resize ViT multi-scale feature maps with cls token readout', 'create a FeatureFusionBlock to merge and upsample multi-scale features with residual conv units', 'test the DPTHead forward_features method with a list of ViT feature tensors', 'create a CenterPadding module that pads tensor dimensions to a specified multiple', 'use CenterPadding forward pass to pad a PyTorch tensor to even multiples', 'create a StretchToMultiple module that interpolates tensor dimensions to a specified multiple', 'use StretchToMultiple forward pass to bilinearly interpolate a tensor to even multiples', 'compare CenterPadding zero-padding versus StretchToMultiple bilinear interpolation for tensor dimension alignment', 'create a DinoVisionTransformerWrapper to extract intermediate layers from a ViT backbone model', 'get output layer indices for a ViT backbone using FOUR_EVEN_INTERVALS strategy', 'configure DinoVisionTransformerWrapper to extract the last 4 layers from a backbone model', 'create a DinoVisionTransformerWrapper with center padding to adapt input images to patch size', 'create a DinoVisionTransformerWrapper that freezes the backbone model gradients for inference', 'create a LinearHead module with specified input channels and output channels for depth estimation', 'build a LinearHead with SyncBatchNorm enabled for multi-level image feature processing', 'run a forward pass through the LinearHead to transform multi-level feature inputs into depth predictions', 'predict a depth map by running forward and bilinear interpolation to a target resolution', 'review the LinearHead class and how it concatenates CLS tokens with patch tokens']
```

Usage

```
{'create_center_padding_module': 'create a CenterPadding module that pads tensor dimensions to a specified multiple', 'use_center_padding_forward': 'use CenterPadding forward pass to pad a PyTorch tensor to even multiples', 'create_stretch_to_multiple_module': 'create a StretchToMultiple module that interpolates tensor dimensions to a specified multiple', 'use_stretch_to_multiple_forward': 'use StretchToMultiple forward pass to bilinearly interpolate a tensor to even multiples', 'compare_padding_vs_stretching': 'compare CenterPadding zero-padding versus StretchToMultiple bilinear interpolation for tensor dimension alignment'}
```

## File: facebookresearch_dinov3/dinov3/eval/depth/models/encoder.py

Prompts

```
['build a DPTHead module for monocular depth estimation from ViT backbone features', 'create a ConvModule that bundles conv, batch norm, and ReLU activation layers', 'build ReassembleBlocks to project and resize ViT multi-scale feature maps with cls token readout', 'create a FeatureFusionBlock to merge and upsample multi-scale features with residual conv units', 'test the DPTHead forward_features method with a list of ViT feature tensors', 'create a CenterPadding module that pads tensor dimensions to a specified multiple', 'use CenterPadding forward pass to pad a PyTorch tensor to even multiples', 'create a StretchToMultiple module that interpolates tensor dimensions to a specified multiple', 'use StretchToMultiple forward pass to bilinearly interpolate a tensor to even multiples', 'compare CenterPadding zero-padding versus StretchToMultiple bilinear interpolation for tensor dimension alignment', 'create a DinoVisionTransformerWrapper to extract intermediate layers from a ViT backbone model', 'get output layer indices for a ViT backbone using FOUR_EVEN_INTERVALS strategy', 'configure DinoVisionTransformerWrapper to extract the last 4 layers from a backbone model', 'create a DinoVisionTransformerWrapper with center padding to adapt input images to patch size', 'create a DinoVisionTransformerWrapper that freezes the backbone model gradients for inference', 'create a LinearHead module with specified input channels and output channels for depth estimation', 'build a LinearHead with SyncBatchNorm enabled for multi-level image feature processing', 'run a forward pass through the LinearHead to transform multi-level feature inputs into depth predictions', 'predict a depth map by running forward and bilinear interpolation to a target resolution', 'review the LinearHead class and how it concatenates CLS tokens with patch tokens']
```

Usage

```
{'create_vit_wrapper': 'create a DinoVisionTransformerWrapper to extract intermediate layers from a ViT backbone model', 'get_backbone_out_indices': 'get output layer indices for a ViT backbone using FOUR_EVEN_INTERVALS strategy', 'configure_backbone_layers': 'configure DinoVisionTransformerWrapper to extract the last 4 layers from a backbone model', 'adapt_patch_size': 'create a DinoVisionTransformerWrapper with center padding to adapt input images to patch size', 'freeze_backbone_encoder': 'create a DinoVisionTransformerWrapper that freezes the backbone model gradients for inference'}
```

## File: facebookresearch_dinov3/dinov3/eval/depth/models/linear_head.py

Prompts

```
['build a DPTHead module for monocular depth estimation from ViT backbone features', 'create a ConvModule that bundles conv, batch norm, and ReLU activation layers', 'build ReassembleBlocks to project and resize ViT multi-scale feature maps with cls token readout', 'create a FeatureFusionBlock to merge and upsample multi-scale features with residual conv units', 'test the DPTHead forward_features method with a list of ViT feature tensors', 'create a CenterPadding module that pads tensor dimensions to a specified multiple', 'use CenterPadding forward pass to pad a PyTorch tensor to even multiples', 'create a StretchToMultiple module that interpolates tensor dimensions to a specified multiple', 'use StretchToMultiple forward pass to bilinearly interpolate a tensor to even multiples', 'compare CenterPadding zero-padding versus StretchToMultiple bilinear interpolation for tensor dimension alignment', 'create a DinoVisionTransformerWrapper to extract intermediate layers from a ViT backbone model', 'get output layer indices for a ViT backbone using FOUR_EVEN_INTERVALS strategy', 'configure DinoVisionTransformerWrapper to extract the last 4 layers from a backbone model', 'create a DinoVisionTransformerWrapper with center padding to adapt input images to patch size', 'create a DinoVisionTransformerWrapper that freezes the backbone model gradients for inference', 'create a LinearHead module with specified input channels and output channels for depth estimation', 'build a LinearHead with SyncBatchNorm enabled for multi-level image feature processing', 'run a forward pass through the LinearHead to transform multi-level feature inputs into depth predictions', 'predict a depth map by running forward and bilinear interpolation to a target resolution', 'review the LinearHead class and how it concatenates CLS tokens with patch tokens']
```

Usage

```
{'create_linear_head_for_depth': 'create a LinearHead module with specified input channels and output channels for depth estimation', 'build_linear_head_with_batchnorm': 'build a LinearHead with SyncBatchNorm enabled for multi-level image feature processing', 'run_forward_pass_linear_head': 'run a forward pass through the LinearHead to transform multi-level feature inputs into depth predictions', 'predict_depth_map_linear_head': 'predict a depth map by running forward and bilinear interpolation to a target resolution', 'review_linear_head_cls_token_handling': 'review the LinearHead class and how it concatenates CLS tokens with patch tokens'}
```

