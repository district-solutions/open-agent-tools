# Agent Python Tools

- repo: facebookresearch/lingua
- repo_uri: https://github.com/facebookresearch/lingua

## File: facebookresearch_lingua/setup/download_prepare_hf_data.py

Prompts

```
['run the CLI to download, shuffle, and split a HuggingFace dataset like fineweb_edu into chunks', 'download a HuggingFace dataset to a local directory using snapshot_download with retry logic for timeouts', 'convert Parquet files to JSONL format using a datatrove LocalPipelineExecutor with ParquetReader and JsonlWriter', 'clone and build the terashuf tool from GitHub for fast shuffling of large datasets', 'shuffle dataset files with terashuf and split them into N random chunks for training and validation']
```

Usage

```
{'run_download_prepare_hf_data': 'run the CLI to download, shuffle, and split a HuggingFace dataset like fineweb_edu into chunks', 'download_dataset_from_hf': 'download a HuggingFace dataset to a local directory using snapshot_download with retry logic for timeouts', 'convert_parquet_to_jsonl': 'convert Parquet files to JSONL format using a datatrove LocalPipelineExecutor with ParquetReader and JsonlWriter', 'setup_terashuf_for_shuffling': 'clone and build the terashuf tool from GitHub for fast shuffling of large datasets', 'shuffle_and_split_dataset': 'shuffle dataset files with terashuf and split them into N random chunks for training and validation'}
```

