# Agent Python Tools

- repo: facebookresearch/sam3
- repo_uri: https://github.com/facebookresearch/sam3

## File: facebookresearch_sam3/sam3/train/utils/checkpoint_utils.py

Prompts

```
['load a PyTorch checkpoint from a list of paths with optional recursive key selection and CPU mapping', 'load a checkpoint and apply preprocessing kernels like include or exclude patterns to the state dict', 'load a state dict into a PyTorch model with optional kernel preprocessing and strict mismatch handling', 'filter a model state dict to remove parameters matching given unix glob patterns', 'create a checkpoint kernel that removes state dict keys matching configurable unix glob patterns', 'build a distributed all-reduce sum operation across all GPU ranks for aggregating tensor values', 'create an all-gather call to collect arbitrary picklable data from all distributed ranks into a single list', 'test the GatherLayer autograd function that gathers tensors from all workers with full backward propagation support', 'refactor the init_distributed_data_parallel_model function to wrap a PyTorch model for DDP with configurable GPU or CPU device', 'review the broadcast_object function that serializes and broadcasts Python objects from a source rank to all workers via disk or memory', 'create a TensorBoard logger that writes scalar metrics to a specified log directory during training', 'log scalar training metrics to TensorBoard with a tag name and global step value', 'log multiple scalar metrics to TensorBoard in a single call using a dictionary payload and step', 'setup distributed training logging with console and file handlers filtered by process rank', 'log hyperparameters and corresponding meter values to TensorBoard for experiment tracking', 'build a distributed training setup by initializing torch.distributed with a configurable timeout and backend', 'create a module to register Hydra/OmegaConf resolvers for arithmetic, type conversion, and config merging operations', 'test the deterministic seeding of Python random, NumPy, and PyTorch across distributed GPU ranks', 'refactor the AverageMeter class to compute and store running averages and current values for training metrics', 'review the ProgressMeter class that displays training progress with multiple meters and batch formatting']
```

Usage

```
{'load_checkpoint': 'load a PyTorch checkpoint from a list of paths with optional recursive key selection and CPU mapping', 'load_checkpoint_and_apply_kernels': 'load a checkpoint and apply preprocessing kernels like include or exclude patterns to the state dict', 'load_state_dict_into_model': 'load a state dict into a PyTorch model with optional kernel preprocessing and strict mismatch handling', 'exclude_params_matching_unix_pattern': 'filter a model state dict to remove parameters matching given unix glob patterns', 'CkptExcludeKernel': 'create a checkpoint kernel that removes state dict keys matching configurable unix glob patterns'}
```

## File: facebookresearch_sam3/sam3/train/utils/distributed.py

Prompts

```
['load a PyTorch checkpoint from a list of paths with optional recursive key selection and CPU mapping', 'load a checkpoint and apply preprocessing kernels like include or exclude patterns to the state dict', 'load a state dict into a PyTorch model with optional kernel preprocessing and strict mismatch handling', 'filter a model state dict to remove parameters matching given unix glob patterns', 'create a checkpoint kernel that removes state dict keys matching configurable unix glob patterns', 'build a distributed all-reduce sum operation across all GPU ranks for aggregating tensor values', 'create an all-gather call to collect arbitrary picklable data from all distributed ranks into a single list', 'test the GatherLayer autograd function that gathers tensors from all workers with full backward propagation support', 'refactor the init_distributed_data_parallel_model function to wrap a PyTorch model for DDP with configurable GPU or CPU device', 'review the broadcast_object function that serializes and broadcasts Python objects from a source rank to all workers via disk or memory', 'create a TensorBoard logger that writes scalar metrics to a specified log directory during training', 'log scalar training metrics to TensorBoard with a tag name and global step value', 'log multiple scalar metrics to TensorBoard in a single call using a dictionary payload and step', 'setup distributed training logging with console and file handlers filtered by process rank', 'log hyperparameters and corresponding meter values to TensorBoard for experiment tracking', 'build a distributed training setup by initializing torch.distributed with a configurable timeout and backend', 'create a module to register Hydra/OmegaConf resolvers for arithmetic, type conversion, and config merging operations', 'test the deterministic seeding of Python random, NumPy, and PyTorch across distributed GPU ranks', 'refactor the AverageMeter class to compute and store running averages and current values for training metrics', 'review the ProgressMeter class that displays training progress with multiple meters and batch formatting']
```

Usage

```
{'build_all_reduce_sum': 'build a distributed all-reduce sum operation across all GPU ranks for aggregating tensor values', 'create_all_gather_picklable': 'create an all-gather call to collect arbitrary picklable data from all distributed ranks into a single list', 'test_gather_layer_backward': 'test the GatherLayer autograd function that gathers tensors from all workers with full backward propagation support', 'refactor_init_distributed_model': 'refactor the init_distributed_data_parallel_model function to wrap a PyTorch model for DDP with configurable GPU or CPU device', 'review_broadcast_object': 'review the broadcast_object function that serializes and broadcasts Python objects from a source rank to all workers via disk or memory'}
```

## File: facebookresearch_sam3/sam3/train/utils/logger.py

Prompts

```
['load a PyTorch checkpoint from a list of paths with optional recursive key selection and CPU mapping', 'load a checkpoint and apply preprocessing kernels like include or exclude patterns to the state dict', 'load a state dict into a PyTorch model with optional kernel preprocessing and strict mismatch handling', 'filter a model state dict to remove parameters matching given unix glob patterns', 'create a checkpoint kernel that removes state dict keys matching configurable unix glob patterns', 'build a distributed all-reduce sum operation across all GPU ranks for aggregating tensor values', 'create an all-gather call to collect arbitrary picklable data from all distributed ranks into a single list', 'test the GatherLayer autograd function that gathers tensors from all workers with full backward propagation support', 'refactor the init_distributed_data_parallel_model function to wrap a PyTorch model for DDP with configurable GPU or CPU device', 'review the broadcast_object function that serializes and broadcasts Python objects from a source rank to all workers via disk or memory', 'create a TensorBoard logger that writes scalar metrics to a specified log directory during training', 'log scalar training metrics to TensorBoard with a tag name and global step value', 'log multiple scalar metrics to TensorBoard in a single call using a dictionary payload and step', 'setup distributed training logging with console and file handlers filtered by process rank', 'log hyperparameters and corresponding meter values to TensorBoard for experiment tracking', 'build a distributed training setup by initializing torch.distributed with a configurable timeout and backend', 'create a module to register Hydra/OmegaConf resolvers for arithmetic, type conversion, and config merging operations', 'test the deterministic seeding of Python random, NumPy, and PyTorch across distributed GPU ranks', 'refactor the AverageMeter class to compute and store running averages and current values for training metrics', 'review the ProgressMeter class that displays training progress with multiple meters and batch formatting']
```

Usage

```
{'create_tensorboard_logger': 'create a TensorBoard logger that writes scalar metrics to a specified log directory during training', 'log_scalar_metrics': 'log scalar training metrics to TensorBoard with a tag name and global step value', 'log_multiple_metrics': 'log multiple scalar metrics to TensorBoard in a single call using a dictionary payload and step', 'setup_logging': 'setup distributed training logging with console and file handlers filtered by process rank', 'log_hyperparameters': 'log hyperparameters and corresponding meter values to TensorBoard for experiment tracking'}
```

## File: facebookresearch_sam3/sam3/train/utils/train_utils.py

Prompts

```
['load a PyTorch checkpoint from a list of paths with optional recursive key selection and CPU mapping', 'load a checkpoint and apply preprocessing kernels like include or exclude patterns to the state dict', 'load a state dict into a PyTorch model with optional kernel preprocessing and strict mismatch handling', 'filter a model state dict to remove parameters matching given unix glob patterns', 'create a checkpoint kernel that removes state dict keys matching configurable unix glob patterns', 'build a distributed all-reduce sum operation across all GPU ranks for aggregating tensor values', 'create an all-gather call to collect arbitrary picklable data from all distributed ranks into a single list', 'test the GatherLayer autograd function that gathers tensors from all workers with full backward propagation support', 'refactor the init_distributed_data_parallel_model function to wrap a PyTorch model for DDP with configurable GPU or CPU device', 'review the broadcast_object function that serializes and broadcasts Python objects from a source rank to all workers via disk or memory', 'create a TensorBoard logger that writes scalar metrics to a specified log directory during training', 'log scalar training metrics to TensorBoard with a tag name and global step value', 'log multiple scalar metrics to TensorBoard in a single call using a dictionary payload and step', 'setup distributed training logging with console and file handlers filtered by process rank', 'log hyperparameters and corresponding meter values to TensorBoard for experiment tracking', 'build a distributed training setup by initializing torch.distributed with a configurable timeout and backend', 'create a module to register Hydra/OmegaConf resolvers for arithmetic, type conversion, and config merging operations', 'test the deterministic seeding of Python random, NumPy, and PyTorch across distributed GPU ranks', 'refactor the AverageMeter class to compute and store running averages and current values for training metrics', 'review the ProgressMeter class that displays training progress with multiple meters and batch formatting']
```

Usage

```
{'build_setup_distributed_backend': 'build a distributed training setup by initializing torch.distributed with a configurable timeout and backend', 'create_register_omegaconf_resolvers': 'create a module to register Hydra/OmegaConf resolvers for arithmetic, type conversion, and config merging operations', 'test_set_seeds': 'test the deterministic seeding of Python random, NumPy, and PyTorch across distributed GPU ranks', 'refactor_average_meter': 'refactor the AverageMeter class to compute and store running averages and current values for training metrics', 'review_progress_meter': 'review the ProgressMeter class that displays training progress with multiple meters and batch formatting'}
```

