# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_transformer_model/data_processing_scripts/create_annotated_split.py

Prompts

```
['run the script to split annotated data into train, valid, and test splits with configurable ratios', 'run the script to write a chunk of data lines to a specific output directory and file', 'create train, valid, and test data splits from an annotated dataset using a 70:20:10 ratio', 'refactor the create_data_split function to support additional split names beyond train, valid, and test', 'review the write_data_split function to ensure it creates directories and writes data chunks correctly', 'run the script to preprocess a templated dataset file into training-ready format with pipe delimiters', 'run the preprocess script with custom input and output file paths via command line arguments', 'preprocess templated dialogue examples by joining commands with pipe delimiters and shuffling the dataset', 'filter out examples with more than two commands per chat block during preprocessing', 'summarize the preprocess function that loads templated data, joins commands with pipes, shuffles, and writes output', 'run the script to process templated generation files into ground truth annotations', 'remove duplicate commands, NOOPs, and long commands from a dataset file', 'run the script with --keep_long_commands to preserve commands longer than 6 words', 'run the script with --keep_NOOPs to preserve commands containing NOOP entries', 'review the remove_duplicates_long_commands_and_NOOPs function for parsing pipe-delimited command and action data', 'run the script to update annotated data files with new parse trees from an updated dataset', 'run the script to write a chunk of data lines to a file with optional commands-only mode', 'run the script to load a pipe-delimited data file into a command-to-action dictionary', 'refactor the update_file function to support additional data formats beyond pipe-delimited text', 'review the write_data_chunk_to_file function and its commands_only flag for writing filtered output']
```

Usage

```
{'run_create_data_split': 'run the script to split annotated data into train, valid, and test splits with configurable ratios', 'run_write_data_split': 'run the script to write a chunk of data lines to a specific output directory and file', 'create_train_valid_test_splits': 'create train, valid, and test data splits from an annotated dataset using a 70:20:10 ratio', 'refactor_create_data_split': 'refactor the create_data_split function to support additional split names beyond train, valid, and test', 'review_write_data_split': 'review the write_data_split function to ensure it creates directories and writes data chunks correctly'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_transformer_model/data_processing_scripts/preprocess_templated.py

Prompts

```
['run the script to split annotated data into train, valid, and test splits with configurable ratios', 'run the script to write a chunk of data lines to a specific output directory and file', 'create train, valid, and test data splits from an annotated dataset using a 70:20:10 ratio', 'refactor the create_data_split function to support additional split names beyond train, valid, and test', 'review the write_data_split function to ensure it creates directories and writes data chunks correctly', 'run the script to preprocess a templated dataset file into training-ready format with pipe delimiters', 'run the preprocess script with custom input and output file paths via command line arguments', 'preprocess templated dialogue examples by joining commands with pipe delimiters and shuffling the dataset', 'filter out examples with more than two commands per chat block during preprocessing', 'summarize the preprocess function that loads templated data, joins commands with pipes, shuffles, and writes output', 'run the script to process templated generation files into ground truth annotations', 'remove duplicate commands, NOOPs, and long commands from a dataset file', 'run the script with --keep_long_commands to preserve commands longer than 6 words', 'run the script with --keep_NOOPs to preserve commands containing NOOP entries', 'review the remove_duplicates_long_commands_and_NOOPs function for parsing pipe-delimited command and action data', 'run the script to update annotated data files with new parse trees from an updated dataset', 'run the script to write a chunk of data lines to a file with optional commands-only mode', 'run the script to load a pipe-delimited data file into a command-to-action dictionary', 'refactor the update_file function to support additional data formats beyond pipe-delimited text', 'review the write_data_chunk_to_file function and its commands_only flag for writing filtered output']
```

Usage

```
{'run_preprocess_templated_dataset': 'run the script to preprocess a templated dataset file into training-ready format with pipe delimiters', 'run_preprocess_with_custom_paths': 'run the preprocess script with custom input and output file paths via command line arguments', 'preprocess_templated_examples': 'preprocess templated dialogue examples by joining commands with pipe delimiters and shuffling the dataset', 'filter_multi_chat_examples': 'filter out examples with more than two commands per chat block during preprocessing', 'summarize_preprocess_function': 'summarize the preprocess function that loads templated data, joins commands with pipes, shuffles, and writes output'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_transformer_model/data_processing_scripts/process_files_for_gt.py

Prompts

```
['run the script to split annotated data into train, valid, and test splits with configurable ratios', 'run the script to write a chunk of data lines to a specific output directory and file', 'create train, valid, and test data splits from an annotated dataset using a 70:20:10 ratio', 'refactor the create_data_split function to support additional split names beyond train, valid, and test', 'review the write_data_split function to ensure it creates directories and writes data chunks correctly', 'run the script to preprocess a templated dataset file into training-ready format with pipe delimiters', 'run the preprocess script with custom input and output file paths via command line arguments', 'preprocess templated dialogue examples by joining commands with pipe delimiters and shuffling the dataset', 'filter out examples with more than two commands per chat block during preprocessing', 'summarize the preprocess function that loads templated data, joins commands with pipes, shuffles, and writes output', 'run the script to process templated generation files into ground truth annotations', 'remove duplicate commands, NOOPs, and long commands from a dataset file', 'run the script with --keep_long_commands to preserve commands longer than 6 words', 'run the script with --keep_NOOPs to preserve commands containing NOOP entries', 'review the remove_duplicates_long_commands_and_NOOPs function for parsing pipe-delimited command and action data', 'run the script to update annotated data files with new parse trees from an updated dataset', 'run the script to write a chunk of data lines to a file with optional commands-only mode', 'run the script to load a pipe-delimited data file into a command-to-action dictionary', 'refactor the update_file function to support additional data formats beyond pipe-delimited text', 'review the write_data_chunk_to_file function and its commands_only flag for writing filtered output']
```

Usage

```
{'process_gt_annotations': 'run the script to process templated generation files into ground truth annotations', 'remove_duplicates_long_commands_and_NOOPs': 'remove duplicate commands, NOOPs, and long commands from a dataset file', 'run_with_long_commands': 'run the script with --keep_long_commands to preserve commands longer than 6 words', 'run_with_NOOPs': 'run the script with --keep_NOOPs to preserve commands containing NOOP entries', 'review_remove_duplicates_long_commands_and_NOOPs': 'review the remove_duplicates_long_commands_and_NOOPs function for parsing pipe-delimited command and action data'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_transformer_model/data_processing_scripts/update_valid_test_sets.py

Prompts

```
['run the script to split annotated data into train, valid, and test splits with configurable ratios', 'run the script to write a chunk of data lines to a specific output directory and file', 'create train, valid, and test data splits from an annotated dataset using a 70:20:10 ratio', 'refactor the create_data_split function to support additional split names beyond train, valid, and test', 'review the write_data_split function to ensure it creates directories and writes data chunks correctly', 'run the script to preprocess a templated dataset file into training-ready format with pipe delimiters', 'run the preprocess script with custom input and output file paths via command line arguments', 'preprocess templated dialogue examples by joining commands with pipe delimiters and shuffling the dataset', 'filter out examples with more than two commands per chat block during preprocessing', 'summarize the preprocess function that loads templated data, joins commands with pipes, shuffles, and writes output', 'run the script to process templated generation files into ground truth annotations', 'remove duplicate commands, NOOPs, and long commands from a dataset file', 'run the script with --keep_long_commands to preserve commands longer than 6 words', 'run the script with --keep_NOOPs to preserve commands containing NOOP entries', 'review the remove_duplicates_long_commands_and_NOOPs function for parsing pipe-delimited command and action data', 'run the script to update annotated data files with new parse trees from an updated dataset', 'run the script to write a chunk of data lines to a file with optional commands-only mode', 'run the script to load a pipe-delimited data file into a command-to-action dictionary', 'refactor the update_file function to support additional data formats beyond pipe-delimited text', 'review the write_data_chunk_to_file function and its commands_only flag for writing filtered output']
```

Usage

```
{'run_update_file': 'run the script to update annotated data files with new parse trees from an updated dataset', 'run_write_data_chunk': 'run the script to write a chunk of data lines to a file with optional commands-only mode', 'run_load_file_as_dictionary': 'run the script to load a pipe-delimited data file into a command-to-action dictionary', 'refactor_update_file': 'refactor the update_file function to support additional data formats beyond pipe-delimited text', 'review_write_data_chunk_to_file': 'review the write_data_chunk_to_file function and its commands_only flag for writing filtered output'}
```

