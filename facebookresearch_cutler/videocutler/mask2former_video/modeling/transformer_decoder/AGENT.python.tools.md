# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/mask2former_video/modeling/transformer_decoder/position_encoding.py

Prompts

```
['build a PositionEmbeddingSine3D module to generate sinusoidal 3D positional encodings for video transformer models', 'create a sine-based positional embedding for 5D video tensors with batch, time, channel, height, width dimensions', 'test the PositionEmbeddingSine3D forward pass with a 5D tensor and optional boolean mask input', 'review the PositionEmbeddingSine3D constructor to understand num_pos_feats, temperature, normalize, and scale parameters', 'refactor the PositionEmbeddingSine3D normalization logic to support custom scaling for z, y, x embeddings', 'build a VideoMultiScaleMaskedTransformerDecoder with configurable hidden dim, num queries, and decoder layers for video maskFormer', 'create a SelfAttentionLayer module with multihead attention, layer norm, and optional pre-norm for transformer decoder', 'create a CrossAttentionLayer module that attends between query tokens and memory features with positional embeddings', 'create a FFNLayer feedforward network with two linear layers, dropout, and layer normalization for transformer blocks', 'review the VideoMultiScaleMaskedTransformerDecoder forward pass that processes multi-scale features and produces class and mask predictions']
```

Usage

```
{'build_3d_positional_encoding': 'build a PositionEmbeddingSine3D module to generate sinusoidal 3D positional encodings for video transformer models', 'create_sine_embedding_for_video': 'create a sine-based positional embedding for 5D video tensors with batch, time, channel, height, width dimensions', 'test_PositionEmbeddingSine3D_forward': 'test the PositionEmbeddingSine3D forward pass with a 5D tensor and optional boolean mask input', 'review_PositionEmbeddingSine3D_init': 'review the PositionEmbeddingSine3D constructor to understand num_pos_feats, temperature, normalize, and scale parameters', 'refactor_PositionEmbeddingSine3D_normalization': 'refactor the PositionEmbeddingSine3D normalization logic to support custom scaling for z, y, x embeddings'}
```

## File: facebookresearch_cutler/videocutler/mask2former_video/modeling/transformer_decoder/video_mask2former_transformer_decoder.py

Prompts

```
['build a PositionEmbeddingSine3D module to generate sinusoidal 3D positional encodings for video transformer models', 'create a sine-based positional embedding for 5D video tensors with batch, time, channel, height, width dimensions', 'test the PositionEmbeddingSine3D forward pass with a 5D tensor and optional boolean mask input', 'review the PositionEmbeddingSine3D constructor to understand num_pos_feats, temperature, normalize, and scale parameters', 'refactor the PositionEmbeddingSine3D normalization logic to support custom scaling for z, y, x embeddings', 'build a VideoMultiScaleMaskedTransformerDecoder with configurable hidden dim, num queries, and decoder layers for video maskFormer', 'create a SelfAttentionLayer module with multihead attention, layer norm, and optional pre-norm for transformer decoder', 'create a CrossAttentionLayer module that attends between query tokens and memory features with positional embeddings', 'create a FFNLayer feedforward network with two linear layers, dropout, and layer normalization for transformer blocks', 'review the VideoMultiScaleMaskedTransformerDecoder forward pass that processes multi-scale features and produces class and mask predictions']
```

Usage

```
{'build_VideoMultiScaleMaskedTransformerDecoder': 'build a VideoMultiScaleMaskedTransformerDecoder with configurable hidden dim, num queries, and decoder layers for video maskFormer', 'create_SelfAttentionLayer': 'create a SelfAttentionLayer module with multihead attention, layer norm, and optional pre-norm for transformer decoder', 'create_CrossAttentionLayer': 'create a CrossAttentionLayer module that attends between query tokens and memory features with positional embeddings', 'create_FFNLayer': 'create a FFNLayer feedforward network with two linear layers, dropout, and layer normalization for transformer blocks', 'review_VideoMultiScaleMaskedTransformerDecoder_forward': 'review the VideoMultiScaleMaskedTransformerDecoder forward pass that processes multi-scale features and produces class and mask predictions'}
```

