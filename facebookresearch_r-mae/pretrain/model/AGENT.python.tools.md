# Agent Python Tools

- repo: facebookresearch/r-mae
- repo_uri: https://github.com/facebookresearch/r-mae

## File: facebookresearch_r-mae/pretrain/model/base_model.py

Prompts

```
['build a subclass of BaseModel that implements _build and forward methods for custom model integration', 'create a BaseModel instance by passing config and global_config DictConfig objects to the constructor', 'test the BaseModel build method which calls _build and sets inference mode to False', 'refactor the BaseModel inference method to toggle training mode and propagate inferencing flag to all submodules', 'review the BaseModel train method that sets inferencing to False on all modules and calls parent train', 'build a MaskedAutoencoder model from config with a specified mask ratio for pretraining', 'build a RegionMaskedAutoencoder model with region-based masking and configurable region sampling type', 'run the MaskedAutoencoder forward pass on image samples to compute reconstruction loss and predictions', 'run the RegionMaskedAutoencoder forward pass with region and shuffle IDs for region-aware masked reconstruction', 'review the MaskedAutoencoder get_optimizer_parameters method to inspect weight decay groups for the MAE ViT']
```

Usage

```
{'build_BaseModel_subclass': 'build a subclass of BaseModel that implements _build and forward methods for custom model integration', 'create_BaseModel_init': 'create a BaseModel instance by passing config and global_config DictConfig objects to the constructor', 'test_BaseModel_build': 'test the BaseModel build method which calls _build and sets inference mode to False', 'refactor_BaseModel_inference': 'refactor the BaseModel inference method to toggle training mode and propagate inferencing flag to all submodules', 'review_BaseModel_train': 'review the BaseModel train method that sets inferencing to False on all modules and calls parent train'}
```

## File: facebookresearch_r-mae/pretrain/model/mae.py

Prompts

```
['build a subclass of BaseModel that implements _build and forward methods for custom model integration', 'create a BaseModel instance by passing config and global_config DictConfig objects to the constructor', 'test the BaseModel build method which calls _build and sets inference mode to False', 'refactor the BaseModel inference method to toggle training mode and propagate inferencing flag to all submodules', 'review the BaseModel train method that sets inferencing to False on all modules and calls parent train', 'build a MaskedAutoencoder model from config with a specified mask ratio for pretraining', 'build a RegionMaskedAutoencoder model with region-based masking and configurable region sampling type', 'run the MaskedAutoencoder forward pass on image samples to compute reconstruction loss and predictions', 'run the RegionMaskedAutoencoder forward pass with region and shuffle IDs for region-aware masked reconstruction', 'review the MaskedAutoencoder get_optimizer_parameters method to inspect weight decay groups for the MAE ViT']
```

Usage

```
{'build_MaskedAutoencoder': 'build a MaskedAutoencoder model from config with a specified mask ratio for pretraining', 'build_RegionMaskedAutoencoder': 'build a RegionMaskedAutoencoder model with region-based masking and configurable region sampling type', 'run_MaskedAutoencoder_forward': 'run the MaskedAutoencoder forward pass on image samples to compute reconstruction loss and predictions', 'run_RegionMaskedAutoencoder_forward': 'run the RegionMaskedAutoencoder forward pass with region and shuffle IDs for region-aware masked reconstruction', 'review_MaskedAutoencoder_optimizer_parameters': 'review the MaskedAutoencoder get_optimizer_parameters method to inspect weight decay groups for the MAE ViT'}
```

