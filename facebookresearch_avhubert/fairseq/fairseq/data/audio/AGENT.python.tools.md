# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/data/audio/audio_utils.py

Prompts

```
['create a python module that loads a WAV audio file and returns its waveform and sample rate', 'build a python script that extracts mel-filter bank features from an audio file using PyKaldi or TorchAudio', 'create a function that converts a multi-channel audio waveform numpy array to mono using torchaudio', 'build a python tool that checks if raw bytes represent a numpy .npy file by inspecting the magic header', 'create a python module that parses an audio data path and returns the file path and optional byte slice offset', 'create a HubertDataset instance from an audio manifest and label files for fairseq training', 'load an audio manifest file filtering samples by min and max sample size', 'collate a batch of audio samples with padding or cropping to a uniform size', 'verify that audio durations match label durations within a tolerance threshold', 'postprocess a wav tensor by converting stereo to mono and applying layer normalization', 'create a RawAudioDataset instance to load and preprocess audio samples with configurable sample rate and normalization', 'create a FileAudioDataset from a manifest file to load audio files with optional bucketing and masking', 'create a BinarizedAudioDataset from a binarized data directory to load preprocessed audio samples for training', 'postprocess audio feature tensors by converting stereo to mono and applying layer normalization', 'compute temporal and channel mask indices for audio features using configurable masking probability and length', 'create a S2TDataConfig instance by loading a YAML config file for speech-to-text data settings', 'extract speech features from a .npy file or waveform from a .wav or .flac audio file', 'build a SpeechToTextDataset from TSV manifest files using SpeechToTextDatasetCreator.from_tsv with a target dictionary', 'collate a list of audio frame tensors into a padded batch using the SpeechToTextDataset collater method', 'tokenize text using pre-tokenizer and BPE tokenizer via the SpeechToTextDataset tokenize_text method']
```

Usage

```
{'get_waveform': 'create a python module that loads a WAV audio file and returns its waveform and sample rate', 'get_fbank': 'build a python script that extracts mel-filter bank features from an audio file using PyKaldi or TorchAudio', 'convert_to_mono': 'create a function that converts a multi-channel audio waveform numpy array to mono using torchaudio', 'is_npy_data': 'build a python tool that checks if raw bytes represent a numpy .npy file by inspecting the magic header', 'parse_path': 'create a python module that parses an audio data path and returns the file path and optional byte slice offset'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/data/audio/hubert_dataset.py

Prompts

```
['create a python module that loads a WAV audio file and returns its waveform and sample rate', 'build a python script that extracts mel-filter bank features from an audio file using PyKaldi or TorchAudio', 'create a function that converts a multi-channel audio waveform numpy array to mono using torchaudio', 'build a python tool that checks if raw bytes represent a numpy .npy file by inspecting the magic header', 'create a python module that parses an audio data path and returns the file path and optional byte slice offset', 'create a HubertDataset instance from an audio manifest and label files for fairseq training', 'load an audio manifest file filtering samples by min and max sample size', 'collate a batch of audio samples with padding or cropping to a uniform size', 'verify that audio durations match label durations within a tolerance threshold', 'postprocess a wav tensor by converting stereo to mono and applying layer normalization', 'create a RawAudioDataset instance to load and preprocess audio samples with configurable sample rate and normalization', 'create a FileAudioDataset from a manifest file to load audio files with optional bucketing and masking', 'create a BinarizedAudioDataset from a binarized data directory to load preprocessed audio samples for training', 'postprocess audio feature tensors by converting stereo to mono and applying layer normalization', 'compute temporal and channel mask indices for audio features using configurable masking probability and length', 'create a S2TDataConfig instance by loading a YAML config file for speech-to-text data settings', 'extract speech features from a .npy file or waveform from a .wav or .flac audio file', 'build a SpeechToTextDataset from TSV manifest files using SpeechToTextDatasetCreator.from_tsv with a target dictionary', 'collate a list of audio frame tensors into a padded batch using the SpeechToTextDataset collater method', 'tokenize text using pre-tokenizer and BPE tokenizer via the SpeechToTextDataset tokenize_text method']
```

Usage

```
{'create_HubertDataset': 'create a HubertDataset instance from an audio manifest and label files for fairseq training', 'load_audio_manifest': 'load an audio manifest file filtering samples by min and max sample size', 'collate_audio_samples': 'collate a batch of audio samples with padding or cropping to a uniform size', 'verify_label_lengths': 'verify that audio durations match label durations within a tolerance threshold', 'postprocess_wav_tensor': 'postprocess a wav tensor by converting stereo to mono and applying layer normalization'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/data/audio/raw_audio_dataset.py

Prompts

```
['create a python module that loads a WAV audio file and returns its waveform and sample rate', 'build a python script that extracts mel-filter bank features from an audio file using PyKaldi or TorchAudio', 'create a function that converts a multi-channel audio waveform numpy array to mono using torchaudio', 'build a python tool that checks if raw bytes represent a numpy .npy file by inspecting the magic header', 'create a python module that parses an audio data path and returns the file path and optional byte slice offset', 'create a HubertDataset instance from an audio manifest and label files for fairseq training', 'load an audio manifest file filtering samples by min and max sample size', 'collate a batch of audio samples with padding or cropping to a uniform size', 'verify that audio durations match label durations within a tolerance threshold', 'postprocess a wav tensor by converting stereo to mono and applying layer normalization', 'create a RawAudioDataset instance to load and preprocess audio samples with configurable sample rate and normalization', 'create a FileAudioDataset from a manifest file to load audio files with optional bucketing and masking', 'create a BinarizedAudioDataset from a binarized data directory to load preprocessed audio samples for training', 'postprocess audio feature tensors by converting stereo to mono and applying layer normalization', 'compute temporal and channel mask indices for audio features using configurable masking probability and length', 'create a S2TDataConfig instance by loading a YAML config file for speech-to-text data settings', 'extract speech features from a .npy file or waveform from a .wav or .flac audio file', 'build a SpeechToTextDataset from TSV manifest files using SpeechToTextDatasetCreator.from_tsv with a target dictionary', 'collate a list of audio frame tensors into a padded batch using the SpeechToTextDataset collater method', 'tokenize text using pre-tokenizer and BPE tokenizer via the SpeechToTextDataset tokenize_text method']
```

Usage

```
{'create_raw_audio_dataset': 'create a RawAudioDataset instance to load and preprocess audio samples with configurable sample rate and normalization', 'create_file_audio_dataset': 'create a FileAudioDataset from a manifest file to load audio files with optional bucketing and masking', 'create_binarized_audio_dataset': 'create a BinarizedAudioDataset from a binarized data directory to load preprocessed audio samples for training', 'postprocess_audio_features': 'postprocess audio feature tensors by converting stereo to mono and applying layer normalization', 'compute_mask_indices': 'compute temporal and channel mask indices for audio features using configurable masking probability and length'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/data/audio/speech_to_text_dataset.py

Prompts

```
['create a python module that loads a WAV audio file and returns its waveform and sample rate', 'build a python script that extracts mel-filter bank features from an audio file using PyKaldi or TorchAudio', 'create a function that converts a multi-channel audio waveform numpy array to mono using torchaudio', 'build a python tool that checks if raw bytes represent a numpy .npy file by inspecting the magic header', 'create a python module that parses an audio data path and returns the file path and optional byte slice offset', 'create a HubertDataset instance from an audio manifest and label files for fairseq training', 'load an audio manifest file filtering samples by min and max sample size', 'collate a batch of audio samples with padding or cropping to a uniform size', 'verify that audio durations match label durations within a tolerance threshold', 'postprocess a wav tensor by converting stereo to mono and applying layer normalization', 'create a RawAudioDataset instance to load and preprocess audio samples with configurable sample rate and normalization', 'create a FileAudioDataset from a manifest file to load audio files with optional bucketing and masking', 'create a BinarizedAudioDataset from a binarized data directory to load preprocessed audio samples for training', 'postprocess audio feature tensors by converting stereo to mono and applying layer normalization', 'compute temporal and channel mask indices for audio features using configurable masking probability and length', 'create a S2TDataConfig instance by loading a YAML config file for speech-to-text data settings', 'extract speech features from a .npy file or waveform from a .wav or .flac audio file', 'build a SpeechToTextDataset from TSV manifest files using SpeechToTextDatasetCreator.from_tsv with a target dictionary', 'collate a list of audio frame tensors into a padded batch using the SpeechToTextDataset collater method', 'tokenize text using pre-tokenizer and BPE tokenizer via the SpeechToTextDataset tokenize_text method']
```

Usage

```
{'load_S2TDataConfig_from_yaml': 'create a S2TDataConfig instance by loading a YAML config file for speech-to-text data settings', 'get_features_or_waveform_from_audio': 'extract speech features from a .npy file or waveform from a .wav or .flac audio file', 'build_SpeechToTextDataset_from_tsv': 'build a SpeechToTextDataset from TSV manifest files using SpeechToTextDatasetCreator.from_tsv with a target dictionary', 'collate_audio_frames_with_collater': 'collate a list of audio frame tensors into a padded batch using the SpeechToTextDataset collater method', 'tokenize_text_with_pre_and_bpe': 'tokenize text using pre-tokenizer and BPE tokenizer via the SpeechToTextDataset tokenize_text method'}
```

