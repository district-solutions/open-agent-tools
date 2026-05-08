# Agent Python Tools

- repo: facebookresearch/laser
- repo_uri: https://github.com/facebookresearch/laser

## File: facebookresearch_laser/utils/src/cleaner_splitter.py

Prompts

```
['run the cleaner_splitter CLI module to split and clean sentences from tab-separated stdin input', 'create a SentenceSplitClean instance to split text into sentences and normalize with Moses and NFKC', 'use reach_sentence_from_paragraph to find a matching sentence by digest from a paragraph using candidate modifiers', 'use get_sentence_candidate_modifiers to get a list of text transformation functions for sentence matching', 'use remove_on_unicode_category to strip Unicode symbol characters from a string', 'use legacy_demojizer to remove all emoji characters from a string', 'create a Demojizer instance and call it to replace emojis in text with a custom string', 'build a Demojizer to construct a trie-based search tree from emoji unicode data', 'review the Demojizer class and its trie-based emoji matching algorithm', 'summarize the legacy_demojizer function that filters out emoji characters using emoji.is_emoji', 'create a replacer function that replaces non-printable Unicode characters with a custom string like underscore', 'create a replacer function that replaces non-printable Unicode characters with a space character', 'test the get_replacer function by asserting it correctly strips zero-width and control characters from strings', 'refactor the get_replacer function to filter Unicode characters by their general category using unicodedata', 'summarize the get_replacer function which returns a closure that translates non-printable characters in a string', 'split text into sentences using the default algorithm for a given language code', 'split text into sentences using the Moses sentence splitter for European languages', 'split Indian language text into sentences using the Indic NLP toolkit', "split Amharic or Tigrinya text into sentences using Ge'ez script rules", 'split Burmese or Shan text into sentences using Burmese script rules']
```

Usage

```
{'run_split_clean_cli': 'run the cleaner_splitter CLI module to split and clean sentences from tab-separated stdin input', 'create_SentenceSplitClean': 'create a SentenceSplitClean instance to split text into sentences and normalize with Moses and NFKC', 'use_reach_sentence_from_paragraph': 'use reach_sentence_from_paragraph to find a matching sentence by digest from a paragraph using candidate modifiers', 'use_get_sentence_candidate_modifiers': 'use get_sentence_candidate_modifiers to get a list of text transformation functions for sentence matching', 'use_remove_on_unicode_category': 'use remove_on_unicode_category to strip Unicode symbol characters from a string'}
```

## File: facebookresearch_laser/utils/src/demojizer.py

Prompts

```
['run the cleaner_splitter CLI module to split and clean sentences from tab-separated stdin input', 'create a SentenceSplitClean instance to split text into sentences and normalize with Moses and NFKC', 'use reach_sentence_from_paragraph to find a matching sentence by digest from a paragraph using candidate modifiers', 'use get_sentence_candidate_modifiers to get a list of text transformation functions for sentence matching', 'use remove_on_unicode_category to strip Unicode symbol characters from a string', 'use legacy_demojizer to remove all emoji characters from a string', 'create a Demojizer instance and call it to replace emojis in text with a custom string', 'build a Demojizer to construct a trie-based search tree from emoji unicode data', 'review the Demojizer class and its trie-based emoji matching algorithm', 'summarize the legacy_demojizer function that filters out emoji characters using emoji.is_emoji', 'create a replacer function that replaces non-printable Unicode characters with a custom string like underscore', 'create a replacer function that replaces non-printable Unicode characters with a space character', 'test the get_replacer function by asserting it correctly strips zero-width and control characters from strings', 'refactor the get_replacer function to filter Unicode characters by their general category using unicodedata', 'summarize the get_replacer function which returns a closure that translates non-printable characters in a string', 'split text into sentences using the default algorithm for a given language code', 'split text into sentences using the Moses sentence splitter for European languages', 'split Indian language text into sentences using the Indic NLP toolkit', "split Amharic or Tigrinya text into sentences using Ge'ez script rules", 'split Burmese or Shan text into sentences using Burmese script rules']
```

Usage

```
{'remove_emojis_legacy': 'use legacy_demojizer to remove all emoji characters from a string', 'replace_emojis_with_string': 'create a Demojizer instance and call it to replace emojis in text with a custom string', 'build_search_tree': 'build a Demojizer to construct a trie-based search tree from emoji unicode data', 'review_DEMOJIZER_CLASS': 'review the Demojizer class and its trie-based emoji matching algorithm', 'summarize_legacy_demojizer': 'summarize the legacy_demojizer function that filters out emoji characters using emoji.is_emoji'}
```

## File: facebookresearch_laser/utils/src/remove_non_printing_char.py

Prompts

```
['run the cleaner_splitter CLI module to split and clean sentences from tab-separated stdin input', 'create a SentenceSplitClean instance to split text into sentences and normalize with Moses and NFKC', 'use reach_sentence_from_paragraph to find a matching sentence by digest from a paragraph using candidate modifiers', 'use get_sentence_candidate_modifiers to get a list of text transformation functions for sentence matching', 'use remove_on_unicode_category to strip Unicode symbol characters from a string', 'use legacy_demojizer to remove all emoji characters from a string', 'create a Demojizer instance and call it to replace emojis in text with a custom string', 'build a Demojizer to construct a trie-based search tree from emoji unicode data', 'review the Demojizer class and its trie-based emoji matching algorithm', 'summarize the legacy_demojizer function that filters out emoji characters using emoji.is_emoji', 'create a replacer function that replaces non-printable Unicode characters with a custom string like underscore', 'create a replacer function that replaces non-printable Unicode characters with a space character', 'test the get_replacer function by asserting it correctly strips zero-width and control characters from strings', 'refactor the get_replacer function to filter Unicode characters by their general category using unicodedata', 'summarize the get_replacer function which returns a closure that translates non-printable characters in a string', 'split text into sentences using the default algorithm for a given language code', 'split text into sentences using the Moses sentence splitter for European languages', 'split Indian language text into sentences using the Indic NLP toolkit', "split Amharic or Tigrinya text into sentences using Ge'ez script rules", 'split Burmese or Shan text into sentences using Burmese script rules']
```

Usage

```
{'create_replacer_with_custom_char': 'create a replacer function that replaces non-printable Unicode characters with a custom string like underscore', 'create_replacer_with_space': 'create a replacer function that replaces non-printable Unicode characters with a space character', 'test_remove_non_printing_chars': 'test the get_replacer function by asserting it correctly strips zero-width and control characters from strings', 'refactor_get_replacer': 'refactor the get_replacer function to filter Unicode characters by their general category using unicodedata', 'summarize_get_replacer': 'summarize the get_replacer function which returns a closure that translates non-printable characters in a string'}
```

## File: facebookresearch_laser/utils/src/sentence_split.py

Prompts

```
['run the cleaner_splitter CLI module to split and clean sentences from tab-separated stdin input', 'create a SentenceSplitClean instance to split text into sentences and normalize with Moses and NFKC', 'use reach_sentence_from_paragraph to find a matching sentence by digest from a paragraph using candidate modifiers', 'use get_sentence_candidate_modifiers to get a list of text transformation functions for sentence matching', 'use remove_on_unicode_category to strip Unicode symbol characters from a string', 'use legacy_demojizer to remove all emoji characters from a string', 'create a Demojizer instance and call it to replace emojis in text with a custom string', 'build a Demojizer to construct a trie-based search tree from emoji unicode data', 'review the Demojizer class and its trie-based emoji matching algorithm', 'summarize the legacy_demojizer function that filters out emoji characters using emoji.is_emoji', 'create a replacer function that replaces non-printable Unicode characters with a custom string like underscore', 'create a replacer function that replaces non-printable Unicode characters with a space character', 'test the get_replacer function by asserting it correctly strips zero-width and control characters from strings', 'refactor the get_replacer function to filter Unicode characters by their general category using unicodedata', 'summarize the get_replacer function which returns a closure that translates non-printable characters in a string', 'split text into sentences using the default algorithm for a given language code', 'split text into sentences using the Moses sentence splitter for European languages', 'split Indian language text into sentences using the Indic NLP toolkit', "split Amharic or Tigrinya text into sentences using Ge'ez script rules", 'split Burmese or Shan text into sentences using Burmese script rules']
```

Usage

```
{'split_sentences_default_algo': 'split text into sentences using the default algorithm for a given language code', 'split_sentences_moses': 'split text into sentences using the Moses sentence splitter for European languages', 'split_sentences_indic': 'split Indian language text into sentences using the Indic NLP toolkit', 'split_geez': "split Amharic or Tigrinya text into sentences using Ge'ez script rules", 'split_burmese': 'split Burmese or Shan text into sentences using Burmese script rules'}
```

