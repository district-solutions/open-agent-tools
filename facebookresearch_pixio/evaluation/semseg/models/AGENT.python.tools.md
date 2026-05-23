# Agent Python Tools

- repo: facebookresearch/pixio
- repo_uri: https://github.com/facebookresearch/pixio

## File: facebookresearch_pixio/evaluation/semseg/models/blocks.py

Prompts

```
['build a scratch module with Conv2d layers from input and output channel shapes', 'create a ResidualConvUnit with configurable features, activation, and batch normalization', 'create a FeatureFusionBlock that fuses and upsamples multi-scale features with residual connections', 'test the ResidualConvUnit forward pass with a sample tensor input', 'test the FeatureFusionBlock forward pass with one or two input feature tensors', 'build a DPTSeg model with a PIXIO encoder and DPT head for semantic segmentation', 'create a DPTHead module with project layers, resize layers, and feature fusion blocks', 'run the DPTSeg forward pass to extract features and produce segmentation output', 'lock the DPTSeg encoder parameters to freeze them during training', 'create a FeatureFusionBlock with configurable features, batch norm, and alignment options', 'build a LinearSeg model with a pretrained encoder and classification head for semantic segmentation', 'create an encoder from pixio module and load pretrained checkpoint weights for feature extraction', 'freeze all encoder parameters by setting requires_grad to False for linear probing', 'extract and concatenate normalized patch tokens with averaged class tokens from encoder output', 'upsample the segmentation logits to original image size using bilinear interpolation']
```

Usage

```
{'build_scratch_layer': 'build a scratch module with Conv2d layers from input and output channel shapes', 'create_residual_conv_unit': 'create a ResidualConvUnit with configurable features, activation, and batch normalization', 'create_feature_fusion_block': 'create a FeatureFusionBlock that fuses and upsamples multi-scale features with residual connections', 'test_ResidualConvUnit_forward': 'test the ResidualConvUnit forward pass with a sample tensor input', 'test_FeatureFusionBlock_forward': 'test the FeatureFusionBlock forward pass with one or two input feature tensors'}
```

## File: facebookresearch_pixio/evaluation/semseg/models/dpt.py

Prompts

```
['build a scratch module with Conv2d layers from input and output channel shapes', 'create a ResidualConvUnit with configurable features, activation, and batch normalization', 'create a FeatureFusionBlock that fuses and upsamples multi-scale features with residual connections', 'test the ResidualConvUnit forward pass with a sample tensor input', 'test the FeatureFusionBlock forward pass with one or two input feature tensors', 'build a DPTSeg model with a PIXIO encoder and DPT head for semantic segmentation', 'create a DPTHead module with project layers, resize layers, and feature fusion blocks', 'run the DPTSeg forward pass to extract features and produce segmentation output', 'lock the DPTSeg encoder parameters to freeze them during training', 'create a FeatureFusionBlock with configurable features, batch norm, and alignment options', 'build a LinearSeg model with a pretrained encoder and classification head for semantic segmentation', 'create an encoder from pixio module and load pretrained checkpoint weights for feature extraction', 'freeze all encoder parameters by setting requires_grad to False for linear probing', 'extract and concatenate normalized patch tokens with averaged class tokens from encoder output', 'upsample the segmentation logits to original image size using bilinear interpolation']
```

Usage

```
{'build_DPTSeg_model': 'build a DPTSeg model with a PIXIO encoder and DPT head for semantic segmentation', 'create_DPTHead': 'create a DPTHead module with project layers, resize layers, and feature fusion blocks', 'run_DPTSeg_forward': 'run the DPTSeg forward pass to extract features and produce segmentation output', 'lock_DPTSeg_encoder': 'lock the DPTSeg encoder parameters to freeze them during training', 'create_fusion_block': 'create a FeatureFusionBlock with configurable features, batch norm, and alignment options'}
```

## File: facebookresearch_pixio/evaluation/semseg/models/linear.py

Prompts

```
['build a scratch module with Conv2d layers from input and output channel shapes', 'create a ResidualConvUnit with configurable features, activation, and batch normalization', 'create a FeatureFusionBlock that fuses and upsamples multi-scale features with residual connections', 'test the ResidualConvUnit forward pass with a sample tensor input', 'test the FeatureFusionBlock forward pass with one or two input feature tensors', 'build a DPTSeg model with a PIXIO encoder and DPT head for semantic segmentation', 'create a DPTHead module with project layers, resize layers, and feature fusion blocks', 'run the DPTSeg forward pass to extract features and produce segmentation output', 'lock the DPTSeg encoder parameters to freeze them during training', 'create a FeatureFusionBlock with configurable features, batch norm, and alignment options', 'build a LinearSeg model with a pretrained encoder and classification head for semantic segmentation', 'create an encoder from pixio module and load pretrained checkpoint weights for feature extraction', 'freeze all encoder parameters by setting requires_grad to False for linear probing', 'extract and concatenate normalized patch tokens with averaged class tokens from encoder output', 'upsample the segmentation logits to original image size using bilinear interpolation']
```

Usage

```
{'build_linear_segmentation_model': 'build a LinearSeg model with a pretrained encoder and classification head for semantic segmentation', 'create_encoder_with_pretrained_weights': 'create an encoder from pixio module and load pretrained checkpoint weights for feature extraction', 'freeze_encoder_parameters': 'freeze all encoder parameters by setting requires_grad to False for linear probing', 'extract_patch_and_cls_features': 'extract and concatenate normalized patch tokens with averaged class tokens from encoder output', 'upsample_segmentation_output': 'upsample the segmentation logits to original image size using bilinear interpolation'}
```

