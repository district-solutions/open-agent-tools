# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/pop2piano/test_feature_extraction_pop2piano.py

Prompts

```
['create a Pop2PianoFeatureExtractor instance with custom sampling rate and vocabulary sizes', 'save a Pop2PianoFeatureExtractor to disk and reload it from the pretrained directory', 'extract mel spectrogram input features and beatsteps from raw audio with the feature extractor', 'batch process multiple audio inputs with different sampling rates and return attention masks', 'test serializing a Pop2PianoFeatureExtractor to JSON and deserializing it back', 'test the Pop2PianoTokenizer __call__ method with a list of pretty_midi Notes and return token_ids with padding and truncation', 'test the Pop2PianoTokenizer batch_decode method to convert model output token_ids into PrettyMIDI objects with feature extractor inputs', 'test the Pop2PianoTokenizer batch_decode method to verify predicted note start and end timings match expected values', 'test the Pop2PianoTokenizer padding and truncation behavior with left and right sides and pad_to_multiple_of alignment', 'test saving and loading a Pop2PianoTokenizer with custom tokens and additional special tokens to disk and verifying vocab consistency']
```

Usage

```
{'create_pop2piano_feature_extractor': 'create a Pop2PianoFeatureExtractor instance with custom sampling rate and vocabulary sizes', 'save_and_load_feature_extractor': 'save a Pop2PianoFeatureExtractor to disk and reload it from the pretrained directory', 'extract_audio_features': 'extract mel spectrogram input features and beatsteps from raw audio with the feature extractor', 'batch_process_audio_inputs': 'batch process multiple audio inputs with different sampling rates and return attention masks', 'test_feature_extractor_serialization': 'test serializing a Pop2PianoFeatureExtractor to JSON and deserializing it back'}
```

## File: huggingface_transformers/tests/models/pop2piano/test_tokenization_pop2piano.py

Prompts

```
['create a Pop2PianoFeatureExtractor instance with custom sampling rate and vocabulary sizes', 'save a Pop2PianoFeatureExtractor to disk and reload it from the pretrained directory', 'extract mel spectrogram input features and beatsteps from raw audio with the feature extractor', 'batch process multiple audio inputs with different sampling rates and return attention masks', 'test serializing a Pop2PianoFeatureExtractor to JSON and deserializing it back', 'test the Pop2PianoTokenizer __call__ method with a list of pretty_midi Notes and return token_ids with padding and truncation', 'test the Pop2PianoTokenizer batch_decode method to convert model output token_ids into PrettyMIDI objects with feature extractor inputs', 'test the Pop2PianoTokenizer batch_decode method to verify predicted note start and end timings match expected values', 'test the Pop2PianoTokenizer padding and truncation behavior with left and right sides and pad_to_multiple_of alignment', 'test saving and loading a Pop2PianoTokenizer with custom tokens and additional special tokens to disk and verifying vocab consistency']
```

Usage

```
{'test_pop2piano_tokenizer_call': 'test the Pop2PianoTokenizer __call__ method with a list of pretty_midi Notes and return token_ids with padding and truncation', 'test_batch_decode_pretty_midi': 'test the Pop2PianoTokenizer batch_decode method to convert model output token_ids into PrettyMIDI objects with feature extractor inputs', 'test_batch_decode_note_timings': 'test the Pop2PianoTokenizer batch_decode method to verify predicted note start and end timings match expected values', 'test_tokenizer_padding_truncation': 'test the Pop2PianoTokenizer padding and truncation behavior with left and right sides and pad_to_multiple_of alignment', 'test_tokenizer_save_load': 'test saving and loading a Pop2PianoTokenizer with custom tokens and additional special tokens to disk and verifying vocab consistency'}
```

