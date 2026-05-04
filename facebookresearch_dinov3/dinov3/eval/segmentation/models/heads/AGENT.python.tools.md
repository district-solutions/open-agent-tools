# Agent Python Tools

- repo: facebookresearch/dinov3
- repo_uri: https://github.com/facebookresearch/dinov3

## File: facebookresearch_dinov3/dinov3/eval/segmentation/models/heads/linear_head.py

Prompts

```
['create a LinearHead with specified input channels and output channels for semantic segmentation', 'build a LinearHead that concatenates CLS tokens with patch tokens for segmentation', 'run a forward pass through the LinearHead to get segmentation feature maps', 'predict a segmentation map by running the LinearHead predict method with rescaling', 'transform and concatenate multi-level image features using bilinear interpolation', 'build a Mask2FormerHead instance with a custom input shape and number of classes for segmentation', 'run the Mask2FormerHead forward pass on a batch of feature tensors to get predictions', 'run the Mask2FormerHead predict method to get interpolated segmentation masks at a target resolution', 'review the Mask2FormerHead pixel decoder configuration using MSDeformAttnPixelDecoder with 16 attention heads', 'review the Mask2FormerHead transformer decoder configuration using MultiScaleMaskedTransformerDecoder with 100 queries', 'build a MultiScaleMaskedTransformerDecoder for mask classification with configurable queries, heads, and decoder layers', 'create a SelfAttentionLayer with multihead attention, layer norm, dropout, and optional pre-normalization', 'create a CrossAttentionLayer that attends between target queries and memory features with positional embeddings', 'create a FFNLayer with two linear layers, dropout, layer norm, and configurable activation function', 'create a Conv2d wrapper that supports optional normalization and activation layers after convolution', 'build a MSDeformAttnPixelDecoder for multi-scale feature decoding in semantic segmentation models', 'create a MSDeformAttnTransformerEncoderOnly with configurable encoder layers and multi-scale feature levels', 'build a Conv2d wrapper module with optional normalization and activation layers', 'test the c2_xavier_fill function to initialize module weights using Caffe2 XavierFill', 'review the MSDeformAttnTransformerEncoderLayer forward pass combining self-attention and feed-forward networks']
```

Usage

```
{'create_linear_head_for_segmentation': 'create a LinearHead with specified input channels and output channels for semantic segmentation', 'build_linear_head_with_cls_token': 'build a LinearHead that concatenates CLS tokens with patch tokens for segmentation', 'run_forward_pass_linear_head': 'run a forward pass through the LinearHead to get segmentation feature maps', 'predict_segmentation_map': 'predict a segmentation map by running the LinearHead predict method with rescaling', 'transform_multi_level_features': 'transform and concatenate multi-level image features using bilinear interpolation'}
```

## File: facebookresearch_dinov3/dinov3/eval/segmentation/models/heads/mask2former_head.py

Prompts

```
['create a LinearHead with specified input channels and output channels for semantic segmentation', 'build a LinearHead that concatenates CLS tokens with patch tokens for segmentation', 'run a forward pass through the LinearHead to get segmentation feature maps', 'predict a segmentation map by running the LinearHead predict method with rescaling', 'transform and concatenate multi-level image features using bilinear interpolation', 'build a Mask2FormerHead instance with a custom input shape and number of classes for segmentation', 'run the Mask2FormerHead forward pass on a batch of feature tensors to get predictions', 'run the Mask2FormerHead predict method to get interpolated segmentation masks at a target resolution', 'review the Mask2FormerHead pixel decoder configuration using MSDeformAttnPixelDecoder with 16 attention heads', 'review the Mask2FormerHead transformer decoder configuration using MultiScaleMaskedTransformerDecoder with 100 queries', 'build a MultiScaleMaskedTransformerDecoder for mask classification with configurable queries, heads, and decoder layers', 'create a SelfAttentionLayer with multihead attention, layer norm, dropout, and optional pre-normalization', 'create a CrossAttentionLayer that attends between target queries and memory features with positional embeddings', 'create a FFNLayer with two linear layers, dropout, layer norm, and configurable activation function', 'create a Conv2d wrapper that supports optional normalization and activation layers after convolution', 'build a MSDeformAttnPixelDecoder for multi-scale feature decoding in semantic segmentation models', 'create a MSDeformAttnTransformerEncoderOnly with configurable encoder layers and multi-scale feature levels', 'build a Conv2d wrapper module with optional normalization and activation layers', 'test the c2_xavier_fill function to initialize module weights using Caffe2 XavierFill', 'review the MSDeformAttnTransformerEncoderLayer forward pass combining self-attention and feed-forward networks']
```

Usage

```
{'build_mask2former_head': 'build a Mask2FormerHead instance with a custom input shape and number of classes for segmentation', 'run_mask2former_forward': 'run the Mask2FormerHead forward pass on a batch of feature tensors to get predictions', 'run_mask2former_predict': 'run the Mask2FormerHead predict method to get interpolated segmentation masks at a target resolution', 'review_mask2former_pixel_decoder': 'review the Mask2FormerHead pixel decoder configuration using MSDeformAttnPixelDecoder with 16 attention heads', 'review_mask2former_transformer_decoder': 'review the Mask2FormerHead transformer decoder configuration using MultiScaleMaskedTransformerDecoder with 100 queries'}
```

## File: facebookresearch_dinov3/dinov3/eval/segmentation/models/heads/mask2former_transformer_decoder.py

Prompts

```
['create a LinearHead with specified input channels and output channels for semantic segmentation', 'build a LinearHead that concatenates CLS tokens with patch tokens for segmentation', 'run a forward pass through the LinearHead to get segmentation feature maps', 'predict a segmentation map by running the LinearHead predict method with rescaling', 'transform and concatenate multi-level image features using bilinear interpolation', 'build a Mask2FormerHead instance with a custom input shape and number of classes for segmentation', 'run the Mask2FormerHead forward pass on a batch of feature tensors to get predictions', 'run the Mask2FormerHead predict method to get interpolated segmentation masks at a target resolution', 'review the Mask2FormerHead pixel decoder configuration using MSDeformAttnPixelDecoder with 16 attention heads', 'review the Mask2FormerHead transformer decoder configuration using MultiScaleMaskedTransformerDecoder with 100 queries', 'build a MultiScaleMaskedTransformerDecoder for mask classification with configurable queries, heads, and decoder layers', 'create a SelfAttentionLayer with multihead attention, layer norm, dropout, and optional pre-normalization', 'create a CrossAttentionLayer that attends between target queries and memory features with positional embeddings', 'create a FFNLayer with two linear layers, dropout, layer norm, and configurable activation function', 'create a Conv2d wrapper that supports optional normalization and activation layers after convolution', 'build a MSDeformAttnPixelDecoder for multi-scale feature decoding in semantic segmentation models', 'create a MSDeformAttnTransformerEncoderOnly with configurable encoder layers and multi-scale feature levels', 'build a Conv2d wrapper module with optional normalization and activation layers', 'test the c2_xavier_fill function to initialize module weights using Caffe2 XavierFill', 'review the MSDeformAttnTransformerEncoderLayer forward pass combining self-attention and feed-forward networks']
```

Usage

```
{'build_mask2former_decoder': 'build a MultiScaleMaskedTransformerDecoder for mask classification with configurable queries, heads, and decoder layers', 'create_self_attention_layer': 'create a SelfAttentionLayer with multihead attention, layer norm, dropout, and optional pre-normalization', 'create_cross_attention_layer': 'create a CrossAttentionLayer that attends between target queries and memory features with positional embeddings', 'create_ffn_layer': 'create a FFNLayer with two linear layers, dropout, layer norm, and configurable activation function', 'create_conv2d_wrapper': 'create a Conv2d wrapper that supports optional normalization and activation layers after convolution'}
```

## File: facebookresearch_dinov3/dinov3/eval/segmentation/models/heads/pixel_decoder.py

Prompts

```
['create a LinearHead with specified input channels and output channels for semantic segmentation', 'build a LinearHead that concatenates CLS tokens with patch tokens for segmentation', 'run a forward pass through the LinearHead to get segmentation feature maps', 'predict a segmentation map by running the LinearHead predict method with rescaling', 'transform and concatenate multi-level image features using bilinear interpolation', 'build a Mask2FormerHead instance with a custom input shape and number of classes for segmentation', 'run the Mask2FormerHead forward pass on a batch of feature tensors to get predictions', 'run the Mask2FormerHead predict method to get interpolated segmentation masks at a target resolution', 'review the Mask2FormerHead pixel decoder configuration using MSDeformAttnPixelDecoder with 16 attention heads', 'review the Mask2FormerHead transformer decoder configuration using MultiScaleMaskedTransformerDecoder with 100 queries', 'build a MultiScaleMaskedTransformerDecoder for mask classification with configurable queries, heads, and decoder layers', 'create a SelfAttentionLayer with multihead attention, layer norm, dropout, and optional pre-normalization', 'create a CrossAttentionLayer that attends between target queries and memory features with positional embeddings', 'create a FFNLayer with two linear layers, dropout, layer norm, and configurable activation function', 'create a Conv2d wrapper that supports optional normalization and activation layers after convolution', 'build a MSDeformAttnPixelDecoder for multi-scale feature decoding in semantic segmentation models', 'create a MSDeformAttnTransformerEncoderOnly with configurable encoder layers and multi-scale feature levels', 'build a Conv2d wrapper module with optional normalization and activation layers', 'test the c2_xavier_fill function to initialize module weights using Caffe2 XavierFill', 'review the MSDeformAttnTransformerEncoderLayer forward pass combining self-attention and feed-forward networks']
```

Usage

```
{'build_pixel_decoder': 'build a MSDeformAttnPixelDecoder for multi-scale feature decoding in semantic segmentation models', 'create_transformer_encoder': 'create a MSDeformAttnTransformerEncoderOnly with configurable encoder layers and multi-scale feature levels', 'build_conv2d_wrapper': 'build a Conv2d wrapper module with optional normalization and activation layers', 'test_xavier_fill': 'test the c2_xavier_fill function to initialize module weights using Caffe2 XavierFill', 'review_encoder_layer': 'review the MSDeformAttnTransformerEncoderLayer forward pass combining self-attention and feed-forward networks'}
```

