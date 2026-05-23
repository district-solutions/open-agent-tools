# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/vision/core/datamodule/mnist_data_module.py

Prompts

```
['create an MNISTDataModule instance with custom batch size, val split, and normalization settings', 'build a Compose transform pipeline with ToTensor and optional Normalize using default_transforms method', 'test the _split_dataset method to split MNIST data into train and validation subsets', 'review the setup method that creates train, val, and test datasets for different stages', 'run the train_dataloader method to get a DataLoader with configurable shuffle and batch size', 'create a TorchVisionDataModule wrapping torchvision datasets for train, val, and test phases', 'setup the TorchVisionDataModule for the fit stage to split train data into train and val sets', 'get the train dataloader with RandomSampler from the TorchVisionDataModule', 'get the val dataloader with SequentialSampler from the TorchVisionDataModule', 'split a torchvision dataset into train and validation subsets using a configurable val_split ratio']
```

Usage

```
{'create_MNISTDataModule': 'create an MNISTDataModule instance with custom batch size, val split, and normalization settings', 'build_default_transforms': 'build a Compose transform pipeline with ToTensor and optional Normalize using default_transforms method', 'test_split_dataset': 'test the _split_dataset method to split MNIST data into train and validation subsets', 'review_setup_method': 'review the setup method that creates train, val, and test datasets for different stages', 'run_data_loader': 'run the train_dataloader method to get a DataLoader with configurable shuffle and batch size'}
```

## File: facebookresearch_recipes/torchrecipes/vision/core/datamodule/torchvision_data_module.py

Prompts

```
['create an MNISTDataModule instance with custom batch size, val split, and normalization settings', 'build a Compose transform pipeline with ToTensor and optional Normalize using default_transforms method', 'test the _split_dataset method to split MNIST data into train and validation subsets', 'review the setup method that creates train, val, and test datasets for different stages', 'run the train_dataloader method to get a DataLoader with configurable shuffle and batch size', 'create a TorchVisionDataModule wrapping torchvision datasets for train, val, and test phases', 'setup the TorchVisionDataModule for the fit stage to split train data into train and val sets', 'get the train dataloader with RandomSampler from the TorchVisionDataModule', 'get the val dataloader with SequentialSampler from the TorchVisionDataModule', 'split a torchvision dataset into train and validation subsets using a configurable val_split ratio']
```

Usage

```
{'create_TorchVisionDataModule': 'create a TorchVisionDataModule wrapping torchvision datasets for train, val, and test phases', 'setup_TorchVisionDataModule_fit': 'setup the TorchVisionDataModule for the fit stage to split train data into train and val sets', 'get_train_dataloader': 'get the train dataloader with RandomSampler from the TorchVisionDataModule', 'get_val_dataloader': 'get the val dataloader with SequentialSampler from the TorchVisionDataModule', 'split_dataset_train_val': 'split a torchvision dataset into train and validation subsets using a configurable val_split ratio'}
```

