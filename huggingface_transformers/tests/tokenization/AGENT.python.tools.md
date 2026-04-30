# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/tokenization/test_tokenization_fast.py

Prompts

```
['create a PreTrainedTokenizerFast from a tokenizers backend Tokenizer with special tokens', 'load a PreTrainedTokenizerFast from a saved directory using from_pretrained', 'save a PreTrainedTokenizerFast to a directory using save_pretrained', 'train a new BPE tokenizer from a text iterator with a given vocab size', 'call _patch_mistral_regex on a backend tokenizer to fix regex for non-Mistral models', 'test BatchEncoding.convert_to_tensors to convert inputs and labels to numpy or pytorch tensors with batch axis', 'test tokenizer.pad to pad a list of tokenized features to equal length with numpy or torch tensors', 'test tokenizer.decode to convert token IDs back to text with or without skipping special tokens', 'test apply_chat_template and encode_message_with_chat_template to encode multi-turn chat conversations into token IDs', 'test _set_model_specific_special_tokens and add_tokens to register custom multimodal special tokens like image tokens on a tokenizer']
```

Usage

```
{'create_PreTrainedTokenizerFast_from_backend': 'create a PreTrainedTokenizerFast from a tokenizers backend Tokenizer with special tokens', 'load_PreTrainedTokenizerFast_from_pretrained': 'load a PreTrainedTokenizerFast from a saved directory using from_pretrained', 'save_PreTrainedTokenizerFast_to_disk': 'save a PreTrainedTokenizerFast to a directory using save_pretrained', 'train_tokenizer_from_iterator': 'train a new BPE tokenizer from a text iterator with a given vocab size', 'patch_mistral_regex_tokenizer': 'call _patch_mistral_regex on a backend tokenizer to fix regex for non-Mistral models'}
```

## File: huggingface_transformers/tests/tokenization/test_tokenization_utils.py

Prompts

```
['create a PreTrainedTokenizerFast from a tokenizers backend Tokenizer with special tokens', 'load a PreTrainedTokenizerFast from a saved directory using from_pretrained', 'save a PreTrainedTokenizerFast to a directory using save_pretrained', 'train a new BPE tokenizer from a text iterator with a given vocab size', 'call _patch_mistral_regex on a backend tokenizer to fix regex for non-Mistral models', 'test BatchEncoding.convert_to_tensors to convert inputs and labels to numpy or pytorch tensors with batch axis', 'test tokenizer.pad to pad a list of tokenized features to equal length with numpy or torch tensors', 'test tokenizer.decode to convert token IDs back to text with or without skipping special tokens', 'test apply_chat_template and encode_message_with_chat_template to encode multi-turn chat conversations into token IDs', 'test _set_model_specific_special_tokens and add_tokens to register custom multimodal special tokens like image tokens on a tokenizer']
```

Usage

```
{'test_batch_encoding_convert_to_tensors': 'test BatchEncoding.convert_to_tensors to convert inputs and labels to numpy or pytorch tensors with batch axis', 'test_tokenizer_pad_features': 'test tokenizer.pad to pad a list of tokenized features to equal length with numpy or torch tensors', 'test_tokenizer_decode_skip_special': 'test tokenizer.decode to convert token IDs back to text with or without skipping special tokens', 'test_apply_chat_template': 'test apply_chat_template and encode_message_with_chat_template to encode multi-turn chat conversations into token IDs', 'test_add_special_tokens_multimodal': 'test _set_model_specific_special_tokens and add_tokens to register custom multimodal special tokens like image tokens on a tokenizer'}
```

