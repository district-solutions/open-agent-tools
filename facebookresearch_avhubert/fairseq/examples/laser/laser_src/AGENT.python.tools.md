# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/laser/laser_src/laser_lstm.py

Prompts

```
['build a LASER LSTM encoder-decoder model for multilingual sentence embedding and translation tasks', 'build an LSTM encoder with optional bidirectional layers and pretrained embeddings for source sequence encoding', 'build an incremental LSTM decoder with language embedding support for target sequence generation', 'review the LSTMModel add_args method to configure encoder and decoder hyperparameters via CLI arguments', 'build a base LASER LSTM architecture with default encoder and decoder dimension and layer settings', 'setup a LaserTask from a JSON config file with source and target dictionaries', 'load a multitask language pair dataset split with optional automatic weighting and subsampling', 'build a fairseq model for the LaserTask using the registered model builder', 'get a multidataset epoch batch iterator for multitask language pair datasets with size filtering', 'add task-specific CLI arguments for config file path, weighting alpha, padding, and max positions', 'build a LASER transformer model with encoder and decoder for multilingual sentence embedding tasks', 'build a LASER transformer encoder that produces sentence embeddings via max-pooling over encoder outputs', 'build a LASER transformer decoder with language embedding support for multilingual sequence generation', 'review the LaserTransformerModel forward method that encodes source tokens and decodes with target language ID', 'review the LaserTransformerDecoder extract_features method that concatenates language and sentence embeddings to decoder features', 'create a MultiItr that iterates across multiple iterators in balanced proportion based on their lengths', 'build a MultidatasetEpochBatchIterator to wrap multiple FairseqDataset epoch batch iterators into a single unified iterator', 'review the MultidatasetEpochBatchIterator state_dict and load_state_dict methods for saving and restoring training progress', 'create a MultitaskDatasetWrapper to inject target_language_id and dataset_name into collated batch network inputs', 'test the MultitaskDatasetWrapper ordered_indices method to verify random sampling with a configurable sample fraction']
```

Usage

```
{'build_LSTMModel': 'build a LASER LSTM encoder-decoder model for multilingual sentence embedding and translation tasks', 'build_LSTMEncoder': 'build an LSTM encoder with optional bidirectional layers and pretrained embeddings for source sequence encoding', 'build_LSTMDecoder': 'build an incremental LSTM decoder with language embedding support for target sequence generation', 'review_LSTMModel_add_args': 'review the LSTMModel add_args method to configure encoder and decoder hyperparameters via CLI arguments', 'build_base_architecture': 'build a base LASER LSTM architecture with default encoder and decoder dimension and layer settings'}
```

## File: facebookresearch_avhubert/fairseq/examples/laser/laser_src/laser_task.py

Prompts

```
['build a LASER LSTM encoder-decoder model for multilingual sentence embedding and translation tasks', 'build an LSTM encoder with optional bidirectional layers and pretrained embeddings for source sequence encoding', 'build an incremental LSTM decoder with language embedding support for target sequence generation', 'review the LSTMModel add_args method to configure encoder and decoder hyperparameters via CLI arguments', 'build a base LASER LSTM architecture with default encoder and decoder dimension and layer settings', 'setup a LaserTask from a JSON config file with source and target dictionaries', 'load a multitask language pair dataset split with optional automatic weighting and subsampling', 'build a fairseq model for the LaserTask using the registered model builder', 'get a multidataset epoch batch iterator for multitask language pair datasets with size filtering', 'add task-specific CLI arguments for config file path, weighting alpha, padding, and max positions', 'build a LASER transformer model with encoder and decoder for multilingual sentence embedding tasks', 'build a LASER transformer encoder that produces sentence embeddings via max-pooling over encoder outputs', 'build a LASER transformer decoder with language embedding support for multilingual sequence generation', 'review the LaserTransformerModel forward method that encodes source tokens and decodes with target language ID', 'review the LaserTransformerDecoder extract_features method that concatenates language and sentence embeddings to decoder features', 'create a MultiItr that iterates across multiple iterators in balanced proportion based on their lengths', 'build a MultidatasetEpochBatchIterator to wrap multiple FairseqDataset epoch batch iterators into a single unified iterator', 'review the MultidatasetEpochBatchIterator state_dict and load_state_dict methods for saving and restoring training progress', 'create a MultitaskDatasetWrapper to inject target_language_id and dataset_name into collated batch network inputs', 'test the MultitaskDatasetWrapper ordered_indices method to verify random sampling with a configurable sample fraction']
```

Usage

```
{'setup_laser_task': 'setup a LaserTask from a JSON config file with source and target dictionaries', 'load_laser_dataset': 'load a multitask language pair dataset split with optional automatic weighting and subsampling', 'build_laser_model': 'build a fairseq model for the LaserTask using the registered model builder', 'get_laser_batch_iterator': 'get a multidataset epoch batch iterator for multitask language pair datasets with size filtering', 'add_laser_task_args': 'add task-specific CLI arguments for config file path, weighting alpha, padding, and max positions'}
```

## File: facebookresearch_avhubert/fairseq/examples/laser/laser_src/laser_transformer.py

Prompts

```
['build a LASER LSTM encoder-decoder model for multilingual sentence embedding and translation tasks', 'build an LSTM encoder with optional bidirectional layers and pretrained embeddings for source sequence encoding', 'build an incremental LSTM decoder with language embedding support for target sequence generation', 'review the LSTMModel add_args method to configure encoder and decoder hyperparameters via CLI arguments', 'build a base LASER LSTM architecture with default encoder and decoder dimension and layer settings', 'setup a LaserTask from a JSON config file with source and target dictionaries', 'load a multitask language pair dataset split with optional automatic weighting and subsampling', 'build a fairseq model for the LaserTask using the registered model builder', 'get a multidataset epoch batch iterator for multitask language pair datasets with size filtering', 'add task-specific CLI arguments for config file path, weighting alpha, padding, and max positions', 'build a LASER transformer model with encoder and decoder for multilingual sentence embedding tasks', 'build a LASER transformer encoder that produces sentence embeddings via max-pooling over encoder outputs', 'build a LASER transformer decoder with language embedding support for multilingual sequence generation', 'review the LaserTransformerModel forward method that encodes source tokens and decodes with target language ID', 'review the LaserTransformerDecoder extract_features method that concatenates language and sentence embeddings to decoder features', 'create a MultiItr that iterates across multiple iterators in balanced proportion based on their lengths', 'build a MultidatasetEpochBatchIterator to wrap multiple FairseqDataset epoch batch iterators into a single unified iterator', 'review the MultidatasetEpochBatchIterator state_dict and load_state_dict methods for saving and restoring training progress', 'create a MultitaskDatasetWrapper to inject target_language_id and dataset_name into collated batch network inputs', 'test the MultitaskDatasetWrapper ordered_indices method to verify random sampling with a configurable sample fraction']
```

Usage

```
{'build_laser_transformer_model': 'build a LASER transformer model with encoder and decoder for multilingual sentence embedding tasks', 'build_laser_transformer_encoder': 'build a LASER transformer encoder that produces sentence embeddings via max-pooling over encoder outputs', 'build_laser_transformer_decoder': 'build a LASER transformer decoder with language embedding support for multilingual sequence generation', 'review_laser_transformer_forward': 'review the LaserTransformerModel forward method that encodes source tokens and decodes with target language ID', 'review_laser_transformer_extract_features': 'review the LaserTransformerDecoder extract_features method that concatenates language and sentence embeddings to decoder features'}
```

## File: facebookresearch_avhubert/fairseq/examples/laser/laser_src/multitask_data_utils.py

Prompts

```
['build a LASER LSTM encoder-decoder model for multilingual sentence embedding and translation tasks', 'build an LSTM encoder with optional bidirectional layers and pretrained embeddings for source sequence encoding', 'build an incremental LSTM decoder with language embedding support for target sequence generation', 'review the LSTMModel add_args method to configure encoder and decoder hyperparameters via CLI arguments', 'build a base LASER LSTM architecture with default encoder and decoder dimension and layer settings', 'setup a LaserTask from a JSON config file with source and target dictionaries', 'load a multitask language pair dataset split with optional automatic weighting and subsampling', 'build a fairseq model for the LaserTask using the registered model builder', 'get a multidataset epoch batch iterator for multitask language pair datasets with size filtering', 'add task-specific CLI arguments for config file path, weighting alpha, padding, and max positions', 'build a LASER transformer model with encoder and decoder for multilingual sentence embedding tasks', 'build a LASER transformer encoder that produces sentence embeddings via max-pooling over encoder outputs', 'build a LASER transformer decoder with language embedding support for multilingual sequence generation', 'review the LaserTransformerModel forward method that encodes source tokens and decodes with target language ID', 'review the LaserTransformerDecoder extract_features method that concatenates language and sentence embeddings to decoder features', 'create a MultiItr that iterates across multiple iterators in balanced proportion based on their lengths', 'build a MultidatasetEpochBatchIterator to wrap multiple FairseqDataset epoch batch iterators into a single unified iterator', 'review the MultidatasetEpochBatchIterator state_dict and load_state_dict methods for saving and restoring training progress', 'create a MultitaskDatasetWrapper to inject target_language_id and dataset_name into collated batch network inputs', 'test the MultitaskDatasetWrapper ordered_indices method to verify random sampling with a configurable sample fraction']
```

Usage

```
{'create_multiitr_balanced_iterator': 'create a MultiItr that iterates across multiple iterators in balanced proportion based on their lengths', 'build_multidataset_epoch_batch_iterator': 'build a MultidatasetEpochBatchIterator to wrap multiple FairseqDataset epoch batch iterators into a single unified iterator', 'review_multidataset_epoch_batch_iterator_state': 'review the MultidatasetEpochBatchIterator state_dict and load_state_dict methods for saving and restoring training progress', 'create_multitask_dataset_wrapper': 'create a MultitaskDatasetWrapper to inject target_language_id and dataset_name into collated batch network inputs', 'test_multitask_dataset_wrapper_sampling': 'test the MultitaskDatasetWrapper ordered_indices method to verify random sampling with a configurable sample fraction'}
```

