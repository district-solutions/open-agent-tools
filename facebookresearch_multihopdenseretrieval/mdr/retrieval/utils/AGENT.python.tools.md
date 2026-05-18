# Agent Python Tools

- repo: facebookresearch/multihopdenseretrieval
- repo_uri: https://github.com/facebookresearch/multihop_dense_retrieval

## File: facebookresearch_multihopdenseretrieval/mdr/retrieval/utils/basic_tokenizer.py

Prompts

```
['create a python module that uses RegexpTokenizer to tokenize text into tokens with whitespace and span info', 'create a python module that uses SimpleTokenizer to tokenize text into basic alphanumeric and non-whitespace tokens', 'build a python script that extracts n-grams from tokenized text using the Tokens ngrams method', 'create a function that filters out English stopwords and punctuation using filter_word and filter_ngram', 'build a python module that normalizes unicode text encodings using the normalize function', 'pick the bridge passage title between two candidates using answer presence and link structure', 'normalize an answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'add sentence-level supervision labels to retrieved HotpotQA results using original supporting facts', 'load annotated Wikipedia abstracts and return title-to-document and title-to-linked mappings', 'explore question decomposition data from the BREAK dataset and align it with HotpotQA entries', 'create a BasicTokenizer instance and tokenize a piece of text with lowercasing and accent stripping', 'convert a list of tokens into their corresponding vocabulary IDs using convert_tokens_to_ids', 'split a string into tokens by whitespace using the whitespace_tokenize function', 'use BasicTokenizer _run_strip_accents to remove diacritical marks from Unicode text', 'use BasicTokenizer _run_split_on_punc to split text into tokens at punctuation boundaries', "load a PyTorch model's saved state dict from a file path and apply it to the model", 'recursively move all PyTorch tensors in a nested dict or list sample to CUDA device', 'recursively convert all FloatTensor tensors in a nested dict or list sample to half precision', 'fetch the raw text of a document by its ID from a SQLite-backed document database', 'check if a paragraph contains any of the given answers using tokenized exact match']
```

Usage

```
{'tokenize_text_with_regexp': 'create a python module that uses RegexpTokenizer to tokenize text into tokens with whitespace and span info', 'tokenize_text_with_simple': 'create a python module that uses SimpleTokenizer to tokenize text into basic alphanumeric and non-whitespace tokens', 'extract_ngrams_from_tokens': 'build a python script that extracts n-grams from tokenized text using the Tokens ngrams method', 'filter_stopwords_and_punctuation': 'create a function that filters out English stopwords and punctuation using filter_word and filter_ngram', 'normalize_unicode_text': 'build a python module that normalizes unicode text encodings using the normalize function'}
```

## File: facebookresearch_multihopdenseretrieval/mdr/retrieval/utils/mhop_utils.py

Prompts

```
['create a python module that uses RegexpTokenizer to tokenize text into tokens with whitespace and span info', 'create a python module that uses SimpleTokenizer to tokenize text into basic alphanumeric and non-whitespace tokens', 'build a python script that extracts n-grams from tokenized text using the Tokens ngrams method', 'create a function that filters out English stopwords and punctuation using filter_word and filter_ngram', 'build a python module that normalizes unicode text encodings using the normalize function', 'pick the bridge passage title between two candidates using answer presence and link structure', 'normalize an answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'add sentence-level supervision labels to retrieved HotpotQA results using original supporting facts', 'load annotated Wikipedia abstracts and return title-to-document and title-to-linked mappings', 'explore question decomposition data from the BREAK dataset and align it with HotpotQA entries', 'create a BasicTokenizer instance and tokenize a piece of text with lowercasing and accent stripping', 'convert a list of tokens into their corresponding vocabulary IDs using convert_tokens_to_ids', 'split a string into tokens by whitespace using the whitespace_tokenize function', 'use BasicTokenizer _run_strip_accents to remove diacritical marks from Unicode text', 'use BasicTokenizer _run_split_on_punc to split text into tokens at punctuation boundaries', "load a PyTorch model's saved state dict from a file path and apply it to the model", 'recursively move all PyTorch tensors in a nested dict or list sample to CUDA device', 'recursively convert all FloatTensor tensors in a nested dict or list sample to half precision', 'fetch the raw text of a document by its ID from a SQLite-backed document database', 'check if a paragraph contains any of the given answers using tokenized exact match']
```

Usage

```
{'pick_bridge_v0': 'pick the bridge passage title between two candidates using answer presence and link structure', 'normalize_answer': 'normalize an answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'add_sp_labels': 'add sentence-level supervision labels to retrieved HotpotQA results using original supporting facts', 'load_annotated': 'load annotated Wikipedia abstracts and return title-to-document and title-to-linked mappings', 'explore_QDMR': 'explore question decomposition data from the BREAK dataset and align it with HotpotQA entries'}
```

## File: facebookresearch_multihopdenseretrieval/mdr/retrieval/utils/tokenizer.py

Prompts

```
['create a python module that uses RegexpTokenizer to tokenize text into tokens with whitespace and span info', 'create a python module that uses SimpleTokenizer to tokenize text into basic alphanumeric and non-whitespace tokens', 'build a python script that extracts n-grams from tokenized text using the Tokens ngrams method', 'create a function that filters out English stopwords and punctuation using filter_word and filter_ngram', 'build a python module that normalizes unicode text encodings using the normalize function', 'pick the bridge passage title between two candidates using answer presence and link structure', 'normalize an answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'add sentence-level supervision labels to retrieved HotpotQA results using original supporting facts', 'load annotated Wikipedia abstracts and return title-to-document and title-to-linked mappings', 'explore question decomposition data from the BREAK dataset and align it with HotpotQA entries', 'create a BasicTokenizer instance and tokenize a piece of text with lowercasing and accent stripping', 'convert a list of tokens into their corresponding vocabulary IDs using convert_tokens_to_ids', 'split a string into tokens by whitespace using the whitespace_tokenize function', 'use BasicTokenizer _run_strip_accents to remove diacritical marks from Unicode text', 'use BasicTokenizer _run_split_on_punc to split text into tokens at punctuation boundaries', "load a PyTorch model's saved state dict from a file path and apply it to the model", 'recursively move all PyTorch tensors in a nested dict or list sample to CUDA device', 'recursively convert all FloatTensor tensors in a nested dict or list sample to half precision', 'fetch the raw text of a document by its ID from a SQLite-backed document database', 'check if a paragraph contains any of the given answers using tokenized exact match']
```

Usage

```
{'tokenize_text_with_basic_tokenizer': 'create a BasicTokenizer instance and tokenize a piece of text with lowercasing and accent stripping', 'convert_tokens_to_ids': 'convert a list of tokens into their corresponding vocabulary IDs using convert_tokens_to_ids', 'whitespace_tokenize_text': 'split a string into tokens by whitespace using the whitespace_tokenize function', 'strip_accents_from_text': 'use BasicTokenizer _run_strip_accents to remove diacritical marks from Unicode text', 'split_text_on_punctuation': 'use BasicTokenizer _run_split_on_punc to split text into tokens at punctuation boundaries'}
```

## File: facebookresearch_multihopdenseretrieval/mdr/retrieval/utils/utils.py

Prompts

```
['create a python module that uses RegexpTokenizer to tokenize text into tokens with whitespace and span info', 'create a python module that uses SimpleTokenizer to tokenize text into basic alphanumeric and non-whitespace tokens', 'build a python script that extracts n-grams from tokenized text using the Tokens ngrams method', 'create a function that filters out English stopwords and punctuation using filter_word and filter_ngram', 'build a python module that normalizes unicode text encodings using the normalize function', 'pick the bridge passage title between two candidates using answer presence and link structure', 'normalize an answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'add sentence-level supervision labels to retrieved HotpotQA results using original supporting facts', 'load annotated Wikipedia abstracts and return title-to-document and title-to-linked mappings', 'explore question decomposition data from the BREAK dataset and align it with HotpotQA entries', 'create a BasicTokenizer instance and tokenize a piece of text with lowercasing and accent stripping', 'convert a list of tokens into their corresponding vocabulary IDs using convert_tokens_to_ids', 'split a string into tokens by whitespace using the whitespace_tokenize function', 'use BasicTokenizer _run_strip_accents to remove diacritical marks from Unicode text', 'use BasicTokenizer _run_split_on_punc to split text into tokens at punctuation boundaries', "load a PyTorch model's saved state dict from a file path and apply it to the model", 'recursively move all PyTorch tensors in a nested dict or list sample to CUDA device', 'recursively convert all FloatTensor tensors in a nested dict or list sample to half precision', 'fetch the raw text of a document by its ID from a SQLite-backed document database', 'check if a paragraph contains any of the given answers using tokenized exact match']
```

Usage

```
{'load_saved_model': "load a PyTorch model's saved state dict from a file path and apply it to the model", 'move_tensors_to_cuda': 'recursively move all PyTorch tensors in a nested dict or list sample to CUDA device', 'convert_tensors_to_half': 'recursively convert all FloatTensor tensors in a nested dict or list sample to half precision', 'query_doc_text_from_sqlite': 'fetch the raw text of a document by its ID from a SQLite-backed document database', 'check_paragraph_has_answer': 'check if a paragraph contains any of the given answers using tokenized exact match'}
```

