# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/higgs_audio_v2_tokenizer/configuration_higgs_audio_v2_tokenizer.py

Prompts

```
['create a HiggsAudioV2TokenizerConfig with default parameters for audio tokenization', 'create a HiggsAudioV2TokenizerConfig with custom target_bandwidths, kernel_size, and codebook_size', 'create a HiggsAudioV2TokenizerConfig from a dictionary with acoustic_model_config and semantic_model_config', 'initialize a HiggsAudioV2TokenizerModel from a HiggsAudioV2TokenizerConfig instance', 'access the configuration object from an initialized HiggsAudioV2TokenizerModel', 'convert a HiggsAudioV2Tokenizer model checkpoint from BosonAI to HuggingFace format', 'create a DacFeatureExtractor configured for 24kHz audio with hop length 960 and right padding', 'run the conversion CLI to save or push a HiggsAudioV2Tokenizer model to HuggingFace Hub', 'compute plain weights from weight normalization parameters weight_v and weight_g', 'convert original model checkpoint keys to HuggingFace-compatible key names using regex mappings', 'encode a mono audio waveform into discrete audio codes using HiggsAudioV2TokenizerModel.encode', 'decode discrete audio codes back to a reconstructed audio waveform using HiggsAudioV2TokenizerModel.decode', 'run a full encode then decode pipeline on audio using HiggsAudioV2TokenizerModel.forward', 'extract semantic features from an audio waveform using HiggsAudioV2TokenizerModel._extract_semantic_features', 'quantize audio embeddings into discrete indices using HiggsAudioV2TokenizerResidualVectorQuantization.encode', 'encode audio hidden states using HiggsAudioV2TokenizerVectorQuantization encode method', 'decode audio from embedding indices using HiggsAudioV2TokenizerVectorQuantization decode method']
```

Usage

```
{'create_config_default': 'create a HiggsAudioV2TokenizerConfig with default parameters for audio tokenization', 'create_config_custom': 'create a HiggsAudioV2TokenizerConfig with custom target_bandwidths, kernel_size, and codebook_size', 'create_config_from_dict': 'create a HiggsAudioV2TokenizerConfig from a dictionary with acoustic_model_config and semantic_model_config', 'init_model_from_config': 'initialize a HiggsAudioV2TokenizerModel from a HiggsAudioV2TokenizerConfig instance', 'access_model_config': 'access the configuration object from an initialized HiggsAudioV2TokenizerModel'}
```

## File: huggingface_transformers/src/transformers/models/higgs_audio_v2_tokenizer/convert_higgs_audio_v2_tokenizer_to_hf.py

Prompts

```
['create a HiggsAudioV2TokenizerConfig with default parameters for audio tokenization', 'create a HiggsAudioV2TokenizerConfig with custom target_bandwidths, kernel_size, and codebook_size', 'create a HiggsAudioV2TokenizerConfig from a dictionary with acoustic_model_config and semantic_model_config', 'initialize a HiggsAudioV2TokenizerModel from a HiggsAudioV2TokenizerConfig instance', 'access the configuration object from an initialized HiggsAudioV2TokenizerModel', 'convert a HiggsAudioV2Tokenizer model checkpoint from BosonAI to HuggingFace format', 'create a DacFeatureExtractor configured for 24kHz audio with hop length 960 and right padding', 'run the conversion CLI to save or push a HiggsAudioV2Tokenizer model to HuggingFace Hub', 'compute plain weights from weight normalization parameters weight_v and weight_g', 'convert original model checkpoint keys to HuggingFace-compatible key names using regex mappings', 'encode a mono audio waveform into discrete audio codes using HiggsAudioV2TokenizerModel.encode', 'decode discrete audio codes back to a reconstructed audio waveform using HiggsAudioV2TokenizerModel.decode', 'run a full encode then decode pipeline on audio using HiggsAudioV2TokenizerModel.forward', 'extract semantic features from an audio waveform using HiggsAudioV2TokenizerModel._extract_semantic_features', 'quantize audio embeddings into discrete indices using HiggsAudioV2TokenizerResidualVectorQuantization.encode', 'encode audio hidden states using HiggsAudioV2TokenizerVectorQuantization encode method', 'decode audio from embedding indices using HiggsAudioV2TokenizerVectorQuantization decode method']
```

Usage

```
{'convert_model': 'convert a HiggsAudioV2Tokenizer model checkpoint from BosonAI to HuggingFace format', 'create_feature_extractor': 'create a DacFeatureExtractor configured for 24kHz audio with hop length 960 and right padding', 'run_convert_cli': 'run the conversion CLI to save or push a HiggsAudioV2Tokenizer model to HuggingFace Hub', 'compute_weight_from_weight_norm': 'compute plain weights from weight normalization parameters weight_v and weight_g', 'convert_key': 'convert original model checkpoint keys to HuggingFace-compatible key names using regex mappings'}
```

## File: huggingface_transformers/src/transformers/models/higgs_audio_v2_tokenizer/modeling_higgs_audio_v2_tokenizer.py

Prompts

```
['create a HiggsAudioV2TokenizerConfig with default parameters for audio tokenization', 'create a HiggsAudioV2TokenizerConfig with custom target_bandwidths, kernel_size, and codebook_size', 'create a HiggsAudioV2TokenizerConfig from a dictionary with acoustic_model_config and semantic_model_config', 'initialize a HiggsAudioV2TokenizerModel from a HiggsAudioV2TokenizerConfig instance', 'access the configuration object from an initialized HiggsAudioV2TokenizerModel', 'convert a HiggsAudioV2Tokenizer model checkpoint from BosonAI to HuggingFace format', 'create a DacFeatureExtractor configured for 24kHz audio with hop length 960 and right padding', 'run the conversion CLI to save or push a HiggsAudioV2Tokenizer model to HuggingFace Hub', 'compute plain weights from weight normalization parameters weight_v and weight_g', 'convert original model checkpoint keys to HuggingFace-compatible key names using regex mappings', 'encode a mono audio waveform into discrete audio codes using HiggsAudioV2TokenizerModel.encode', 'decode discrete audio codes back to a reconstructed audio waveform using HiggsAudioV2TokenizerModel.decode', 'run a full encode then decode pipeline on audio using HiggsAudioV2TokenizerModel.forward', 'extract semantic features from an audio waveform using HiggsAudioV2TokenizerModel._extract_semantic_features', 'quantize audio embeddings into discrete indices using HiggsAudioV2TokenizerResidualVectorQuantization.encode', 'encode audio hidden states using HiggsAudioV2TokenizerVectorQuantization encode method', 'decode audio from embedding indices using HiggsAudioV2TokenizerVectorQuantization decode method']
```

Usage

```
{'encode_audio_to_codes': 'encode a mono audio waveform into discrete audio codes using HiggsAudioV2TokenizerModel.encode', 'decode_audio_codes_to_waveform': 'decode discrete audio codes back to a reconstructed audio waveform using HiggsAudioV2TokenizerModel.decode', 'encode_decode_audio_pipeline': 'run a full encode then decode pipeline on audio using HiggsAudioV2TokenizerModel.forward', 'extract_semantic_features': 'extract semantic features from an audio waveform using HiggsAudioV2TokenizerModel._extract_semantic_features', 'quantize_with_residual_vq': 'quantize audio embeddings into discrete indices using HiggsAudioV2TokenizerResidualVectorQuantization.encode'}
```

## File: huggingface_transformers/src/transformers/models/higgs_audio_v2_tokenizer/modular_higgs_audio_v2_tokenizer.py

Prompts

```
['create a HiggsAudioV2TokenizerConfig with default parameters for audio tokenization', 'create a HiggsAudioV2TokenizerConfig with custom target_bandwidths, kernel_size, and codebook_size', 'create a HiggsAudioV2TokenizerConfig from a dictionary with acoustic_model_config and semantic_model_config', 'initialize a HiggsAudioV2TokenizerModel from a HiggsAudioV2TokenizerConfig instance', 'access the configuration object from an initialized HiggsAudioV2TokenizerModel', 'convert a HiggsAudioV2Tokenizer model checkpoint from BosonAI to HuggingFace format', 'create a DacFeatureExtractor configured for 24kHz audio with hop length 960 and right padding', 'run the conversion CLI to save or push a HiggsAudioV2Tokenizer model to HuggingFace Hub', 'compute plain weights from weight normalization parameters weight_v and weight_g', 'convert original model checkpoint keys to HuggingFace-compatible key names using regex mappings', 'encode a mono audio waveform into discrete audio codes using HiggsAudioV2TokenizerModel.encode', 'decode discrete audio codes back to a reconstructed audio waveform using HiggsAudioV2TokenizerModel.decode', 'run a full encode then decode pipeline on audio using HiggsAudioV2TokenizerModel.forward', 'extract semantic features from an audio waveform using HiggsAudioV2TokenizerModel._extract_semantic_features', 'quantize audio embeddings into discrete indices using HiggsAudioV2TokenizerResidualVectorQuantization.encode', 'encode audio hidden states using HiggsAudioV2TokenizerVectorQuantization encode method', 'decode audio from embedding indices using HiggsAudioV2TokenizerVectorQuantization decode method']
```

Usage

```
{'create_config_default': 'create a HiggsAudioV2TokenizerConfig with default parameters for audio tokenization', 'create_config_custom': 'create a HiggsAudioV2TokenizerConfig with custom target_bandwidths, codebook_dim, and sample_rate', 'init_model_from_config': 'initialize a HiggsAudioV2TokenizerModel from a HiggsAudioV2TokenizerConfig instance', 'encode_audio_with_vq': 'encode audio hidden states using HiggsAudioV2TokenizerVectorQuantization encode method', 'decode_audio_with_vq': 'decode audio from embedding indices using HiggsAudioV2TokenizerVectorQuantization decode method', 'extract_semantic_features': 'extract semantic features from audio input using HiggsAudioV2TokenizerModel _extract_semantic_features method'}
```

