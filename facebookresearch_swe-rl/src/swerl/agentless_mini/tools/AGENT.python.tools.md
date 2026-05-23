# Agent Python Tools

- repo: facebookresearch/swe-rl
- repo_uri: https://github.com/facebookresearch/swe-rl

## File: facebookresearch_swe-rl/src/swerl/agentless_mini/tools/check_loc_perf.py

Prompts

```
['run the localization performance checker on a JSON location file against SWE-bench dataset', 'run get_all_filenames to extract Python filenames from a git diff string', 'run map_to_analysis to compute coverage metrics for found files against ground truth', 'run reduce_fn to aggregate two analysis result dictionaries into combined metrics', 'review the Args dataclass defining locfile, dataset, num_proc, and max_samples parameters', 'run the script to extract Python filenames from SWE-bench dataset patches and save to JSON', 'run map_to_files to map a dataset instance dict to its instance_id and found Python files', 'summarize the prepare_gt_files module that loads a SWE-bench dataset, extracts ground truth Python filenames from patches, and exports to JSON']
```

Usage

```
{'run_check_loc_perf': 'run the localization performance checker on a JSON location file against SWE-bench dataset', 'run_get_all_filenames': 'run get_all_filenames to extract Python filenames from a git diff string', 'run_map_to_analysis': 'run map_to_analysis to compute coverage metrics for found files against ground truth', 'run_reduce_fn': 'run reduce_fn to aggregate two analysis result dictionaries into combined metrics', 'review_Args': 'review the Args dataclass defining locfile, dataset, num_proc, and max_samples parameters'}
```

## File: facebookresearch_swe-rl/src/swerl/agentless_mini/tools/prepare_gt_files.py

Prompts

```
['run the localization performance checker on a JSON location file against SWE-bench dataset', 'run get_all_filenames to extract Python filenames from a git diff string', 'run map_to_analysis to compute coverage metrics for found files against ground truth', 'run reduce_fn to aggregate two analysis result dictionaries into combined metrics', 'review the Args dataclass defining locfile, dataset, num_proc, and max_samples parameters', 'run the script to extract Python filenames from SWE-bench dataset patches and save to JSON', 'run map_to_files to map a dataset instance dict to its instance_id and found Python files', 'summarize the prepare_gt_files module that loads a SWE-bench dataset, extracts ground truth Python filenames from patches, and exports to JSON']
```

Usage

```
{'run_prepare_gt_files': 'run the script to extract Python filenames from SWE-bench dataset patches and save to JSON', 'run_get_all_filenames': 'run get_all_filenames to extract Python file paths from a git diff string using regex', 'run_map_to_files': 'run map_to_files to map a dataset instance dict to its instance_id and found Python files', 'review_Args': 'review the Args dataclass that defines output_file, dataset, and num_proc parameters for CLI argument parsing', 'summarize_prepare_gt_files': 'summarize the prepare_gt_files module that loads a SWE-bench dataset, extracts ground truth Python filenames from patches, and exports to JSON'}
```

