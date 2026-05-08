# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/cutler/engine/defaults.py

Prompts

```
['create a DistributedDataParallel model from a torch module with optional fp16 compression hooks', 'build an argparse parser with common detectron2 training arguments like config file, resume, and eval-only', 'run default setup to configure logging, environment info, config backup, and random seed for training', 'create a DefaultPredictor that loads a model checkpoint and runs inference on a single BGR image', 'train a model using DefaultTrainer with resume, checkpointing, evaluation hooks, and auto-scaled worker config', 'run a CustomSimpleTrainer training loop with copy-paste data augmentation on labeled and unlabeled data', 'run a CustomAMPTrainer training loop with automatic mixed precision and gradient scaling', 'run the copy_and_paste method to paste labeled instances onto unlabeled images with random resizing', 'run the IoU method to compute intersection over union between two binary mask tensors', 'run the IoY method to compute intersection over target between two binary mask tensors']
```

Usage

```
{'create_ddp_model': 'create a DistributedDataParallel model from a torch module with optional fp16 compression hooks', 'build_default_argument_parser': 'build an argparse parser with common detectron2 training arguments like config file, resume, and eval-only', 'run_default_setup': 'run default setup to configure logging, environment info, config backup, and random seed for training', 'create_default_predictor': 'create a DefaultPredictor that loads a model checkpoint and runs inference on a single BGR image', 'train_default_trainer': 'train a model using DefaultTrainer with resume, checkpointing, evaluation hooks, and auto-scaled worker config'}
```

## File: facebookresearch_cutler/cutler/engine/train_loop.py

Prompts

```
['create a DistributedDataParallel model from a torch module with optional fp16 compression hooks', 'build an argparse parser with common detectron2 training arguments like config file, resume, and eval-only', 'run default setup to configure logging, environment info, config backup, and random seed for training', 'create a DefaultPredictor that loads a model checkpoint and runs inference on a single BGR image', 'train a model using DefaultTrainer with resume, checkpointing, evaluation hooks, and auto-scaled worker config', 'run a CustomSimpleTrainer training loop with copy-paste data augmentation on labeled and unlabeled data', 'run a CustomAMPTrainer training loop with automatic mixed precision and gradient scaling', 'run the copy_and_paste method to paste labeled instances onto unlabeled images with random resizing', 'run the IoU method to compute intersection over union between two binary mask tensors', 'run the IoY method to compute intersection over target between two binary mask tensors']
```

Usage

```
{'run_CustomSimpleTrainer': 'run a CustomSimpleTrainer training loop with copy-paste data augmentation on labeled and unlabeled data', 'run_CustomAMPTrainer': 'run a CustomAMPTrainer training loop with automatic mixed precision and gradient scaling', 'run_copy_and_paste': 'run the copy_and_paste method to paste labeled instances onto unlabeled images with random resizing', 'run_IoU': 'run the IoU method to compute intersection over union between two binary mask tensors', 'run_IoY': 'run the IoY method to compute intersection over target between two binary mask tensors'}
```

