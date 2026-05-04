# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/dinov2/dinov2/train/ssl_meta_arch.py

Prompts

```
['build a SSLMetaArch instance from a config to create student and teacher vision transformer models for DINOv2 training', 'run the forward_backward method on SSLMetaArch with cropped images and teacher temperature to compute DINO and iBOT losses', 'update the teacher model parameters using exponential moving average with the student model via the update_teacher method', 'prepare the SSLMetaArch model for distributed FSDP training by wrapping student and teacher subnetworks with FSDP wrappers', 'get fused parameter groups with layer-wise decay for the student model submodules to configure the optimizer', 'run DINOv2 self-supervised training with a config file and output directory via CLI', 'build an AdamW optimizer with configurable beta values from a DINOv2 config and param groups', 'build cosine schedulers for learning rate, weight decay, momentum, and teacher temperature', 'apply scheduled learning rate, weight decay, and last layer LR to optimizer param groups', 'run the full DINOv2 training loop with gradient clipping, EMA teacher updates, and checkpointing']
```

Usage

```
{'build_SSLMetaArch': 'build a SSLMetaArch instance from a config to create student and teacher vision transformer models for DINOv2 training', 'run_forward_backward': 'run the forward_backward method on SSLMetaArch with cropped images and teacher temperature to compute DINO and iBOT losses', 'update_teacher_params': 'update the teacher model parameters using exponential moving average with the student model via the update_teacher method', 'prepare_distributed_training': 'prepare the SSLMetaArch model for distributed FSDP training by wrapping student and teacher subnetworks with FSDP wrappers', 'get_params_groups': 'get fused parameter groups with layer-wise decay for the student model submodules to configure the optimizer'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/train/train.py

Prompts

```
['build a SSLMetaArch instance from a config to create student and teacher vision transformer models for DINOv2 training', 'run the forward_backward method on SSLMetaArch with cropped images and teacher temperature to compute DINO and iBOT losses', 'update the teacher model parameters using exponential moving average with the student model via the update_teacher method', 'prepare the SSLMetaArch model for distributed FSDP training by wrapping student and teacher subnetworks with FSDP wrappers', 'get fused parameter groups with layer-wise decay for the student model submodules to configure the optimizer', 'run DINOv2 self-supervised training with a config file and output directory via CLI', 'build an AdamW optimizer with configurable beta values from a DINOv2 config and param groups', 'build cosine schedulers for learning rate, weight decay, momentum, and teacher temperature', 'apply scheduled learning rate, weight decay, and last layer LR to optimizer param groups', 'run the full DINOv2 training loop with gradient clipping, EMA teacher updates, and checkpointing']
```

Usage

```
{'run_DINOv2_training': 'run DINOv2 self-supervised training with a config file and output directory via CLI', 'build_optimizer': 'build an AdamW optimizer with configurable beta values from a DINOv2 config and param groups', 'build_schedulers': 'build cosine schedulers for learning rate, weight decay, momentum, and teacher temperature', 'apply_optim_scheduler': 'apply scheduled learning rate, weight decay, and last layer LR to optimizer param groups', 'do_train': 'run the full DINOv2 training loop with gradient clipping, EMA teacher updates, and checkpointing'}
```

