# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/mask2former_video/engine/defaults.py

Prompts

```
['create a DistributedDataParallel model wrapping a torch module for multi-GPU training with optional fp16 compression', 'build an argparse parser with common detectron2 training arguments like config file, resume, eval-only, and num-gpus', 'run default setup to configure logging, seed RNG, backup config, and set cudnn benchmark for a training job', 'create a DefaultPredictor from a detectron2 config to run single-image inference with automatic preprocessing and checkpoint loading', 'train a model using DefaultTrainer which handles model building, optimizer, DDP wrapping, checkpointing, hooks, and evaluation', 'build a CustomSimpleTrainer with model, data_loader, optimizer, and optional copy-paste augmentation config', 'build a CustomAMPTrainer with model, data_loader, optimizer, and gradient scaler for mixed precision training', 'run copy_and_paste to augment video segmentation targets by pasting source instances onto target frames', 'test the IoU and IoY methods to compute mask intersection-over-union and intersection-over-y metrics', 'review the run_step method to understand the training loop with copy-paste augmentation and loss computation']
```

Usage

```
{'create_ddp_model': 'create a DistributedDataParallel model wrapping a torch module for multi-GPU training with optional fp16 compression', 'build_default_argument_parser': 'build an argparse parser with common detectron2 training arguments like config file, resume, eval-only, and num-gpus', 'run_default_setup': 'run default setup to configure logging, seed RNG, backup config, and set cudnn benchmark for a training job', 'create_default_predictor': 'create a DefaultPredictor from a detectron2 config to run single-image inference with automatic preprocessing and checkpoint loading', 'train_default_trainer': 'train a model using DefaultTrainer which handles model building, optimizer, DDP wrapping, checkpointing, hooks, and evaluation'}
```

## File: facebookresearch_cutler/videocutler/mask2former_video/engine/train_loop.py

Prompts

```
['create a DistributedDataParallel model wrapping a torch module for multi-GPU training with optional fp16 compression', 'build an argparse parser with common detectron2 training arguments like config file, resume, eval-only, and num-gpus', 'run default setup to configure logging, seed RNG, backup config, and set cudnn benchmark for a training job', 'create a DefaultPredictor from a detectron2 config to run single-image inference with automatic preprocessing and checkpoint loading', 'train a model using DefaultTrainer which handles model building, optimizer, DDP wrapping, checkpointing, hooks, and evaluation', 'build a CustomSimpleTrainer with model, data_loader, optimizer, and optional copy-paste augmentation config', 'build a CustomAMPTrainer with model, data_loader, optimizer, and gradient scaler for mixed precision training', 'run copy_and_paste to augment video segmentation targets by pasting source instances onto target frames', 'test the IoU and IoY methods to compute mask intersection-over-union and intersection-over-y metrics', 'review the run_step method to understand the training loop with copy-paste augmentation and loss computation']
```

Usage

```
{'build_CustomSimpleTrainer': 'build a CustomSimpleTrainer with model, data_loader, optimizer, and optional copy-paste augmentation config', 'build_CustomAMPTrainer': 'build a CustomAMPTrainer with model, data_loader, optimizer, and gradient scaler for mixed precision training', 'run_copy_and_paste': 'run copy_and_paste to augment video segmentation targets by pasting source instances onto target frames', 'test_IoU_IoY': 'test the IoU and IoY methods to compute mask intersection-over-union and intersection-over-y metrics', 'review_run_step': 'review the run_step method to understand the training loop with copy-paste augmentation and loss computation'}
```

