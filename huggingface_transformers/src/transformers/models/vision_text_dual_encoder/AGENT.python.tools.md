# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/vision_text_dual_encoder/configuration_vision_text_dual_encoder.py

Prompts

```
['create a VisionTextDualEncoderConfig from separate vision and text model configs with a projection dimension', 'create a VisionTextDualEncoderConfig by passing vision_config and text_config dicts with model types', 'test that VisionTextDualEncoderConfig raises ValueError when vision_config or text_config is missing', 'build a VisionTextDualEncoderConfig using CLIPVisionConfig as the vision model and BertConfig as the text model', 'review loading a VisionTextDualEncoderConfig from a pretrained directory via from_pretrained', 'build a VisionTextDualEncoderModel from pretrained vision and text models using from_vision_text_pretrained', 'create text features from input token IDs using the get_text_features method', 'create image features from pixel values using the get_image_features method', 'run the forward pass with return_loss to compute image-text contrastive training loss', 'test image-text similarity by computing cosine similarity logits from encoded embeddings']
```

Usage

```
{'create_VisionTextDualEncoderConfig_from_vision_text_configs': 'create a VisionTextDualEncoderConfig from separate vision and text model configs with a projection dimension', 'create_VisionTextDualEncoderConfig_directly': 'create a VisionTextDualEncoderConfig by passing vision_config and text_config dicts with model types', 'test_VisionTextDualEncoderConfig_missing_configs': 'test that VisionTextDualEncoderConfig raises ValueError when vision_config or text_config is missing', 'build_VisionTextDualEncoderConfig_with_clip': 'build a VisionTextDualEncoderConfig using CLIPVisionConfig as the vision model and BertConfig as the text model', 'review_VisionTextDualEncoderConfig_from_pretrained': 'review loading a VisionTextDualEncoderConfig from a pretrained directory via from_pretrained'}
```

## File: huggingface_transformers/src/transformers/models/vision_text_dual_encoder/modeling_vision_text_dual_encoder.py

Prompts

```
['create a VisionTextDualEncoderConfig from separate vision and text model configs with a projection dimension', 'create a VisionTextDualEncoderConfig by passing vision_config and text_config dicts with model types', 'test that VisionTextDualEncoderConfig raises ValueError when vision_config or text_config is missing', 'build a VisionTextDualEncoderConfig using CLIPVisionConfig as the vision model and BertConfig as the text model', 'review loading a VisionTextDualEncoderConfig from a pretrained directory via from_pretrained', 'build a VisionTextDualEncoderModel from pretrained vision and text models using from_vision_text_pretrained', 'create text features from input token IDs using the get_text_features method', 'create image features from pixel values using the get_image_features method', 'run the forward pass with return_loss to compute image-text contrastive training loss', 'test image-text similarity by computing cosine similarity logits from encoded embeddings']
```

Usage

```
{'build_vision_text_dual_encoder_model': 'build a VisionTextDualEncoderModel from pretrained vision and text models using from_vision_text_pretrained', 'create_get_text_features': 'create text features from input token IDs using the get_text_features method', 'create_get_image_features': 'create image features from pixel values using the get_image_features method', 'run_contrastive_loss': 'run the forward pass with return_loss to compute image-text contrastive training loss', 'test_image_text_similarity': 'test image-text similarity by computing cosine similarity logits from encoded embeddings'}
```

