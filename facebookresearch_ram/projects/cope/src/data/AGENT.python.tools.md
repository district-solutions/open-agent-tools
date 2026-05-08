# Agent Python Tools

- repo: facebookresearch/ram
- repo_uri: https://github.com/facebookresearch/ram

## File: facebookresearch_ram/projects/cope/src/data/data_collator.py

Prompts

```
['create a DataCollatorForDecoder instance with a config, tokenizer, and fixed sequence length', 'pad encoded sequences and their token types to a uniform length for batching', 'collate a batch of context-question-answer instances into decoder input and target tensors', 'encode context, question, and answer text into token sequences with corresponding token type labels', 'shift encoded sequences right by one token to create decoder input and target pairs', 'create a SimpleDataset from a JSONL file path and config object for PyTorch data loading', 'create a SimpleDataset that loads JSON lines and joins list contexts into a single string', 'get train, validation, and test SimpleDataset objects from a config with data file paths', 'review the SimpleDataset class that extends PyTorch Dataset for JSONL data loading with context joining', 'refactor the get_data function to support additional data splits beyond train, val, and test', 'encode a text string into a list of word indices using SimpleTokenizer', 'decode a list of word indices back into words using SimpleTokenizer', 'build a vocabulary from train, validation, and test data samples using SimpleTokenizer', 'add a new word to the SimpleTokenizer vocabulary with an auto-assigned index', 'get a SimpleTokenizer instance from a config using the get_tokenizer factory function']
```

Usage

```
{'create_decoder_data_collator': 'create a DataCollatorForDecoder instance with a config, tokenizer, and fixed sequence length', 'pad_right_sequences': 'pad encoded sequences and their token types to a uniform length for batching', 'collate_instances_for_decoder': 'collate a batch of context-question-answer instances into decoder input and target tensors', 'encode_context_question_answer': 'encode context, question, and answer text into token sequences with corresponding token type labels', 'shift_decoder_targets': 'shift encoded sequences right by one token to create decoder input and target pairs'}
```

## File: facebookresearch_ram/projects/cope/src/data/simple.py

Prompts

```
['create a DataCollatorForDecoder instance with a config, tokenizer, and fixed sequence length', 'pad encoded sequences and their token types to a uniform length for batching', 'collate a batch of context-question-answer instances into decoder input and target tensors', 'encode context, question, and answer text into token sequences with corresponding token type labels', 'shift encoded sequences right by one token to create decoder input and target pairs', 'create a SimpleDataset from a JSONL file path and config object for PyTorch data loading', 'create a SimpleDataset that loads JSON lines and joins list contexts into a single string', 'get train, validation, and test SimpleDataset objects from a config with data file paths', 'review the SimpleDataset class that extends PyTorch Dataset for JSONL data loading with context joining', 'refactor the get_data function to support additional data splits beyond train, val, and test', 'encode a text string into a list of word indices using SimpleTokenizer', 'decode a list of word indices back into words using SimpleTokenizer', 'build a vocabulary from train, validation, and test data samples using SimpleTokenizer', 'add a new word to the SimpleTokenizer vocabulary with an auto-assigned index', 'get a SimpleTokenizer instance from a config using the get_tokenizer factory function']
```

Usage

```
{'create_simple_dataset': 'create a SimpleDataset from a JSONL file path and config object for PyTorch data loading', 'create_simple_dataset_from_jsonl': 'create a SimpleDataset that loads JSON lines and joins list contexts into a single string', 'get_data_train_val_test': 'get train, validation, and test SimpleDataset objects from a config with data file paths', 'review_simple_dataset_class': 'review the SimpleDataset class that extends PyTorch Dataset for JSONL data loading with context joining', 'refactor_get_data': 'refactor the get_data function to support additional data splits beyond train, val, and test'}
```

## File: facebookresearch_ram/projects/cope/src/data/tokenizer.py

Prompts

```
['create a DataCollatorForDecoder instance with a config, tokenizer, and fixed sequence length', 'pad encoded sequences and their token types to a uniform length for batching', 'collate a batch of context-question-answer instances into decoder input and target tensors', 'encode context, question, and answer text into token sequences with corresponding token type labels', 'shift encoded sequences right by one token to create decoder input and target pairs', 'create a SimpleDataset from a JSONL file path and config object for PyTorch data loading', 'create a SimpleDataset that loads JSON lines and joins list contexts into a single string', 'get train, validation, and test SimpleDataset objects from a config with data file paths', 'review the SimpleDataset class that extends PyTorch Dataset for JSONL data loading with context joining', 'refactor the get_data function to support additional data splits beyond train, val, and test', 'encode a text string into a list of word indices using SimpleTokenizer', 'decode a list of word indices back into words using SimpleTokenizer', 'build a vocabulary from train, validation, and test data samples using SimpleTokenizer', 'add a new word to the SimpleTokenizer vocabulary with an auto-assigned index', 'get a SimpleTokenizer instance from a config using the get_tokenizer factory function']
```

Usage

```
{'encode_text_to_indices': 'encode a text string into a list of word indices using SimpleTokenizer', 'decode_indices_to_words': 'decode a list of word indices back into words using SimpleTokenizer', 'build_vocabulary_from_data': 'build a vocabulary from train, validation, and test data samples using SimpleTokenizer', 'add_word_to_vocab': 'add a new word to the SimpleTokenizer vocabulary with an auto-assigned index', 'get_tokenizer_from_config': 'get a SimpleTokenizer instance from a config using the get_tokenizer factory function'}
```

