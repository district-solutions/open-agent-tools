# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/dinov3_convnext/configuration_dinov3_convnext.py

Prompts

```
['create a DINOv3ConvNextConfig instance with default architecture settings for the ConvNeXT backbone model', 'initialize a DINOv3ConvNextModel with a DINOv3ConvNextConfig for random-weight model instantiation', 'set custom hidden_sizes and depths values on a DINOv3ConvNextConfig to define the model layer architecture', 'configure out_indices and out_features on a DINOv3ConvNextConfig via kwargs for multi-stage feature extraction', 'get the number of stages from a DINOv3ConvNextConfig by reading the num_stages property', "convert a DINOv3 ConvNeXt checkpoint from Facebook's repository to Hugging Face Transformers format", 'run the DINOv3 ConvNeXt checkpoint conversion script via argparse CLI with model name and save directory', 'create a DINOv3 ConvNeXt config object for a given model variant such as convnext_tiny or convnext_large', 'test the DINOv3 ConvNeXt checkpoint conversion by verifying preprocessing and forward pass outputs match expected values', 'create a key renaming function that maps original checkpoint state dict keys to Hugging Face Transformers key format using regex patterns', 'build a DINOv3ConvNextModel forward pass that takes pixel values and returns pooled output with patch tokens', 'create a DINOv3ConvNextBackbone that extracts multi-stage feature maps from image pixel values', 'test the drop_path function applies stochastic depth regularization during training mode', 'refactor DINOv3ConvNextLayerNorm to support both channels_first and channels_last tensor formats', 'summarize the DINOv3ConvNextEncoder stages pipeline that processes hidden states through each stage']
```

Usage

```
{'create_dinov3_config': 'create a DINOv3ConvNextConfig instance with default architecture settings for the ConvNeXT backbone model', 'initialize_model_with_config': 'initialize a DINOv3ConvNextModel with a DINOv3ConvNextConfig for random-weight model instantiation', 'set_hidden_sizes_and_depths': 'set custom hidden_sizes and depths values on a DINOv3ConvNextConfig to define the model layer architecture', 'configure_output_features': 'configure out_indices and out_features on a DINOv3ConvNextConfig via kwargs for multi-stage feature extraction', 'get_num_stages': 'get the number of stages from a DINOv3ConvNextConfig by reading the num_stages property'}
```

## File: huggingface_transformers/src/transformers/models/dinov3_convnext/convert_dinov3_convnext_to_hf.py

Prompts

```
['create a DINOv3ConvNextConfig instance with default architecture settings for the ConvNeXT backbone model', 'initialize a DINOv3ConvNextModel with a DINOv3ConvNextConfig for random-weight model instantiation', 'set custom hidden_sizes and depths values on a DINOv3ConvNextConfig to define the model layer architecture', 'configure out_indices and out_features on a DINOv3ConvNextConfig via kwargs for multi-stage feature extraction', 'get the number of stages from a DINOv3ConvNextConfig by reading the num_stages property', "convert a DINOv3 ConvNeXt checkpoint from Facebook's repository to Hugging Face Transformers format", 'run the DINOv3 ConvNeXt checkpoint conversion script via argparse CLI with model name and save directory', 'create a DINOv3 ConvNeXt config object for a given model variant such as convnext_tiny or convnext_large', 'test the DINOv3 ConvNeXt checkpoint conversion by verifying preprocessing and forward pass outputs match expected values', 'create a key renaming function that maps original checkpoint state dict keys to Hugging Face Transformers key format using regex patterns', 'build a DINOv3ConvNextModel forward pass that takes pixel values and returns pooled output with patch tokens', 'create a DINOv3ConvNextBackbone that extracts multi-stage feature maps from image pixel values', 'test the drop_path function applies stochastic depth regularization during training mode', 'refactor DINOv3ConvNextLayerNorm to support both channels_first and channels_last tensor formats', 'summarize the DINOv3ConvNextEncoder stages pipeline that processes hidden states through each stage']
```

Usage

```
{'build_convert_dinov3_checkpoint': "convert a DINOv3 ConvNeXt checkpoint from Facebook's repository to Hugging Face Transformers format", 'run_convert_dinov3_checkpoint_cli': 'run the DINOv3 ConvNeXt checkpoint conversion script via argparse CLI with model name and save directory', 'create_get_dinov3_config': 'create a DINOv3 ConvNeXt config object for a given model variant such as convnext_tiny or convnext_large', 'test_convert_dinov3_checkpoint': 'test the DINOv3 ConvNeXt checkpoint conversion by verifying preprocessing and forward pass outputs match expected values', 'create_convert_old_keys_to_new_keys': 'create a key renaming function that maps original checkpoint state dict keys to Hugging Face Transformers key format using regex patterns'}
```

## File: huggingface_transformers/src/transformers/models/dinov3_convnext/modeling_dinov3_convnext.py

Prompts

```
['create a DINOv3ConvNextConfig instance with default architecture settings for the ConvNeXT backbone model', 'initialize a DINOv3ConvNextModel with a DINOv3ConvNextConfig for random-weight model instantiation', 'set custom hidden_sizes and depths values on a DINOv3ConvNextConfig to define the model layer architecture', 'configure out_indices and out_features on a DINOv3ConvNextConfig via kwargs for multi-stage feature extraction', 'get the number of stages from a DINOv3ConvNextConfig by reading the num_stages property', "convert a DINOv3 ConvNeXt checkpoint from Facebook's repository to Hugging Face Transformers format", 'run the DINOv3 ConvNeXt checkpoint conversion script via argparse CLI with model name and save directory', 'create a DINOv3 ConvNeXt config object for a given model variant such as convnext_tiny or convnext_large', 'test the DINOv3 ConvNeXt checkpoint conversion by verifying preprocessing and forward pass outputs match expected values', 'create a key renaming function that maps original checkpoint state dict keys to Hugging Face Transformers key format using regex patterns', 'build a DINOv3ConvNextModel forward pass that takes pixel values and returns pooled output with patch tokens', 'create a DINOv3ConvNextBackbone that extracts multi-stage feature maps from image pixel values', 'test the drop_path function applies stochastic depth regularization during training mode', 'refactor DINOv3ConvNextLayerNorm to support both channels_first and channels_last tensor formats', 'summarize the DINOv3ConvNextEncoder stages pipeline that processes hidden states through each stage']
```

Usage

```
{'build_model_forward_pass': 'build a DINOv3ConvNextModel forward pass that takes pixel values and returns pooled output with patch tokens', 'create_backbone_feature_maps': 'create a DINOv3ConvNextBackbone that extracts multi-stage feature maps from image pixel values', 'test_drop_path_stochastic': 'test the drop_path function applies stochastic depth regularization during training mode', 'refactor_layer_norm_format': 'refactor DINOv3ConvNextLayerNorm to support both channels_first and channels_last tensor formats', 'summarize_encoder_stages': 'summarize the DINOv3ConvNextEncoder stages pipeline that processes hidden states through each stage'}
```

