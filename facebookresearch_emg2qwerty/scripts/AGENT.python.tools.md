# Agent Python Tools

- repo: facebookresearch/emg2qwerty
- repo_uri: https://github.com/facebookresearch/emg2qwerty

## File: facebookresearch_emg2qwerty/scripts/convert_to_bids.py

Prompts

```
['run the CLI script to convert all HDF5 EMG sessions to BIDS format using dataset-root and bids-root options', 'run get_mne_raw to read an HDF5 EMG session file and return an MNE Raw object with keystroke and prompt annotations', 'run convert_to_bids to convert a single HDF5 EMG session file to BIDS BrainVision format in the output directory', 'review get_mne_raw to understand how EMG left and right channel data is concatenated and annotated with keystrokes and prompts', 'review convert_to_bids to understand how subject and session indices map to BIDSPath and how write_raw_bids is configured', 'run the generate_splits CLI to create train val and test YAML configs for EMG dataset users', 'run sample_test_users to select N users with the most sessions for personalization benchmarks', 'run generate_split to partition a DataFrame into train val and test splits per user constraints', 'run filter_users to return users from a DataFrame who have at least a minimum number of sessions', 'run stratified_sample to sample N rows per user from a DataFrame with optional random seed', 'run the script to print statistics about the emg2qwerty dataset from its metadata CSV file', 'run the main CLI command with a custom dataset root path to print dataset statistics', 'run the print_dataset_stats function with a pandas DataFrame to display user-level and aggregate dataset statistics', 'review the print_dataset_stats function that computes per-user counts, duration, keystrokes, and prompts from metadata', 'refactor the main CLI entry point to support additional options for filtering dataset statistics output']
```

Usage

```
{'run_convert_hdf5_to_bids': 'run the CLI script to convert all HDF5 EMG sessions to BIDS format using dataset-root and bids-root options', 'run_get_mne_raw': 'run get_mne_raw to read an HDF5 EMG session file and return an MNE Raw object with keystroke and prompt annotations', 'run_convert_to_bids': 'run convert_to_bids to convert a single HDF5 EMG session file to BIDS BrainVision format in the output directory', 'review_get_mne_raw': 'review get_mne_raw to understand how EMG left and right channel data is concatenated and annotated with keystrokes and prompts', 'review_convert_to_bids': 'review convert_to_bids to understand how subject and session indices map to BIDSPath and how write_raw_bids is configured'}
```

## File: facebookresearch_emg2qwerty/scripts/generate_splits.py

Prompts

```
['run the CLI script to convert all HDF5 EMG sessions to BIDS format using dataset-root and bids-root options', 'run get_mne_raw to read an HDF5 EMG session file and return an MNE Raw object with keystroke and prompt annotations', 'run convert_to_bids to convert a single HDF5 EMG session file to BIDS BrainVision format in the output directory', 'review get_mne_raw to understand how EMG left and right channel data is concatenated and annotated with keystrokes and prompts', 'review convert_to_bids to understand how subject and session indices map to BIDSPath and how write_raw_bids is configured', 'run the generate_splits CLI to create train val and test YAML configs for EMG dataset users', 'run sample_test_users to select N users with the most sessions for personalization benchmarks', 'run generate_split to partition a DataFrame into train val and test splits per user constraints', 'run filter_users to return users from a DataFrame who have at least a minimum number of sessions', 'run stratified_sample to sample N rows per user from a DataFrame with optional random seed', 'run the script to print statistics about the emg2qwerty dataset from its metadata CSV file', 'run the main CLI command with a custom dataset root path to print dataset statistics', 'run the print_dataset_stats function with a pandas DataFrame to display user-level and aggregate dataset statistics', 'review the print_dataset_stats function that computes per-user counts, duration, keystrokes, and prompts from metadata', 'refactor the main CLI entry point to support additional options for filtering dataset statistics output']
```

Usage

```
{'run_generate_splits_cli': 'run the generate_splits CLI to create train val and test YAML configs for EMG dataset users', 'run_sample_test_users': 'run sample_test_users to select N users with the most sessions for personalization benchmarks', 'run_generate_split': 'run generate_split to partition a DataFrame into train val and test splits per user constraints', 'run_filter_users': 'run filter_users to return users from a DataFrame who have at least a minimum number of sessions', 'run_stratified_sample': 'run stratified_sample to sample N rows per user from a DataFrame with optional random seed'}
```

## File: facebookresearch_emg2qwerty/scripts/print_dataset_stats.py

Prompts

```
['run the CLI script to convert all HDF5 EMG sessions to BIDS format using dataset-root and bids-root options', 'run get_mne_raw to read an HDF5 EMG session file and return an MNE Raw object with keystroke and prompt annotations', 'run convert_to_bids to convert a single HDF5 EMG session file to BIDS BrainVision format in the output directory', 'review get_mne_raw to understand how EMG left and right channel data is concatenated and annotated with keystrokes and prompts', 'review convert_to_bids to understand how subject and session indices map to BIDSPath and how write_raw_bids is configured', 'run the generate_splits CLI to create train val and test YAML configs for EMG dataset users', 'run sample_test_users to select N users with the most sessions for personalization benchmarks', 'run generate_split to partition a DataFrame into train val and test splits per user constraints', 'run filter_users to return users from a DataFrame who have at least a minimum number of sessions', 'run stratified_sample to sample N rows per user from a DataFrame with optional random seed', 'run the script to print statistics about the emg2qwerty dataset from its metadata CSV file', 'run the main CLI command with a custom dataset root path to print dataset statistics', 'run the print_dataset_stats function with a pandas DataFrame to display user-level and aggregate dataset statistics', 'review the print_dataset_stats function that computes per-user counts, duration, keystrokes, and prompts from metadata', 'refactor the main CLI entry point to support additional options for filtering dataset statistics output']
```

Usage

```
{'run_print_dataset_stats': 'run the script to print statistics about the emg2qwerty dataset from its metadata CSV file', 'run_main_with_dataset_root': 'run the main CLI command with a custom dataset root path to print dataset statistics', 'run_print_dataset_stats_function': 'run the print_dataset_stats function with a pandas DataFrame to display user-level and aggregate dataset statistics', 'review_print_dataset_stats': 'review the print_dataset_stats function that computes per-user counts, duration, keystrokes, and prompts from metadata', 'refactor_main_cli': 'refactor the main CLI entry point to support additional options for filtering dataset statistics output'}
```

