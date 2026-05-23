# Agent Python Tools

- repo: facebookresearch/sam2
- repo_uri: https://github.com/facebookresearch/sam2

## File: facebookresearch_sam2/training/loss_fns.py

Prompts

```
['compute the DICE loss between predicted masks and ground truth targets for segmentation', 'compute the sigmoid focal loss for dense detection with configurable alpha and gamma weighting', 'compute the IoU loss between predicted and actual intersection over union scores using MSE or L1', 'build a MultiStepMultiMasksAndIou loss module that combines focal, dice, and IoU losses for multi-step mask prediction', 'reduce a dictionary of losses by applying configurable weights from the weight dictionary', 'construct a PyTorch optimizer with configurable param groups, schedulers, and Hydra config from a model', 'apply layer-wise learning rate decay to scheduler configs for a model with get_layer_id method', 'clip gradients of a PyTorch model by max norm using DDP-compatible gradient clipping utility', 'filter model parameter names using unix-style wildcard patterns like block.2.*', 'build a mapping from module classes to their owned parameter names for a PyTorch model', 'run the SAM2 training loop on a single node with one or more GPUs using Hydra config', 'submit a SAM2 training job to a SLURM cluster via submitit with configurable partition and account', 'review the SubmititRunner class which wraps training jobs for checkpointable cluster execution with SLURM job info setup', 'refactor the single_proc_run function to customize environment variable setup and trainer instantiation for a single GPU process', 'test the format_exception function to verify it produces a readable traceback string from a Python exception', 'run the Trainer to train a SAM2 model with DDP across multiple GPUs using Hydra config', 'run the Trainer in val mode to evaluate a SAM2 model on a validation dataset', 'save a training checkpoint with model state dict, optimizer state, and epoch info to disk', 'load a resuming checkpoint to restore model weights, optimizer state, and training progress', "summarize a PyTorch model's total, trainable, and non-trainable parameter counts with human-readable abbreviations"]
```

Usage

```
{'compute_dice_loss': 'compute the DICE loss between predicted masks and ground truth targets for segmentation', 'compute_sigmoid_focal_loss': 'compute the sigmoid focal loss for dense detection with configurable alpha and gamma weighting', 'compute_iou_loss': 'compute the IoU loss between predicted and actual intersection over union scores using MSE or L1', 'build_multistep_loss_module': 'build a MultiStepMultiMasksAndIou loss module that combines focal, dice, and IoU losses for multi-step mask prediction', 'reduce_weighted_losses': 'reduce a dictionary of losses by applying configurable weights from the weight dictionary'}
```

## File: facebookresearch_sam2/training/optimizer.py

Prompts

```
['compute the DICE loss between predicted masks and ground truth targets for segmentation', 'compute the sigmoid focal loss for dense detection with configurable alpha and gamma weighting', 'compute the IoU loss between predicted and actual intersection over union scores using MSE or L1', 'build a MultiStepMultiMasksAndIou loss module that combines focal, dice, and IoU losses for multi-step mask prediction', 'reduce a dictionary of losses by applying configurable weights from the weight dictionary', 'construct a PyTorch optimizer with configurable param groups, schedulers, and Hydra config from a model', 'apply layer-wise learning rate decay to scheduler configs for a model with get_layer_id method', 'clip gradients of a PyTorch model by max norm using DDP-compatible gradient clipping utility', 'filter model parameter names using unix-style wildcard patterns like block.2.*', 'build a mapping from module classes to their owned parameter names for a PyTorch model', 'run the SAM2 training loop on a single node with one or more GPUs using Hydra config', 'submit a SAM2 training job to a SLURM cluster via submitit with configurable partition and account', 'review the SubmititRunner class which wraps training jobs for checkpointable cluster execution with SLURM job info setup', 'refactor the single_proc_run function to customize environment variable setup and trainer instantiation for a single GPU process', 'test the format_exception function to verify it produces a readable traceback string from a Python exception', 'run the Trainer to train a SAM2 model with DDP across multiple GPUs using Hydra config', 'run the Trainer in val mode to evaluate a SAM2 model on a validation dataset', 'save a training checkpoint with model state dict, optimizer state, and epoch info to disk', 'load a resuming checkpoint to restore model weights, optimizer state, and training progress', "summarize a PyTorch model's total, trainable, and non-trainable parameter counts with human-readable abbreviations"]
```

Usage

```
{'construct_optimizer': 'construct a PyTorch optimizer with configurable param groups, schedulers, and Hydra config from a model', 'layer_decay_param_modifier': 'apply layer-wise learning rate decay to scheduler configs for a model with get_layer_id method', 'GradientClipper': 'clip gradients of a PyTorch model by max norm using DDP-compatible gradient clipping utility', 'unix_param_pattern_to_parameter_names': 'filter model parameter names using unix-style wildcard patterns like block.2.*', 'get_module_cls_to_param_names': 'build a mapping from module classes to their owned parameter names for a PyTorch model'}
```

## File: facebookresearch_sam2/training/train.py

Prompts

```
['compute the DICE loss between predicted masks and ground truth targets for segmentation', 'compute the sigmoid focal loss for dense detection with configurable alpha and gamma weighting', 'compute the IoU loss between predicted and actual intersection over union scores using MSE or L1', 'build a MultiStepMultiMasksAndIou loss module that combines focal, dice, and IoU losses for multi-step mask prediction', 'reduce a dictionary of losses by applying configurable weights from the weight dictionary', 'construct a PyTorch optimizer with configurable param groups, schedulers, and Hydra config from a model', 'apply layer-wise learning rate decay to scheduler configs for a model with get_layer_id method', 'clip gradients of a PyTorch model by max norm using DDP-compatible gradient clipping utility', 'filter model parameter names using unix-style wildcard patterns like block.2.*', 'build a mapping from module classes to their owned parameter names for a PyTorch model', 'run the SAM2 training loop on a single node with one or more GPUs using Hydra config', 'submit a SAM2 training job to a SLURM cluster via submitit with configurable partition and account', 'review the SubmititRunner class which wraps training jobs for checkpointable cluster execution with SLURM job info setup', 'refactor the single_proc_run function to customize environment variable setup and trainer instantiation for a single GPU process', 'test the format_exception function to verify it produces a readable traceback string from a Python exception', 'run the Trainer to train a SAM2 model with DDP across multiple GPUs using Hydra config', 'run the Trainer in val mode to evaluate a SAM2 model on a validation dataset', 'save a training checkpoint with model state dict, optimizer state, and epoch info to disk', 'load a resuming checkpoint to restore model weights, optimizer state, and training progress', "summarize a PyTorch model's total, trainable, and non-trainable parameter counts with human-readable abbreviations"]
```

Usage

```
{'run_training_single_node': 'run the SAM2 training loop on a single node with one or more GPUs using Hydra config', 'run_training_on_cluster': 'submit a SAM2 training job to a SLURM cluster via submitit with configurable partition and account', 'review_SubmititRunner': 'review the SubmititRunner class which wraps training jobs for checkpointable cluster execution with SLURM job info setup', 'refactor_single_proc_run': 'refactor the single_proc_run function to customize environment variable setup and trainer instantiation for a single GPU process', 'test_format_exception': 'test the format_exception function to verify it produces a readable traceback string from a Python exception'}
```

## File: facebookresearch_sam2/training/trainer.py

Prompts

```
['compute the DICE loss between predicted masks and ground truth targets for segmentation', 'compute the sigmoid focal loss for dense detection with configurable alpha and gamma weighting', 'compute the IoU loss between predicted and actual intersection over union scores using MSE or L1', 'build a MultiStepMultiMasksAndIou loss module that combines focal, dice, and IoU losses for multi-step mask prediction', 'reduce a dictionary of losses by applying configurable weights from the weight dictionary', 'construct a PyTorch optimizer with configurable param groups, schedulers, and Hydra config from a model', 'apply layer-wise learning rate decay to scheduler configs for a model with get_layer_id method', 'clip gradients of a PyTorch model by max norm using DDP-compatible gradient clipping utility', 'filter model parameter names using unix-style wildcard patterns like block.2.*', 'build a mapping from module classes to their owned parameter names for a PyTorch model', 'run the SAM2 training loop on a single node with one or more GPUs using Hydra config', 'submit a SAM2 training job to a SLURM cluster via submitit with configurable partition and account', 'review the SubmititRunner class which wraps training jobs for checkpointable cluster execution with SLURM job info setup', 'refactor the single_proc_run function to customize environment variable setup and trainer instantiation for a single GPU process', 'test the format_exception function to verify it produces a readable traceback string from a Python exception', 'run the Trainer to train a SAM2 model with DDP across multiple GPUs using Hydra config', 'run the Trainer in val mode to evaluate a SAM2 model on a validation dataset', 'save a training checkpoint with model state dict, optimizer state, and epoch info to disk', 'load a resuming checkpoint to restore model weights, optimizer state, and training progress', "summarize a PyTorch model's total, trainable, and non-trainable parameter counts with human-readable abbreviations"]
```

Usage

```
{'run_trainer_training': 'run the Trainer to train a SAM2 model with DDP across multiple GPUs using Hydra config', 'run_trainer_validation': 'run the Trainer in val mode to evaluate a SAM2 model on a validation dataset', 'save_trainer_checkpoint': 'save a training checkpoint with model state dict, optimizer state, and epoch info to disk', 'load_trainer_checkpoint': 'load a resuming checkpoint to restore model weights, optimizer state, and training progress', 'summarize_model_parameters': "summarize a PyTorch model's total, trainable, and non-trainable parameter counts with human-readable abbreviations"}
```

