# Agent Python Tools

- repo: facebookresearch/maskformer
- repo_uri: https://github.com/facebookresearch/maskformer

## File: facebookresearch_maskformer/mask_former/modeling/transformer/position_encoding.py

Prompts

```
['create a PositionEmbeddingSine module with default 64 positional features for transformer image encoding', 'create a PositionEmbeddingSine module with normalize enabled and a custom scale for positional encoding', 'run the forward pass of PositionEmbeddingSine on a batch of image feature tensors', 'run the forward pass of PositionEmbeddingSine on feature tensors with a boolean padding mask', 'review the PositionEmbeddingSine constructor to understand num_pos_feats, temperature, normalize, and scale parameters', 'build a Transformer encoder-decoder model with configurable d_model, nhead, and layer count', 'create a TransformerEncoder that stacks cloned encoder layers with optional layer normalization', 'create a TransformerDecoder that returns intermediate outputs from all decoding layers', 'run the Transformer forward pass with source, mask, query embed, and positional embed', 'review the TransformerEncoderLayer self-attention and feedforward sub-layers with pre/post normalization', 'build a TransformerPredictor module for maskFormer semantic segmentation with configurable transformer encoder and decoder layers', 'create a simple multi-layer perceptron FFN with configurable input, hidden, output dimensions and layer count', 'review the TransformerPredictor from_config class method that reads detectron2 config to initialize transformer parameters', 'test the _set_aux_loss method that prepares auxiliary loss outputs for deep supervision training']
```

Usage

```
{'create_position_embedding_sine': 'create a PositionEmbeddingSine module with default 64 positional features for transformer image encoding', 'create_position_embedding_sine_normalized': 'create a PositionEmbeddingSine module with normalize enabled and a custom scale for positional encoding', 'run_position_embedding_forward': 'run the forward pass of PositionEmbeddingSine on a batch of image feature tensors', 'run_position_embedding_forward_with_mask': 'run the forward pass of PositionEmbeddingSine on feature tensors with a boolean padding mask', 'review_position_embedding_sine_init': 'review the PositionEmbeddingSine constructor to understand num_pos_feats, temperature, normalize, and scale parameters'}
```

## File: facebookresearch_maskformer/mask_former/modeling/transformer/transformer.py

Prompts

```
['create a PositionEmbeddingSine module with default 64 positional features for transformer image encoding', 'create a PositionEmbeddingSine module with normalize enabled and a custom scale for positional encoding', 'run the forward pass of PositionEmbeddingSine on a batch of image feature tensors', 'run the forward pass of PositionEmbeddingSine on feature tensors with a boolean padding mask', 'review the PositionEmbeddingSine constructor to understand num_pos_feats, temperature, normalize, and scale parameters', 'build a Transformer encoder-decoder model with configurable d_model, nhead, and layer count', 'create a TransformerEncoder that stacks cloned encoder layers with optional layer normalization', 'create a TransformerDecoder that returns intermediate outputs from all decoding layers', 'run the Transformer forward pass with source, mask, query embed, and positional embed', 'review the TransformerEncoderLayer self-attention and feedforward sub-layers with pre/post normalization', 'build a TransformerPredictor module for maskFormer semantic segmentation with configurable transformer encoder and decoder layers', 'create a simple multi-layer perceptron FFN with configurable input, hidden, output dimensions and layer count', 'review the TransformerPredictor from_config class method that reads detectron2 config to initialize transformer parameters', 'test the _set_aux_loss method that prepares auxiliary loss outputs for deep supervision training']
```

Usage

```
{'build_transformer_model': 'build a Transformer encoder-decoder model with configurable d_model, nhead, and layer count', 'create_transformer_encoder': 'create a TransformerEncoder that stacks cloned encoder layers with optional layer normalization', 'create_transformer_decoder': 'create a TransformerDecoder that returns intermediate outputs from all decoding layers', 'run_transformer_forward': 'run the Transformer forward pass with source, mask, query embed, and positional embed', 'review_transformer_encoder_layer': 'review the TransformerEncoderLayer self-attention and feedforward sub-layers with pre/post normalization'}
```

## File: facebookresearch_maskformer/mask_former/modeling/transformer/transformer_predictor.py

Prompts

```
['create a PositionEmbeddingSine module with default 64 positional features for transformer image encoding', 'create a PositionEmbeddingSine module with normalize enabled and a custom scale for positional encoding', 'run the forward pass of PositionEmbeddingSine on a batch of image feature tensors', 'run the forward pass of PositionEmbeddingSine on feature tensors with a boolean padding mask', 'review the PositionEmbeddingSine constructor to understand num_pos_feats, temperature, normalize, and scale parameters', 'build a Transformer encoder-decoder model with configurable d_model, nhead, and layer count', 'create a TransformerEncoder that stacks cloned encoder layers with optional layer normalization', 'create a TransformerDecoder that returns intermediate outputs from all decoding layers', 'run the Transformer forward pass with source, mask, query embed, and positional embed', 'review the TransformerEncoderLayer self-attention and feedforward sub-layers with pre/post normalization', 'build a TransformerPredictor module for maskFormer semantic segmentation with configurable transformer encoder and decoder layers', 'create a simple multi-layer perceptron FFN with configurable input, hidden, output dimensions and layer count', 'review the TransformerPredictor from_config class method that reads detectron2 config to initialize transformer parameters', 'test the _set_aux_loss method that prepares auxiliary loss outputs for deep supervision training']
```

Usage

```
{'build_transformer_predictor': 'build a TransformerPredictor module for maskFormer semantic segmentation with configurable transformer encoder and decoder layers', 'create_mlp_ffn': 'create a simple multi-layer perceptron FFN with configurable input, hidden, output dimensions and layer count', 'run_transformer_forward': 'run the TransformerPredictor forward pass with input features and mask features to get predicted logits and masks', 'review_from_config': 'review the TransformerPredictor from_config class method that reads detectron2 config to initialize transformer parameters', 'test_set_aux_loss': 'test the _set_aux_loss method that prepares auxiliary loss outputs for deep supervision training'}
```

