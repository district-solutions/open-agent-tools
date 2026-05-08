# Agent Python Tools

- repo: facebookresearch/convnext
- repo_uri: https://github.com/facebookresearch/convnext

## File: facebookresearch_convnext/semantic_segmentation/mmcv_custom/customized_text.py

Prompts

```
['create a CustomizedTextLoggerHook instance to log training metrics including lr and layer_0_lr', 'use the CustomizedTextLoggerHook with an mmcv runner to log training and validation progress', 'customize the log output format by modifying the _log_info method to include additional metrics', 'register the CustomizedTextLoggerHook module with mmcv HOOKS registry for use in training configs', 'review the CustomizedTextLoggerHook log method to understand how lr values are extracted and formatted', 'build a ConvNeXt optimizer using LearningRateDecayOptimizerConstructor with layer-wise learning rate decay', 'create an optimizer constructor that applies stage-wise learning rate decay across backbone stages', 'get the layer ID for a parameter name using the layer-wise assignment strategy', 'get the layer ID for a parameter name using the stage-wise assignment strategy', 'review the LearningRateDecayOptimizerConstructor add_params method to understand parameter grouping and weight decay logic']
```

Usage

```
{'create_CustomizedTextLoggerHook': 'create a CustomizedTextLoggerHook instance to log training metrics including lr and layer_0_lr', 'use_CustomizedTextLoggerHook_with_runner': 'use the CustomizedTextLoggerHook with an mmcv runner to log training and validation progress', 'customize_log_output_format': 'customize the log output format by modifying the _log_info method to include additional metrics', 'register_hook_with_HOOKS': 'register the CustomizedTextLoggerHook module with mmcv HOOKS registry for use in training configs', 'review_CustomizedTextLoggerHook_log_method': 'review the CustomizedTextLoggerHook log method to understand how lr values are extracted and formatted'}
```

## File: facebookresearch_convnext/semantic_segmentation/mmcv_custom/layer_decay_optimizer_constructor.py

Prompts

```
['create a CustomizedTextLoggerHook instance to log training metrics including lr and layer_0_lr', 'use the CustomizedTextLoggerHook with an mmcv runner to log training and validation progress', 'customize the log output format by modifying the _log_info method to include additional metrics', 'register the CustomizedTextLoggerHook module with mmcv HOOKS registry for use in training configs', 'review the CustomizedTextLoggerHook log method to understand how lr values are extracted and formatted', 'build a ConvNeXt optimizer using LearningRateDecayOptimizerConstructor with layer-wise learning rate decay', 'create an optimizer constructor that applies stage-wise learning rate decay across backbone stages', 'get the layer ID for a parameter name using the layer-wise assignment strategy', 'get the layer ID for a parameter name using the stage-wise assignment strategy', 'review the LearningRateDecayOptimizerConstructor add_params method to understand parameter grouping and weight decay logic']
```

Usage

```
{'build_optimizer_with_layer_decay': 'build a ConvNeXt optimizer using LearningRateDecayOptimizerConstructor with layer-wise learning rate decay', 'create_stage_wise_lr_decay': 'create an optimizer constructor that applies stage-wise learning rate decay across backbone stages', 'get_layer_id_layer_wise': 'get the layer ID for a parameter name using the layer-wise assignment strategy', 'get_layer_id_stage_wise': 'get the layer ID for a parameter name using the stage-wise assignment strategy', 'review_optimizer_param_groups': 'review the LearningRateDecayOptimizerConstructor add_params method to understand parameter grouping and weight decay logic'}
```

