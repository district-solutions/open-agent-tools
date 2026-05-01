# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/gemma3n/test_feature_extraction_gemma3n.py

Prompts

```
['create a Gemma3nAudioFeatureExtractor with custom audio processing parameters like sampling rate and mel filters', 'test saving and loading a Gemma3nAudioFeatureExtractor from a temporary directory with JSON serialization', 'test the feature extractor call method with audio inputs, padding, truncation, and numpy array conversion', 'test that audio features with and without dithering produce similar but not identical output', 'test that input_features and input_features_mask have consistent shapes across different audio lengths', 'test the Gemma3nAudioEncoder forward pass and feature extractor output against golden values', 'test generating text with StaticCache and verify cache shapes match expected dimensions', 'test RoPE scaling frequency properties for default, linear, dynamic, and yarn scaling types', 'test the Gemma3nVision2TextModel generate method with pixel values and text inputs', 'test the Gemma3nForConditionalGeneration integration with images, audio, and sliding window generation', 'test the Gemma3nProcessorTest class to verify omni-modal processor functionality with text audio and image inputs', 'test the audio feature extractor by passing raw speech floats through the Gemma3nProcessor and comparing outputs', 'review the prepare_image_inputs method that overrides the parent class to always use nested image inputs', 'review the _setup_test_attributes classmethod that configures the image token from the processor boi_token', 'summarize the Gemma3nProcessorTest class which tests the omni-modal Gemma3nProcessor with torch torchaudio vision and sentencepiece dependencies']
```

Usage

```
{'create_feature_extractor': 'create a Gemma3nAudioFeatureExtractor with custom audio processing parameters like sampling rate and mel filters', 'test_feat_extract_save_load': 'test saving and loading a Gemma3nAudioFeatureExtractor from a temporary directory with JSON serialization', 'test_feature_extraction_call': 'test the feature extractor call method with audio inputs, padding, truncation, and numpy array conversion', 'test_dither_audio_features': 'test that audio features with and without dithering produce similar but not identical output', 'test_audio_features_mask_consistency': 'test that input_features and input_features_mask have consistent shapes across different audio lengths'}
```

## File: huggingface_transformers/tests/models/gemma3n/test_modeling_gemma3n.py

Prompts

```
['create a Gemma3nAudioFeatureExtractor with custom audio processing parameters like sampling rate and mel filters', 'test saving and loading a Gemma3nAudioFeatureExtractor from a temporary directory with JSON serialization', 'test the feature extractor call method with audio inputs, padding, truncation, and numpy array conversion', 'test that audio features with and without dithering produce similar but not identical output', 'test that input_features and input_features_mask have consistent shapes across different audio lengths', 'test the Gemma3nAudioEncoder forward pass and feature extractor output against golden values', 'test generating text with StaticCache and verify cache shapes match expected dimensions', 'test RoPE scaling frequency properties for default, linear, dynamic, and yarn scaling types', 'test the Gemma3nVision2TextModel generate method with pixel values and text inputs', 'test the Gemma3nForConditionalGeneration integration with images, audio, and sliding window generation', 'test the Gemma3nProcessorTest class to verify omni-modal processor functionality with text audio and image inputs', 'test the audio feature extractor by passing raw speech floats through the Gemma3nProcessor and comparing outputs', 'review the prepare_image_inputs method that overrides the parent class to always use nested image inputs', 'review the _setup_test_attributes classmethod that configures the image token from the processor boi_token', 'summarize the Gemma3nProcessorTest class which tests the omni-modal Gemma3nProcessor with torch torchaudio vision and sentencepiece dependencies']
```

Usage

```
{'test_audio_encoder': 'test the Gemma3nAudioEncoder forward pass and feature extractor output against golden values', 'test_generate_static_cache': 'test generating text with StaticCache and verify cache shapes match expected dimensions', 'test_rope_scaling_frequencies': 'test RoPE scaling frequency properties for default, linear, dynamic, and yarn scaling types', 'test_vision2text_generate': 'test the Gemma3nVision2TextModel generate method with pixel values and text inputs', 'test_model_integration': 'test the Gemma3nForConditionalGeneration integration with images, audio, and sliding window generation'}
```

## File: huggingface_transformers/tests/models/gemma3n/test_processing_gemma3n.py

Prompts

```
['create a Gemma3nAudioFeatureExtractor with custom audio processing parameters like sampling rate and mel filters', 'test saving and loading a Gemma3nAudioFeatureExtractor from a temporary directory with JSON serialization', 'test the feature extractor call method with audio inputs, padding, truncation, and numpy array conversion', 'test that audio features with and without dithering produce similar but not identical output', 'test that input_features and input_features_mask have consistent shapes across different audio lengths', 'test the Gemma3nAudioEncoder forward pass and feature extractor output against golden values', 'test generating text with StaticCache and verify cache shapes match expected dimensions', 'test RoPE scaling frequency properties for default, linear, dynamic, and yarn scaling types', 'test the Gemma3nVision2TextModel generate method with pixel values and text inputs', 'test the Gemma3nForConditionalGeneration integration with images, audio, and sliding window generation', 'test the Gemma3nProcessorTest class to verify omni-modal processor functionality with text audio and image inputs', 'test the audio feature extractor by passing raw speech floats through the Gemma3nProcessor and comparing outputs', 'review the prepare_image_inputs method that overrides the parent class to always use nested image inputs', 'review the _setup_test_attributes classmethod that configures the image token from the processor boi_token', 'summarize the Gemma3nProcessorTest class which tests the omni-modal Gemma3nProcessor with torch torchaudio vision and sentencepiece dependencies']
```

Usage

```
{'test_Gemma3nProcessorTest': 'test the Gemma3nProcessorTest class to verify omni-modal processor functionality with text audio and image inputs', 'test_audio_feature_extractor': 'test the audio feature extractor by passing raw speech floats through the Gemma3nProcessor and comparing outputs', 'review_Gemma3nProcessorTest_prepare_image_inputs': 'review the prepare_image_inputs method that overrides the parent class to always use nested image inputs', 'review_Gemma3nProcessorTest_setup_test_attributes': 'review the _setup_test_attributes classmethod that configures the image token from the processor boi_token', 'summarize_Gemma3nProcessorTest': 'summarize the Gemma3nProcessorTest class which tests the omni-modal Gemma3nProcessor with torch torchaudio vision and sentencepiece dependencies'}
```

