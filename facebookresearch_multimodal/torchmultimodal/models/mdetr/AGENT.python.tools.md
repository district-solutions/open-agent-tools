# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/torchmultimodal/models/mdetr/image_encoder.py

Prompts

```
['build a ResNet101 backbone with frozen batch norm and frozen early layer weights for MDetr', 'create a FrozenBatchNorm2d module with fixed batch statistics to replace BatchNorm2d for small batches', 'create a 2D sinusoidal position embedding module from a padding mask tensor for transformer models', 'create a MaskedIntermediateLayer wrapper that extracts a named intermediate layer and resizes masks accordingly', 'review the FrozenBatchNorm2d forward pass that normalizes input tensors using fixed running mean and variance', 'build an MDETR model with ResNet101 backbone and RoBERTa text encoder for multimodal object detection', 'build an MDETR model for visual question answering with GQA heads and contrastive alignment', 'build an MDETR model for phrase grounding with contrastive image-text alignment projections', 'run the MDETR model forward pass with a list of image tensors and tokenized text tensors', 'create a ModuleDict of GQA answer prediction heads for answer type, object, relation, attribute, category, and global tasks', 'build a RoBERTa text encoder with BERT embeddings and a modified transformer encoder for MDETR', 'create a transformer encoder that takes embeddings and applies layer-by-layer encoding with attention masks', 'create a feature resizer that linearly transforms embeddings from one dimension to another with dropout and layer norm', 'run the modified transformer encoder forward pass on a batch of embeddings with an attention mask', 'run the feature resizer forward pass to resize encoder features to a target dimension', 'build a MDETR transformer model with configurable encoder and decoder layers for multimodal detection', 'create a TransformerEncoder that stacks multiple encoder layers with optional layer normalization', 'create a TransformerDecoder that stacks decoder layers and returns intermediate outputs per layer', 'build a TransformerEncoderLayer with self-attention, MLP, and support for PreNorm or PostNorm', 'build a TransformerDecoderLayer with self-attention, cross-attention to image memory, and feedforward network']
```

Usage

```
{'build_resnet101_backbone': 'build a ResNet101 backbone with frozen batch norm and frozen early layer weights for MDetr', 'create_frozen_batch_norm': 'create a FrozenBatchNorm2d module with fixed batch statistics to replace BatchNorm2d for small batches', 'create_position_embedding_2d': 'create a 2D sinusoidal position embedding module from a padding mask tensor for transformer models', 'create_masked_intermediate_layer': 'create a MaskedIntermediateLayer wrapper that extracts a named intermediate layer and resizes masks accordingly', 'review_frozen_batch_norm_forward': 'review the FrozenBatchNorm2d forward pass that normalizes input tensors using fixed running mean and variance'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/mdetr/model.py

Prompts

```
['build a ResNet101 backbone with frozen batch norm and frozen early layer weights for MDetr', 'create a FrozenBatchNorm2d module with fixed batch statistics to replace BatchNorm2d for small batches', 'create a 2D sinusoidal position embedding module from a padding mask tensor for transformer models', 'create a MaskedIntermediateLayer wrapper that extracts a named intermediate layer and resizes masks accordingly', 'review the FrozenBatchNorm2d forward pass that normalizes input tensors using fixed running mean and variance', 'build an MDETR model with ResNet101 backbone and RoBERTa text encoder for multimodal object detection', 'build an MDETR model for visual question answering with GQA heads and contrastive alignment', 'build an MDETR model for phrase grounding with contrastive image-text alignment projections', 'run the MDETR model forward pass with a list of image tensors and tokenized text tensors', 'create a ModuleDict of GQA answer prediction heads for answer type, object, relation, attribute, category, and global tasks', 'build a RoBERTa text encoder with BERT embeddings and a modified transformer encoder for MDETR', 'create a transformer encoder that takes embeddings and applies layer-by-layer encoding with attention masks', 'create a feature resizer that linearly transforms embeddings from one dimension to another with dropout and layer norm', 'run the modified transformer encoder forward pass on a batch of embeddings with an attention mask', 'run the feature resizer forward pass to resize encoder features to a target dimension', 'build a MDETR transformer model with configurable encoder and decoder layers for multimodal detection', 'create a TransformerEncoder that stacks multiple encoder layers with optional layer normalization', 'create a TransformerDecoder that stacks decoder layers and returns intermediate outputs per layer', 'build a TransformerEncoderLayer with self-attention, MLP, and support for PreNorm or PostNorm', 'build a TransformerDecoderLayer with self-attention, cross-attention to image memory, and feedforward network']
```

Usage

```
{'build_mdetr_model': 'build an MDETR model with ResNet101 backbone and RoBERTa text encoder for multimodal object detection', 'build_mdetr_vqa_model': 'build an MDETR model for visual question answering with GQA heads and contrastive alignment', 'build_mdetr_phrase_grounding_model': 'build an MDETR model for phrase grounding with contrastive image-text alignment projections', 'run_mdetr_forward': 'run the MDETR model forward pass with a list of image tensors and tokenized text tensors', 'create_gqa_heads': 'create a ModuleDict of GQA answer prediction heads for answer type, object, relation, attribute, category, and global tasks'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/mdetr/text_encoder.py

Prompts

```
['build a ResNet101 backbone with frozen batch norm and frozen early layer weights for MDetr', 'create a FrozenBatchNorm2d module with fixed batch statistics to replace BatchNorm2d for small batches', 'create a 2D sinusoidal position embedding module from a padding mask tensor for transformer models', 'create a MaskedIntermediateLayer wrapper that extracts a named intermediate layer and resizes masks accordingly', 'review the FrozenBatchNorm2d forward pass that normalizes input tensors using fixed running mean and variance', 'build an MDETR model with ResNet101 backbone and RoBERTa text encoder for multimodal object detection', 'build an MDETR model for visual question answering with GQA heads and contrastive alignment', 'build an MDETR model for phrase grounding with contrastive image-text alignment projections', 'run the MDETR model forward pass with a list of image tensors and tokenized text tensors', 'create a ModuleDict of GQA answer prediction heads for answer type, object, relation, attribute, category, and global tasks', 'build a RoBERTa text encoder with BERT embeddings and a modified transformer encoder for MDETR', 'create a transformer encoder that takes embeddings and applies layer-by-layer encoding with attention masks', 'create a feature resizer that linearly transforms embeddings from one dimension to another with dropout and layer norm', 'run the modified transformer encoder forward pass on a batch of embeddings with an attention mask', 'run the feature resizer forward pass to resize encoder features to a target dimension', 'build a MDETR transformer model with configurable encoder and decoder layers for multimodal detection', 'create a TransformerEncoder that stacks multiple encoder layers with optional layer normalization', 'create a TransformerDecoder that stacks decoder layers and returns intermediate outputs per layer', 'build a TransformerEncoderLayer with self-attention, MLP, and support for PreNorm or PostNorm', 'build a TransformerDecoderLayer with self-attention, cross-attention to image memory, and feedforward network']
```

Usage

```
{'build_mdetr_roberta_text_encoder': 'build a RoBERTa text encoder with BERT embeddings and a modified transformer encoder for MDETR', 'create_modified_transformer_encoder': 'create a transformer encoder that takes embeddings and applies layer-by-layer encoding with attention masks', 'create_feature_resizer': 'create a feature resizer that linearly transforms embeddings from one dimension to another with dropout and layer norm', 'run_modified_transformer_forward': 'run the modified transformer encoder forward pass on a batch of embeddings with an attention mask', 'run_feature_resizer_forward': 'run the feature resizer forward pass to resize encoder features to a target dimension'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/mdetr/transformer.py

Prompts

```
['build a ResNet101 backbone with frozen batch norm and frozen early layer weights for MDetr', 'create a FrozenBatchNorm2d module with fixed batch statistics to replace BatchNorm2d for small batches', 'create a 2D sinusoidal position embedding module from a padding mask tensor for transformer models', 'create a MaskedIntermediateLayer wrapper that extracts a named intermediate layer and resizes masks accordingly', 'review the FrozenBatchNorm2d forward pass that normalizes input tensors using fixed running mean and variance', 'build an MDETR model with ResNet101 backbone and RoBERTa text encoder for multimodal object detection', 'build an MDETR model for visual question answering with GQA heads and contrastive alignment', 'build an MDETR model for phrase grounding with contrastive image-text alignment projections', 'run the MDETR model forward pass with a list of image tensors and tokenized text tensors', 'create a ModuleDict of GQA answer prediction heads for answer type, object, relation, attribute, category, and global tasks', 'build a RoBERTa text encoder with BERT embeddings and a modified transformer encoder for MDETR', 'create a transformer encoder that takes embeddings and applies layer-by-layer encoding with attention masks', 'create a feature resizer that linearly transforms embeddings from one dimension to another with dropout and layer norm', 'run the modified transformer encoder forward pass on a batch of embeddings with an attention mask', 'run the feature resizer forward pass to resize encoder features to a target dimension', 'build a MDETR transformer model with configurable encoder and decoder layers for multimodal detection', 'create a TransformerEncoder that stacks multiple encoder layers with optional layer normalization', 'create a TransformerDecoder that stacks decoder layers and returns intermediate outputs per layer', 'build a TransformerEncoderLayer with self-attention, MLP, and support for PreNorm or PostNorm', 'build a TransformerDecoderLayer with self-attention, cross-attention to image memory, and feedforward network']
```

Usage

```
{'build_mdetr_transformer': 'build a MDETR transformer model with configurable encoder and decoder layers for multimodal detection', 'create_transformer_encoder': 'create a TransformerEncoder that stacks multiple encoder layers with optional layer normalization', 'create_transformer_decoder': 'create a TransformerDecoder that stacks decoder layers and returns intermediate outputs per layer', 'build_encoder_layer': 'build a TransformerEncoderLayer with self-attention, MLP, and support for PreNorm or PostNorm', 'build_decoder_layer': 'build a TransformerDecoderLayer with self-attention, cross-attention to image memory, and feedforward network'}
```

