# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/resnet/configuration_resnet.py

Prompts

```
['create a ResNetConfig instance with default resnet-50 style configuration', 'create a ResNetConfig with custom layer_type, hidden_sizes, and depths parameters', 'validate the layer_type attribute of a ResNetConfig is basic or bottleneck', 'create a ResNetConfig and initialize stage_names from depths array', 'create a ResNetConfig with out_indices and out_features for output feature selection', 'convert a ResNet model from timm pretrained weights to a Hugging Face ResNetForImageClassification model', 'convert a single ResNet model (resnet18, resnet26, resnet34, resnet50, resnet101, or resnet152) from timm to Hugging Face', 'convert all supported ResNet models (resnet18, resnet26, resnet34, resnet50, resnet101, resnet152) from timm to Hugging Face', 'transfer weights from a source PyTorch module to a destination module by tracing and matching parametrized operations', 'push a converted ResNet model and its image processor to the Hugging Face Hub', 'create a ResNet image feature extractor model with configurable stages and bottleneck layers', 'build a ResNet image classification model with a linear head on top of pooled features', 'build a ResNet backbone model to extract multi-scale feature maps for DETR and MaskFormer', 'test the ResNet encoder that stacks stages with residual connections and hidden state tracking', 'review the ResNet forward pass that applies embeddings, encoder stages, and adaptive pooling']
```

Usage

```
{'create_ResNetConfig': 'create a ResNetConfig instance with default resnet-50 style configuration', 'create_ResNetConfig_custom': 'create a ResNetConfig with custom layer_type, hidden_sizes, and depths parameters', 'validate_ResNetConfig_layer_type': 'validate the layer_type attribute of a ResNetConfig is basic or bottleneck', 'create_ResNetConfig_stem_stages': 'create a ResNetConfig and initialize stage_names from depths array', 'create_ResNetConfig_output_features': 'create a ResNetConfig with out_indices and out_features for output feature selection'}
```

## File: huggingface_transformers/src/transformers/models/resnet/convert_resnet_to_pytorch.py

Prompts

```
['create a ResNetConfig instance with default resnet-50 style configuration', 'create a ResNetConfig with custom layer_type, hidden_sizes, and depths parameters', 'validate the layer_type attribute of a ResNetConfig is basic or bottleneck', 'create a ResNetConfig and initialize stage_names from depths array', 'create a ResNetConfig with out_indices and out_features for output feature selection', 'convert a ResNet model from timm pretrained weights to a Hugging Face ResNetForImageClassification model', 'convert a single ResNet model (resnet18, resnet26, resnet34, resnet50, resnet101, or resnet152) from timm to Hugging Face', 'convert all supported ResNet models (resnet18, resnet26, resnet34, resnet50, resnet101, resnet152) from timm to Hugging Face', 'transfer weights from a source PyTorch module to a destination module by tracing and matching parametrized operations', 'push a converted ResNet model and its image processor to the Hugging Face Hub', 'create a ResNet image feature extractor model with configurable stages and bottleneck layers', 'build a ResNet image classification model with a linear head on top of pooled features', 'build a ResNet backbone model to extract multi-scale feature maps for DETR and MaskFormer', 'test the ResNet encoder that stacks stages with residual connections and hidden state tracking', 'review the ResNet forward pass that applies embeddings, encoder stages, and adaptive pooling']
```

Usage

```
{'convert_resnet_timm_to_pytorch': 'convert a ResNet model from timm pretrained weights to a Hugging Face ResNetForImageClassification model', 'convert_single_resnet_model': 'convert a single ResNet model (resnet18, resnet26, resnet34, resnet50, resnet101, or resnet152) from timm to Hugging Face', 'convert_all_resnet_models': 'convert all supported ResNet models (resnet18, resnet26, resnet34, resnet50, resnet101, resnet152) from timm to Hugging Face', 'transfer_weights_modules': 'transfer weights from a source PyTorch module to a destination module by tracing and matching parametrized operations', 'push_resnet_to_hub': 'push a converted ResNet model and its image processor to the Hugging Face Hub'}
```

## File: huggingface_transformers/src/transformers/models/resnet/modeling_resnet.py

Prompts

```
['create a ResNetConfig instance with default resnet-50 style configuration', 'create a ResNetConfig with custom layer_type, hidden_sizes, and depths parameters', 'validate the layer_type attribute of a ResNetConfig is basic or bottleneck', 'create a ResNetConfig and initialize stage_names from depths array', 'create a ResNetConfig with out_indices and out_features for output feature selection', 'convert a ResNet model from timm pretrained weights to a Hugging Face ResNetForImageClassification model', 'convert a single ResNet model (resnet18, resnet26, resnet34, resnet50, resnet101, or resnet152) from timm to Hugging Face', 'convert all supported ResNet models (resnet18, resnet26, resnet34, resnet50, resnet101, resnet152) from timm to Hugging Face', 'transfer weights from a source PyTorch module to a destination module by tracing and matching parametrized operations', 'push a converted ResNet model and its image processor to the Hugging Face Hub', 'create a ResNet image feature extractor model with configurable stages and bottleneck layers', 'build a ResNet image classification model with a linear head on top of pooled features', 'build a ResNet backbone model to extract multi-scale feature maps for DETR and MaskFormer', 'test the ResNet encoder that stacks stages with residual connections and hidden state tracking', 'review the ResNet forward pass that applies embeddings, encoder stages, and adaptive pooling']
```

Usage

```
{'create_model_resnet': 'create a ResNet image feature extractor model with configurable stages and bottleneck layers', 'build_classifier_resnet': 'build a ResNet image classification model with a linear head on top of pooled features', 'build_backbone_resnet': 'build a ResNet backbone model to extract multi-scale feature maps for DETR and MaskFormer', 'test_resnet_encoder': 'test the ResNet encoder that stacks stages with residual connections and hidden state tracking', 'review_resnet_forward': 'review the ResNet forward pass that applies embeddings, encoder stages, and adaptive pooling'}
```

