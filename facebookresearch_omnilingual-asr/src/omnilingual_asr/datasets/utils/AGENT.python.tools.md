# Agent Python Tools

- repo: facebookresearch/omnilingual-asr
- repo_uri: https://github.com/facebookresearch/omnilingual-asr

## File: facebookresearch_omnilingual-asr/src/omnilingual_asr/datasets/utils/audio.py

Prompts

```
['apply SpecAugment with frequency and time masking to an audio waveform tensor', 'postprocess an audio waveform with normalization and optional SpecAugment augmentation', 'add filterbank feature extraction to a fairseq2 data pipeline builder', 'crop audio sequences in a batch to a maximum length using AudioCropper', 'filter audio data by minimum and maximum length in a data pipeline', 'add static batching to a fairseq2 data pipeline with a fixed batch size', 'add length-based batching to a fairseq2 data pipeline using audio sequence lengths', 'use the BatchingStrategy enum to choose between STATIC or LENGTH batching strategies', 'create bucket sizes for length-based batching using fairseq2 create_bucket_sizes utility', 'apply bucket_by_length to a DataPipelineBuilder with computed bucket sizes and a selector', 'filter a DataPipelineBuilder to remove examples where the text field is empty', 'encode text in a DataPipelineBuilder using a TokenEncoder on the specified field', 'filter a DataPipelineBuilder to remove sequences containing only unknown tokens', 'filter a DataPipelineBuilder to remove text sequences exceeding a length threshold', 'filter a DataPipelineBuilder to remove samples with speech that is too fast']
```

Usage

```
{'apply_spec_augment': 'apply SpecAugment with frequency and time masking to an audio waveform tensor', 'postprocess_waveform': 'postprocess an audio waveform with normalization and optional SpecAugment augmentation', 'add_fbank_processing': 'add filterbank feature extraction to a fairseq2 data pipeline builder', 'AudioCropper': 'crop audio sequences in a batch to a maximum length using AudioCropper', 'filter_by_audio_length': 'filter audio data by minimum and maximum length in a data pipeline'}
```

## File: facebookresearch_omnilingual-asr/src/omnilingual_asr/datasets/utils/batching.py

Prompts

```
['apply SpecAugment with frequency and time masking to an audio waveform tensor', 'postprocess an audio waveform with normalization and optional SpecAugment augmentation', 'add filterbank feature extraction to a fairseq2 data pipeline builder', 'crop audio sequences in a batch to a maximum length using AudioCropper', 'filter audio data by minimum and maximum length in a data pipeline', 'add static batching to a fairseq2 data pipeline with a fixed batch size', 'add length-based batching to a fairseq2 data pipeline using audio sequence lengths', 'use the BatchingStrategy enum to choose between STATIC or LENGTH batching strategies', 'create bucket sizes for length-based batching using fairseq2 create_bucket_sizes utility', 'apply bucket_by_length to a DataPipelineBuilder with computed bucket sizes and a selector', 'filter a DataPipelineBuilder to remove examples where the text field is empty', 'encode text in a DataPipelineBuilder using a TokenEncoder on the specified field', 'filter a DataPipelineBuilder to remove sequences containing only unknown tokens', 'filter a DataPipelineBuilder to remove text sequences exceeding a length threshold', 'filter a DataPipelineBuilder to remove samples with speech that is too fast']
```

Usage

```
{'add_static_batching': 'add static batching to a fairseq2 data pipeline with a fixed batch size', 'add_length_batching': 'add length-based batching to a fairseq2 data pipeline using audio sequence lengths', 'BatchingStrategy_enum': 'use the BatchingStrategy enum to choose between STATIC or LENGTH batching strategies', 'create_bucket_sizes': 'create bucket sizes for length-based batching using fairseq2 create_bucket_sizes utility', 'bucket_by_length': 'apply bucket_by_length to a DataPipelineBuilder with computed bucket sizes and a selector'}
```

## File: facebookresearch_omnilingual-asr/src/omnilingual_asr/datasets/utils/text.py

Prompts

```
['apply SpecAugment with frequency and time masking to an audio waveform tensor', 'postprocess an audio waveform with normalization and optional SpecAugment augmentation', 'add filterbank feature extraction to a fairseq2 data pipeline builder', 'crop audio sequences in a batch to a maximum length using AudioCropper', 'filter audio data by minimum and maximum length in a data pipeline', 'add static batching to a fairseq2 data pipeline with a fixed batch size', 'add length-based batching to a fairseq2 data pipeline using audio sequence lengths', 'use the BatchingStrategy enum to choose between STATIC or LENGTH batching strategies', 'create bucket sizes for length-based batching using fairseq2 create_bucket_sizes utility', 'apply bucket_by_length to a DataPipelineBuilder with computed bucket sizes and a selector', 'filter a DataPipelineBuilder to remove examples where the text field is empty', 'encode text in a DataPipelineBuilder using a TokenEncoder on the specified field', 'filter a DataPipelineBuilder to remove sequences containing only unknown tokens', 'filter a DataPipelineBuilder to remove text sequences exceeding a length threshold', 'filter a DataPipelineBuilder to remove samples with speech that is too fast']
```

Usage

```
{'filter_empty_text': 'filter a DataPipelineBuilder to remove examples where the text field is empty', 'encode_text': 'encode text in a DataPipelineBuilder using a TokenEncoder on the specified field', 'filter_unknown_sequences': 'filter a DataPipelineBuilder to remove sequences containing only unknown tokens', 'filter_long_text': 'filter a DataPipelineBuilder to remove text sequences exceeding a length threshold', 'filter_fast_speech': 'filter a DataPipelineBuilder to remove samples with speech that is too fast'}
```

