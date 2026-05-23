# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/scripts/read_results.py

Prompts

```
['run the script to calculate average stats from JSON files in a folder', 'run calculate_averages to compute task completion, success, sim steps, and replanning averages', 'create a CLI tool that reads stats JSON files recursively and prints average metrics', 'refactor calculate_averages to return a dictionary of averages instead of printing them', 'test calculate_averages with a folder containing stats JSON files with task_percent_complete and task_state_success keys', 'run the stats calculator script with a CSV file and log folder to compute overall episode statistics', 'calculate average values for all numeric columns in a CSV file and return a DataFrame', 'count successful rearrange and place actions for each agent from JSON log files in a folder', 'count hallucination errors including object name errors, action name errors, and syntax errors from agent log files', 'count embodiment, reachability, and affordance errors from agent log files and calculate error fractions per episode']
```

Usage

```
{'run_read_results': 'run the script to calculate average stats from JSON files in a folder', 'run_calculate_averages': 'run calculate_averages to compute task completion, success, sim steps, and replanning averages', 'create_stats_parser': 'create a CLI tool that reads stats JSON files recursively and prints average metrics', 'refactor_calculate_averages': 'refactor calculate_averages to return a dictionary of averages instead of printing them', 'test_calculate_averages': 'test calculate_averages with a folder containing stats JSON files with task_percent_complete and task_state_success keys'}
```

## File: facebookresearch_partnr-planner/scripts/stats_calculator.py

Prompts

```
['run the script to calculate average stats from JSON files in a folder', 'run calculate_averages to compute task completion, success, sim steps, and replanning averages', 'create a CLI tool that reads stats JSON files recursively and prints average metrics', 'refactor calculate_averages to return a dictionary of averages instead of printing them', 'test calculate_averages with a folder containing stats JSON files with task_percent_complete and task_state_success keys', 'run the stats calculator script with a CSV file and log folder to compute overall episode statistics', 'calculate average values for all numeric columns in a CSV file and return a DataFrame', 'count successful rearrange and place actions for each agent from JSON log files in a folder', 'count hallucination errors including object name errors, action name errors, and syntax errors from agent log files', 'count embodiment, reachability, and affordance errors from agent log files and calculate error fractions per episode']
```

Usage

```
{'run_stats_calculator': 'run the stats calculator script with a CSV file and log folder to compute overall episode statistics', 'calculate_column_averages': 'calculate average values for all numeric columns in a CSV file and return a DataFrame', 'count_successful_actions': 'count successful rearrange and place actions for each agent from JSON log files in a folder', 'count_hallucination_errors': 'count hallucination errors including object name errors, action name errors, and syntax errors from agent log files', 'count_embodiment_errors': 'count embodiment, reachability, and affordance errors from agent log files and calculate error fractions per episode'}
```

