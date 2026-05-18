# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/torchmultimodal/models/albef/image_encoder.py

Prompts

```
['build an ALBEFVisionEncoder with default 256x256 image size and 12 transformer layers', 'build an ALBEFVisionEncoder with custom image size, patch size, and hidden dimensions', 'run the ALBEFVisionEncoder forward pass on a batch of image tensors', 'review the ALBEFVisionEncoder constructor to configure dropout and attention dropout rates', 'summarize the ALBEFVisionEncoder class which wraps a VisionTransformer feature extractor', 'build an ALBEF model with vision, text, and multimodal encoders for image-text alignment', 'build an ALBEF model with similarity computation and momentum queue for ITC and ITM losses', 'run the ALBEF model forward pass with image, text, and attention mask tensors', 'run the ALBEF model with similarity forward pass to get embeddings and similarity scores', 'gather embeddings across all GPUs using distributed all_gather for multi-GPU training', 'build a TransformerCrossAttentionLayer with self-attention and cross-attention blocks for multimodal inputs', 'build an ALBEFMultimodalEncoder with stacked cross-attention layers for image-text encoding', 'run forward pass on TransformerCrossAttentionLayer with hidden states and encoder hidden states', 'run forward pass on ALBEFMultimodalEncoder with text and image embeddings and attention masks', 'review the TransformerCrossAttentionLayer pre-norm forward path for layer norm placement before attention']
```

Usage

```
{'build_ALBEFVisionEncoder': 'build an ALBEFVisionEncoder with default 256x256 image size and 12 transformer layers', 'build_ALBEFVisionEncoder_custom': 'build an ALBEFVisionEncoder with custom image size, patch size, and hidden dimensions', 'run_ALBEFVisionEncoder_forward': 'run the ALBEFVisionEncoder forward pass on a batch of image tensors', 'review_ALBEFVisionEncoder_init': 'review the ALBEFVisionEncoder constructor to configure dropout and attention dropout rates', 'summarize_ALBEFVisionEncoder': 'summarize the ALBEFVisionEncoder class which wraps a VisionTransformer feature extractor'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/albef/model.py

Prompts

```
['build an ALBEFVisionEncoder with default 256x256 image size and 12 transformer layers', 'build an ALBEFVisionEncoder with custom image size, patch size, and hidden dimensions', 'run the ALBEFVisionEncoder forward pass on a batch of image tensors', 'review the ALBEFVisionEncoder constructor to configure dropout and attention dropout rates', 'summarize the ALBEFVisionEncoder class which wraps a VisionTransformer feature extractor', 'build an ALBEF model with vision, text, and multimodal encoders for image-text alignment', 'build an ALBEF model with similarity computation and momentum queue for ITC and ITM losses', 'run the ALBEF model forward pass with image, text, and attention mask tensors', 'run the ALBEF model with similarity forward pass to get embeddings and similarity scores', 'gather embeddings across all GPUs using distributed all_gather for multi-GPU training', 'build a TransformerCrossAttentionLayer with self-attention and cross-attention blocks for multimodal inputs', 'build an ALBEFMultimodalEncoder with stacked cross-attention layers for image-text encoding', 'run forward pass on TransformerCrossAttentionLayer with hidden states and encoder hidden states', 'run forward pass on ALBEFMultimodalEncoder with text and image embeddings and attention masks', 'review the TransformerCrossAttentionLayer pre-norm forward path for layer norm placement before attention']
```

Usage

```
{'build_ALBEFModel': 'build an ALBEF model with vision, text, and multimodal encoders for image-text alignment', 'build_ALBEFModelWithSimilarity': 'build an ALBEF model with similarity computation and momentum queue for ITC and ITM losses', 'run_ALBEFModel_forward': 'run the ALBEF model forward pass with image, text, and attention mask tensors', 'run_ALBEFModelWithSimilarity_forward': 'run the ALBEF model with similarity forward pass to get embeddings and similarity scores', 'run_gather_embeddings': 'gather embeddings across all GPUs using distributed all_gather for multi-GPU training'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/albef/multimodal_encoder.py

Prompts

```
['build an ALBEFVisionEncoder with default 256x256 image size and 12 transformer layers', 'build an ALBEFVisionEncoder with custom image size, patch size, and hidden dimensions', 'run the ALBEFVisionEncoder forward pass on a batch of image tensors', 'review the ALBEFVisionEncoder constructor to configure dropout and attention dropout rates', 'summarize the ALBEFVisionEncoder class which wraps a VisionTransformer feature extractor', 'build an ALBEF model with vision, text, and multimodal encoders for image-text alignment', 'build an ALBEF model with similarity computation and momentum queue for ITC and ITM losses', 'run the ALBEF model forward pass with image, text, and attention mask tensors', 'run the ALBEF model with similarity forward pass to get embeddings and similarity scores', 'gather embeddings across all GPUs using distributed all_gather for multi-GPU training', 'build a TransformerCrossAttentionLayer with self-attention and cross-attention blocks for multimodal inputs', 'build an ALBEFMultimodalEncoder with stacked cross-attention layers for image-text encoding', 'run forward pass on TransformerCrossAttentionLayer with hidden states and encoder hidden states', 'run forward pass on ALBEFMultimodalEncoder with text and image embeddings and attention masks', 'review the TransformerCrossAttentionLayer pre-norm forward path for layer norm placement before attention']
```

Usage

```
{'build_transformer_cross_attention_layer': 'build a TransformerCrossAttentionLayer with self-attention and cross-attention blocks for multimodal inputs', 'build_albef_multimodal_encoder': 'build an ALBEFMultimodalEncoder with stacked cross-attention layers for image-text encoding', 'run_transformer_cross_attention_forward': 'run forward pass on TransformerCrossAttentionLayer with hidden states and encoder hidden states', 'run_albef_encoder_forward': 'run forward pass on ALBEFMultimodalEncoder with text and image embeddings and attention masks', 'review_transformer_cross_attention_prenorm': 'review the TransformerCrossAttentionLayer pre-norm forward path for layer norm placement before attention'}
```

