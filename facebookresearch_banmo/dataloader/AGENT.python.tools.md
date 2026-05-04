# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/dataloader/frameloader.py

Prompts

```
['build a distributed PyTorch DataLoader for training with configurable batch size and workers', 'build a single-batch PyTorch DataLoader for evaluation with no shuffling or workers', 'review the data_loader function to understand distributed sampler and worker initialization setup', 'review the eval_loader function to understand single-batch evaluation data loading configuration', 'refactor the _init_fn worker init function to use a configurable random seed instead of hardcoded 1003', 'create a subclass of BaseDataset that defines img_dir, anno, and anno_sfm attributes', 'build a PyTorch DataLoader using BaseDataset to load img, mask, flow, and densepose data', 'review the BaseDataset read_raw method that loads images, masks, optical flow, and densepose data', 'refactor the BaseDataset flow_process method to transform optical flow between forward and backward frames', 'summarize the BaseDataset compute_crop_params method that calculates crop parameters from a binary mask']
```

Usage

```
{'build_data_loader': 'build a distributed PyTorch DataLoader for training with configurable batch size and workers', 'build_eval_loader': 'build a single-batch PyTorch DataLoader for evaluation with no shuffling or workers', 'review_data_loader': 'review the data_loader function to understand distributed sampler and worker initialization setup', 'review_eval_loader': 'review the eval_loader function to understand single-batch evaluation data loading configuration', 'refactor_init_fn': 'refactor the _init_fn worker init function to use a configurable random seed instead of hardcoded 1003'}
```

## File: facebookresearch_banmo/dataloader/vidbase.py

Prompts

```
['build a distributed PyTorch DataLoader for training with configurable batch size and workers', 'build a single-batch PyTorch DataLoader for evaluation with no shuffling or workers', 'review the data_loader function to understand distributed sampler and worker initialization setup', 'review the eval_loader function to understand single-batch evaluation data loading configuration', 'refactor the _init_fn worker init function to use a configurable random seed instead of hardcoded 1003', 'create a subclass of BaseDataset that defines img_dir, anno, and anno_sfm attributes', 'build a PyTorch DataLoader using BaseDataset to load img, mask, flow, and densepose data', 'review the BaseDataset read_raw method that loads images, masks, optical flow, and densepose data', 'refactor the BaseDataset flow_process method to transform optical flow between forward and backward frames', 'summarize the BaseDataset compute_crop_params method that calculates crop parameters from a binary mask']
```

Usage

```
{'create_BaseDataset_subclass': 'create a subclass of BaseDataset that defines img_dir, anno, and anno_sfm attributes', 'build_dataset_loader_with_BaseDataset': 'build a PyTorch DataLoader using BaseDataset to load img, mask, flow, and densepose data', 'review_BaseDataset_read_raw': 'review the BaseDataset read_raw method that loads images, masks, optical flow, and densepose data', 'refactor_BaseDataset_flow_process': 'refactor the BaseDataset flow_process method to transform optical flow between forward and backward frames', 'summarize_BaseDataset_compute_crop_params': 'summarize the BaseDataset compute_crop_params method that calculates crop parameters from a binary mask'}
```

