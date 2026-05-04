# Agent Python Tools

- repo: facebookresearch/fixres
- repo_uri: https://github.com/facebookresearch/fixres

## File: facebookresearch_fixres/imnet_resnet50_scratch/samplers.py

Prompts

```
['create a RASampler instance for distributed training with repeated augmentations and configurable shuffle', 'use the RASampler shuffler method to generate repeated shuffled indices for a dataset', 'iterate over a RASampler to get subsampled indices for the current rank in distributed training', 'set the epoch on a RASampler instance to control shuffling behavior per training epoch', 'collate a batch of variable-sized inputs into lists instead of stacked tensors using list_collate', 'run the Trainer to train a ResNet50 model on ImageNet from scratch using distributed data parallel', 'create a TrainerState checkpoint by calling save to persist model, optimizer, and lr scheduler state', 'load a TrainerState from a checkpoint file using the load class method to resume training', 'setup a distributed process group with CUDA device and init_process_group for multi-GPU training', 'evaluate the trained ResNet50 model on the validation set and return accuracy and loss', 'build a train and validation image transform pipeline with random crop, flip, and normalization for ImageNet', 'create a custom Resize class that resizes images by the largest side without cropping', 'test the Resize.target_size static method to compute target dimensions from width, height, and size', 'refactor get_transforms to support custom backbone normalization for pnasnet5large or nasnetamobile', 'summarize the available transform kinds listed in transforms_list as torch and full']
```

Usage

```
{'create_RASampler_for_distributed_training': 'create a RASampler instance for distributed training with repeated augmentations and configurable shuffle', 'use_RASampler_shuffler_generator': 'use the RASampler shuffler method to generate repeated shuffled indices for a dataset', 'iterate_RASampler_indices': 'iterate over a RASampler to get subsampled indices for the current rank in distributed training', 'set_RASampler_epoch': 'set the epoch on a RASampler instance to control shuffling behavior per training epoch', 'collate_batch_with_list_collate': 'collate a batch of variable-sized inputs into lists instead of stacked tensors using list_collate'}
```

## File: facebookresearch_fixres/imnet_resnet50_scratch/train.py

Prompts

```
['create a RASampler instance for distributed training with repeated augmentations and configurable shuffle', 'use the RASampler shuffler method to generate repeated shuffled indices for a dataset', 'iterate over a RASampler to get subsampled indices for the current rank in distributed training', 'set the epoch on a RASampler instance to control shuffling behavior per training epoch', 'collate a batch of variable-sized inputs into lists instead of stacked tensors using list_collate', 'run the Trainer to train a ResNet50 model on ImageNet from scratch using distributed data parallel', 'create a TrainerState checkpoint by calling save to persist model, optimizer, and lr scheduler state', 'load a TrainerState from a checkpoint file using the load class method to resume training', 'setup a distributed process group with CUDA device and init_process_group for multi-GPU training', 'evaluate the trained ResNet50 model on the validation set and return accuracy and loss', 'build a train and validation image transform pipeline with random crop, flip, and normalization for ImageNet', 'create a custom Resize class that resizes images by the largest side without cropping', 'test the Resize.target_size static method to compute target dimensions from width, height, and size', 'refactor get_transforms to support custom backbone normalization for pnasnet5large or nasnetamobile', 'summarize the available transform kinds listed in transforms_list as torch and full']
```

Usage

```
{'run_resnet50_training': 'run the Trainer to train a ResNet50 model on ImageNet from scratch using distributed data parallel', 'create_trainer_state_checkpoint': 'create a TrainerState checkpoint by calling save to persist model, optimizer, and lr scheduler state', 'load_trainer_state_from_checkpoint': 'load a TrainerState from a checkpoint file using the load class method to resume training', 'setup_distributed_process_group': 'setup a distributed process group with CUDA device and init_process_group for multi-GPU training', 'evaluate_resnet50_model': 'evaluate the trained ResNet50 model on the validation set and return accuracy and loss'}
```

## File: facebookresearch_fixres/imnet_resnet50_scratch/transforms.py

Prompts

```
['create a RASampler instance for distributed training with repeated augmentations and configurable shuffle', 'use the RASampler shuffler method to generate repeated shuffled indices for a dataset', 'iterate over a RASampler to get subsampled indices for the current rank in distributed training', 'set the epoch on a RASampler instance to control shuffling behavior per training epoch', 'collate a batch of variable-sized inputs into lists instead of stacked tensors using list_collate', 'run the Trainer to train a ResNet50 model on ImageNet from scratch using distributed data parallel', 'create a TrainerState checkpoint by calling save to persist model, optimizer, and lr scheduler state', 'load a TrainerState from a checkpoint file using the load class method to resume training', 'setup a distributed process group with CUDA device and init_process_group for multi-GPU training', 'evaluate the trained ResNet50 model on the validation set and return accuracy and loss', 'build a train and validation image transform pipeline with random crop, flip, and normalization for ImageNet', 'create a custom Resize class that resizes images by the largest side without cropping', 'test the Resize.target_size static method to compute target dimensions from width, height, and size', 'refactor get_transforms to support custom backbone normalization for pnasnet5large or nasnetamobile', 'summarize the available transform kinds listed in transforms_list as torch and full']
```

Usage

```
{'build_train_val_transforms': 'build a train and validation image transform pipeline with random crop, flip, and normalization for ImageNet', 'create_resize_class': 'create a custom Resize class that resizes images by the largest side without cropping', 'test_resize_target_size': 'test the Resize.target_size static method to compute target dimensions from width, height, and size', 'refactor_get_transforms_backbone': 'refactor get_transforms to support custom backbone normalization for pnasnet5large or nasnetamobile', 'summarize_transforms_list': 'summarize the available transform kinds listed in transforms_list as torch and full'}
```

