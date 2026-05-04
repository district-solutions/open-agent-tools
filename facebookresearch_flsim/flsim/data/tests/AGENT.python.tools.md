# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/flsim/data/tests/test_data_sharder.py

Prompts

```
['test the RandomSharderConfig to shard data rows randomly across configured number of shards', 'test the PowerLawSharderConfig to shard rows with power law distribution using alpha parameter', 'test the BroadcastSharderConfig to replicate all data rows to every shard in the system', 'test the ColumnSharderConfig to assign each row to a unique shard based on a column value', 'test FLDatasetDataLoaderWithBatch with SequentialSharderConfig for distributed user sharding across multiple workers', 'test FLDatasetDataLoaderWithBatch yields correct batch counts for train eval and test sets', 'create a subclass of FLCSVDataset that overrides _get_processed_row_from_single_raw_row to return PyTorch tensors', 'instantiate a ColumnSharderConfig with a sharding column name using hydra utils instantiate', 'test that FLCSVDataset subclasses correctly process raw CSV rows into userid and label tensors', 'review FLDatasetDataLoaderWithBatch fl_train_set fl_eval_set and fl_test_set methods for correct batch sizing']
```

Usage

```
{'test_random_sharder': 'test the RandomSharderConfig to shard data rows randomly across configured number of shards', 'test_power_law_sharder': 'test the PowerLawSharderConfig to shard rows with power law distribution using alpha parameter', 'test_broadcast_sharder': 'test the BroadcastSharderConfig to replicate all data rows to every shard in the system', 'test_column_sharder': 'test the ColumnSharderConfig to assign each row to a unique shard based on a column value', 'test_distributed_user_sharding': 'test FLDatasetDataLoaderWithBatch with SequentialSharderConfig for distributed user sharding across multiple workers'}
```

## File: facebookresearch_flsim/flsim/data/tests/test_dataset_dataloader_with_batch.py

Prompts

```
['test the RandomSharderConfig to shard data rows randomly across configured number of shards', 'test the PowerLawSharderConfig to shard rows with power law distribution using alpha parameter', 'test the BroadcastSharderConfig to replicate all data rows to every shard in the system', 'test the ColumnSharderConfig to assign each row to a unique shard based on a column value', 'test FLDatasetDataLoaderWithBatch with SequentialSharderConfig for distributed user sharding across multiple workers', 'test FLDatasetDataLoaderWithBatch yields correct batch counts for train eval and test sets', 'create a subclass of FLCSVDataset that overrides _get_processed_row_from_single_raw_row to return PyTorch tensors', 'instantiate a ColumnSharderConfig with a sharding column name using hydra utils instantiate', 'test that FLCSVDataset subclasses correctly process raw CSV rows into userid and label tensors', 'review FLDatasetDataLoaderWithBatch fl_train_set fl_eval_set and fl_test_set methods for correct batch sizing']
```

Usage

```
{'test_FLDatasetDataLoaderWithBatch_batch_size': 'test FLDatasetDataLoaderWithBatch yields correct batch counts for train eval and test sets', 'create_FLCSVDataset_subclass': 'create a subclass of FLCSVDataset that overrides _get_processed_row_from_single_raw_row to return PyTorch tensors', 'instantiate_ColumnSharderConfig': 'instantiate a ColumnSharderConfig with a sharding column name using hydra utils instantiate', 'test_FLCSVDataset_row_processing': 'test that FLCSVDataset subclasses correctly process raw CSV rows into userid and label tensors', 'review_FLDatasetDataLoaderWithBatch_sets': 'review FLDatasetDataLoaderWithBatch fl_train_set fl_eval_set and fl_test_set methods for correct batch sizing'}
```

