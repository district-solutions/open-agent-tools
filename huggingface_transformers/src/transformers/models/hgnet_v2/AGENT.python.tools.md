# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/hgnet_v2/configuration_hgnet_v2.py

Prompts

```
['create an HGNetV2Config instance with default backbone architecture parameters', 'create an HGNetV2Config with custom stage channels, block counts, and kernel sizes', 'validate that all HGNetV2Config stage configuration lists have matching lengths', 'build an HGNetV2 backbone model using HGNetV2Config for architecture definition', 'configure HGNetV2Config output features and output indices for feature extraction', 'create an HGNetV2Backbone model with configurable stem and stage layers for feature extraction', 'create an HGNetV2ForImageClassification model with a classification head for image classification tasks', 'build an HGNetV2Encoder with multiple stages, each containing basic layers and aggregation blocks', 'test the HGNetV2Embeddings stem pipeline that processes pixel values through convolutional layers', 'review the HGNetV2BasicLayer with residual connections, light blocks, and feature aggregation', 'create an HGNetV2 backbone model for feature extraction with configurable stem and stage channels', 'build an HGNetV2 image classification model with a linear head on top of the backbone encoder', 'configure HGNetV2 architecture with custom stem channels, stage depths, kernel sizes, and light blocks', 'run a forward pass through HGNetV2 backbone to extract multi-scale feature maps from pixel values', 'test HGNetV2 image classification model with labeled data and compute cross-entropy loss']
```

Usage

```
{'create_hgnetv2_config': 'create an HGNetV2Config instance with default backbone architecture parameters', 'create_hgnetv2_custom_config': 'create an HGNetV2Config with custom stage channels, block counts, and kernel sizes', 'validate_hgnetv2_architecture': 'validate that all HGNetV2Config stage configuration lists have matching lengths', 'build_hgnetv2_backbone': 'build an HGNetV2 backbone model using HGNetV2Config for architecture definition', 'configure_hgnetv2_output_features': 'configure HGNetV2Config output features and output indices for feature extraction'}
```

## File: huggingface_transformers/src/transformers/models/hgnet_v2/modeling_hgnet_v2.py

Prompts

```
['create an HGNetV2Config instance with default backbone architecture parameters', 'create an HGNetV2Config with custom stage channels, block counts, and kernel sizes', 'validate that all HGNetV2Config stage configuration lists have matching lengths', 'build an HGNetV2 backbone model using HGNetV2Config for architecture definition', 'configure HGNetV2Config output features and output indices for feature extraction', 'create an HGNetV2Backbone model with configurable stem and stage layers for feature extraction', 'create an HGNetV2ForImageClassification model with a classification head for image classification tasks', 'build an HGNetV2Encoder with multiple stages, each containing basic layers and aggregation blocks', 'test the HGNetV2Embeddings stem pipeline that processes pixel values through convolutional layers', 'review the HGNetV2BasicLayer with residual connections, light blocks, and feature aggregation', 'create an HGNetV2 backbone model for feature extraction with configurable stem and stage channels', 'build an HGNetV2 image classification model with a linear head on top of the backbone encoder', 'configure HGNetV2 architecture with custom stem channels, stage depths, kernel sizes, and light blocks', 'run a forward pass through HGNetV2 backbone to extract multi-scale feature maps from pixel values', 'test HGNetV2 image classification model with labeled data and compute cross-entropy loss']
```

Usage

```
{'create_model_backbone': 'create an HGNetV2Backbone model with configurable stem and stage layers for feature extraction', 'create_image_classifier': 'create an HGNetV2ForImageClassification model with a classification head for image classification tasks', 'build_encoder_stages': 'build an HGNetV2Encoder with multiple stages, each containing basic layers and aggregation blocks', 'test_embedding_stem': 'test the HGNetV2Embeddings stem pipeline that processes pixel values through convolutional layers', 'review_basic_layer': 'review the HGNetV2BasicLayer with residual connections, light blocks, and feature aggregation'}
```

## File: huggingface_transformers/src/transformers/models/hgnet_v2/modular_hgnet_v2.py

Prompts

```
['create an HGNetV2Config instance with default backbone architecture parameters', 'create an HGNetV2Config with custom stage channels, block counts, and kernel sizes', 'validate that all HGNetV2Config stage configuration lists have matching lengths', 'build an HGNetV2 backbone model using HGNetV2Config for architecture definition', 'configure HGNetV2Config output features and output indices for feature extraction', 'create an HGNetV2Backbone model with configurable stem and stage layers for feature extraction', 'create an HGNetV2ForImageClassification model with a classification head for image classification tasks', 'build an HGNetV2Encoder with multiple stages, each containing basic layers and aggregation blocks', 'test the HGNetV2Embeddings stem pipeline that processes pixel values through convolutional layers', 'review the HGNetV2BasicLayer with residual connections, light blocks, and feature aggregation', 'create an HGNetV2 backbone model for feature extraction with configurable stem and stage channels', 'build an HGNetV2 image classification model with a linear head on top of the backbone encoder', 'configure HGNetV2 architecture with custom stem channels, stage depths, kernel sizes, and light blocks', 'run a forward pass through HGNetV2 backbone to extract multi-scale feature maps from pixel values', 'test HGNetV2 image classification model with labeled data and compute cross-entropy loss']
```

Usage

```
{'create_hgnetv2_backbone': 'create an HGNetV2 backbone model for feature extraction with configurable stem and stage channels', 'build_hgnetv2_classifier': 'build an HGNetV2 image classification model with a linear head on top of the backbone encoder', 'configure_hgnetv2_architecture': 'configure HGNetV2 architecture with custom stem channels, stage depths, kernel sizes, and light blocks', 'run_hgnetv2_forward_pass': 'run a forward pass through HGNetV2 backbone to extract multi-scale feature maps from pixel values', 'test_hgnetv2_classification': 'test HGNetV2 image classification model with labeled data and compute cross-entropy loss'}
```

