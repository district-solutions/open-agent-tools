# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/wav2vec2/test_feature_extraction_wav2vec2.py

Prompts

```
['test the Wav2Vec2FeatureExtractor by calling encode_plus and batch_encode_plus with list and numpy inputs', 'test zero mean unit variance normalization on batched speech inputs with numpy arrays', 'test zero mean unit variance normalization with truncation and max_length padding strategies', 'test that double precision float64 inputs are converted to float32 in numpy and torch outputs', 'test that pretrained wav2vec2 checkpoints set return_attention_mask based on feat_extract_norm config', 'test Wav2Vec2ForCTC model inference with automatic speech recognition on audio samples', 'test Wav2Vec2ForSequenceClassification model for audio classification and keyword spotting tasks', 'test loading and applying Wav2Vec2 adapters for different target languages with safetensors support', 'test _compute_mask_indices utility for generating masked time indices in wav2vec2 pretraining', 'test Wav2Vec2ForCTC batch decoding with language model using pyctcdecode and torchaudio', 'test the Wav2Vec2CTCTokenizer decode method to convert token IDs back to readable text strings', 'test the Wav2Vec2CTCTokenizer word delimiter round trip by saving and reloading the tokenizer', 'test adding new tokens to the Wav2Vec2CTCTokenizer vocabulary and verifying encoded output', 'test the Wav2Vec2CTCTokenizer offset tracking for character and word boundaries during decode', 'test the Wav2Vec2CTCTokenizer nested vocabulary support for switching between language-specific vocabularies']
```

Usage

```
{'test_feature_extraction_wav2vec2': 'test the Wav2Vec2FeatureExtractor by calling encode_plus and batch_encode_plus with list and numpy inputs', 'test_normalization_zero_mean_unit_variance': 'test zero mean unit variance normalization on batched speech inputs with numpy arrays', 'test_normalization_truncation_padding': 'test zero mean unit variance normalization with truncation and max_length padding strategies', 'test_double_precision_padding': 'test that double precision float64 inputs are converted to float32 in numpy and torch outputs', 'test_pretrained_checkpoints_attention_mask': 'test that pretrained wav2vec2 checkpoints set return_attention_mask based on feat_extract_norm config'}
```

## File: huggingface_transformers/tests/models/wav2vec2/test_modeling_wav2vec2.py

Prompts

```
['test the Wav2Vec2FeatureExtractor by calling encode_plus and batch_encode_plus with list and numpy inputs', 'test zero mean unit variance normalization on batched speech inputs with numpy arrays', 'test zero mean unit variance normalization with truncation and max_length padding strategies', 'test that double precision float64 inputs are converted to float32 in numpy and torch outputs', 'test that pretrained wav2vec2 checkpoints set return_attention_mask based on feat_extract_norm config', 'test Wav2Vec2ForCTC model inference with automatic speech recognition on audio samples', 'test Wav2Vec2ForSequenceClassification model for audio classification and keyword spotting tasks', 'test loading and applying Wav2Vec2 adapters for different target languages with safetensors support', 'test _compute_mask_indices utility for generating masked time indices in wav2vec2 pretraining', 'test Wav2Vec2ForCTC batch decoding with language model using pyctcdecode and torchaudio', 'test the Wav2Vec2CTCTokenizer decode method to convert token IDs back to readable text strings', 'test the Wav2Vec2CTCTokenizer word delimiter round trip by saving and reloading the tokenizer', 'test adding new tokens to the Wav2Vec2CTCTokenizer vocabulary and verifying encoded output', 'test the Wav2Vec2CTCTokenizer offset tracking for character and word boundaries during decode', 'test the Wav2Vec2CTCTokenizer nested vocabulary support for switching between language-specific vocabularies']
```

Usage

```
{'test_wav2vec2_ctc_inference': 'test Wav2Vec2ForCTC model inference with automatic speech recognition on audio samples', 'test_wav2vec2_sequence_classification': 'test Wav2Vec2ForSequenceClassification model for audio classification and keyword spotting tasks', 'test_wav2vec2_adapter_loading': 'test loading and applying Wav2Vec2 adapters for different target languages with safetensors support', 'test_mask_indices_computation': 'test _compute_mask_indices utility for generating masked time indices in wav2vec2 pretraining', 'test_wav2vec2_with_language_model': 'test Wav2Vec2ForCTC batch decoding with language model using pyctcdecode and torchaudio'}
```

## File: huggingface_transformers/tests/models/wav2vec2/test_tokenization_wav2vec2.py

Prompts

```
['test the Wav2Vec2FeatureExtractor by calling encode_plus and batch_encode_plus with list and numpy inputs', 'test zero mean unit variance normalization on batched speech inputs with numpy arrays', 'test zero mean unit variance normalization with truncation and max_length padding strategies', 'test that double precision float64 inputs are converted to float32 in numpy and torch outputs', 'test that pretrained wav2vec2 checkpoints set return_attention_mask based on feat_extract_norm config', 'test Wav2Vec2ForCTC model inference with automatic speech recognition on audio samples', 'test Wav2Vec2ForSequenceClassification model for audio classification and keyword spotting tasks', 'test loading and applying Wav2Vec2 adapters for different target languages with safetensors support', 'test _compute_mask_indices utility for generating masked time indices in wav2vec2 pretraining', 'test Wav2Vec2ForCTC batch decoding with language model using pyctcdecode and torchaudio', 'test the Wav2Vec2CTCTokenizer decode method to convert token IDs back to readable text strings', 'test the Wav2Vec2CTCTokenizer word delimiter round trip by saving and reloading the tokenizer', 'test adding new tokens to the Wav2Vec2CTCTokenizer vocabulary and verifying encoded output', 'test the Wav2Vec2CTCTokenizer offset tracking for character and word boundaries during decode', 'test the Wav2Vec2CTCTokenizer nested vocabulary support for switching between language-specific vocabularies']
```

Usage

```
{'test_tokenizer_decode': 'test the Wav2Vec2CTCTokenizer decode method to convert token IDs back to readable text strings', 'test_word_delimiter_round_trip': 'test the Wav2Vec2CTCTokenizer word delimiter round trip by saving and reloading the tokenizer', 'test_tokenizer_add_tokens': 'test adding new tokens to the Wav2Vec2CTCTokenizer vocabulary and verifying encoded output', 'test_offsets': 'test the Wav2Vec2CTCTokenizer offset tracking for character and word boundaries during decode', 'test_nested_vocab': 'test the Wav2Vec2CTCTokenizer nested vocabulary support for switching between language-specific vocabularies'}
```

