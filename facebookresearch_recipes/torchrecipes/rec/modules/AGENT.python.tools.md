# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/rec/modules/lightning_dlrm.py

Prompts

```
['build a PyTorch Lightning DLRM model with embedding bags and distributed training pipeline', 'create a LightningDLRM instance with an EmbeddingBagCollection and dense feature architecture layer sizes', 'run the training step on a dataloader iterator to compute loss and accuracy metrics', 'test the validation step on a dataloader iterator to evaluate model accuracy and loss', 'review the configure_optimizers method that returns a KeyedOptimizerWrapper with SGD for the DLRM model', 'build a PyTorch Lightning DLRM model with embedding bags and dense feature layers for CTR prediction', 'run the DLRM forward pass with dense tensors and keyed jagged sparse features to get predictions', 'test the training step of UnshardedLightningDLRM that computes BCE loss, accuracy, and AUROC metrics per batch', 'review the configure_optimizers method that returns an Adam optimizer for all DLRM model parameters', 'summarize the Hydra config dataclass that registers UnshardedLightningDLRM in the schema module config store']
```

Usage

```
{'build_LightningDLRM': 'build a PyTorch Lightning DLRM model with embedding bags and distributed training pipeline', 'create_LightningDLRM_init': 'create a LightningDLRM instance with an EmbeddingBagCollection and dense feature architecture layer sizes', 'run_training_step': 'run the training step on a dataloader iterator to compute loss and accuracy metrics', 'test_validation_step': 'test the validation step on a dataloader iterator to evaluate model accuracy and loss', 'review_configure_optimizers': 'review the configure_optimizers method that returns a KeyedOptimizerWrapper with SGD for the DLRM model'}
```

## File: facebookresearch_recipes/torchrecipes/rec/modules/unsharded_lightning_dlrm.py

Prompts

```
['build a PyTorch Lightning DLRM model with embedding bags and distributed training pipeline', 'create a LightningDLRM instance with an EmbeddingBagCollection and dense feature architecture layer sizes', 'run the training step on a dataloader iterator to compute loss and accuracy metrics', 'test the validation step on a dataloader iterator to evaluate model accuracy and loss', 'review the configure_optimizers method that returns a KeyedOptimizerWrapper with SGD for the DLRM model', 'build a PyTorch Lightning DLRM model with embedding bags and dense feature layers for CTR prediction', 'run the DLRM forward pass with dense tensors and keyed jagged sparse features to get predictions', 'test the training step of UnshardedLightningDLRM that computes BCE loss, accuracy, and AUROC metrics per batch', 'review the configure_optimizers method that returns an Adam optimizer for all DLRM model parameters', 'summarize the Hydra config dataclass that registers UnshardedLightningDLRM in the schema module config store']
```

Usage

```
{'build_UnshardedLightningDLRM': 'build a PyTorch Lightning DLRM model with embedding bags and dense feature layers for CTR prediction', 'run_forward_UnshardedLightningDLRM': 'run the DLRM forward pass with dense tensors and keyed jagged sparse features to get predictions', 'test_training_step_UnshardedLightningDLRM': 'test the training step of UnshardedLightningDLRM that computes BCE loss, accuracy, and AUROC metrics per batch', 'review_configure_optimizers_UnshardedLightningDLRM': 'review the configure_optimizers method that returns an Adam optimizer for all DLRM model parameters', 'summarize_UnshardedLightningDLRMModuleConf': 'summarize the Hydra config dataclass that registers UnshardedLightningDLRM in the schema module config store'}
```

