# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/tests/models/masked_auto_encoder/test_model.py

Prompts

```
['test the image_mae model in eval mode and verify encoder output tensor shape and mean', 'test the image_mae model in training mode with masking_ratio set to zero', 'test the audio_mae model in eval mode and verify encoder output tensor shape', 'test the audio_mae model in training mode with masking_ratio set to 0.5', 'test the vit_s_16_audio_mae, vit_b_16_audio_mae, and vit_l_16_audio_mae standard model variants', 'test get_2d_sin_cos_embeddings with a 2x2 square input size and embed_dim 8', 'test get_2d_sin_cos_embeddings with a 2x1 rectangular input size and embed_dim 8', 'test that get_2d_sin_cos_embeddings raises ValueError when embed_dim is odd', 'run the TestPositionEmbeddings pytest class to validate all 2D positional embedding test cases', 'review the get_2d_sin_cos_embeddings function for correctness of sin and cos positional encoding values', 'test the WindowMultiHeadAttention forward pass with constant weights and ones input tensor', 'test the SwinTransformerBlock forward pass without shift using constant weights and ones input', 'test the SwinTransformerBlock forward pass with shift_size parameter using constant weights', 'test the SwinTransformer forward pass with multiple layers and verify last_hidden_state output', 'review the SwinTransformerBlock and WindowMultiHeadAttention classes for window attention and shift behavior', 'test CosineWithWarmupAndLRScaling scheduler step method with custom lr_scale param groups', 'test CosineWithWarmupAndLRScaling scheduler step method with default lr_scale of 1.0', 'test get_param_groups_with_layer_decay function with a vision transformer model and layer decay factor', 'test get_param_groups_with_weight_decay function with an audio MAE model to verify param grouping', 'review the CosineWithWarmupAndLRScaling class for cosine decay with warmup and layer-wise lr scaling']
```

Usage

```
{'test_image_mae_eval': 'test the image_mae model in eval mode and verify encoder output tensor shape and mean', 'test_image_mae_train_no_masking': 'test the image_mae model in training mode with masking_ratio set to zero', 'test_audio_mae_eval': 'test the audio_mae model in eval mode and verify encoder output tensor shape', 'test_audio_mae_train_masking': 'test the audio_mae model in training mode with masking_ratio set to 0.5', 'test_standard_audio_mae': 'test the vit_s_16_audio_mae, vit_b_16_audio_mae, and vit_l_16_audio_mae standard model variants'}
```

## File: facebookresearch_multimodal/tests/models/masked_auto_encoder/test_position_embeddings.py

Prompts

```
['test the image_mae model in eval mode and verify encoder output tensor shape and mean', 'test the image_mae model in training mode with masking_ratio set to zero', 'test the audio_mae model in eval mode and verify encoder output tensor shape', 'test the audio_mae model in training mode with masking_ratio set to 0.5', 'test the vit_s_16_audio_mae, vit_b_16_audio_mae, and vit_l_16_audio_mae standard model variants', 'test get_2d_sin_cos_embeddings with a 2x2 square input size and embed_dim 8', 'test get_2d_sin_cos_embeddings with a 2x1 rectangular input size and embed_dim 8', 'test that get_2d_sin_cos_embeddings raises ValueError when embed_dim is odd', 'run the TestPositionEmbeddings pytest class to validate all 2D positional embedding test cases', 'review the get_2d_sin_cos_embeddings function for correctness of sin and cos positional encoding values', 'test the WindowMultiHeadAttention forward pass with constant weights and ones input tensor', 'test the SwinTransformerBlock forward pass without shift using constant weights and ones input', 'test the SwinTransformerBlock forward pass with shift_size parameter using constant weights', 'test the SwinTransformer forward pass with multiple layers and verify last_hidden_state output', 'review the SwinTransformerBlock and WindowMultiHeadAttention classes for window attention and shift behavior', 'test CosineWithWarmupAndLRScaling scheduler step method with custom lr_scale param groups', 'test CosineWithWarmupAndLRScaling scheduler step method with default lr_scale of 1.0', 'test get_param_groups_with_layer_decay function with a vision transformer model and layer decay factor', 'test get_param_groups_with_weight_decay function with an audio MAE model to verify param grouping', 'review the CosineWithWarmupAndLRScaling class for cosine decay with warmup and layer-wise lr scaling']
```

Usage

```
{'test_2d_sin_cos_embeddings_square': 'test get_2d_sin_cos_embeddings with a 2x2 square input size and embed_dim 8', 'test_2d_sin_cos_embeddings_rectangle': 'test get_2d_sin_cos_embeddings with a 2x1 rectangular input size and embed_dim 8', 'test_invalid_embed_dim': 'test that get_2d_sin_cos_embeddings raises ValueError when embed_dim is odd', 'run_TestPositionEmbeddings': 'run the TestPositionEmbeddings pytest class to validate all 2D positional embedding test cases', 'review_get_2d_sin_cos_embeddings': 'review the get_2d_sin_cos_embeddings function for correctness of sin and cos positional encoding values'}
```

## File: facebookresearch_multimodal/tests/models/masked_auto_encoder/test_swin_decoder.py

Prompts

```
['test the image_mae model in eval mode and verify encoder output tensor shape and mean', 'test the image_mae model in training mode with masking_ratio set to zero', 'test the audio_mae model in eval mode and verify encoder output tensor shape', 'test the audio_mae model in training mode with masking_ratio set to 0.5', 'test the vit_s_16_audio_mae, vit_b_16_audio_mae, and vit_l_16_audio_mae standard model variants', 'test get_2d_sin_cos_embeddings with a 2x2 square input size and embed_dim 8', 'test get_2d_sin_cos_embeddings with a 2x1 rectangular input size and embed_dim 8', 'test that get_2d_sin_cos_embeddings raises ValueError when embed_dim is odd', 'run the TestPositionEmbeddings pytest class to validate all 2D positional embedding test cases', 'review the get_2d_sin_cos_embeddings function for correctness of sin and cos positional encoding values', 'test the WindowMultiHeadAttention forward pass with constant weights and ones input tensor', 'test the SwinTransformerBlock forward pass without shift using constant weights and ones input', 'test the SwinTransformerBlock forward pass with shift_size parameter using constant weights', 'test the SwinTransformer forward pass with multiple layers and verify last_hidden_state output', 'review the SwinTransformerBlock and WindowMultiHeadAttention classes for window attention and shift behavior', 'test CosineWithWarmupAndLRScaling scheduler step method with custom lr_scale param groups', 'test CosineWithWarmupAndLRScaling scheduler step method with default lr_scale of 1.0', 'test get_param_groups_with_layer_decay function with a vision transformer model and layer decay factor', 'test get_param_groups_with_weight_decay function with an audio MAE model to verify param grouping', 'review the CosineWithWarmupAndLRScaling class for cosine decay with warmup and layer-wise lr scaling']
```

Usage

```
{'test_WindowMultiHeadAttention_forward': 'test the WindowMultiHeadAttention forward pass with constant weights and ones input tensor', 'test_SwinTransformerBlock_forward_no_shift': 'test the SwinTransformerBlock forward pass without shift using constant weights and ones input', 'test_SwinTransformerBlock_forward_shift': 'test the SwinTransformerBlock forward pass with shift_size parameter using constant weights', 'test_SwinTransformer_forward': 'test the SwinTransformer forward pass with multiple layers and verify last_hidden_state output', 'review_SwinTransformerBlock_classes': 'review the SwinTransformerBlock and WindowMultiHeadAttention classes for window attention and shift behavior'}
```

## File: facebookresearch_multimodal/tests/models/masked_auto_encoder/test_utils.py

Prompts

```
['test the image_mae model in eval mode and verify encoder output tensor shape and mean', 'test the image_mae model in training mode with masking_ratio set to zero', 'test the audio_mae model in eval mode and verify encoder output tensor shape', 'test the audio_mae model in training mode with masking_ratio set to 0.5', 'test the vit_s_16_audio_mae, vit_b_16_audio_mae, and vit_l_16_audio_mae standard model variants', 'test get_2d_sin_cos_embeddings with a 2x2 square input size and embed_dim 8', 'test get_2d_sin_cos_embeddings with a 2x1 rectangular input size and embed_dim 8', 'test that get_2d_sin_cos_embeddings raises ValueError when embed_dim is odd', 'run the TestPositionEmbeddings pytest class to validate all 2D positional embedding test cases', 'review the get_2d_sin_cos_embeddings function for correctness of sin and cos positional encoding values', 'test the WindowMultiHeadAttention forward pass with constant weights and ones input tensor', 'test the SwinTransformerBlock forward pass without shift using constant weights and ones input', 'test the SwinTransformerBlock forward pass with shift_size parameter using constant weights', 'test the SwinTransformer forward pass with multiple layers and verify last_hidden_state output', 'review the SwinTransformerBlock and WindowMultiHeadAttention classes for window attention and shift behavior', 'test CosineWithWarmupAndLRScaling scheduler step method with custom lr_scale param groups', 'test CosineWithWarmupAndLRScaling scheduler step method with default lr_scale of 1.0', 'test get_param_groups_with_layer_decay function with a vision transformer model and layer decay factor', 'test get_param_groups_with_weight_decay function with an audio MAE model to verify param grouping', 'review the CosineWithWarmupAndLRScaling class for cosine decay with warmup and layer-wise lr scaling']
```

Usage

```
{'test_CosineWithWarmupAndLRScaling_step': 'test CosineWithWarmupAndLRScaling scheduler step method with custom lr_scale param groups', 'test_CosineWithWarmupAndLRScaling_default_lr_scale': 'test CosineWithWarmupAndLRScaling scheduler step method with default lr_scale of 1.0', 'test_get_param_groups_with_layer_decay': 'test get_param_groups_with_layer_decay function with a vision transformer model and layer decay factor', 'test_get_param_groups_with_weight_decay': 'test get_param_groups_with_weight_decay function with an audio MAE model to verify param grouping', 'review_CosineWithWarmupAndLRScaling': 'review the CosineWithWarmupAndLRScaling class for cosine decay with warmup and layer-wise lr scaling'}
```

