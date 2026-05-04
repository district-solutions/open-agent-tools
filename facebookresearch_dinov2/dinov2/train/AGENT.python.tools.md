# Agent Python Tools

- repo: facebookresearch/dinov2
- repo_uri: https://github.com/facebookresearch/dinov2.git

## File: facebookresearch_dinov2/dinov2/train/ssl_meta_arch.py

Prompts

```
['build a SSLMetaArch instance from a config to create student and teacher models for DINOv2 training', 'run the forward_backward method on SSLMetaArch to compute DINO and iBOT losses and backpropagate gradients', 'update teacher model weights via exponential moving average using SSLMetaArch update_teacher method with momentum factor', 'prepare the SSLMetaArch student and teacher models for distributed FSDP training across multiple GPUs', 'get fused parameter groups with layer-wise decay for the SSLMetaArch student submodels to configure the optimizer', 'run DINOv2 self-supervised training with a config file and optional resume flag', 'build an AdamW optimizer with configurable beta1 and beta2 from config and param groups', 'build cosine schedulers for learning rate, weight decay, momentum, and teacher temperature', 'apply learning rate and weight decay schedules to optimizer param groups with last layer support', 'save the teacher model state dict as a checkpoint for evaluation at a given iteration']
```

Usage

```
{'build_ssl_meta_arch': 'build a SSLMetaArch instance from a config to create student and teacher models for DINOv2 training', 'run_forward_backward': 'run the forward_backward method on SSLMetaArch to compute DINO and iBOT losses and backpropagate gradients', 'update_teacher_weights': 'update teacher model weights via exponential moving average using SSLMetaArch update_teacher method with momentum factor', 'prepare_distributed_training': 'prepare the SSLMetaArch student and teacher models for distributed FSDP training across multiple GPUs', 'get_param_groups': 'get fused parameter groups with layer-wise decay for the SSLMetaArch student submodels to configure the optimizer'}
```

## File: facebookresearch_dinov2/dinov2/train/train.py

Prompts

```
['build a SSLMetaArch instance from a config to create student and teacher models for DINOv2 training', 'run the forward_backward method on SSLMetaArch to compute DINO and iBOT losses and backpropagate gradients', 'update teacher model weights via exponential moving average using SSLMetaArch update_teacher method with momentum factor', 'prepare the SSLMetaArch student and teacher models for distributed FSDP training across multiple GPUs', 'get fused parameter groups with layer-wise decay for the SSLMetaArch student submodels to configure the optimizer', 'run DINOv2 self-supervised training with a config file and optional resume flag', 'build an AdamW optimizer with configurable beta1 and beta2 from config and param groups', 'build cosine schedulers for learning rate, weight decay, momentum, and teacher temperature', 'apply learning rate and weight decay schedules to optimizer param groups with last layer support', 'save the teacher model state dict as a checkpoint for evaluation at a given iteration']
```

Usage

```
{'run_DINOv2_training': 'run DINOv2 self-supervised training with a config file and optional resume flag', 'build_optimizer_AdamW': 'build an AdamW optimizer with configurable beta1 and beta2 from config and param groups', 'build_schedulers_cosine': 'build cosine schedulers for learning rate, weight decay, momentum, and teacher temperature', 'apply_optim_scheduler_param_groups': 'apply learning rate and weight decay schedules to optimizer param groups with last layer support', 'do_test_save_teacher_checkpoint': 'save the teacher model state dict as a checkpoint for evaluation at a given iteration'}
```

