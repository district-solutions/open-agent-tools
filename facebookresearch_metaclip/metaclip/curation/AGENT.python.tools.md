# Agent Python Tools

- repo: facebookresearch/metaclip
- repo_uri: https://github.com/facebookresearch/metaclip

## File: facebookresearch_metaclip/metaclip/curation/curate.py

Prompts

```
['run substring matching on text shards and count metadata matches for a shard range', 'run global aggregation of per-shard match counts and compute per-language sampling probabilities', 'run curation of image-text pairs using probability-based sampling across a shard range', 'use p_to_t to convert a tail portion into a count threshold from entry counts', 'use count_to_prob to convert raw entry counts into sampling probabilities using a threshold', 'parse gzipped WAT files from a directory and extract image URLs with alt text into a JSON output file', 'extract image URLs and associated alt/title text from HTML metadata links in WARC records', 'normalize a relative URL against a target URI base using urljoin with optional query parameter stripping', 'generate a 24 character SHA-224 based UUID hash from a cleaned URL string', 'detect the language of a text string using fasttext and ftlangdetect with low memory mode', 'build an Aho-Corasick automaton from spaced metadata entries for efficient multi-pattern substring matching', 'check if a single character belongs to CJK, Thai, Lao, Burmese, Khmer, or Tibetan Unicode ranges', 'check if a character is ASCII or CJK punctuation using the additional_punctuation lookup', 'match substrings in text against a language-specific Aho-Corasick automaton and return matched entry IDs', 'prepare a list of metadata strings by adding boundary spaces for non-CJK entries to enable automaton matching']
```

Usage

```
{'run_count_per_shard': 'run substring matching on text shards and count metadata matches for a shard range', 'run_global_count': 'run global aggregation of per-shard match counts and compute per-language sampling probabilities', 'run_curate': 'run curation of image-text pairs using probability-based sampling across a shard range', 'use_p_to_t': 'use p_to_t to convert a tail portion into a count threshold from entry counts', 'use_count_to_prob': 'use count_to_prob to convert raw entry counts into sampling probabilities using a threshold'}
```

## File: facebookresearch_metaclip/metaclip/curation/parse_wat.py

Prompts

```
['run substring matching on text shards and count metadata matches for a shard range', 'run global aggregation of per-shard match counts and compute per-language sampling probabilities', 'run curation of image-text pairs using probability-based sampling across a shard range', 'use p_to_t to convert a tail portion into a count threshold from entry counts', 'use count_to_prob to convert raw entry counts into sampling probabilities using a threshold', 'parse gzipped WAT files from a directory and extract image URLs with alt text into a JSON output file', 'extract image URLs and associated alt/title text from HTML metadata links in WARC records', 'normalize a relative URL against a target URI base using urljoin with optional query parameter stripping', 'generate a 24 character SHA-224 based UUID hash from a cleaned URL string', 'detect the language of a text string using fasttext and ftlangdetect with low memory mode', 'build an Aho-Corasick automaton from spaced metadata entries for efficient multi-pattern substring matching', 'check if a single character belongs to CJK, Thai, Lao, Burmese, Khmer, or Tibetan Unicode ranges', 'check if a character is ASCII or CJK punctuation using the additional_punctuation lookup', 'match substrings in text against a language-specific Aho-Corasick automaton and return matched entry IDs', 'prepare a list of metadata strings by adding boundary spaces for non-CJK entries to enable automaton matching']
```

Usage

```
{'parse_wat_files': 'parse gzipped WAT files from a directory and extract image URLs with alt text into a JSON output file', 'extract_images_from_links': 'extract image URLs and associated alt/title text from HTML metadata links in WARC records', 'normalize_url': 'normalize a relative URL against a target URI base using urljoin with optional query parameter stripping', 'gen_uuid': 'generate a 24 character SHA-224 based UUID hash from a cleaned URL string', 'detect_language': 'detect the language of a text string using fasttext and ftlangdetect with low memory mode'}
```

## File: facebookresearch_metaclip/metaclip/curation/substr_matching.py

Prompts

```
['run substring matching on text shards and count metadata matches for a shard range', 'run global aggregation of per-shard match counts and compute per-language sampling probabilities', 'run curation of image-text pairs using probability-based sampling across a shard range', 'use p_to_t to convert a tail portion into a count threshold from entry counts', 'use count_to_prob to convert raw entry counts into sampling probabilities using a threshold', 'parse gzipped WAT files from a directory and extract image URLs with alt text into a JSON output file', 'extract image URLs and associated alt/title text from HTML metadata links in WARC records', 'normalize a relative URL against a target URI base using urljoin with optional query parameter stripping', 'generate a 24 character SHA-224 based UUID hash from a cleaned URL string', 'detect the language of a text string using fasttext and ftlangdetect with low memory mode', 'build an Aho-Corasick automaton from spaced metadata entries for efficient multi-pattern substring matching', 'check if a single character belongs to CJK, Thai, Lao, Burmese, Khmer, or Tibetan Unicode ranges', 'check if a character is ASCII or CJK punctuation using the additional_punctuation lookup', 'match substrings in text against a language-specific Aho-Corasick automaton and return matched entry IDs', 'prepare a list of metadata strings by adding boundary spaces for non-CJK entries to enable automaton matching']
```

Usage

```
{'build_automaton_for_substring_matching': 'build an Aho-Corasick automaton from spaced metadata entries for efficient multi-pattern substring matching', 'check_if_character_is_cjk': 'check if a single character belongs to CJK, Thai, Lao, Burmese, Khmer, or Tibetan Unicode ranges', 'check_if_character_is_punctuation': 'check if a character is ASCII or CJK punctuation using the additional_punctuation lookup', 'match_substrings_with_automaton': 'match substrings in text against a language-specific Aho-Corasick automaton and return matched entry IDs', 'prepare_metadata_for_matching': 'prepare a list of metadata strings by adding boundary spaces for non-CJK entries to enable automaton matching'}
```

