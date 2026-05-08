# Agent Python Tools

- repo: facebookresearch/ram
- repo_uri: https://github.com/facebookresearch/ram

## File: facebookresearch_ram/projects/cocomix/data/data.py

Prompts

```
['create a PreprocessedDataset from a .bin memmap file with configurable block size and train or val split', 'get a batch item from PreprocessedDataset returning input_ids, labels, and attention_mask tensors', 'build a PyTorch DataLoader for training using PreprocessedDataset with shuffle, batch size, and num workers', 'build a dictionary of validation PyTorch DataLoaders for each named dataset in the config', 'review the PreprocessedDataset class and its random shift augmentation logic for training splits']
```

Usage

```
{'create_preprocessed_dataset': 'create a PreprocessedDataset from a .bin memmap file with configurable block size and train or val split', 'get_item_from_dataset': 'get a batch item from PreprocessedDataset returning input_ids, labels, and attention_mask tensors', 'build_train_dataloader': 'build a PyTorch DataLoader for training using PreprocessedDataset with shuffle, batch size, and num workers', 'build_val_dataloaders': 'build a dictionary of validation PyTorch DataLoaders for each named dataset in the config', 'review_preprocessed_dataset_class': 'review the PreprocessedDataset class and its random shift augmentation logic for training splits'}
```

