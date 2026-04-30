# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/gemma3n/test_feature_extraction_gemma3n.py

Prompts

```
['create a Gemma3nAudioFeatureExtractor with custom audio processing parameters like sampling rate and mel filters', 'test saving and loading a Gemma3nAudioFeatureExtractor from a temporary directory with JSON serialization', 'test the feature extractor call method with audio inputs, padding, truncation, and numpy array conversion', 'test that audio features with and without dithering produce similar but not identical output', 'test that input_features and input_features_mask have consistent shapes across different audio lengths', 'test the Gemma3nAudioEncoder forward pass and feature extractor output against golden values', 'test generating text with StaticCache and verify cache shapes match expected dimensions', 'test RoPE scaling frequency properties for default, linear, dynamic, and yarn scaling types', 'test the Gemma3nVision2TextModel generate method with pixel values and text inputs', 'test the Gemma3nForConditionalGeneration integration with images, audio, and sliding window generation']
```

Usage

```
{'create_feature_extractor': 'create a Gemma3nAudioFeatureExtractor with custom audio processing parameters like sampling rate and mel filters', 'test_feat_extract_save_load': 'test saving and loading a Gemma3nAudioFeatureExtractor from a temporary directory with JSON serialization', 'test_feature_extraction_call': 'test the feature extractor call method with audio inputs, padding, truncation, and numpy array conversion', 'test_dither_audio_features': 'test that audio features with and without dithering produce similar but not identical output', 'test_audio_features_mask_consistency': 'test that input_features and input_features_mask have consistent shapes across different audio lengths'}
```

## File: huggingface_transformers/tests/models/gemma3n/test_modeling_gemma3n.py

Prompts

```
['create a Gemma3nAudioFeatureExtractor with custom audio processing parameters like sampling rate and mel filters', 'test saving and loading a Gemma3nAudioFeatureExtractor from a temporary directory with JSON serialization', 'test the feature extractor call method with audio inputs, padding, truncation, and numpy array conversion', 'test that audio features with and without dithering produce similar but not identical output', 'test that input_features and input_features_mask have consistent shapes across different audio lengths', 'test the Gemma3nAudioEncoder forward pass and feature extractor output against golden values', 'test generating text with StaticCache and verify cache shapes match expected dimensions', 'test RoPE scaling frequency properties for default, linear, dynamic, and yarn scaling types', 'test the Gemma3nVision2TextModel generate method with pixel values and text inputs', 'test the Gemma3nForConditionalGeneration integration with images, audio, and sliding window generation']
```

Usage

```
{'test_audio_encoder': 'test the Gemma3nAudioEncoder forward pass and feature extractor output against golden values', 'test_generate_static_cache': 'test generating text with StaticCache and verify cache shapes match expected dimensions', 'test_rope_scaling_frequencies': 'test RoPE scaling frequency properties for default, linear, dynamic, and yarn scaling types', 'test_vision2text_generate': 'test the Gemma3nVision2TextModel generate method with pixel values and text inputs', 'test_model_integration': 'test the Gemma3nForConditionalGeneration integration with images, audio, and sliding window generation'}
```

