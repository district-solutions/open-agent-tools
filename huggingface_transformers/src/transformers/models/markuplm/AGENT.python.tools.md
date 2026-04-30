# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/markuplm/feature_extraction_markuplm.py

Prompts

```
['create a MarkupLMFeatureExtractor instance to parse HTML strings into text nodes and xpaths', 'extract text nodes and corresponding xpaths from a single HTML string using MarkupLMFeatureExtractor', 'batch extract text nodes and xpaths from multiple HTML strings using MarkupLMFeatureExtractor', 'construct an xpath string from a list of tag names and their sibling subscripts', 'parse a BeautifulSoup element and return its xpath tag sequence and subscript sequence', 'run the MarkupLMModel to encode HTML sequences and extract hidden states with pooled output', 'create a MarkupLMForQuestionAnswering model to extract answer spans from HTML input sequences', 'run MarkupLMForTokenClassification to predict token labels for HTML node classification tasks', 'run MarkupLMForSequenceClassification to classify entire HTML documents into labeled categories', 'build XPath-aware embeddings combining word, position, token type, and structural tag information', 'create a MarkupLMTokenizer instance with custom vocabulary, merges, and xpath tag dictionary for HTML tokenization', 'encode HTML text sequences with xpaths and node labels into token-level input_ids, attention_mask, and xpath sequences', 'get xpath tag IDs and subscript sequences from an xpath expression string for a given DOM node', 'pad encoded token sequences to a maximum length with attention masks, token_type_ids, and xpath sequences', 'build model inputs from token sequences by concatenating and adding special tokens like cls and sep']
```

Usage

```
{'create_markuplm_feature_extractor': 'create a MarkupLMFeatureExtractor instance to parse HTML strings into text nodes and xpaths', 'extract_html_nodes_and_xpaths': 'extract text nodes and corresponding xpaths from a single HTML string using MarkupLMFeatureExtractor', 'batch_extract_html_nodes_xpaths': 'batch extract text nodes and xpaths from multiple HTML strings using MarkupLMFeatureExtractor', 'construct_xpath_from_tags': 'construct an xpath string from a list of tag names and their sibling subscripts', 'parse_html_with_xpath_soup': 'parse a BeautifulSoup element and return its xpath tag sequence and subscript sequence'}
```

## File: huggingface_transformers/src/transformers/models/markuplm/modeling_markuplm.py

Prompts

```
['create a MarkupLMFeatureExtractor instance to parse HTML strings into text nodes and xpaths', 'extract text nodes and corresponding xpaths from a single HTML string using MarkupLMFeatureExtractor', 'batch extract text nodes and xpaths from multiple HTML strings using MarkupLMFeatureExtractor', 'construct an xpath string from a list of tag names and their sibling subscripts', 'parse a BeautifulSoup element and return its xpath tag sequence and subscript sequence', 'run the MarkupLMModel to encode HTML sequences and extract hidden states with pooled output', 'create a MarkupLMForQuestionAnswering model to extract answer spans from HTML input sequences', 'run MarkupLMForTokenClassification to predict token labels for HTML node classification tasks', 'run MarkupLMForSequenceClassification to classify entire HTML documents into labeled categories', 'build XPath-aware embeddings combining word, position, token type, and structural tag information', 'create a MarkupLMTokenizer instance with custom vocabulary, merges, and xpath tag dictionary for HTML tokenization', 'encode HTML text sequences with xpaths and node labels into token-level input_ids, attention_mask, and xpath sequences', 'get xpath tag IDs and subscript sequences from an xpath expression string for a given DOM node', 'pad encoded token sequences to a maximum length with attention masks, token_type_ids, and xpath sequences', 'build model inputs from token sequences by concatenating and adding special tokens like cls and sep']
```

Usage

```
{'run_markuplm_model': 'run the MarkupLMModel to encode HTML sequences and extract hidden states with pooled output', 'create_markuplm_question_answering': 'create a MarkupLMForQuestionAnswering model to extract answer spans from HTML input sequences', 'run_markuplm_token_classification': 'run MarkupLMForTokenClassification to predict token labels for HTML node classification tasks', 'run_markuplm_sequence_classification': 'run MarkupLMForSequenceClassification to classify entire HTML documents into labeled categories', 'build_markuplm_embeddings': 'build XPath-aware embeddings combining word, position, token type, and structural tag information'}
```

## File: huggingface_transformers/src/transformers/models/markuplm/tokenization_markuplm.py

Prompts

```
['create a MarkupLMFeatureExtractor instance to parse HTML strings into text nodes and xpaths', 'extract text nodes and corresponding xpaths from a single HTML string using MarkupLMFeatureExtractor', 'batch extract text nodes and xpaths from multiple HTML strings using MarkupLMFeatureExtractor', 'construct an xpath string from a list of tag names and their sibling subscripts', 'parse a BeautifulSoup element and return its xpath tag sequence and subscript sequence', 'run the MarkupLMModel to encode HTML sequences and extract hidden states with pooled output', 'create a MarkupLMForQuestionAnswering model to extract answer spans from HTML input sequences', 'run MarkupLMForTokenClassification to predict token labels for HTML node classification tasks', 'run MarkupLMForSequenceClassification to classify entire HTML documents into labeled categories', 'build XPath-aware embeddings combining word, position, token type, and structural tag information', 'create a MarkupLMTokenizer instance with custom vocabulary, merges, and xpath tag dictionary for HTML tokenization', 'encode HTML text sequences with xpaths and node labels into token-level input_ids, attention_mask, and xpath sequences', 'get xpath tag IDs and subscript sequences from an xpath expression string for a given DOM node', 'pad encoded token sequences to a maximum length with attention masks, token_type_ids, and xpath sequences', 'build model inputs from token sequences by concatenating and adding special tokens like cls and sep']
```

Usage

```
{'create_markuplm_tokenizer': 'create a MarkupLMTokenizer instance with custom vocabulary, merges, and xpath tag dictionary for HTML tokenization', 'encode_html_sequences': 'encode HTML text sequences with xpaths and node labels into token-level input_ids, attention_mask, and xpath sequences', 'get_xpath_sequence': 'get xpath tag IDs and subscript sequences from an xpath expression string for a given DOM node', 'pad_encoded_inputs': 'pad encoded token sequences to a maximum length with attention masks, token_type_ids, and xpath sequences', 'build_special_token_inputs': 'build model inputs from token sequences by concatenating and adding special tokens like cls and sep'}
```

