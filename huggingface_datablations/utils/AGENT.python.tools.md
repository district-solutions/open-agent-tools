# Agent Python Tools

- repo: huggingface/datablations
- repo_uri: https://github.com/huggingface/datablations

## File: huggingface_datablations/utils/flops-params_py.py

Prompts

```
['calculate the total FLOPs for a transformer model given dataset size, hidden size, num heads, and num layers', 'calculate the total number of parameters for a transformer model given hidden size, num heads, and num layers', 'estimate training FLOPs using the simple 2x params times dataset size formula for a transformer model', 'compute the required dataset size in tokens given a target FLOP count and transformer model architecture', 'refactor the full_flops function to support additional attention mechanisms or custom layer configurations', 'run the CLI to subsample a HuggingFace dataset by byte ratio and export JSONL files', 'create a function that computes the byte length of each text example in a batch', 'create a function that sums the total byte size of all examples in a dataset', 'create a function that generates the output JSONL file path for a given subsample ratio', 'review the argparse configuration for dataset name, subset, ratios, shuffle seed, and output naming', 'run hub-sync to push new and modified files matching patterns to a Hugging Face hub repo', 'get a dictionary of files grouped by their git status in a local directory', 'get a list of untracked files in a git working directory', 'get a list of modified files in a git working directory', 'get a list of all new and modified files in a git working directory recursively', 'run the merge_generative script to merge all JSON files in a directory into merged.json', 'run find_all_json to recursively find all JSON files in a given directory', 'run sort_dict to recursively sort dictionary keys and list values in a nested dictionary', 'refactor merge_generative to support additional bigscience evaluation file formats beyond lm-eval-harness and t-zero', 'review the find_all_json function for recursive JSON file discovery in a directory tree']
```

Usage

```
{'calculate_full_flops': 'calculate the total FLOPs for a transformer model given dataset size, hidden size, num heads, and num layers', 'calculate_model_params': 'calculate the total number of parameters for a transformer model given hidden size, num heads, and num layers', 'calculate_simple_flops': 'estimate training FLOPs using the simple 2x params times dataset size formula for a transformer model', 'get_dataset_size_from_flops': 'compute the required dataset size in tokens given a target FLOP count and transformer model architecture', 'refactor_flops_calculation': 'refactor the full_flops function to support additional attention mechanisms or custom layer configurations'}
```

## File: huggingface_datablations/utils/hf_dataset_subsampling.py

Prompts

```
['calculate the total FLOPs for a transformer model given dataset size, hidden size, num heads, and num layers', 'calculate the total number of parameters for a transformer model given hidden size, num heads, and num layers', 'estimate training FLOPs using the simple 2x params times dataset size formula for a transformer model', 'compute the required dataset size in tokens given a target FLOP count and transformer model architecture', 'refactor the full_flops function to support additional attention mechanisms or custom layer configurations', 'run the CLI to subsample a HuggingFace dataset by byte ratio and export JSONL files', 'create a function that computes the byte length of each text example in a batch', 'create a function that sums the total byte size of all examples in a dataset', 'create a function that generates the output JSONL file path for a given subsample ratio', 'review the argparse configuration for dataset name, subset, ratios, shuffle seed, and output naming', 'run hub-sync to push new and modified files matching patterns to a Hugging Face hub repo', 'get a dictionary of files grouped by their git status in a local directory', 'get a list of untracked files in a git working directory', 'get a list of modified files in a git working directory', 'get a list of all new and modified files in a git working directory recursively', 'run the merge_generative script to merge all JSON files in a directory into merged.json', 'run find_all_json to recursively find all JSON files in a given directory', 'run sort_dict to recursively sort dictionary keys and list values in a nested dictionary', 'refactor merge_generative to support additional bigscience evaluation file formats beyond lm-eval-harness and t-zero', 'review the find_all_json function for recursive JSON file discovery in a directory tree']
```

Usage

```
{'run_dataset_subsampling': 'run the CLI to subsample a HuggingFace dataset by byte ratio and export JSONL files', 'create_get_size_per_example': 'create a function that computes the byte length of each text example in a batch', 'create_get_total_byte_size': 'create a function that sums the total byte size of all examples in a dataset', 'create_output_path': 'create a function that generates the output JSONL file path for a given subsample ratio', 'review_get_args': 'review the argparse configuration for dataset name, subset, ratios, shuffle seed, and output naming'}
```

## File: huggingface_datablations/utils/hub_sync.py

Prompts

```
['calculate the total FLOPs for a transformer model given dataset size, hidden size, num heads, and num layers', 'calculate the total number of parameters for a transformer model given hidden size, num heads, and num layers', 'estimate training FLOPs using the simple 2x params times dataset size formula for a transformer model', 'compute the required dataset size in tokens given a target FLOP count and transformer model architecture', 'refactor the full_flops function to support additional attention mechanisms or custom layer configurations', 'run the CLI to subsample a HuggingFace dataset by byte ratio and export JSONL files', 'create a function that computes the byte length of each text example in a batch', 'create a function that sums the total byte size of all examples in a dataset', 'create a function that generates the output JSONL file path for a given subsample ratio', 'review the argparse configuration for dataset name, subset, ratios, shuffle seed, and output naming', 'run hub-sync to push new and modified files matching patterns to a Hugging Face hub repo', 'get a dictionary of files grouped by their git status in a local directory', 'get a list of untracked files in a git working directory', 'get a list of modified files in a git working directory', 'get a list of all new and modified files in a git working directory recursively', 'run the merge_generative script to merge all JSON files in a directory into merged.json', 'run find_all_json to recursively find all JSON files in a given directory', 'run sort_dict to recursively sort dictionary keys and list values in a nested dictionary', 'refactor merge_generative to support additional bigscience evaluation file formats beyond lm-eval-harness and t-zero', 'review the find_all_json function for recursive JSON file discovery in a directory tree']
```

Usage

```
{'run_hub_sync': 'run hub-sync to push new and modified files matching patterns to a Hugging Face hub repo', 'get_git_files_by_status': 'get a dictionary of files grouped by their git status in a local directory', 'get_untracked_files': 'get a list of untracked files in a git working directory', 'get_modified_files': 'get a list of modified files in a git working directory', 'get_new_and_modified_files': 'get a list of all new and modified files in a git working directory recursively'}
```

## File: huggingface_datablations/utils/merge_generative.py

Prompts

```
['calculate the total FLOPs for a transformer model given dataset size, hidden size, num heads, and num layers', 'calculate the total number of parameters for a transformer model given hidden size, num heads, and num layers', 'estimate training FLOPs using the simple 2x params times dataset size formula for a transformer model', 'compute the required dataset size in tokens given a target FLOP count and transformer model architecture', 'refactor the full_flops function to support additional attention mechanisms or custom layer configurations', 'run the CLI to subsample a HuggingFace dataset by byte ratio and export JSONL files', 'create a function that computes the byte length of each text example in a batch', 'create a function that sums the total byte size of all examples in a dataset', 'create a function that generates the output JSONL file path for a given subsample ratio', 'review the argparse configuration for dataset name, subset, ratios, shuffle seed, and output naming', 'run hub-sync to push new and modified files matching patterns to a Hugging Face hub repo', 'get a dictionary of files grouped by their git status in a local directory', 'get a list of untracked files in a git working directory', 'get a list of modified files in a git working directory', 'get a list of all new and modified files in a git working directory recursively', 'run the merge_generative script to merge all JSON files in a directory into merged.json', 'run find_all_json to recursively find all JSON files in a given directory', 'run sort_dict to recursively sort dictionary keys and list values in a nested dictionary', 'refactor merge_generative to support additional bigscience evaluation file formats beyond lm-eval-harness and t-zero', 'review the find_all_json function for recursive JSON file discovery in a directory tree']
```

Usage

```
{'run_merge_json': 'run the merge_generative script to merge all JSON files in a directory into merged.json', 'run_find_all_json': 'run find_all_json to recursively find all JSON files in a given directory', 'run_sort_dict': 'run sort_dict to recursively sort dictionary keys and list values in a nested dictionary', 'refactor_merge_generative': 'refactor merge_generative to support additional bigscience evaluation file formats beyond lm-eval-harness and t-zero', 'review_find_all_json': 'review the find_all_json function for recursive JSON file discovery in a directory tree'}
```

