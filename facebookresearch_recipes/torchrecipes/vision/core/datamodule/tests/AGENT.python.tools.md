# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/vision/core/datamodule/tests/test_mnist_data_module.py

Prompts

```
['test MNISTDataModule raises MisconfigurationException when val_split is negative', 'test MNISTDataModule train_dataloader returns batches with images and labels', 'test MNISTDataModule splits dataset into train and validation sets with val_split', 'build torchvision transforms from a Hydra-style config list with Resize and ToTensor', 'instantiate MNISTDataModule using hydra.utils.instantiate with a config dictionary', 'test initializing TorchVisionDataModule using a Hydra configuration dictionary with dataset and batch settings', 'test creating a TorchVisionDataModule, calling setup, and verifying the train dataloader returns correct image shapes', 'test splitting the training dataset into train and validation sets using integer or float split values', 'build torchvision datasets from a Hydra-style config dict by applying transforms and instantiating each split', 'create a TorchVisionDataModule instance with configurable batch size and optional validation split ratio']
```

Usage

```
{'test_MNISTDataModule_misconfiguration': 'test MNISTDataModule raises MisconfigurationException when val_split is negative', 'test_MNISTDataModule_dataloading': 'test MNISTDataModule train_dataloader returns batches with images and labels', 'test_MNISTDataModule_split_dataset': 'test MNISTDataModule splits dataset into train and validation sets with val_split', 'build_transforms_from_config': 'build torchvision transforms from a Hydra-style config list with Resize and ToTensor', 'instantiate_MNISTDataModule_with_hydra': 'instantiate MNISTDataModule using hydra.utils.instantiate with a config dictionary'}
```

## File: facebookresearch_recipes/torchrecipes/vision/core/datamodule/tests/test_torchvision_data_module.py

Prompts

```
['test MNISTDataModule raises MisconfigurationException when val_split is negative', 'test MNISTDataModule train_dataloader returns batches with images and labels', 'test MNISTDataModule splits dataset into train and validation sets with val_split', 'build torchvision transforms from a Hydra-style config list with Resize and ToTensor', 'instantiate MNISTDataModule using hydra.utils.instantiate with a config dictionary', 'test initializing TorchVisionDataModule using a Hydra configuration dictionary with dataset and batch settings', 'test creating a TorchVisionDataModule, calling setup, and verifying the train dataloader returns correct image shapes', 'test splitting the training dataset into train and validation sets using integer or float split values', 'build torchvision datasets from a Hydra-style config dict by applying transforms and instantiating each split', 'create a TorchVisionDataModule instance with configurable batch size and optional validation split ratio']
```

Usage

```
{'test_init_datamodule_with_hydra': 'test initializing TorchVisionDataModule using a Hydra configuration dictionary with dataset and batch settings', 'test_creating_datamodule': 'test creating a TorchVisionDataModule, calling setup, and verifying the train dataloader returns correct image shapes', 'test_val_split': 'test splitting the training dataset into train and validation sets using integer or float split values', 'get_datasets_from_config': 'build torchvision datasets from a Hydra-style config dict by applying transforms and instantiating each split', 'get_torchvision_data_module': 'create a TorchVisionDataModule instance with configurable batch size and optional validation split ratio'}
```

