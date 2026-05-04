# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/backtranslation/deduplicate_lines.py

Prompts

```
['run the deduplicate_lines script to remove duplicate lines from input text files using MD5 hashing', 'run the deduplicate_lines script with a custom number of multiprocessing workers for faster processing', 'run the deduplicate_lines script on multiple input files to deduplicate across all of them', 'review the get_hashes_and_lines function that computes an MD5 hash for a raw line of data', 'review the main function that uses a set to track seen hashes and writes unique lines to stdout', 'run the script to extract back-translations from fairseq-generate stdout into source and target language files', 'run the script with minlen, maxlen, and ratio filters to extract filtered back-translation pairs', 'run the script on multiple input files to extract back-translations and write paired output files', 'review the validate function that filters sentence pairs by min length, max length, and length ratio', 'review the safe_index helper that safely retrieves a list element with a default fallback value']
```

Usage

```
{'run_deduplicate_lines': 'run the deduplicate_lines script to remove duplicate lines from input text files using MD5 hashing', 'run_deduplicate_with_workers': 'run the deduplicate_lines script with a custom number of multiprocessing workers for faster processing', 'run_deduplicate_multiple_files': 'run the deduplicate_lines script on multiple input files to deduplicate across all of them', 'review_get_hashes_and_lines': 'review the get_hashes_and_lines function that computes an MD5 hash for a raw line of data', 'review_main_deduplication_logic': 'review the main function that uses a set to track seen hashes and writes unique lines to stdout'}
```

## File: facebookresearch_avhubert/fairseq/examples/backtranslation/extract_bt_data.py

Prompts

```
['run the deduplicate_lines script to remove duplicate lines from input text files using MD5 hashing', 'run the deduplicate_lines script with a custom number of multiprocessing workers for faster processing', 'run the deduplicate_lines script on multiple input files to deduplicate across all of them', 'review the get_hashes_and_lines function that computes an MD5 hash for a raw line of data', 'review the main function that uses a set to track seen hashes and writes unique lines to stdout', 'run the script to extract back-translations from fairseq-generate stdout into source and target language files', 'run the script with minlen, maxlen, and ratio filters to extract filtered back-translation pairs', 'run the script on multiple input files to extract back-translations and write paired output files', 'review the validate function that filters sentence pairs by min length, max length, and length ratio', 'review the safe_index helper that safely retrieves a list element with a default fallback value']
```

Usage

```
{'run_extract_bt_data': 'run the script to extract back-translations from fairseq-generate stdout into source and target language files', 'run_extract_bt_data_with_filters': 'run the script with minlen, maxlen, and ratio filters to extract filtered back-translation pairs', 'run_extract_bt_data_multi_file': 'run the script on multiple input files to extract back-translations and write paired output files', 'review_validate_function': 'review the validate function that filters sentence pairs by min length, max length, and length ratio', 'review_safe_index_function': 'review the safe_index helper that safely retrieves a list element with a default fallback value'}
```

