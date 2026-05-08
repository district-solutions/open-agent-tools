# Agent Python Tools

- repo: facebookresearch/clinical-trial-parser
- repo_uri: https://github.com/facebookresearch/clinical-trial-parser

## File: facebookresearch_clinical-trial-parser/src/text/transformer.py

Prompts

```
['use the Transformer class to normalize and tokenize clinical trial text into space-separated tokens', 'use the Transformer class to normalize and tokenize text into a list of tokens', 'use the Normalizer class to normalize comparison operators like less than and greater than in text', 'use the Tokenizer class to tokenize text and optionally mask numbers with @NUMBER', 'use the is_number function to check if a string represents a number or number range', 'test the Normalizer class normalize method to convert comparison operators like <= to unicode symbols', 'test the Transformer class transform method to tokenize and mask numbers in clinical trial text', 'test the Transformer class transform method with an empty string input to verify it returns empty', 'run the unittest test suite for Normalizer and Transformer classes in the transformer test module', 'review the Normalizer class regex patterns for normalizing less than and greater than comparison operators']
```

Usage

```
{'transform_text_with_transformer': 'use the Transformer class to normalize and tokenize clinical trial text into space-separated tokens', 'tokenize_text_with_transformer': 'use the Transformer class to normalize and tokenize text into a list of tokens', 'normalize_comparison_operators': 'use the Normalizer class to normalize comparison operators like less than and greater than in text', 'tokenize_with_number_masking': 'use the Tokenizer class to tokenize text and optionally mask numbers with @NUMBER', 'check_if_string_is_number': 'use the is_number function to check if a string represents a number or number range'}
```

## File: facebookresearch_clinical-trial-parser/src/text/transformer_test.py

Prompts

```
['use the Transformer class to normalize and tokenize clinical trial text into space-separated tokens', 'use the Transformer class to normalize and tokenize text into a list of tokens', 'use the Normalizer class to normalize comparison operators like less than and greater than in text', 'use the Tokenizer class to tokenize text and optionally mask numbers with @NUMBER', 'use the is_number function to check if a string represents a number or number range', 'test the Normalizer class normalize method to convert comparison operators like <= to unicode symbols', 'test the Transformer class transform method to tokenize and mask numbers in clinical trial text', 'test the Transformer class transform method with an empty string input to verify it returns empty', 'run the unittest test suite for Normalizer and Transformer classes in the transformer test module', 'review the Normalizer class regex patterns for normalizing less than and greater than comparison operators']
```

Usage

```
{'test_normalizer_normalize': 'test the Normalizer class normalize method to convert comparison operators like <= to unicode symbols', 'test_transformer_transform': 'test the Transformer class transform method to tokenize and mask numbers in clinical trial text', 'test_transformer_empty': 'test the Transformer class transform method with an empty string input to verify it returns empty', 'run_transformer_tests': 'run the unittest test suite for Normalizer and Transformer classes in the transformer test module', 'review_normalizer_comparison_patterns': 'review the Normalizer class regex patterns for normalizing less than and greater than comparison operators'}
```

