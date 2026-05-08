# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/model/src/data/dataset.py

Prompts

```
['create a StreamDataset to prepare BPTT batches from tokenized sentences for language model training', 'create a Dataset to manage tokenized sentences with batching, filtering, and iterator support', 'create a ParallelDataset to manage paired source-target sentence tensors for translation or span prediction tasks', 'get a batched sentences iterator from a Dataset with optional shuffling and size grouping', 'select a subset of sentences from a Dataset by index range for train-validation splitting', 'create a Dictionary by reading a vocabulary file with word counts using Dictionary.read_vocab', 'index text sentences into word IDs using Dictionary.index_data and save to a binary file', 'lookup the index of a word in the Dictionary using the index method with optional no_unk flag', 'limit the Dictionary vocabulary size to a maximum number of words using max_vocab', 'filter Dictionary words by minimum frequency count using min_count to remove rare tokens', 'load a binarized .pth dataset file and process it with vocabulary constraints and logging', 'process a binarized dataset dictionary to enforce max vocab size and log word statistics', 'load monolingual datasets for multiple languages with stream and batched dataset support', 'load parallel sentence datasets for language pairs with optional span prediction data', 'validate and parse all dataset parameters including language steps, training splits, and file paths']
```

Usage

```
{'create_StreamDataset': 'create a StreamDataset to prepare BPTT batches from tokenized sentences for language model training', 'create_Dataset': 'create a Dataset to manage tokenized sentences with batching, filtering, and iterator support', 'create_ParallelDataset': 'create a ParallelDataset to manage paired source-target sentence tensors for translation or span prediction tasks', 'get_iterator_Dataset': 'get a batched sentences iterator from a Dataset with optional shuffling and size grouping', 'select_data_Dataset': 'select a subset of sentences from a Dataset by index range for train-validation splitting'}
```

## File: facebookresearch_codegen/codegen_sources/model/src/data/dictionary.py

Prompts

```
['create a StreamDataset to prepare BPTT batches from tokenized sentences for language model training', 'create a Dataset to manage tokenized sentences with batching, filtering, and iterator support', 'create a ParallelDataset to manage paired source-target sentence tensors for translation or span prediction tasks', 'get a batched sentences iterator from a Dataset with optional shuffling and size grouping', 'select a subset of sentences from a Dataset by index range for train-validation splitting', 'create a Dictionary by reading a vocabulary file with word counts using Dictionary.read_vocab', 'index text sentences into word IDs using Dictionary.index_data and save to a binary file', 'lookup the index of a word in the Dictionary using the index method with optional no_unk flag', 'limit the Dictionary vocabulary size to a maximum number of words using max_vocab', 'filter Dictionary words by minimum frequency count using min_count to remove rare tokens', 'load a binarized .pth dataset file and process it with vocabulary constraints and logging', 'process a binarized dataset dictionary to enforce max vocab size and log word statistics', 'load monolingual datasets for multiple languages with stream and batched dataset support', 'load parallel sentence datasets for language pairs with optional span prediction data', 'validate and parse all dataset parameters including language steps, training splits, and file paths']
```

Usage

```
{'create_dictionary_from_vocab_file': 'create a Dictionary by reading a vocabulary file with word counts using Dictionary.read_vocab', 'index_sentences_with_dictionary': 'index text sentences into word IDs using Dictionary.index_data and save to a binary file', 'lookup_word_index': 'lookup the index of a word in the Dictionary using the index method with optional no_unk flag', 'limit_vocabulary_size': 'limit the Dictionary vocabulary size to a maximum number of words using max_vocab', 'filter_words_by_min_count': 'filter Dictionary words by minimum frequency count using min_count to remove rare tokens'}
```

## File: facebookresearch_codegen/codegen_sources/model/src/data/loader.py

Prompts

```
['create a StreamDataset to prepare BPTT batches from tokenized sentences for language model training', 'create a Dataset to manage tokenized sentences with batching, filtering, and iterator support', 'create a ParallelDataset to manage paired source-target sentence tensors for translation or span prediction tasks', 'get a batched sentences iterator from a Dataset with optional shuffling and size grouping', 'select a subset of sentences from a Dataset by index range for train-validation splitting', 'create a Dictionary by reading a vocabulary file with word counts using Dictionary.read_vocab', 'index text sentences into word IDs using Dictionary.index_data and save to a binary file', 'lookup the index of a word in the Dictionary using the index method with optional no_unk flag', 'limit the Dictionary vocabulary size to a maximum number of words using max_vocab', 'filter Dictionary words by minimum frequency count using min_count to remove rare tokens', 'load a binarized .pth dataset file and process it with vocabulary constraints and logging', 'process a binarized dataset dictionary to enforce max vocab size and log word statistics', 'load monolingual datasets for multiple languages with stream and batched dataset support', 'load parallel sentence datasets for language pairs with optional span prediction data', 'validate and parse all dataset parameters including language steps, training splits, and file paths']
```

Usage

```
{'load_binarized_dataset': 'load a binarized .pth dataset file and process it with vocabulary constraints and logging', 'process_binarized_data': 'process a binarized dataset dictionary to enforce max vocab size and log word statistics', 'load_monolingual_data': 'load monolingual datasets for multiple languages with stream and batched dataset support', 'load_parallel_data': 'load parallel sentence datasets for language pairs with optional span prediction data', 'check_data_params': 'validate and parse all dataset parameters including language steps, training splits, and file paths'}
```

