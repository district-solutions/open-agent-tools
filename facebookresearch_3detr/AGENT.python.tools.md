# Agent Python Tools

- repo: facebookresearch/3detr
- repo_uri: https://github.com/facebookresearch/3detr

## File: facebookresearch_3detr/criterion.py

Prompts

```
['build a SetCriterion with Matcher and loss weights for 3D object detection training', 'create a Matcher to compute bipartite matching costs between predictions and ground truth boxes', 'review the SetCriterion forward method that computes total loss including auxiliary outputs', 'test the loss_sem_cls method that computes cross-entropy classification loss for semantic classes', 'summarize the loss_angle method that computes angle classification and regression losses', 'train a 3D detection model for one epoch using a point cloud dataset loader and criterion', 'evaluate a 3D detection model on a test dataset and compute exact AP metrics', 'compute the learning rate for a given normalized epoch using cosine schedule with warmup', 'adjust the optimizer learning rate based on the current training iteration and cosine schedule', 'review the train_one_epoch function to understand the training loop, loss computation, and gradient clipping', 'run 3D object detection training on scannet or sunrgbd dataset using the 3DETR transformer model', 'evaluate a trained 3DETR model checkpoint on the test dataset using --test_only and --test_ckpt flags', 'build an argparse parser with 3DETR training hyperparameters including optimizer, model, loss, and dataset config', 'launch multi-GPU distributed training for 3DETR using torch multiprocessing spawn with NCCL backend', 'run the main training loop with epoch-based training, periodic evaluation, and automatic best checkpoint saving', 'build an AdamW optimizer for a PyTorch model using provided args and model parameters', 'build an optimizer that separates bias parameters from weight decay using filter_biases_wd flag', 'build parameter groups for an optimizer splitting params with and without weight decay', 'build an optimizer that skips parameters where requires_grad is False', 'build an AdamW optimizer configured with base_lr and weight_decay from an args namespace']
```

Usage

```
{'build_criterion': 'build a SetCriterion with Matcher and loss weights for 3D object detection training', 'create_matcher': 'create a Matcher to compute bipartite matching costs between predictions and ground truth boxes', 'review_SetCriterion_forward': 'review the SetCriterion forward method that computes total loss including auxiliary outputs', 'test_loss_sem_cls': 'test the loss_sem_cls method that computes cross-entropy classification loss for semantic classes', 'summarize_loss_angle': 'summarize the loss_angle method that computes angle classification and regression losses'}
```

## File: facebookresearch_3detr/engine.py

Prompts

```
['build a SetCriterion with Matcher and loss weights for 3D object detection training', 'create a Matcher to compute bipartite matching costs between predictions and ground truth boxes', 'review the SetCriterion forward method that computes total loss including auxiliary outputs', 'test the loss_sem_cls method that computes cross-entropy classification loss for semantic classes', 'summarize the loss_angle method that computes angle classification and regression losses', 'train a 3D detection model for one epoch using a point cloud dataset loader and criterion', 'evaluate a 3D detection model on a test dataset and compute exact AP metrics', 'compute the learning rate for a given normalized epoch using cosine schedule with warmup', 'adjust the optimizer learning rate based on the current training iteration and cosine schedule', 'review the train_one_epoch function to understand the training loop, loss computation, and gradient clipping', 'run 3D object detection training on scannet or sunrgbd dataset using the 3DETR transformer model', 'evaluate a trained 3DETR model checkpoint on the test dataset using --test_only and --test_ckpt flags', 'build an argparse parser with 3DETR training hyperparameters including optimizer, model, loss, and dataset config', 'launch multi-GPU distributed training for 3DETR using torch multiprocessing spawn with NCCL backend', 'run the main training loop with epoch-based training, periodic evaluation, and automatic best checkpoint saving', 'build an AdamW optimizer for a PyTorch model using provided args and model parameters', 'build an optimizer that separates bias parameters from weight decay using filter_biases_wd flag', 'build parameter groups for an optimizer splitting params with and without weight decay', 'build an optimizer that skips parameters where requires_grad is False', 'build an AdamW optimizer configured with base_lr and weight_decay from an args namespace']
```

Usage

```
{'train_one_epoch': 'train a 3D detection model for one epoch using a point cloud dataset loader and criterion', 'evaluate': 'evaluate a 3D detection model on a test dataset and compute exact AP metrics', 'compute_learning_rate': 'compute the learning rate for a given normalized epoch using cosine schedule with warmup', 'adjust_learning_rate': 'adjust the optimizer learning rate based on the current training iteration and cosine schedule', 'review_train_one_epoch': 'review the train_one_epoch function to understand the training loop, loss computation, and gradient clipping'}
```

## File: facebookresearch_3detr/main.py

Prompts

```
['build a SetCriterion with Matcher and loss weights for 3D object detection training', 'create a Matcher to compute bipartite matching costs between predictions and ground truth boxes', 'review the SetCriterion forward method that computes total loss including auxiliary outputs', 'test the loss_sem_cls method that computes cross-entropy classification loss for semantic classes', 'summarize the loss_angle method that computes angle classification and regression losses', 'train a 3D detection model for one epoch using a point cloud dataset loader and criterion', 'evaluate a 3D detection model on a test dataset and compute exact AP metrics', 'compute the learning rate for a given normalized epoch using cosine schedule with warmup', 'adjust the optimizer learning rate based on the current training iteration and cosine schedule', 'review the train_one_epoch function to understand the training loop, loss computation, and gradient clipping', 'run 3D object detection training on scannet or sunrgbd dataset using the 3DETR transformer model', 'evaluate a trained 3DETR model checkpoint on the test dataset using --test_only and --test_ckpt flags', 'build an argparse parser with 3DETR training hyperparameters including optimizer, model, loss, and dataset config', 'launch multi-GPU distributed training for 3DETR using torch multiprocessing spawn with NCCL backend', 'run the main training loop with epoch-based training, periodic evaluation, and automatic best checkpoint saving', 'build an AdamW optimizer for a PyTorch model using provided args and model parameters', 'build an optimizer that separates bias parameters from weight decay using filter_biases_wd flag', 'build parameter groups for an optimizer splitting params with and without weight decay', 'build an optimizer that skips parameters where requires_grad is False', 'build an AdamW optimizer configured with base_lr and weight_decay from an args namespace']
```

Usage

```
{'run_3detr_training': 'run 3D object detection training on scannet or sunrgbd dataset using the 3DETR transformer model', 'run_3detr_evaluation': 'evaluate a trained 3DETR model checkpoint on the test dataset using --test_only and --test_ckpt flags', 'build_args_parser': 'build an argparse parser with 3DETR training hyperparameters including optimizer, model, loss, and dataset config', 'run_distributed_training': 'launch multi-GPU distributed training for 3DETR using torch multiprocessing spawn with NCCL backend', 'run_training_loop': 'run the main training loop with epoch-based training, periodic evaluation, and automatic best checkpoint saving'}
```

## File: facebookresearch_3detr/optimizer.py

Prompts

```
['build a SetCriterion with Matcher and loss weights for 3D object detection training', 'create a Matcher to compute bipartite matching costs between predictions and ground truth boxes', 'review the SetCriterion forward method that computes total loss including auxiliary outputs', 'test the loss_sem_cls method that computes cross-entropy classification loss for semantic classes', 'summarize the loss_angle method that computes angle classification and regression losses', 'train a 3D detection model for one epoch using a point cloud dataset loader and criterion', 'evaluate a 3D detection model on a test dataset and compute exact AP metrics', 'compute the learning rate for a given normalized epoch using cosine schedule with warmup', 'adjust the optimizer learning rate based on the current training iteration and cosine schedule', 'review the train_one_epoch function to understand the training loop, loss computation, and gradient clipping', 'run 3D object detection training on scannet or sunrgbd dataset using the 3DETR transformer model', 'evaluate a trained 3DETR model checkpoint on the test dataset using --test_only and --test_ckpt flags', 'build an argparse parser with 3DETR training hyperparameters including optimizer, model, loss, and dataset config', 'launch multi-GPU distributed training for 3DETR using torch multiprocessing spawn with NCCL backend', 'run the main training loop with epoch-based training, periodic evaluation, and automatic best checkpoint saving', 'build an AdamW optimizer for a PyTorch model using provided args and model parameters', 'build an optimizer that separates bias parameters from weight decay using filter_biases_wd flag', 'build parameter groups for an optimizer splitting params with and without weight decay', 'build an optimizer that skips parameters where requires_grad is False', 'build an AdamW optimizer configured with base_lr and weight_decay from an args namespace']
```

Usage

```
{'build_optimizer_adamw': 'build an AdamW optimizer for a PyTorch model using provided args and model parameters', 'build_optimizer_with_weight_decay_filter': 'build an optimizer that separates bias parameters from weight decay using filter_biases_wd flag', 'build_optimizer_param_groups': 'build parameter groups for an optimizer splitting params with and without weight decay', 'build_optimizer_skip_frozen_params': 'build an optimizer that skips parameters where requires_grad is False', 'build_optimizer_from_args': 'build an AdamW optimizer configured with base_lr and weight_decay from an args namespace'}
```

