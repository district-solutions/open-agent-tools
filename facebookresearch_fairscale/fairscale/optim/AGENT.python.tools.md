# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/optim/adam.py

Prompts

```
['create a FusedAdam optimizer with mixed precision for FP16 model parameters on GPU', 'create an Adam optimizer with a custom learning rate and beta values for training', 'run a single optimization step with the FusedAdam optimizer to update model parameters', 'review the Precision enum to choose between FULL_PRECISION, MIXED_PRECISION, or PURE_FP16 modes', 'review the _MultiDeviceReplicator class for lazy per-device tensor copying and caching', 'create an AdaScale optimizer wrapping SGD for distributed large batch training', 'create an AdaScaleWrapper optimizer with model parameters and SGD class', 'review the AdaScale gain method to understand learning rate scaling ratio', 'refactor the AdaScale set_scale method to update batch size scaling factor', 'test the AdaScale step method to verify scaled learning rate optimizer updates', 'create a ShardedGradScaler instance with custom init_scale, growth_factor, and process_group parameters', "scale a loss tensor or list of tensors by the GradScaler's current scale factor", 'unscale the gradients of an SGD optimizer and synchronize inf detection across distributed ranks', 'step an optimizer with gradient scaling, automatically calling unscale and skipping steps on inf/NaN', "update the GradScaler's scale factor based on detected inf/NaN gradients or set a new manual scale", 'create a LayerwiseGradientScaler for a PyTorch model with per-layer gradient scaling factors', 'call the scale method on a LayerwiseGradientScaler to register backward hooks before loss backward pass', 'call the unscale method on a LayerwiseGradientScaler to unscale gradients and remove backward hooks', 'call the step method on a LayerwiseGradientScaler to conditionally run optimizer step and update scales', 'get the list of LayerInfo objects from a LayerwiseGradientScaler to inspect per-layer scaling factors', 'create an OSS sharded optimizer wrapping Adam with lr 0.01 for distributed training', 'run a single OSS optimizer step to update and broadcast sharded parameters across ranks', 'clip the OSS optimizer gradients to a max norm across all distributed ranks', 'consolidate the OSS optimizer state dict from all ranks to a single recipient rank', 'refresh the OSS optimizer partitioning after freezing or unfreezing model parameters']
```

Usage

```
{'create_fused_adam_optimizer': 'create a FusedAdam optimizer with mixed precision for FP16 model parameters on GPU', 'create_adam_with_custom_lr': 'create an Adam optimizer with a custom learning rate and beta values for training', 'run_adam_step': 'run a single optimization step with the FusedAdam optimizer to update model parameters', 'review_precision_enum': 'review the Precision enum to choose between FULL_PRECISION, MIXED_PRECISION, or PURE_FP16 modes', 'review_multidevicereplicator': 'review the _MultiDeviceReplicator class for lazy per-device tensor copying and caching'}
```

## File: facebookresearch_fairscale/fairscale/optim/adascale.py

Prompts

```
['create a FusedAdam optimizer with mixed precision for FP16 model parameters on GPU', 'create an Adam optimizer with a custom learning rate and beta values for training', 'run a single optimization step with the FusedAdam optimizer to update model parameters', 'review the Precision enum to choose between FULL_PRECISION, MIXED_PRECISION, or PURE_FP16 modes', 'review the _MultiDeviceReplicator class for lazy per-device tensor copying and caching', 'create an AdaScale optimizer wrapping SGD for distributed large batch training', 'create an AdaScaleWrapper optimizer with model parameters and SGD class', 'review the AdaScale gain method to understand learning rate scaling ratio', 'refactor the AdaScale set_scale method to update batch size scaling factor', 'test the AdaScale step method to verify scaled learning rate optimizer updates', 'create a ShardedGradScaler instance with custom init_scale, growth_factor, and process_group parameters', "scale a loss tensor or list of tensors by the GradScaler's current scale factor", 'unscale the gradients of an SGD optimizer and synchronize inf detection across distributed ranks', 'step an optimizer with gradient scaling, automatically calling unscale and skipping steps on inf/NaN', "update the GradScaler's scale factor based on detected inf/NaN gradients or set a new manual scale", 'create a LayerwiseGradientScaler for a PyTorch model with per-layer gradient scaling factors', 'call the scale method on a LayerwiseGradientScaler to register backward hooks before loss backward pass', 'call the unscale method on a LayerwiseGradientScaler to unscale gradients and remove backward hooks', 'call the step method on a LayerwiseGradientScaler to conditionally run optimizer step and update scales', 'get the list of LayerInfo objects from a LayerwiseGradientScaler to inspect per-layer scaling factors', 'create an OSS sharded optimizer wrapping Adam with lr 0.01 for distributed training', 'run a single OSS optimizer step to update and broadcast sharded parameters across ranks', 'clip the OSS optimizer gradients to a max norm across all distributed ranks', 'consolidate the OSS optimizer state dict from all ranks to a single recipient rank', 'refresh the OSS optimizer partitioning after freezing or unfreezing model parameters']
```

Usage

```
{'create_adascale_optimizer': 'create an AdaScale optimizer wrapping SGD for distributed large batch training', 'create_adascale_wrapper': 'create an AdaScaleWrapper optimizer with model parameters and SGD class', 'review_adascale_gain': 'review the AdaScale gain method to understand learning rate scaling ratio', 'refactor_adascale_set_scale': 'refactor the AdaScale set_scale method to update batch size scaling factor', 'test_adascale_step': 'test the AdaScale step method to verify scaled learning rate optimizer updates'}
```

## File: facebookresearch_fairscale/fairscale/optim/grad_scaler.py

Prompts

```
['create a FusedAdam optimizer with mixed precision for FP16 model parameters on GPU', 'create an Adam optimizer with a custom learning rate and beta values for training', 'run a single optimization step with the FusedAdam optimizer to update model parameters', 'review the Precision enum to choose between FULL_PRECISION, MIXED_PRECISION, or PURE_FP16 modes', 'review the _MultiDeviceReplicator class for lazy per-device tensor copying and caching', 'create an AdaScale optimizer wrapping SGD for distributed large batch training', 'create an AdaScaleWrapper optimizer with model parameters and SGD class', 'review the AdaScale gain method to understand learning rate scaling ratio', 'refactor the AdaScale set_scale method to update batch size scaling factor', 'test the AdaScale step method to verify scaled learning rate optimizer updates', 'create a ShardedGradScaler instance with custom init_scale, growth_factor, and process_group parameters', "scale a loss tensor or list of tensors by the GradScaler's current scale factor", 'unscale the gradients of an SGD optimizer and synchronize inf detection across distributed ranks', 'step an optimizer with gradient scaling, automatically calling unscale and skipping steps on inf/NaN', "update the GradScaler's scale factor based on detected inf/NaN gradients or set a new manual scale", 'create a LayerwiseGradientScaler for a PyTorch model with per-layer gradient scaling factors', 'call the scale method on a LayerwiseGradientScaler to register backward hooks before loss backward pass', 'call the unscale method on a LayerwiseGradientScaler to unscale gradients and remove backward hooks', 'call the step method on a LayerwiseGradientScaler to conditionally run optimizer step and update scales', 'get the list of LayerInfo objects from a LayerwiseGradientScaler to inspect per-layer scaling factors', 'create an OSS sharded optimizer wrapping Adam with lr 0.01 for distributed training', 'run a single OSS optimizer step to update and broadcast sharded parameters across ranks', 'clip the OSS optimizer gradients to a max norm across all distributed ranks', 'consolidate the OSS optimizer state dict from all ranks to a single recipient rank', 'refresh the OSS optimizer partitioning after freezing or unfreezing model parameters']
```

Usage

```
{'create_shardedgradscaler': 'create a ShardedGradScaler instance with custom init_scale, growth_factor, and process_group parameters', 'scale_loss_tensors': "scale a loss tensor or list of tensors by the GradScaler's current scale factor", 'unscale_optimizer_grads': 'unscale the gradients of an SGD optimizer and synchronize inf detection across distributed ranks', 'step_optimizer_with_scaler': 'step an optimizer with gradient scaling, automatically calling unscale and skipping steps on inf/NaN', 'update_scaler_scale': "update the GradScaler's scale factor based on detected inf/NaN gradients or set a new manual scale"}
```

## File: facebookresearch_fairscale/fairscale/optim/layerwise_gradient_scaler.py

Prompts

```
['create a FusedAdam optimizer with mixed precision for FP16 model parameters on GPU', 'create an Adam optimizer with a custom learning rate and beta values for training', 'run a single optimization step with the FusedAdam optimizer to update model parameters', 'review the Precision enum to choose between FULL_PRECISION, MIXED_PRECISION, or PURE_FP16 modes', 'review the _MultiDeviceReplicator class for lazy per-device tensor copying and caching', 'create an AdaScale optimizer wrapping SGD for distributed large batch training', 'create an AdaScaleWrapper optimizer with model parameters and SGD class', 'review the AdaScale gain method to understand learning rate scaling ratio', 'refactor the AdaScale set_scale method to update batch size scaling factor', 'test the AdaScale step method to verify scaled learning rate optimizer updates', 'create a ShardedGradScaler instance with custom init_scale, growth_factor, and process_group parameters', "scale a loss tensor or list of tensors by the GradScaler's current scale factor", 'unscale the gradients of an SGD optimizer and synchronize inf detection across distributed ranks', 'step an optimizer with gradient scaling, automatically calling unscale and skipping steps on inf/NaN', "update the GradScaler's scale factor based on detected inf/NaN gradients or set a new manual scale", 'create a LayerwiseGradientScaler for a PyTorch model with per-layer gradient scaling factors', 'call the scale method on a LayerwiseGradientScaler to register backward hooks before loss backward pass', 'call the unscale method on a LayerwiseGradientScaler to unscale gradients and remove backward hooks', 'call the step method on a LayerwiseGradientScaler to conditionally run optimizer step and update scales', 'get the list of LayerInfo objects from a LayerwiseGradientScaler to inspect per-layer scaling factors', 'create an OSS sharded optimizer wrapping Adam with lr 0.01 for distributed training', 'run a single OSS optimizer step to update and broadcast sharded parameters across ranks', 'clip the OSS optimizer gradients to a max norm across all distributed ranks', 'consolidate the OSS optimizer state dict from all ranks to a single recipient rank', 'refresh the OSS optimizer partitioning after freezing or unfreezing model parameters']
```

Usage

```
{'create_LayerwiseGradientScaler': 'create a LayerwiseGradientScaler for a PyTorch model with per-layer gradient scaling factors', 'call_scale_method': 'call the scale method on a LayerwiseGradientScaler to register backward hooks before loss backward pass', 'call_unscale_method': 'call the unscale method on a LayerwiseGradientScaler to unscale gradients and remove backward hooks', 'call_step_method': 'call the step method on a LayerwiseGradientScaler to conditionally run optimizer step and update scales', 'get_layer_info': 'get the list of LayerInfo objects from a LayerwiseGradientScaler to inspect per-layer scaling factors'}
```

## File: facebookresearch_fairscale/fairscale/optim/oss.py

Prompts

```
['create a FusedAdam optimizer with mixed precision for FP16 model parameters on GPU', 'create an Adam optimizer with a custom learning rate and beta values for training', 'run a single optimization step with the FusedAdam optimizer to update model parameters', 'review the Precision enum to choose between FULL_PRECISION, MIXED_PRECISION, or PURE_FP16 modes', 'review the _MultiDeviceReplicator class for lazy per-device tensor copying and caching', 'create an AdaScale optimizer wrapping SGD for distributed large batch training', 'create an AdaScaleWrapper optimizer with model parameters and SGD class', 'review the AdaScale gain method to understand learning rate scaling ratio', 'refactor the AdaScale set_scale method to update batch size scaling factor', 'test the AdaScale step method to verify scaled learning rate optimizer updates', 'create a ShardedGradScaler instance with custom init_scale, growth_factor, and process_group parameters', "scale a loss tensor or list of tensors by the GradScaler's current scale factor", 'unscale the gradients of an SGD optimizer and synchronize inf detection across distributed ranks', 'step an optimizer with gradient scaling, automatically calling unscale and skipping steps on inf/NaN', "update the GradScaler's scale factor based on detected inf/NaN gradients or set a new manual scale", 'create a LayerwiseGradientScaler for a PyTorch model with per-layer gradient scaling factors', 'call the scale method on a LayerwiseGradientScaler to register backward hooks before loss backward pass', 'call the unscale method on a LayerwiseGradientScaler to unscale gradients and remove backward hooks', 'call the step method on a LayerwiseGradientScaler to conditionally run optimizer step and update scales', 'get the list of LayerInfo objects from a LayerwiseGradientScaler to inspect per-layer scaling factors', 'create an OSS sharded optimizer wrapping Adam with lr 0.01 for distributed training', 'run a single OSS optimizer step to update and broadcast sharded parameters across ranks', 'clip the OSS optimizer gradients to a max norm across all distributed ranks', 'consolidate the OSS optimizer state dict from all ranks to a single recipient rank', 'refresh the OSS optimizer partitioning after freezing or unfreezing model parameters']
```

Usage

```
{'create_OSS_optimizer': 'create an OSS sharded optimizer wrapping Adam with lr 0.01 for distributed training', 'run_OSS_step': 'run a single OSS optimizer step to update and broadcast sharded parameters across ranks', 'clip_OSS_grad_norm': 'clip the OSS optimizer gradients to a max norm across all distributed ranks', 'consolidate_OSS_state_dict': 'consolidate the OSS optimizer state dict from all ranks to a single recipient rank', 'refresh_OSS_trainable': 'refresh the OSS optimizer partitioning after freezing or unfreezing model parameters'}
```

