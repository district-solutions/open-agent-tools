# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/mask2former/modeling/pixel_decoder/fpn.py

Prompts

```
['build a pixel decoder from config using build_pixel_decoder with cfg and input_shape', 'create a BasePixelDecoder instance with input_shape, conv_dim, mask_dim, and norm parameters', 'create a TransformerEncoderPixelDecoder with transformer config and FPN conv parameters for mask features', 'run forward_features on BasePixelDecoder to get mask features and multi-scale feature maps', 'run forward_features on TransformerEncoderPixelDecoder to get mask features, transformer encoder features, and multi-scale features', 'build a multi-scale deformable attention transformer encoder with configurable model dimension, heads, and encoder layers', 'create a single transformer encoder layer with deformable self-attention and feed-forward network for feature processing', 'build a stacked transformer encoder that computes reference points and applies multiple encoder layers sequentially', 'create a pixel decoder with deformable transformer encoder and FPN adapter for semantic segmentation feature extraction', 'review the forward_features method that processes multi-scale features through the transformer encoder and FPN levels']
```

Usage

```
{'build_pixel_decoder': 'build a pixel decoder from config using build_pixel_decoder with cfg and input_shape', 'create_base_pixel_decoder': 'create a BasePixelDecoder instance with input_shape, conv_dim, mask_dim, and norm parameters', 'create_transformer_encoder_pixel_decoder': 'create a TransformerEncoderPixelDecoder with transformer config and FPN conv parameters for mask features', 'forward_features_base_pixel_decoder': 'run forward_features on BasePixelDecoder to get mask features and multi-scale feature maps', 'forward_features_transformer_encoder_pixel_decoder': 'run forward_features on TransformerEncoderPixelDecoder to get mask features, transformer encoder features, and multi-scale features'}
```

## File: facebookresearch_mask2former/mask2former/modeling/pixel_decoder/msdeformattn.py

Prompts

```
['build a pixel decoder from config using build_pixel_decoder with cfg and input_shape', 'create a BasePixelDecoder instance with input_shape, conv_dim, mask_dim, and norm parameters', 'create a TransformerEncoderPixelDecoder with transformer config and FPN conv parameters for mask features', 'run forward_features on BasePixelDecoder to get mask features and multi-scale feature maps', 'run forward_features on TransformerEncoderPixelDecoder to get mask features, transformer encoder features, and multi-scale features', 'build a multi-scale deformable attention transformer encoder with configurable model dimension, heads, and encoder layers', 'create a single transformer encoder layer with deformable self-attention and feed-forward network for feature processing', 'build a stacked transformer encoder that computes reference points and applies multiple encoder layers sequentially', 'create a pixel decoder with deformable transformer encoder and FPN adapter for semantic segmentation feature extraction', 'review the forward_features method that processes multi-scale features through the transformer encoder and FPN levels']
```

Usage

```
{'build_MSDeformAttnTransformerEncoderOnly': 'build a multi-scale deformable attention transformer encoder with configurable model dimension, heads, and encoder layers', 'create_MSDeformAttnTransformerEncoderLayer': 'create a single transformer encoder layer with deformable self-attention and feed-forward network for feature processing', 'build_MSDeformAttnTransformerEncoder': 'build a stacked transformer encoder that computes reference points and applies multiple encoder layers sequentially', 'create_MSDeformAttnPixelDecoder': 'create a pixel decoder with deformable transformer encoder and FPN adapter for semantic segmentation feature extraction', 'review_MSDeformAttnPixelDecoder_forward_features': 'review the forward_features method that processes multi-scale features through the transformer encoder and FPN levels'}
```

