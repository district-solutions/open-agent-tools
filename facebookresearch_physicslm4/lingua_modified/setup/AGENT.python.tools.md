# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/lingua_modified/setup/download_prepare_hf_data.py

Prompts

```
['run the CLI to download, shuffle, and split a HuggingFace dataset like fineweb_edu into chunks', 'download a HuggingFace dataset with retry logic using snapshot_download and allow_patterns filtering', 'convert parquet files to JSONL format using a datatrove LocalPipelineExecutor with ParquetReader and JsonlWriter', 'clone and compile the terashuf tool from GitHub for fast large-scale file shuffling', 'execute a shell command via subprocess.run with shell=True and print the command before running']
```

Usage

```
{'run_download_prepare_hf_data': 'run the CLI to download, shuffle, and split a HuggingFace dataset like fineweb_edu into chunks', 'download_dataset_from_hf': 'download a HuggingFace dataset with retry logic using snapshot_download and allow_patterns filtering', 'convert_parquet_to_jsonl': 'convert parquet files to JSONL format using a datatrove LocalPipelineExecutor with ParquetReader and JsonlWriter', 'setup_terashuf_for_shuffling': 'clone and compile the terashuf tool from GitHub for fast large-scale file shuffling', 'run_command_subprocess': 'execute a shell command via subprocess.run with shell=True and print the command before running'}
```

