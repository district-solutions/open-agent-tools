# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/examples/m2m_100/process_data/clean_histogram.py

Prompts

```
['run the script to filter parallel source and target language files by character histogram acceptance threshold', 'run the read_hist function to extract accepted characters from a histogram file until the threshold character', 'build a parallel data cleaner that filters bilingual sentence pairs based on character acceptance ratios', 'refactor the read_hist function to accept the threshold character as a parameter instead of using global args', 'review the clean_histogram CLI arguments and histogram-based filtering logic for parallel corpus cleaning', 'run the dedup_data script with start-index and size arguments to deduplicate M2M-100 training data', 'run the main function to deduplicate parallel training data for a subset of language pairs', 'run the dedup function to remove duplicate lines from source and target training files', 'run the existing_data function to load all lines from evaluation data files into a set', 'review the dedup function that filters training data by removing lines found in the evaluation set', 'run the script to filter sentences with excessive punctuation from a gzipped TSV bitext file', 'run main to extract source and target columns from a gzipped TSV and write filtered bitext files', 'run len_no_punc to count the number of punctuation characters in a given string', 'run filter_overpunc to check if a sentence has less than 50 percent punctuation characters', 'run the CLI with --input --bitext --src-lang --tgt-lang to filter over-punctuated parallel corpus lines']
```

Usage

```
{'run_clean_histogram_filter': 'run the script to filter parallel source and target language files by character histogram acceptance threshold', 'run_read_hist_function': 'run the read_hist function to extract accepted characters from a histogram file until the threshold character', 'build_parallel_data_cleaner': 'build a parallel data cleaner that filters bilingual sentence pairs based on character acceptance ratios', 'refactor_read_hist': 'refactor the read_hist function to accept the threshold character as a parameter instead of using global args', 'review_clean_histogram_cli': 'review the clean_histogram CLI arguments and histogram-based filtering logic for parallel corpus cleaning'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/m2m_100/process_data/dedup_data.py

Prompts

```
['run the script to filter parallel source and target language files by character histogram acceptance threshold', 'run the read_hist function to extract accepted characters from a histogram file until the threshold character', 'build a parallel data cleaner that filters bilingual sentence pairs based on character acceptance ratios', 'refactor the read_hist function to accept the threshold character as a parameter instead of using global args', 'review the clean_histogram CLI arguments and histogram-based filtering logic for parallel corpus cleaning', 'run the dedup_data script with start-index and size arguments to deduplicate M2M-100 training data', 'run the main function to deduplicate parallel training data for a subset of language pairs', 'run the dedup function to remove duplicate lines from source and target training files', 'run the existing_data function to load all lines from evaluation data files into a set', 'review the dedup function that filters training data by removing lines found in the evaluation set', 'run the script to filter sentences with excessive punctuation from a gzipped TSV bitext file', 'run main to extract source and target columns from a gzipped TSV and write filtered bitext files', 'run len_no_punc to count the number of punctuation characters in a given string', 'run filter_overpunc to check if a sentence has less than 50 percent punctuation characters', 'run the CLI with --input --bitext --src-lang --tgt-lang to filter over-punctuated parallel corpus lines']
```

Usage

```
{'run_dedup_data_cli': 'run the dedup_data script with start-index and size arguments to deduplicate M2M-100 training data', 'run_main_function': 'run the main function to deduplicate parallel training data for a subset of language pairs', 'run_dedup_function': 'run the dedup function to remove duplicate lines from source and target training files', 'run_existing_data_function': 'run the existing_data function to load all lines from evaluation data files into a set', 'review_dedup_function': 'review the dedup function that filters training data by removing lines found in the evaluation set'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/m2m_100/process_data/remove_too_much_punc.py

Prompts

```
['run the script to filter parallel source and target language files by character histogram acceptance threshold', 'run the read_hist function to extract accepted characters from a histogram file until the threshold character', 'build a parallel data cleaner that filters bilingual sentence pairs based on character acceptance ratios', 'refactor the read_hist function to accept the threshold character as a parameter instead of using global args', 'review the clean_histogram CLI arguments and histogram-based filtering logic for parallel corpus cleaning', 'run the dedup_data script with start-index and size arguments to deduplicate M2M-100 training data', 'run the main function to deduplicate parallel training data for a subset of language pairs', 'run the dedup function to remove duplicate lines from source and target training files', 'run the existing_data function to load all lines from evaluation data files into a set', 'review the dedup function that filters training data by removing lines found in the evaluation set', 'run the script to filter sentences with excessive punctuation from a gzipped TSV bitext file', 'run main to extract source and target columns from a gzipped TSV and write filtered bitext files', 'run len_no_punc to count the number of punctuation characters in a given string', 'run filter_overpunc to check if a sentence has less than 50 percent punctuation characters', 'run the CLI with --input --bitext --src-lang --tgt-lang to filter over-punctuated parallel corpus lines']
```

Usage

```
{'run_remove_too_much_punc': 'run the script to filter sentences with excessive punctuation from a gzipped TSV bitext file', 'run_main_bitext_filter': 'run main to extract source and target columns from a gzipped TSV and write filtered bitext files', 'run_len_no_punc': 'run len_no_punc to count the number of punctuation characters in a given string', 'run_filter_overpunc': 'run filter_overpunc to check if a sentence has less than 50 percent punctuation characters', 'run_cli_punctuation_filter': 'run the CLI with --input --bitext --src-lang --tgt-lang to filter over-punctuated parallel corpus lines'}
```

