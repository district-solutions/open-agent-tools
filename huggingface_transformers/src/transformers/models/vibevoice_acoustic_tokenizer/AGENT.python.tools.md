# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/vibevoice_acoustic_tokenizer/configuration_vibevoice_acoustic_tokenizer.py

Prompts

```
['create a VibeVoiceAcousticTokenizerConfig instance with default channels, hidden_size, and downsampling_ratios', 'build a VibeVoiceAcousticTokenizerEncoderConfig instance inheriting from the main tokenizer config', 'build a VibeVoiceAcousticTokenizerDecoderConfig instance with reversed depths and upsampling_ratios', 'test the hop_length property that computes the product of downsampling_ratios as an integer', 'review the decoder_config property that returns a decoder config with reversed depths', 'convert a VibeVoice model checkpoint to HuggingFace format using the convert_checkpoint function', 'convert state dict keys from original VibeVoice format to HuggingFace-compatible format', 'map old checkpoint key to new HF key using regex patterns with index shifting', 'create a VibeVoiceAcousticTokenizerConfig from JSON model configuration', 'build a VibeVoiceAcousticTokenizerFeatureExtractor with audio processing parameters', 'build a VibeVoiceAcousticTokenizerModel that encodes audio waveforms into latent representations and decodes them back to audio', 'build a VibeVoiceAcousticTokenizerEncoderModel that converts raw audio waveforms into continuous latent representations using causal convolutions', 'build a VibeVoiceAcousticTokenizerDecoderModel that reconstructs audio waveforms from continuous latent representations using causal transposed convolutions', 'build a VibeVoiceAcousticTokenizerCausalConv1d layer with streaming cache support for causal 1D convolution on time-series data', 'build a VibeVoiceAcousticTokenizerCausalConvTranspose1d layer with streaming cache support for causal transposed 1D convolution upsampling']
```

Usage

```
{'create_VibeVoiceAcousticTokenizerConfig': 'create a VibeVoiceAcousticTokenizerConfig instance with default channels, hidden_size, and downsampling_ratios', 'build_VibeVoiceAcousticTokenizerEncoderConfig': 'build a VibeVoiceAcousticTokenizerEncoderConfig instance inheriting from the main tokenizer config', 'build_VibeVoiceAcousticTokenizerDecoderConfig': 'build a VibeVoiceAcousticTokenizerDecoderConfig instance with reversed depths and upsampling_ratios', 'test_hop_length_property': 'test the hop_length property that computes the product of downsampling_ratios as an integer', 'review_decoder_config_property': 'review the decoder_config property that returns a decoder config with reversed depths'}
```

## File: huggingface_transformers/src/transformers/models/vibevoice_acoustic_tokenizer/convert_vibevoice_acoustic_tokenizer_to_hf.py

Prompts

```
['create a VibeVoiceAcousticTokenizerConfig instance with default channels, hidden_size, and downsampling_ratios', 'build a VibeVoiceAcousticTokenizerEncoderConfig instance inheriting from the main tokenizer config', 'build a VibeVoiceAcousticTokenizerDecoderConfig instance with reversed depths and upsampling_ratios', 'test the hop_length property that computes the product of downsampling_ratios as an integer', 'review the decoder_config property that returns a decoder config with reversed depths', 'convert a VibeVoice model checkpoint to HuggingFace format using the convert_checkpoint function', 'convert state dict keys from original VibeVoice format to HuggingFace-compatible format', 'map old checkpoint key to new HF key using regex patterns with index shifting', 'create a VibeVoiceAcousticTokenizerConfig from JSON model configuration', 'build a VibeVoiceAcousticTokenizerFeatureExtractor with audio processing parameters', 'build a VibeVoiceAcousticTokenizerModel that encodes audio waveforms into latent representations and decodes them back to audio', 'build a VibeVoiceAcousticTokenizerEncoderModel that converts raw audio waveforms into continuous latent representations using causal convolutions', 'build a VibeVoiceAcousticTokenizerDecoderModel that reconstructs audio waveforms from continuous latent representations using causal transposed convolutions', 'build a VibeVoiceAcousticTokenizerCausalConv1d layer with streaming cache support for causal 1D convolution on time-series data', 'build a VibeVoiceAcousticTokenizerCausalConvTranspose1d layer with streaming cache support for causal transposed 1D convolution upsampling']
```

Usage

```
{'convert_checkpoint_vibevoice': 'convert a VibeVoice model checkpoint to HuggingFace format using the convert_checkpoint function', 'convert_state_dict_keys': 'convert state dict keys from original VibeVoice format to HuggingFace-compatible format', 'map_old_key_to_new_pattern': 'map old checkpoint key to new HF key using regex patterns with index shifting', 'create_acoustic_tokenizer_config': 'create a VibeVoiceAcousticTokenizerConfig from JSON model configuration', 'build_feature_extractor': 'build a VibeVoiceAcousticTokenizerFeatureExtractor with audio processing parameters'}
```

## File: huggingface_transformers/src/transformers/models/vibevoice_acoustic_tokenizer/modeling_vibevoice_acoustic_tokenizer.py

Prompts

```
['create a VibeVoiceAcousticTokenizerConfig instance with default channels, hidden_size, and downsampling_ratios', 'build a VibeVoiceAcousticTokenizerEncoderConfig instance inheriting from the main tokenizer config', 'build a VibeVoiceAcousticTokenizerDecoderConfig instance with reversed depths and upsampling_ratios', 'test the hop_length property that computes the product of downsampling_ratios as an integer', 'review the decoder_config property that returns a decoder config with reversed depths', 'convert a VibeVoice model checkpoint to HuggingFace format using the convert_checkpoint function', 'convert state dict keys from original VibeVoice format to HuggingFace-compatible format', 'map old checkpoint key to new HF key using regex patterns with index shifting', 'create a VibeVoiceAcousticTokenizerConfig from JSON model configuration', 'build a VibeVoiceAcousticTokenizerFeatureExtractor with audio processing parameters', 'build a VibeVoiceAcousticTokenizerModel that encodes audio waveforms into latent representations and decodes them back to audio', 'build a VibeVoiceAcousticTokenizerEncoderModel that converts raw audio waveforms into continuous latent representations using causal convolutions', 'build a VibeVoiceAcousticTokenizerDecoderModel that reconstructs audio waveforms from continuous latent representations using causal transposed convolutions', 'build a VibeVoiceAcousticTokenizerCausalConv1d layer with streaming cache support for causal 1D convolution on time-series data', 'build a VibeVoiceAcousticTokenizerCausalConvTranspose1d layer with streaming cache support for causal transposed 1D convolution upsampling']
```

Usage

```
{'build_vibevoice_acoustic_tokenizer_model': 'build a VibeVoiceAcousticTokenizerModel that encodes audio waveforms into latent representations and decodes them back to audio', 'build_vibevoice_encoder_model': 'build a VibeVoiceAcousticTokenizerEncoderModel that converts raw audio waveforms into continuous latent representations using causal convolutions', 'build_vibevoice_decoder_model': 'build a VibeVoiceAcousticTokenizerDecoderModel that reconstructs audio waveforms from continuous latent representations using causal transposed convolutions', 'build_causal_conv1d': 'build a VibeVoiceAcousticTokenizerCausalConv1d layer with streaming cache support for causal 1D convolution on time-series data', 'build_causal_conv_transpose1d': 'build a VibeVoiceAcousticTokenizerCausalConvTranspose1d layer with streaming cache support for causal transposed 1D convolution upsampling'}
```

## File: huggingface_transformers/src/transformers/models/vibevoice_acoustic_tokenizer/modular_vibevoice_acoustic_tokenizer.py

Prompts

```
['create a VibeVoiceAcousticTokenizerConfig instance with default channels, hidden_size, and downsampling_ratios', 'build a VibeVoiceAcousticTokenizerEncoderConfig instance inheriting from the main tokenizer config', 'build a VibeVoiceAcousticTokenizerDecoderConfig instance with reversed depths and upsampling_ratios', 'test the hop_length property that computes the product of downsampling_ratios as an integer', 'review the decoder_config property that returns a decoder config with reversed depths', 'convert a VibeVoice model checkpoint to HuggingFace format using the convert_checkpoint function', 'convert state dict keys from original VibeVoice format to HuggingFace-compatible format', 'map old checkpoint key to new HF key using regex patterns with index shifting', 'create a VibeVoiceAcousticTokenizerConfig from JSON model configuration', 'build a VibeVoiceAcousticTokenizerFeatureExtractor with audio processing parameters', 'build a VibeVoiceAcousticTokenizerModel that encodes audio waveforms into latent representations and decodes them back to audio', 'build a VibeVoiceAcousticTokenizerEncoderModel that converts raw audio waveforms into continuous latent representations using causal convolutions', 'build a VibeVoiceAcousticTokenizerDecoderModel that reconstructs audio waveforms from continuous latent representations using causal transposed convolutions', 'build a VibeVoiceAcousticTokenizerCausalConv1d layer with streaming cache support for causal 1D convolution on time-series data', 'build a VibeVoiceAcousticTokenizerCausalConvTranspose1d layer with streaming cache support for causal transposed 1D convolution upsampling']
```

Usage

```
{'build_vibevoice_acoustic_tokenizer_model': 'build a VibeVoiceAcousticTokenizerModel that encodes audio waveforms into latent representations and decodes them back to audio', 'build_vibevoice_encoder_model': 'build a VibeVoiceAcousticTokenizerEncoderModel that converts raw audio waveforms into continuous latent representations using causal convolutions', 'build_vibevoice_decoder_model': 'build a VibeVoiceAcousticTokenizerDecoderModel that reconstructs audio waveforms from continuous latent representations using causal transposed convolutions', 'build_causal_conv1d': 'build a VibeVoiceAcousticTokenizerCausalConv1d layer with streaming cache support for causal 1D convolution on time-series data', 'build_causal_conv_transpose1d': 'build a VibeVoiceAcousticTokenizerCausalConvTranspose1d layer with streaming cache support for causal transposed 1D convolution upsampling'}
```

