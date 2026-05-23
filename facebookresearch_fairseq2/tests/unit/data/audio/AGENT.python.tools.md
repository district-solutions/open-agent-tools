# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/unit/data/audio/test_audio_decoder.py

Prompts

```
['test that AudioDecoder raises ValueError when initialized with an unsupported dtype like torch.bool', 'test that AudioDecoder correctly decodes an OGG Vorbis audio file from a MemoryBlock into a waveform tensor', 'test that AudioDecoder raises ValueError when called with non-MemoryBlock inputs like None, int, or string', 'test that AudioDecoder raises ValueError when called with an empty MemoryBlock containing zero bytes', 'test that AudioDecoder raises ValueError when called with a MemoryBlock containing invalid audio data', 'test the WaveformToFbankConverter to convert audio waveform to fbank features with channel_last=True', 'test the WaveformToFbankConverter with standardize=True to normalize fbank output to zero mean and unit std', 'test the WaveformToFbankConverter with keep_waveform=True to preserve the original waveform in output', 'test the WaveformToFbankConverter with a custom dtype like torch.float64 for fbank output', 'test the WaveformToFbankConverter error handling for invalid input types, missing keys, and wrong sample rates']
```

Usage

```
{'test_AudioDecoder_init_unsupported_dtype': 'test that AudioDecoder raises ValueError when initialized with an unsupported dtype like torch.bool', 'test_AudioDecoder_decode_ogg_audio': 'test that AudioDecoder correctly decodes an OGG Vorbis audio file from a MemoryBlock into a waveform tensor', 'test_AudioDecoder_reject_non_memory_block_input': 'test that AudioDecoder raises ValueError when called with non-MemoryBlock inputs like None, int, or string', 'test_AudioDecoder_reject_empty_memory_block': 'test that AudioDecoder raises ValueError when called with an empty MemoryBlock containing zero bytes', 'test_AudioDecoder_reject_invalid_audio_data': 'test that AudioDecoder raises ValueError when called with a MemoryBlock containing invalid audio data'}
```

## File: facebookresearch_fairseq2/tests/unit/data/audio/test_waveform_to_fbank_converter.py

Prompts

```
['test that AudioDecoder raises ValueError when initialized with an unsupported dtype like torch.bool', 'test that AudioDecoder correctly decodes an OGG Vorbis audio file from a MemoryBlock into a waveform tensor', 'test that AudioDecoder raises ValueError when called with non-MemoryBlock inputs like None, int, or string', 'test that AudioDecoder raises ValueError when called with an empty MemoryBlock containing zero bytes', 'test that AudioDecoder raises ValueError when called with a MemoryBlock containing invalid audio data', 'test the WaveformToFbankConverter to convert audio waveform to fbank features with channel_last=True', 'test the WaveformToFbankConverter with standardize=True to normalize fbank output to zero mean and unit std', 'test the WaveformToFbankConverter with keep_waveform=True to preserve the original waveform in output', 'test the WaveformToFbankConverter with a custom dtype like torch.float64 for fbank output', 'test the WaveformToFbankConverter error handling for invalid input types, missing keys, and wrong sample rates']
```

Usage

```
{'test_waveform_to_fbank_converter_basic': 'test the WaveformToFbankConverter to convert audio waveform to fbank features with channel_last=True', 'test_waveform_to_fbank_converter_standardize': 'test the WaveformToFbankConverter with standardize=True to normalize fbank output to zero mean and unit std', 'test_waveform_to_fbank_converter_keep_waveform': 'test the WaveformToFbankConverter with keep_waveform=True to preserve the original waveform in output', 'test_waveform_to_fbank_converter_dtype': 'test the WaveformToFbankConverter with a custom dtype like torch.float64 for fbank output', 'test_waveform_to_fbank_converter_error_handling': 'test the WaveformToFbankConverter error handling for invalid input types, missing keys, and wrong sample rates'}
```

