# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/mask2former/modeling/transformer_decoder/mask2former_transformer_decoder.py

Prompts

```
['build a MultiScaleMaskedTransformerDecoder with configurable hidden dim, num queries, and decoder layers for mask classification', 'create a SelfAttentionLayer with multihead attention, layer norm, and optional pre or post normalization', 'create a CrossAttentionLayer that attends between query targets and memory features with positional embeddings', 'create a FFNLayer with two linear layers, dropout, and layer normalization for transformer feedforward processing', 'run forward_prediction_heads to produce class logits, mask embeddings, and attention masks from decoder output', 'build a transformer decoder from config using build_transformer_decoder with cfg and in_channels', 'create a StandardTransformerDecoder instance with num_queries, hidden_dim, nheads, and enc_layers parameters', 'run the StandardTransformerDecoder forward pass with x features, mask_features, and optional mask tensor', 'create an MLP multi-layer perceptron module with input_dim, hidden_dim, output_dim, and num_layers', 'review the StandardTransformerDecoder forward method for mask classification and deep supervision output logic', 'build a PositionEmbeddingSine module with custom num_pos_feats and temperature for transformer image encoding', 'create a PositionEmbeddingSine module with normalize enabled and a custom scale for normalized positional embeddings', 'run the forward pass of PositionEmbeddingSine on a feature tensor to generate sinusoidal positional encodings', 'test the PositionEmbeddingSine forward method with a boolean mask to handle padded image regions', 'review the PositionEmbeddingSine class __repr__ output to inspect num_pos_feats, temperature, normalize, and scale settings', 'build a Transformer module with encoder and decoder layers for vision transformer models', 'create a TransformerEncoder that stacks multiple encoder layers with optional layer normalization', 'create a TransformerDecoder that returns intermediate outputs from all decoding layers', 'review the TransformerEncoderLayer forward pass with pre and post normalization options', 'review the TransformerDecoderLayer forward pass with self attention and cross attention']
```

Usage

```
{'build_MultiScaleMaskedTransformerDecoder': 'build a MultiScaleMaskedTransformerDecoder with configurable hidden dim, num queries, and decoder layers for mask classification', 'create_SelfAttentionLayer': 'create a SelfAttentionLayer with multihead attention, layer norm, and optional pre or post normalization', 'create_CrossAttentionLayer': 'create a CrossAttentionLayer that attends between query targets and memory features with positional embeddings', 'create_FFNLayer': 'create a FFNLayer with two linear layers, dropout, and layer normalization for transformer feedforward processing', 'run_forward_prediction_heads': 'run forward_prediction_heads to produce class logits, mask embeddings, and attention masks from decoder output'}
```

## File: facebookresearch_cutler/videocutler/mask2former/modeling/transformer_decoder/maskformer_transformer_decoder.py

Prompts

```
['build a MultiScaleMaskedTransformerDecoder with configurable hidden dim, num queries, and decoder layers for mask classification', 'create a SelfAttentionLayer with multihead attention, layer norm, and optional pre or post normalization', 'create a CrossAttentionLayer that attends between query targets and memory features with positional embeddings', 'create a FFNLayer with two linear layers, dropout, and layer normalization for transformer feedforward processing', 'run forward_prediction_heads to produce class logits, mask embeddings, and attention masks from decoder output', 'build a transformer decoder from config using build_transformer_decoder with cfg and in_channels', 'create a StandardTransformerDecoder instance with num_queries, hidden_dim, nheads, and enc_layers parameters', 'run the StandardTransformerDecoder forward pass with x features, mask_features, and optional mask tensor', 'create an MLP multi-layer perceptron module with input_dim, hidden_dim, output_dim, and num_layers', 'review the StandardTransformerDecoder forward method for mask classification and deep supervision output logic', 'build a PositionEmbeddingSine module with custom num_pos_feats and temperature for transformer image encoding', 'create a PositionEmbeddingSine module with normalize enabled and a custom scale for normalized positional embeddings', 'run the forward pass of PositionEmbeddingSine on a feature tensor to generate sinusoidal positional encodings', 'test the PositionEmbeddingSine forward method with a boolean mask to handle padded image regions', 'review the PositionEmbeddingSine class __repr__ output to inspect num_pos_feats, temperature, normalize, and scale settings', 'build a Transformer module with encoder and decoder layers for vision transformer models', 'create a TransformerEncoder that stacks multiple encoder layers with optional layer normalization', 'create a TransformerDecoder that returns intermediate outputs from all decoding layers', 'review the TransformerEncoderLayer forward pass with pre and post normalization options', 'review the TransformerDecoderLayer forward pass with self attention and cross attention']
```

Usage

```
{'build_transformer_decoder': 'build a transformer decoder from config using build_transformer_decoder with cfg and in_channels', 'create_standard_transformer_decoder': 'create a StandardTransformerDecoder instance with num_queries, hidden_dim, nheads, and enc_layers parameters', 'run_forward_decoder': 'run the StandardTransformerDecoder forward pass with x features, mask_features, and optional mask tensor', 'create_mlp_module': 'create an MLP multi-layer perceptron module with input_dim, hidden_dim, output_dim, and num_layers', 'review_standard_transformer_decoder_forward': 'review the StandardTransformerDecoder forward method for mask classification and deep supervision output logic'}
```

## File: facebookresearch_cutler/videocutler/mask2former/modeling/transformer_decoder/position_encoding.py

Prompts

```
['build a MultiScaleMaskedTransformerDecoder with configurable hidden dim, num queries, and decoder layers for mask classification', 'create a SelfAttentionLayer with multihead attention, layer norm, and optional pre or post normalization', 'create a CrossAttentionLayer that attends between query targets and memory features with positional embeddings', 'create a FFNLayer with two linear layers, dropout, and layer normalization for transformer feedforward processing', 'run forward_prediction_heads to produce class logits, mask embeddings, and attention masks from decoder output', 'build a transformer decoder from config using build_transformer_decoder with cfg and in_channels', 'create a StandardTransformerDecoder instance with num_queries, hidden_dim, nheads, and enc_layers parameters', 'run the StandardTransformerDecoder forward pass with x features, mask_features, and optional mask tensor', 'create an MLP multi-layer perceptron module with input_dim, hidden_dim, output_dim, and num_layers', 'review the StandardTransformerDecoder forward method for mask classification and deep supervision output logic', 'build a PositionEmbeddingSine module with custom num_pos_feats and temperature for transformer image encoding', 'create a PositionEmbeddingSine module with normalize enabled and a custom scale for normalized positional embeddings', 'run the forward pass of PositionEmbeddingSine on a feature tensor to generate sinusoidal positional encodings', 'test the PositionEmbeddingSine forward method with a boolean mask to handle padded image regions', 'review the PositionEmbeddingSine class __repr__ output to inspect num_pos_feats, temperature, normalize, and scale settings', 'build a Transformer module with encoder and decoder layers for vision transformer models', 'create a TransformerEncoder that stacks multiple encoder layers with optional layer normalization', 'create a TransformerDecoder that returns intermediate outputs from all decoding layers', 'review the TransformerEncoderLayer forward pass with pre and post normalization options', 'review the TransformerDecoderLayer forward pass with self attention and cross attention']
```

Usage

```
{'build_sine_positional_encoding': 'build a PositionEmbeddingSine module with custom num_pos_feats and temperature for transformer image encoding', 'create_positional_encoding_with_normalize': 'create a PositionEmbeddingSine module with normalize enabled and a custom scale for normalized positional embeddings', 'run_forward_positional_encoding': 'run the forward pass of PositionEmbeddingSine on a feature tensor to generate sinusoidal positional encodings', 'test_positional_encoding_with_mask': 'test the PositionEmbeddingSine forward method with a boolean mask to handle padded image regions', 'review_positional_encoding_repr': 'review the PositionEmbeddingSine class __repr__ output to inspect num_pos_feats, temperature, normalize, and scale settings'}
```

## File: facebookresearch_cutler/videocutler/mask2former/modeling/transformer_decoder/transformer.py

Prompts

```
['build a MultiScaleMaskedTransformerDecoder with configurable hidden dim, num queries, and decoder layers for mask classification', 'create a SelfAttentionLayer with multihead attention, layer norm, and optional pre or post normalization', 'create a CrossAttentionLayer that attends between query targets and memory features with positional embeddings', 'create a FFNLayer with two linear layers, dropout, and layer normalization for transformer feedforward processing', 'run forward_prediction_heads to produce class logits, mask embeddings, and attention masks from decoder output', 'build a transformer decoder from config using build_transformer_decoder with cfg and in_channels', 'create a StandardTransformerDecoder instance with num_queries, hidden_dim, nheads, and enc_layers parameters', 'run the StandardTransformerDecoder forward pass with x features, mask_features, and optional mask tensor', 'create an MLP multi-layer perceptron module with input_dim, hidden_dim, output_dim, and num_layers', 'review the StandardTransformerDecoder forward method for mask classification and deep supervision output logic', 'build a PositionEmbeddingSine module with custom num_pos_feats and temperature for transformer image encoding', 'create a PositionEmbeddingSine module with normalize enabled and a custom scale for normalized positional embeddings', 'run the forward pass of PositionEmbeddingSine on a feature tensor to generate sinusoidal positional encodings', 'test the PositionEmbeddingSine forward method with a boolean mask to handle padded image regions', 'review the PositionEmbeddingSine class __repr__ output to inspect num_pos_feats, temperature, normalize, and scale settings', 'build a Transformer module with encoder and decoder layers for vision transformer models', 'create a TransformerEncoder that stacks multiple encoder layers with optional layer normalization', 'create a TransformerDecoder that returns intermediate outputs from all decoding layers', 'review the TransformerEncoderLayer forward pass with pre and post normalization options', 'review the TransformerDecoderLayer forward pass with self attention and cross attention']
```

Usage

```
{'build_transformer_encoder_decoder': 'build a Transformer module with encoder and decoder layers for vision transformer models', 'create_transformer_encoder': 'create a TransformerEncoder that stacks multiple encoder layers with optional layer normalization', 'create_transformer_decoder': 'create a TransformerDecoder that returns intermediate outputs from all decoding layers', 'review_encoder_layer_forward': 'review the TransformerEncoderLayer forward pass with pre and post normalization options', 'review_decoder_layer_forward': 'review the TransformerDecoderLayer forward pass with self attention and cross attention'}
```

