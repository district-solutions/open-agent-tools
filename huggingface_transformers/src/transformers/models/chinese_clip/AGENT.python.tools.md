# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/chinese_clip/configuration_chinese_clip.py

Prompts

```
['create a ChineseCLIPTextConfig with custom vocab_size, hidden_size, and num_hidden_layers for the text encoder', 'create a ChineseCLIPVisionConfig with custom image_size, patch_size, and projection_dim for the vision encoder', 'create a ChineseCLIPConfig combining ChineseCLIPTextConfig and ChineseCLIPVisionConfig with a projection_dim', 'test ChineseCLIPTextConfig validate_architecture raises ValueError when hidden_size is not a multiple of num_attention_heads', 'test ChineseCLIPVisionConfig validate_architecture raises ValueError when hidden_size is not a multiple of num_attention_heads', 'convert a ChineseCLIP PyTorch checkpoint to HuggingFace Transformers format', 'copy text encoder weights and projection matrix from original checkpoint to HuggingFace model', 'copy vision encoder weights and projection matrix from original checkpoint to HuggingFace model', 'copy attention layer weights including q, k, v projections and output projection from original checkpoint', 'copy transformer encoder layers including layer norms, MLP, and attention from original checkpoint', 'create a ChineseCLIPModel for Chinese image-text contrastive learning with pretrained weights', 'run ChineseCLIPModel forward pass to compute image-text similarity logits and contrastive loss', 'get normalized text embeddings from ChineseCLIPModel using get_text_features with tokenized Chinese input', 'get normalized image embeddings from ChineseCLIPModel using get_image_features with pixel values', 'build a ChineseCLIPVisionModel encoder to extract pooled and sequence outputs from image inputs', 'build a ChineseCLIPTextModel to encode Chinese text into embedding vectors', 'run ChineseCLIPModel forward pass with text and images to compute contrastive similarity logits', 'get text features from ChineseCLIPModel by encoding Chinese tokenized input sequences', 'get image features from ChineseCLIPModel by encoding pixel values through the vision encoder']
```

Usage

```
{'create_ChineseCLIPTextConfig': 'create a ChineseCLIPTextConfig with custom vocab_size, hidden_size, and num_hidden_layers for the text encoder', 'create_ChineseCLIPVisionConfig': 'create a ChineseCLIPVisionConfig with custom image_size, patch_size, and projection_dim for the vision encoder', 'create_ChineseCLIPConfig': 'create a ChineseCLIPConfig combining ChineseCLIPTextConfig and ChineseCLIPVisionConfig with a projection_dim', 'test_ChineseCLIPTextConfig_validate_architecture': 'test ChineseCLIPTextConfig validate_architecture raises ValueError when hidden_size is not a multiple of num_attention_heads', 'test_ChineseCLIPVisionConfig_validate_architecture': 'test ChineseCLIPVisionConfig validate_architecture raises ValueError when hidden_size is not a multiple of num_attention_heads'}
```

## File: huggingface_transformers/src/transformers/models/chinese_clip/convert_chinese_clip_original_pytorch_to_hf.py

Prompts

```
['create a ChineseCLIPTextConfig with custom vocab_size, hidden_size, and num_hidden_layers for the text encoder', 'create a ChineseCLIPVisionConfig with custom image_size, patch_size, and projection_dim for the vision encoder', 'create a ChineseCLIPConfig combining ChineseCLIPTextConfig and ChineseCLIPVisionConfig with a projection_dim', 'test ChineseCLIPTextConfig validate_architecture raises ValueError when hidden_size is not a multiple of num_attention_heads', 'test ChineseCLIPVisionConfig validate_architecture raises ValueError when hidden_size is not a multiple of num_attention_heads', 'convert a ChineseCLIP PyTorch checkpoint to HuggingFace Transformers format', 'copy text encoder weights and projection matrix from original checkpoint to HuggingFace model', 'copy vision encoder weights and projection matrix from original checkpoint to HuggingFace model', 'copy attention layer weights including q, k, v projections and output projection from original checkpoint', 'copy transformer encoder layers including layer norms, MLP, and attention from original checkpoint', 'create a ChineseCLIPModel for Chinese image-text contrastive learning with pretrained weights', 'run ChineseCLIPModel forward pass to compute image-text similarity logits and contrastive loss', 'get normalized text embeddings from ChineseCLIPModel using get_text_features with tokenized Chinese input', 'get normalized image embeddings from ChineseCLIPModel using get_image_features with pixel values', 'build a ChineseCLIPVisionModel encoder to extract pooled and sequence outputs from image inputs', 'build a ChineseCLIPTextModel to encode Chinese text into embedding vectors', 'run ChineseCLIPModel forward pass with text and images to compute contrastive similarity logits', 'get text features from ChineseCLIPModel by encoding Chinese tokenized input sequences', 'get image features from ChineseCLIPModel by encoding pixel values through the vision encoder']
```

Usage

```
{'convert_chinese_clip_checkpoint': 'convert a ChineseCLIP PyTorch checkpoint to HuggingFace Transformers format', 'copy_text_model_and_projection': 'copy text encoder weights and projection matrix from original checkpoint to HuggingFace model', 'copy_vision_model_and_projection': 'copy vision encoder weights and projection matrix from original checkpoint to HuggingFace model', 'copy_attn_layer': 'copy attention layer weights including q, k, v projections and output projection from original checkpoint', 'copy_layers': 'copy transformer encoder layers including layer norms, MLP, and attention from original checkpoint'}
```

## File: huggingface_transformers/src/transformers/models/chinese_clip/modeling_chinese_clip.py

Prompts

```
['create a ChineseCLIPTextConfig with custom vocab_size, hidden_size, and num_hidden_layers for the text encoder', 'create a ChineseCLIPVisionConfig with custom image_size, patch_size, and projection_dim for the vision encoder', 'create a ChineseCLIPConfig combining ChineseCLIPTextConfig and ChineseCLIPVisionConfig with a projection_dim', 'test ChineseCLIPTextConfig validate_architecture raises ValueError when hidden_size is not a multiple of num_attention_heads', 'test ChineseCLIPVisionConfig validate_architecture raises ValueError when hidden_size is not a multiple of num_attention_heads', 'convert a ChineseCLIP PyTorch checkpoint to HuggingFace Transformers format', 'copy text encoder weights and projection matrix from original checkpoint to HuggingFace model', 'copy vision encoder weights and projection matrix from original checkpoint to HuggingFace model', 'copy attention layer weights including q, k, v projections and output projection from original checkpoint', 'copy transformer encoder layers including layer norms, MLP, and attention from original checkpoint', 'create a ChineseCLIPModel for Chinese image-text contrastive learning with pretrained weights', 'run ChineseCLIPModel forward pass to compute image-text similarity logits and contrastive loss', 'get normalized text embeddings from ChineseCLIPModel using get_text_features with tokenized Chinese input', 'get normalized image embeddings from ChineseCLIPModel using get_image_features with pixel values', 'build a ChineseCLIPVisionModel encoder to extract pooled and sequence outputs from image inputs', 'build a ChineseCLIPTextModel to encode Chinese text into embedding vectors', 'run ChineseCLIPModel forward pass with text and images to compute contrastive similarity logits', 'get text features from ChineseCLIPModel by encoding Chinese tokenized input sequences', 'get image features from ChineseCLIPModel by encoding pixel values through the vision encoder']
```

Usage

```
{'create_chinese_clip_model': 'create a ChineseCLIPModel for Chinese image-text contrastive learning with pretrained weights', 'run_image_text_similarity': 'run ChineseCLIPModel forward pass to compute image-text similarity logits and contrastive loss', 'get_text_embeddings': 'get normalized text embeddings from ChineseCLIPModel using get_text_features with tokenized Chinese input', 'get_image_embeddings': 'get normalized image embeddings from ChineseCLIPModel using get_image_features with pixel values', 'build_vision_encoder': 'build a ChineseCLIPVisionModel encoder to extract pooled and sequence outputs from image inputs'}
```

## File: huggingface_transformers/src/transformers/models/chinese_clip/modular_chinese_clip.py

Prompts

```
['create a ChineseCLIPTextConfig with custom vocab_size, hidden_size, and num_hidden_layers for the text encoder', 'create a ChineseCLIPVisionConfig with custom image_size, patch_size, and projection_dim for the vision encoder', 'create a ChineseCLIPConfig combining ChineseCLIPTextConfig and ChineseCLIPVisionConfig with a projection_dim', 'test ChineseCLIPTextConfig validate_architecture raises ValueError when hidden_size is not a multiple of num_attention_heads', 'test ChineseCLIPVisionConfig validate_architecture raises ValueError when hidden_size is not a multiple of num_attention_heads', 'convert a ChineseCLIP PyTorch checkpoint to HuggingFace Transformers format', 'copy text encoder weights and projection matrix from original checkpoint to HuggingFace model', 'copy vision encoder weights and projection matrix from original checkpoint to HuggingFace model', 'copy attention layer weights including q, k, v projections and output projection from original checkpoint', 'copy transformer encoder layers including layer norms, MLP, and attention from original checkpoint', 'create a ChineseCLIPModel for Chinese image-text contrastive learning with pretrained weights', 'run ChineseCLIPModel forward pass to compute image-text similarity logits and contrastive loss', 'get normalized text embeddings from ChineseCLIPModel using get_text_features with tokenized Chinese input', 'get normalized image embeddings from ChineseCLIPModel using get_image_features with pixel values', 'build a ChineseCLIPVisionModel encoder to extract pooled and sequence outputs from image inputs', 'build a ChineseCLIPTextModel to encode Chinese text into embedding vectors', 'run ChineseCLIPModel forward pass with text and images to compute contrastive similarity logits', 'get text features from ChineseCLIPModel by encoding Chinese tokenized input sequences', 'get image features from ChineseCLIPModel by encoding pixel values through the vision encoder']
```

Usage

```
{'create_chinese_clip_model': 'create a ChineseCLIPModel instance with text and vision configs for Chinese image-text retrieval', 'build_chinese_clip_text_model': 'build a ChineseCLIPTextModel to encode Chinese text into embedding vectors', 'run_chinese_clip_forward': 'run ChineseCLIPModel forward pass with text and images to compute contrastive similarity logits', 'get_chinese_clip_text_features': 'get text features from ChineseCLIPModel by encoding Chinese tokenized input sequences', 'get_chinese_clip_image_features': 'get image features from ChineseCLIPModel by encoding pixel values through the vision encoder'}
```

