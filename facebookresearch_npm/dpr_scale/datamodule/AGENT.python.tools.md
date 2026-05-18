# Agent Python Tools

- repo: facebookresearch/npm
- repo_uri: https://github.com/facebookresearch/npm

## File: facebookresearch_npm/dpr_scale/datamodule/corpus.py

Prompts

```
['create a CorpusDataModule instance with train, val, and test data paths for DPR scale training', 'build a PyTorch DataLoader for training corpus data with custom collate function and batch size', 'build a PyTorch DataLoader for validation corpus data with custom collate function and batch size', 'build a PyTorch DataLoader for test corpus data with custom collate function and batch size', 'collate a batch of corpus samples into input_ids, attention_mask, and is_valid tensors', 'create a LanguageModelingJsonlDataModule instance with train, val, and test JSONL data paths for language modeling', 'review the LanguageModelingJsonlDataModule collate method that delegates batch processing to LanguageModelingTransform by stage', 'create a MemoryMappedDataset from a file path to efficiently read large text files using memory mapping', 'initialize a memory-mapped file with optional header skipping and line count limits using _initialize', 'create a CorpusDataset from numpy arrays to load tokenized input IDs with block indexing and attention masks', 'get a padded sequence item with input_ids, attention_mask, and is_valid from a CorpusDataset by index', 'process a raw line from a MemoryMappedDataset or CorpusDataset by overriding the process_line method']
```

Usage

```
{'create_corpus_datamodule': 'create a CorpusDataModule instance with train, val, and test data paths for DPR scale training', 'build_train_dataloader': 'build a PyTorch DataLoader for training corpus data with custom collate function and batch size', 'build_val_dataloader': 'build a PyTorch DataLoader for validation corpus data with custom collate function and batch size', 'build_test_dataloader': 'build a PyTorch DataLoader for test corpus data with custom collate function and batch size', 'collate_batch': 'collate a batch of corpus samples into input_ids, attention_mask, and is_valid tensors'}
```

## File: facebookresearch_npm/dpr_scale/datamodule/lm.py

Prompts

```
['create a CorpusDataModule instance with train, val, and test data paths for DPR scale training', 'build a PyTorch DataLoader for training corpus data with custom collate function and batch size', 'build a PyTorch DataLoader for validation corpus data with custom collate function and batch size', 'build a PyTorch DataLoader for test corpus data with custom collate function and batch size', 'collate a batch of corpus samples into input_ids, attention_mask, and is_valid tensors', 'create a LanguageModelingJsonlDataModule instance with train, val, and test JSONL data paths for language modeling', 'review the LanguageModelingJsonlDataModule collate method that delegates batch processing to LanguageModelingTransform by stage', 'create a MemoryMappedDataset from a file path to efficiently read large text files using memory mapping', 'initialize a memory-mapped file with optional header skipping and line count limits using _initialize', 'create a CorpusDataset from numpy arrays to load tokenized input IDs with block indexing and attention masks', 'get a padded sequence item with input_ids, attention_mask, and is_valid from a CorpusDataset by index', 'process a raw line from a MemoryMappedDataset or CorpusDataset by overriding the process_line method']
```

Usage

```
{'create_LanguageModelingJsonlDataModule': 'create a LanguageModelingJsonlDataModule instance with train, val, and test JSONL data paths for language modeling', 'build_train_dataloader': 'build a training DataLoader with distributed sampling support from the LanguageModelingJsonlDataModule train dataset', 'build_val_dataloader': 'build a validation DataLoader from the LanguageModelingJsonlDataModule with no shuffling and eval collation', 'build_test_dataloader': 'build a test DataLoader from the LanguageModelingJsonlDataModule with no shuffling and test collation', 'review_collate': 'review the LanguageModelingJsonlDataModule collate method that delegates batch processing to LanguageModelingTransform by stage'}
```

## File: facebookresearch_npm/dpr_scale/datamodule/utils.py

Prompts

```
['create a CorpusDataModule instance with train, val, and test data paths for DPR scale training', 'build a PyTorch DataLoader for training corpus data with custom collate function and batch size', 'build a PyTorch DataLoader for validation corpus data with custom collate function and batch size', 'build a PyTorch DataLoader for test corpus data with custom collate function and batch size', 'collate a batch of corpus samples into input_ids, attention_mask, and is_valid tensors', 'create a LanguageModelingJsonlDataModule instance with train, val, and test JSONL data paths for language modeling', 'review the LanguageModelingJsonlDataModule collate method that delegates batch processing to LanguageModelingTransform by stage', 'create a MemoryMappedDataset from a file path to efficiently read large text files using memory mapping', 'initialize a memory-mapped file with optional header skipping and line count limits using _initialize', 'create a CorpusDataset from numpy arrays to load tokenized input IDs with block indexing and attention masks', 'get a padded sequence item with input_ids, attention_mask, and is_valid from a CorpusDataset by index', 'process a raw line from a MemoryMappedDataset or CorpusDataset by overriding the process_line method']
```

Usage

```
{'create_memory_mapped_dataset': 'create a MemoryMappedDataset from a file path to efficiently read large text files using memory mapping', 'initialize_memory_map': 'initialize a memory-mapped file with optional header skipping and line count limits using _initialize', 'create_corpus_dataset': 'create a CorpusDataset from numpy arrays to load tokenized input IDs with block indexing and attention masks', 'get_corpus_item': 'get a padded sequence item with input_ids, attention_mask, and is_valid from a CorpusDataset by index', 'process_dataset_line': 'process a raw line from a MemoryMappedDataset or CorpusDataset by overriding the process_line method'}
```

