# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/rec/modules/tests/test_lightning_dlrm.py

Prompts

```
['test that LightningDLRM trainer produces equivalent results to manual training steps', 'test checkpointing functionality for LightningDLRM model with ModelCheckpoint callback', 'run distributed training of LightningDLRM using elastic_launch with LaunchConfig', 'create an EmbeddingBagConfig with name, embedding_dim, num_embeddings, and feature_names', 'assert model state dict equality including ShardedTensor local shards comparison', 'test the UnshardedLightningDLRM model by training and evaluating it with PyTorch Lightning', 'create an EmbeddingBagCollection from a list of EmbeddingBagConfig table definitions', 'build an UnshardedLightningDLRM model with embedding bag collection, dense features, and layer sizes', 'run DLRM training and testing using a PyTorch Lightning Trainer with a RandomRecDataModule']
```

Usage

```
{'test_LightningDLRM_equivalence': 'test that LightningDLRM trainer produces equivalent results to manual training steps', 'test_checkpointing_LightningDLRM': 'test checkpointing functionality for LightningDLRM model with ModelCheckpoint callback', 'run_elastic_launch_LightningDLRM': 'run distributed training of LightningDLRM using elastic_launch with LaunchConfig', 'create_EmbeddingBagConfig': 'create an EmbeddingBagConfig with name, embedding_dim, num_embeddings, and feature_names', 'assert_model_state_dict': 'assert model state dict equality including ShardedTensor local shards comparison'}
```

## File: facebookresearch_recipes/torchrecipes/rec/modules/tests/test_unsharded_lightning_dlrm.py

Prompts

```
['test that LightningDLRM trainer produces equivalent results to manual training steps', 'test checkpointing functionality for LightningDLRM model with ModelCheckpoint callback', 'run distributed training of LightningDLRM using elastic_launch with LaunchConfig', 'create an EmbeddingBagConfig with name, embedding_dim, num_embeddings, and feature_names', 'assert model state dict equality including ShardedTensor local shards comparison', 'test the UnshardedLightningDLRM model by training and evaluating it with PyTorch Lightning', 'create an EmbeddingBagCollection from a list of EmbeddingBagConfig table definitions', 'build an UnshardedLightningDLRM model with embedding bag collection, dense features, and layer sizes', 'run DLRM training and testing using a PyTorch Lightning Trainer with a RandomRecDataModule']
```

Usage

```
{'test_UnshardedLightningDLRM_train_model': 'test the UnshardedLightningDLRM model by training and evaluating it with PyTorch Lightning', 'create_EmbeddingBagConfig': 'create an EmbeddingBagConfig with a name, embedding dimension, number of embeddings, and feature names', 'create_EmbeddingBagCollection': 'create an EmbeddingBagCollection from a list of EmbeddingBagConfig table definitions', 'build_UnshardedLightningDLRM': 'build an UnshardedLightningDLRM model with embedding bag collection, dense features, and layer sizes', 'run_DLRM_training': 'run DLRM training and testing using a PyTorch Lightning Trainer with a RandomRecDataModule'}
```

