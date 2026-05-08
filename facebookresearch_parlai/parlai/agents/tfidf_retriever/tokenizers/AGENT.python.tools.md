# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/agents/tfidf_retriever/tokenizers/regexp_tokenizer.py

Prompts

```
['create a RegexpTokenizer and call tokenize on a string to get tokenized words with whitespace and span info', 'create a RegexpTokenizer with substitutions=False to keep original quote and dash characters instead of normalizing them', 'call ngrams on the Tokens object returned by tokenize to get n-grams up to a specified length', 'call words with uncased=True on the Tokens object to get a list of lowercased token strings', 'review the RegexpTokenizer class regex patterns for digits, titles, abbreviations, contractions, quotes, dashes, and ellipses', 'create a SimpleTokenizer instance and call tokenize on a string to get alpha-numeric and non-whitespace tokens', 'build a SimpleTokenizer that uses ALPHA_NUM and NON_WS regex patterns to split text into tokens', 'review the SimpleTokenizer class and its tokenize method to understand token span and whitespace handling', 'summarize how SimpleTokenizer splits text into tokens with associated whitespace and character spans', 'test the SimpleTokenizer tokenize method with sample text and verify the returned Tokens data structure', 'create a SpacyTokenizer instance using the default English spaCy model', 'create a SpacyTokenizer with pos, lemma, and ner annotators enabled', 'tokenize text using SpacyTokenizer to get tokens with whitespace and span info', 'tokenize text with NER enabled to extract named entity types for each token', 'review the SpacyTokenizer class and its tokenize method for spaCy-backed tokenization', 'create a Tokens object and extract a list of tokenized words from text data', 'create a Tokens object and generate ngrams up to a specified length from tokenized text', 'build a subclass of Tokenizer that implements the tokenize method to return a Tokens object', 'review the Tokens class and its accessor methods for words, ngrams, POS, lemma, and NER', 'test the Tokenizer base class tokenize method and shutdown lifecycle in a subclass']
```

Usage

```
{'tokenize_text_with_regexp': 'create a RegexpTokenizer and call tokenize on a string to get tokenized words with whitespace and span info', 'tokenize_with_substitutions_disabled': 'create a RegexpTokenizer with substitutions=False to keep original quote and dash characters instead of normalizing them', 'extract_ngrams_from_tokens': 'call ngrams on the Tokens object returned by tokenize to get n-grams up to a specified length', 'get_lowercased_words': 'call words with uncased=True on the Tokens object to get a list of lowercased token strings', 'review_tokenizer_regex_patterns': 'review the RegexpTokenizer class regex patterns for digits, titles, abbreviations, contractions, quotes, dashes, and ellipses'}
```

## File: facebookresearch_parlai/parlai/agents/tfidf_retriever/tokenizers/simple_tokenizer.py

Prompts

```
['create a RegexpTokenizer and call tokenize on a string to get tokenized words with whitespace and span info', 'create a RegexpTokenizer with substitutions=False to keep original quote and dash characters instead of normalizing them', 'call ngrams on the Tokens object returned by tokenize to get n-grams up to a specified length', 'call words with uncased=True on the Tokens object to get a list of lowercased token strings', 'review the RegexpTokenizer class regex patterns for digits, titles, abbreviations, contractions, quotes, dashes, and ellipses', 'create a SimpleTokenizer instance and call tokenize on a string to get alpha-numeric and non-whitespace tokens', 'build a SimpleTokenizer that uses ALPHA_NUM and NON_WS regex patterns to split text into tokens', 'review the SimpleTokenizer class and its tokenize method to understand token span and whitespace handling', 'summarize how SimpleTokenizer splits text into tokens with associated whitespace and character spans', 'test the SimpleTokenizer tokenize method with sample text and verify the returned Tokens data structure', 'create a SpacyTokenizer instance using the default English spaCy model', 'create a SpacyTokenizer with pos, lemma, and ner annotators enabled', 'tokenize text using SpacyTokenizer to get tokens with whitespace and span info', 'tokenize text with NER enabled to extract named entity types for each token', 'review the SpacyTokenizer class and its tokenize method for spaCy-backed tokenization', 'create a Tokens object and extract a list of tokenized words from text data', 'create a Tokens object and generate ngrams up to a specified length from tokenized text', 'build a subclass of Tokenizer that implements the tokenize method to return a Tokens object', 'review the Tokens class and its accessor methods for words, ngrams, POS, lemma, and NER', 'test the Tokenizer base class tokenize method and shutdown lifecycle in a subclass']
```

Usage

```
{'tokenize_text_with_simple_tokenizer': 'create a SimpleTokenizer instance and call tokenize on a string to get alpha-numeric and non-whitespace tokens', 'build_tokenizer_with_regex_pattern': 'build a SimpleTokenizer that uses ALPHA_NUM and NON_WS regex patterns to split text into tokens', 'review_simple_tokenizer_class': 'review the SimpleTokenizer class and its tokenize method to understand token span and whitespace handling', 'summarize_simple_tokenizer_usage': 'summarize how SimpleTokenizer splits text into tokens with associated whitespace and character spans', 'test_simple_tokenizer_tokenize': 'test the SimpleTokenizer tokenize method with sample text and verify the returned Tokens data structure'}
```

## File: facebookresearch_parlai/parlai/agents/tfidf_retriever/tokenizers/spacy_tokenizer.py

Prompts

```
['create a RegexpTokenizer and call tokenize on a string to get tokenized words with whitespace and span info', 'create a RegexpTokenizer with substitutions=False to keep original quote and dash characters instead of normalizing them', 'call ngrams on the Tokens object returned by tokenize to get n-grams up to a specified length', 'call words with uncased=True on the Tokens object to get a list of lowercased token strings', 'review the RegexpTokenizer class regex patterns for digits, titles, abbreviations, contractions, quotes, dashes, and ellipses', 'create a SimpleTokenizer instance and call tokenize on a string to get alpha-numeric and non-whitespace tokens', 'build a SimpleTokenizer that uses ALPHA_NUM and NON_WS regex patterns to split text into tokens', 'review the SimpleTokenizer class and its tokenize method to understand token span and whitespace handling', 'summarize how SimpleTokenizer splits text into tokens with associated whitespace and character spans', 'test the SimpleTokenizer tokenize method with sample text and verify the returned Tokens data structure', 'create a SpacyTokenizer instance using the default English spaCy model', 'create a SpacyTokenizer with pos, lemma, and ner annotators enabled', 'tokenize text using SpacyTokenizer to get tokens with whitespace and span info', 'tokenize text with NER enabled to extract named entity types for each token', 'review the SpacyTokenizer class and its tokenize method for spaCy-backed tokenization', 'create a Tokens object and extract a list of tokenized words from text data', 'create a Tokens object and generate ngrams up to a specified length from tokenized text', 'build a subclass of Tokenizer that implements the tokenize method to return a Tokens object', 'review the Tokens class and its accessor methods for words, ngrams, POS, lemma, and NER', 'test the Tokenizer base class tokenize method and shutdown lifecycle in a subclass']
```

Usage

```
{'create_spacy_tokenizer_basic': 'create a SpacyTokenizer instance using the default English spaCy model', 'create_spacy_tokenizer_with_annotators': 'create a SpacyTokenizer with pos, lemma, and ner annotators enabled', 'tokenize_text_with_spacy': 'tokenize text using SpacyTokenizer to get tokens with whitespace and span info', 'tokenize_with_ner_annotator': 'tokenize text with NER enabled to extract named entity types for each token', 'review_spacy_tokenizer_class': 'review the SpacyTokenizer class and its tokenize method for spaCy-backed tokenization'}
```

## File: facebookresearch_parlai/parlai/agents/tfidf_retriever/tokenizers/tokenizer.py

Prompts

```
['create a RegexpTokenizer and call tokenize on a string to get tokenized words with whitespace and span info', 'create a RegexpTokenizer with substitutions=False to keep original quote and dash characters instead of normalizing them', 'call ngrams on the Tokens object returned by tokenize to get n-grams up to a specified length', 'call words with uncased=True on the Tokens object to get a list of lowercased token strings', 'review the RegexpTokenizer class regex patterns for digits, titles, abbreviations, contractions, quotes, dashes, and ellipses', 'create a SimpleTokenizer instance and call tokenize on a string to get alpha-numeric and non-whitespace tokens', 'build a SimpleTokenizer that uses ALPHA_NUM and NON_WS regex patterns to split text into tokens', 'review the SimpleTokenizer class and its tokenize method to understand token span and whitespace handling', 'summarize how SimpleTokenizer splits text into tokens with associated whitespace and character spans', 'test the SimpleTokenizer tokenize method with sample text and verify the returned Tokens data structure', 'create a SpacyTokenizer instance using the default English spaCy model', 'create a SpacyTokenizer with pos, lemma, and ner annotators enabled', 'tokenize text using SpacyTokenizer to get tokens with whitespace and span info', 'tokenize text with NER enabled to extract named entity types for each token', 'review the SpacyTokenizer class and its tokenize method for spaCy-backed tokenization', 'create a Tokens object and extract a list of tokenized words from text data', 'create a Tokens object and generate ngrams up to a specified length from tokenized text', 'build a subclass of Tokenizer that implements the tokenize method to return a Tokens object', 'review the Tokens class and its accessor methods for words, ngrams, POS, lemma, and NER', 'test the Tokenizer base class tokenize method and shutdown lifecycle in a subclass']
```

Usage

```
{'create_tokens_words': 'create a Tokens object and extract a list of tokenized words from text data', 'create_tokens_ngrams': 'create a Tokens object and generate ngrams up to a specified length from tokenized text', 'build_tokenizer_subclass': 'build a subclass of Tokenizer that implements the tokenize method to return a Tokens object', 'review_tokens_class': 'review the Tokens class and its accessor methods for words, ngrams, POS, lemma, and NER', 'test_tokenizer_base': 'test the Tokenizer base class tokenize method and shutdown lifecycle in a subclass'}
```

