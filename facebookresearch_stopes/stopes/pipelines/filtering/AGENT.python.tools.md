# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/pipelines/filtering/configs.py

Prompts

```
['call register_configs to store all filter dataclasses in the Hydra ConfigStore for filtering pipelines', 'create a FilterConfig dataclass instance with data_conf_dir, output_dir, executor, directions, and group filter configs', 'create a GroupFilterConfig with included or excluded corpora and optional laser, length, lid, toxicity, and dedup filters', 'create a LidFilterConfig dataclass with model_path, excluded languages, and language-specific detection thresholds', 'create a FilterConfig with an ExecutorConfig specifying log_folder, cluster type, and optional slurm partition', 'run the filter pipeline on train_primary, train_mined, and train_bt data groups using hydra config', 'run filter_direction to apply laser, length, lid, toxicity, and dedup filters on a language direction dataset', 'run filter_group to schedule and execute filtering jobs for a named data group via submitit executor', 'refactor filter_direction to use MultiprocLineProcessor instead of sequential line-by-line filtering', 'review filter_group to understand how it submits parallel filtering jobs via submitit AutoExecutor', 'build a python module that generates n-grams from a string by stripping spaces and extracting character sequences of a given order', 'create a function that normalizes unicode text using NFKC normalization and collapses whitespace into single spaces', 'test the cache_step_sync decorator that caches function results to disk and reuses them when input kwargs match', 'refactor the check_cache function to compare cached input kwargs against current kwargs and return cached results on match', 'summarize the cache_results function that pickles function output and input kwargs into separate files in a progress directory']
```

Usage

```
{'register_Hydra_configs': 'call register_configs to store all filter dataclasses in the Hydra ConfigStore for filtering pipelines', 'create_FilterConfig': 'create a FilterConfig dataclass instance with data_conf_dir, output_dir, executor, directions, and group filter configs', 'create_GroupFilterConfig': 'create a GroupFilterConfig with included or excluded corpora and optional laser, length, lid, toxicity, and dedup filters', 'create_LidFilterConfig': 'create a LidFilterConfig dataclass with model_path, excluded languages, and language-specific detection thresholds', 'create_FilterConfig_with_executor': 'create a FilterConfig with an ExecutorConfig specifying log_folder, cluster type, and optional slurm partition'}
```

## File: facebookresearch_stopes/stopes/pipelines/filtering/filter.py

Prompts

```
['call register_configs to store all filter dataclasses in the Hydra ConfigStore for filtering pipelines', 'create a FilterConfig dataclass instance with data_conf_dir, output_dir, executor, directions, and group filter configs', 'create a GroupFilterConfig with included or excluded corpora and optional laser, length, lid, toxicity, and dedup filters', 'create a LidFilterConfig dataclass with model_path, excluded languages, and language-specific detection thresholds', 'create a FilterConfig with an ExecutorConfig specifying log_folder, cluster type, and optional slurm partition', 'run the filter pipeline on train_primary, train_mined, and train_bt data groups using hydra config', 'run filter_direction to apply laser, length, lid, toxicity, and dedup filters on a language direction dataset', 'run filter_group to schedule and execute filtering jobs for a named data group via submitit executor', 'refactor filter_direction to use MultiprocLineProcessor instead of sequential line-by-line filtering', 'review filter_group to understand how it submits parallel filtering jobs via submitit AutoExecutor', 'build a python module that generates n-grams from a string by stripping spaces and extracting character sequences of a given order', 'create a function that normalizes unicode text using NFKC normalization and collapses whitespace into single spaces', 'test the cache_step_sync decorator that caches function results to disk and reuses them when input kwargs match', 'refactor the check_cache function to compare cached input kwargs against current kwargs and return cached results on match', 'summarize the cache_results function that pickles function output and input kwargs into separate files in a progress directory']
```

Usage

```
{'run_filter_pipeline': 'run the filter pipeline on train_primary, train_mined, and train_bt data groups using hydra config', 'run_filter_direction': 'run filter_direction to apply laser, length, lid, toxicity, and dedup filters on a language direction dataset', 'run_filter_group': 'run filter_group to schedule and execute filtering jobs for a named data group via submitit executor', 'refactor_filter_direction': 'refactor filter_direction to use MultiprocLineProcessor instead of sequential line-by-line filtering', 'review_filter_group': 'review filter_group to understand how it submits parallel filtering jobs via submitit AutoExecutor'}
```

## File: facebookresearch_stopes/stopes/pipelines/filtering/utils.py

Prompts

```
['call register_configs to store all filter dataclasses in the Hydra ConfigStore for filtering pipelines', 'create a FilterConfig dataclass instance with data_conf_dir, output_dir, executor, directions, and group filter configs', 'create a GroupFilterConfig with included or excluded corpora and optional laser, length, lid, toxicity, and dedup filters', 'create a LidFilterConfig dataclass with model_path, excluded languages, and language-specific detection thresholds', 'create a FilterConfig with an ExecutorConfig specifying log_folder, cluster type, and optional slurm partition', 'run the filter pipeline on train_primary, train_mined, and train_bt data groups using hydra config', 'run filter_direction to apply laser, length, lid, toxicity, and dedup filters on a language direction dataset', 'run filter_group to schedule and execute filtering jobs for a named data group via submitit executor', 'refactor filter_direction to use MultiprocLineProcessor instead of sequential line-by-line filtering', 'review filter_group to understand how it submits parallel filtering jobs via submitit AutoExecutor', 'build a python module that generates n-grams from a string by stripping spaces and extracting character sequences of a given order', 'create a function that normalizes unicode text using NFKC normalization and collapses whitespace into single spaces', 'test the cache_step_sync decorator that caches function results to disk and reuses them when input kwargs match', 'refactor the check_cache function to compare cached input kwargs against current kwargs and return cached results on match', 'summarize the cache_results function that pickles function output and input kwargs into separate files in a progress directory']
```

Usage

```
{'build_ngrams': 'build a python module that generates n-grams from a string by stripping spaces and extracting character sequences of a given order', 'create_normalize_unicode': 'create a function that normalizes unicode text using NFKC normalization and collapses whitespace into single spaces', 'test_cache_step_sync': 'test the cache_step_sync decorator that caches function results to disk and reuses them when input kwargs match', 'refactor_check_cache': 'refactor the check_cache function to compare cached input kwargs against current kwargs and return cached results on match', 'summarize_cache_results': 'summarize the cache_results function that pickles function output and input kwargs into separate files in a progress directory'}
```

