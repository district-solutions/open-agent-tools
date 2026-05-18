# Agent Python Tools

- repo: facebookresearch/omnilingual-asr
- repo_uri: https://github.com/facebookresearch/omnilingual-asr

## File: facebookresearch_omnilingual-asr/src/omnilingual_asr/datasets/interfaces/storage_interface.py

Prompts

```
['create a StorageConfig dataclass instance with sync_batches and sync_mode settings for data storage', 'implement a subclass of StorageInterface to provide a custom data storage backend', 'call create_raw_data_pipeline on a StorageInterface subclass to build a DataPipelineBuilder for a split', 'access the splits property on a StorageInterface subclass to get available dataset split names', 'access the config property on a StorageInterface instance to retrieve its StorageConfig settings', 'create a TaskConfig dataclass subclass to hold task-specific configuration parameters', 'implement a TaskInterface subclass that applies task-specific processing to raw examples', 'apply task-specific processing to raw examples using a DataPipelineBuilder and Gangs', 'get the batch type that a TaskInterface subclass produces for downstream processing', 'review the TaskInterface abstract base class and its required abstract methods']
```

Usage

```
{'create_storage_config': 'create a StorageConfig dataclass instance with sync_batches and sync_mode settings for data storage', 'implement_storage_interface': 'implement a subclass of StorageInterface to provide a custom data storage backend', 'create_raw_data_pipeline': 'call create_raw_data_pipeline on a StorageInterface subclass to build a DataPipelineBuilder for a split', 'get_storage_splits': 'access the splits property on a StorageInterface subclass to get available dataset split names', 'access_storage_config': 'access the config property on a StorageInterface instance to retrieve its StorageConfig settings'}
```

## File: facebookresearch_omnilingual-asr/src/omnilingual_asr/datasets/interfaces/task_interface.py

Prompts

```
['create a StorageConfig dataclass instance with sync_batches and sync_mode settings for data storage', 'implement a subclass of StorageInterface to provide a custom data storage backend', 'call create_raw_data_pipeline on a StorageInterface subclass to build a DataPipelineBuilder for a split', 'access the splits property on a StorageInterface subclass to get available dataset split names', 'access the config property on a StorageInterface instance to retrieve its StorageConfig settings', 'create a TaskConfig dataclass subclass to hold task-specific configuration parameters', 'implement a TaskInterface subclass that applies task-specific processing to raw examples', 'apply task-specific processing to raw examples using a DataPipelineBuilder and Gangs', 'get the batch type that a TaskInterface subclass produces for downstream processing', 'review the TaskInterface abstract base class and its required abstract methods']
```

Usage

```
{'create_TaskConfig': 'create a TaskConfig dataclass subclass to hold task-specific configuration parameters', 'implement_TaskInterface': 'implement a TaskInterface subclass that applies task-specific processing to raw examples', 'apply_processing_pipeline': 'apply task-specific processing to raw examples using a DataPipelineBuilder and Gangs', 'get_batch_type': 'get the batch type that a TaskInterface subclass produces for downstream processing', 'review_TaskInterface': 'review the TaskInterface abstract base class and its required abstract methods'}
```

