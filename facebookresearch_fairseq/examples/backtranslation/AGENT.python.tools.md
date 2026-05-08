# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/backtranslation/deduplicate_lines.py

Prompts

```
['run the script to remove duplicate lines from one or more input text files', 'run the deduplication script with a custom number of multiprocessing workers', 'run the deduplication script reading from stdin when no input files are provided', 'review the get_hashes_and_lines function that computes an MD5 hash for a raw line', 'refactor the main deduplication logic to use a different hashing algorithm instead of MD5', 'run extract_bt_data.py to extract back-translations from fairseq-generate stdout into parallel source and target files', 'run extract_bt_data.py with --minlen and --maxlen flags to filter sentence pairs by token count', 'run extract_bt_data.py with --ratio flag to filter sentence pairs by source-to-target length ratio', 'review the validate function to understand how source and target sentence pairs are filtered by length constraints', 'run extract_bt_data.py with --output, --srclang, --tgtlang arguments and input files to produce parallel corpus files']
```

Usage

```
{'run_deduplicate_lines': 'run the script to remove duplicate lines from one or more input text files', 'run_deduplicate_lines_with_workers': 'run the deduplication script with a custom number of multiprocessing workers', 'run_deduplicate_lines_stdin': 'run the deduplication script reading from stdin when no input files are provided', 'review_get_hashes_and_lines': 'review the get_hashes_and_lines function that computes an MD5 hash for a raw line', 'refactor_main_deduplication': 'refactor the main deduplication logic to use a different hashing algorithm instead of MD5'}
```

## File: facebookresearch_fairseq/examples/backtranslation/extract_bt_data.py

Prompts

```
['run the script to remove duplicate lines from one or more input text files', 'run the deduplication script with a custom number of multiprocessing workers', 'run the deduplication script reading from stdin when no input files are provided', 'review the get_hashes_and_lines function that computes an MD5 hash for a raw line', 'refactor the main deduplication logic to use a different hashing algorithm instead of MD5', 'run extract_bt_data.py to extract back-translations from fairseq-generate stdout into parallel source and target files', 'run extract_bt_data.py with --minlen and --maxlen flags to filter sentence pairs by token count', 'run extract_bt_data.py with --ratio flag to filter sentence pairs by source-to-target length ratio', 'review the validate function to understand how source and target sentence pairs are filtered by length constraints', 'run extract_bt_data.py with --output, --srclang, --tgtlang arguments and input files to produce parallel corpus files']
```

Usage

```
{'extract_backtranslations': 'run extract_bt_data.py to extract back-translations from fairseq-generate stdout into parallel source and target files', 'filter_by_length': 'run extract_bt_data.py with --minlen and --maxlen flags to filter sentence pairs by token count', 'filter_by_ratio': 'run extract_bt_data.py with --ratio flag to filter sentence pairs by source-to-target length ratio', 'validate_sentence_pairs': 'review the validate function to understand how source and target sentence pairs are filtered by length constraints', 'extract_bt_data_cli': 'run extract_bt_data.py with --output, --srclang, --tgtlang arguments and input files to produce parallel corpus files'}
```

