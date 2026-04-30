# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/timm_wrapper/configuration_timm_wrapper.py

Prompts

```
['create a TimmWrapperConfig with a specified timm architecture like resnet50 or vit', 'build a TimmWrapperConfig from a dictionary including num_classes and pretrained_cfg', 'resolve imagenet label names automatically when loading a timm config without explicit labels', 'serialize a TimmWrapperConfig to dict converting id2label and label2id to label_names', 'configure whether TimmWrapperModel applies pooling to the last hidden state output', 'create a TimmWrapperImageProcessor instance from pretrained_cfg and architecture for timm model image preprocessing', 'preprocess a single or batch of images using TimmWrapperImageProcessor and return pixel_values tensor', 'serialize TimmWrapperImageProcessor to a dictionary using to_dict excluding transforms', 'get image processor configuration dict from pretrained model path using get_image_processor_dict', 'save TimmWrapperImageProcessor config by calling save_pretrained on the parent model', 'create a timm wrapper model for feature extraction with pooled output and hidden states', 'create a timm wrapper model for image classification with configurable number of labels', 'build a forward pass through a timm wrapper model using pixel values and optional pooling', 'test the timm wrapper model with hidden states output enabled via forward_intermediates', 'review the timm wrapper model gradient checkpointing support and initialization logic']
```

Usage

```
{'create_timm_config': 'create a TimmWrapperConfig with a specified timm architecture like resnet50 or vit', 'build_config_from_dict': 'build a TimmWrapperConfig from a dictionary including num_classes and pretrained_cfg', 'resolve_imagenet_labels': 'resolve imagenet label names automatically when loading a timm config without explicit labels', 'serialize_config_to_dict': 'serialize a TimmWrapperConfig to dict converting id2label and label2id to label_names', 'configure_model_pooling': 'configure whether TimmWrapperModel applies pooling to the last hidden state output'}
```

## File: huggingface_transformers/src/transformers/models/timm_wrapper/image_processing_timm_wrapper.py

Prompts

```
['create a TimmWrapperConfig with a specified timm architecture like resnet50 or vit', 'build a TimmWrapperConfig from a dictionary including num_classes and pretrained_cfg', 'resolve imagenet label names automatically when loading a timm config without explicit labels', 'serialize a TimmWrapperConfig to dict converting id2label and label2id to label_names', 'configure whether TimmWrapperModel applies pooling to the last hidden state output', 'create a TimmWrapperImageProcessor instance from pretrained_cfg and architecture for timm model image preprocessing', 'preprocess a single or batch of images using TimmWrapperImageProcessor and return pixel_values tensor', 'serialize TimmWrapperImageProcessor to a dictionary using to_dict excluding transforms', 'get image processor configuration dict from pretrained model path using get_image_processor_dict', 'save TimmWrapperImageProcessor config by calling save_pretrained on the parent model', 'create a timm wrapper model for feature extraction with pooled output and hidden states', 'create a timm wrapper model for image classification with configurable number of labels', 'build a forward pass through a timm wrapper model using pixel values and optional pooling', 'test the timm wrapper model with hidden states output enabled via forward_intermediates', 'review the timm wrapper model gradient checkpointing support and initialization logic']
```

Usage

```
{'create_TimmWrapperImageProcessor': 'create a TimmWrapperImageProcessor instance from pretrained_cfg and architecture for timm model image preprocessing', 'preprocess_images_timm': 'preprocess a single or batch of images using TimmWrapperImageProcessor and return pixel_values tensor', 'serialize_image_processor': 'serialize TimmWrapperImageProcessor to a dictionary using to_dict excluding transforms', 'get_image_processor_dict': 'get image processor configuration dict from pretrained model path using get_image_processor_dict', 'save_image_processor_config': 'save TimmWrapperImageProcessor config by calling save_pretrained on the parent model'}
```

## File: huggingface_transformers/src/transformers/models/timm_wrapper/modeling_timm_wrapper.py

Prompts

```
['create a TimmWrapperConfig with a specified timm architecture like resnet50 or vit', 'build a TimmWrapperConfig from a dictionary including num_classes and pretrained_cfg', 'resolve imagenet label names automatically when loading a timm config without explicit labels', 'serialize a TimmWrapperConfig to dict converting id2label and label2id to label_names', 'configure whether TimmWrapperModel applies pooling to the last hidden state output', 'create a TimmWrapperImageProcessor instance from pretrained_cfg and architecture for timm model image preprocessing', 'preprocess a single or batch of images using TimmWrapperImageProcessor and return pixel_values tensor', 'serialize TimmWrapperImageProcessor to a dictionary using to_dict excluding transforms', 'get image processor configuration dict from pretrained model path using get_image_processor_dict', 'save TimmWrapperImageProcessor config by calling save_pretrained on the parent model', 'create a timm wrapper model for feature extraction with pooled output and hidden states', 'create a timm wrapper model for image classification with configurable number of labels', 'build a forward pass through a timm wrapper model using pixel values and optional pooling', 'test the timm wrapper model with hidden states output enabled via forward_intermediates', 'review the timm wrapper model gradient checkpointing support and initialization logic']
```

Usage

```
{'create_timm_feature_extractor': 'create a timm wrapper model for feature extraction with pooled output and hidden states', 'create_image_classifier': 'create a timm wrapper model for image classification with configurable number of labels', 'build_timm_forward_pass': 'build a forward pass through a timm wrapper model using pixel values and optional pooling', 'test_hidden_states_output': 'test the timm wrapper model with hidden states output enabled via forward_intermediates', 'review_gradient_checkpointing': 'review the timm wrapper model gradient checkpointing support and initialization logic'}
```

