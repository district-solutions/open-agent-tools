# Agent Python Tools

- repo: facebookresearch/metaicl
- repo_uri: https://github.com/facebookresearch/metaicl

## File: facebookresearch_metaicl/utils/data.py

Prompts

```
['load data from JSONL files using a task config JSON and specified split, k-shot, and seed parameters', 'load data by passing a custom list of dataset names instead of reading from a config file', 'load data and replace all input fields with N/A using the is_null flag for zero-shot evaluation', 'load data using a different config split name than the target split via the config_split parameter', 'review the load_data function to understand how it reads JSONL files and merges data from multiple datasets', 'run the download script with --demo_data to fetch the financial phrasebank training data', 'run the download script with --checkpoints to download all trained model checkpoints', 'run the download script with --checkpoints --method --setting to download a specific model checkpoint', 'run the download script with --checkpoints --setting all --method all to download every checkpoint', 'run the download script with --data_dir and --checkpoint_dir to specify custom output directories', 'get the checkpoint method, setting, and model path for a given MetaICL key like metaicl or multitask-zero', 'download a file from a URL or Google Drive ID to a specified destination path using wget', 'download and automatically unzip a .zip file from a URL to a specified destination directory', 'review the get_checkpoint_id function to understand how it resolves MetaICL method keys to checkpoint paths', 'review the download_file function to understand how it handles URL downloads and automatic zip extraction']
```

Usage

```
{'load_data_from_config': 'load data from JSONL files using a task config JSON and specified split, k-shot, and seed parameters', 'load_data_with_datasets': 'load data by passing a custom list of dataset names instead of reading from a config file', 'load_data_with_null_input': 'load data and replace all input fields with N/A using the is_null flag for zero-shot evaluation', 'load_data_custom_config_split': 'load data using a different config split name than the target split via the config_split parameter', 'review_load_data': 'review the load_data function to understand how it reads JSONL files and merges data from multiple datasets'}
```

## File: facebookresearch_metaicl/utils/download.py

Prompts

```
['load data from JSONL files using a task config JSON and specified split, k-shot, and seed parameters', 'load data by passing a custom list of dataset names instead of reading from a config file', 'load data and replace all input fields with N/A using the is_null flag for zero-shot evaluation', 'load data using a different config split name than the target split via the config_split parameter', 'review the load_data function to understand how it reads JSONL files and merges data from multiple datasets', 'run the download script with --demo_data to fetch the financial phrasebank training data', 'run the download script with --checkpoints to download all trained model checkpoints', 'run the download script with --checkpoints --method --setting to download a specific model checkpoint', 'run the download script with --checkpoints --setting all --method all to download every checkpoint', 'run the download script with --data_dir and --checkpoint_dir to specify custom output directories', 'get the checkpoint method, setting, and model path for a given MetaICL key like metaicl or multitask-zero', 'download a file from a URL or Google Drive ID to a specified destination path using wget', 'download and automatically unzip a .zip file from a URL to a specified destination directory', 'review the get_checkpoint_id function to understand how it resolves MetaICL method keys to checkpoint paths', 'review the download_file function to understand how it handles URL downloads and automatic zip extraction']
```

Usage

```
{'run_download_demo_data': 'run the download script with --demo_data to fetch the financial phrasebank training data', 'run_download_checkpoints': 'run the download script with --checkpoints to download all trained model checkpoints', 'run_download_specific_checkpoint': 'run the download script with --checkpoints --method --setting to download a specific model checkpoint', 'run_download_all_checkpoints': 'run the download script with --checkpoints --setting all --method all to download every checkpoint', 'run_download_with_custom_dirs': 'run the download script with --data_dir and --checkpoint_dir to specify custom output directories'}
```

## File: facebookresearch_metaicl/utils/utils.py

Prompts

```
['load data from JSONL files using a task config JSON and specified split, k-shot, and seed parameters', 'load data by passing a custom list of dataset names instead of reading from a config file', 'load data and replace all input fields with N/A using the is_null flag for zero-shot evaluation', 'load data using a different config split name than the target split via the config_split parameter', 'review the load_data function to understand how it reads JSONL files and merges data from multiple datasets', 'run the download script with --demo_data to fetch the financial phrasebank training data', 'run the download script with --checkpoints to download all trained model checkpoints', 'run the download script with --checkpoints --method --setting to download a specific model checkpoint', 'run the download script with --checkpoints --setting all --method all to download every checkpoint', 'run the download script with --data_dir and --checkpoint_dir to specify custom output directories', 'get the checkpoint method, setting, and model path for a given MetaICL key like metaicl or multitask-zero', 'download a file from a URL or Google Drive ID to a specified destination path using wget', 'download and automatically unzip a .zip file from a URL to a specified destination directory', 'review the get_checkpoint_id function to understand how it resolves MetaICL method keys to checkpoint paths', 'review the download_file function to understand how it handles URL downloads and automatic zip extraction']
```

Usage

```
{'get_checkpoint_id': 'get the checkpoint method, setting, and model path for a given MetaICL key like metaicl or multitask-zero', 'download_file_url': 'download a file from a URL or Google Drive ID to a specified destination path using wget', 'download_file_zip': 'download and automatically unzip a .zip file from a URL to a specified destination directory', 'review_get_checkpoint_id': 'review the get_checkpoint_id function to understand how it resolves MetaICL method keys to checkpoint paths', 'review_download_file': 'review the download_file function to understand how it handles URL downloads and automatic zip extraction'}
```

