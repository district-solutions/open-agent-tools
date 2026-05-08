# Agent Python Tools

- repo: facebookresearch/r-mae
- repo_uri: https://github.com/facebookresearch/r-mae

## File: facebookresearch_r-mae/pretrain/dataset/base.py

Prompts

```
['build a subclass of BaseDataset that implements __getitem__ and get_collate_fn for a custom dataset', 'create a BaseDataset instance and call init_processors to build and attach processor objects from config', 'test the prepare_batch method to transfer CPU tensors in a batch to the GPU device', 'refactor the _get_absolute_path method to resolve relative paths using the E2E_DATASETS environment variable', 'review the BaseDataset prepare_for_evaluation and format_for_evalai abstract methods for custom evaluation logic', 'create a COCO pretrain dataset instance with mask folders and annotation files for vision pretraining', 'create an ImageNet pretrain dataset instance with image and mask folders for masked autoencoder training', 'review the PretrainWithMask class _process_mask method for region sampling and patch filtering logic', 'refactor the PretrainWithMask class to support a new region_sample_type beyond random and random_fg', 'summarize the VisionPretrain class get_collate_fn method that returns a partial collate2d function']
```

Usage

```
{'build_BaseDataset_subclass': 'build a subclass of BaseDataset that implements __getitem__ and get_collate_fn for a custom dataset', 'create_init_processors': 'create a BaseDataset instance and call init_processors to build and attach processor objects from config', 'test_prepare_batch': 'test the prepare_batch method to transfer CPU tensors in a batch to the GPU device', 'refactor_get_absolute_path': 'refactor the _get_absolute_path method to resolve relative paths using the E2E_DATASETS environment variable', 'review_BaseDataset_evaluation': 'review the BaseDataset prepare_for_evaluation and format_for_evalai abstract methods for custom evaluation logic'}
```

## File: facebookresearch_r-mae/pretrain/dataset/pretrain.py

Prompts

```
['build a subclass of BaseDataset that implements __getitem__ and get_collate_fn for a custom dataset', 'create a BaseDataset instance and call init_processors to build and attach processor objects from config', 'test the prepare_batch method to transfer CPU tensors in a batch to the GPU device', 'refactor the _get_absolute_path method to resolve relative paths using the E2E_DATASETS environment variable', 'review the BaseDataset prepare_for_evaluation and format_for_evalai abstract methods for custom evaluation logic', 'create a COCO pretrain dataset instance with mask folders and annotation files for vision pretraining', 'create an ImageNet pretrain dataset instance with image and mask folders for masked autoencoder training', 'review the PretrainWithMask class _process_mask method for region sampling and patch filtering logic', 'refactor the PretrainWithMask class to support a new region_sample_type beyond random and random_fg', 'summarize the VisionPretrain class get_collate_fn method that returns a partial collate2d function']
```

Usage

```
{'create_COCOPretrain_dataset': 'create a COCO pretrain dataset instance with mask folders and annotation files for vision pretraining', 'create_ImageNetPretrain_dataset': 'create an ImageNet pretrain dataset instance with image and mask folders for masked autoencoder training', 'review_PretrainWithMask_process_mask': 'review the PretrainWithMask class _process_mask method for region sampling and patch filtering logic', 'refactor_PretrainWithMask_rmae_sampling': 'refactor the PretrainWithMask class to support a new region_sample_type beyond random and random_fg', 'summarize_VisionPretrain_collate_fn': 'summarize the VisionPretrain class get_collate_fn method that returns a partial collate2d function'}
```

