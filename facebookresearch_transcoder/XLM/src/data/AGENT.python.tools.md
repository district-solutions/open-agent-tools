# Agent Python Tools

- repo: facebookresearch/transcoder
- repo_uri: https://github.com/facebookresearch/transcoder

## File: facebookresearch_transcoder/XLM/src/data/dataset.py

Prompts

```
['create a StreamDataset to prepare fixed-length BPTT batches from tokenized sentences for language model training', 'create a Dataset to manage sentence-level batching with padding, EOS markers, and length-based grouping for NLP training', 'create a ParallelDataset to manage paired sentence batching for machine translation or cross-lingual training tasks', 'get an iterator from Dataset that yields shuffled batches grouped by sentence length with configurable tokens per batch', 'remove sentences exceeding a maximum length threshold from a Dataset or ParallelDataset to filter outliers', 'create a Dictionary by reading words and counts from a vocabulary file using read_vocab', 'index sentences from a text file into word IDs using index_data with a Dictionary', 'limit the dictionary vocabulary to a maximum number of words using max_vocab', 'filter out low-frequency words from the dictionary using min_count threshold', 'lookup the index of a word in the dictionary using the index method', 'load a binarized .pth dataset file and process it with vocabulary constraints', 'process a binarized dataset by applying max vocab and min count filters', 'load monolingual datasets for specified languages and create stream and batched datasets', 'load parallel datasets for source-target language pairs and create parallel datasets', 'validate dataset parameters including language configs, CLM steps, MLM steps, and MT steps']
```

Usage

```
{'create_stream_dataset': 'create a StreamDataset to prepare fixed-length BPTT batches from tokenized sentences for language model training', 'create_dataset': 'create a Dataset to manage sentence-level batching with padding, EOS markers, and length-based grouping for NLP training', 'create_parallel_dataset': 'create a ParallelDataset to manage paired sentence batching for machine translation or cross-lingual training tasks', 'get_iterator_dataset': 'get an iterator from Dataset that yields shuffled batches grouped by sentence length with configurable tokens per batch', 'remove_long_sentences': 'remove sentences exceeding a maximum length threshold from a Dataset or ParallelDataset to filter outliers'}
```

## File: facebookresearch_transcoder/XLM/src/data/dictionary.py

Prompts

```
['create a StreamDataset to prepare fixed-length BPTT batches from tokenized sentences for language model training', 'create a Dataset to manage sentence-level batching with padding, EOS markers, and length-based grouping for NLP training', 'create a ParallelDataset to manage paired sentence batching for machine translation or cross-lingual training tasks', 'get an iterator from Dataset that yields shuffled batches grouped by sentence length with configurable tokens per batch', 'remove sentences exceeding a maximum length threshold from a Dataset or ParallelDataset to filter outliers', 'create a Dictionary by reading words and counts from a vocabulary file using read_vocab', 'index sentences from a text file into word IDs using index_data with a Dictionary', 'limit the dictionary vocabulary to a maximum number of words using max_vocab', 'filter out low-frequency words from the dictionary using min_count threshold', 'lookup the index of a word in the dictionary using the index method', 'load a binarized .pth dataset file and process it with vocabulary constraints', 'process a binarized dataset by applying max vocab and min count filters', 'load monolingual datasets for specified languages and create stream and batched datasets', 'load parallel datasets for source-target language pairs and create parallel datasets', 'validate dataset parameters including language configs, CLM steps, MLM steps, and MT steps']
```

Usage

```
{'create_dictionary_from_vocab_file': 'create a Dictionary by reading words and counts from a vocabulary file using read_vocab', 'index_text_data_with_dictionary': 'index sentences from a text file into word IDs using index_data with a Dictionary', 'limit_dictionary_vocabulary_size': 'limit the dictionary vocabulary to a maximum number of words using max_vocab', 'filter_words_by_min_count': 'filter out low-frequency words from the dictionary using min_count threshold', 'lookup_word_index_in_dictionary': 'lookup the index of a word in the dictionary using the index method'}
```

## File: facebookresearch_transcoder/XLM/src/data/loader.py

Prompts

```
['create a StreamDataset to prepare fixed-length BPTT batches from tokenized sentences for language model training', 'create a Dataset to manage sentence-level batching with padding, EOS markers, and length-based grouping for NLP training', 'create a ParallelDataset to manage paired sentence batching for machine translation or cross-lingual training tasks', 'get an iterator from Dataset that yields shuffled batches grouped by sentence length with configurable tokens per batch', 'remove sentences exceeding a maximum length threshold from a Dataset or ParallelDataset to filter outliers', 'create a Dictionary by reading words and counts from a vocabulary file using read_vocab', 'index sentences from a text file into word IDs using index_data with a Dictionary', 'limit the dictionary vocabulary to a maximum number of words using max_vocab', 'filter out low-frequency words from the dictionary using min_count threshold', 'lookup the index of a word in the dictionary using the index method', 'load a binarized .pth dataset file and process it with vocabulary constraints', 'process a binarized dataset by applying max vocab and min count filters', 'load monolingual datasets for specified languages and create stream and batched datasets', 'load parallel datasets for source-target language pairs and create parallel datasets', 'validate dataset parameters including language configs, CLM steps, MLM steps, and MT steps']
```

Usage

```
{'load_binarized_dataset': 'load a binarized .pth dataset file and process it with vocabulary constraints', 'process_binarized_data': 'process a binarized dataset by applying max vocab and min count filters', 'load_mono_data': 'load monolingual datasets for specified languages and create stream and batched datasets', 'load_para_data': 'load parallel datasets for source-target language pairs and create parallel datasets', 'check_data_params': 'validate dataset parameters including language configs, CLM steps, MLM steps, and MT steps'}
```

