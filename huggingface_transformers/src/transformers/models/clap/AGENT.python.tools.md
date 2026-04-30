# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/clap/convert_clap_original_pytorch_to_hf.py

Prompts

```
['convert a CLAP checkpoint from laion to HuggingFace transformers format using CLI arguments', 'initialize a CLAP model from a checkpoint path with a specified model type and fusion option', 'rename state dict keys from original CLAP format to HuggingFace transformers naming convention', 'extract audio and text configuration from a loaded CLAP model into a ClapConfig object', 'run the CLAP checkpoint conversion script via argparse with checkpoint path and output folder', 'create a ClapFeatureExtractor instance with custom mel filter bank parameters for audio feature extraction', 'build log-mel spectrogram features from raw audio waveforms using STFT and mel-filter banks', 'extract fbank features from a numpy audio waveform using the Hann window and mel filter configuration', 'apply random mel fusion to combine three random crops and a downsampled mel spectrogram for long audio', 'featurize raw speech audio into batched mel spectrogram inputs with truncation and padding handling', 'run the ClapModel to compute audio-text similarity scores with contrastive loss', 'get normalized text embeddings from the ClapModel using input_ids and attention_mask', 'get normalized audio embeddings from the ClapModel using mel spectrogram input_features', 'build a ClapTextModel with projection layer for text embedding generation', 'build a ClapAudioModel with Swin Transformer encoder for audio feature extraction']
```

Usage

```
{'convert_clap_checkpoint': 'convert a CLAP checkpoint from laion to HuggingFace transformers format using CLI arguments', 'init_clap_model': 'initialize a CLAP model from a checkpoint path with a specified model type and fusion option', 'rename_state_dict_keys': 'rename state dict keys from original CLAP format to HuggingFace transformers naming convention', 'get_clap_config_from_model': 'extract audio and text configuration from a loaded CLAP model into a ClapConfig object', 'run_clap_conversion_cli': 'run the CLAP checkpoint conversion script via argparse with checkpoint path and output folder'}
```

## File: huggingface_transformers/src/transformers/models/clap/feature_extraction_clap.py

Prompts

```
['convert a CLAP checkpoint from laion to HuggingFace transformers format using CLI arguments', 'initialize a CLAP model from a checkpoint path with a specified model type and fusion option', 'rename state dict keys from original CLAP format to HuggingFace transformers naming convention', 'extract audio and text configuration from a loaded CLAP model into a ClapConfig object', 'run the CLAP checkpoint conversion script via argparse with checkpoint path and output folder', 'create a ClapFeatureExtractor instance with custom mel filter bank parameters for audio feature extraction', 'build log-mel spectrogram features from raw audio waveforms using STFT and mel-filter banks', 'extract fbank features from a numpy audio waveform using the Hann window and mel filter configuration', 'apply random mel fusion to combine three random crops and a downsampled mel spectrogram for long audio', 'featurize raw speech audio into batched mel spectrogram inputs with truncation and padding handling', 'run the ClapModel to compute audio-text similarity scores with contrastive loss', 'get normalized text embeddings from the ClapModel using input_ids and attention_mask', 'get normalized audio embeddings from the ClapModel using mel spectrogram input_features', 'build a ClapTextModel with projection layer for text embedding generation', 'build a ClapAudioModel with Swin Transformer encoder for audio feature extraction']
```

Usage

```
{'create_clap_feature_extractor': 'create a ClapFeatureExtractor instance with custom mel filter bank parameters for audio feature extraction', 'build_mel_spectrogram_features': 'build log-mel spectrogram features from raw audio waveforms using STFT and mel-filter banks', 'extract_fbank_features': 'extract fbank features from a numpy audio waveform using the Hann window and mel filter configuration', 'random_mel_fusion': 'apply random mel fusion to combine three random crops and a downsampled mel spectrogram for long audio', 'featurize_raw_audio': 'featurize raw speech audio into batched mel spectrogram inputs with truncation and padding handling'}
```

## File: huggingface_transformers/src/transformers/models/clap/modeling_clap.py

Prompts

```
['convert a CLAP checkpoint from laion to HuggingFace transformers format using CLI arguments', 'initialize a CLAP model from a checkpoint path with a specified model type and fusion option', 'rename state dict keys from original CLAP format to HuggingFace transformers naming convention', 'extract audio and text configuration from a loaded CLAP model into a ClapConfig object', 'run the CLAP checkpoint conversion script via argparse with checkpoint path and output folder', 'create a ClapFeatureExtractor instance with custom mel filter bank parameters for audio feature extraction', 'build log-mel spectrogram features from raw audio waveforms using STFT and mel-filter banks', 'extract fbank features from a numpy audio waveform using the Hann window and mel filter configuration', 'apply random mel fusion to combine three random crops and a downsampled mel spectrogram for long audio', 'featurize raw speech audio into batched mel spectrogram inputs with truncation and padding handling', 'run the ClapModel to compute audio-text similarity scores with contrastive loss', 'get normalized text embeddings from the ClapModel using input_ids and attention_mask', 'get normalized audio embeddings from the ClapModel using mel spectrogram input_features', 'build a ClapTextModel with projection layer for text embedding generation', 'build a ClapAudioModel with Swin Transformer encoder for audio feature extraction']
```

Usage

```
{'run_clap_model': 'run the ClapModel to compute audio-text similarity scores with contrastive loss', 'get_text_features': 'get normalized text embeddings from the ClapModel using input_ids and attention_mask', 'get_audio_features': 'get normalized audio embeddings from the ClapModel using mel spectrogram input_features', 'build_clap_text_model': 'build a ClapTextModel with projection layer for text embedding generation', 'build_clap_audio_model': 'build a ClapAudioModel with Swin Transformer encoder for audio feature extraction'}
```

