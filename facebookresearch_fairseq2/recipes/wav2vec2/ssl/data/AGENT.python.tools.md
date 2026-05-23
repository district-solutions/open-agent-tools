# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/recipes/wav2vec2/ssl/data/batch_utils.py

Prompts

```
['build a data pipeline with length-based batching using add_length_batching for audio sequences', 'build a data pipeline with batch shuffling using add_batch_shuffling and a configurable window size', 'create bucket sizes for audio data batching based on min and max audio length parameters', 'review the add_length_batching function to understand how it rounds max_num_elements and creates buckets', 'review the add_batch_shuffling function to understand its OOM warning when batch_shuffle_window is zero', 'create a Wav2Vec2SslDataset from a manifest directory path using the from_path class method', 'create a data reader with audio processing pipeline for a specific split using create_reader', 'create a SequenceBatch from a batch dictionary containing audio waveform tensor data', 'open a wav2vec2 SSL dataset from a Wav2Vec2SslDatasetConfig using open_wav2vec2_ssl_dataset', 'review the Wav2Vec2SslDatasetSection dataclass configuration for audio length batching and shuffling settings', 'add audio file loading to a fairseq2 data pipeline builder using FileMapper with LRU caching', 'add audio decoding to a fairseq2 data pipeline builder with configurable dtype and normalization', 'crop audio sequences in a batch to a maximum length using random start positions', 'add audio cropping to a fairseq2 data pipeline builder to limit audio sequence length', 'get or set nested dictionary values using a dot-separated JSONPath style selector string']
```

Usage

```
{'build_length_batching_pipeline': 'build a data pipeline with length-based batching using add_length_batching for audio sequences', 'build_batch_shuffling_pipeline': 'build a data pipeline with batch shuffling using add_batch_shuffling and a configurable window size', 'create_bucket_sizes_for_audio': 'create bucket sizes for audio data batching based on min and max audio length parameters', 'review_add_length_batching': 'review the add_length_batching function to understand how it rounds max_num_elements and creates buckets', 'review_add_batch_shuffling': 'review the add_batch_shuffling function to understand its OOM warning when batch_shuffle_window is zero'}
```

## File: facebookresearch_fairseq2/recipes/wav2vec2/ssl/data/dataset.py

Prompts

```
['build a data pipeline with length-based batching using add_length_batching for audio sequences', 'build a data pipeline with batch shuffling using add_batch_shuffling and a configurable window size', 'create bucket sizes for audio data batching based on min and max audio length parameters', 'review the add_length_batching function to understand how it rounds max_num_elements and creates buckets', 'review the add_batch_shuffling function to understand its OOM warning when batch_shuffle_window is zero', 'create a Wav2Vec2SslDataset from a manifest directory path using the from_path class method', 'create a data reader with audio processing pipeline for a specific split using create_reader', 'create a SequenceBatch from a batch dictionary containing audio waveform tensor data', 'open a wav2vec2 SSL dataset from a Wav2Vec2SslDatasetConfig using open_wav2vec2_ssl_dataset', 'review the Wav2Vec2SslDatasetSection dataclass configuration for audio length batching and shuffling settings', 'add audio file loading to a fairseq2 data pipeline builder using FileMapper with LRU caching', 'add audio decoding to a fairseq2 data pipeline builder with configurable dtype and normalization', 'crop audio sequences in a batch to a maximum length using random start positions', 'add audio cropping to a fairseq2 data pipeline builder to limit audio sequence length', 'get or set nested dictionary values using a dot-separated JSONPath style selector string']
```

Usage

```
{'create_ssl_dataset_from_path': 'create a Wav2Vec2SslDataset from a manifest directory path using the from_path class method', 'create_ssl_data_reader': 'create a data reader with audio processing pipeline for a specific split using create_reader', 'create_sequence_batch': 'create a SequenceBatch from a batch dictionary containing audio waveform tensor data', 'open_ssl_dataset_from_config': 'open a wav2vec2 SSL dataset from a Wav2Vec2SslDatasetConfig using open_wav2vec2_ssl_dataset', 'review_ssl_dataset_section': 'review the Wav2Vec2SslDatasetSection dataclass configuration for audio length batching and shuffling settings'}
```

## File: facebookresearch_fairseq2/recipes/wav2vec2/ssl/data/preprocessing.py

Prompts

```
['build a data pipeline with length-based batching using add_length_batching for audio sequences', 'build a data pipeline with batch shuffling using add_batch_shuffling and a configurable window size', 'create bucket sizes for audio data batching based on min and max audio length parameters', 'review the add_length_batching function to understand how it rounds max_num_elements and creates buckets', 'review the add_batch_shuffling function to understand its OOM warning when batch_shuffle_window is zero', 'create a Wav2Vec2SslDataset from a manifest directory path using the from_path class method', 'create a data reader with audio processing pipeline for a specific split using create_reader', 'create a SequenceBatch from a batch dictionary containing audio waveform tensor data', 'open a wav2vec2 SSL dataset from a Wav2Vec2SslDatasetConfig using open_wav2vec2_ssl_dataset', 'review the Wav2Vec2SslDatasetSection dataclass configuration for audio length batching and shuffling settings', 'add audio file loading to a fairseq2 data pipeline builder using FileMapper with LRU caching', 'add audio decoding to a fairseq2 data pipeline builder with configurable dtype and normalization', 'crop audio sequences in a batch to a maximum length using random start positions', 'add audio cropping to a fairseq2 data pipeline builder to limit audio sequence length', 'get or set nested dictionary values using a dot-separated JSONPath style selector string']
```

Usage

```
{'add_audio_file_loading': 'add audio file loading to a fairseq2 data pipeline builder using FileMapper with LRU caching', 'add_audio_decoding': 'add audio decoding to a fairseq2 data pipeline builder with configurable dtype and normalization', 'AudioCropper_crop_audios_in_batch': 'crop audio sequences in a batch to a maximum length using random start positions', 'add_audio_cropping': 'add audio cropping to a fairseq2 data pipeline builder to limit audio sequence length', 'AudioCropper_get_set_nested': 'get or set nested dictionary values using a dot-separated JSONPath style selector string'}
```

