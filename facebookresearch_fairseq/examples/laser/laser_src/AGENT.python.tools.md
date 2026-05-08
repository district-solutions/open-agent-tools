# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/laser/laser_src/laser_lstm.py

Prompts

```
['build a LASER LSTM encoder-decoder model for multilingual sentence embedding and translation', 'build an LSTM encoder that produces sentence embeddings via max-pooling over encoder outputs', 'build an incremental LSTM decoder with language embedding support for sequence generation', 'review the LSTMModel add_args method to configure encoder and decoder hyperparameters', 'review the base_architecture function to set default LASER LSTM model architecture arguments', 'setup a LaserTask from a JSON config file with source and target vocabularies', 'load a multitask language pair dataset split with optional automatic weighting and subsampling', 'build a fairseq model for the LaserTask using registered model arguments', 'get a multidataset epoch batch iterator for multitask language pair datasets with batching and filtering', 'add LaserTask CLI arguments for config file path, weighting alpha, padding, and max positions', 'build a LaserTransformerModel with encoder and decoder for the LASER multilingual task', 'build a LaserTransformerEncoder that max-pools encoder outputs into sentence embeddings', 'build a LaserTransformerDecoder with language embeddings and sentence embedding concatenation', 'review the LaserTransformerModel forward pass that encodes source tokens and decodes with language id', 'review the LaserTransformerDecoder extract_features method that concatenates language and sentence embeddings', 'create a MultiItr that iterates across multiple iterators in balanced proportion based on their lengths', 'build a MultidatasetEpochBatchIterator to wrap multiple FairseqDataset epoch batch iterators with sharding support', 'create a MultitaskDatasetWrapper that injects target_language_id and dataset_name into collated batch net_input', 'test the MultitaskDatasetWrapper ordered_indices method to sample a fraction of dataset indices randomly', 'review the MultidatasetEpochBatchIterator state_dict and load_state_dict methods for checkpoint save and restore']
```

Usage

```
{'build_LSTMModel': 'build a LASER LSTM encoder-decoder model for multilingual sentence embedding and translation', 'build_LSTMEncoder': 'build an LSTM encoder that produces sentence embeddings via max-pooling over encoder outputs', 'build_LSTMDecoder': 'build an incremental LSTM decoder with language embedding support for sequence generation', 'review_LSTMModel_add_args': 'review the LSTMModel add_args method to configure encoder and decoder hyperparameters', 'review_base_architecture': 'review the base_architecture function to set default LASER LSTM model architecture arguments'}
```

## File: facebookresearch_fairseq/examples/laser/laser_src/laser_task.py

Prompts

```
['build a LASER LSTM encoder-decoder model for multilingual sentence embedding and translation', 'build an LSTM encoder that produces sentence embeddings via max-pooling over encoder outputs', 'build an incremental LSTM decoder with language embedding support for sequence generation', 'review the LSTMModel add_args method to configure encoder and decoder hyperparameters', 'review the base_architecture function to set default LASER LSTM model architecture arguments', 'setup a LaserTask from a JSON config file with source and target vocabularies', 'load a multitask language pair dataset split with optional automatic weighting and subsampling', 'build a fairseq model for the LaserTask using registered model arguments', 'get a multidataset epoch batch iterator for multitask language pair datasets with batching and filtering', 'add LaserTask CLI arguments for config file path, weighting alpha, padding, and max positions', 'build a LaserTransformerModel with encoder and decoder for the LASER multilingual task', 'build a LaserTransformerEncoder that max-pools encoder outputs into sentence embeddings', 'build a LaserTransformerDecoder with language embeddings and sentence embedding concatenation', 'review the LaserTransformerModel forward pass that encodes source tokens and decodes with language id', 'review the LaserTransformerDecoder extract_features method that concatenates language and sentence embeddings', 'create a MultiItr that iterates across multiple iterators in balanced proportion based on their lengths', 'build a MultidatasetEpochBatchIterator to wrap multiple FairseqDataset epoch batch iterators with sharding support', 'create a MultitaskDatasetWrapper that injects target_language_id and dataset_name into collated batch net_input', 'test the MultitaskDatasetWrapper ordered_indices method to sample a fraction of dataset indices randomly', 'review the MultidatasetEpochBatchIterator state_dict and load_state_dict methods for checkpoint save and restore']
```

Usage

```
{'setup_laser_task': 'setup a LaserTask from a JSON config file with source and target vocabularies', 'load_laser_dataset': 'load a multitask language pair dataset split with optional automatic weighting and subsampling', 'build_laser_model': 'build a fairseq model for the LaserTask using registered model arguments', 'get_laser_batch_iterator': 'get a multidataset epoch batch iterator for multitask language pair datasets with batching and filtering', 'add_laser_task_args': 'add LaserTask CLI arguments for config file path, weighting alpha, padding, and max positions'}
```

## File: facebookresearch_fairseq/examples/laser/laser_src/laser_transformer.py

Prompts

```
['build a LASER LSTM encoder-decoder model for multilingual sentence embedding and translation', 'build an LSTM encoder that produces sentence embeddings via max-pooling over encoder outputs', 'build an incremental LSTM decoder with language embedding support for sequence generation', 'review the LSTMModel add_args method to configure encoder and decoder hyperparameters', 'review the base_architecture function to set default LASER LSTM model architecture arguments', 'setup a LaserTask from a JSON config file with source and target vocabularies', 'load a multitask language pair dataset split with optional automatic weighting and subsampling', 'build a fairseq model for the LaserTask using registered model arguments', 'get a multidataset epoch batch iterator for multitask language pair datasets with batching and filtering', 'add LaserTask CLI arguments for config file path, weighting alpha, padding, and max positions', 'build a LaserTransformerModel with encoder and decoder for the LASER multilingual task', 'build a LaserTransformerEncoder that max-pools encoder outputs into sentence embeddings', 'build a LaserTransformerDecoder with language embeddings and sentence embedding concatenation', 'review the LaserTransformerModel forward pass that encodes source tokens and decodes with language id', 'review the LaserTransformerDecoder extract_features method that concatenates language and sentence embeddings', 'create a MultiItr that iterates across multiple iterators in balanced proportion based on their lengths', 'build a MultidatasetEpochBatchIterator to wrap multiple FairseqDataset epoch batch iterators with sharding support', 'create a MultitaskDatasetWrapper that injects target_language_id and dataset_name into collated batch net_input', 'test the MultitaskDatasetWrapper ordered_indices method to sample a fraction of dataset indices randomly', 'review the MultidatasetEpochBatchIterator state_dict and load_state_dict methods for checkpoint save and restore']
```

Usage

```
{'build_laser_transformer_model': 'build a LaserTransformerModel with encoder and decoder for the LASER multilingual task', 'build_laser_encoder': 'build a LaserTransformerEncoder that max-pools encoder outputs into sentence embeddings', 'build_laser_decoder': 'build a LaserTransformerDecoder with language embeddings and sentence embedding concatenation', 'review_laser_transformer_forward': 'review the LaserTransformerModel forward pass that encodes source tokens and decodes with language id', 'review_laser_decoder_extract_features': 'review the LaserTransformerDecoder extract_features method that concatenates language and sentence embeddings'}
```

## File: facebookresearch_fairseq/examples/laser/laser_src/multitask_data_utils.py

Prompts

```
['build a LASER LSTM encoder-decoder model for multilingual sentence embedding and translation', 'build an LSTM encoder that produces sentence embeddings via max-pooling over encoder outputs', 'build an incremental LSTM decoder with language embedding support for sequence generation', 'review the LSTMModel add_args method to configure encoder and decoder hyperparameters', 'review the base_architecture function to set default LASER LSTM model architecture arguments', 'setup a LaserTask from a JSON config file with source and target vocabularies', 'load a multitask language pair dataset split with optional automatic weighting and subsampling', 'build a fairseq model for the LaserTask using registered model arguments', 'get a multidataset epoch batch iterator for multitask language pair datasets with batching and filtering', 'add LaserTask CLI arguments for config file path, weighting alpha, padding, and max positions', 'build a LaserTransformerModel with encoder and decoder for the LASER multilingual task', 'build a LaserTransformerEncoder that max-pools encoder outputs into sentence embeddings', 'build a LaserTransformerDecoder with language embeddings and sentence embedding concatenation', 'review the LaserTransformerModel forward pass that encodes source tokens and decodes with language id', 'review the LaserTransformerDecoder extract_features method that concatenates language and sentence embeddings', 'create a MultiItr that iterates across multiple iterators in balanced proportion based on their lengths', 'build a MultidatasetEpochBatchIterator to wrap multiple FairseqDataset epoch batch iterators with sharding support', 'create a MultitaskDatasetWrapper that injects target_language_id and dataset_name into collated batch net_input', 'test the MultitaskDatasetWrapper ordered_indices method to sample a fraction of dataset indices randomly', 'review the MultidatasetEpochBatchIterator state_dict and load_state_dict methods for checkpoint save and restore']
```

Usage

```
{'create_multiitr_balanced_iteration': 'create a MultiItr that iterates across multiple iterators in balanced proportion based on their lengths', 'build_multidataset_epoch_batch_iterator': 'build a MultidatasetEpochBatchIterator to wrap multiple FairseqDataset epoch batch iterators with sharding support', 'create_multitask_dataset_wrapper': 'create a MultitaskDatasetWrapper that injects target_language_id and dataset_name into collated batch net_input', 'test_multitask_dataset_sampling': 'test the MultitaskDatasetWrapper ordered_indices method to sample a fraction of dataset indices randomly', 'review_multidataset_state_management': 'review the MultidatasetEpochBatchIterator state_dict and load_state_dict methods for checkpoint save and restore'}
```

