# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/altclip/configuration_altclip.py

Prompts

```
['create an AltCLIPTextConfig instance with default BAAI/AltCLIP text model parameters', 'create an AltCLIPVisionConfig instance with default BAAI/AltCLIP vision model parameters', 'create an AltCLIPConfig instance combining text and vision sub-configs for the multimodal model', 'review the AltCLIPTextConfig validate_architecture method that checks hidden size divisibility', 'review the AltCLIPVisionConfig validate_architecture method that checks hidden size divisibility', 'create a call to AltCLIPModel.get_text_features to extract normalized text embeddings from input token ids', 'create a call to AltCLIPModel.get_image_features to extract normalized image embeddings from pixel values', 'run AltCLIPModel forward pass with both image and text inputs to compute image-text similarity logits', 'build AltCLIPVisionModel to extract pooled and sequence image embeddings from pixel values', 'test AltCLIPModel forward with return_loss=True to compute bidirectional image-text contrastive loss', 'create an AltCLIPModel instance with text and vision configs for multimodal image-text retrieval', 'run the AltCLIPModel forward pass with text and image inputs to compute contrastive logits', 'build an AltCLIPTextModel from AltCLIPTextConfig to encode text into projected embeddings', 'build an AltCLIPVisionModel from AltCLIPVisionConfig to encode images into visual embeddings', 'test AltCLIPModel get_text_features and get_image_features methods for embedding extraction']
```

Usage

```
{'create_AltCLIPTextConfig': 'create an AltCLIPTextConfig instance with default BAAI/AltCLIP text model parameters', 'create_AltCLIPVisionConfig': 'create an AltCLIPVisionConfig instance with default BAAI/AltCLIP vision model parameters', 'create_AltCLIPConfig': 'create an AltCLIPConfig instance combining text and vision sub-configs for the multimodal model', 'review_AltCLIPTextConfig_validate_architecture': 'review the AltCLIPTextConfig validate_architecture method that checks hidden size divisibility', 'review_AltCLIPVisionConfig_validate_architecture': 'review the AltCLIPVisionConfig validate_architecture method that checks hidden size divisibility'}
```

## File: huggingface_transformers/src/transformers/models/altclip/modeling_altclip.py

Prompts

```
['create an AltCLIPTextConfig instance with default BAAI/AltCLIP text model parameters', 'create an AltCLIPVisionConfig instance with default BAAI/AltCLIP vision model parameters', 'create an AltCLIPConfig instance combining text and vision sub-configs for the multimodal model', 'review the AltCLIPTextConfig validate_architecture method that checks hidden size divisibility', 'review the AltCLIPVisionConfig validate_architecture method that checks hidden size divisibility', 'create a call to AltCLIPModel.get_text_features to extract normalized text embeddings from input token ids', 'create a call to AltCLIPModel.get_image_features to extract normalized image embeddings from pixel values', 'run AltCLIPModel forward pass with both image and text inputs to compute image-text similarity logits', 'build AltCLIPVisionModel to extract pooled and sequence image embeddings from pixel values', 'test AltCLIPModel forward with return_loss=True to compute bidirectional image-text contrastive loss', 'create an AltCLIPModel instance with text and vision configs for multimodal image-text retrieval', 'run the AltCLIPModel forward pass with text and image inputs to compute contrastive logits', 'build an AltCLIPTextModel from AltCLIPTextConfig to encode text into projected embeddings', 'build an AltCLIPVisionModel from AltCLIPVisionConfig to encode images into visual embeddings', 'test AltCLIPModel get_text_features and get_image_features methods for embedding extraction']
```

Usage

```
{'create_model_get_text_features': 'create a call to AltCLIPModel.get_text_features to extract normalized text embeddings from input token ids', 'create_model_get_image_features': 'create a call to AltCLIPModel.get_image_features to extract normalized image embeddings from pixel values', 'run_model_forward_pass': 'run AltCLIPModel forward pass with both image and text inputs to compute image-text similarity logits', 'build_vision_encoder': 'build AltCLIPVisionModel to extract pooled and sequence image embeddings from pixel values', 'test_contrastive_loss': 'test AltCLIPModel forward with return_loss=True to compute bidirectional image-text contrastive loss'}
```

## File: huggingface_transformers/src/transformers/models/altclip/modular_altclip.py

Prompts

```
['create an AltCLIPTextConfig instance with default BAAI/AltCLIP text model parameters', 'create an AltCLIPVisionConfig instance with default BAAI/AltCLIP vision model parameters', 'create an AltCLIPConfig instance combining text and vision sub-configs for the multimodal model', 'review the AltCLIPTextConfig validate_architecture method that checks hidden size divisibility', 'review the AltCLIPVisionConfig validate_architecture method that checks hidden size divisibility', 'create a call to AltCLIPModel.get_text_features to extract normalized text embeddings from input token ids', 'create a call to AltCLIPModel.get_image_features to extract normalized image embeddings from pixel values', 'run AltCLIPModel forward pass with both image and text inputs to compute image-text similarity logits', 'build AltCLIPVisionModel to extract pooled and sequence image embeddings from pixel values', 'test AltCLIPModel forward with return_loss=True to compute bidirectional image-text contrastive loss', 'create an AltCLIPModel instance with text and vision configs for multimodal image-text retrieval', 'run the AltCLIPModel forward pass with text and image inputs to compute contrastive logits', 'build an AltCLIPTextModel from AltCLIPTextConfig to encode text into projected embeddings', 'build an AltCLIPVisionModel from AltCLIPVisionConfig to encode images into visual embeddings', 'test AltCLIPModel get_text_features and get_image_features methods for embedding extraction']
```

Usage

```
{'create_AltCLIPModel': 'create an AltCLIPModel instance with text and vision configs for multimodal image-text retrieval', 'run_AltCLIPModel_forward': 'run the AltCLIPModel forward pass with text and image inputs to compute contrastive logits', 'build_AltCLIPTextModel': 'build an AltCLIPTextModel from AltCLIPTextConfig to encode text into projected embeddings', 'build_AltCLIPVisionModel': 'build an AltCLIPVisionModel from AltCLIPVisionConfig to encode images into visual embeddings', 'test_AltCLIPModel_get_features': 'test AltCLIPModel get_text_features and get_image_features methods for embedding extraction'}
```

