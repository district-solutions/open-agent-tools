# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/mask2former_video/modeling/transformer_decoder/position_encoding.py

Prompts

```
['build a PositionEmbeddingSine3D module with custom num_pos_feats, temperature, normalize, and scale parameters', 'run the forward pass of PositionEmbeddingSine3D on a 5D tensor with shape b, t, c, h, w', 'test PositionEmbeddingSine3D forward pass with a boolean mask tensor to exclude positions', 'review the PositionEmbeddingSine3D normalize logic that scales z, y, x embeddings by their last dimension', 'summarize the PositionEmbeddingSine3D class that generates 3D sinusoidal positional encodings for video transformer models', 'build a VideoMultiScaleMaskedTransformerDecoder for video mask transformer decoding with multi-scale features and temporal attention', 'create a SelfAttentionLayer module with multihead self-attention, layer normalization, and optional pre-norm support', 'create a CrossAttentionLayer module with multihead cross-attention between query and memory tensors with positional encoding', 'create a FFNLayer feedforward network with two linear layers, dropout, and layer normalization', 'review the VideoMultiScaleMaskedTransformerDecoder forward pass that processes multi-scale features through self-attention, cross-attention, and FFN layers']
```

Usage

```
{'build_PositionEmbeddingSine3D': 'build a PositionEmbeddingSine3D module with custom num_pos_feats, temperature, normalize, and scale parameters', 'run_PositionEmbeddingSine3D_forward': 'run the forward pass of PositionEmbeddingSine3D on a 5D tensor with shape b, t, c, h, w', 'test_PositionEmbeddingSine3D_mask': 'test PositionEmbeddingSine3D forward pass with a boolean mask tensor to exclude positions', 'review_PositionEmbeddingSine3D_normalize': 'review the PositionEmbeddingSine3D normalize logic that scales z, y, x embeddings by their last dimension', 'summarize_PositionEmbeddingSine3D_sine_encoding': 'summarize the PositionEmbeddingSine3D class that generates 3D sinusoidal positional encodings for video transformer models'}
```

## File: facebookresearch_mask2former/mask2former_video/modeling/transformer_decoder/video_mask2former_transformer_decoder.py

Prompts

```
['build a PositionEmbeddingSine3D module with custom num_pos_feats, temperature, normalize, and scale parameters', 'run the forward pass of PositionEmbeddingSine3D on a 5D tensor with shape b, t, c, h, w', 'test PositionEmbeddingSine3D forward pass with a boolean mask tensor to exclude positions', 'review the PositionEmbeddingSine3D normalize logic that scales z, y, x embeddings by their last dimension', 'summarize the PositionEmbeddingSine3D class that generates 3D sinusoidal positional encodings for video transformer models', 'build a VideoMultiScaleMaskedTransformerDecoder for video mask transformer decoding with multi-scale features and temporal attention', 'create a SelfAttentionLayer module with multihead self-attention, layer normalization, and optional pre-norm support', 'create a CrossAttentionLayer module with multihead cross-attention between query and memory tensors with positional encoding', 'create a FFNLayer feedforward network with two linear layers, dropout, and layer normalization', 'review the VideoMultiScaleMaskedTransformerDecoder forward pass that processes multi-scale features through self-attention, cross-attention, and FFN layers']
```

Usage

```
{'build_VideoMultiScaleMaskedTransformerDecoder': 'build a VideoMultiScaleMaskedTransformerDecoder for video mask transformer decoding with multi-scale features and temporal attention', 'create_SelfAttentionLayer': 'create a SelfAttentionLayer module with multihead self-attention, layer normalization, and optional pre-norm support', 'create_CrossAttentionLayer': 'create a CrossAttentionLayer module with multihead cross-attention between query and memory tensors with positional encoding', 'create_FFNLayer': 'create a FFNLayer feedforward network with two linear layers, dropout, and layer normalization', 'review_VideoMultiScaleMaskedTransformerDecoder_forward': 'review the VideoMultiScaleMaskedTransformerDecoder forward pass that processes multi-scale features through self-attention, cross-attention, and FFN layers'}
```

