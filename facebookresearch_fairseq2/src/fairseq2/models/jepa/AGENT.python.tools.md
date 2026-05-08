# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/models/jepa/config.py

Prompts

```
['create a JepaConfig dataclass instance with default base JEPA model architecture settings', 'create a JepaEncoderConfig dataclass to configure Vision Transformer encoder dimensions and attention heads', 'register JEPA model architecture configs like tiny, small, base, large, huge, giant, and gigantic into a DependencyContainer', 'customize the JepaEncoderConfig model_dim to set the dimensionality of the JEPA model', 'customize the JepaEncoderConfig patch_dims to configure patch extraction dimensions for image or video inputs', 'create a JEPA model from a JepaConfig using the create_jepa_model factory function', 'build a JEPA model by instantiating JepaFactory with a config and calling create_model', 'create a transformer encoder frontend with a 2D or 3D patch feature extractor and position encoder', 'create a transformer encoder with configurable layers, self-attention, and feed-forward networks using JepaEncoderFactory', 'initialize model weights with truncated normal distribution and zero biases using _init_truncated_normal', 'convert a JEPA model state dict from the original checkpoint format to fairseq2 format using a JepaConfig', 'split combined qkv weight and bias tensors into separate q_proj, k_proj, and v_proj parameters', 'remap JEPA backbone layer keys from module.backbone.blocks format to encoder.layers format', 'extract encoder state from a checkpoint using either the target_encoder or encoder key', 'remove the module.backbone.pos_embed key from the JEPA encoder state dict during conversion', 'build a JepaModel with a TransformerFrontend and TransformerEncoder for sequence encoding', 'run the JepaModel forward pass on sequences with a BatchLayout', 'create a JepaModel instance with a custom model dimension and encoder components', 'review the JepaModel constructor to understand model_dim, encoder_frontend, and encoder parameters', 'summarize the JepaModel extra_repr method that returns the model_dim string']
```

Usage

```
{'create_JepaConfig': 'create a JepaConfig dataclass instance with default base JEPA model architecture settings', 'create_JepaEncoderConfig': 'create a JepaEncoderConfig dataclass to configure Vision Transformer encoder dimensions and attention heads', 'register_jepa_configs': 'register JEPA model architecture configs like tiny, small, base, large, huge, giant, and gigantic into a DependencyContainer', 'customize_JepaEncoderConfig_model_dim': 'customize the JepaEncoderConfig model_dim to set the dimensionality of the JEPA model', 'customize_JepaEncoderConfig_patch_dims': 'customize the JepaEncoderConfig patch_dims to configure patch extraction dimensions for image or video inputs'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/jepa/factory.py

Prompts

```
['create a JepaConfig dataclass instance with default base JEPA model architecture settings', 'create a JepaEncoderConfig dataclass to configure Vision Transformer encoder dimensions and attention heads', 'register JEPA model architecture configs like tiny, small, base, large, huge, giant, and gigantic into a DependencyContainer', 'customize the JepaEncoderConfig model_dim to set the dimensionality of the JEPA model', 'customize the JepaEncoderConfig patch_dims to configure patch extraction dimensions for image or video inputs', 'create a JEPA model from a JepaConfig using the create_jepa_model factory function', 'build a JEPA model by instantiating JepaFactory with a config and calling create_model', 'create a transformer encoder frontend with a 2D or 3D patch feature extractor and position encoder', 'create a transformer encoder with configurable layers, self-attention, and feed-forward networks using JepaEncoderFactory', 'initialize model weights with truncated normal distribution and zero biases using _init_truncated_normal', 'convert a JEPA model state dict from the original checkpoint format to fairseq2 format using a JepaConfig', 'split combined qkv weight and bias tensors into separate q_proj, k_proj, and v_proj parameters', 'remap JEPA backbone layer keys from module.backbone.blocks format to encoder.layers format', 'extract encoder state from a checkpoint using either the target_encoder or encoder key', 'remove the module.backbone.pos_embed key from the JEPA encoder state dict during conversion', 'build a JepaModel with a TransformerFrontend and TransformerEncoder for sequence encoding', 'run the JepaModel forward pass on sequences with a BatchLayout', 'create a JepaModel instance with a custom model dimension and encoder components', 'review the JepaModel constructor to understand model_dim, encoder_frontend, and encoder parameters', 'summarize the JepaModel extra_repr method that returns the model_dim string']
```

Usage

```
{'create_jepa_model_from_config': 'create a JEPA model from a JepaConfig using the create_jepa_model factory function', 'build_jepa_model_with_factory': 'build a JEPA model by instantiating JepaFactory with a config and calling create_model', 'create_encoder_frontend_with_patch_extractor': 'create a transformer encoder frontend with a 2D or 3D patch feature extractor and position encoder', 'create_transformer_encoder_with_layers': 'create a transformer encoder with configurable layers, self-attention, and feed-forward networks using JepaEncoderFactory', 'init_weights_with_truncated_normal': 'initialize model weights with truncated normal distribution and zero biases using _init_truncated_normal'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/jepa/interop.py

Prompts

```
['create a JepaConfig dataclass instance with default base JEPA model architecture settings', 'create a JepaEncoderConfig dataclass to configure Vision Transformer encoder dimensions and attention heads', 'register JEPA model architecture configs like tiny, small, base, large, huge, giant, and gigantic into a DependencyContainer', 'customize the JepaEncoderConfig model_dim to set the dimensionality of the JEPA model', 'customize the JepaEncoderConfig patch_dims to configure patch extraction dimensions for image or video inputs', 'create a JEPA model from a JepaConfig using the create_jepa_model factory function', 'build a JEPA model by instantiating JepaFactory with a config and calling create_model', 'create a transformer encoder frontend with a 2D or 3D patch feature extractor and position encoder', 'create a transformer encoder with configurable layers, self-attention, and feed-forward networks using JepaEncoderFactory', 'initialize model weights with truncated normal distribution and zero biases using _init_truncated_normal', 'convert a JEPA model state dict from the original checkpoint format to fairseq2 format using a JepaConfig', 'split combined qkv weight and bias tensors into separate q_proj, k_proj, and v_proj parameters', 'remap JEPA backbone layer keys from module.backbone.blocks format to encoder.layers format', 'extract encoder state from a checkpoint using either the target_encoder or encoder key', 'remove the module.backbone.pos_embed key from the JEPA encoder state dict during conversion', 'build a JepaModel with a TransformerFrontend and TransformerEncoder for sequence encoding', 'run the JepaModel forward pass on sequences with a BatchLayout', 'create a JepaModel instance with a custom model dimension and encoder components', 'review the JepaModel constructor to understand model_dim, encoder_frontend, and encoder parameters', 'summarize the JepaModel extra_repr method that returns the model_dim string']
```

Usage

```
{'convert_jepa_state_dict': 'convert a JEPA model state dict from the original checkpoint format to fairseq2 format using a JepaConfig', 'convert_qkv_projections': 'split combined qkv weight and bias tensors into separate q_proj, k_proj, and v_proj parameters', 'remap_encoder_keys': 'remap JEPA backbone layer keys from module.backbone.blocks format to encoder.layers format', 'handle_target_or_encoder': 'extract encoder state from a checkpoint using either the target_encoder or encoder key', 'remove_pos_embed': 'remove the module.backbone.pos_embed key from the JEPA encoder state dict during conversion'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/jepa/model.py

Prompts

```
['create a JepaConfig dataclass instance with default base JEPA model architecture settings', 'create a JepaEncoderConfig dataclass to configure Vision Transformer encoder dimensions and attention heads', 'register JEPA model architecture configs like tiny, small, base, large, huge, giant, and gigantic into a DependencyContainer', 'customize the JepaEncoderConfig model_dim to set the dimensionality of the JEPA model', 'customize the JepaEncoderConfig patch_dims to configure patch extraction dimensions for image or video inputs', 'create a JEPA model from a JepaConfig using the create_jepa_model factory function', 'build a JEPA model by instantiating JepaFactory with a config and calling create_model', 'create a transformer encoder frontend with a 2D or 3D patch feature extractor and position encoder', 'create a transformer encoder with configurable layers, self-attention, and feed-forward networks using JepaEncoderFactory', 'initialize model weights with truncated normal distribution and zero biases using _init_truncated_normal', 'convert a JEPA model state dict from the original checkpoint format to fairseq2 format using a JepaConfig', 'split combined qkv weight and bias tensors into separate q_proj, k_proj, and v_proj parameters', 'remap JEPA backbone layer keys from module.backbone.blocks format to encoder.layers format', 'extract encoder state from a checkpoint using either the target_encoder or encoder key', 'remove the module.backbone.pos_embed key from the JEPA encoder state dict during conversion', 'build a JepaModel with a TransformerFrontend and TransformerEncoder for sequence encoding', 'run the JepaModel forward pass on sequences with a BatchLayout', 'create a JepaModel instance with a custom model dimension and encoder components', 'review the JepaModel constructor to understand model_dim, encoder_frontend, and encoder parameters', 'summarize the JepaModel extra_repr method that returns the model_dim string']
```

Usage

```
{'build_JepaModel': 'build a JepaModel with a TransformerFrontend and TransformerEncoder for sequence encoding', 'run_JepaModel_forward': 'run the JepaModel forward pass on sequences with a BatchLayout', 'create_JepaModel_encoder': 'create a JepaModel instance with a custom model dimension and encoder components', 'review_JepaModel_init': 'review the JepaModel constructor to understand model_dim, encoder_frontend, and encoder parameters', 'summarize_JepaModel_extra_repr': 'summarize the JepaModel extra_repr method that returns the model_dim string'}
```

