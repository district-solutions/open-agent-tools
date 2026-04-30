# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/speecht5/test_feature_extraction_speecht5.py

Prompts

```
['create a SpeechT5FeatureExtractor with custom mel-bins, hop-length, and normalization settings', 'test the SpeechT5FeatureExtractor call method with batched and unbatched numpy audio inputs', 'test zero-mean unit-variance normalization on padded speech inputs with numpy tensors', 'test padding and truncation behavior with max_length and longest padding strategies', 'test attention mask generation for padded and truncated target speech features', 'test the SpeechT5Model forward pass with input values and attention masks', 'test the SpeechT5ForSpeechToText model for automatic speech recognition generation', 'test the SpeechT5ForTextToSpeech model for text-to-speech synthesis with speaker embeddings', 'test the SpeechT5ForSpeechToSpeech model for voice conversion with speaker embeddings', 'test the SpeechT5HifiGan vocoder model for waveform generation from spectrograms', 'test SpeechT5 encoder, decoder, and cross attention output shapes and layer counts', 'test SpeechT5 encoder and decoder hidden states output dimensions', 'test the SpeechT5Processor class save and load pretrained model with default tokenizer and feature extractor', 'test the SpeechT5Processor class save and load pretrained model with additional tokenizer and feature extractor kwargs', 'test the SpeechT5Processor processes raw audio input through the feature extractor and returns matching tensor keys', 'test the SpeechT5Processor encodes text input through the tokenizer and returns matching tokenized keys', 'test the SpeechT5Processor batch decodes predicted token ids through the tokenizer', 'test the SpeechT5TokenizerTest class for tokenizer normalization, vocab, encoding and decoding', 'build a SpeechT5Tokenizer from a SentencePiece fixture with custom mask and special tokens', 'test the tokenizer normalization of numeric and monetary values into spelled-out text', 'test the full tokenizer encode, decode, and token-to-id conversion round-trip', 'test the tokenizer integration against the microsoft/speecht5_asr pretrained model']
```

Usage

```
{'create_feature_extractor': 'create a SpeechT5FeatureExtractor with custom mel-bins, hop-length, and normalization settings', 'test_feature_extraction_call': 'test the SpeechT5FeatureExtractor call method with batched and unbatched numpy audio inputs', 'test_normalization_zero_mean_unit_variance': 'test zero-mean unit-variance normalization on padded speech inputs with numpy tensors', 'test_padding_with_truncation': 'test padding and truncation behavior with max_length and longest padding strategies', 'test_attention_mask_generation': 'test attention mask generation for padded and truncated target speech features'}
```

## File: huggingface_transformers/tests/models/speecht5/test_modeling_speecht5.py

Prompts

```
['create a SpeechT5FeatureExtractor with custom mel-bins, hop-length, and normalization settings', 'test the SpeechT5FeatureExtractor call method with batched and unbatched numpy audio inputs', 'test zero-mean unit-variance normalization on padded speech inputs with numpy tensors', 'test padding and truncation behavior with max_length and longest padding strategies', 'test attention mask generation for padded and truncated target speech features', 'test the SpeechT5Model forward pass with input values and attention masks', 'test the SpeechT5ForSpeechToText model for automatic speech recognition generation', 'test the SpeechT5ForTextToSpeech model for text-to-speech synthesis with speaker embeddings', 'test the SpeechT5ForSpeechToSpeech model for voice conversion with speaker embeddings', 'test the SpeechT5HifiGan vocoder model for waveform generation from spectrograms', 'test SpeechT5 encoder, decoder, and cross attention output shapes and layer counts', 'test SpeechT5 encoder and decoder hidden states output dimensions', 'test the SpeechT5Processor class save and load pretrained model with default tokenizer and feature extractor', 'test the SpeechT5Processor class save and load pretrained model with additional tokenizer and feature extractor kwargs', 'test the SpeechT5Processor processes raw audio input through the feature extractor and returns matching tensor keys', 'test the SpeechT5Processor encodes text input through the tokenizer and returns matching tokenized keys', 'test the SpeechT5Processor batch decodes predicted token ids through the tokenizer', 'test the SpeechT5TokenizerTest class for tokenizer normalization, vocab, encoding and decoding', 'build a SpeechT5Tokenizer from a SentencePiece fixture with custom mask and special tokens', 'test the tokenizer normalization of numeric and monetary values into spelled-out text', 'test the full tokenizer encode, decode, and token-to-id conversion round-trip', 'test the tokenizer integration against the microsoft/speecht5_asr pretrained model']
```

Usage

```
{'test_SpeechT5Model_forward': 'test the SpeechT5Model forward pass with input values and attention masks', 'test_SpeechT5ForSpeechToText_generate': 'test the SpeechT5ForSpeechToText model for automatic speech recognition generation', 'test_SpeechT5ForTextToSpeech_generate': 'test the SpeechT5ForTextToSpeech model for text-to-speech synthesis with speaker embeddings', 'test_SpeechT5ForSpeechToSpeech_generation': 'test the SpeechT5ForSpeechToSpeech model for voice conversion with speaker embeddings', 'test_SpeechT5HifiGan_vocoder': 'test the SpeechT5HifiGan vocoder model for waveform generation from spectrograms', 'test_SpeechT5_attention_outputs': 'test SpeechT5 encoder, decoder, and cross attention output shapes and layer counts', 'test_SpeechT5_hidden_states': 'test SpeechT5 encoder and decoder hidden states output dimensions'}
```

## File: huggingface_transformers/tests/models/speecht5/test_processing_speecht5.py

Prompts

```
['create a SpeechT5FeatureExtractor with custom mel-bins, hop-length, and normalization settings', 'test the SpeechT5FeatureExtractor call method with batched and unbatched numpy audio inputs', 'test zero-mean unit-variance normalization on padded speech inputs with numpy tensors', 'test padding and truncation behavior with max_length and longest padding strategies', 'test attention mask generation for padded and truncated target speech features', 'test the SpeechT5Model forward pass with input values and attention masks', 'test the SpeechT5ForSpeechToText model for automatic speech recognition generation', 'test the SpeechT5ForTextToSpeech model for text-to-speech synthesis with speaker embeddings', 'test the SpeechT5ForSpeechToSpeech model for voice conversion with speaker embeddings', 'test the SpeechT5HifiGan vocoder model for waveform generation from spectrograms', 'test SpeechT5 encoder, decoder, and cross attention output shapes and layer counts', 'test SpeechT5 encoder and decoder hidden states output dimensions', 'test the SpeechT5Processor class save and load pretrained model with default tokenizer and feature extractor', 'test the SpeechT5Processor class save and load pretrained model with additional tokenizer and feature extractor kwargs', 'test the SpeechT5Processor processes raw audio input through the feature extractor and returns matching tensor keys', 'test the SpeechT5Processor encodes text input through the tokenizer and returns matching tokenized keys', 'test the SpeechT5Processor batch decodes predicted token ids through the tokenizer', 'test the SpeechT5TokenizerTest class for tokenizer normalization, vocab, encoding and decoding', 'build a SpeechT5Tokenizer from a SentencePiece fixture with custom mask and special tokens', 'test the tokenizer normalization of numeric and monetary values into spelled-out text', 'test the full tokenizer encode, decode, and token-to-id conversion round-trip', 'test the tokenizer integration against the microsoft/speecht5_asr pretrained model']
```

Usage

```
{'test_SpeechT5Processor_save_load_pretrained_default': 'test the SpeechT5Processor class save and load pretrained model with default tokenizer and feature extractor', 'test_SpeechT5Processor_save_load_pretrained_additional_features': 'test the SpeechT5Processor class save and load pretrained model with additional tokenizer and feature extractor kwargs', 'test_SpeechT5Processor_feature_extractor': 'test the SpeechT5Processor processes raw audio input through the feature extractor and returns matching tensor keys', 'test_SpeechT5Processor_tokenizer': 'test the SpeechT5Processor encodes text input through the tokenizer and returns matching tokenized keys', 'test_SpeechT5Processor_tokenizer_decode': 'test the SpeechT5Processor batch decodes predicted token ids through the tokenizer'}
```

## File: huggingface_transformers/tests/models/speecht5/test_tokenization_speecht5.py

Prompts

```
['create a SpeechT5FeatureExtractor with custom mel-bins, hop-length, and normalization settings', 'test the SpeechT5FeatureExtractor call method with batched and unbatched numpy audio inputs', 'test zero-mean unit-variance normalization on padded speech inputs with numpy tensors', 'test padding and truncation behavior with max_length and longest padding strategies', 'test attention mask generation for padded and truncated target speech features', 'test the SpeechT5Model forward pass with input values and attention masks', 'test the SpeechT5ForSpeechToText model for automatic speech recognition generation', 'test the SpeechT5ForTextToSpeech model for text-to-speech synthesis with speaker embeddings', 'test the SpeechT5ForSpeechToSpeech model for voice conversion with speaker embeddings', 'test the SpeechT5HifiGan vocoder model for waveform generation from spectrograms', 'test SpeechT5 encoder, decoder, and cross attention output shapes and layer counts', 'test SpeechT5 encoder and decoder hidden states output dimensions', 'test the SpeechT5Processor class save and load pretrained model with default tokenizer and feature extractor', 'test the SpeechT5Processor class save and load pretrained model with additional tokenizer and feature extractor kwargs', 'test the SpeechT5Processor processes raw audio input through the feature extractor and returns matching tensor keys', 'test the SpeechT5Processor encodes text input through the tokenizer and returns matching tokenized keys', 'test the SpeechT5Processor batch decodes predicted token ids through the tokenizer', 'test the SpeechT5TokenizerTest class for tokenizer normalization, vocab, encoding and decoding', 'build a SpeechT5Tokenizer from a SentencePiece fixture with custom mask and special tokens', 'test the tokenizer normalization of numeric and monetary values into spelled-out text', 'test the full tokenizer encode, decode, and token-to-id conversion round-trip', 'test the tokenizer integration against the microsoft/speecht5_asr pretrained model']
```

Usage

```
{'test_SpeechT5TokenizerTest': 'test the SpeechT5TokenizerTest class for tokenizer normalization, vocab, encoding and decoding', 'build_SpeechT5Tokenizer_fixture': 'build a SpeechT5Tokenizer from a SentencePiece fixture with custom mask and special tokens', 'test_tokenizer_normalization': 'test the tokenizer normalization of numeric and monetary values into spelled-out text', 'test_full_tokenizer': 'test the full tokenizer encode, decode, and token-to-id conversion round-trip', 'test_tokenizer_integration': 'test the tokenizer integration against the microsoft/speecht5_asr pretrained model'}
```

