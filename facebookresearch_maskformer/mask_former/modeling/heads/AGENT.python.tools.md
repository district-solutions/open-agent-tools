# Agent Python Tools

- repo: facebookresearch/maskformer
- repo_uri: https://github.com/facebookresearch/maskformer

## File: facebookresearch_maskformer/mask_former/modeling/heads/mask_former_head.py

Prompts

```
['build a MaskFormerHead module for semantic segmentation using a pixel decoder and transformer predictor', 'create a MaskFormerHead instance from a detectron2 config with pixel decoder and transformer predictor', 'run the MaskFormerHead forward pass on image features to produce mask predictions', 'review the MaskFormerHead layers method that routes features through the pixel decoder and predictor', 'refactor the MaskFormerHead _load_from_state_dict to handle weight format migration for older checkpoints', 'build a PerPixelBaselineHead semantic segmentation head with a pixel decoder and 1x1 conv predictor', 'build a PerPixelBaselinePlusHead semantic segmentation head with a transformer predictor and deep supervision', 'run forward pass on PerPixelBaselineHead to get segmentation logits or training losses', 'run forward pass on PerPixelBaselinePlusHead with optional deep supervision auxiliary outputs', 'review the PerPixelBaselineHead losses method for cross entropy computation with bilinear interpolation', 'build a pixel decoder from config using build_pixel_decoder with cfg and input_shape', 'create a BasePixelDecoder instance with input_shape, conv_dim, mask_dim, and norm parameters', 'run forward_features on BasePixelDecoder to extract mask features from input feature maps', 'create a TransformerEncoderPixelDecoder with transformer config including dropout, nheads, and enc_layers', 'run forward_features on TransformerEncoderPixelDecoder to get mask features and transformer encoder features']
```

Usage

```
{'build_maskformer_head': 'build a MaskFormerHead module for semantic segmentation using a pixel decoder and transformer predictor', 'create_maskformer_head_from_config': 'create a MaskFormerHead instance from a detectron2 config with pixel decoder and transformer predictor', 'run_maskformer_forward': 'run the MaskFormerHead forward pass on image features to produce mask predictions', 'review_maskformer_head_layers': 'review the MaskFormerHead layers method that routes features through the pixel decoder and predictor', 'refactor_maskformer_state_dict_loading': 'refactor the MaskFormerHead _load_from_state_dict to handle weight format migration for older checkpoints'}
```

## File: facebookresearch_maskformer/mask_former/modeling/heads/per_pixel_baseline.py

Prompts

```
['build a MaskFormerHead module for semantic segmentation using a pixel decoder and transformer predictor', 'create a MaskFormerHead instance from a detectron2 config with pixel decoder and transformer predictor', 'run the MaskFormerHead forward pass on image features to produce mask predictions', 'review the MaskFormerHead layers method that routes features through the pixel decoder and predictor', 'refactor the MaskFormerHead _load_from_state_dict to handle weight format migration for older checkpoints', 'build a PerPixelBaselineHead semantic segmentation head with a pixel decoder and 1x1 conv predictor', 'build a PerPixelBaselinePlusHead semantic segmentation head with a transformer predictor and deep supervision', 'run forward pass on PerPixelBaselineHead to get segmentation logits or training losses', 'run forward pass on PerPixelBaselinePlusHead with optional deep supervision auxiliary outputs', 'review the PerPixelBaselineHead losses method for cross entropy computation with bilinear interpolation', 'build a pixel decoder from config using build_pixel_decoder with cfg and input_shape', 'create a BasePixelDecoder instance with input_shape, conv_dim, mask_dim, and norm parameters', 'run forward_features on BasePixelDecoder to extract mask features from input feature maps', 'create a TransformerEncoderPixelDecoder with transformer config including dropout, nheads, and enc_layers', 'run forward_features on TransformerEncoderPixelDecoder to get mask features and transformer encoder features']
```

Usage

```
{'build_PerPixelBaselineHead': 'build a PerPixelBaselineHead semantic segmentation head with a pixel decoder and 1x1 conv predictor', 'build_PerPixelBaselinePlusHead': 'build a PerPixelBaselinePlusHead semantic segmentation head with a transformer predictor and deep supervision', 'forward_PerPixelBaselineHead': 'run forward pass on PerPixelBaselineHead to get segmentation logits or training losses', 'forward_PerPixelBaselinePlusHead': 'run forward pass on PerPixelBaselinePlusHead with optional deep supervision auxiliary outputs', 'review_PerPixelBaselineHead_losses': 'review the PerPixelBaselineHead losses method for cross entropy computation with bilinear interpolation'}
```

## File: facebookresearch_maskformer/mask_former/modeling/heads/pixel_decoder.py

Prompts

```
['build a MaskFormerHead module for semantic segmentation using a pixel decoder and transformer predictor', 'create a MaskFormerHead instance from a detectron2 config with pixel decoder and transformer predictor', 'run the MaskFormerHead forward pass on image features to produce mask predictions', 'review the MaskFormerHead layers method that routes features through the pixel decoder and predictor', 'refactor the MaskFormerHead _load_from_state_dict to handle weight format migration for older checkpoints', 'build a PerPixelBaselineHead semantic segmentation head with a pixel decoder and 1x1 conv predictor', 'build a PerPixelBaselinePlusHead semantic segmentation head with a transformer predictor and deep supervision', 'run forward pass on PerPixelBaselineHead to get segmentation logits or training losses', 'run forward pass on PerPixelBaselinePlusHead with optional deep supervision auxiliary outputs', 'review the PerPixelBaselineHead losses method for cross entropy computation with bilinear interpolation', 'build a pixel decoder from config using build_pixel_decoder with cfg and input_shape', 'create a BasePixelDecoder instance with input_shape, conv_dim, mask_dim, and norm parameters', 'run forward_features on BasePixelDecoder to extract mask features from input feature maps', 'create a TransformerEncoderPixelDecoder with transformer config including dropout, nheads, and enc_layers', 'run forward_features on TransformerEncoderPixelDecoder to get mask features and transformer encoder features']
```

Usage

```
{'build_pixel_decoder': 'build a pixel decoder from config using build_pixel_decoder with cfg and input_shape', 'create_base_pixel_decoder': 'create a BasePixelDecoder instance with input_shape, conv_dim, mask_dim, and norm parameters', 'forward_features_base': 'run forward_features on BasePixelDecoder to extract mask features from input feature maps', 'create_transformer_encoder_pixel_decoder': 'create a TransformerEncoderPixelDecoder with transformer config including dropout, nheads, and enc_layers', 'forward_features_transformer': 'run forward_features on TransformerEncoderPixelDecoder to get mask features and transformer encoder features'}
```

