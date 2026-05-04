# Agent Python Tools

- repo: facebookresearch/flowdec
- repo_uri: https://github.com/facebookresearch/flowdec

## File: facebookresearch_flowdec/flowdec/data/data_module.py

Prompts

```
['create a PairedAudioFiles dataset from clean and noisy WAV folders with resampling and cropping', 'load a specific clean and noisy audio pair by index with optional padding and cropping', 'create a PairedAudioDataModule with train, validation, and test dataloaders for paired audio files', 'setup shuffled training and unshuffled validation dataloaders with configurable batch size and workers', 'get uncropped audio samples from train, valid, or test sets for evaluation without batching', 'create a ComplexSTFT module to compute the complex STFT of audio tensors with a configurable window function', 'invert a complex spectrogram tensor back to audio waveform using the ComplexSTFT invert method', 'build an AmplitudeCompressedComplexSTFT pipeline that applies STFT followed by amplitude compression and scaling', 'create a CompressAmplitudesAndScale module to compress amplitudes with an exponent and scale a complex spectrogram', 'create an InvertibleSequential module to chain multiple invertible feature extractors in forward and reverse order']
```

Usage

```
{'create_paired_audio_dataset': 'create a PairedAudioFiles dataset from clean and noisy WAV folders with resampling and cropping', 'load_audio_pair_by_index': 'load a specific clean and noisy audio pair by index with optional padding and cropping', 'create_lightning_datamodule': 'create a PairedAudioDataModule with train, validation, and test dataloaders for paired audio files', 'setup_train_validation_dataloaders': 'setup shuffled training and unshuffled validation dataloaders with configurable batch size and workers', 'get_evaluation_samples': 'get uncropped audio samples from train, valid, or test sets for evaluation without batching'}
```

## File: facebookresearch_flowdec/flowdec/data/feature_extractors.py

Prompts

```
['create a PairedAudioFiles dataset from clean and noisy WAV folders with resampling and cropping', 'load a specific clean and noisy audio pair by index with optional padding and cropping', 'create a PairedAudioDataModule with train, validation, and test dataloaders for paired audio files', 'setup shuffled training and unshuffled validation dataloaders with configurable batch size and workers', 'get uncropped audio samples from train, valid, or test sets for evaluation without batching', 'create a ComplexSTFT module to compute the complex STFT of audio tensors with a configurable window function', 'invert a complex spectrogram tensor back to audio waveform using the ComplexSTFT invert method', 'build an AmplitudeCompressedComplexSTFT pipeline that applies STFT followed by amplitude compression and scaling', 'create a CompressAmplitudesAndScale module to compress amplitudes with an exponent and scale a complex spectrogram', 'create an InvertibleSequential module to chain multiple invertible feature extractors in forward and reverse order']
```

Usage

```
{'create_complex_stft_extractor': 'create a ComplexSTFT module to compute the complex STFT of audio tensors with a configurable window function', 'invert_complex_stft_spectrogram': 'invert a complex spectrogram tensor back to audio waveform using the ComplexSTFT invert method', 'build_amplitude_compressed_stft': 'build an AmplitudeCompressedComplexSTFT pipeline that applies STFT followed by amplitude compression and scaling', 'compress_and_scale_spectrogram': 'create a CompressAmplitudesAndScale module to compress amplitudes with an exponent and scale a complex spectrogram', 'chain_invertible_extractors': 'create an InvertibleSequential module to chain multiple invertible feature extractors in forward and reverse order'}
```

