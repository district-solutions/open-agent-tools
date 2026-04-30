# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/regnet/configuration_regnet.py

Prompts

```
['create a RegNetConfig instance with default architecture settings for a RegNet model', 'create a RegNetConfig with custom hidden_sizes, depths, and layer_type parameters', 'validate the RegNetConfig architecture by checking layer_type against allowed values', 'initialize a RegNetModel using a RegNetConfig configuration object', 'access the configuration from an instantiated RegNetModel via the config attribute', 'convert RegNet 10B SEER checkpoints from Vissl to HuggingFace PyTorch format and push to hub', 'run the CLI script to convert a RegNet 10B SEER model checkpoint to PyTorch format', 'build a key mapping dictionary between Vissl RegNet state dict keys and HuggingFace RegNet keys', 'trace a RegNet model to collect parametrized modules and their state dict keys via forward hooks', 'create a fake Vissl RegNet wrapper that extracts feature blocks without a config file', 'convert RegNet model weights from timm or vissl checkpoints into Hugging Face transformers format', 'run the RegNet conversion script via CLI to convert a single or all supported RegNet models', 'transfer trained weights from a source PyTorch module to a destination module by tracing forward passes', 'push converted RegNet model weights and image processor to the Hugging Face model hub', 'build a RegNetConfig with specified depths, hidden sizes, and group widths for any supported RegNet variant', 'build a RegNetModel for feature extraction with configurable embedding size and hidden stages', 'create a RegNetForImageClassification model with a linear classification head for ImageNet', 'test the RegNetModel forward pass with pixel values and output hidden states', 'review the RegNetSELayer squeeze and excitation attention mechanism', 'summarize the RegNetEncoder stage composition and residual shortcut logic']
```

Usage

```
{'create_regnet_config': 'create a RegNetConfig instance with default architecture settings for a RegNet model', 'create_regnet_config_custom': 'create a RegNetConfig with custom hidden_sizes, depths, and layer_type parameters', 'validate_regnet_architecture': 'validate the RegNetConfig architecture by checking layer_type against allowed values', 'initialize_regnet_model': 'initialize a RegNetModel using a RegNetConfig configuration object', 'access_regnet_model_config': 'access the configuration from an instantiated RegNetModel via the config attribute'}
```

## File: huggingface_transformers/src/transformers/models/regnet/convert_regnet_seer_10b_to_pytorch.py

Prompts

```
['create a RegNetConfig instance with default architecture settings for a RegNet model', 'create a RegNetConfig with custom hidden_sizes, depths, and layer_type parameters', 'validate the RegNetConfig architecture by checking layer_type against allowed values', 'initialize a RegNetModel using a RegNetConfig configuration object', 'access the configuration from an instantiated RegNetModel via the config attribute', 'convert RegNet 10B SEER checkpoints from Vissl to HuggingFace PyTorch format and push to hub', 'run the CLI script to convert a RegNet 10B SEER model checkpoint to PyTorch format', 'build a key mapping dictionary between Vissl RegNet state dict keys and HuggingFace RegNet keys', 'trace a RegNet model to collect parametrized modules and their state dict keys via forward hooks', 'create a fake Vissl RegNet wrapper that extracts feature blocks without a config file', 'convert RegNet model weights from timm or vissl checkpoints into Hugging Face transformers format', 'run the RegNet conversion script via CLI to convert a single or all supported RegNet models', 'transfer trained weights from a source PyTorch module to a destination module by tracing forward passes', 'push converted RegNet model weights and image processor to the Hugging Face model hub', 'build a RegNetConfig with specified depths, hidden sizes, and group widths for any supported RegNet variant', 'build a RegNetModel for feature extraction with configurable embedding size and hidden stages', 'create a RegNetForImageClassification model with a linear classification head for ImageNet', 'test the RegNetModel forward pass with pixel values and output hidden states', 'review the RegNetSELayer squeeze and excitation attention mechanism', 'summarize the RegNetEncoder stage composition and residual shortcut logic']
```

Usage

```
{'convert_regnet_seer_weights': 'convert RegNet 10B SEER checkpoints from Vissl to HuggingFace PyTorch format and push to hub', 'run_convert_cli': 'run the CLI script to convert a RegNet 10B SEER model checkpoint to PyTorch format', 'build_key_mapping': 'build a key mapping dictionary between Vissl RegNet state dict keys and HuggingFace RegNet keys', 'trace_model_modules': 'trace a RegNet model to collect parametrized modules and their state dict keys via forward hooks', 'create_fake_regnet_wrapper': 'create a fake Vissl RegNet wrapper that extracts feature blocks without a config file'}
```

## File: huggingface_transformers/src/transformers/models/regnet/convert_regnet_to_pytorch.py

Prompts

```
['create a RegNetConfig instance with default architecture settings for a RegNet model', 'create a RegNetConfig with custom hidden_sizes, depths, and layer_type parameters', 'validate the RegNetConfig architecture by checking layer_type against allowed values', 'initialize a RegNetModel using a RegNetConfig configuration object', 'access the configuration from an instantiated RegNetModel via the config attribute', 'convert RegNet 10B SEER checkpoints from Vissl to HuggingFace PyTorch format and push to hub', 'run the CLI script to convert a RegNet 10B SEER model checkpoint to PyTorch format', 'build a key mapping dictionary between Vissl RegNet state dict keys and HuggingFace RegNet keys', 'trace a RegNet model to collect parametrized modules and their state dict keys via forward hooks', 'create a fake Vissl RegNet wrapper that extracts feature blocks without a config file', 'convert RegNet model weights from timm or vissl checkpoints into Hugging Face transformers format', 'run the RegNet conversion script via CLI to convert a single or all supported RegNet models', 'transfer trained weights from a source PyTorch module to a destination module by tracing forward passes', 'push converted RegNet model weights and image processor to the Hugging Face model hub', 'build a RegNetConfig with specified depths, hidden sizes, and group widths for any supported RegNet variant', 'build a RegNetModel for feature extraction with configurable embedding size and hidden stages', 'create a RegNetForImageClassification model with a linear classification head for ImageNet', 'test the RegNetModel forward pass with pixel values and output hidden states', 'review the RegNetSELayer squeeze and excitation attention mechanism', 'summarize the RegNetEncoder stage composition and residual shortcut logic']
```

Usage

```
{'convert_regnet_weights': 'convert RegNet model weights from timm or vissl checkpoints into Hugging Face transformers format', 'run_regnet_conversion_cli': 'run the RegNet conversion script via CLI to convert a single or all supported RegNet models', 'transfer_module_weights': 'transfer trained weights from a source PyTorch module to a destination module by tracing forward passes', 'push_regnet_to_hub': 'push converted RegNet model weights and image processor to the Hugging Face model hub', 'build_regnet_config': 'build a RegNetConfig with specified depths, hidden sizes, and group widths for any supported RegNet variant'}
```

## File: huggingface_transformers/src/transformers/models/regnet/modeling_regnet.py

Prompts

```
['create a RegNetConfig instance with default architecture settings for a RegNet model', 'create a RegNetConfig with custom hidden_sizes, depths, and layer_type parameters', 'validate the RegNetConfig architecture by checking layer_type against allowed values', 'initialize a RegNetModel using a RegNetConfig configuration object', 'access the configuration from an instantiated RegNetModel via the config attribute', 'convert RegNet 10B SEER checkpoints from Vissl to HuggingFace PyTorch format and push to hub', 'run the CLI script to convert a RegNet 10B SEER model checkpoint to PyTorch format', 'build a key mapping dictionary between Vissl RegNet state dict keys and HuggingFace RegNet keys', 'trace a RegNet model to collect parametrized modules and their state dict keys via forward hooks', 'create a fake Vissl RegNet wrapper that extracts feature blocks without a config file', 'convert RegNet model weights from timm or vissl checkpoints into Hugging Face transformers format', 'run the RegNet conversion script via CLI to convert a single or all supported RegNet models', 'transfer trained weights from a source PyTorch module to a destination module by tracing forward passes', 'push converted RegNet model weights and image processor to the Hugging Face model hub', 'build a RegNetConfig with specified depths, hidden sizes, and group widths for any supported RegNet variant', 'build a RegNetModel for feature extraction with configurable embedding size and hidden stages', 'create a RegNetForImageClassification model with a linear classification head for ImageNet', 'test the RegNetModel forward pass with pixel values and output hidden states', 'review the RegNetSELayer squeeze and excitation attention mechanism', 'summarize the RegNetEncoder stage composition and residual shortcut logic']
```

Usage

```
{'build_regnet_model': 'build a RegNetModel for feature extraction with configurable embedding size and hidden stages', 'create_regnet_classification': 'create a RegNetForImageClassification model with a linear classification head for ImageNet', 'test_regnet_forward': 'test the RegNetModel forward pass with pixel values and output hidden states', 'review_regnet_se_layer': 'review the RegNetSELayer squeeze and excitation attention mechanism', 'summarize_regnet_encoder': 'summarize the RegNetEncoder stage composition and residual shortcut logic'}
```

