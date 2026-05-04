# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/data/audio/audio_utils.py

Prompts

```
['get the waveform and sample rate from a WAV or FLAC audio file using soundfile', 'get the waveform as 16-bit signed integers from a WAV file by disabling normalization', 'extract mel-filter bank features from a WAV or FLAC audio file using PyKaldi or TorchAudio', 'extract mel-filter bank features with a custom number of mel bins from an audio file', 'review the get_waveform function to understand how it reads WAV and FLAC files with soundfile', 'create a FileAudioDataset from a manifest file with tab-separated filenames and sample sizes', 'build a RawAudioDataset subclass that overrides __getitem__ to load audio samples from a custom source', 'test the RawAudioDataset collater method to batch audio samples with padding and padding masks', 'review the RawAudioDataset postprocess method that converts stereo to mono and applies layer normalization', 'summarize the RawAudioDataset crop_to_max_size method that randomly crops waveforms to a target size', 'create an S2TDataConfig instance by loading speech-to-text data configuration from a YAML file path', 'build a SpeechToTextDataset from TSV manifest files using SpeechToTextDatasetCreator.from_tsv with root, config, and splits', 'extract speech features from .npy files or waveforms from .wav/.flac files using get_features_or_waveform', 'collate a list of 2D audio frames into a padded 3D tensor using _collate_frames for batching', 'get split-specific audio feature transforms from S2TDataConfig using get_feature_transforms with split name and training flag']
```

Usage

```
{'get_waveform_from_wav': 'get the waveform and sample rate from a WAV or FLAC audio file using soundfile', 'get_waveform_denormalized': 'get the waveform as 16-bit signed integers from a WAV file by disabling normalization', 'get_fbank_features': 'extract mel-filter bank features from a WAV or FLAC audio file using PyKaldi or TorchAudio', 'get_fbank_custom_bins': 'extract mel-filter bank features with a custom number of mel bins from an audio file', 'review_get_waveform': 'review the get_waveform function to understand how it reads WAV and FLAC files with soundfile'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/data/audio/raw_audio_dataset.py

Prompts

```
['get the waveform and sample rate from a WAV or FLAC audio file using soundfile', 'get the waveform as 16-bit signed integers from a WAV file by disabling normalization', 'extract mel-filter bank features from a WAV or FLAC audio file using PyKaldi or TorchAudio', 'extract mel-filter bank features with a custom number of mel bins from an audio file', 'review the get_waveform function to understand how it reads WAV and FLAC files with soundfile', 'create a FileAudioDataset from a manifest file with tab-separated filenames and sample sizes', 'build a RawAudioDataset subclass that overrides __getitem__ to load audio samples from a custom source', 'test the RawAudioDataset collater method to batch audio samples with padding and padding masks', 'review the RawAudioDataset postprocess method that converts stereo to mono and applies layer normalization', 'summarize the RawAudioDataset crop_to_max_size method that randomly crops waveforms to a target size', 'create an S2TDataConfig instance by loading speech-to-text data configuration from a YAML file path', 'build a SpeechToTextDataset from TSV manifest files using SpeechToTextDatasetCreator.from_tsv with root, config, and splits', 'extract speech features from .npy files or waveforms from .wav/.flac files using get_features_or_waveform', 'collate a list of 2D audio frames into a padded 3D tensor using _collate_frames for batching', 'get split-specific audio feature transforms from S2TDataConfig using get_feature_transforms with split name and training flag']
```

Usage

```
{'create_FileAudioDataset_from_manifest': 'create a FileAudioDataset from a manifest file with tab-separated filenames and sample sizes', 'build_RawAudioDataset_subclass': 'build a RawAudioDataset subclass that overrides __getitem__ to load audio samples from a custom source', 'test_collater_padding': 'test the RawAudioDataset collater method to batch audio samples with padding and padding masks', 'review_postprocess_normalization': 'review the RawAudioDataset postprocess method that converts stereo to mono and applies layer normalization', 'summarize_crop_to_max_size': 'summarize the RawAudioDataset crop_to_max_size method that randomly crops waveforms to a target size'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/data/audio/speech_to_text_dataset.py

Prompts

```
['get the waveform and sample rate from a WAV or FLAC audio file using soundfile', 'get the waveform as 16-bit signed integers from a WAV file by disabling normalization', 'extract mel-filter bank features from a WAV or FLAC audio file using PyKaldi or TorchAudio', 'extract mel-filter bank features with a custom number of mel bins from an audio file', 'review the get_waveform function to understand how it reads WAV and FLAC files with soundfile', 'create a FileAudioDataset from a manifest file with tab-separated filenames and sample sizes', 'build a RawAudioDataset subclass that overrides __getitem__ to load audio samples from a custom source', 'test the RawAudioDataset collater method to batch audio samples with padding and padding masks', 'review the RawAudioDataset postprocess method that converts stereo to mono and applies layer normalization', 'summarize the RawAudioDataset crop_to_max_size method that randomly crops waveforms to a target size', 'create an S2TDataConfig instance by loading speech-to-text data configuration from a YAML file path', 'build a SpeechToTextDataset from TSV manifest files using SpeechToTextDatasetCreator.from_tsv with root, config, and splits', 'extract speech features from .npy files or waveforms from .wav/.flac files using get_features_or_waveform', 'collate a list of 2D audio frames into a padded 3D tensor using _collate_frames for batching', 'get split-specific audio feature transforms from S2TDataConfig using get_feature_transforms with split name and training flag']
```

Usage

```
{'create_S2TDataConfig_from_yaml': 'create an S2TDataConfig instance by loading speech-to-text data configuration from a YAML file path', 'build_SpeechToTextDataset_from_tsv': 'build a SpeechToTextDataset from TSV manifest files using SpeechToTextDatasetCreator.from_tsv with root, config, and splits', 'extract_audio_features_or_waveform': 'extract speech features from .npy files or waveforms from .wav/.flac files using get_features_or_waveform', 'collate_audio_frames_into_tensor': 'collate a list of 2D audio frames into a padded 3D tensor using _collate_frames for batching', 'get_split_feature_transforms': 'get split-specific audio feature transforms from S2TDataConfig using get_feature_transforms with split name and training flag'}
```

