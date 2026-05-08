# Agent Python Tools

- repo: facebookresearch/llm-speedrunner
- repo_uri: https://github.com/facebookresearch/llm-speedrunner

## File: facebookresearch_llm-speedrunner/tests/test_metrics_utils.py

Prompts

```
['extract key-value metrics from a single line of training log text with type casting', 'find the best training log line by selecting the highest accuracy metric value', 'find the best training log line by selecting the lowest loss metric value', 'find the best training log line filtered by minimum and maximum metric threshold constraints', 'extract metrics from the last valid line of multi-line training log output', 'create a new Workspace version from a template directory or existing parent version', 'save content to a file in the Workspace root or a specific version directory', 'view the version history of a Workspace including ancestors and descendants with bug filtering', 'get the top K Workspace versions ranked by a metric score from results.json', 'delete a specific Workspace version and update version info and child pointers']
```

Usage

```
{'extract_single_line_metrics': 'extract key-value metrics from a single line of training log text with type casting', 'extract_best_line_metrics_higher': 'find the best training log line by selecting the highest accuracy metric value', 'extract_best_line_metrics_lower': 'find the best training log line by selecting the lowest loss metric value', 'extract_best_line_metrics_thresholds': 'find the best training log line filtered by minimum and maximum metric threshold constraints', 'extract_last_line_metrics': 'extract metrics from the last valid line of multi-line training log output'}
```

## File: facebookresearch_llm-speedrunner/tests/test_workspace.py

Prompts

```
['extract key-value metrics from a single line of training log text with type casting', 'find the best training log line by selecting the highest accuracy metric value', 'find the best training log line by selecting the lowest loss metric value', 'find the best training log line filtered by minimum and maximum metric threshold constraints', 'extract metrics from the last valid line of multi-line training log output', 'create a new Workspace version from a template directory or existing parent version', 'save content to a file in the Workspace root or a specific version directory', 'view the version history of a Workspace including ancestors and descendants with bug filtering', 'get the top K Workspace versions ranked by a metric score from results.json', 'delete a specific Workspace version and update version info and child pointers']
```

Usage

```
{'create_workspace_version': 'create a new Workspace version from a template directory or existing parent version', 'save_workspace_file': 'save content to a file in the Workspace root or a specific version directory', 'view_workspace_history': 'view the version history of a Workspace including ancestors and descendants with bug filtering', 'get_top_k_versions': 'get the top K Workspace versions ranked by a metric score from results.json', 'delete_workspace_version': 'delete a specific Workspace version and update version info and child pointers'}
```

