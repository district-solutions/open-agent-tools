# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/detectron2/engine/defaults.py

Prompts

```
['create a DistributedDataParallel model wrapping a torch.nn.Module for multi-process training with optional fp16 compression', 'build an argparse.ArgumentParser with common detectron2 CLI arguments like config-file, resume, eval-only, and num-gpus', 'run basic job setup including logger configuration, environment info logging, config backup, and random seed initialization', 'create a single-image end-to-end predictor that loads checkpoints, handles BGR to RGB conversion, and applies resizing', 'build a default training loop with model, optimizer, data loader, LR scheduler, checkpointing, and evaluation hooks', 'create a CallbackHook with before_train and after_step callback functions for a detectron2 trainer', 'create an EvalHook that runs a custom evaluation function every N iterations during training', 'create a BestCheckpointer hook that saves the best model based on a validation metric like bbox/AP50', 'create a TorchProfiler hook to profile training iterations and export chrome trace files to an output directory', 'create a PreciseBN hook to compute true batch normalization statistics using a data loader during training', 'run multi-gpu distributed training by calling launch with a main function and number of GPUs per machine', 'run single GPU training by calling launch with num_gpus_per_machine set to 1', 'run distributed training with automatic port selection by setting dist_url to auto', 'run multi-machine distributed training by specifying num_machines and machine_rank in launch', 'run distributed training with a custom timeout value passed to the launch function', 'create a subclass of HookBase implementing before_train, after_train, before_step, and after_step lifecycle methods', 'register a list of HookBase instances onto a TrainerBase using register_hooks method', 'run a SimpleTrainer with a model, data_loader, and optimizer for single-cost iterative optimization', 'run an AMPTrainer with automatic mixed precision using GradScaler for CUDA training', 'save and restore trainer state including iteration, optimizer, and hook state via state_dict and load_state_dict']
```

Usage

```
{'create_ddp_model': 'create a DistributedDataParallel model wrapping a torch.nn.Module for multi-process training with optional fp16 compression', 'default_argument_parser': 'build an argparse.ArgumentParser with common detectron2 CLI arguments like config-file, resume, eval-only, and num-gpus', 'default_setup': 'run basic job setup including logger configuration, environment info logging, config backup, and random seed initialization', 'DefaultPredictor': 'create a single-image end-to-end predictor that loads checkpoints, handles BGR to RGB conversion, and applies resizing', 'DefaultTrainer': 'build a default training loop with model, optimizer, data loader, LR scheduler, checkpointing, and evaluation hooks'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/engine/hooks.py

Prompts

```
['create a DistributedDataParallel model wrapping a torch.nn.Module for multi-process training with optional fp16 compression', 'build an argparse.ArgumentParser with common detectron2 CLI arguments like config-file, resume, eval-only, and num-gpus', 'run basic job setup including logger configuration, environment info logging, config backup, and random seed initialization', 'create a single-image end-to-end predictor that loads checkpoints, handles BGR to RGB conversion, and applies resizing', 'build a default training loop with model, optimizer, data loader, LR scheduler, checkpointing, and evaluation hooks', 'create a CallbackHook with before_train and after_step callback functions for a detectron2 trainer', 'create an EvalHook that runs a custom evaluation function every N iterations during training', 'create a BestCheckpointer hook that saves the best model based on a validation metric like bbox/AP50', 'create a TorchProfiler hook to profile training iterations and export chrome trace files to an output directory', 'create a PreciseBN hook to compute true batch normalization statistics using a data loader during training', 'run multi-gpu distributed training by calling launch with a main function and number of GPUs per machine', 'run single GPU training by calling launch with num_gpus_per_machine set to 1', 'run distributed training with automatic port selection by setting dist_url to auto', 'run multi-machine distributed training by specifying num_machines and machine_rank in launch', 'run distributed training with a custom timeout value passed to the launch function', 'create a subclass of HookBase implementing before_train, after_train, before_step, and after_step lifecycle methods', 'register a list of HookBase instances onto a TrainerBase using register_hooks method', 'run a SimpleTrainer with a model, data_loader, and optimizer for single-cost iterative optimization', 'run an AMPTrainer with automatic mixed precision using GradScaler for CUDA training', 'save and restore trainer state including iteration, optimizer, and hook state via state_dict and load_state_dict']
```

Usage

```
{'create_CallbackHook': 'create a CallbackHook with before_train and after_step callback functions for a detectron2 trainer', 'create_EvalHook': 'create an EvalHook that runs a custom evaluation function every N iterations during training', 'create_BestCheckpointer': 'create a BestCheckpointer hook that saves the best model based on a validation metric like bbox/AP50', 'create_TorchProfiler': 'create a TorchProfiler hook to profile training iterations and export chrome trace files to an output directory', 'create_PreciseBN': 'create a PreciseBN hook to compute true batch normalization statistics using a data loader during training'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/engine/launch.py

Prompts

```
['create a DistributedDataParallel model wrapping a torch.nn.Module for multi-process training with optional fp16 compression', 'build an argparse.ArgumentParser with common detectron2 CLI arguments like config-file, resume, eval-only, and num-gpus', 'run basic job setup including logger configuration, environment info logging, config backup, and random seed initialization', 'create a single-image end-to-end predictor that loads checkpoints, handles BGR to RGB conversion, and applies resizing', 'build a default training loop with model, optimizer, data loader, LR scheduler, checkpointing, and evaluation hooks', 'create a CallbackHook with before_train and after_step callback functions for a detectron2 trainer', 'create an EvalHook that runs a custom evaluation function every N iterations during training', 'create a BestCheckpointer hook that saves the best model based on a validation metric like bbox/AP50', 'create a TorchProfiler hook to profile training iterations and export chrome trace files to an output directory', 'create a PreciseBN hook to compute true batch normalization statistics using a data loader during training', 'run multi-gpu distributed training by calling launch with a main function and number of GPUs per machine', 'run single GPU training by calling launch with num_gpus_per_machine set to 1', 'run distributed training with automatic port selection by setting dist_url to auto', 'run multi-machine distributed training by specifying num_machines and machine_rank in launch', 'run distributed training with a custom timeout value passed to the launch function', 'create a subclass of HookBase implementing before_train, after_train, before_step, and after_step lifecycle methods', 'register a list of HookBase instances onto a TrainerBase using register_hooks method', 'run a SimpleTrainer with a model, data_loader, and optimizer for single-cost iterative optimization', 'run an AMPTrainer with automatic mixed precision using GradScaler for CUDA training', 'save and restore trainer state including iteration, optimizer, and hook state via state_dict and load_state_dict']
```

Usage

```
{'run_distributed_training': 'run multi-gpu distributed training by calling launch with a main function and number of GPUs per machine', 'run_single_gpu_training': 'run single GPU training by calling launch with num_gpus_per_machine set to 1', 'run_auto_port_distributed': 'run distributed training with automatic port selection by setting dist_url to auto', 'run_multi_machine_training': 'run multi-machine distributed training by specifying num_machines and machine_rank in launch', 'run_distributed_with_timeout': 'run distributed training with a custom timeout value passed to the launch function'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/engine/train_loop.py

Prompts

```
['create a DistributedDataParallel model wrapping a torch.nn.Module for multi-process training with optional fp16 compression', 'build an argparse.ArgumentParser with common detectron2 CLI arguments like config-file, resume, eval-only, and num-gpus', 'run basic job setup including logger configuration, environment info logging, config backup, and random seed initialization', 'create a single-image end-to-end predictor that loads checkpoints, handles BGR to RGB conversion, and applies resizing', 'build a default training loop with model, optimizer, data loader, LR scheduler, checkpointing, and evaluation hooks', 'create a CallbackHook with before_train and after_step callback functions for a detectron2 trainer', 'create an EvalHook that runs a custom evaluation function every N iterations during training', 'create a BestCheckpointer hook that saves the best model based on a validation metric like bbox/AP50', 'create a TorchProfiler hook to profile training iterations and export chrome trace files to an output directory', 'create a PreciseBN hook to compute true batch normalization statistics using a data loader during training', 'run multi-gpu distributed training by calling launch with a main function and number of GPUs per machine', 'run single GPU training by calling launch with num_gpus_per_machine set to 1', 'run distributed training with automatic port selection by setting dist_url to auto', 'run multi-machine distributed training by specifying num_machines and machine_rank in launch', 'run distributed training with a custom timeout value passed to the launch function', 'create a subclass of HookBase implementing before_train, after_train, before_step, and after_step lifecycle methods', 'register a list of HookBase instances onto a TrainerBase using register_hooks method', 'run a SimpleTrainer with a model, data_loader, and optimizer for single-cost iterative optimization', 'run an AMPTrainer with automatic mixed precision using GradScaler for CUDA training', 'save and restore trainer state including iteration, optimizer, and hook state via state_dict and load_state_dict']
```

Usage

```
{'create_hookbase_subclass': 'create a subclass of HookBase implementing before_train, after_train, before_step, and after_step lifecycle methods', 'register_hooks_on_trainer': 'register a list of HookBase instances onto a TrainerBase using register_hooks method', 'run_simpletrainer_loop': 'run a SimpleTrainer with a model, data_loader, and optimizer for single-cost iterative optimization', 'run_amptrainer_loop': 'run an AMPTrainer with automatic mixed precision using GradScaler for CUDA training', 'checkpoint_trainer_state': 'save and restore trainer state including iteration, optimizer, and hook state via state_dict and load_state_dict'}
```

