# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/engine/mmengine/model/wrappers/distributed.py

Prompts

```
['build a distributed model wrapper using MMDistributedDataParallel for multi-GPU training with automatic gradient synchronization', 'run a training step with data and optim_wrapper to compute losses and update model parameters', 'run a validation step to get model predictions on sampled validation data', 'run a test step to get model predictions on sampled test data', 'review the MMDistributedDataParallel class to detect anomalous parameters not included in the computational graph', 'wrap a PyTorch nn.Module with MMFullyShardedDataParallel for sharded data parallel training', 'get the optimizer state dict from an FSDP-wrapped model using optim_state_dict static method', 'wrap a GAN model with separate DistributedDataParallel for generator and discriminator submodules', 'run a training step on the separately wrapped DDP model with data and optimizer', 'run a validation step on the separately wrapped DDP model to get predictions', 'run a test step on the separately wrapped DDP model to get predictions', 'use the no_sync context manager to skip gradient synchronization across submodules', 'check if a PyTorch nn.Module is a model wrapper like DataParallel or DistributedDataParallel', 'check if a model is a wrapper using a custom Registry instead of the default MODEL_WRAPPERS', 'review the is_model_wrapper function that recursively checks child registries for wrapper types', 'test the is_model_wrapper function with a DataParallel or MMDistributedDataParallel model instance', 'summarize the is_model_wrapper utility that checks if a module belongs to registered model wrapper types']
```

Usage

```
{'build_MMDistributedDataParallel': 'build a distributed model wrapper using MMDistributedDataParallel for multi-GPU training with automatic gradient synchronization', 'run_train_step': 'run a training step with data and optim_wrapper to compute losses and update model parameters', 'run_val_step': 'run a validation step to get model predictions on sampled validation data', 'run_test_step': 'run a test step to get model predictions on sampled test data', 'review_detect_anomalous_params': 'review the MMDistributedDataParallel class to detect anomalous parameters not included in the computational graph'}
```

## File: facebookresearch_sapiens/engine/mmengine/model/wrappers/fully_sharded_distributed.py

Prompts

```
['build a distributed model wrapper using MMDistributedDataParallel for multi-GPU training with automatic gradient synchronization', 'run a training step with data and optim_wrapper to compute losses and update model parameters', 'run a validation step to get model predictions on sampled validation data', 'run a test step to get model predictions on sampled test data', 'review the MMDistributedDataParallel class to detect anomalous parameters not included in the computational graph', 'wrap a PyTorch nn.Module with MMFullyShardedDataParallel for sharded data parallel training', 'get the optimizer state dict from an FSDP-wrapped model using optim_state_dict static method', 'wrap a GAN model with separate DistributedDataParallel for generator and discriminator submodules', 'run a training step on the separately wrapped DDP model with data and optimizer', 'run a validation step on the separately wrapped DDP model to get predictions', 'run a test step on the separately wrapped DDP model to get predictions', 'use the no_sync context manager to skip gradient synchronization across submodules', 'check if a PyTorch nn.Module is a model wrapper like DataParallel or DistributedDataParallel', 'check if a model is a wrapper using a custom Registry instead of the default MODEL_WRAPPERS', 'review the is_model_wrapper function that recursively checks child registries for wrapper types', 'test the is_model_wrapper function with a DataParallel or MMDistributedDataParallel model instance', 'summarize the is_model_wrapper utility that checks if a module belongs to registered model wrapper types']
```

Usage

```
{'wrap_model_with_fsdp': 'wrap a PyTorch nn.Module with MMFullyShardedDataParallel for sharded data parallel training', 'run_train_step': 'run a training step with MMFullyShardedDataParallel that performs forward, backward, and parameter update', 'run_val_step': 'run a validation step with MMFullyShardedDataParallel to get inference predictions on data', 'run_test_step': 'run a test step with MMFullyShardedDataParallel to get inference predictions on test data', 'get_optim_state_dict': 'get the optimizer state dict from an FSDP-wrapped model using optim_state_dict static method'}
```

## File: facebookresearch_sapiens/engine/mmengine/model/wrappers/seperate_distributed.py

Prompts

```
['build a distributed model wrapper using MMDistributedDataParallel for multi-GPU training with automatic gradient synchronization', 'run a training step with data and optim_wrapper to compute losses and update model parameters', 'run a validation step to get model predictions on sampled validation data', 'run a test step to get model predictions on sampled test data', 'review the MMDistributedDataParallel class to detect anomalous parameters not included in the computational graph', 'wrap a PyTorch nn.Module with MMFullyShardedDataParallel for sharded data parallel training', 'get the optimizer state dict from an FSDP-wrapped model using optim_state_dict static method', 'wrap a GAN model with separate DistributedDataParallel for generator and discriminator submodules', 'run a training step on the separately wrapped DDP model with data and optimizer', 'run a validation step on the separately wrapped DDP model to get predictions', 'run a test step on the separately wrapped DDP model to get predictions', 'use the no_sync context manager to skip gradient synchronization across submodules', 'check if a PyTorch nn.Module is a model wrapper like DataParallel or DistributedDataParallel', 'check if a model is a wrapper using a custom Registry instead of the default MODEL_WRAPPERS', 'review the is_model_wrapper function that recursively checks child registries for wrapper types', 'test the is_model_wrapper function with a DataParallel or MMDistributedDataParallel model instance', 'summarize the is_model_wrapper utility that checks if a module belongs to registered model wrapper types']
```

Usage

```
{'wrap_model_separate_ddp': 'wrap a GAN model with separate DistributedDataParallel for generator and discriminator submodules', 'train_step_separate_ddp': 'run a training step on the separately wrapped DDP model with data and optimizer', 'val_step_separate_ddp': 'run a validation step on the separately wrapped DDP model to get predictions', 'test_step_separate_ddp': 'run a test step on the separately wrapped DDP model to get predictions', 'no_sync_separate_ddp': 'use the no_sync context manager to skip gradient synchronization across submodules'}
```

## File: facebookresearch_sapiens/engine/mmengine/model/wrappers/utils.py

Prompts

```
['build a distributed model wrapper using MMDistributedDataParallel for multi-GPU training with automatic gradient synchronization', 'run a training step with data and optim_wrapper to compute losses and update model parameters', 'run a validation step to get model predictions on sampled validation data', 'run a test step to get model predictions on sampled test data', 'review the MMDistributedDataParallel class to detect anomalous parameters not included in the computational graph', 'wrap a PyTorch nn.Module with MMFullyShardedDataParallel for sharded data parallel training', 'get the optimizer state dict from an FSDP-wrapped model using optim_state_dict static method', 'wrap a GAN model with separate DistributedDataParallel for generator and discriminator submodules', 'run a training step on the separately wrapped DDP model with data and optimizer', 'run a validation step on the separately wrapped DDP model to get predictions', 'run a test step on the separately wrapped DDP model to get predictions', 'use the no_sync context manager to skip gradient synchronization across submodules', 'check if a PyTorch nn.Module is a model wrapper like DataParallel or DistributedDataParallel', 'check if a model is a wrapper using a custom Registry instead of the default MODEL_WRAPPERS', 'review the is_model_wrapper function that recursively checks child registries for wrapper types', 'test the is_model_wrapper function with a DataParallel or MMDistributedDataParallel model instance', 'summarize the is_model_wrapper utility that checks if a module belongs to registered model wrapper types']
```

Usage

```
{'check_is_model_wrapper': 'check if a PyTorch nn.Module is a model wrapper like DataParallel or DistributedDataParallel', 'check_is_model_wrapper_custom_registry': 'check if a model is a wrapper using a custom Registry instead of the default MODEL_WRAPPERS', 'review_is_model_wrapper_recursive': 'review the is_model_wrapper function that recursively checks child registries for wrapper types', 'test_is_model_wrapper': 'test the is_model_wrapper function with a DataParallel or MMDistributedDataParallel model instance', 'summarize_is_model_wrapper': 'summarize the is_model_wrapper utility that checks if a module belongs to registered model wrapper types'}
```

