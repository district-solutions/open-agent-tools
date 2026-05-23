# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/rec/datamodules/commons.py

Prompts

```
['create a Batch dataclass with dense_features, sparse_features, and labels for recommendation model data', 'move a Batch to a GPU device using the to method with non_blocking transfer', 'pin a Batch memory for faster GPU data transfer using the pin_memory method', 'record a CUDA stream on a Batch tensors for async GPU operations', 'build a Batch using KeyedJaggedTensor for sparse features and dense tensors for embeddings', 'create a CriteoDataModule instance with num_days=1, batch_size=32, and dataset_path for Criteo 1TB data', 'setup the CriteoDataModule for fit stage to create train and validation datapipe splits', 'get the training DataLoader from CriteoDataModule after calling setup for model training', 'transform a raw Criteo batch into a Batch object with dense features, sparse KeyedJaggedTensor, and labels', 'create a CriteoDataModule with undersampling_rate=0.3 to retain only 30 percent of zero-labeled samples', 'create a RandomRecDataModule instance with custom batch size, hash size, and feature keys for recommendation data', 'build a training dataloader from RandomRecDataModule that yields random batches of sparse and dense features', 'build a validation dataloader from RandomRecDataModule that yields random batches of sparse and dense features', 'build a test dataloader from RandomRecDataModule that yields random batches of sparse and dense features', 'register the RandomRecDataModuleConf dataclass with Hydra ConfigStore under the schema/datamodule group']
```

Usage

```
{'create_batch_dataclass': 'create a Batch dataclass with dense_features, sparse_features, and labels for recommendation model data', 'move_batch_to_device': 'move a Batch to a GPU device using the to method with non_blocking transfer', 'pin_batch_memory': 'pin a Batch memory for faster GPU data transfer using the pin_memory method', 'record_batch_stream': 'record a CUDA stream on a Batch tensors for async GPU operations', 'build_batch_with_keyed_jagged_tensor': 'build a Batch using KeyedJaggedTensor for sparse features and dense tensors for embeddings'}
```

## File: facebookresearch_recipes/torchrecipes/rec/datamodules/criteo_datamodule.py

Prompts

```
['create a Batch dataclass with dense_features, sparse_features, and labels for recommendation model data', 'move a Batch to a GPU device using the to method with non_blocking transfer', 'pin a Batch memory for faster GPU data transfer using the pin_memory method', 'record a CUDA stream on a Batch tensors for async GPU operations', 'build a Batch using KeyedJaggedTensor for sparse features and dense tensors for embeddings', 'create a CriteoDataModule instance with num_days=1, batch_size=32, and dataset_path for Criteo 1TB data', 'setup the CriteoDataModule for fit stage to create train and validation datapipe splits', 'get the training DataLoader from CriteoDataModule after calling setup for model training', 'transform a raw Criteo batch into a Batch object with dense features, sparse KeyedJaggedTensor, and labels', 'create a CriteoDataModule with undersampling_rate=0.3 to retain only 30 percent of zero-labeled samples', 'create a RandomRecDataModule instance with custom batch size, hash size, and feature keys for recommendation data', 'build a training dataloader from RandomRecDataModule that yields random batches of sparse and dense features', 'build a validation dataloader from RandomRecDataModule that yields random batches of sparse and dense features', 'build a test dataloader from RandomRecDataModule that yields random batches of sparse and dense features', 'register the RandomRecDataModuleConf dataclass with Hydra ConfigStore under the schema/datamodule group']
```

Usage

```
{'create_CriteoDataModule': 'create a CriteoDataModule instance with num_days=1, batch_size=32, and dataset_path for Criteo 1TB data', 'setup_CriteoDataModule': 'setup the CriteoDataModule for fit stage to create train and validation datapipe splits', 'get_train_dataloader': 'get the training DataLoader from CriteoDataModule after calling setup for model training', 'transform_batch': 'transform a raw Criteo batch into a Batch object with dense features, sparse KeyedJaggedTensor, and labels', 'undersample_CriteoDataModule': 'create a CriteoDataModule with undersampling_rate=0.3 to retain only 30 percent of zero-labeled samples'}
```

## File: facebookresearch_recipes/torchrecipes/rec/datamodules/random_rec_datamodule.py

Prompts

```
['create a Batch dataclass with dense_features, sparse_features, and labels for recommendation model data', 'move a Batch to a GPU device using the to method with non_blocking transfer', 'pin a Batch memory for faster GPU data transfer using the pin_memory method', 'record a CUDA stream on a Batch tensors for async GPU operations', 'build a Batch using KeyedJaggedTensor for sparse features and dense tensors for embeddings', 'create a CriteoDataModule instance with num_days=1, batch_size=32, and dataset_path for Criteo 1TB data', 'setup the CriteoDataModule for fit stage to create train and validation datapipe splits', 'get the training DataLoader from CriteoDataModule after calling setup for model training', 'transform a raw Criteo batch into a Batch object with dense features, sparse KeyedJaggedTensor, and labels', 'create a CriteoDataModule with undersampling_rate=0.3 to retain only 30 percent of zero-labeled samples', 'create a RandomRecDataModule instance with custom batch size, hash size, and feature keys for recommendation data', 'build a training dataloader from RandomRecDataModule that yields random batches of sparse and dense features', 'build a validation dataloader from RandomRecDataModule that yields random batches of sparse and dense features', 'build a test dataloader from RandomRecDataModule that yields random batches of sparse and dense features', 'register the RandomRecDataModuleConf dataclass with Hydra ConfigStore under the schema/datamodule group']
```

Usage

```
{'create_random_rec_datamodule': 'create a RandomRecDataModule instance with custom batch size, hash size, and feature keys for recommendation data', 'build_train_dataloader': 'build a training dataloader from RandomRecDataModule that yields random batches of sparse and dense features', 'build_val_dataloader': 'build a validation dataloader from RandomRecDataModule that yields random batches of sparse and dense features', 'build_test_dataloader': 'build a test dataloader from RandomRecDataModule that yields random batches of sparse and dense features', 'register_hydra_config': 'register the RandomRecDataModuleConf dataclass with Hydra ConfigStore under the schema/datamodule group'}
```

