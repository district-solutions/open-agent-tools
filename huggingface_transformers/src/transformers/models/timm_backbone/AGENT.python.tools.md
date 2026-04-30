# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/timm_backbone/configuration_timm_backbone.py

Prompts

```
['create a TimmBackboneConfig instance initialized with a timm checkpoint name like resnet50', 'configure a TimmBackboneConfig to output only features or also logits via features_only flag', 'set the out_indices property on TimmBackboneConfig to specify which output feature layers to use', 'set the out_features property on TimmBackboneConfig to specify output feature layer names', 'configure TimmBackboneConfig to freeze BatchNorm2d and SyncBatchNorm layers via freeze_batch_norm_2d flag', 'create a TimmBackbone model wrapping a timm model as a feature extractor backbone', 'build a TimmBackbone model loaded from a pretrained timm model checkpoint', 'unfreeze previously frozen BatchNorm2d layers in a TimmBackbone model', 'run a forward pass on a TimmBackbone model to extract feature maps from pixel values']
```

Usage

```
{'create_timm_backbone_config': 'create a TimmBackboneConfig instance initialized with a timm checkpoint name like resnet50', 'configure_timm_backbone_features_only': 'configure a TimmBackboneConfig to output only features or also logits via features_only flag', 'set_timm_backbone_out_indices': 'set the out_indices property on TimmBackboneConfig to specify which output feature layers to use', 'set_timm_backbone_out_features': 'set the out_features property on TimmBackboneConfig to specify output feature layer names', 'freeze_timm_backbone_batch_norm': 'configure TimmBackboneConfig to freeze BatchNorm2d and SyncBatchNorm layers via freeze_batch_norm_2d flag'}
```

## File: huggingface_transformers/src/transformers/models/timm_backbone/modeling_timm_backbone.py

Prompts

```
['create a TimmBackboneConfig instance initialized with a timm checkpoint name like resnet50', 'configure a TimmBackboneConfig to output only features or also logits via features_only flag', 'set the out_indices property on TimmBackboneConfig to specify which output feature layers to use', 'set the out_features property on TimmBackboneConfig to specify output feature layer names', 'configure TimmBackboneConfig to freeze BatchNorm2d and SyncBatchNorm layers via freeze_batch_norm_2d flag', 'create a TimmBackbone model wrapping a timm model as a feature extractor backbone', 'build a TimmBackbone model loaded from a pretrained timm model checkpoint', 'unfreeze previously frozen BatchNorm2d layers in a TimmBackbone model', 'run a forward pass on a TimmBackbone model to extract feature maps from pixel values']
```

Usage

```
{'create_timm_backbone_model': 'create a TimmBackbone model wrapping a timm model as a feature extractor backbone', 'build_timm_backbone_from_pretrained': 'build a TimmBackbone model loaded from a pretrained timm model checkpoint', 'freeze_timm_backbone_batch_norm': 'freeze BatchNorm2d layers in a TimmBackbone model for training stability', 'unfreeze_timm_backbone_batch_norm': 'unfreeze previously frozen BatchNorm2d layers in a TimmBackbone model', 'run_timm_backbone_forward_pass': 'run a forward pass on a TimmBackbone model to extract feature maps from pixel values'}
```

