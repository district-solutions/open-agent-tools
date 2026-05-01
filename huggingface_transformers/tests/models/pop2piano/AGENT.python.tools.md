# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/pop2piano/test_feature_extraction_pop2piano.py

Prompts

```
['create a Pop2PianoFeatureExtractor instance with custom sampling rate and vocabulary sizes', 'save a Pop2PianoFeatureExtractor to disk and reload it from the pretrained directory', 'extract mel spectrogram input features and beatsteps from raw audio with the feature extractor', 'batch process multiple audio inputs with different sampling rates and return attention masks', 'test serializing a Pop2PianoFeatureExtractor to JSON and deserializing it back', 'test the Pop2PianoForConditionalGeneration model with encoder-decoder inputs and attention masks', 'test the Pop2Piano decoder model past key-value caching for efficient generation', 'test the Pop2Piano model with language modeling head and loss computation', 'test the Pop2Piano full model integration with audio feature extraction and MIDI generation', 'test the Pop2PianoConfig class with common configuration parameters and model initialization', 'test that Pop2PianoProcessor saves and loads with custom token kwargs like unk_token and eos_token', 'test that Pop2PianoFeatureExtractor extracts audio features matching processor output for the same input', 'test that Pop2PianoProcessor batch_decode returns matching note start, end, pitch, and velocity values', 'test that calling Pop2PianoProcessor with notes returns a BatchEncoding instance', 'test that Pop2PianoProcessor with audio and notes returns input_features, beatsteps, extrapolated_beatstep, and token_ids', 'test the Pop2PianoTokenizer __call__ method with a list of pretty_midi Notes and return token_ids with padding and truncation', 'test the Pop2PianoTokenizer batch_decode method to convert model output token_ids into PrettyMIDI objects with feature extractor inputs', 'test the Pop2PianoTokenizer batch_decode method to verify predicted note start and end timings match expected values', 'test the Pop2PianoTokenizer padding and truncation behavior with left and right sides and pad_to_multiple_of alignment', 'test saving and loading a Pop2PianoTokenizer with custom tokens and additional special tokens to disk and verifying vocab consistency']
```

Usage

```
{'create_pop2piano_feature_extractor': 'create a Pop2PianoFeatureExtractor instance with custom sampling rate and vocabulary sizes', 'save_and_load_feature_extractor': 'save a Pop2PianoFeatureExtractor to disk and reload it from the pretrained directory', 'extract_audio_features': 'extract mel spectrogram input features and beatsteps from raw audio with the feature extractor', 'batch_process_audio_inputs': 'batch process multiple audio inputs with different sampling rates and return attention masks', 'test_feature_extractor_serialization': 'test serializing a Pop2PianoFeatureExtractor to JSON and deserializing it back'}
```

## File: huggingface_transformers/tests/models/pop2piano/test_modeling_pop2piano.py

Prompts

```
['create a Pop2PianoFeatureExtractor instance with custom sampling rate and vocabulary sizes', 'save a Pop2PianoFeatureExtractor to disk and reload it from the pretrained directory', 'extract mel spectrogram input features and beatsteps from raw audio with the feature extractor', 'batch process multiple audio inputs with different sampling rates and return attention masks', 'test serializing a Pop2PianoFeatureExtractor to JSON and deserializing it back', 'test the Pop2PianoForConditionalGeneration model with encoder-decoder inputs and attention masks', 'test the Pop2Piano decoder model past key-value caching for efficient generation', 'test the Pop2Piano model with language modeling head and loss computation', 'test the Pop2Piano full model integration with audio feature extraction and MIDI generation', 'test the Pop2PianoConfig class with common configuration parameters and model initialization', 'test that Pop2PianoProcessor saves and loads with custom token kwargs like unk_token and eos_token', 'test that Pop2PianoFeatureExtractor extracts audio features matching processor output for the same input', 'test that Pop2PianoProcessor batch_decode returns matching note start, end, pitch, and velocity values', 'test that calling Pop2PianoProcessor with notes returns a BatchEncoding instance', 'test that Pop2PianoProcessor with audio and notes returns input_features, beatsteps, extrapolated_beatstep, and token_ids', 'test the Pop2PianoTokenizer __call__ method with a list of pretty_midi Notes and return token_ids with padding and truncation', 'test the Pop2PianoTokenizer batch_decode method to convert model output token_ids into PrettyMIDI objects with feature extractor inputs', 'test the Pop2PianoTokenizer batch_decode method to verify predicted note start and end timings match expected values', 'test the Pop2PianoTokenizer padding and truncation behavior with left and right sides and pad_to_multiple_of alignment', 'test saving and loading a Pop2PianoTokenizer with custom tokens and additional special tokens to disk and verifying vocab consistency']
```

Usage

```
{'test_pop2piano_model': 'test the Pop2PianoForConditionalGeneration model with encoder-decoder inputs and attention masks', 'test_pop2piano_decoder_past': 'test the Pop2Piano decoder model past key-value caching for efficient generation', 'test_pop2piano_lm_head': 'test the Pop2Piano model with language modeling head and loss computation', 'test_pop2piano_integration': 'test the Pop2Piano full model integration with audio feature extraction and MIDI generation', 'test_pop2piano_config': 'test the Pop2PianoConfig class with common configuration parameters and model initialization'}
```

## File: huggingface_transformers/tests/models/pop2piano/test_processing_pop2piano.py

Prompts

```
['create a Pop2PianoFeatureExtractor instance with custom sampling rate and vocabulary sizes', 'save a Pop2PianoFeatureExtractor to disk and reload it from the pretrained directory', 'extract mel spectrogram input features and beatsteps from raw audio with the feature extractor', 'batch process multiple audio inputs with different sampling rates and return attention masks', 'test serializing a Pop2PianoFeatureExtractor to JSON and deserializing it back', 'test the Pop2PianoForConditionalGeneration model with encoder-decoder inputs and attention masks', 'test the Pop2Piano decoder model past key-value caching for efficient generation', 'test the Pop2Piano model with language modeling head and loss computation', 'test the Pop2Piano full model integration with audio feature extraction and MIDI generation', 'test the Pop2PianoConfig class with common configuration parameters and model initialization', 'test that Pop2PianoProcessor saves and loads with custom token kwargs like unk_token and eos_token', 'test that Pop2PianoFeatureExtractor extracts audio features matching processor output for the same input', 'test that Pop2PianoProcessor batch_decode returns matching note start, end, pitch, and velocity values', 'test that calling Pop2PianoProcessor with notes returns a BatchEncoding instance', 'test that Pop2PianoProcessor with audio and notes returns input_features, beatsteps, extrapolated_beatstep, and token_ids', 'test the Pop2PianoTokenizer __call__ method with a list of pretty_midi Notes and return token_ids with padding and truncation', 'test the Pop2PianoTokenizer batch_decode method to convert model output token_ids into PrettyMIDI objects with feature extractor inputs', 'test the Pop2PianoTokenizer batch_decode method to verify predicted note start and end timings match expected values', 'test the Pop2PianoTokenizer padding and truncation behavior with left and right sides and pad_to_multiple_of alignment', 'test saving and loading a Pop2PianoTokenizer with custom tokens and additional special tokens to disk and verifying vocab consistency']
```

Usage

```
{'test_Pop2PianoProcessor_save_load': 'test that Pop2PianoProcessor saves and loads with custom token kwargs like unk_token and eos_token', 'test_Pop2PianoFeatureExtractor_extraction': 'test that Pop2PianoFeatureExtractor extracts audio features matching processor output for the same input', 'test_Pop2PianoProcessor_batch_decode': 'test that Pop2PianoProcessor batch_decode returns matching note start, end, pitch, and velocity values', 'test_Pop2PianoProcessor_tokenizer_call': 'test that calling Pop2PianoProcessor with notes returns a BatchEncoding instance', 'test_Pop2PianoProcessor_full_inputs': 'test that Pop2PianoProcessor with audio and notes returns input_features, beatsteps, extrapolated_beatstep, and token_ids'}
```

## File: huggingface_transformers/tests/models/pop2piano/test_tokenization_pop2piano.py

Prompts

```
['create a Pop2PianoFeatureExtractor instance with custom sampling rate and vocabulary sizes', 'save a Pop2PianoFeatureExtractor to disk and reload it from the pretrained directory', 'extract mel spectrogram input features and beatsteps from raw audio with the feature extractor', 'batch process multiple audio inputs with different sampling rates and return attention masks', 'test serializing a Pop2PianoFeatureExtractor to JSON and deserializing it back', 'test the Pop2PianoForConditionalGeneration model with encoder-decoder inputs and attention masks', 'test the Pop2Piano decoder model past key-value caching for efficient generation', 'test the Pop2Piano model with language modeling head and loss computation', 'test the Pop2Piano full model integration with audio feature extraction and MIDI generation', 'test the Pop2PianoConfig class with common configuration parameters and model initialization', 'test that Pop2PianoProcessor saves and loads with custom token kwargs like unk_token and eos_token', 'test that Pop2PianoFeatureExtractor extracts audio features matching processor output for the same input', 'test that Pop2PianoProcessor batch_decode returns matching note start, end, pitch, and velocity values', 'test that calling Pop2PianoProcessor with notes returns a BatchEncoding instance', 'test that Pop2PianoProcessor with audio and notes returns input_features, beatsteps, extrapolated_beatstep, and token_ids', 'test the Pop2PianoTokenizer __call__ method with a list of pretty_midi Notes and return token_ids with padding and truncation', 'test the Pop2PianoTokenizer batch_decode method to convert model output token_ids into PrettyMIDI objects with feature extractor inputs', 'test the Pop2PianoTokenizer batch_decode method to verify predicted note start and end timings match expected values', 'test the Pop2PianoTokenizer padding and truncation behavior with left and right sides and pad_to_multiple_of alignment', 'test saving and loading a Pop2PianoTokenizer with custom tokens and additional special tokens to disk and verifying vocab consistency']
```

Usage

```
{'test_pop2piano_tokenizer_call': 'test the Pop2PianoTokenizer __call__ method with a list of pretty_midi Notes and return token_ids with padding and truncation', 'test_batch_decode_pretty_midi': 'test the Pop2PianoTokenizer batch_decode method to convert model output token_ids into PrettyMIDI objects with feature extractor inputs', 'test_batch_decode_note_timings': 'test the Pop2PianoTokenizer batch_decode method to verify predicted note start and end timings match expected values', 'test_tokenizer_padding_truncation': 'test the Pop2PianoTokenizer padding and truncation behavior with left and right sides and pad_to_multiple_of alignment', 'test_tokenizer_save_load': 'test saving and loading a Pop2PianoTokenizer with custom tokens and additional special tokens to disk and verifying vocab consistency'}
```

