# Agent Python Tools

- repo: facebookresearch/anli
- repo_uri: https://github.com/facebookresearch/anli

## File: facebookresearch_anli/src/flint/data_utils/batchbuilder.py

Prompts

```
['build a BaseBatchBuilder with a batching schema dict to batch a list of sample dicts', 'run the BaseBatchBuilder on a batch of sample dicts to get batched data per field', 'test the has_tensor function to check if a nested dict or list contains any torch tensors', 'run move_to_device to recursively move all torch tensors in a nested structure to a GPU', 'review the BaseBatchBuilder class and its batching schema logic for handling unknown fields with RawFlintField', 'create a RawFlintField to pass batched data through unchanged without transformation', 'create a LabelFlintField to convert batched label data into a PyTorch tensor', 'create an ArrayIndexFlintField with pad_idx and eos_idx for token sequence padding', 'use ArrayIndexFlintField collate_tokens to convert a list of 1d tensors into a padded 2d tensor', 'use ArrayIndexFlintField batching to pad and collate token sequences with left or right padding']
```

Usage

```
{'build_BaseBatchBuilder': 'build a BaseBatchBuilder with a batching schema dict to batch a list of sample dicts', 'run_BaseBatchBuilder_call': 'run the BaseBatchBuilder on a batch of sample dicts to get batched data per field', 'test_has_tensor': 'test the has_tensor function to check if a nested dict or list contains any torch tensors', 'run_move_to_device': 'run move_to_device to recursively move all torch tensors in a nested structure to a GPU', 'review_BaseBatchBuilder_schema': 'review the BaseBatchBuilder class and its batching schema logic for handling unknown fields with RawFlintField'}
```

## File: facebookresearch_anli/src/flint/data_utils/fields.py

Prompts

```
['build a BaseBatchBuilder with a batching schema dict to batch a list of sample dicts', 'run the BaseBatchBuilder on a batch of sample dicts to get batched data per field', 'test the has_tensor function to check if a nested dict or list contains any torch tensors', 'run move_to_device to recursively move all torch tensors in a nested structure to a GPU', 'review the BaseBatchBuilder class and its batching schema logic for handling unknown fields with RawFlintField', 'create a RawFlintField to pass batched data through unchanged without transformation', 'create a LabelFlintField to convert batched label data into a PyTorch tensor', 'create an ArrayIndexFlintField with pad_idx and eos_idx for token sequence padding', 'use ArrayIndexFlintField collate_tokens to convert a list of 1d tensors into a padded 2d tensor', 'use ArrayIndexFlintField batching to pad and collate token sequences with left or right padding']
```

Usage

```
{'create_raw_field_batching': 'create a RawFlintField to pass batched data through unchanged without transformation', 'create_label_field_batching': 'create a LabelFlintField to convert batched label data into a PyTorch tensor', 'create_array_index_field': 'create an ArrayIndexFlintField with pad_idx and eos_idx for token sequence padding', 'collate_tokens_to_padded_tensor': 'use ArrayIndexFlintField collate_tokens to convert a list of 1d tensors into a padded 2d tensor', 'batch_token_sequences_with_padding': 'use ArrayIndexFlintField batching to pad and collate token sequences with left or right padding'}
```

