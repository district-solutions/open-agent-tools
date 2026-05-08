# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/mask2former/modeling/pixel_decoder/fpn.py

Prompts

```
['build a pixel decoder from the config PIXEL_DECODER_NAME and input shape', 'create a BasePixelDecoder with lateral and output convs for FPN-style feature pyramid decoding', 'create a TransformerEncoderPixelDecoder that adds a transformer encoder on the lowest-resolution feature map', 'run forward_features on a BasePixelDecoder to get mask features and multi-scale features', 'run forward_features on a TransformerEncoderPixelDecoder to get mask features, transformer encoder features, and multi-scale features', 'build a multi-scale deformable attention transformer encoder with configurable model dimension, heads, and encoder layers', 'create a single transformer encoder layer with deformable self-attention and feed-forward network', 'run the stacked transformer encoder layers to encode multi-scale feature maps with reference points', 'build a pixel decoder with deformable transformer encoder and FPN for semantic segmentation feature extraction', 'review the forward_features method that processes multi-scale features through the transformer and FPN adapter layers']
```

Usage

```
{'build_pixel_decoder': 'build a pixel decoder from the config PIXEL_DECODER_NAME and input shape', 'create_base_pixel_decoder': 'create a BasePixelDecoder with lateral and output convs for FPN-style feature pyramid decoding', 'create_transformer_encoder_pixel_decoder': 'create a TransformerEncoderPixelDecoder that adds a transformer encoder on the lowest-resolution feature map', 'run_forward_features_base': 'run forward_features on a BasePixelDecoder to get mask features and multi-scale features', 'run_forward_features_transformer': 'run forward_features on a TransformerEncoderPixelDecoder to get mask features, transformer encoder features, and multi-scale features'}
```

## File: facebookresearch_cutler/videocutler/mask2former/modeling/pixel_decoder/msdeformattn.py

Prompts

```
['build a pixel decoder from the config PIXEL_DECODER_NAME and input shape', 'create a BasePixelDecoder with lateral and output convs for FPN-style feature pyramid decoding', 'create a TransformerEncoderPixelDecoder that adds a transformer encoder on the lowest-resolution feature map', 'run forward_features on a BasePixelDecoder to get mask features and multi-scale features', 'run forward_features on a TransformerEncoderPixelDecoder to get mask features, transformer encoder features, and multi-scale features', 'build a multi-scale deformable attention transformer encoder with configurable model dimension, heads, and encoder layers', 'create a single transformer encoder layer with deformable self-attention and feed-forward network', 'run the stacked transformer encoder layers to encode multi-scale feature maps with reference points', 'build a pixel decoder with deformable transformer encoder and FPN for semantic segmentation feature extraction', 'review the forward_features method that processes multi-scale features through the transformer and FPN adapter layers']
```

Usage

```
{'build_MSDeformAttnTransformerEncoderOnly': 'build a multi-scale deformable attention transformer encoder with configurable model dimension, heads, and encoder layers', 'create_MSDeformAttnTransformerEncoderLayer': 'create a single transformer encoder layer with deformable self-attention and feed-forward network', 'run_MSDeformAttnTransformerEncoder': 'run the stacked transformer encoder layers to encode multi-scale feature maps with reference points', 'build_MSDeformAttnPixelDecoder': 'build a pixel decoder with deformable transformer encoder and FPN for semantic segmentation feature extraction', 'review_MSDeformAttnPixelDecoder_forward_features': 'review the forward_features method that processes multi-scale features through the transformer and FPN adapter layers'}
```

