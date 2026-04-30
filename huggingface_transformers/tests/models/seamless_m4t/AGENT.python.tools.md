# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/seamless_m4t/test_feature_extraction_seamless_m4t.py

Prompts

```
['test the SeamlessM4TFeatureExtractor class for correct feature extraction behavior with numpy and torch inputs', 'create a SeamlessM4TFeatureExtractor instance and save/load it from a pretrained directory using from_pretrained and save_pretrained', 'test batch encoding of numpy speech inputs with padding and variable sequence lengths producing 3-D input_features tensors', 'test that attention masks are generated with correct 2-D shape matching the padded input_features length', 'test zero_mean_unit_var_norm method to verify audio inputs are normalized to zero mean and unit variance', 'test the SeamlessM4TTokenizationTest class for batch encoding, padding, and sequence length validation', 'test the prepare_seq2seq_batch method with source and target texts, max_length, and language codes', 'test that tokenizer padding respects pad_to_multiple_of parameter for empty and normal inputs', 'test training a new SeamlessM4TTokenizer from a small corpus and verify token consistency', 'test the _build_translation_inputs method with source and target language codes', 'test that SeamlessM4TTokenizer correctly maps language codes to token IDs', 'test setting and switching target language special tokens on the tokenizer', 'test batch encoding with source and target texts, truncation, and decoder input IDs', 'test that the tokenizer removes extra whitespaces and handles sentencepiece whitespace tokens', 'test that special tokens are properly stripped of surrounding whitespace during tokenization']
```

Usage

```
{'test_feature_extraction_seamless_m4t': 'test the SeamlessM4TFeatureExtractor class for correct feature extraction behavior with numpy and torch inputs', 'create_feature_extractor_pretrained': 'create a SeamlessM4TFeatureExtractor instance and save/load it from a pretrained directory using from_pretrained and save_pretrained', 'test_batch_encode_numpy_inputs': 'test batch encoding of numpy speech inputs with padding and variable sequence lengths producing 3-D input_features tensors', 'test_attention_mask_generation': 'test that attention masks are generated with correct 2-D shape matching the padded input_features length', 'test_zero_mean_unit_variance_normalization': 'test zero_mean_unit_var_norm method to verify audio inputs are normalized to zero mean and unit variance'}
```

## File: huggingface_transformers/tests/models/seamless_m4t/test_tokenization_seamless_m4t.py

Prompts

```
['test the SeamlessM4TFeatureExtractor class for correct feature extraction behavior with numpy and torch inputs', 'create a SeamlessM4TFeatureExtractor instance and save/load it from a pretrained directory using from_pretrained and save_pretrained', 'test batch encoding of numpy speech inputs with padding and variable sequence lengths producing 3-D input_features tensors', 'test that attention masks are generated with correct 2-D shape matching the padded input_features length', 'test zero_mean_unit_var_norm method to verify audio inputs are normalized to zero mean and unit variance', 'test the SeamlessM4TTokenizationTest class for batch encoding, padding, and sequence length validation', 'test the prepare_seq2seq_batch method with source and target texts, max_length, and language codes', 'test that tokenizer padding respects pad_to_multiple_of parameter for empty and normal inputs', 'test training a new SeamlessM4TTokenizer from a small corpus and verify token consistency', 'test the _build_translation_inputs method with source and target language codes', 'test that SeamlessM4TTokenizer correctly maps language codes to token IDs', 'test setting and switching target language special tokens on the tokenizer', 'test batch encoding with source and target texts, truncation, and decoder input IDs', 'test that the tokenizer removes extra whitespaces and handles sentencepiece whitespace tokens', 'test that special tokens are properly stripped of surrounding whitespace during tokenization']
```

Usage

```
{'test_tokenization_seamless_m4t': 'test the SeamlessM4TTokenizationTest class for batch encoding, padding, and sequence length validation', 'test_prepare_seq2seq_batch': 'test the prepare_seq2seq_batch method with source and target texts, max_length, and language codes', 'test_padding_to_multiple_of': 'test that tokenizer padding respects pad_to_multiple_of parameter for empty and normal inputs', 'test_training_new_tokenizer': 'test training a new SeamlessM4TTokenizer from a small corpus and verify token consistency', 'test_tokenizer_translation': 'test the _build_translation_inputs method with source and target language codes', 'test_language_codes': 'test that SeamlessM4TTokenizer correctly maps language codes to token IDs', 'test_tokenizer_tgt_lang': 'test setting and switching target language special tokens on the tokenizer', 'test_enro_tokenizer_prepare_batch': 'test batch encoding with source and target texts, truncation, and decoder input IDs', 'test_int_remove_extra_whitespaces': 'test that the tokenizer removes extra whitespaces and handles sentencepiece whitespace tokens', 'test_special_tokens_strip': 'test that special tokens are properly stripped of surrounding whitespace during tokenization'}
```

