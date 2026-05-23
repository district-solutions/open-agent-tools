# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/recipes/wav2vec2/asr/data/batch_utils.py

Prompts

```
['build a data pipeline that buckets audio examples by length using configurable min and max audio lengths', 'create bucket sizes for ASR data pipeline based on audio length constraints and max element count', 'add batch shuffling with a configurable window size and seed to a data pipeline builder', 'review the add_length_batching function to understand how it rounds max_num_elements and creates bucket sizes', 'refactor the add_batch_shuffling function to support additional shuffle strategies beyond window-based shuffling', 'create a Wav2Vec2AsrDataset from a manifest directory path using the from_path class method', 'build a data reader with audio decoding, text tokenization, and batching using create_reader', 'configure a Wav2Vec2AsrDatasetSection with audio length limits, batching params, and shuffle windows', 'convert a collated audio-text example dict into a Seq2SeqBatch using to_seq2seq_batch', 'open a wav2vec2 ASR dataset from a Wav2Vec2AsrDatasetConfig using open_wav2vec2_asr_dataset', 'build a data pipeline step that memory-maps audio files from disk using FileMapper with LRU caching', 'build a data pipeline step that decodes audio files into waveforms with configurable dtype and parallel calls', 'build a data pipeline step that applies layer normalization to audio waveforms and casts to dtype', 'build a data pipeline step that encodes text tokens using a TokenEncoder with parallel calls', 'build a data pipeline step that filters examples by minimum and maximum audio length']
```

Usage

```
{'build_length_batching_pipeline': 'build a data pipeline that buckets audio examples by length using configurable min and max audio lengths', 'create_bucket_sizes_for_asr': 'create bucket sizes for ASR data pipeline based on audio length constraints and max element count', 'add_batch_shuffling_to_pipeline': 'add batch shuffling with a configurable window size and seed to a data pipeline builder', 'review_add_length_batching': 'review the add_length_batching function to understand how it rounds max_num_elements and creates bucket sizes', 'refactor_add_batch_shuffling': 'refactor the add_batch_shuffling function to support additional shuffle strategies beyond window-based shuffling'}
```

## File: facebookresearch_fairseq2/recipes/wav2vec2/asr/data/dataset.py

Prompts

```
['build a data pipeline that buckets audio examples by length using configurable min and max audio lengths', 'create bucket sizes for ASR data pipeline based on audio length constraints and max element count', 'add batch shuffling with a configurable window size and seed to a data pipeline builder', 'review the add_length_batching function to understand how it rounds max_num_elements and creates bucket sizes', 'refactor the add_batch_shuffling function to support additional shuffle strategies beyond window-based shuffling', 'create a Wav2Vec2AsrDataset from a manifest directory path using the from_path class method', 'build a data reader with audio decoding, text tokenization, and batching using create_reader', 'configure a Wav2Vec2AsrDatasetSection with audio length limits, batching params, and shuffle windows', 'convert a collated audio-text example dict into a Seq2SeqBatch using to_seq2seq_batch', 'open a wav2vec2 ASR dataset from a Wav2Vec2AsrDatasetConfig using open_wav2vec2_asr_dataset', 'build a data pipeline step that memory-maps audio files from disk using FileMapper with LRU caching', 'build a data pipeline step that decodes audio files into waveforms with configurable dtype and parallel calls', 'build a data pipeline step that applies layer normalization to audio waveforms and casts to dtype', 'build a data pipeline step that encodes text tokens using a TokenEncoder with parallel calls', 'build a data pipeline step that filters examples by minimum and maximum audio length']
```

Usage

```
{'create_wav2vec2_asr_dataset_from_path': 'create a Wav2Vec2AsrDataset from a manifest directory path using the from_path class method', 'build_data_reader_with_pipeline': 'build a data reader with audio decoding, text tokenization, and batching using create_reader', 'configure_wav2vec2_asr_dataset_section': 'configure a Wav2Vec2AsrDatasetSection with audio length limits, batching params, and shuffle windows', 'convert_example_to_seq2seq_batch': 'convert a collated audio-text example dict into a Seq2SeqBatch using to_seq2seq_batch', 'open_wav2vec2_asr_dataset_from_config': 'open a wav2vec2 ASR dataset from a Wav2Vec2AsrDatasetConfig using open_wav2vec2_asr_dataset'}
```

## File: facebookresearch_fairseq2/recipes/wav2vec2/asr/data/preprocessing.py

Prompts

```
['build a data pipeline that buckets audio examples by length using configurable min and max audio lengths', 'create bucket sizes for ASR data pipeline based on audio length constraints and max element count', 'add batch shuffling with a configurable window size and seed to a data pipeline builder', 'review the add_length_batching function to understand how it rounds max_num_elements and creates bucket sizes', 'refactor the add_batch_shuffling function to support additional shuffle strategies beyond window-based shuffling', 'create a Wav2Vec2AsrDataset from a manifest directory path using the from_path class method', 'build a data reader with audio decoding, text tokenization, and batching using create_reader', 'configure a Wav2Vec2AsrDatasetSection with audio length limits, batching params, and shuffle windows', 'convert a collated audio-text example dict into a Seq2SeqBatch using to_seq2seq_batch', 'open a wav2vec2 ASR dataset from a Wav2Vec2AsrDatasetConfig using open_wav2vec2_asr_dataset', 'build a data pipeline step that memory-maps audio files from disk using FileMapper with LRU caching', 'build a data pipeline step that decodes audio files into waveforms with configurable dtype and parallel calls', 'build a data pipeline step that applies layer normalization to audio waveforms and casts to dtype', 'build a data pipeline step that encodes text tokens using a TokenEncoder with parallel calls', 'build a data pipeline step that filters examples by minimum and maximum audio length']
```

Usage

```
{'build_audio_file_loading_pipeline': 'build a data pipeline step that memory-maps audio files from disk using FileMapper with LRU caching', 'build_audio_decoding_pipeline': 'build a data pipeline step that decodes audio files into waveforms with configurable dtype and parallel calls', 'build_layernorm_pipeline': 'build a data pipeline step that applies layer normalization to audio waveforms and casts to dtype', 'build_text_encoding_pipeline': 'build a data pipeline step that encodes text tokens using a TokenEncoder with parallel calls', 'build_audio_filter_pipeline': 'build a data pipeline step that filters examples by minimum and maximum audio length'}
```

