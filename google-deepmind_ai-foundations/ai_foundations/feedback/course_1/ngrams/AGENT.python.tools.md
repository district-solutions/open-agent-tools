# Agent Python Tools

- repo: google-deepmind/ai-foundations
- repo_uri: https://github.com/google-deepmind/ai-foundations

## File: google-deepmind_ai-foundations/ai_foundations/feedback/course_1/ngrams/test_candidate_tokens.py

Prompts

```
['test if a learner correctly identifies candidate tokens and probabilities from a trigram model', 'test that a trigram model contains the expected context and candidate tokens', 'test that candidate token probabilities match the expected values from a trigram model', 'review a trigram model dictionary to extract candidate tokens using the keys method', 'review a trigram model dictionary to extract token probabilities using the values method', "test a learner's get_ngram_counts implementation against a reference implementation using sample data", 'test the reference n-gram counts function that computes context to next token counts from a dataset', 'review the test_ngram_counts function that validates n-gram count dictionaries for bigrams and trigrams', 'summarize the reference implementation that builds a defaultdict of counters mapping contexts to next token frequencies', "run the n-gram counts test to validate a learner's implementation against sample sentences", "test a learner's n-gram model implementation by comparing output against a reference implementation", 'test a bigram language model by validating conditional probabilities on sample sentence datasets', 'test a trigram language model by comparing candidate probabilities against reference counts', 'build an n-gram language model from text corpus using n-gram counts and conditional probabilities', 'render feedback when the n-gram model test raises NameError, KeyError, or ValueError exceptions', "test a learner's n-gram generation function against a reference implementation using sample text", 'run the n-gram generation test to validate correctness of bigrams and trigrams', 'review the test_generate_ngrams function to understand the three validation checks it performs', 'refactor the nested reference implementation to generate n-grams from tokenized text', 'summarize the n-gram test module that validates length, tuple type, and content correctness']
```

Usage

```
{'test_candidate_tokens': 'test if a learner correctly identifies candidate tokens and probabilities from a trigram model', 'test_trigram_model_context': 'test that a trigram model contains the expected context and candidate tokens', 'test_token_probabilities': 'test that candidate token probabilities match the expected values from a trigram model', 'review_trigram_model_keys': 'review a trigram model dictionary to extract candidate tokens using the keys method', 'review_trigram_model_values': 'review a trigram model dictionary to extract token probabilities using the values method'}
```

## File: google-deepmind_ai-foundations/ai_foundations/feedback/course_1/ngrams/test_ngram_counts.py

Prompts

```
['test if a learner correctly identifies candidate tokens and probabilities from a trigram model', 'test that a trigram model contains the expected context and candidate tokens', 'test that candidate token probabilities match the expected values from a trigram model', 'review a trigram model dictionary to extract candidate tokens using the keys method', 'review a trigram model dictionary to extract token probabilities using the values method', "test a learner's get_ngram_counts implementation against a reference implementation using sample data", 'test the reference n-gram counts function that computes context to next token counts from a dataset', 'review the test_ngram_counts function that validates n-gram count dictionaries for bigrams and trigrams', 'summarize the reference implementation that builds a defaultdict of counters mapping contexts to next token frequencies', "run the n-gram counts test to validate a learner's implementation against sample sentences", "test a learner's n-gram model implementation by comparing output against a reference implementation", 'test a bigram language model by validating conditional probabilities on sample sentence datasets', 'test a trigram language model by comparing candidate probabilities against reference counts', 'build an n-gram language model from text corpus using n-gram counts and conditional probabilities', 'render feedback when the n-gram model test raises NameError, KeyError, or ValueError exceptions', "test a learner's n-gram generation function against a reference implementation using sample text", 'run the n-gram generation test to validate correctness of bigrams and trigrams', 'review the test_generate_ngrams function to understand the three validation checks it performs', 'refactor the nested reference implementation to generate n-grams from tokenized text', 'summarize the n-gram test module that validates length, tuple type, and content correctness']
```

Usage

```
{'test_ngram_counts': "test a learner's get_ngram_counts implementation against a reference implementation using sample data", 'test_reference_implementation': 'test the reference n-gram counts function that computes context to next token counts from a dataset', 'review_test_ngram_counts': 'review the test_ngram_counts function that validates n-gram count dictionaries for bigrams and trigrams', 'summarize_reference_implementation': 'summarize the reference implementation that builds a defaultdict of counters mapping contexts to next token frequencies', 'run_test_ngram_counts': "run the n-gram counts test to validate a learner's implementation against sample sentences"}
```

## File: google-deepmind_ai-foundations/ai_foundations/feedback/course_1/ngrams/test_ngram_model.py

Prompts

```
['test if a learner correctly identifies candidate tokens and probabilities from a trigram model', 'test that a trigram model contains the expected context and candidate tokens', 'test that candidate token probabilities match the expected values from a trigram model', 'review a trigram model dictionary to extract candidate tokens using the keys method', 'review a trigram model dictionary to extract token probabilities using the values method', "test a learner's get_ngram_counts implementation against a reference implementation using sample data", 'test the reference n-gram counts function that computes context to next token counts from a dataset', 'review the test_ngram_counts function that validates n-gram count dictionaries for bigrams and trigrams', 'summarize the reference implementation that builds a defaultdict of counters mapping contexts to next token frequencies', "run the n-gram counts test to validate a learner's implementation against sample sentences", "test a learner's n-gram model implementation by comparing output against a reference implementation", 'test a bigram language model by validating conditional probabilities on sample sentence datasets', 'test a trigram language model by comparing candidate probabilities against reference counts', 'build an n-gram language model from text corpus using n-gram counts and conditional probabilities', 'render feedback when the n-gram model test raises NameError, KeyError, or ValueError exceptions', "test a learner's n-gram generation function against a reference implementation using sample text", 'run the n-gram generation test to validate correctness of bigrams and trigrams', 'review the test_generate_ngrams function to understand the three validation checks it performs', 'refactor the nested reference implementation to generate n-grams from tokenized text', 'summarize the n-gram test module that validates length, tuple type, and content correctness']
```

Usage

```
{'test_build_ngram_model': "test a learner's n-gram model implementation by comparing output against a reference implementation", 'test_bigram_model': 'test a bigram language model by validating conditional probabilities on sample sentence datasets', 'test_trigram_model': 'test a trigram language model by comparing candidate probabilities against reference counts', 'build_ngram_model_reference': 'build an n-gram language model from text corpus using n-gram counts and conditional probabilities', 'render_feedback_on_error': 'render feedback when the n-gram model test raises NameError, KeyError, or ValueError exceptions'}
```

## File: google-deepmind_ai-foundations/ai_foundations/feedback/course_1/ngrams/test_ngrams.py

Prompts

```
['test if a learner correctly identifies candidate tokens and probabilities from a trigram model', 'test that a trigram model contains the expected context and candidate tokens', 'test that candidate token probabilities match the expected values from a trigram model', 'review a trigram model dictionary to extract candidate tokens using the keys method', 'review a trigram model dictionary to extract token probabilities using the values method', "test a learner's get_ngram_counts implementation against a reference implementation using sample data", 'test the reference n-gram counts function that computes context to next token counts from a dataset', 'review the test_ngram_counts function that validates n-gram count dictionaries for bigrams and trigrams', 'summarize the reference implementation that builds a defaultdict of counters mapping contexts to next token frequencies', "run the n-gram counts test to validate a learner's implementation against sample sentences", "test a learner's n-gram model implementation by comparing output against a reference implementation", 'test a bigram language model by validating conditional probabilities on sample sentence datasets', 'test a trigram language model by comparing candidate probabilities against reference counts', 'build an n-gram language model from text corpus using n-gram counts and conditional probabilities', 'render feedback when the n-gram model test raises NameError, KeyError, or ValueError exceptions', "test a learner's n-gram generation function against a reference implementation using sample text", 'run the n-gram generation test to validate correctness of bigrams and trigrams', 'review the test_generate_ngrams function to understand the three validation checks it performs', 'refactor the nested reference implementation to generate n-grams from tokenized text', 'summarize the n-gram test module that validates length, tuple type, and content correctness']
```

Usage

```
{'test_generate_ngrams': "test a learner's n-gram generation function against a reference implementation using sample text", 'run_test_ngrams': 'run the n-gram generation test to validate correctness of bigrams and trigrams', 'review_test_generate_ngrams': 'review the test_generate_ngrams function to understand the three validation checks it performs', 'refactor_reference_implementation': 'refactor the nested reference implementation to generate n-grams from tokenized text', 'summarize_test_ngrams': 'summarize the n-gram test module that validates length, tuple type, and content correctness'}
```

