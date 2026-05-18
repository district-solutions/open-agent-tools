# Agent Python Tools

- repo: facebookresearch/omnilingual-asr
- repo_uri: https://github.com/facebookresearch/omnilingual-asr

## File: facebookresearch_omnilingual-asr/src/omnilingual_asr/datasets/tasks/asr_task.py

Prompts

```
['create an AsrTaskConfig with custom min and max audio length and batching strategy', 'build an ASR data processing pipeline using AsrTask.apply_processing_pipeline with a tokenizer and dtype', 'add a tokenization pipeline to filter empty text, encode text, and remove unknown tokens', 'add a bucketing pipeline with length or static batching strategy for ASR training data', 'add an audio processing pipeline with fbank features, waveform processing, and SpecAugment augmentation', 'create an SslTaskConfig with custom batching strategy, audio length limits, and spec augment parameters', 'build a self-supervised learning data pipeline using SslTask with shuffling, bucketing, and audio processing steps', 'configure length-based batching with max_num_elements and num_seqs_multiple_of for hardware optimization', 'apply audio decoding, fbank or waveform processing, and spec augment to the data pipeline builder', 'create a SequenceBatch from a batch dictionary with proper sequence length handling and no padding support']
```

Usage

```
{'create_asr_task_config': 'create an AsrTaskConfig with custom min and max audio length and batching strategy', 'build_asr_processing_pipeline': 'build an ASR data processing pipeline using AsrTask.apply_processing_pipeline with a tokenizer and dtype', 'add_tokenization_pipeline': 'add a tokenization pipeline to filter empty text, encode text, and remove unknown tokens', 'add_bucketing_pipeline': 'add a bucketing pipeline with length or static batching strategy for ASR training data', 'add_audio_processing_pipeline': 'add an audio processing pipeline with fbank features, waveform processing, and SpecAugment augmentation'}
```

## File: facebookresearch_omnilingual-asr/src/omnilingual_asr/datasets/tasks/ssl_task.py

Prompts

```
['create an AsrTaskConfig with custom min and max audio length and batching strategy', 'build an ASR data processing pipeline using AsrTask.apply_processing_pipeline with a tokenizer and dtype', 'add a tokenization pipeline to filter empty text, encode text, and remove unknown tokens', 'add a bucketing pipeline with length or static batching strategy for ASR training data', 'add an audio processing pipeline with fbank features, waveform processing, and SpecAugment augmentation', 'create an SslTaskConfig with custom batching strategy, audio length limits, and spec augment parameters', 'build a self-supervised learning data pipeline using SslTask with shuffling, bucketing, and audio processing steps', 'configure length-based batching with max_num_elements and num_seqs_multiple_of for hardware optimization', 'apply audio decoding, fbank or waveform processing, and spec augment to the data pipeline builder', 'create a SequenceBatch from a batch dictionary with proper sequence length handling and no padding support']
```

Usage

```
{'create_ssl_task_config': 'create an SslTaskConfig with custom batching strategy, audio length limits, and spec augment parameters', 'build_ssl_data_pipeline': 'build a self-supervised learning data pipeline using SslTask with shuffling, bucketing, and audio processing steps', 'configure_length_batching': 'configure length-based batching with max_num_elements and num_seqs_multiple_of for hardware optimization', 'apply_audio_processing': 'apply audio decoding, fbank or waveform processing, and spec augment to the data pipeline builder', 'create_sequence_batch': 'create a SequenceBatch from a batch dictionary with proper sequence length handling and no padding support'}
```

