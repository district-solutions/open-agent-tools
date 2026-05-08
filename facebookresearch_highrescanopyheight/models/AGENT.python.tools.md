# Agent Python Tools

- repo: facebookresearch/highrescanopyheight
- repo_uri: https://github.com/facebookresearch/highrescanopyheight

## File: facebookresearch_highrescanopyheight/models/backbone.py

Prompts

```
['build a SSLVisionTransformer backbone with configurable out_indices and frozen stages for feature extraction', 'create a DinoVisionTransformer model with patch masking support for self-supervised learning', 'test the PatchEmbed layer to convert 2D images into patch token sequences', 'refactor the Block transformer module to customize attention, MLP ratio, or drop path rate', 'review the MaskingGenerator class for generating random rectangular patch masks for masked autoencoder training', 'build a DPTHead module for dense prediction from ViT backbone features with configurable channels and patch size', 'create a ConvModule that bundles convolution, normalization, and activation layers with configurable ordering', 'build ReassembleBlocks to process ViT cls tokens and rearrange feature vectors into feature maps', 'create a FeatureFusionBlock to merge feature maps from different stages with residual convolution units', 'run HeadDepth to produce a single-channel depth prediction or binned classification output from feature maps', 'build a PyTorch RNet regression model with configurable channels, classes, and filter sizes', 'create a forward pass through the RNet model with an input tensor', 'test instantiating the RNet class with custom n_channels, n_classes, and n_pix parameters', 'refactor the RNet conv_block inner function to add dropout or different activation', 'review the RNet class architecture with 5 conv blocks and 4 fully connected layers']
```

Usage

```
{'build_SSLVisionTransformer_backbone': 'build a SSLVisionTransformer backbone with configurable out_indices and frozen stages for feature extraction', 'create_DinoVisionTransformer_model': 'create a DinoVisionTransformer model with patch masking support for self-supervised learning', 'test_PatchEmbed_layer': 'test the PatchEmbed layer to convert 2D images into patch token sequences', 'refactor_Block_transformer': 'refactor the Block transformer module to customize attention, MLP ratio, or drop path rate', 'review_MaskingGenerator_class': 'review the MaskingGenerator class for generating random rectangular patch masks for masked autoencoder training'}
```

## File: facebookresearch_highrescanopyheight/models/dpt_head.py

Prompts

```
['build a SSLVisionTransformer backbone with configurable out_indices and frozen stages for feature extraction', 'create a DinoVisionTransformer model with patch masking support for self-supervised learning', 'test the PatchEmbed layer to convert 2D images into patch token sequences', 'refactor the Block transformer module to customize attention, MLP ratio, or drop path rate', 'review the MaskingGenerator class for generating random rectangular patch masks for masked autoencoder training', 'build a DPTHead module for dense prediction from ViT backbone features with configurable channels and patch size', 'create a ConvModule that bundles convolution, normalization, and activation layers with configurable ordering', 'build ReassembleBlocks to process ViT cls tokens and rearrange feature vectors into feature maps', 'create a FeatureFusionBlock to merge feature maps from different stages with residual convolution units', 'run HeadDepth to produce a single-channel depth prediction or binned classification output from feature maps', 'build a PyTorch RNet regression model with configurable channels, classes, and filter sizes', 'create a forward pass through the RNet model with an input tensor', 'test instantiating the RNet class with custom n_channels, n_classes, and n_pix parameters', 'refactor the RNet conv_block inner function to add dropout or different activation', 'review the RNet class architecture with 5 conv blocks and 4 fully connected layers']
```

Usage

```
{'build_DPTHead': 'build a DPTHead module for dense prediction from ViT backbone features with configurable channels and patch size', 'create_ConvModule': 'create a ConvModule that bundles convolution, normalization, and activation layers with configurable ordering', 'build_ReassembleBlocks': 'build ReassembleBlocks to process ViT cls tokens and rearrange feature vectors into feature maps', 'create_FeatureFusionBlock': 'create a FeatureFusionBlock to merge feature maps from different stages with residual convolution units', 'run_HeadDepth': 'run HeadDepth to produce a single-channel depth prediction or binned classification output from feature maps'}
```

## File: facebookresearch_highrescanopyheight/models/regressor.py

Prompts

```
['build a SSLVisionTransformer backbone with configurable out_indices and frozen stages for feature extraction', 'create a DinoVisionTransformer model with patch masking support for self-supervised learning', 'test the PatchEmbed layer to convert 2D images into patch token sequences', 'refactor the Block transformer module to customize attention, MLP ratio, or drop path rate', 'review the MaskingGenerator class for generating random rectangular patch masks for masked autoencoder training', 'build a DPTHead module for dense prediction from ViT backbone features with configurable channels and patch size', 'create a ConvModule that bundles convolution, normalization, and activation layers with configurable ordering', 'build ReassembleBlocks to process ViT cls tokens and rearrange feature vectors into feature maps', 'create a FeatureFusionBlock to merge feature maps from different stages with residual convolution units', 'run HeadDepth to produce a single-channel depth prediction or binned classification output from feature maps', 'build a PyTorch RNet regression model with configurable channels, classes, and filter sizes', 'create a forward pass through the RNet model with an input tensor', 'test instantiating the RNet class with custom n_channels, n_classes, and n_pix parameters', 'refactor the RNet conv_block inner function to add dropout or different activation', 'review the RNet class architecture with 5 conv blocks and 4 fully connected layers']
```

Usage

```
{'build_RNet_model': 'build a PyTorch RNet regression model with configurable channels, classes, and filter sizes', 'create_RNet_forward_pass': 'create a forward pass through the RNet model with an input tensor', 'test_RNet_instantiation': 'test instantiating the RNet class with custom n_channels, n_classes, and n_pix parameters', 'refactor_RNet_conv_block': 'refactor the RNet conv_block inner function to add dropout or different activation', 'review_RNet_architecture': 'review the RNet class architecture with 5 conv blocks and 4 fully connected layers'}
```

