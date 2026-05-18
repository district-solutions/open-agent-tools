# Agent Python Tools

- repo: facebookresearch/metaclip
- repo_uri: https://github.com/facebookresearch/metaclip

## File: facebookresearch_metaclip/metaclip/metadata/build_metadata.py

Prompts

```
['run build_metadata to generate per-language metadata JSON from WordNet, n-grams, and Wikipedia titles', 'run the script without arguments to submit batch jobs for all wiki language codes via submitit', 'use is_punctuation to check if a single character is ASCII or CJK punctuation', 'use is_pure_punctuations to check if a string contains only punctuation characters', 'review the wordnet_to_wiki and wiki_to_wordnet dictionaries that map WordNet language codes to Wikipedia language codes', 'build unigram and bigram counts from wiki text files and save as JSON', 'tokenize text into tokens using language-aware tokenization for CJK and space-separated languages', 'tokenize text by splitting on whitespace and treating CJK characters as individual tokens', 'remove HTML tags and encoded angle brackets from text strings', 'count unigram and bigram frequencies from a list of tokens with punctuation filtering', 'download and parse Wikipedia pageview data for a specific date into title counts', 'merge per-date title count JSON files into aggregated multilingual title counts per language', 'submit batch jobs via submitit to process Wikipedia pageview data for all dates', 'refactor process_date to support custom date ranges or alternative pageview data sources', 'review wiki_multilingual_title to verify language code normalization and title aggregation logic']
```

Usage

```
{'build_metadata_for_language': 'run build_metadata to generate per-language metadata JSON from WordNet, n-grams, and Wikipedia titles', 'run_batch_metadata_build': 'run the script without arguments to submit batch jobs for all wiki language codes via submitit', 'check_punctuation_character': 'use is_punctuation to check if a single character is ASCII or CJK punctuation', 'check_pure_punctuation_string': 'use is_pure_punctuations to check if a string contains only punctuation characters', 'review_wordnet_wiki_mapping': 'review the wordnet_to_wiki and wiki_to_wordnet dictionaries that map WordNet language codes to Wikipedia language codes'}
```

## File: facebookresearch_metaclip/metaclip/metadata/build_ngram.py

Prompts

```
['run build_metadata to generate per-language metadata JSON from WordNet, n-grams, and Wikipedia titles', 'run the script without arguments to submit batch jobs for all wiki language codes via submitit', 'use is_punctuation to check if a single character is ASCII or CJK punctuation', 'use is_pure_punctuations to check if a string contains only punctuation characters', 'review the wordnet_to_wiki and wiki_to_wordnet dictionaries that map WordNet language codes to Wikipedia language codes', 'build unigram and bigram counts from wiki text files and save as JSON', 'tokenize text into tokens using language-aware tokenization for CJK and space-separated languages', 'tokenize text by splitting on whitespace and treating CJK characters as individual tokens', 'remove HTML tags and encoded angle brackets from text strings', 'count unigram and bigram frequencies from a list of tokens with punctuation filtering', 'download and parse Wikipedia pageview data for a specific date into title counts', 'merge per-date title count JSON files into aggregated multilingual title counts per language', 'submit batch jobs via submitit to process Wikipedia pageview data for all dates', 'refactor process_date to support custom date ranges or alternative pageview data sources', 'review wiki_multilingual_title to verify language code normalization and title aggregation logic']
```

Usage

```
{'build_ngrams': 'build unigram and bigram counts from wiki text files and save as JSON', 'tokenize': 'tokenize text into tokens using language-aware tokenization for CJK and space-separated languages', 'simple_tokenizer': 'tokenize text by splitting on whitespace and treating CJK characters as individual tokens', 'remove_html_tags': 'remove HTML tags and encoded angle brackets from text strings', 'count_ngrams': 'count unigram and bigram frequencies from a list of tokens with punctuation filtering'}
```

## File: facebookresearch_metaclip/metaclip/metadata/build_title.py

Prompts

```
['run build_metadata to generate per-language metadata JSON from WordNet, n-grams, and Wikipedia titles', 'run the script without arguments to submit batch jobs for all wiki language codes via submitit', 'use is_punctuation to check if a single character is ASCII or CJK punctuation', 'use is_pure_punctuations to check if a string contains only punctuation characters', 'review the wordnet_to_wiki and wiki_to_wordnet dictionaries that map WordNet language codes to Wikipedia language codes', 'build unigram and bigram counts from wiki text files and save as JSON', 'tokenize text into tokens using language-aware tokenization for CJK and space-separated languages', 'tokenize text by splitting on whitespace and treating CJK characters as individual tokens', 'remove HTML tags and encoded angle brackets from text strings', 'count unigram and bigram frequencies from a list of tokens with punctuation filtering', 'download and parse Wikipedia pageview data for a specific date into title counts', 'merge per-date title count JSON files into aggregated multilingual title counts per language', 'submit batch jobs via submitit to process Wikipedia pageview data for all dates', 'refactor process_date to support custom date ranges or alternative pageview data sources', 'review wiki_multilingual_title to verify language code normalization and title aggregation logic']
```

Usage

```
{'run_process_date': 'download and parse Wikipedia pageview data for a specific date into title counts', 'run_wiki_multilingual_title': 'merge per-date title count JSON files into aggregated multilingual title counts per language', 'run_build_title_main': 'submit batch jobs via submitit to process Wikipedia pageview data for all dates', 'refactor_process_date': 'refactor process_date to support custom date ranges or alternative pageview data sources', 'review_wiki_multilingual_title': 'review wiki_multilingual_title to verify language code normalization and title aggregation logic'}
```

