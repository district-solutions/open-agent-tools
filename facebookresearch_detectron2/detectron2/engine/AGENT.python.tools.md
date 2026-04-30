# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/detectron2/engine/defaults.py

Prompts

```
['create a DistributedDataParallel model from a torch.nn.Module for multi-GPU training', 'parse command line arguments for detectron2 training including config file, GPUs, and distributed settings', 'setup detectron2 training environment with logger, config backup, seeding, and precision settings', 'create a DefaultPredictor that loads a model checkpoint and runs inference on a single image', 'build a DefaultTrainer with model, optimizer, dataloader, hooks, and checkpointing for standard training', 'run an evaluation function periodically during training with EvalHook', 'create a training hook with custom before and after step callbacks using CallbackHook', 'run torch profiler during training iterations with TorchProfiler hook', 'run precise batch norm statistics update hook on model during training', 'build a checkpoint hook that saves the best model weights based on a validation metric', 'run distributed training by launching multi-process workers across multiple GPUs and machines', 'run single-machine multi-GPU training with auto-selected free port for distributed initialization', 'run multi-machine distributed training with TCP-based process group initialization', 'find an available network port by binding to port 0 and retrieving the assigned port', 'setup distributed worker process with NCCL or GLOO backend and local process group', 'build a HookBase subclass to register custom callbacks before and after each training step', 'create a TrainerBase subclass with a custom run_step implementation for iterative training loops', 'create a SimpleTrainer instance with a model, data loader, and optimizer for standard single-cost training', 'create an AMPTrainer instance with automatic mixed precision using autocast and grad scaler', 'test the TrainerBase register_hooks method to verify hooks execute in order during training']
```

Usage

```
{'create_ddp_model': 'create a DistributedDataParallel model from a torch.nn.Module for multi-GPU training', 'parse_training_arguments': 'parse command line arguments for detectron2 training including config file, GPUs, and distributed settings', 'setup_training_environment': 'setup detectron2 training environment with logger, config backup, seeding, and precision settings', 'create_prediction_pipeline': 'create a DefaultPredictor that loads a model checkpoint and runs inference on a single image', 'build_training_loop': 'build a DefaultTrainer with model, optimizer, dataloader, hooks, and checkpointing for standard training'}
```

## File: facebookresearch_detectron2/detectron2/engine/hooks.py

Prompts

```
['create a DistributedDataParallel model from a torch.nn.Module for multi-GPU training', 'parse command line arguments for detectron2 training including config file, GPUs, and distributed settings', 'setup detectron2 training environment with logger, config backup, seeding, and precision settings', 'create a DefaultPredictor that loads a model checkpoint and runs inference on a single image', 'build a DefaultTrainer with model, optimizer, dataloader, hooks, and checkpointing for standard training', 'run an evaluation function periodically during training with EvalHook', 'create a training hook with custom before and after step callbacks using CallbackHook', 'run torch profiler during training iterations with TorchProfiler hook', 'run precise batch norm statistics update hook on model during training', 'build a checkpoint hook that saves the best model weights based on a validation metric', 'run distributed training by launching multi-process workers across multiple GPUs and machines', 'run single-machine multi-GPU training with auto-selected free port for distributed initialization', 'run multi-machine distributed training with TCP-based process group initialization', 'find an available network port by binding to port 0 and retrieving the assigned port', 'setup distributed worker process with NCCL or GLOO backend and local process group', 'build a HookBase subclass to register custom callbacks before and after each training step', 'create a TrainerBase subclass with a custom run_step implementation for iterative training loops', 'create a SimpleTrainer instance with a model, data loader, and optimizer for standard single-cost training', 'create an AMPTrainer instance with automatic mixed precision using autocast and grad scaler', 'test the TrainerBase register_hooks method to verify hooks execute in order during training']
```

Usage

```
{'run_hook_eval_periodically': 'run an evaluation function periodically during training with EvalHook', 'create_hook_custom_callbacks': 'create a training hook with custom before and after step callbacks using CallbackHook', 'run_hook_profile_model': 'run torch profiler during training iterations with TorchProfiler hook', 'run_hook_compute_precise_bn': 'run precise batch norm statistics update hook on model during training', 'build_hook_checkpoint_best': 'build a checkpoint hook that saves the best model weights based on a validation metric'}
```

## File: facebookresearch_detectron2/detectron2/engine/launch.py

Prompts

```
['create a DistributedDataParallel model from a torch.nn.Module for multi-GPU training', 'parse command line arguments for detectron2 training including config file, GPUs, and distributed settings', 'setup detectron2 training environment with logger, config backup, seeding, and precision settings', 'create a DefaultPredictor that loads a model checkpoint and runs inference on a single image', 'build a DefaultTrainer with model, optimizer, dataloader, hooks, and checkpointing for standard training', 'run an evaluation function periodically during training with EvalHook', 'create a training hook with custom before and after step callbacks using CallbackHook', 'run torch profiler during training iterations with TorchProfiler hook', 'run precise batch norm statistics update hook on model during training', 'build a checkpoint hook that saves the best model weights based on a validation metric', 'run distributed training by launching multi-process workers across multiple GPUs and machines', 'run single-machine multi-GPU training with auto-selected free port for distributed initialization', 'run multi-machine distributed training with TCP-based process group initialization', 'find an available network port by binding to port 0 and retrieving the assigned port', 'setup distributed worker process with NCCL or GLOO backend and local process group', 'build a HookBase subclass to register custom callbacks before and after each training step', 'create a TrainerBase subclass with a custom run_step implementation for iterative training loops', 'create a SimpleTrainer instance with a model, data loader, and optimizer for standard single-cost training', 'create an AMPTrainer instance with automatic mixed precision using autocast and grad scaler', 'test the TrainerBase register_hooks method to verify hooks execute in order during training']
```

Usage

```
{'run_launch_distributed_training': 'run distributed training by launching multi-process workers across multiple GPUs and machines', 'run_launch_single_machine_training': 'run single-machine multi-GPU training with auto-selected free port for distributed initialization', 'run_launch_multi_machine_training': 'run multi-machine distributed training with TCP-based process group initialization', 'run_find_free_port': 'find an available network port by binding to port 0 and retrieving the assigned port', 'run_distributed_worker_setup': 'setup distributed worker process with NCCL or GLOO backend and local process group'}
```

## File: facebookresearch_detectron2/detectron2/engine/train_loop.py

Prompts

```
['create a DistributedDataParallel model from a torch.nn.Module for multi-GPU training', 'parse command line arguments for detectron2 training including config file, GPUs, and distributed settings', 'setup detectron2 training environment with logger, config backup, seeding, and precision settings', 'create a DefaultPredictor that loads a model checkpoint and runs inference on a single image', 'build a DefaultTrainer with model, optimizer, dataloader, hooks, and checkpointing for standard training', 'run an evaluation function periodically during training with EvalHook', 'create a training hook with custom before and after step callbacks using CallbackHook', 'run torch profiler during training iterations with TorchProfiler hook', 'run precise batch norm statistics update hook on model during training', 'build a checkpoint hook that saves the best model weights based on a validation metric', 'run distributed training by launching multi-process workers across multiple GPUs and machines', 'run single-machine multi-GPU training with auto-selected free port for distributed initialization', 'run multi-machine distributed training with TCP-based process group initialization', 'find an available network port by binding to port 0 and retrieving the assigned port', 'setup distributed worker process with NCCL or GLOO backend and local process group', 'build a HookBase subclass to register custom callbacks before and after each training step', 'create a TrainerBase subclass with a custom run_step implementation for iterative training loops', 'create a SimpleTrainer instance with a model, data loader, and optimizer for standard single-cost training', 'create an AMPTrainer instance with automatic mixed precision using autocast and grad scaler', 'test the TrainerBase register_hooks method to verify hooks execute in order during training']
```

Usage

```
{'build_hook_base': 'build a HookBase subclass to register custom callbacks before and after each training step', 'create_trainer_base': 'create a TrainerBase subclass with a custom run_step implementation for iterative training loops', 'create_simple_trainer': 'create a SimpleTrainer instance with a model, data loader, and optimizer for standard single-cost training', 'create_amp_trainer': 'create an AMPTrainer instance with automatic mixed precision using autocast and grad scaler', 'test_trainer_hooks': 'test the TrainerBase register_hooks method to verify hooks execute in order during training'}
```

