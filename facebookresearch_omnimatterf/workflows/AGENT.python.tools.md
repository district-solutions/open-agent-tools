# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/workflows/common.py

Prompts

```
['build a foreground or background model from a config with dependency injection and parameter overrides', 'create a matting dataset and build foreground and background models from a workflow config', 'merge an eval config with a train config and migrate legacy experiment settings', 'create a trainer with loaded checkpoint, dataset, and models for evaluation testing', 'review the build_model function that constructs models with config injection and training mode control', 'run the evaluate function to test a model checkpoint on a dataset and save results', 'run the main entry point to start evaluation with Hydra config for the Omnimatterf model', 'create a masked image by overlaying colored masks onto an RGB image using make_masked', 'review the evaluate function that iterates over a dataset, runs inference, and computes frame metrics', 'summarize the make_masked function that blends colored masks into an image using predefined mask colors', 'run the training workflow with a TrainConfig to train foreground and background models', 'run the Hydra-decorated main entry point to start training with config files', 'build a ComposedLoss from loss configs by calling build_loss for each criterion', 'add validation hooks to the trainer for post-step and pre-train events', 'load a checkpoint to resume training with optional fg/bg model exclusion']
```

Usage

```
{'build_model': 'build a foreground or background model from a config with dependency injection and parameter overrides', 'create_dataset_and_model': 'create a matting dataset and build foreground and background models from a workflow config', 'merge_config': 'merge an eval config with a train config and migrate legacy experiment settings', 'create_for_test': 'create a trainer with loaded checkpoint, dataset, and models for evaluation testing', 'review_build_model': 'review the build_model function that constructs models with config injection and training mode control'}
```

## File: facebookresearch_omnimatterf/workflows/eval.py

Prompts

```
['build a foreground or background model from a config with dependency injection and parameter overrides', 'create a matting dataset and build foreground and background models from a workflow config', 'merge an eval config with a train config and migrate legacy experiment settings', 'create a trainer with loaded checkpoint, dataset, and models for evaluation testing', 'review the build_model function that constructs models with config injection and training mode control', 'run the evaluate function to test a model checkpoint on a dataset and save results', 'run the main entry point to start evaluation with Hydra config for the Omnimatterf model', 'create a masked image by overlaying colored masks onto an RGB image using make_masked', 'review the evaluate function that iterates over a dataset, runs inference, and computes frame metrics', 'summarize the make_masked function that blends colored masks into an image using predefined mask colors', 'run the training workflow with a TrainConfig to train foreground and background models', 'run the Hydra-decorated main entry point to start training with config files', 'build a ComposedLoss from loss configs by calling build_loss for each criterion', 'add validation hooks to the trainer for post-step and pre-train events', 'load a checkpoint to resume training with optional fg/bg model exclusion']
```

Usage

```
{'run_evaluate': 'run the evaluate function to test a model checkpoint on a dataset and save results', 'run_main': 'run the main entry point to start evaluation with Hydra config for the Omnimatterf model', 'create_make_masked': 'create a masked image by overlaying colored masks onto an RGB image using make_masked', 'review_evaluate': 'review the evaluate function that iterates over a dataset, runs inference, and computes frame metrics', 'summarize_make_masked': 'summarize the make_masked function that blends colored masks into an image using predefined mask colors'}
```

## File: facebookresearch_omnimatterf/workflows/train.py

Prompts

```
['build a foreground or background model from a config with dependency injection and parameter overrides', 'create a matting dataset and build foreground and background models from a workflow config', 'merge an eval config with a train config and migrate legacy experiment settings', 'create a trainer with loaded checkpoint, dataset, and models for evaluation testing', 'review the build_model function that constructs models with config injection and training mode control', 'run the evaluate function to test a model checkpoint on a dataset and save results', 'run the main entry point to start evaluation with Hydra config for the Omnimatterf model', 'create a masked image by overlaying colored masks onto an RGB image using make_masked', 'review the evaluate function that iterates over a dataset, runs inference, and computes frame metrics', 'summarize the make_masked function that blends colored masks into an image using predefined mask colors', 'run the training workflow with a TrainConfig to train foreground and background models', 'run the Hydra-decorated main entry point to start training with config files', 'build a ComposedLoss from loss configs by calling build_loss for each criterion', 'add validation hooks to the trainer for post-step and pre-train events', 'load a checkpoint to resume training with optional fg/bg model exclusion']
```

Usage

```
{'run_train_workflow': 'run the training workflow with a TrainConfig to train foreground and background models', 'run_main_entry': 'run the Hydra-decorated main entry point to start training with config files', 'build_composed_loss': 'build a ComposedLoss from loss configs by calling build_loss for each criterion', 'add_validation_hooks': 'add validation hooks to the trainer for post-step and pre-train events', 'load_checkpoint_resume': 'load a checkpoint to resume training with optional fg/bg model exclusion'}
```

