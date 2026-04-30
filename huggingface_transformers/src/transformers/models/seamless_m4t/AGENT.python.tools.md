# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/seamless_m4t/convert_fairseq2_to_hf.py

Prompts

```
['convert a Meta SeamlessM4T fairseq2 checkpoint to a Hugging Face SeamlessM4T model', 'build a SeamlessM4T tokenizer with language-specific special tokens for supported languages', 'test the fairseq2 to Hugging Face SeamlessM4T model conversion with sanity checks', 'summarize the load_model function that converts Meta SeamlessM4T components to HF', 'review the _convert_model function that maps fairseq2 state dict keys to Hugging Face layer names', 'create a SeamlessM4TFeatureExtractor instance with configurable feature_size, sampling_rate, num_mel_bins, padding_value, and stride', 'run the __call__ method to extract mel-filter bank features from raw speech waveform input and return padded BatchFeature', 'test the zero_mean_unit_var_norm static method to normalize input arrays to zero mean and unit variance', 'run the _extract_fbank_features method to compute mel-filter bank spectrogram features from a single waveform array', 'review the SeamlessM4TFeatureExtractor class that inherits from SequenceFeatureExtractor for audio feature extraction', 'generate translated text sequences using SeamlessM4TForTextToText with source input_ids and target language', 'generate translated speech waveforms using SeamlessM4TForSpeechToSpeech from input audio features and target language', 'synthesize speech waveforms from text input using SeamlessM4TForTextToSpeech with target language and speaker id', 'convert speech audio features to translated text sequences using SeamlessM4TForSpeechToText', 'run multimodal text and speech generation using SeamlessM4TModel with generate_speech flag and target language', 'create a SeamlessM4TTokenizer instance from pretrained model with source and target languages', 'build translation inputs with forced BOS token for a source and target language pair', 'prepare a seq2seq batch with source texts, target texts, and language codes for training', 'switch the tokenizer to target language mode with eos prefix and target lang tokens', 'set source language special tokens with prefix and suffix for tokenization']
```

Usage

```
{'convert_fairseq2_to_hf_model': 'convert a Meta SeamlessM4T fairseq2 checkpoint to a Hugging Face SeamlessM4T model', 'build_seamlessm4t_tokenizer': 'build a SeamlessM4T tokenizer with language-specific special tokens for supported languages', 'test_seamlessm4t_conversion': 'test the fairseq2 to Hugging Face SeamlessM4T model conversion with sanity checks', 'summarize_load_model': 'summarize the load_model function that converts Meta SeamlessM4T components to HF', 'review_convert_model': 'review the _convert_model function that maps fairseq2 state dict keys to Hugging Face layer names'}
```

## File: huggingface_transformers/src/transformers/models/seamless_m4t/feature_extraction_seamless_m4t.py

Prompts

```
['convert a Meta SeamlessM4T fairseq2 checkpoint to a Hugging Face SeamlessM4T model', 'build a SeamlessM4T tokenizer with language-specific special tokens for supported languages', 'test the fairseq2 to Hugging Face SeamlessM4T model conversion with sanity checks', 'summarize the load_model function that converts Meta SeamlessM4T components to HF', 'review the _convert_model function that maps fairseq2 state dict keys to Hugging Face layer names', 'create a SeamlessM4TFeatureExtractor instance with configurable feature_size, sampling_rate, num_mel_bins, padding_value, and stride', 'run the __call__ method to extract mel-filter bank features from raw speech waveform input and return padded BatchFeature', 'test the zero_mean_unit_var_norm static method to normalize input arrays to zero mean and unit variance', 'run the _extract_fbank_features method to compute mel-filter bank spectrogram features from a single waveform array', 'review the SeamlessM4TFeatureExtractor class that inherits from SequenceFeatureExtractor for audio feature extraction', 'generate translated text sequences using SeamlessM4TForTextToText with source input_ids and target language', 'generate translated speech waveforms using SeamlessM4TForSpeechToSpeech from input audio features and target language', 'synthesize speech waveforms from text input using SeamlessM4TForTextToSpeech with target language and speaker id', 'convert speech audio features to translated text sequences using SeamlessM4TForSpeechToText', 'run multimodal text and speech generation using SeamlessM4TModel with generate_speech flag and target language', 'create a SeamlessM4TTokenizer instance from pretrained model with source and target languages', 'build translation inputs with forced BOS token for a source and target language pair', 'prepare a seq2seq batch with source texts, target texts, and language codes for training', 'switch the tokenizer to target language mode with eos prefix and target lang tokens', 'set source language special tokens with prefix and suffix for tokenization']
```

Usage

```
{'create_SeamlessM4TFeatureExtractor': 'create a SeamlessM4TFeatureExtractor instance with configurable feature_size, sampling_rate, num_mel_bins, padding_value, and stride', 'run___call__extract_fbank': 'run the __call__ method to extract mel-filter bank features from raw speech waveform input and return padded BatchFeature', 'test_zero_mean_unit_var_norm': 'test the zero_mean_unit_var_norm static method to normalize input arrays to zero mean and unit variance', 'run__extract_fbank_features': 'run the _extract_fbank_features method to compute mel-filter bank spectrogram features from a single waveform array', 'review_SeamlessM4TFeatureExtractor': 'review the SeamlessM4TFeatureExtractor class that inherits from SequenceFeatureExtractor for audio feature extraction'}
```

## File: huggingface_transformers/src/transformers/models/seamless_m4t/modeling_seamless_m4t.py

Prompts

```
['convert a Meta SeamlessM4T fairseq2 checkpoint to a Hugging Face SeamlessM4T model', 'build a SeamlessM4T tokenizer with language-specific special tokens for supported languages', 'test the fairseq2 to Hugging Face SeamlessM4T model conversion with sanity checks', 'summarize the load_model function that converts Meta SeamlessM4T components to HF', 'review the _convert_model function that maps fairseq2 state dict keys to Hugging Face layer names', 'create a SeamlessM4TFeatureExtractor instance with configurable feature_size, sampling_rate, num_mel_bins, padding_value, and stride', 'run the __call__ method to extract mel-filter bank features from raw speech waveform input and return padded BatchFeature', 'test the zero_mean_unit_var_norm static method to normalize input arrays to zero mean and unit variance', 'run the _extract_fbank_features method to compute mel-filter bank spectrogram features from a single waveform array', 'review the SeamlessM4TFeatureExtractor class that inherits from SequenceFeatureExtractor for audio feature extraction', 'generate translated text sequences using SeamlessM4TForTextToText with source input_ids and target language', 'generate translated speech waveforms using SeamlessM4TForSpeechToSpeech from input audio features and target language', 'synthesize speech waveforms from text input using SeamlessM4TForTextToSpeech with target language and speaker id', 'convert speech audio features to translated text sequences using SeamlessM4TForSpeechToText', 'run multimodal text and speech generation using SeamlessM4TModel with generate_speech flag and target language', 'create a SeamlessM4TTokenizer instance from pretrained model with source and target languages', 'build translation inputs with forced BOS token for a source and target language pair', 'prepare a seq2seq batch with source texts, target texts, and language codes for training', 'switch the tokenizer to target language mode with eos prefix and target lang tokens', 'set source language special tokens with prefix and suffix for tokenization']
```

Usage

```
{'generate_text_translation': 'generate translated text sequences using SeamlessM4TForTextToText with source input_ids and target language', 'generate_speech_translation': 'generate translated speech waveforms using SeamlessM4TForSpeechToSpeech from input audio features and target language', 'synthesize_speech_from_text': 'synthesize speech waveforms from text input using SeamlessM4TForTextToSpeech with target language and speaker id', 'convert_speech_to_text': 'convert speech audio features to translated text sequences using SeamlessM4TForSpeechToText', 'run_multimodal_generation': 'run multimodal text and speech generation using SeamlessM4TModel with generate_speech flag and target language'}
```

## File: huggingface_transformers/src/transformers/models/seamless_m4t/tokenization_seamless_m4t.py

Prompts

```
['convert a Meta SeamlessM4T fairseq2 checkpoint to a Hugging Face SeamlessM4T model', 'build a SeamlessM4T tokenizer with language-specific special tokens for supported languages', 'test the fairseq2 to Hugging Face SeamlessM4T model conversion with sanity checks', 'summarize the load_model function that converts Meta SeamlessM4T components to HF', 'review the _convert_model function that maps fairseq2 state dict keys to Hugging Face layer names', 'create a SeamlessM4TFeatureExtractor instance with configurable feature_size, sampling_rate, num_mel_bins, padding_value, and stride', 'run the __call__ method to extract mel-filter bank features from raw speech waveform input and return padded BatchFeature', 'test the zero_mean_unit_var_norm static method to normalize input arrays to zero mean and unit variance', 'run the _extract_fbank_features method to compute mel-filter bank spectrogram features from a single waveform array', 'review the SeamlessM4TFeatureExtractor class that inherits from SequenceFeatureExtractor for audio feature extraction', 'generate translated text sequences using SeamlessM4TForTextToText with source input_ids and target language', 'generate translated speech waveforms using SeamlessM4TForSpeechToSpeech from input audio features and target language', 'synthesize speech waveforms from text input using SeamlessM4TForTextToSpeech with target language and speaker id', 'convert speech audio features to translated text sequences using SeamlessM4TForSpeechToText', 'run multimodal text and speech generation using SeamlessM4TModel with generate_speech flag and target language', 'create a SeamlessM4TTokenizer instance from pretrained model with source and target languages', 'build translation inputs with forced BOS token for a source and target language pair', 'prepare a seq2seq batch with source texts, target texts, and language codes for training', 'switch the tokenizer to target language mode with eos prefix and target lang tokens', 'set source language special tokens with prefix and suffix for tokenization']
```

Usage

```
{'create_seamless_m4t_tokenizer': 'create a SeamlessM4TTokenizer instance from pretrained model with source and target languages', 'build_translation_inputs': 'build translation inputs with forced BOS token for a source and target language pair', 'prepare_seq2seq_batch': 'prepare a seq2seq batch with source texts, target texts, and language codes for training', 'switch_to_target_mode': 'switch the tokenizer to target language mode with eos prefix and target lang tokens', 'set_src_lang_special_tokens': 'set source language special tokens with prefix and suffix for tokenization'}
```

