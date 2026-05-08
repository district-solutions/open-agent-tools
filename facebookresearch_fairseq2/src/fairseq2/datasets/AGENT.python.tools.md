# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/datasets/batch.py

Prompts

```
['create a SequenceBatch with packed sequences and sequence lengths for efficient batched training', 'create a SequenceBatch with padded 2D sequences and per-example length list for standard batching', 'call as_auto_regressive on a SequenceBatch to get input and target batches shifted by one token', 'create a Seq2SeqBatch with source and target sequences plus their lengths for sequence-to-sequence training', 'call as_auto_regressive on a Seq2SeqBatch to get source-target input and target-only batches for training', 'create a DataPipelineReader to read batches from a DataPipeline with configurable accumulation and sync', 'review the SyncMode enum with UNTIL_FIRST and UNTIL_LAST modes for multi-rank data iteration', 'review the DataReader abstract class defining the interface for batch-reading iterators with state management', 'test the DataPipelineReader __next__ method to verify batch accumulation and end-of-data handling', 'refactor the DataPipelineReader sync logic to support custom synchronization strategies across distributed ranks', 'get the dataset family name from an asset card or card name string', 'get the dataset family name from an asset card or return None if not defined', 'get the validated dataset configuration from an asset card with override support', 'open a dataset from an asset card using default or provided configuration', 'open a custom dataset directly from a validated configuration object', 'open a dataset from the asset store by name using DatasetHub.open_dataset', 'get the dataset configuration from an asset card using DatasetHub.get_dataset_config', 'iterate over all dataset family asset cards using DatasetHub.iter_cards', 'open a custom dataset from a config object using DatasetHub.open_custom_dataset', 'create a DatasetHubAccessor to lazily resolve a DatasetHub by family name']
```

Usage

```
{'create_SequenceBatch_packed': 'create a SequenceBatch with packed sequences and sequence lengths for efficient batched training', 'create_SequenceBatch_unpacked': 'create a SequenceBatch with padded 2D sequences and per-example length list for standard batching', 'as_auto_regressive_SequenceBatch': 'call as_auto_regressive on a SequenceBatch to get input and target batches shifted by one token', 'create_Seq2SeqBatch': 'create a Seq2SeqBatch with source and target sequences plus their lengths for sequence-to-sequence training', 'as_auto_regressive_Seq2SeqBatch': 'call as_auto_regressive on a Seq2SeqBatch to get source-target input and target-only batches for training'}
```

## File: facebookresearch_fairseq2/src/fairseq2/datasets/data_reader.py

Prompts

```
['create a SequenceBatch with packed sequences and sequence lengths for efficient batched training', 'create a SequenceBatch with padded 2D sequences and per-example length list for standard batching', 'call as_auto_regressive on a SequenceBatch to get input and target batches shifted by one token', 'create a Seq2SeqBatch with source and target sequences plus their lengths for sequence-to-sequence training', 'call as_auto_regressive on a Seq2SeqBatch to get source-target input and target-only batches for training', 'create a DataPipelineReader to read batches from a DataPipeline with configurable accumulation and sync', 'review the SyncMode enum with UNTIL_FIRST and UNTIL_LAST modes for multi-rank data iteration', 'review the DataReader abstract class defining the interface for batch-reading iterators with state management', 'test the DataPipelineReader __next__ method to verify batch accumulation and end-of-data handling', 'refactor the DataPipelineReader sync logic to support custom synchronization strategies across distributed ranks', 'get the dataset family name from an asset card or card name string', 'get the dataset family name from an asset card or return None if not defined', 'get the validated dataset configuration from an asset card with override support', 'open a dataset from an asset card using default or provided configuration', 'open a custom dataset directly from a validated configuration object', 'open a dataset from the asset store by name using DatasetHub.open_dataset', 'get the dataset configuration from an asset card using DatasetHub.get_dataset_config', 'iterate over all dataset family asset cards using DatasetHub.iter_cards', 'open a custom dataset from a config object using DatasetHub.open_custom_dataset', 'create a DatasetHubAccessor to lazily resolve a DatasetHub by family name']
```

Usage

```
{'create_data_pipeline_reader': 'create a DataPipelineReader to read batches from a DataPipeline with configurable accumulation and sync', 'review_syncmode_enum': 'review the SyncMode enum with UNTIL_FIRST and UNTIL_LAST modes for multi-rank data iteration', 'review_datareader_abstract_class': 'review the DataReader abstract class defining the interface for batch-reading iterators with state management', 'test_data_pipeline_reader_next': 'test the DataPipelineReader __next__ method to verify batch accumulation and end-of-data handling', 'refactor_data_pipeline_reader_sync': 'refactor the DataPipelineReader sync logic to support custom synchronization strategies across distributed ranks'}
```

## File: facebookresearch_fairseq2/src/fairseq2/datasets/family.py

Prompts

```
['create a SequenceBatch with packed sequences and sequence lengths for efficient batched training', 'create a SequenceBatch with padded 2D sequences and per-example length list for standard batching', 'call as_auto_regressive on a SequenceBatch to get input and target batches shifted by one token', 'create a Seq2SeqBatch with source and target sequences plus their lengths for sequence-to-sequence training', 'call as_auto_regressive on a Seq2SeqBatch to get source-target input and target-only batches for training', 'create a DataPipelineReader to read batches from a DataPipeline with configurable accumulation and sync', 'review the SyncMode enum with UNTIL_FIRST and UNTIL_LAST modes for multi-rank data iteration', 'review the DataReader abstract class defining the interface for batch-reading iterators with state management', 'test the DataPipelineReader __next__ method to verify batch accumulation and end-of-data handling', 'refactor the DataPipelineReader sync logic to support custom synchronization strategies across distributed ranks', 'get the dataset family name from an asset card or card name string', 'get the dataset family name from an asset card or return None if not defined', 'get the validated dataset configuration from an asset card with override support', 'open a dataset from an asset card using default or provided configuration', 'open a custom dataset directly from a validated configuration object', 'open a dataset from the asset store by name using DatasetHub.open_dataset', 'get the dataset configuration from an asset card using DatasetHub.get_dataset_config', 'iterate over all dataset family asset cards using DatasetHub.iter_cards', 'open a custom dataset from a config object using DatasetHub.open_custom_dataset', 'create a DatasetHubAccessor to lazily resolve a DatasetHub by family name']
```

Usage

```
{'get_dataset_family_name': 'get the dataset family name from an asset card or card name string', 'maybe_get_dataset_family_name': 'get the dataset family name from an asset card or return None if not defined', 'StandardDatasetFamily_get_dataset_config': 'get the validated dataset configuration from an asset card with override support', 'StandardDatasetFamily_open_dataset': 'open a dataset from an asset card using default or provided configuration', 'StandardDatasetFamily_open_custom_dataset': 'open a custom dataset directly from a validated configuration object'}
```

## File: facebookresearch_fairseq2/src/fairseq2/datasets/hub.py

Prompts

```
['create a SequenceBatch with packed sequences and sequence lengths for efficient batched training', 'create a SequenceBatch with padded 2D sequences and per-example length list for standard batching', 'call as_auto_regressive on a SequenceBatch to get input and target batches shifted by one token', 'create a Seq2SeqBatch with source and target sequences plus their lengths for sequence-to-sequence training', 'call as_auto_regressive on a Seq2SeqBatch to get source-target input and target-only batches for training', 'create a DataPipelineReader to read batches from a DataPipeline with configurable accumulation and sync', 'review the SyncMode enum with UNTIL_FIRST and UNTIL_LAST modes for multi-rank data iteration', 'review the DataReader abstract class defining the interface for batch-reading iterators with state management', 'test the DataPipelineReader __next__ method to verify batch accumulation and end-of-data handling', 'refactor the DataPipelineReader sync logic to support custom synchronization strategies across distributed ranks', 'get the dataset family name from an asset card or card name string', 'get the dataset family name from an asset card or return None if not defined', 'get the validated dataset configuration from an asset card with override support', 'open a dataset from an asset card using default or provided configuration', 'open a custom dataset directly from a validated configuration object', 'open a dataset from the asset store by name using DatasetHub.open_dataset', 'get the dataset configuration from an asset card using DatasetHub.get_dataset_config', 'iterate over all dataset family asset cards using DatasetHub.iter_cards', 'open a custom dataset from a config object using DatasetHub.open_custom_dataset', 'create a DatasetHubAccessor to lazily resolve a DatasetHub by family name']
```

Usage

```
{'open_dataset_by_name': 'open a dataset from the asset store by name using DatasetHub.open_dataset', 'get_dataset_config': 'get the dataset configuration from an asset card using DatasetHub.get_dataset_config', 'iter_dataset_cards': 'iterate over all dataset family asset cards using DatasetHub.iter_cards', 'open_custom_dataset': 'open a custom dataset from a config object using DatasetHub.open_custom_dataset', 'create_dataset_hub_accessor': 'create a DatasetHubAccessor to lazily resolve a DatasetHub by family name'}
```

