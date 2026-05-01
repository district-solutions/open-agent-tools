# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/vibevoice_acoustic_tokenizer/test_feature_extraction_vibevoice_acoustic_tokenizer.py

Prompts

```
['test the VibeVoiceAcousticTokenizerFeatureExtractor feature extraction with torch and numpy inputs', 'test audio normalization with VibeVoiceAcousticTokenizerFeatureExtractor at target_dB_FS=-25', 'test that VibeVoiceAcousticTokenizerFeatureExtractor rejects incorrect sampling rates', 'test that VibeVoiceAcousticTokenizerFeatureExtractor generates correct padding masks', 'create a VibeVoiceAcousticTokenizerFeatureExtractor with custom sampling_rate and normalization settings', 'test the VibeVoiceAcousticTokenizerModel forward pass to verify latent and audio output shapes', 'test the encode method of VibeVoiceAcousticTokenizerModel to produce latent representations from audio input', 'test the decode method of VibeVoiceAcousticTokenizerModel to reconstruct audio from latent representations', 'test the VibeVoiceAcousticTokenizerModel with use_cache enabled to verify padding cache output', 'test the VibeVoiceAcousticTokenizerModel integration with real audio files and compare against expected encoder and decoder outputs']
```

Usage

```
{'test_feature_extraction_call': 'test the VibeVoiceAcousticTokenizerFeatureExtractor feature extraction with torch and numpy inputs', 'test_normalize_audio': 'test audio normalization with VibeVoiceAcousticTokenizerFeatureExtractor at target_dB_FS=-25', 'test_sampling_rate_validation': 'test that VibeVoiceAcousticTokenizerFeatureExtractor rejects incorrect sampling rates', 'test_padding_mask_generation': 'test that VibeVoiceAcousticTokenizerFeatureExtractor generates correct padding masks', 'create_feature_extractor': 'create a VibeVoiceAcousticTokenizerFeatureExtractor with custom sampling_rate and normalization settings'}
```

## File: huggingface_transformers/tests/models/vibevoice_acoustic_tokenizer/test_modeling_vibevoice_acoustic_tokenizer.py

Prompts

```
['test the VibeVoiceAcousticTokenizerFeatureExtractor feature extraction with torch and numpy inputs', 'test audio normalization with VibeVoiceAcousticTokenizerFeatureExtractor at target_dB_FS=-25', 'test that VibeVoiceAcousticTokenizerFeatureExtractor rejects incorrect sampling rates', 'test that VibeVoiceAcousticTokenizerFeatureExtractor generates correct padding masks', 'create a VibeVoiceAcousticTokenizerFeatureExtractor with custom sampling_rate and normalization settings', 'test the VibeVoiceAcousticTokenizerModel forward pass to verify latent and audio output shapes', 'test the encode method of VibeVoiceAcousticTokenizerModel to produce latent representations from audio input', 'test the decode method of VibeVoiceAcousticTokenizerModel to reconstruct audio from latent representations', 'test the VibeVoiceAcousticTokenizerModel with use_cache enabled to verify padding cache output', 'test the VibeVoiceAcousticTokenizerModel integration with real audio files and compare against expected encoder and decoder outputs']
```

Usage

```
{'test_model_forward': 'test the VibeVoiceAcousticTokenizerModel forward pass to verify latent and audio output shapes', 'test_encode_method': 'test the encode method of VibeVoiceAcousticTokenizerModel to produce latent representations from audio input', 'test_decode_method': 'test the decode method of VibeVoiceAcousticTokenizerModel to reconstruct audio from latent representations', 'test_use_cache': 'test the VibeVoiceAcousticTokenizerModel with use_cache enabled to verify padding cache output', 'test_batch_integration': 'test the VibeVoiceAcousticTokenizerModel integration with real audio files and compare against expected encoder and decoder outputs'}
```

