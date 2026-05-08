# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/datasets/collaters/mt_collater.py

Prompts

```
['create an MTCollater instance with a task config and exclude keys for multi-task collation', 'collate a list of AtomicData objects into a batch using the MTCollater callable', 'create a dataset to task mapping from a task config with dataset and level info', 'add missing task attributes as infinity tensors to AtomicData objects in a batch', 'review the MTCollater class and its data_list_collater method for multi-task batching logic', 'collate a list of AtomicData objects into a single batch using atomicdata_list_to_batch', 'collate AtomicData objects and compute neighbor counts from edge_index for each data point', 'collate a list of AtomicData objects and return the batch as a dictionary of tensors', 'collate AtomicData objects with otf_graph enabled to skip neighbor computation when edge index is missing', 'review the data_list_collater function to understand how AtomicData batching and neighbor counting work']
```

Usage

```
{'create_mt_collater': 'create an MTCollater instance with a task config and exclude keys for multi-task collation', 'collate_atomic_data_batch': 'collate a list of AtomicData objects into a batch using the MTCollater callable', 'create_dataset_task_map': 'create a dataset to task mapping from a task config with dataset and level info', 'add_missing_attributes': 'add missing task attributes as infinity tensors to AtomicData objects in a batch', 'review_mt_collater_class': 'review the MTCollater class and its data_list_collater method for multi-task batching logic'}
```

## File: facebookresearch_fairchem/src/fairchem/core/datasets/collaters/simple_collater.py

Prompts

```
['create an MTCollater instance with a task config and exclude keys for multi-task collation', 'collate a list of AtomicData objects into a batch using the MTCollater callable', 'create a dataset to task mapping from a task config with dataset and level info', 'add missing task attributes as infinity tensors to AtomicData objects in a batch', 'review the MTCollater class and its data_list_collater method for multi-task batching logic', 'collate a list of AtomicData objects into a single batch using atomicdata_list_to_batch', 'collate AtomicData objects and compute neighbor counts from edge_index for each data point', 'collate a list of AtomicData objects and return the batch as a dictionary of tensors', 'collate AtomicData objects with otf_graph enabled to skip neighbor computation when edge index is missing', 'review the data_list_collater function to understand how AtomicData batching and neighbor counting work']
```

Usage

```
{'collate_atomic_data_list_to_batch': 'collate a list of AtomicData objects into a single batch using atomicdata_list_to_batch', 'collate_atomic_data_with_neighbors': 'collate AtomicData objects and compute neighbor counts from edge_index for each data point', 'collate_atomic_data_to_dict': 'collate a list of AtomicData objects and return the batch as a dictionary of tensors', 'collate_atomic_data_with_otf_graph': 'collate AtomicData objects with otf_graph enabled to skip neighbor computation when edge index is missing', 'review_data_list_collater': 'review the data_list_collater function to understand how AtomicData batching and neighbor counting work'}
```

