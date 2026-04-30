# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/speech_to_text/test_feature_extraction_speech_to_text.py

Prompts

```
['test the Speech2TextFeatureExtractor call method with batched and unbatched numpy inputs', 'test the Speech2TextFeatureExtractor dither parameter by comparing features with and without dithering', 'test the Speech2TextFeatureExtractor cepstral mean and variance normalization with different padding modes', 'test saving and loading Speech2TextFeatureExtractor to and from pretrained directories and JSON files', 'test the Speech2TextFeatureExtractor integration with real audio samples from librispeech dataset', 'test the Speech2TextModel forward pass with input features and decoder input ids', 'test the Speech2TextModel decoder with past key values for large inputs', 'test the Speech2TextModel encoder and decoder standalone save and load', 'test the Speech2TextModel attention outputs including self, decoder, and cross attentions', 'test Speech2TextForConditionalGeneration generation with fp16 precision', 'test the Speech2TextProcessor save and load pretrained methods with default tokenizer and feature extractor', 'test the Speech2TextProcessor save and load pretrained methods with additional tokenizer and feature extractor kwargs', 'test the Speech2TextProcessor processes raw audio input identically to the standalone feature extractor', 'test the Speech2TextProcessor encodes text input identically to the standalone tokenizer', 'test the Speech2TextProcessor batch decodes predicted token ids identically to the standalone tokenizer']
```

Usage

```
{'test_feature_extraction_call': 'test the Speech2TextFeatureExtractor call method with batched and unbatched numpy inputs', 'test_feature_extraction_dither': 'test the Speech2TextFeatureExtractor dither parameter by comparing features with and without dithering', 'test_cepstral_mean_normalization': 'test the Speech2TextFeatureExtractor cepstral mean and variance normalization with different padding modes', 'test_feature_extraction_save_load': 'test saving and loading Speech2TextFeatureExtractor to and from pretrained directories and JSON files', 'test_feature_extraction_integration': 'test the Speech2TextFeatureExtractor integration with real audio samples from librispeech dataset'}
```

## File: huggingface_transformers/tests/models/speech_to_text/test_modeling_speech_to_text.py

Prompts

```
['test the Speech2TextFeatureExtractor call method with batched and unbatched numpy inputs', 'test the Speech2TextFeatureExtractor dither parameter by comparing features with and without dithering', 'test the Speech2TextFeatureExtractor cepstral mean and variance normalization with different padding modes', 'test saving and loading Speech2TextFeatureExtractor to and from pretrained directories and JSON files', 'test the Speech2TextFeatureExtractor integration with real audio samples from librispeech dataset', 'test the Speech2TextModel forward pass with input features and decoder input ids', 'test the Speech2TextModel decoder with past key values for large inputs', 'test the Speech2TextModel encoder and decoder standalone save and load', 'test the Speech2TextModel attention outputs including self, decoder, and cross attentions', 'test Speech2TextForConditionalGeneration generation with fp16 precision', 'test the Speech2TextProcessor save and load pretrained methods with default tokenizer and feature extractor', 'test the Speech2TextProcessor save and load pretrained methods with additional tokenizer and feature extractor kwargs', 'test the Speech2TextProcessor processes raw audio input identically to the standalone feature extractor', 'test the Speech2TextProcessor encodes text input identically to the standalone tokenizer', 'test the Speech2TextProcessor batch decodes predicted token ids identically to the standalone tokenizer']
```

Usage

```
{'test_Speech2TextModel_forward': 'test the Speech2TextModel forward pass with input features and decoder input ids', 'test_Speech2TextModel_decoder_past': 'test the Speech2TextModel decoder with past key values for large inputs', 'test_Speech2TextModel_encoder_decoder': 'test the Speech2TextModel encoder and decoder standalone save and load', 'test_Speech2TextModel_attention': 'test the Speech2TextModel attention outputs including self, decoder, and cross attentions', 'test_Speech2TextModel_generate_fp16': 'test Speech2TextForConditionalGeneration generation with fp16 precision'}
```

## File: huggingface_transformers/tests/models/speech_to_text/test_processing_speech_to_text.py

Prompts

```
['test the Speech2TextFeatureExtractor call method with batched and unbatched numpy inputs', 'test the Speech2TextFeatureExtractor dither parameter by comparing features with and without dithering', 'test the Speech2TextFeatureExtractor cepstral mean and variance normalization with different padding modes', 'test saving and loading Speech2TextFeatureExtractor to and from pretrained directories and JSON files', 'test the Speech2TextFeatureExtractor integration with real audio samples from librispeech dataset', 'test the Speech2TextModel forward pass with input features and decoder input ids', 'test the Speech2TextModel decoder with past key values for large inputs', 'test the Speech2TextModel encoder and decoder standalone save and load', 'test the Speech2TextModel attention outputs including self, decoder, and cross attentions', 'test Speech2TextForConditionalGeneration generation with fp16 precision', 'test the Speech2TextProcessor save and load pretrained methods with default tokenizer and feature extractor', 'test the Speech2TextProcessor save and load pretrained methods with additional tokenizer and feature extractor kwargs', 'test the Speech2TextProcessor processes raw audio input identically to the standalone feature extractor', 'test the Speech2TextProcessor encodes text input identically to the standalone tokenizer', 'test the Speech2TextProcessor batch decodes predicted token ids identically to the standalone tokenizer']
```

Usage

```
{'test_save_load_pretrained_default': 'test the Speech2TextProcessor save and load pretrained methods with default tokenizer and feature extractor', 'test_save_load_pretrained_additional_features': 'test the Speech2TextProcessor save and load pretrained methods with additional tokenizer and feature extractor kwargs', 'test_feature_extractor': 'test the Speech2TextProcessor processes raw audio input identically to the standalone feature extractor', 'test_tokenizer': 'test the Speech2TextProcessor encodes text input identically to the standalone tokenizer', 'test_tokenizer_decode': 'test the Speech2TextProcessor batch decodes predicted token ids identically to the standalone tokenizer'}
```

