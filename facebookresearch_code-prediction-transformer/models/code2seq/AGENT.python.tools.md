# Agent Python Tools

- repo: facebookresearch/code-prediction-transformer
- repo_uri: https://github.com/facebookresearch/code-prediction-transformer

## File: facebookresearch_code-prediction-transformer/models/code2seq/dataset.py

Prompts

```
['create a PyTorch Dataset instance from a JSONL file path for code2seq model training', 'use the Dataset __getitem__ method to load a single JSON data point by index', 'use the Dataset __len__ method to get the total number of data points in the file', 'run the Dataset collate static method to pad and stack a batch into PyTorch tensors', 'review the Dataset class that provides efficient random-access loading of JSONL data for code2seq', 'run generate_vocab.py to build a token vocabulary from a JSONL dataset for the code2seq model', 'run generate_vocab.py with subtoken mode to tokenize terminal nodes and build a vocabulary pickle file', 'run generate_vocab.py with output mode to extract terminal nodes as the vocabulary from a JSONL input', 'create a function that extracts vocabulary items from a parsed JSON line using token, subtoken, or output mode', 'refactor get_value to support a new vocab_type that combines token and subtoken extraction strategies']
```

Usage

```
{'create_Dataset': 'create a PyTorch Dataset instance from a JSONL file path for code2seq model training', 'use_Dataset_getitem': 'use the Dataset __getitem__ method to load a single JSON data point by index', 'use_Dataset_len': 'use the Dataset __len__ method to get the total number of data points in the file', 'run_Dataset_collate': 'run the Dataset collate static method to pad and stack a batch into PyTorch tensors', 'review_Dataset_class': 'review the Dataset class that provides efficient random-access loading of JSONL data for code2seq'}
```

## File: facebookresearch_code-prediction-transformer/models/code2seq/generate_vocab.py

Prompts

```
['create a PyTorch Dataset instance from a JSONL file path for code2seq model training', 'use the Dataset __getitem__ method to load a single JSON data point by index', 'use the Dataset __len__ method to get the total number of data points in the file', 'run the Dataset collate static method to pad and stack a batch into PyTorch tensors', 'review the Dataset class that provides efficient random-access loading of JSONL data for code2seq', 'run generate_vocab.py to build a token vocabulary from a JSONL dataset for the code2seq model', 'run generate_vocab.py with subtoken mode to tokenize terminal nodes and build a vocabulary pickle file', 'run generate_vocab.py with output mode to extract terminal nodes as the vocabulary from a JSONL input', 'create a function that extracts vocabulary items from a parsed JSON line using token, subtoken, or output mode', 'refactor get_value to support a new vocab_type that combines token and subtoken extraction strategies']
```

Usage

```
{'run_generate_vocab_token': 'run generate_vocab.py to build a token vocabulary from a JSONL dataset for the code2seq model', 'run_generate_vocab_subtoken': 'run generate_vocab.py with subtoken mode to tokenize terminal nodes and build a vocabulary pickle file', 'run_generate_vocab_output': 'run generate_vocab.py with output mode to extract terminal nodes as the vocabulary from a JSONL input', 'create_get_value_function': 'create a function that extracts vocabulary items from a parsed JSON line using token, subtoken, or output mode', 'refactor_get_value_subtoken': 'refactor get_value to support a new vocab_type that combines token and subtoken extraction strategies'}
```

