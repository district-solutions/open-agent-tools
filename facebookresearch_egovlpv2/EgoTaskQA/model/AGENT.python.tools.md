# Agent Python Tools

- repo: facebookresearch/egovlpv2
- repo_uri: https://github.com/facebookresearch/egovlpv2

## File: facebookresearch_egovlpv2/EgoTaskQA/model/heads.py

Prompts

```
['build a Pooler layer that applies linear transform and tanh activation to hidden states', 'create an ITMHead that maps hidden states to a 2-class image-text matching output', 'create an MLMHead with BertPredictionHeadTransform and decoder for masked language modeling', 'review the Pooler forward pass that transforms hidden states through dense and tanh layers', 'test the MLMHead initialization that optionally reuses decoder weights from a pretrained model', 'build a FrozenInTime model with SpaceTimeTransformer video and RoBERTa text encoders for multimodal learning', 'run a forward pass through FrozenInTime with video and text data to get fused embeddings', 'compute text embeddings from input tokens using the RoBERTa encoder and projection layers', 'compute video embeddings from input frames using the SpaceTimeTransformer and projection layers', 'calculate cosine similarity matrix between two sets of normalized embeddings using sim_matrix', 'build a RoBERTa model with text-to-image cross-attention layers for multimodal fusion', 'create a RoBERTa encoder that uses gradient checkpointing to save memory during training', 'refactor RobertaLayer to add cross-attention between text and image features in the last N layers', 'review RobertaSelfAttention where key and value projections use DIM_IMG input size for cross-attention layers', 'test apply_chunking_to_forward to chunk tensors and apply a forward function per chunk to reduce memory', 'run the FrozenInTime forward pass with video and text data to get task predictions', 'build a SpaceTimeTransformer model with configurable num_frames, embed_dim, and depth for video understanding', 'create a VideoPatchEmbed module to convert video frames into patch embeddings with 2D convolution', 'run the SpaceTimeBlock forward pass with separate spatial and temporal attention mechanisms', 'test the VarAttention module with optional text input y and y_mask for image-to-text cross-attention', 'review the Mlp class implementing a GELU-activated two-layer feed-forward network with dropout']
```

Usage

```
{'build_pooler_layer': 'build a Pooler layer that applies linear transform and tanh activation to hidden states', 'create_itm_head': 'create an ITMHead that maps hidden states to a 2-class image-text matching output', 'create_mlm_head': 'create an MLMHead with BertPredictionHeadTransform and decoder for masked language modeling', 'review_pooler_forward': 'review the Pooler forward pass that transforms hidden states through dense and tanh layers', 'test_mlm_head_weight_init': 'test the MLMHead initialization that optionally reuses decoder weights from a pretrained model'}
```

## File: facebookresearch_egovlpv2/EgoTaskQA/model/model.py

Prompts

```
['build a Pooler layer that applies linear transform and tanh activation to hidden states', 'create an ITMHead that maps hidden states to a 2-class image-text matching output', 'create an MLMHead with BertPredictionHeadTransform and decoder for masked language modeling', 'review the Pooler forward pass that transforms hidden states through dense and tanh layers', 'test the MLMHead initialization that optionally reuses decoder weights from a pretrained model', 'build a FrozenInTime model with SpaceTimeTransformer video and RoBERTa text encoders for multimodal learning', 'run a forward pass through FrozenInTime with video and text data to get fused embeddings', 'compute text embeddings from input tokens using the RoBERTa encoder and projection layers', 'compute video embeddings from input frames using the SpaceTimeTransformer and projection layers', 'calculate cosine similarity matrix between two sets of normalized embeddings using sim_matrix', 'build a RoBERTa model with text-to-image cross-attention layers for multimodal fusion', 'create a RoBERTa encoder that uses gradient checkpointing to save memory during training', 'refactor RobertaLayer to add cross-attention between text and image features in the last N layers', 'review RobertaSelfAttention where key and value projections use DIM_IMG input size for cross-attention layers', 'test apply_chunking_to_forward to chunk tensors and apply a forward function per chunk to reduce memory', 'run the FrozenInTime forward pass with video and text data to get task predictions', 'build a SpaceTimeTransformer model with configurable num_frames, embed_dim, and depth for video understanding', 'create a VideoPatchEmbed module to convert video frames into patch embeddings with 2D convolution', 'run the SpaceTimeBlock forward pass with separate spatial and temporal attention mechanisms', 'test the VarAttention module with optional text input y and y_mask for image-to-text cross-attention', 'review the Mlp class implementing a GELU-activated two-layer feed-forward network with dropout']
```

Usage

```
{'build_FrozenInTime_model': 'build a FrozenInTime model with SpaceTimeTransformer video and RoBERTa text encoders for multimodal learning', 'run_forward_pass': 'run a forward pass through FrozenInTime with video and text data to get fused embeddings', 'compute_text_embeddings': 'compute text embeddings from input tokens using the RoBERTa encoder and projection layers', 'compute_video_embeddings': 'compute video embeddings from input frames using the SpaceTimeTransformer and projection layers', 'calculate_similarity_matrix': 'calculate cosine similarity matrix between two sets of normalized embeddings using sim_matrix'}
```

## File: facebookresearch_egovlpv2/EgoTaskQA/model/roberta.py

Prompts

```
['build a Pooler layer that applies linear transform and tanh activation to hidden states', 'create an ITMHead that maps hidden states to a 2-class image-text matching output', 'create an MLMHead with BertPredictionHeadTransform and decoder for masked language modeling', 'review the Pooler forward pass that transforms hidden states through dense and tanh layers', 'test the MLMHead initialization that optionally reuses decoder weights from a pretrained model', 'build a FrozenInTime model with SpaceTimeTransformer video and RoBERTa text encoders for multimodal learning', 'run a forward pass through FrozenInTime with video and text data to get fused embeddings', 'compute text embeddings from input tokens using the RoBERTa encoder and projection layers', 'compute video embeddings from input frames using the SpaceTimeTransformer and projection layers', 'calculate cosine similarity matrix between two sets of normalized embeddings using sim_matrix', 'build a RoBERTa model with text-to-image cross-attention layers for multimodal fusion', 'create a RoBERTa encoder that uses gradient checkpointing to save memory during training', 'refactor RobertaLayer to add cross-attention between text and image features in the last N layers', 'review RobertaSelfAttention where key and value projections use DIM_IMG input size for cross-attention layers', 'test apply_chunking_to_forward to chunk tensors and apply a forward function per chunk to reduce memory', 'run the FrozenInTime forward pass with video and text data to get task predictions', 'build a SpaceTimeTransformer model with configurable num_frames, embed_dim, and depth for video understanding', 'create a VideoPatchEmbed module to convert video frames into patch embeddings with 2D convolution', 'run the SpaceTimeBlock forward pass with separate spatial and temporal attention mechanisms', 'test the VarAttention module with optional text input y and y_mask for image-to-text cross-attention', 'review the Mlp class implementing a GELU-activated two-layer feed-forward network with dropout']
```

Usage

```
{'build_roberta_model_with_cross_attention': 'build a RoBERTa model with text-to-image cross-attention layers for multimodal fusion', 'create_roberta_encoder_with_checkpointing': 'create a RoBERTa encoder that uses gradient checkpointing to save memory during training', 'refactor_roberta_layer_for_multimodal': 'refactor RobertaLayer to add cross-attention between text and image features in the last N layers', 'review_roberta_self_attention_key_value': 'review RobertaSelfAttention where key and value projections use DIM_IMG input size for cross-attention layers', 'test_apply_chunking_to_forward': 'test apply_chunking_to_forward to chunk tensors and apply a forward function per chunk to reduce memory'}
```

## File: facebookresearch_egovlpv2/EgoTaskQA/model/video_qa_model_linear_end2end.py

Prompts

```
['build a Pooler layer that applies linear transform and tanh activation to hidden states', 'create an ITMHead that maps hidden states to a 2-class image-text matching output', 'create an MLMHead with BertPredictionHeadTransform and decoder for masked language modeling', 'review the Pooler forward pass that transforms hidden states through dense and tanh layers', 'test the MLMHead initialization that optionally reuses decoder weights from a pretrained model', 'build a FrozenInTime model with SpaceTimeTransformer video and RoBERTa text encoders for multimodal learning', 'run a forward pass through FrozenInTime with video and text data to get fused embeddings', 'compute text embeddings from input tokens using the RoBERTa encoder and projection layers', 'compute video embeddings from input frames using the SpaceTimeTransformer and projection layers', 'calculate cosine similarity matrix between two sets of normalized embeddings using sim_matrix', 'build a RoBERTa model with text-to-image cross-attention layers for multimodal fusion', 'create a RoBERTa encoder that uses gradient checkpointing to save memory during training', 'refactor RobertaLayer to add cross-attention between text and image features in the last N layers', 'review RobertaSelfAttention where key and value projections use DIM_IMG input size for cross-attention layers', 'test apply_chunking_to_forward to chunk tensors and apply a forward function per chunk to reduce memory', 'run the FrozenInTime forward pass with video and text data to get task predictions', 'build a SpaceTimeTransformer model with configurable num_frames, embed_dim, and depth for video understanding', 'create a VideoPatchEmbed module to convert video frames into patch embeddings with 2D convolution', 'run the SpaceTimeBlock forward pass with separate spatial and temporal attention mechanisms', 'test the VarAttention module with optional text input y and y_mask for image-to-text cross-attention', 'review the Mlp class implementing a GELU-activated two-layer feed-forward network with dropout']
```

Usage

```
{'build_FrozenInTime_model': 'build a FrozenInTime model with SpaceTimeTransformer video and RoBERTa text encoders for EgoTaskQA', 'run_FrozenInTime_forward': 'run the FrozenInTime forward pass with video and text data to get task predictions', 'compute_text_embeddings': 'compute text embeddings using the RoBERTa model and projection layers from FrozenInTime', 'compute_video_embeddings': 'compute video embeddings using the SpaceTimeTransformer model and projection layers from FrozenInTime', 'calculate_similarity_matrix': 'calculate cosine similarity matrix between two sets of normalized embeddings using sim_matrix'}
```

## File: facebookresearch_egovlpv2/EgoTaskQA/model/video_transformer.py

Prompts

```
['build a Pooler layer that applies linear transform and tanh activation to hidden states', 'create an ITMHead that maps hidden states to a 2-class image-text matching output', 'create an MLMHead with BertPredictionHeadTransform and decoder for masked language modeling', 'review the Pooler forward pass that transforms hidden states through dense and tanh layers', 'test the MLMHead initialization that optionally reuses decoder weights from a pretrained model', 'build a FrozenInTime model with SpaceTimeTransformer video and RoBERTa text encoders for multimodal learning', 'run a forward pass through FrozenInTime with video and text data to get fused embeddings', 'compute text embeddings from input tokens using the RoBERTa encoder and projection layers', 'compute video embeddings from input frames using the SpaceTimeTransformer and projection layers', 'calculate cosine similarity matrix between two sets of normalized embeddings using sim_matrix', 'build a RoBERTa model with text-to-image cross-attention layers for multimodal fusion', 'create a RoBERTa encoder that uses gradient checkpointing to save memory during training', 'refactor RobertaLayer to add cross-attention between text and image features in the last N layers', 'review RobertaSelfAttention where key and value projections use DIM_IMG input size for cross-attention layers', 'test apply_chunking_to_forward to chunk tensors and apply a forward function per chunk to reduce memory', 'run the FrozenInTime forward pass with video and text data to get task predictions', 'build a SpaceTimeTransformer model with configurable num_frames, embed_dim, and depth for video understanding', 'create a VideoPatchEmbed module to convert video frames into patch embeddings with 2D convolution', 'run the SpaceTimeBlock forward pass with separate spatial and temporal attention mechanisms', 'test the VarAttention module with optional text input y and y_mask for image-to-text cross-attention', 'review the Mlp class implementing a GELU-activated two-layer feed-forward network with dropout']
```

Usage

```
{'build_video_transformer_model': 'build a SpaceTimeTransformer model with configurable num_frames, embed_dim, and depth for video understanding', 'create_video_patch_embedding': 'create a VideoPatchEmbed module to convert video frames into patch embeddings with 2D convolution', 'run_space_time_attention': 'run the SpaceTimeBlock forward pass with separate spatial and temporal attention mechanisms', 'test_var_attention_with_text': 'test the VarAttention module with optional text input y and y_mask for image-to-text cross-attention', 'review_mlp_feed_forward': 'review the Mlp class implementing a GELU-activated two-layer feed-forward network with dropout'}
```

