# Agent Python Tools

- repo: facebookresearch/convnext
- repo_uri: https://github.com/facebookresearch/convnext

## File: facebookresearch_convnext/object_detection/mmcv_custom/customized_text.py

Prompts

```
['create a CustomizedTextLoggerHook instance to log training metrics including lr and layer_0_lr', 'use the CustomizedTextLoggerHook with an mmcv runner to log training and validation progress', 'customize the log output format to include experiment name, learning rates, and timing statistics', 'register the CustomizedTextLoggerHook module with mmcv HOOKS for use in training configurations', 'review the CustomizedTextLoggerHook log method to understand how lr and layer_0_lr are extracted and recorded', 'build a ConvNeXt optimizer constructor with layer-wise learning rate decay for backbone parameters', 'create a function that assigns layer IDs to ConvNeXt backbone parameters for layer-wise LR decay', 'create a function that assigns layer IDs to ConvNeXt backbone parameters for stage-wise LR decay', 'refactor the add_params method to customize parameter grouping and weight decay rules for optimizer construction', 'review the LearningRateDecayOptimizerConstructor class and its layer-wise and stage-wise learning rate decay strategies']
```

Usage

```
{'create_CustomizedTextLoggerHook': 'create a CustomizedTextLoggerHook instance to log training metrics including lr and layer_0_lr', 'use_CustomizedTextLoggerHook_with_runner': 'use the CustomizedTextLoggerHook with an mmcv runner to log training and validation progress', 'customize_log_output_format': 'customize the log output format to include experiment name, learning rates, and timing statistics', 'register_CustomizedTextLoggerHook': 'register the CustomizedTextLoggerHook module with mmcv HOOKS for use in training configurations', 'review_CustomizedTextLoggerHook_log_method': 'review the CustomizedTextLoggerHook log method to understand how lr and layer_0_lr are extracted and recorded'}
```

## File: facebookresearch_convnext/object_detection/mmcv_custom/layer_decay_optimizer_constructor.py

Prompts

```
['create a CustomizedTextLoggerHook instance to log training metrics including lr and layer_0_lr', 'use the CustomizedTextLoggerHook with an mmcv runner to log training and validation progress', 'customize the log output format to include experiment name, learning rates, and timing statistics', 'register the CustomizedTextLoggerHook module with mmcv HOOKS for use in training configurations', 'review the CustomizedTextLoggerHook log method to understand how lr and layer_0_lr are extracted and recorded', 'build a ConvNeXt optimizer constructor with layer-wise learning rate decay for backbone parameters', 'create a function that assigns layer IDs to ConvNeXt backbone parameters for layer-wise LR decay', 'create a function that assigns layer IDs to ConvNeXt backbone parameters for stage-wise LR decay', 'refactor the add_params method to customize parameter grouping and weight decay rules for optimizer construction', 'review the LearningRateDecayOptimizerConstructor class and its layer-wise and stage-wise learning rate decay strategies']
```

Usage

```
{'build_LearningRateDecayOptimizerConstructor': 'build a ConvNeXt optimizer constructor with layer-wise learning rate decay for backbone parameters', 'create_get_num_layer_layer_wise': 'create a function that assigns layer IDs to ConvNeXt backbone parameters for layer-wise LR decay', 'create_get_num_layer_stage_wise': 'create a function that assigns layer IDs to ConvNeXt backbone parameters for stage-wise LR decay', 'refactor_add_params': 'refactor the add_params method to customize parameter grouping and weight decay rules for optimizer construction', 'review_LearningRateDecayOptimizerConstructor': 'review the LearningRateDecayOptimizerConstructor class and its layer-wise and stage-wise learning rate decay strategies'}
```

