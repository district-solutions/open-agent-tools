# Agent Python Tools

- repo: facebookresearch/tart
- repo_uri: https://github.com/facebookresearch/tart

## File: facebookresearch_tart/BERRI/enc_t5/modeling_enc_t5.py

Prompts

```
['build a T5 encoder-only sequence classification model using EncT5ForSequenceClassification with a T5Config', 'run a forward pass on EncT5ForSequenceClassification with input_ids and attention_mask to get classification logits', 'parallelize the EncT5ForSequenceClassification model across multiple GPUs using the parallelize method with a device map', 'prune specific attention heads in the EncT5ForSequenceClassification encoder using the _prune_heads method with a layer to heads mapping', 'review the EncT5ForSequenceClassification forward method to understand regression, single label, and multi label classification problem types', 'initialize an EncT5Tokenizer instance with a vocab file and custom special tokens', 'build model inputs by wrapping token sequences with bos and eos special tokens', 'get a binary mask identifying special tokens versus regular tokens in a sequence', 'create token type ids for single or paired sequences with special tokens', 'review the EncT5Tokenizer class that extends T5Tokenizer with custom special token handling']
```

Usage

```
{'build_enc_t5_classifier': 'build a T5 encoder-only sequence classification model using EncT5ForSequenceClassification with a T5Config', 'run_forward_pass': 'run a forward pass on EncT5ForSequenceClassification with input_ids and attention_mask to get classification logits', 'parallelize_model': 'parallelize the EncT5ForSequenceClassification model across multiple GPUs using the parallelize method with a device map', 'prune_attention_heads': 'prune specific attention heads in the EncT5ForSequenceClassification encoder using the _prune_heads method with a layer to heads mapping', 'review_classifier_problem_types': 'review the EncT5ForSequenceClassification forward method to understand regression, single label, and multi label classification problem types'}
```

## File: facebookresearch_tart/BERRI/enc_t5/tokenization_enc_t5.py

Prompts

```
['build a T5 encoder-only sequence classification model using EncT5ForSequenceClassification with a T5Config', 'run a forward pass on EncT5ForSequenceClassification with input_ids and attention_mask to get classification logits', 'parallelize the EncT5ForSequenceClassification model across multiple GPUs using the parallelize method with a device map', 'prune specific attention heads in the EncT5ForSequenceClassification encoder using the _prune_heads method with a layer to heads mapping', 'review the EncT5ForSequenceClassification forward method to understand regression, single label, and multi label classification problem types', 'initialize an EncT5Tokenizer instance with a vocab file and custom special tokens', 'build model inputs by wrapping token sequences with bos and eos special tokens', 'get a binary mask identifying special tokens versus regular tokens in a sequence', 'create token type ids for single or paired sequences with special tokens', 'review the EncT5Tokenizer class that extends T5Tokenizer with custom special token handling']
```

Usage

```
{'init_EncT5Tokenizer': 'initialize an EncT5Tokenizer instance with a vocab file and custom special tokens', 'build_inputs_with_special_tokens': 'build model inputs by wrapping token sequences with bos and eos special tokens', 'get_special_tokens_mask': 'get a binary mask identifying special tokens versus regular tokens in a sequence', 'create_token_type_ids_from_sequences': 'create token type ids for single or paired sequences with special tokens', 'review_EncT5Tokenizer': 'review the EncT5Tokenizer class that extends T5Tokenizer with custom special token handling'}
```

