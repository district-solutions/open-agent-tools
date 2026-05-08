# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/mask2former/modeling/transformer_decoder/mask2former_transformer_decoder.py

Prompts

```
['build a MultiScaleMaskedTransformerDecoder with configurable hidden dim, num queries, and decoder layers for mask classification', 'create a SelfAttentionLayer module with multihead attention, layer norm, and optional pre or post normalization', 'create a CrossAttentionLayer module that applies multihead cross attention between target queries and memory features', 'create a FFNLayer feedforward network with two linear layers, dropout, and layer normalization', 'review the forward pass of MultiScaleMaskedTransformerDecoder that processes multi-scale features through self attention, cross attention, and FFN layers', 'build a transformer decoder from config using build_transformer_decoder with cfg and in_channels', 'create a StandardTransformerDecoder instance with num_queries, hidden_dim, nheads, and enc_layers parameters', 'run a forward pass on the StandardTransformerDecoder with x, mask_features, and optional mask inputs', 'create an MLP multi-layer perceptron module with input_dim, hidden_dim, output_dim, and num_layers', 'review the _set_aux_loss method to understand how intermediate decoder outputs are structured for loss computation', 'create a PositionEmbeddingSine module with 64 positional features for transformer image encoding', 'build a PositionEmbeddingSine module with normalize enabled and a custom scale value', 'run forward pass on a tensor through PositionEmbeddingSine to get sinusoidal positional embeddings', 'run forward pass on a tensor with a boolean mask to skip masked positions in encoding', 'review the PositionEmbeddingSine class repr output showing num_pos_feats, temperature, normalize, and scale', 'build a Transformer model with configurable encoder and decoder layers for mask2former segmentation', 'create a TransformerEncoder with cloned encoder layers and optional layer normalization', 'create a TransformerDecoder with cloned decoder layers and intermediate output support', 'review the TransformerEncoderLayer self-attention and feedforward operations with pre/post normalization options', 'review the TransformerDecoderLayer self-attention cross-attention and feedforward operations with normalization options']
```

Usage

```
{'build_MultiScaleMaskedTransformerDecoder': 'build a MultiScaleMaskedTransformerDecoder with configurable hidden dim, num queries, and decoder layers for mask classification', 'create_SelfAttentionLayer': 'create a SelfAttentionLayer module with multihead attention, layer norm, and optional pre or post normalization', 'create_CrossAttentionLayer': 'create a CrossAttentionLayer module that applies multihead cross attention between target queries and memory features', 'create_FFNLayer': 'create a FFNLayer feedforward network with two linear layers, dropout, and layer normalization', 'review_MultiScaleMaskedTransformerDecoder_forward': 'review the forward pass of MultiScaleMaskedTransformerDecoder that processes multi-scale features through self attention, cross attention, and FFN layers'}
```

## File: facebookresearch_mask2former/mask2former/modeling/transformer_decoder/maskformer_transformer_decoder.py

Prompts

```
['build a MultiScaleMaskedTransformerDecoder with configurable hidden dim, num queries, and decoder layers for mask classification', 'create a SelfAttentionLayer module with multihead attention, layer norm, and optional pre or post normalization', 'create a CrossAttentionLayer module that applies multihead cross attention between target queries and memory features', 'create a FFNLayer feedforward network with two linear layers, dropout, and layer normalization', 'review the forward pass of MultiScaleMaskedTransformerDecoder that processes multi-scale features through self attention, cross attention, and FFN layers', 'build a transformer decoder from config using build_transformer_decoder with cfg and in_channels', 'create a StandardTransformerDecoder instance with num_queries, hidden_dim, nheads, and enc_layers parameters', 'run a forward pass on the StandardTransformerDecoder with x, mask_features, and optional mask inputs', 'create an MLP multi-layer perceptron module with input_dim, hidden_dim, output_dim, and num_layers', 'review the _set_aux_loss method to understand how intermediate decoder outputs are structured for loss computation', 'create a PositionEmbeddingSine module with 64 positional features for transformer image encoding', 'build a PositionEmbeddingSine module with normalize enabled and a custom scale value', 'run forward pass on a tensor through PositionEmbeddingSine to get sinusoidal positional embeddings', 'run forward pass on a tensor with a boolean mask to skip masked positions in encoding', 'review the PositionEmbeddingSine class repr output showing num_pos_feats, temperature, normalize, and scale', 'build a Transformer model with configurable encoder and decoder layers for mask2former segmentation', 'create a TransformerEncoder with cloned encoder layers and optional layer normalization', 'create a TransformerDecoder with cloned decoder layers and intermediate output support', 'review the TransformerEncoderLayer self-attention and feedforward operations with pre/post normalization options', 'review the TransformerDecoderLayer self-attention cross-attention and feedforward operations with normalization options']
```

Usage

```
{'build_transformer_decoder': 'build a transformer decoder from config using build_transformer_decoder with cfg and in_channels', 'create_standard_transformer_decoder': 'create a StandardTransformerDecoder instance with num_queries, hidden_dim, nheads, and enc_layers parameters', 'run_forward_pass': 'run a forward pass on the StandardTransformerDecoder with x, mask_features, and optional mask inputs', 'create_mlp_module': 'create an MLP multi-layer perceptron module with input_dim, hidden_dim, output_dim, and num_layers', 'review_aux_loss': 'review the _set_aux_loss method to understand how intermediate decoder outputs are structured for loss computation'}
```

## File: facebookresearch_mask2former/mask2former/modeling/transformer_decoder/position_encoding.py

Prompts

```
['build a MultiScaleMaskedTransformerDecoder with configurable hidden dim, num queries, and decoder layers for mask classification', 'create a SelfAttentionLayer module with multihead attention, layer norm, and optional pre or post normalization', 'create a CrossAttentionLayer module that applies multihead cross attention between target queries and memory features', 'create a FFNLayer feedforward network with two linear layers, dropout, and layer normalization', 'review the forward pass of MultiScaleMaskedTransformerDecoder that processes multi-scale features through self attention, cross attention, and FFN layers', 'build a transformer decoder from config using build_transformer_decoder with cfg and in_channels', 'create a StandardTransformerDecoder instance with num_queries, hidden_dim, nheads, and enc_layers parameters', 'run a forward pass on the StandardTransformerDecoder with x, mask_features, and optional mask inputs', 'create an MLP multi-layer perceptron module with input_dim, hidden_dim, output_dim, and num_layers', 'review the _set_aux_loss method to understand how intermediate decoder outputs are structured for loss computation', 'create a PositionEmbeddingSine module with 64 positional features for transformer image encoding', 'build a PositionEmbeddingSine module with normalize enabled and a custom scale value', 'run forward pass on a tensor through PositionEmbeddingSine to get sinusoidal positional embeddings', 'run forward pass on a tensor with a boolean mask to skip masked positions in encoding', 'review the PositionEmbeddingSine class repr output showing num_pos_feats, temperature, normalize, and scale', 'build a Transformer model with configurable encoder and decoder layers for mask2former segmentation', 'create a TransformerEncoder with cloned encoder layers and optional layer normalization', 'create a TransformerDecoder with cloned decoder layers and intermediate output support', 'review the TransformerEncoderLayer self-attention and feedforward operations with pre/post normalization options', 'review the TransformerDecoderLayer self-attention cross-attention and feedforward operations with normalization options']
```

Usage

```
{'create_sine_positional_embedding': 'create a PositionEmbeddingSine module with 64 positional features for transformer image encoding', 'build_normalized_positional_encoding': 'build a PositionEmbeddingSine module with normalize enabled and a custom scale value', 'forward_positional_encoding': 'run forward pass on a tensor through PositionEmbeddingSine to get sinusoidal positional embeddings', 'forward_with_mask': 'run forward pass on a tensor with a boolean mask to skip masked positions in encoding', 'review_positional_encoding_repr': 'review the PositionEmbeddingSine class repr output showing num_pos_feats, temperature, normalize, and scale'}
```

## File: facebookresearch_mask2former/mask2former/modeling/transformer_decoder/transformer.py

Prompts

```
['build a MultiScaleMaskedTransformerDecoder with configurable hidden dim, num queries, and decoder layers for mask classification', 'create a SelfAttentionLayer module with multihead attention, layer norm, and optional pre or post normalization', 'create a CrossAttentionLayer module that applies multihead cross attention between target queries and memory features', 'create a FFNLayer feedforward network with two linear layers, dropout, and layer normalization', 'review the forward pass of MultiScaleMaskedTransformerDecoder that processes multi-scale features through self attention, cross attention, and FFN layers', 'build a transformer decoder from config using build_transformer_decoder with cfg and in_channels', 'create a StandardTransformerDecoder instance with num_queries, hidden_dim, nheads, and enc_layers parameters', 'run a forward pass on the StandardTransformerDecoder with x, mask_features, and optional mask inputs', 'create an MLP multi-layer perceptron module with input_dim, hidden_dim, output_dim, and num_layers', 'review the _set_aux_loss method to understand how intermediate decoder outputs are structured for loss computation', 'create a PositionEmbeddingSine module with 64 positional features for transformer image encoding', 'build a PositionEmbeddingSine module with normalize enabled and a custom scale value', 'run forward pass on a tensor through PositionEmbeddingSine to get sinusoidal positional embeddings', 'run forward pass on a tensor with a boolean mask to skip masked positions in encoding', 'review the PositionEmbeddingSine class repr output showing num_pos_feats, temperature, normalize, and scale', 'build a Transformer model with configurable encoder and decoder layers for mask2former segmentation', 'create a TransformerEncoder with cloned encoder layers and optional layer normalization', 'create a TransformerDecoder with cloned decoder layers and intermediate output support', 'review the TransformerEncoderLayer self-attention and feedforward operations with pre/post normalization options', 'review the TransformerDecoderLayer self-attention cross-attention and feedforward operations with normalization options']
```

Usage

```
{'build_Transformer': 'build a Transformer model with configurable encoder and decoder layers for mask2former segmentation', 'create_TransformerEncoder': 'create a TransformerEncoder with cloned encoder layers and optional layer normalization', 'create_TransformerDecoder': 'create a TransformerDecoder with cloned decoder layers and intermediate output support', 'review_TransformerEncoderLayer': 'review the TransformerEncoderLayer self-attention and feedforward operations with pre/post normalization options', 'review_TransformerDecoderLayer': 'review the TransformerDecoderLayer self-attention cross-attention and feedforward operations with normalization options'}
```

