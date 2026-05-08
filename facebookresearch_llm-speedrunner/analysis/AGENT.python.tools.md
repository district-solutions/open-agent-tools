# Agent Python Tools

- repo: facebookresearch/llm-speedrunner
- repo_uri: https://github.com/facebookresearch/llm-speedrunner

## File: facebookresearch_llm-speedrunner/analysis/analyze_embeddings.py

Prompts

```
['compute code embedding distances between LLM solutions and human ground-truth records using a pretrained embedding model', 'build a pandas DataFrame of embedding distances from a JSON file containing LLM run records and human code', 'aggregate embedding distance metrics by method, model, record, and levels then print the grouped means', 'plot aggregated embedding distance metrics filtered by model and hint level with a line chart', 'get a cached code embedding vector for a given text string using the Salesforce SFR embedding model', 'extract a level number from a file path string using regex pattern matching', 'extract a record number from a directory name string using regex pattern matching', 'walk a directory tree and parse config.yaml files to extract level numbers and record info', 'parse config.yaml files matching glob patterns to extract experiment metadata including model, runner, and ideator', 'filter a folder info dictionary by key-value conditions to find matching experiment configurations', 'gather metrics from versioned workspace subdirectories into a sorted pandas DataFrame', 'create a subplot grid of bar charts comparing gap percentages across multiple datasets', 'gather metrics from workspace subdirectories including an optional initial template results file', 'create a bar chart comparison with a custom main title and adaptive subplot layout', 'review the gather_metrics function to understand how it parses versioned results JSON files']
```

Usage

```
{'compute_embedding_distances': 'compute code embedding distances between LLM solutions and human ground-truth records using a pretrained embedding model', 'build_dataframe_from_json': 'build a pandas DataFrame of embedding distances from a JSON file containing LLM run records and human code', 'aggregate_and_print_distances': 'aggregate embedding distance metrics by method, model, record, and levels then print the grouped means', 'plot_embedding_distances': 'plot aggregated embedding distance metrics filtered by model and hint level with a line chart', 'get_code_embedding': 'get a cached code embedding vector for a given text string using the Salesforce SFR embedding model'}
```

## File: facebookresearch_llm-speedrunner/analysis/parse_levels.py

Prompts

```
['compute code embedding distances between LLM solutions and human ground-truth records using a pretrained embedding model', 'build a pandas DataFrame of embedding distances from a JSON file containing LLM run records and human code', 'aggregate embedding distance metrics by method, model, record, and levels then print the grouped means', 'plot aggregated embedding distance metrics filtered by model and hint level with a line chart', 'get a cached code embedding vector for a given text string using the Salesforce SFR embedding model', 'extract a level number from a file path string using regex pattern matching', 'extract a record number from a directory name string using regex pattern matching', 'walk a directory tree and parse config.yaml files to extract level numbers and record info', 'parse config.yaml files matching glob patterns to extract experiment metadata including model, runner, and ideator', 'filter a folder info dictionary by key-value conditions to find matching experiment configurations', 'gather metrics from versioned workspace subdirectories into a sorted pandas DataFrame', 'create a subplot grid of bar charts comparing gap percentages across multiple datasets', 'gather metrics from workspace subdirectories including an optional initial template results file', 'create a bar chart comparison with a custom main title and adaptive subplot layout', 'review the gather_metrics function to understand how it parses versioned results JSON files']
```

Usage

```
{'extract_level_number': 'extract a level number from a file path string using regex pattern matching', 'extract_record_number': 'extract a record number from a directory name string using regex pattern matching', 'find_levels_in_configs': 'walk a directory tree and parse config.yaml files to extract level numbers and record info', 'find_levels_in_configs_glob': 'parse config.yaml files matching glob patterns to extract experiment metadata including model, runner, and ideator', 'filter_folder_info': 'filter a folder info dictionary by key-value conditions to find matching experiment configurations'}
```

## File: facebookresearch_llm-speedrunner/analysis/plot_utils.py

Prompts

```
['compute code embedding distances between LLM solutions and human ground-truth records using a pretrained embedding model', 'build a pandas DataFrame of embedding distances from a JSON file containing LLM run records and human code', 'aggregate embedding distance metrics by method, model, record, and levels then print the grouped means', 'plot aggregated embedding distance metrics filtered by model and hint level with a line chart', 'get a cached code embedding vector for a given text string using the Salesforce SFR embedding model', 'extract a level number from a file path string using regex pattern matching', 'extract a record number from a directory name string using regex pattern matching', 'walk a directory tree and parse config.yaml files to extract level numbers and record info', 'parse config.yaml files matching glob patterns to extract experiment metadata including model, runner, and ideator', 'filter a folder info dictionary by key-value conditions to find matching experiment configurations', 'gather metrics from versioned workspace subdirectories into a sorted pandas DataFrame', 'create a subplot grid of bar charts comparing gap percentages across multiple datasets', 'gather metrics from workspace subdirectories including an optional initial template results file', 'create a bar chart comparison with a custom main title and adaptive subplot layout', 'review the gather_metrics function to understand how it parses versioned results JSON files']
```

Usage

```
{'gather_metrics_from_workspace': 'gather metrics from versioned workspace subdirectories into a sorted pandas DataFrame', 'plot_gap_comparison_subplots': 'create a subplot grid of bar charts comparing gap percentages across multiple datasets', 'gather_metrics_with_template': 'gather metrics from workspace subdirectories including an optional initial template results file', 'plot_gap_comparison_custom_title': 'create a bar chart comparison with a custom main title and adaptive subplot layout', 'review_gather_metrics_function': 'review the gather_metrics function to understand how it parses versioned results JSON files'}
```

