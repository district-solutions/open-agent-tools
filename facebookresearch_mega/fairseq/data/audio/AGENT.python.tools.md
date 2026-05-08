# Agent Python Tools

- repo: facebookresearch/mega
- repo_uri: https://github.com/facebookresearch/mega

## File: facebookresearch_mega/fairseq/data/audio/raw_audio_dataset.py

Prompts

```
['create a FileAudioDataset from a manifest file with audio file paths and sample sizes', 'postprocess audio waveform features by converting stereo to mono and applying layer normalization', 'collate a batch of audio samples into padded tensors with optional padding masks', 'crop an audio waveform tensor to a target size using random start position sampling', 'get ordered indices for batching audio samples sorted by size with optional shuffling', 'create a SpeechCommandsDataset instance to load and preprocess the Google Speech Commands dataset for training', 'build a mu-law encoding pipeline to quantize audio signals into discrete levels for speech generation', 'test the split_data function to perform a stratified 70/15/15 train/val/test split on tensors', 'review the normalize_all_data function to standardize train, val, and test tensors using training statistics', 'create an SCTruncateDataset wrapper to truncate speech command sequences to a specified length']
```

Usage

```
{'create_FileAudioDataset_from_manifest': 'create a FileAudioDataset from a manifest file with audio file paths and sample sizes', 'postprocess_audio_features': 'postprocess audio waveform features by converting stereo to mono and applying layer normalization', 'collate_audio_samples': 'collate a batch of audio samples into padded tensors with optional padding masks', 'crop_audio_to_max_size': 'crop an audio waveform tensor to a target size using random start position sampling', 'get_ordered_indices_for_batching': 'get ordered indices for batching audio samples sorted by size with optional shuffling'}
```

## File: facebookresearch_mega/fairseq/data/audio/speech_commands_dataset.py

Prompts

```
['create a FileAudioDataset from a manifest file with audio file paths and sample sizes', 'postprocess audio waveform features by converting stereo to mono and applying layer normalization', 'collate a batch of audio samples into padded tensors with optional padding masks', 'crop an audio waveform tensor to a target size using random start position sampling', 'get ordered indices for batching audio samples sorted by size with optional shuffling', 'create a SpeechCommandsDataset instance to load and preprocess the Google Speech Commands dataset for training', 'build a mu-law encoding pipeline to quantize audio signals into discrete levels for speech generation', 'test the split_data function to perform a stratified 70/15/15 train/val/test split on tensors', 'review the normalize_all_data function to standardize train, val, and test tensors using training statistics', 'create an SCTruncateDataset wrapper to truncate speech command sequences to a specified length']
```

Usage

```
{'create_speech_commands_dataset': 'create a SpeechCommandsDataset instance to load and preprocess the Google Speech Commands dataset for training', 'build_mu_law_encoding': 'build a mu-law encoding pipeline to quantize audio signals into discrete levels for speech generation', 'test_split_data': 'test the split_data function to perform a stratified 70/15/15 train/val/test split on tensors', 'review_normalize_all_data': 'review the normalize_all_data function to standardize train, val, and test tensors using training statistics', 'create_sctruncatataset_wrapper': 'create an SCTruncateDataset wrapper to truncate speech command sequences to a specified length'}
```

