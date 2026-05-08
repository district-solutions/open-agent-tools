# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/m2m_100/process_data/clean_histogram.py

Prompts

```
['run the clean_histogram script to filter parallel translation files based on character histogram thresholds', 'run the read_hist function to extract accepted characters from a histogram file up to a threshold character', 'build a tool to clean parallel source and target translation files using character acceptance thresholds', 'refactor the read_hist function to support configurable threshold characters for histogram parsing', 'review the clean_histogram script and its parallel file filtering logic based on character ratios', 'run the dedup_data script with --start-index and --size to deduplicate M2M100 training data', 'run the dedup function to remove duplicate lines from parallel source and target training files', 'run the existing_data function to load all lines from evaluation data files into a dedup set', 'review the dedup function logic that filters training pairs where source or target lines exist in eval data', 'refactor the dedup_data module to accept DATADIR, DEDUP_FROM_DIR, and OUTPUT_DIR as CLI arguments instead of hardcoded paths', 'run the script to filter bilingual TSV data by removing sentences with excessive punctuation', 'run main to read a gzipped TSV and write filtered source and target language files', 'test the len_no_punc function to count punctuation characters in a given string', 'test the filter_overpunc function to check if a sentence has less than 50 percent punctuation', 'refactor the main function to process all lines in the TSV instead of only the first line']
```

Usage

```
{'run_clean_histogram_filter': 'run the clean_histogram script to filter parallel translation files based on character histogram thresholds', 'run_read_hist_function': 'run the read_hist function to extract accepted characters from a histogram file up to a threshold character', 'build_parallel_data_cleaner': 'build a tool to clean parallel source and target translation files using character acceptance thresholds', 'refactor_read_hist': 'refactor the read_hist function to support configurable threshold characters for histogram parsing', 'review_clean_histogram_filtering': 'review the clean_histogram script and its parallel file filtering logic based on character ratios'}
```

## File: facebookresearch_fairseq/examples/m2m_100/process_data/dedup_data.py

Prompts

```
['run the clean_histogram script to filter parallel translation files based on character histogram thresholds', 'run the read_hist function to extract accepted characters from a histogram file up to a threshold character', 'build a tool to clean parallel source and target translation files using character acceptance thresholds', 'refactor the read_hist function to support configurable threshold characters for histogram parsing', 'review the clean_histogram script and its parallel file filtering logic based on character ratios', 'run the dedup_data script with --start-index and --size to deduplicate M2M100 training data', 'run the dedup function to remove duplicate lines from parallel source and target training files', 'run the existing_data function to load all lines from evaluation data files into a dedup set', 'review the dedup function logic that filters training pairs where source or target lines exist in eval data', 'refactor the dedup_data module to accept DATADIR, DEDUP_FROM_DIR, and OUTPUT_DIR as CLI arguments instead of hardcoded paths', 'run the script to filter bilingual TSV data by removing sentences with excessive punctuation', 'run main to read a gzipped TSV and write filtered source and target language files', 'test the len_no_punc function to count punctuation characters in a given string', 'test the filter_overpunc function to check if a sentence has less than 50 percent punctuation', 'refactor the main function to process all lines in the TSV instead of only the first line']
```

Usage

```
{'run_dedup_data_cli': 'run the dedup_data script with --start-index and --size to deduplicate M2M100 training data', 'run_dedup_function': 'run the dedup function to remove duplicate lines from parallel source and target training files', 'run_existing_data_function': 'run the existing_data function to load all lines from evaluation data files into a dedup set', 'review_dedup_function': 'review the dedup function logic that filters training pairs where source or target lines exist in eval data', 'refactor_dedup_data_paths': 'refactor the dedup_data module to accept DATADIR, DEDUP_FROM_DIR, and OUTPUT_DIR as CLI arguments instead of hardcoded paths'}
```

## File: facebookresearch_fairseq/examples/m2m_100/process_data/remove_too_much_punc.py

Prompts

```
['run the clean_histogram script to filter parallel translation files based on character histogram thresholds', 'run the read_hist function to extract accepted characters from a histogram file up to a threshold character', 'build a tool to clean parallel source and target translation files using character acceptance thresholds', 'refactor the read_hist function to support configurable threshold characters for histogram parsing', 'review the clean_histogram script and its parallel file filtering logic based on character ratios', 'run the dedup_data script with --start-index and --size to deduplicate M2M100 training data', 'run the dedup function to remove duplicate lines from parallel source and target training files', 'run the existing_data function to load all lines from evaluation data files into a dedup set', 'review the dedup function logic that filters training pairs where source or target lines exist in eval data', 'refactor the dedup_data module to accept DATADIR, DEDUP_FROM_DIR, and OUTPUT_DIR as CLI arguments instead of hardcoded paths', 'run the script to filter bilingual TSV data by removing sentences with excessive punctuation', 'run main to read a gzipped TSV and write filtered source and target language files', 'test the len_no_punc function to count punctuation characters in a given string', 'test the filter_overpunc function to check if a sentence has less than 50 percent punctuation', 'refactor the main function to process all lines in the TSV instead of only the first line']
```

Usage

```
{'run_remove_too_much_punc': 'run the script to filter bilingual TSV data by removing sentences with excessive punctuation', 'run_main_filter_bitext': 'run main to read a gzipped TSV and write filtered source and target language files', 'test_len_no_punc': 'test the len_no_punc function to count punctuation characters in a given string', 'test_filter_overpunc': 'test the filter_overpunc function to check if a sentence has less than 50 percent punctuation', 'refactor_main_loop': 'refactor the main function to process all lines in the TSV instead of only the first line'}
```

