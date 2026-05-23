# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/seg/mmseg/engine/optimizers/force_default_constructor.py

Prompts

```
['build an optimizer wrapper constructor that forces default settings on all model parameters', 'create a parameter-wise config with custom_keys, bias_lr_mult, and norm_decay_mult settings', 'test the add_params method to verify parameter groups are built correctly for a model', 'review the ForceDefaultOptimWrapperConstructor class and its force_default_settings override behavior', 'refactor the custom_keys matching logic in add_params to support new parameter naming patterns', 'build a LayerDecayOptimWrapperConstructor to create parameter groups with layer-wise learning rate decay for ViT models', 'create a function that maps ViT parameter names to their corresponding layer IDs for optimizer scheduling', 'test the fsdp_get_num_layer_for_vit function to extract layer IDs from FSDP-wrapped parameter names', 'review the LayerDecayOptimWrapperConstructor add_params method to understand parameter grouping and weight decay logic', 'summarize how the layer_decay_rate exponent scales learning rates across ViT backbone layers', 'get the layer id for a ConvNeXt model parameter name to set different learning rates', 'get the stage id for a ConvNeXt model parameter name in stage_wise decay', 'get the layer id for a ViT BEiT or MAE model parameter name', 'add module parameters to param groups with layer-wise learning rate decay for ConvNeXt or ViT backbones', 'initialize the deprecated LayerDecayOptimizerConstructor for BEiT models with layer-wise ViT decay type', 'create parameter groups with decay and no_decay categories based on weight shape and name patterns', 'test the get_num_layer_for_vit function to map parameter names to their corresponding layer IDs', 'review the add_params method that groups module parameters by layer ID and assigns scaled learning rates', 'refactor the StereoPointmapLayerDecayOptimWrapperConstructor to customize the layer_decay_rate exponent for learning rate scheduling']
```

Usage

```
{'build_optimizer_wrapper': 'build an optimizer wrapper constructor that forces default settings on all model parameters', 'create_paramwise_config': 'create a parameter-wise config with custom_keys, bias_lr_mult, and norm_decay_mult settings', 'test_add_params': 'test the add_params method to verify parameter groups are built correctly for a model', 'review_force_default_settings': 'review the ForceDefaultOptimWrapperConstructor class and its force_default_settings override behavior', 'refactor_custom_keys': 'refactor the custom_keys matching logic in add_params to support new parameter naming patterns'}
```

## File: facebookresearch_sapiens/seg/mmseg/engine/optimizers/layer_decay_optim_wrapper.py

Prompts

```
['build an optimizer wrapper constructor that forces default settings on all model parameters', 'create a parameter-wise config with custom_keys, bias_lr_mult, and norm_decay_mult settings', 'test the add_params method to verify parameter groups are built correctly for a model', 'review the ForceDefaultOptimWrapperConstructor class and its force_default_settings override behavior', 'refactor the custom_keys matching logic in add_params to support new parameter naming patterns', 'build a LayerDecayOptimWrapperConstructor to create parameter groups with layer-wise learning rate decay for ViT models', 'create a function that maps ViT parameter names to their corresponding layer IDs for optimizer scheduling', 'test the fsdp_get_num_layer_for_vit function to extract layer IDs from FSDP-wrapped parameter names', 'review the LayerDecayOptimWrapperConstructor add_params method to understand parameter grouping and weight decay logic', 'summarize how the layer_decay_rate exponent scales learning rates across ViT backbone layers', 'get the layer id for a ConvNeXt model parameter name to set different learning rates', 'get the stage id for a ConvNeXt model parameter name in stage_wise decay', 'get the layer id for a ViT BEiT or MAE model parameter name', 'add module parameters to param groups with layer-wise learning rate decay for ConvNeXt or ViT backbones', 'initialize the deprecated LayerDecayOptimizerConstructor for BEiT models with layer-wise ViT decay type', 'create parameter groups with decay and no_decay categories based on weight shape and name patterns', 'test the get_num_layer_for_vit function to map parameter names to their corresponding layer IDs', 'review the add_params method that groups module parameters by layer ID and assigns scaled learning rates', 'refactor the StereoPointmapLayerDecayOptimWrapperConstructor to customize the layer_decay_rate exponent for learning rate scheduling']
```

Usage

```
{'build_layer_decay_optimizer': 'build a LayerDecayOptimWrapperConstructor to create parameter groups with layer-wise learning rate decay for ViT models', 'create_vit_layer_id_mapping': 'create a function that maps ViT parameter names to their corresponding layer IDs for optimizer scheduling', 'test_fsdp_layer_extraction': 'test the fsdp_get_num_layer_for_vit function to extract layer IDs from FSDP-wrapped parameter names', 'review_add_params_method': 'review the LayerDecayOptimWrapperConstructor add_params method to understand parameter grouping and weight decay logic', 'summarize_layer_decay_rate': 'summarize how the layer_decay_rate exponent scales learning rates across ViT backbone layers'}
```

## File: facebookresearch_sapiens/seg/mmseg/engine/optimizers/layer_decay_optimizer_constructor.py

Prompts

```
['build an optimizer wrapper constructor that forces default settings on all model parameters', 'create a parameter-wise config with custom_keys, bias_lr_mult, and norm_decay_mult settings', 'test the add_params method to verify parameter groups are built correctly for a model', 'review the ForceDefaultOptimWrapperConstructor class and its force_default_settings override behavior', 'refactor the custom_keys matching logic in add_params to support new parameter naming patterns', 'build a LayerDecayOptimWrapperConstructor to create parameter groups with layer-wise learning rate decay for ViT models', 'create a function that maps ViT parameter names to their corresponding layer IDs for optimizer scheduling', 'test the fsdp_get_num_layer_for_vit function to extract layer IDs from FSDP-wrapped parameter names', 'review the LayerDecayOptimWrapperConstructor add_params method to understand parameter grouping and weight decay logic', 'summarize how the layer_decay_rate exponent scales learning rates across ViT backbone layers', 'get the layer id for a ConvNeXt model parameter name to set different learning rates', 'get the stage id for a ConvNeXt model parameter name in stage_wise decay', 'get the layer id for a ViT BEiT or MAE model parameter name', 'add module parameters to param groups with layer-wise learning rate decay for ConvNeXt or ViT backbones', 'initialize the deprecated LayerDecayOptimizerConstructor for BEiT models with layer-wise ViT decay type', 'create parameter groups with decay and no_decay categories based on weight shape and name patterns', 'test the get_num_layer_for_vit function to map parameter names to their corresponding layer IDs', 'review the add_params method that groups module parameters by layer ID and assigns scaled learning rates', 'refactor the StereoPointmapLayerDecayOptimWrapperConstructor to customize the layer_decay_rate exponent for learning rate scheduling']
```

Usage

```
{'get_layer_id_for_convnext': 'get the layer id for a ConvNeXt model parameter name to set different learning rates', 'get_stage_id_for_convnext': 'get the stage id for a ConvNeXt model parameter name in stage_wise decay', 'get_layer_id_for_vit': 'get the layer id for a ViT BEiT or MAE model parameter name', 'LearningRateDecayOptimizerConstructor_add_params': 'add module parameters to param groups with layer-wise learning rate decay for ConvNeXt or ViT backbones', 'LayerDecayOptimizerConstructor_init': 'initialize the deprecated LayerDecayOptimizerConstructor for BEiT models with layer-wise ViT decay type'}
```

## File: facebookresearch_sapiens/seg/mmseg/engine/optimizers/stereo_pointmap_layer_decay_optim_wrapper.py

Prompts

```
['build an optimizer wrapper constructor that forces default settings on all model parameters', 'create a parameter-wise config with custom_keys, bias_lr_mult, and norm_decay_mult settings', 'test the add_params method to verify parameter groups are built correctly for a model', 'review the ForceDefaultOptimWrapperConstructor class and its force_default_settings override behavior', 'refactor the custom_keys matching logic in add_params to support new parameter naming patterns', 'build a LayerDecayOptimWrapperConstructor to create parameter groups with layer-wise learning rate decay for ViT models', 'create a function that maps ViT parameter names to their corresponding layer IDs for optimizer scheduling', 'test the fsdp_get_num_layer_for_vit function to extract layer IDs from FSDP-wrapped parameter names', 'review the LayerDecayOptimWrapperConstructor add_params method to understand parameter grouping and weight decay logic', 'summarize how the layer_decay_rate exponent scales learning rates across ViT backbone layers', 'get the layer id for a ConvNeXt model parameter name to set different learning rates', 'get the stage id for a ConvNeXt model parameter name in stage_wise decay', 'get the layer id for a ViT BEiT or MAE model parameter name', 'add module parameters to param groups with layer-wise learning rate decay for ConvNeXt or ViT backbones', 'initialize the deprecated LayerDecayOptimizerConstructor for BEiT models with layer-wise ViT decay type', 'create parameter groups with decay and no_decay categories based on weight shape and name patterns', 'test the get_num_layer_for_vit function to map parameter names to their corresponding layer IDs', 'review the add_params method that groups module parameters by layer ID and assigns scaled learning rates', 'refactor the StereoPointmapLayerDecayOptimWrapperConstructor to customize the layer_decay_rate exponent for learning rate scheduling']
```

Usage

```
{'build_layer_decay_optimizer': 'build a StereoPointmapLayerDecayOptimWrapperConstructor to apply layer-wise learning rate decay for ViT backbone parameters', 'create_parameter_groups': 'create parameter groups with decay and no_decay categories based on weight shape and name patterns', 'test_get_num_layer_for_vit': 'test the get_num_layer_for_vit function to map parameter names to their corresponding layer IDs', 'review_add_params': 'review the add_params method that groups module parameters by layer ID and assigns scaled learning rates', 'refactor_layer_decay_rate': 'refactor the StereoPointmapLayerDecayOptimWrapperConstructor to customize the layer_decay_rate exponent for learning rate scheduling'}
```

