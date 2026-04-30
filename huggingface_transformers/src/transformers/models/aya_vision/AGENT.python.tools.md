# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/aya_vision/configuration_aya_vision.py

Prompts

```
['create an AyaVisionConfig instance with default vision and text sub-configs for the Cohere Aya Vision model', 'create an AyaVisionConfig from a dictionary specifying vision_config and text_config parameters', "validate the AyaVisionConfig architecture ensuring vision_feature_select_strategy is 'default' or 'full'", 'build an AyaVisionConfig with a custom siglip_vision_model config for vision_feature_layer and downsample_factor', 'review the AyaVisionConfig class attributes including image_token_index, tie_word_embeddings, and adapter_layer_norm_eps', 'build an AyaVisionForConditionalGeneration model for multimodal image-and-text language generation', 'create an AyaVisionModel that combines a vision backbone with a text language model for multimodal understanding', 'run text generation on AyaVisionForConditionalGeneration with input images and chat messages', 'test the AyaVisionModel.get_image_features method to extract and project visual features from pixel values', 'review the AyaVisionMultiModalProjector class that downsamples and projects image features into text embedding space', 'build an AyaVision multi-modal projector that applies SwiGLU and pixel-shuffle to align vision features with text embeddings', 'create image features from pixel values using the vision tower and multi-modal projector in AyaVisionModel', 'run the AyaVisionModel forward pass to combine text input embeddings with image features for multi-modal understanding', 'generate text conditioned on images using AyaVisionForConditionalGeneration with chat templates and token generation', 'test the AyaVisionPreTrainedModel base class that extends LlavaPreTrainedModel with compile graph disabled']
```

Usage

```
{'create_aya_vision_config': 'create an AyaVisionConfig instance with default vision and text sub-configs for the Cohere Aya Vision model', 'create_aya_vision_config_with_dict': 'create an AyaVisionConfig from a dictionary specifying vision_config and text_config parameters', 'validate_aya_vision_architecture': "validate the AyaVisionConfig architecture ensuring vision_feature_select_strategy is 'default' or 'full'", 'build_aya_vision_config_custom_vision': 'build an AyaVisionConfig with a custom siglip_vision_model config for vision_feature_layer and downsample_factor', 'review_aya_vision_config_attributes': 'review the AyaVisionConfig class attributes including image_token_index, tie_word_embeddings, and adapter_layer_norm_eps'}
```

## File: huggingface_transformers/src/transformers/models/aya_vision/modeling_aya_vision.py

Prompts

```
['create an AyaVisionConfig instance with default vision and text sub-configs for the Cohere Aya Vision model', 'create an AyaVisionConfig from a dictionary specifying vision_config and text_config parameters', "validate the AyaVisionConfig architecture ensuring vision_feature_select_strategy is 'default' or 'full'", 'build an AyaVisionConfig with a custom siglip_vision_model config for vision_feature_layer and downsample_factor', 'review the AyaVisionConfig class attributes including image_token_index, tie_word_embeddings, and adapter_layer_norm_eps', 'build an AyaVisionForConditionalGeneration model for multimodal image-and-text language generation', 'create an AyaVisionModel that combines a vision backbone with a text language model for multimodal understanding', 'run text generation on AyaVisionForConditionalGeneration with input images and chat messages', 'test the AyaVisionModel.get_image_features method to extract and project visual features from pixel values', 'review the AyaVisionMultiModalProjector class that downsamples and projects image features into text embedding space', 'build an AyaVision multi-modal projector that applies SwiGLU and pixel-shuffle to align vision features with text embeddings', 'create image features from pixel values using the vision tower and multi-modal projector in AyaVisionModel', 'run the AyaVisionModel forward pass to combine text input embeddings with image features for multi-modal understanding', 'generate text conditioned on images using AyaVisionForConditionalGeneration with chat templates and token generation', 'test the AyaVisionPreTrainedModel base class that extends LlavaPreTrainedModel with compile graph disabled']
```

Usage

```
{'build_aya_vision_conditional_generation': 'build an AyaVisionForConditionalGeneration model for multimodal image-and-text language generation', 'create_aya_vision_model': 'create an AyaVisionModel that combines a vision backbone with a text language model for multimodal understanding', 'run_aya_vision_generate': 'run text generation on AyaVisionForConditionalGeneration with input images and chat messages', 'test_aya_vision_get_image_features': 'test the AyaVisionModel.get_image_features method to extract and project visual features from pixel values', 'review_aya_vision_multimodal_projector': 'review the AyaVisionMultiModalProjector class that downsamples and projects image features into text embedding space'}
```

## File: huggingface_transformers/src/transformers/models/aya_vision/modular_aya_vision.py

Prompts

```
['create an AyaVisionConfig instance with default vision and text sub-configs for the Cohere Aya Vision model', 'create an AyaVisionConfig from a dictionary specifying vision_config and text_config parameters', "validate the AyaVisionConfig architecture ensuring vision_feature_select_strategy is 'default' or 'full'", 'build an AyaVisionConfig with a custom siglip_vision_model config for vision_feature_layer and downsample_factor', 'review the AyaVisionConfig class attributes including image_token_index, tie_word_embeddings, and adapter_layer_norm_eps', 'build an AyaVisionForConditionalGeneration model for multimodal image-and-text language generation', 'create an AyaVisionModel that combines a vision backbone with a text language model for multimodal understanding', 'run text generation on AyaVisionForConditionalGeneration with input images and chat messages', 'test the AyaVisionModel.get_image_features method to extract and project visual features from pixel values', 'review the AyaVisionMultiModalProjector class that downsamples and projects image features into text embedding space', 'build an AyaVision multi-modal projector that applies SwiGLU and pixel-shuffle to align vision features with text embeddings', 'create image features from pixel values using the vision tower and multi-modal projector in AyaVisionModel', 'run the AyaVisionModel forward pass to combine text input embeddings with image features for multi-modal understanding', 'generate text conditioned on images using AyaVisionForConditionalGeneration with chat templates and token generation', 'test the AyaVisionPreTrainedModel base class that extends LlavaPreTrainedModel with compile graph disabled']
```

Usage

```
{'build_aya_vision_model': 'build an AyaVision multi-modal projector that applies SwiGLU and pixel-shuffle to align vision features with text embeddings', 'create_aya_vision_get_image_features': 'create image features from pixel values using the vision tower and multi-modal projector in AyaVisionModel', 'run_aya_vision_forward': 'run the AyaVisionModel forward pass to combine text input embeddings with image features for multi-modal understanding', 'generate_aya_vision_conditional': 'generate text conditioned on images using AyaVisionForConditionalGeneration with chat templates and token generation', 'test_aya_vision_pretrained': 'test the AyaVisionPreTrainedModel base class that extends LlavaPreTrainedModel with compile graph disabled'}
```

