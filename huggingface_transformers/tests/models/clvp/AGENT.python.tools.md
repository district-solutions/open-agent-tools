# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/clvp/test_processing_clvp.py

Prompts

```
['test ClvpProcessor save_pretrained and from_pretrained with default tokenizer and feature extractor', 'test ClvpProcessor processes raw speech audio input and produces feature extractor output', 'test ClvpProcessor encodes text input identically to ClvpTokenizer directly', 'test ClvpProcessor batch_decode produces same output as ClvpTokenizer batch_decode', 'test ClvpProcessor from_pretrained with additional kwargs like pad_token and sampling_rate', 'test the ClvpTokenizer full tokenizer with vocab and merges files to verify BPE tokenization output', 'test the ClvpTokenizer add_special_tokens method with custom cls_token and boxes input', 'test the ClvpTokenizer padding behavior with pad_token set and max_length truncation', 'test the ClvpTokenizer token_type_ids generation for sequence classification tagging', 'test the ClvpTokenizer special_tokens_mask with input pairs and bos_token enabled']
```

Usage

```
{'test_clvp_processor_save_load': 'test ClvpProcessor save_pretrained and from_pretrained with default tokenizer and feature extractor', 'test_clvp_processor_feature_extraction': 'test ClvpProcessor processes raw speech audio input and produces feature extractor output', 'test_clvp_processor_tokenization': 'test ClvpProcessor encodes text input identically to ClvpTokenizer directly', 'test_clvp_processor_batch_decode': 'test ClvpProcessor batch_decode produces same output as ClvpTokenizer batch_decode', 'test_clvp_processor_save_load_kwargs': 'test ClvpProcessor from_pretrained with additional kwargs like pad_token and sampling_rate'}
```

## File: huggingface_transformers/tests/models/clvp/test_tokenization_clvp.py

Prompts

```
['test ClvpProcessor save_pretrained and from_pretrained with default tokenizer and feature extractor', 'test ClvpProcessor processes raw speech audio input and produces feature extractor output', 'test ClvpProcessor encodes text input identically to ClvpTokenizer directly', 'test ClvpProcessor batch_decode produces same output as ClvpTokenizer batch_decode', 'test ClvpProcessor from_pretrained with additional kwargs like pad_token and sampling_rate', 'test the ClvpTokenizer full tokenizer with vocab and merges files to verify BPE tokenization output', 'test the ClvpTokenizer add_special_tokens method with custom cls_token and boxes input', 'test the ClvpTokenizer padding behavior with pad_token set and max_length truncation', 'test the ClvpTokenizer token_type_ids generation for sequence classification tagging', 'test the ClvpTokenizer special_tokens_mask with input pairs and bos_token enabled']
```

Usage

```
{'test_tokenization_clvp_full_tokenizer': 'test the ClvpTokenizer full tokenizer with vocab and merges files to verify BPE tokenization output', 'test_tokenization_clvp_special_tokens': 'test the ClvpTokenizer add_special_tokens method with custom cls_token and boxes input', 'test_tokenization_clvp_padding': 'test the ClvpTokenizer padding behavior with pad_token set and max_length truncation', 'test_tokenization_clvp_token_type_ids': 'test the ClvpTokenizer token_type_ids generation for sequence classification tagging', 'test_tokenization_clvp_special_tokens_mask': 'test the ClvpTokenizer special_tokens_mask with input pairs and bos_token enabled'}
```

