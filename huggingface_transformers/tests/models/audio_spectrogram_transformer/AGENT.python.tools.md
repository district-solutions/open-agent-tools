# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/audio_spectrogram_transformer/test_feature_extraction_audio_spectrogram_transformer.py

Prompts

```
['test ASTFeatureExtractor with single and batched speech inputs returning numpy tensors', 'test ASTFeatureExtractor pad method preserves float32 dtype for double precision inputs', 'test ASTFeatureExtractor integration with LibriSpeech dummy dataset and verify expected output values', 'test ASTFeatureExtractor save_pretrained and from_pretrained round-trip preserves configuration', 'test ASTFeatureExtractor falls back to audio_utils when torchaudio is unavailable', 'run the ASTModelTester to generate config and input values for AST model testing', 'test the ASTModel and ASTForAudioClassification classes using the ASTModelTest suite', 'test audio classification inference with a pretrained AST model on sample audio', 'review the prepare_audio function that downloads and loads a sample FLAC audio file', 'review the ASTModelTester get_config method that creates an ASTConfig instance']
```

Usage

```
{'test_ASTFeatureExtractor_call': 'test ASTFeatureExtractor with single and batched speech inputs returning numpy tensors', 'test_ASTFeatureExtractor_padding': 'test ASTFeatureExtractor pad method preserves float32 dtype for double precision inputs', 'test_ASTFeatureExtractor_integration': 'test ASTFeatureExtractor integration with LibriSpeech dummy dataset and verify expected output values', 'test_ASTFeatureExtractor_save_load': 'test ASTFeatureExtractor save_pretrained and from_pretrained round-trip preserves configuration', 'test_ASTFeatureExtractor_without_torchaudio': 'test ASTFeatureExtractor falls back to audio_utils when torchaudio is unavailable'}
```

## File: huggingface_transformers/tests/models/audio_spectrogram_transformer/test_modeling_audio_spectrogram_transformer.py

Prompts

```
['test ASTFeatureExtractor with single and batched speech inputs returning numpy tensors', 'test ASTFeatureExtractor pad method preserves float32 dtype for double precision inputs', 'test ASTFeatureExtractor integration with LibriSpeech dummy dataset and verify expected output values', 'test ASTFeatureExtractor save_pretrained and from_pretrained round-trip preserves configuration', 'test ASTFeatureExtractor falls back to audio_utils when torchaudio is unavailable', 'run the ASTModelTester to generate config and input values for AST model testing', 'test the ASTModel and ASTForAudioClassification classes using the ASTModelTest suite', 'test audio classification inference with a pretrained AST model on sample audio', 'review the prepare_audio function that downloads and loads a sample FLAC audio file', 'review the ASTModelTester get_config method that creates an ASTConfig instance']
```

Usage

```
{'run_ASTModelTester': 'run the ASTModelTester to generate config and input values for AST model testing', 'test_ASTModelTest': 'test the ASTModel and ASTForAudioClassification classes using the ASTModelTest suite', 'test_ASTModelIntegrationTest': 'test audio classification inference with a pretrained AST model on sample audio', 'review_prepare_audio': 'review the prepare_audio function that downloads and loads a sample FLAC audio file', 'review_ASTModelTester_get_config': 'review the ASTModelTester get_config method that creates an ASTConfig instance'}
```

