# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/bit/configuration_bit.py

Prompts

```
['create a BitConfig instance with default BiT model settings for google/bit-50', 'initialize BitConfig with custom layer_type, hidden_sizes, and depth parameters', 'validate BitConfig architecture by checking layer_type and global_padding values', 'configure BitConfig backbone output features and output indices via set_output_features_output_indices', 'customize BitConfig parameters including num_groups, drop_path_rate, and width_factor', 'convert a BiT timm checkpoint to HuggingFace PyTorch format and save to a local directory', 'get a BitConfig for a BiT model with ImageNet-1k label mappings and conv layer settings', 'rename a timm state dict key to match the HuggingFace BiT model naming convention', 'create a BitImageProcessor configured with timm transforms for image preprocessing', 'push a converted BiT model and processor to the HuggingFace Hub under a specified user', 'create a BiT image feature extractor model from a BitConfig for backbone or classification', 'build a BiT model with image classification head for ImageNet-style label prediction', 'build a BiT backbone model to extract multi-scale feature maps for DETR and MaskFormer', 'review the BiT encoder composed of stacked stages with residual bottleneck blocks', 'review the BiT embedding stem with weight-standardized convolution and pooling']
```

Usage

```
{'create_BitConfig': 'create a BitConfig instance with default BiT model settings for google/bit-50', 'initialize_BitConfig_custom': 'initialize BitConfig with custom layer_type, hidden_sizes, and depth parameters', 'validate_BitConfig_architecture': 'validate BitConfig architecture by checking layer_type and global_padding values', 'configure_BitConfig_backbone': 'configure BitConfig backbone output features and output indices via set_output_features_output_indices', 'customize_BitConfig_parameters': 'customize BitConfig parameters including num_groups, drop_path_rate, and width_factor'}
```

## File: huggingface_transformers/src/transformers/models/bit/convert_bit_to_pytorch.py

Prompts

```
['create a BitConfig instance with default BiT model settings for google/bit-50', 'initialize BitConfig with custom layer_type, hidden_sizes, and depth parameters', 'validate BitConfig architecture by checking layer_type and global_padding values', 'configure BitConfig backbone output features and output indices via set_output_features_output_indices', 'customize BitConfig parameters including num_groups, drop_path_rate, and width_factor', 'convert a BiT timm checkpoint to HuggingFace PyTorch format and save to a local directory', 'get a BitConfig for a BiT model with ImageNet-1k label mappings and conv layer settings', 'rename a timm state dict key to match the HuggingFace BiT model naming convention', 'create a BitImageProcessor configured with timm transforms for image preprocessing', 'push a converted BiT model and processor to the HuggingFace Hub under a specified user', 'create a BiT image feature extractor model from a BitConfig for backbone or classification', 'build a BiT model with image classification head for ImageNet-style label prediction', 'build a BiT backbone model to extract multi-scale feature maps for DETR and MaskFormer', 'review the BiT encoder composed of stacked stages with residual bottleneck blocks', 'review the BiT embedding stem with weight-standardized convolution and pooling']
```

Usage

```
{'convert_bit_checkpoint': 'convert a BiT timm checkpoint to HuggingFace PyTorch format and save to a local directory', 'get_config_bit_model': 'get a BitConfig for a BiT model with ImageNet-1k label mappings and conv layer settings', 'rename_key_timm_to_hf': 'rename a timm state dict key to match the HuggingFace BiT model naming convention', 'create_bit_image_processor': 'create a BitImageProcessor configured with timm transforms for image preprocessing', 'push_bit_model_to_hub': 'push a converted BiT model and processor to the HuggingFace Hub under a specified user'}
```

## File: huggingface_transformers/src/transformers/models/bit/modeling_bit.py

Prompts

```
['create a BitConfig instance with default BiT model settings for google/bit-50', 'initialize BitConfig with custom layer_type, hidden_sizes, and depth parameters', 'validate BitConfig architecture by checking layer_type and global_padding values', 'configure BitConfig backbone output features and output indices via set_output_features_output_indices', 'customize BitConfig parameters including num_groups, drop_path_rate, and width_factor', 'convert a BiT timm checkpoint to HuggingFace PyTorch format and save to a local directory', 'get a BitConfig for a BiT model with ImageNet-1k label mappings and conv layer settings', 'rename a timm state dict key to match the HuggingFace BiT model naming convention', 'create a BitImageProcessor configured with timm transforms for image preprocessing', 'push a converted BiT model and processor to the HuggingFace Hub under a specified user', 'create a BiT image feature extractor model from a BitConfig for backbone or classification', 'build a BiT model with image classification head for ImageNet-style label prediction', 'build a BiT backbone model to extract multi-scale feature maps for DETR and MaskFormer', 'review the BiT encoder composed of stacked stages with residual bottleneck blocks', 'review the BiT embedding stem with weight-standardized convolution and pooling']
```

Usage

```
{'create_bit_model': 'create a BiT image feature extractor model from a BitConfig for backbone or classification', 'build_image_classifier': 'build a BiT model with image classification head for ImageNet-style label prediction', 'build_backbone': 'build a BiT backbone model to extract multi-scale feature maps for DETR and MaskFormer', 'review_bit_encoder': 'review the BiT encoder composed of stacked stages with residual bottleneck blocks', 'review_bit_embeddings': 'review the BiT embedding stem with weight-standardized convolution and pooling'}
```

