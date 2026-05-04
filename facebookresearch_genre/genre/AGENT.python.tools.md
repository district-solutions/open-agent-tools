# Agent Python Tools

- repo: facebookresearch/genre
- repo_uri: https://github.com/facebookresearch/genre

## File: facebookresearch_genre/genre/entity_linking.py

Prompts

```
['build a HuggingFace prefix allowed tokens function for end-to-end entity linking with mention and entity trigrams', 'build a Fairseq prefix allowed tokens function for end-to-end entity linking with mention and entity trigrams', 'create a prefix allowed tokens function using custom encode and decode functions for constrained entity linking generation', 'review the get_status helper to determine if generation is in outside, mention, or entity phase', 'review the get_pointer_end helper to track alignment between generated tokens and original sentence tokens', 'load a pretrained GENRE model from a model name or path using GENRE.from_pretrained', 'load a pretrained mGENRE model with sentencepiece BPE using mGENRE.from_pretrained', 'sample entity predictions from input sentences using the GENREHubInterface sample method with beam search', 'encode a sentence into a tokenized tensor using the GENREHubInterface encode method', 'generate batched hypotheses from tokenized sentences using the GENREHubInterface generate method', 'sample entity predictions for a list of sentences using beam search with configurable beams and return sequences', 'sample entity predictions and marginalize scores across multiple mentions using a text to ID mapping', 'create a Trie from a list of integer sequences for prefix-based token lookups', 'query a Trie with a prefix sequence to get valid next token candidates', 'build a MarisaTrie from integer sequences using marisa_trie for efficient prefix search', 'load a Trie instance from an existing trie dictionary using the load_from_dict static method', 'create a DummyTrieMention that always returns fixed values for mention token generation', 'split a list of items into N roughly equal sized chunks for parallel processing', 'batch a sequence of items into groups of a specified size for batched model inference', 'create a model input string with left context, mention delimiters, and right context', 'extract entity mention spans and linked Wikipedia titles from sentences using a HuggingFace model', 'parse a Wikipedia XML dump file into a dictionary of documents with paragraphs and anchor links']
```

Usage

```
{'build_hf_prefix_allowed_tokens_fn': 'build a HuggingFace prefix allowed tokens function for end-to-end entity linking with mention and entity trigrams', 'build_fairseq_prefix_allowed_tokens_fn': 'build a Fairseq prefix allowed tokens function for end-to-end entity linking with mention and entity trigrams', 'create_prefix_allowed_tokens_fn': 'create a prefix allowed tokens function using custom encode and decode functions for constrained entity linking generation', 'review_get_status': 'review the get_status helper to determine if generation is in outside, mention, or entity phase', 'review_get_pointer_end': 'review the get_pointer_end helper to track alignment between generated tokens and original sentence tokens'}
```

## File: facebookresearch_genre/genre/fairseq_model.py

Prompts

```
['build a HuggingFace prefix allowed tokens function for end-to-end entity linking with mention and entity trigrams', 'build a Fairseq prefix allowed tokens function for end-to-end entity linking with mention and entity trigrams', 'create a prefix allowed tokens function using custom encode and decode functions for constrained entity linking generation', 'review the get_status helper to determine if generation is in outside, mention, or entity phase', 'review the get_pointer_end helper to track alignment between generated tokens and original sentence tokens', 'load a pretrained GENRE model from a model name or path using GENRE.from_pretrained', 'load a pretrained mGENRE model with sentencepiece BPE using mGENRE.from_pretrained', 'sample entity predictions from input sentences using the GENREHubInterface sample method with beam search', 'encode a sentence into a tokenized tensor using the GENREHubInterface encode method', 'generate batched hypotheses from tokenized sentences using the GENREHubInterface generate method', 'sample entity predictions for a list of sentences using beam search with configurable beams and return sequences', 'sample entity predictions and marginalize scores across multiple mentions using a text to ID mapping', 'create a Trie from a list of integer sequences for prefix-based token lookups', 'query a Trie with a prefix sequence to get valid next token candidates', 'build a MarisaTrie from integer sequences using marisa_trie for efficient prefix search', 'load a Trie instance from an existing trie dictionary using the load_from_dict static method', 'create a DummyTrieMention that always returns fixed values for mention token generation', 'split a list of items into N roughly equal sized chunks for parallel processing', 'batch a sequence of items into groups of a specified size for batched model inference', 'create a model input string with left context, mention delimiters, and right context', 'extract entity mention spans and linked Wikipedia titles from sentences using a HuggingFace model', 'parse a Wikipedia XML dump file into a dictionary of documents with paragraphs and anchor links']
```

Usage

```
{'load_GENRE_model': 'load a pretrained GENRE model from a model name or path using GENRE.from_pretrained', 'load_mGENRE_model': 'load a pretrained mGENRE model with sentencepiece BPE using mGENRE.from_pretrained', 'sample_entity_predictions': 'sample entity predictions from input sentences using the GENREHubInterface sample method with beam search', 'encode_sentence': 'encode a sentence into a tokenized tensor using the GENREHubInterface encode method', 'generate_hypotheses': 'generate batched hypotheses from tokenized sentences using the GENREHubInterface generate method'}
```

## File: facebookresearch_genre/genre/hf_model.py

Prompts

```
['build a HuggingFace prefix allowed tokens function for end-to-end entity linking with mention and entity trigrams', 'build a Fairseq prefix allowed tokens function for end-to-end entity linking with mention and entity trigrams', 'create a prefix allowed tokens function using custom encode and decode functions for constrained entity linking generation', 'review the get_status helper to determine if generation is in outside, mention, or entity phase', 'review the get_pointer_end helper to track alignment between generated tokens and original sentence tokens', 'load a pretrained GENRE model from a model name or path using GENRE.from_pretrained', 'load a pretrained mGENRE model with sentencepiece BPE using mGENRE.from_pretrained', 'sample entity predictions from input sentences using the GENREHubInterface sample method with beam search', 'encode a sentence into a tokenized tensor using the GENREHubInterface encode method', 'generate batched hypotheses from tokenized sentences using the GENREHubInterface generate method', 'sample entity predictions for a list of sentences using beam search with configurable beams and return sequences', 'sample entity predictions and marginalize scores across multiple mentions using a text to ID mapping', 'create a Trie from a list of integer sequences for prefix-based token lookups', 'query a Trie with a prefix sequence to get valid next token candidates', 'build a MarisaTrie from integer sequences using marisa_trie for efficient prefix search', 'load a Trie instance from an existing trie dictionary using the load_from_dict static method', 'create a DummyTrieMention that always returns fixed values for mention token generation', 'split a list of items into N roughly equal sized chunks for parallel processing', 'batch a sequence of items into groups of a specified size for batched model inference', 'create a model input string with left context, mention delimiters, and right context', 'extract entity mention spans and linked Wikipedia titles from sentences using a HuggingFace model', 'parse a Wikipedia XML dump file into a dictionary of documents with paragraphs and anchor links']
```

Usage

```
{'load_GENRE_model': 'load a pretrained GENRE entity linking model from a HuggingFace model name or local path', 'load_mGENRE_model': 'load a pretrained multilingual mGENRE model from a HuggingFace model name or local path', 'sample_entity_mentions': 'sample entity predictions for a list of sentences using beam search with configurable beams and return sequences', 'encode_sentence': "encode a single sentence into a token ID tensor using the model's tokenizer", 'sample_with_marginalization': 'sample entity predictions and marginalize scores across multiple mentions using a text to ID mapping'}
```

## File: facebookresearch_genre/genre/trie.py

Prompts

```
['build a HuggingFace prefix allowed tokens function for end-to-end entity linking with mention and entity trigrams', 'build a Fairseq prefix allowed tokens function for end-to-end entity linking with mention and entity trigrams', 'create a prefix allowed tokens function using custom encode and decode functions for constrained entity linking generation', 'review the get_status helper to determine if generation is in outside, mention, or entity phase', 'review the get_pointer_end helper to track alignment between generated tokens and original sentence tokens', 'load a pretrained GENRE model from a model name or path using GENRE.from_pretrained', 'load a pretrained mGENRE model with sentencepiece BPE using mGENRE.from_pretrained', 'sample entity predictions from input sentences using the GENREHubInterface sample method with beam search', 'encode a sentence into a tokenized tensor using the GENREHubInterface encode method', 'generate batched hypotheses from tokenized sentences using the GENREHubInterface generate method', 'sample entity predictions for a list of sentences using beam search with configurable beams and return sequences', 'sample entity predictions and marginalize scores across multiple mentions using a text to ID mapping', 'create a Trie from a list of integer sequences for prefix-based token lookups', 'query a Trie with a prefix sequence to get valid next token candidates', 'build a MarisaTrie from integer sequences using marisa_trie for efficient prefix search', 'load a Trie instance from an existing trie dictionary using the load_from_dict static method', 'create a DummyTrieMention that always returns fixed values for mention token generation', 'split a list of items into N roughly equal sized chunks for parallel processing', 'batch a sequence of items into groups of a specified size for batched model inference', 'create a model input string with left context, mention delimiters, and right context', 'extract entity mention spans and linked Wikipedia titles from sentences using a HuggingFace model', 'parse a Wikipedia XML dump file into a dictionary of documents with paragraphs and anchor links']
```

Usage

```
{'create_trie_from_sequences': 'create a Trie from a list of integer sequences for prefix-based token lookups', 'query_trie_prefix': 'query a Trie with a prefix sequence to get valid next token candidates', 'build_marisa_trie': 'build a MarisaTrie from integer sequences using marisa_trie for efficient prefix search', 'load_trie_from_dict': 'load a Trie instance from an existing trie dictionary using the load_from_dict static method', 'create_dummy_trie_mention': 'create a DummyTrieMention that always returns fixed values for mention token generation'}
```

## File: facebookresearch_genre/genre/utils.py

Prompts

```
['build a HuggingFace prefix allowed tokens function for end-to-end entity linking with mention and entity trigrams', 'build a Fairseq prefix allowed tokens function for end-to-end entity linking with mention and entity trigrams', 'create a prefix allowed tokens function using custom encode and decode functions for constrained entity linking generation', 'review the get_status helper to determine if generation is in outside, mention, or entity phase', 'review the get_pointer_end helper to track alignment between generated tokens and original sentence tokens', 'load a pretrained GENRE model from a model name or path using GENRE.from_pretrained', 'load a pretrained mGENRE model with sentencepiece BPE using mGENRE.from_pretrained', 'sample entity predictions from input sentences using the GENREHubInterface sample method with beam search', 'encode a sentence into a tokenized tensor using the GENREHubInterface encode method', 'generate batched hypotheses from tokenized sentences using the GENREHubInterface generate method', 'sample entity predictions for a list of sentences using beam search with configurable beams and return sequences', 'sample entity predictions and marginalize scores across multiple mentions using a text to ID mapping', 'create a Trie from a list of integer sequences for prefix-based token lookups', 'query a Trie with a prefix sequence to get valid next token candidates', 'build a MarisaTrie from integer sequences using marisa_trie for efficient prefix search', 'load a Trie instance from an existing trie dictionary using the load_from_dict static method', 'create a DummyTrieMention that always returns fixed values for mention token generation', 'split a list of items into N roughly equal sized chunks for parallel processing', 'batch a sequence of items into groups of a specified size for batched model inference', 'create a model input string with left context, mention delimiters, and right context', 'extract entity mention spans and linked Wikipedia titles from sentences using a HuggingFace model', 'parse a Wikipedia XML dump file into a dictionary of documents with paragraphs and anchor links']
```

Usage

```
{'chunk_it': 'split a list of items into N roughly equal sized chunks for parallel processing', 'batch_it': 'batch a sequence of items into groups of a specified size for batched model inference', 'create_input': 'create a model input string with left context, mention delimiters, and right context', 'get_entity_spans_hf': 'extract entity mention spans and linked Wikipedia titles from sentences using a HuggingFace model', 'extract_pages': 'parse a Wikipedia XML dump file into a dictionary of documents with paragraphs and anchor links'}
```

