# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/flsim/data/data_provider.py

Prompts

```
['create FLUserDataFromList from a list of user batches and an IFLModel instance', 'iterate over training batches using FLUserDataFromList train_data method', 'iterate over evaluation batches using FLUserDataFromList eval_data method', 'create FLDataProviderFromList from train eval and test user lists with an IFLModel', 'get a specific train user by index using FLDataProviderFromList get_train_user method', 'create a RandomSharder to split training data randomly across a specified number of shards', 'build a SequentialSharder to assign consecutive rows to shards with a fixed examples per shard count', 'create a BroadcastSharder to copy each training datum to all shards for uniform distribution', 'build a ColumnSharder to partition data rows into shards based on a specified column value', 'create a RoundRobinSharder to split training data in a round-robin fashion across all shards', 'create an FLDatasetDataLoader instance with a dataset class, train/test/eval paths, and a sharder', 'get sharded training data batches from an FLDatasetDataLoader using the fl_train_set method', 'get the evaluation dataset from an FLDatasetDataLoader using the fl_eval_set method', 'create an FLDatasetDataLoaderWithBatch instance with pre-built datasets, a sharder, and a train batch size', 'get batched and sharded training data distributed across workers using fl_train_set with rank and world_size']
```

Usage

```
{'create_FLUserDataFromList': 'create FLUserDataFromList from a list of user batches and an IFLModel instance', 'iterate_FLUserDataFromList_train_data': 'iterate over training batches using FLUserDataFromList train_data method', 'iterate_FLUserDataFromList_eval_data': 'iterate over evaluation batches using FLUserDataFromList eval_data method', 'create_FLDataProviderFromList': 'create FLDataProviderFromList from train eval and test user lists with an IFLModel', 'get_train_user_FLDataProviderFromList': 'get a specific train user by index using FLDataProviderFromList get_train_user method'}
```

## File: facebookresearch_flsim/flsim/data/data_sharder.py

Prompts

```
['create FLUserDataFromList from a list of user batches and an IFLModel instance', 'iterate over training batches using FLUserDataFromList train_data method', 'iterate over evaluation batches using FLUserDataFromList eval_data method', 'create FLDataProviderFromList from train eval and test user lists with an IFLModel', 'get a specific train user by index using FLDataProviderFromList get_train_user method', 'create a RandomSharder to split training data randomly across a specified number of shards', 'build a SequentialSharder to assign consecutive rows to shards with a fixed examples per shard count', 'create a BroadcastSharder to copy each training datum to all shards for uniform distribution', 'build a ColumnSharder to partition data rows into shards based on a specified column value', 'create a RoundRobinSharder to split training data in a round-robin fashion across all shards', 'create an FLDatasetDataLoader instance with a dataset class, train/test/eval paths, and a sharder', 'get sharded training data batches from an FLDatasetDataLoader using the fl_train_set method', 'get the evaluation dataset from an FLDatasetDataLoader using the fl_eval_set method', 'create an FLDatasetDataLoaderWithBatch instance with pre-built datasets, a sharder, and a train batch size', 'get batched and sharded training data distributed across workers using fl_train_set with rank and world_size']
```

Usage

```
{'shard_rows_randomly': 'create a RandomSharder to split training data randomly across a specified number of shards', 'shard_rows_sequentially': 'build a SequentialSharder to assign consecutive rows to shards with a fixed examples per shard count', 'shard_rows_broadcast': 'create a BroadcastSharder to copy each training datum to all shards for uniform distribution', 'shard_rows_by_column': 'build a ColumnSharder to partition data rows into shards based on a specified column value', 'shard_rows_round_robin': 'create a RoundRobinSharder to split training data in a round-robin fashion across all shards'}
```

## File: facebookresearch_flsim/flsim/data/dataset_data_loader.py

Prompts

```
['create FLUserDataFromList from a list of user batches and an IFLModel instance', 'iterate over training batches using FLUserDataFromList train_data method', 'iterate over evaluation batches using FLUserDataFromList eval_data method', 'create FLDataProviderFromList from train eval and test user lists with an IFLModel', 'get a specific train user by index using FLDataProviderFromList get_train_user method', 'create a RandomSharder to split training data randomly across a specified number of shards', 'build a SequentialSharder to assign consecutive rows to shards with a fixed examples per shard count', 'create a BroadcastSharder to copy each training datum to all shards for uniform distribution', 'build a ColumnSharder to partition data rows into shards based on a specified column value', 'create a RoundRobinSharder to split training data in a round-robin fashion across all shards', 'create an FLDatasetDataLoader instance with a dataset class, train/test/eval paths, and a sharder', 'get sharded training data batches from an FLDatasetDataLoader using the fl_train_set method', 'get the evaluation dataset from an FLDatasetDataLoader using the fl_eval_set method', 'create an FLDatasetDataLoaderWithBatch instance with pre-built datasets, a sharder, and a train batch size', 'get batched and sharded training data distributed across workers using fl_train_set with rank and world_size']
```

Usage

```
{'create_FLDatasetDataLoader': 'create an FLDatasetDataLoader instance with a dataset class, train/test/eval paths, and a sharder', 'get_fl_train_set': 'get sharded training data batches from an FLDatasetDataLoader using the fl_train_set method', 'get_fl_eval_set': 'get the evaluation dataset from an FLDatasetDataLoader using the fl_eval_set method', 'create_FLDatasetDataLoaderWithBatch': 'create an FLDatasetDataLoaderWithBatch instance with pre-built datasets, a sharder, and a train batch size', 'get_batched_train_set': 'get batched and sharded training data distributed across workers using fl_train_set with rank and world_size'}
```

