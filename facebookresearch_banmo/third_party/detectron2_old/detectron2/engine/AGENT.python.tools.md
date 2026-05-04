# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/engine/defaults.py

Prompts

```
['create a DistributedDataParallel model from a torch module with optional fp16 compression hooks', 'build an argparse parser with common detectron2 training arguments like config file and resume flags', 'run basic setup including logger configuration, environment info logging, and config backup to output directory', 'create an end-to-end predictor that loads a checkpoint and runs inference on a single BGR image', 'build a default trainer with model, optimizer, data loader, hooks, and checkpointing for standard training workflow', 'create a CallbackHook with before_train and after_train callback functions for the trainer', 'build an IterationTimer hook to track training iteration speed with configurable warmup iterations', 'run a PeriodicWriter hook to periodically write events to EventWriter objects every N iterations', 'test the PeriodicCheckpointer hook to save model checkpoints every N iterations during training', 'review the LRScheduler hook to execute a torch LR scheduler and summarize learning rate each step', 'launch multi-gpu or distributed training by spawning child processes per GPU on each machine', 'launch single GPU training by calling main_func directly when world size is one', 'launch distributed training with auto port selection for single machine jobs using dist_url auto', 'launch multi-machine distributed training with explicit dist_url and machine rank configuration', 'launch distributed training with a custom timeout for the distributed workers process group', 'create a custom training hook by subclassing HookBase and implementing before_train or after_step methods', 'register a list of HookBase hooks to a TrainerBase instance using the register_hooks method', 'run a standard single-optimizer training loop with a model, data_loader, and optimizer using SimpleTrainer', 'run automatic mixed precision training with a GradScaler using AMPTrainer for faster GPU training', 'save and restore training state including iteration count, optimizer, and hook states via state_dict and load_state_dict']
```

Usage

```
{'create_ddp_model': 'create a DistributedDataParallel model from a torch module with optional fp16 compression hooks', 'default_argument_parser': 'build an argparse parser with common detectron2 training arguments like config file and resume flags', 'default_setup': 'run basic setup including logger configuration, environment info logging, and config backup to output directory', 'DefaultPredictor': 'create an end-to-end predictor that loads a checkpoint and runs inference on a single BGR image', 'DefaultTrainer': 'build a default trainer with model, optimizer, data loader, hooks, and checkpointing for standard training workflow'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/engine/hooks.py

Prompts

```
['create a DistributedDataParallel model from a torch module with optional fp16 compression hooks', 'build an argparse parser with common detectron2 training arguments like config file and resume flags', 'run basic setup including logger configuration, environment info logging, and config backup to output directory', 'create an end-to-end predictor that loads a checkpoint and runs inference on a single BGR image', 'build a default trainer with model, optimizer, data loader, hooks, and checkpointing for standard training workflow', 'create a CallbackHook with before_train and after_train callback functions for the trainer', 'build an IterationTimer hook to track training iteration speed with configurable warmup iterations', 'run a PeriodicWriter hook to periodically write events to EventWriter objects every N iterations', 'test the PeriodicCheckpointer hook to save model checkpoints every N iterations during training', 'review the LRScheduler hook to execute a torch LR scheduler and summarize learning rate each step', 'launch multi-gpu or distributed training by spawning child processes per GPU on each machine', 'launch single GPU training by calling main_func directly when world size is one', 'launch distributed training with auto port selection for single machine jobs using dist_url auto', 'launch multi-machine distributed training with explicit dist_url and machine rank configuration', 'launch distributed training with a custom timeout for the distributed workers process group', 'create a custom training hook by subclassing HookBase and implementing before_train or after_step methods', 'register a list of HookBase hooks to a TrainerBase instance using the register_hooks method', 'run a standard single-optimizer training loop with a model, data_loader, and optimizer using SimpleTrainer', 'run automatic mixed precision training with a GradScaler using AMPTrainer for faster GPU training', 'save and restore training state including iteration count, optimizer, and hook states via state_dict and load_state_dict']
```

Usage

```
{'create_CallbackHook': 'create a CallbackHook with before_train and after_train callback functions for the trainer', 'build_IterationTimer': 'build an IterationTimer hook to track training iteration speed with configurable warmup iterations', 'run_PeriodicWriter': 'run a PeriodicWriter hook to periodically write events to EventWriter objects every N iterations', 'test_PeriodicCheckpointer': 'test the PeriodicCheckpointer hook to save model checkpoints every N iterations during training', 'review_LRScheduler': 'review the LRScheduler hook to execute a torch LR scheduler and summarize learning rate each step'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/engine/launch.py

Prompts

```
['create a DistributedDataParallel model from a torch module with optional fp16 compression hooks', 'build an argparse parser with common detectron2 training arguments like config file and resume flags', 'run basic setup including logger configuration, environment info logging, and config backup to output directory', 'create an end-to-end predictor that loads a checkpoint and runs inference on a single BGR image', 'build a default trainer with model, optimizer, data loader, hooks, and checkpointing for standard training workflow', 'create a CallbackHook with before_train and after_train callback functions for the trainer', 'build an IterationTimer hook to track training iteration speed with configurable warmup iterations', 'run a PeriodicWriter hook to periodically write events to EventWriter objects every N iterations', 'test the PeriodicCheckpointer hook to save model checkpoints every N iterations during training', 'review the LRScheduler hook to execute a torch LR scheduler and summarize learning rate each step', 'launch multi-gpu or distributed training by spawning child processes per GPU on each machine', 'launch single GPU training by calling main_func directly when world size is one', 'launch distributed training with auto port selection for single machine jobs using dist_url auto', 'launch multi-machine distributed training with explicit dist_url and machine rank configuration', 'launch distributed training with a custom timeout for the distributed workers process group', 'create a custom training hook by subclassing HookBase and implementing before_train or after_step methods', 'register a list of HookBase hooks to a TrainerBase instance using the register_hooks method', 'run a standard single-optimizer training loop with a model, data_loader, and optimizer using SimpleTrainer', 'run automatic mixed precision training with a GradScaler using AMPTrainer for faster GPU training', 'save and restore training state including iteration count, optimizer, and hook states via state_dict and load_state_dict']
```

Usage

```
{'launch_multi_gpu_training': 'launch multi-gpu or distributed training by spawning child processes per GPU on each machine', 'launch_single_gpu_training': 'launch single GPU training by calling main_func directly when world size is one', 'launch_auto_dist_url': 'launch distributed training with auto port selection for single machine jobs using dist_url auto', 'launch_multi_machine_training': 'launch multi-machine distributed training with explicit dist_url and machine rank configuration', 'launch_with_timeout': 'launch distributed training with a custom timeout for the distributed workers process group'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/engine/train_loop.py

Prompts

```
['create a DistributedDataParallel model from a torch module with optional fp16 compression hooks', 'build an argparse parser with common detectron2 training arguments like config file and resume flags', 'run basic setup including logger configuration, environment info logging, and config backup to output directory', 'create an end-to-end predictor that loads a checkpoint and runs inference on a single BGR image', 'build a default trainer with model, optimizer, data loader, hooks, and checkpointing for standard training workflow', 'create a CallbackHook with before_train and after_train callback functions for the trainer', 'build an IterationTimer hook to track training iteration speed with configurable warmup iterations', 'run a PeriodicWriter hook to periodically write events to EventWriter objects every N iterations', 'test the PeriodicCheckpointer hook to save model checkpoints every N iterations during training', 'review the LRScheduler hook to execute a torch LR scheduler and summarize learning rate each step', 'launch multi-gpu or distributed training by spawning child processes per GPU on each machine', 'launch single GPU training by calling main_func directly when world size is one', 'launch distributed training with auto port selection for single machine jobs using dist_url auto', 'launch multi-machine distributed training with explicit dist_url and machine rank configuration', 'launch distributed training with a custom timeout for the distributed workers process group', 'create a custom training hook by subclassing HookBase and implementing before_train or after_step methods', 'register a list of HookBase hooks to a TrainerBase instance using the register_hooks method', 'run a standard single-optimizer training loop with a model, data_loader, and optimizer using SimpleTrainer', 'run automatic mixed precision training with a GradScaler using AMPTrainer for faster GPU training', 'save and restore training state including iteration count, optimizer, and hook states via state_dict and load_state_dict']
```

Usage

```
{'create_HookBase_subclass': 'create a custom training hook by subclassing HookBase and implementing before_train or after_step methods', 'register_hooks_on_TrainerBase': 'register a list of HookBase hooks to a TrainerBase instance using the register_hooks method', 'run_SimpleTrainer_training_loop': 'run a standard single-optimizer training loop with a model, data_loader, and optimizer using SimpleTrainer', 'run_AMPTrainer_mixed_precision': 'run automatic mixed precision training with a GradScaler using AMPTrainer for faster GPU training', 'checkpoint_TrainerBase_state_dict': 'save and restore training state including iteration count, optimizer, and hook states via state_dict and load_state_dict'}
```

