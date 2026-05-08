# Agent Python Tools

- repo: facebookresearch/classyvision
- repo_uri: https://github.com/facebookresearch/classyvision

## File: facebookresearch_classyvision/classy_vision/tasks/classification_task.py

Prompts

```
['build a ClassificationTask from a config dict with model, loss, optimizer, and dataset settings', 'set distributed training options like broadcast buffers mode and synchronized batch norm on the task', 'set automatic mixed precision arguments to enable Apex or PyTorch AMP for faster training', 'run a single training step with forward pass, loss computation, backward pass, and optimizer update', 'set a checkpoint path to resume training from a saved model state', 'create a subclass of ClassyTask that implements all abstract methods for a custom training task', 'build a ClassyTask instance from a configuration dictionary using the from_config class method', 'get and set the ClassyTask state dictionary for saving and loading training checkpoints', 'run hook functions for all registered ClassyHook instances with local variables from train_step', 'create a FineTuningTask instance from a config dict with pretrained checkpoint and freeze options', 'set the pretrained checkpoint file path on a FineTuningTask instance for model loading', 'set freeze_trunk to disable gradient updates on the trunk model except head layers', 'set reset_heads to reinitialize the head layers when loading a pretrained checkpoint', 'prepare the FineTuningTask by loading pretrained weights and optionally freezing the trunk']
```

Usage

```
{'build_classification_task_from_config': 'build a ClassificationTask from a config dict with model, loss, optimizer, and dataset settings', 'set_distributed_options_ddp': 'set distributed training options like broadcast buffers mode and synchronized batch norm on the task', 'set_amp_args_mixed_precision': 'set automatic mixed precision arguments to enable Apex or PyTorch AMP for faster training', 'run_train_step': 'run a single training step with forward pass, loss computation, backward pass, and optimizer update', 'set_checkpoint_resume_training': 'set a checkpoint path to resume training from a saved model state'}
```

## File: facebookresearch_classyvision/classy_vision/tasks/classy_task.py

Prompts

```
['build a ClassificationTask from a config dict with model, loss, optimizer, and dataset settings', 'set distributed training options like broadcast buffers mode and synchronized batch norm on the task', 'set automatic mixed precision arguments to enable Apex or PyTorch AMP for faster training', 'run a single training step with forward pass, loss computation, backward pass, and optimizer update', 'set a checkpoint path to resume training from a saved model state', 'create a subclass of ClassyTask that implements all abstract methods for a custom training task', 'build a ClassyTask instance from a configuration dictionary using the from_config class method', 'get and set the ClassyTask state dictionary for saving and loading training checkpoints', 'run hook functions for all registered ClassyHook instances with local variables from train_step', 'create a FineTuningTask instance from a config dict with pretrained checkpoint and freeze options', 'set the pretrained checkpoint file path on a FineTuningTask instance for model loading', 'set freeze_trunk to disable gradient updates on the trunk model except head layers', 'set reset_heads to reinitialize the head layers when loading a pretrained checkpoint', 'prepare the FineTuningTask by loading pretrained weights and optionally freezing the trunk']
```

Usage

```
{'create_ClassyTask_subclass': 'create a subclass of ClassyTask that implements all abstract methods for a custom training task', 'build_from_config': 'build a ClassyTask instance from a configuration dictionary using the from_config class method', 'run_train_step': 'run a single training step over one batch of data from the dataloaders', 'checkpoint_get_set_state': 'get and set the ClassyTask state dictionary for saving and loading training checkpoints', 'run_hooks': 'run hook functions for all registered ClassyHook instances with local variables from train_step'}
```

## File: facebookresearch_classyvision/classy_vision/tasks/fine_tuning_task.py

Prompts

```
['build a ClassificationTask from a config dict with model, loss, optimizer, and dataset settings', 'set distributed training options like broadcast buffers mode and synchronized batch norm on the task', 'set automatic mixed precision arguments to enable Apex or PyTorch AMP for faster training', 'run a single training step with forward pass, loss computation, backward pass, and optimizer update', 'set a checkpoint path to resume training from a saved model state', 'create a subclass of ClassyTask that implements all abstract methods for a custom training task', 'build a ClassyTask instance from a configuration dictionary using the from_config class method', 'get and set the ClassyTask state dictionary for saving and loading training checkpoints', 'run hook functions for all registered ClassyHook instances with local variables from train_step', 'create a FineTuningTask instance from a config dict with pretrained checkpoint and freeze options', 'set the pretrained checkpoint file path on a FineTuningTask instance for model loading', 'set freeze_trunk to disable gradient updates on the trunk model except head layers', 'set reset_heads to reinitialize the head layers when loading a pretrained checkpoint', 'prepare the FineTuningTask by loading pretrained weights and optionally freezing the trunk']
```

Usage

```
{'create_finetuningtask_from_config': 'create a FineTuningTask instance from a config dict with pretrained checkpoint and freeze options', 'set_pretrained_checkpoint': 'set the pretrained checkpoint file path on a FineTuningTask instance for model loading', 'set_freeze_trunk': 'set freeze_trunk to disable gradient updates on the trunk model except head layers', 'set_reset_heads': 'set reset_heads to reinitialize the head layers when loading a pretrained checkpoint', 'prepare_finetuning_task': 'prepare the FineTuningTask by loading pretrained weights and optionally freezing the trunk'}
```

