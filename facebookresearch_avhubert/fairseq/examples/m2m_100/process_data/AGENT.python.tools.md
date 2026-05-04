# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/m2m_100/process_data/clean_histogram.py

Prompts

```
['run the script to filter parallel source and target language files by character histogram thresholds', 'run the read_hist function to extract accepted characters from a histogram file until the threshold character', 'build a pipeline that filters bilingual parallel corpus lines based on accepted character ratios per language', 'review the argparse CLI arguments for configuring source language, target language, input files, output files, and threshold settings', 'summarize the logic that compares character acceptance ratios against a threshold to decide which parallel lines to keep', 'run the dedup_data script with --start-index and --size arguments to deduplicate M2M100 training data', 'run the main function to deduplicate a slice of language pairs from training data', "run the dedup function to remove duplicate lines from a language pair's source and target training files", 'run the existing_data function to load all lines from evaluation data files into a dedup set', 'review the dedup_data module that removes duplicate training samples from M2M100 multilingual datasets', 'run the script to filter bilingual TSV data by removing sentences with excessive punctuation', 'run the filter_overpunc function to check if a sentence has less than 50 percent punctuation characters', 'run the len_no_punc function to count punctuation characters in a given string', 'review the main function that reads gzipped TSV bitext and writes filtered source and target language files', 'refactor the len_no_punc function to correctly count non-punctuation characters instead of punctuation characters']
```

Usage

```
{'run_clean_histogram_filter': 'run the script to filter parallel source and target language files by character histogram thresholds', 'run_read_hist_function': 'run the read_hist function to extract accepted characters from a histogram file until the threshold character', 'build_character_filter_pipeline': 'build a pipeline that filters bilingual parallel corpus lines based on accepted character ratios per language', 'review_clean_histogram_args': 'review the argparse CLI arguments for configuring source language, target language, input files, output files, and threshold settings', 'summarize_histogram_cleaning_logic': 'summarize the logic that compares character acceptance ratios against a threshold to decide which parallel lines to keep'}
```

## File: facebookresearch_avhubert/fairseq/examples/m2m_100/process_data/dedup_data.py

Prompts

```
['run the script to filter parallel source and target language files by character histogram thresholds', 'run the read_hist function to extract accepted characters from a histogram file until the threshold character', 'build a pipeline that filters bilingual parallel corpus lines based on accepted character ratios per language', 'review the argparse CLI arguments for configuring source language, target language, input files, output files, and threshold settings', 'summarize the logic that compares character acceptance ratios against a threshold to decide which parallel lines to keep', 'run the dedup_data script with --start-index and --size arguments to deduplicate M2M100 training data', 'run the main function to deduplicate a slice of language pairs from training data', "run the dedup function to remove duplicate lines from a language pair's source and target training files", 'run the existing_data function to load all lines from evaluation data files into a dedup set', 'review the dedup_data module that removes duplicate training samples from M2M100 multilingual datasets', 'run the script to filter bilingual TSV data by removing sentences with excessive punctuation', 'run the filter_overpunc function to check if a sentence has less than 50 percent punctuation characters', 'run the len_no_punc function to count punctuation characters in a given string', 'review the main function that reads gzipped TSV bitext and writes filtered source and target language files', 'refactor the len_no_punc function to correctly count non-punctuation characters instead of punctuation characters']
```

Usage

```
{'run_dedup_data_cli': 'run the dedup_data script with --start-index and --size arguments to deduplicate M2M100 training data', 'run_main_dedup_language_pairs': 'run the main function to deduplicate a slice of language pairs from training data', 'run_dedup_function': "run the dedup function to remove duplicate lines from a language pair's source and target training files", 'run_existing_data_load': 'run the existing_data function to load all lines from evaluation data files into a dedup set', 'review_dedup_data_module': 'review the dedup_data module that removes duplicate training samples from M2M100 multilingual datasets'}
```

## File: facebookresearch_avhubert/fairseq/examples/m2m_100/process_data/remove_too_much_punc.py

Prompts

```
['run the script to filter parallel source and target language files by character histogram thresholds', 'run the read_hist function to extract accepted characters from a histogram file until the threshold character', 'build a pipeline that filters bilingual parallel corpus lines based on accepted character ratios per language', 'review the argparse CLI arguments for configuring source language, target language, input files, output files, and threshold settings', 'summarize the logic that compares character acceptance ratios against a threshold to decide which parallel lines to keep', 'run the dedup_data script with --start-index and --size arguments to deduplicate M2M100 training data', 'run the main function to deduplicate a slice of language pairs from training data', "run the dedup function to remove duplicate lines from a language pair's source and target training files", 'run the existing_data function to load all lines from evaluation data files into a dedup set', 'review the dedup_data module that removes duplicate training samples from M2M100 multilingual datasets', 'run the script to filter bilingual TSV data by removing sentences with excessive punctuation', 'run the filter_overpunc function to check if a sentence has less than 50 percent punctuation characters', 'run the len_no_punc function to count punctuation characters in a given string', 'review the main function that reads gzipped TSV bitext and writes filtered source and target language files', 'refactor the len_no_punc function to correctly count non-punctuation characters instead of punctuation characters']
```

Usage

```
{'run_remove_too_much_punc': 'run the script to filter bilingual TSV data by removing sentences with excessive punctuation', 'run_filter_overpunc': 'run the filter_overpunc function to check if a sentence has less than 50 percent punctuation characters', 'run_len_no_punc': 'run the len_no_punc function to count punctuation characters in a given string', 'review_main': 'review the main function that reads gzipped TSV bitext and writes filtered source and target language files', 'refactor_len_no_punc': 'refactor the len_no_punc function to correctly count non-punctuation characters instead of punctuation characters'}
```

