# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/scripts/evaluation/get_ranks.py

Prompts

```
['run the get_ranks script with a trajectory directory path to compute model rankings and save CSV results', 'calculate model rankings from a scores dictionary sorted by maximize or minimize metric direction', 'compute a Plackett-Luce aggregate ranking from a dictionary of per-task model rankings', 'compute a Borda count aggregate ranking from a dictionary of per-task model rankings', 'calculate performance ratios for each model relative to the best score for a given task', 'plot a stacked bar chart of exit status counts per model and save to PDF', 'plot a bar chart of failed and incomplete runs for each model and save to PDF', 'plot a bar chart of failed and incomplete runs for each task and save to PDF', 'plot a bar chart of total action type counts across all tasks and models and save to PDF', 'plot a stacked bar chart showing action distribution at each step from 0 to 50 and save to PDF', 'run the script to process evaluation results for multiple models using trajectory directories and a priority metric', 'get the index of the best agent attempt based on a priority metric and maximize or minimize direction', 'get the average best and last attempt scores for a model across all parallel runs', 'get the baseline scores for a task from the first result that contains baseline data', 'print a formatted table of results by model showing min, max, average, and standard deviation for each metric']
```

Usage

```
{'run_get_ranks_cli': 'run the get_ranks script with a trajectory directory path to compute model rankings and save CSV results', 'calculate_rankings': 'calculate model rankings from a scores dictionary sorted by maximize or minimize metric direction', 'compute_plackett_luce_ranking': 'compute a Plackett-Luce aggregate ranking from a dictionary of per-task model rankings', 'compute_broda_ranking': 'compute a Borda count aggregate ranking from a dictionary of per-task model rankings', 'calculate_performance_ratios': 'calculate performance ratios for each model relative to the best score for a given task'}
```

## File: facebookresearch_mlgym/scripts/evaluation/plot_exit_status.py

Prompts

```
['run the get_ranks script with a trajectory directory path to compute model rankings and save CSV results', 'calculate model rankings from a scores dictionary sorted by maximize or minimize metric direction', 'compute a Plackett-Luce aggregate ranking from a dictionary of per-task model rankings', 'compute a Borda count aggregate ranking from a dictionary of per-task model rankings', 'calculate performance ratios for each model relative to the best score for a given task', 'plot a stacked bar chart of exit status counts per model and save to PDF', 'plot a bar chart of failed and incomplete runs for each model and save to PDF', 'plot a bar chart of failed and incomplete runs for each task and save to PDF', 'plot a bar chart of total action type counts across all tasks and models and save to PDF', 'plot a stacked bar chart showing action distribution at each step from 0 to 50 and save to PDF', 'run the script to process evaluation results for multiple models using trajectory directories and a priority metric', 'get the index of the best agent attempt based on a priority metric and maximize or minimize direction', 'get the average best and last attempt scores for a model across all parallel runs', 'get the baseline scores for a task from the first result that contains baseline data', 'print a formatted table of results by model showing min, max, average, and standard deviation for each metric']
```

Usage

```
{'plot_exit_status_counts_per_model': 'plot a stacked bar chart of exit status counts per model and save to PDF', 'plot_failed_incomplete_runs_per_model': 'plot a bar chart of failed and incomplete runs for each model and save to PDF', 'plot_failed_incomplete_runs_per_task': 'plot a bar chart of failed and incomplete runs for each task and save to PDF', 'plot_total_actions': 'plot a bar chart of total action type counts across all tasks and models and save to PDF', 'plot_actions_per_step': 'plot a stacked bar chart showing action distribution at each step from 0 to 50 and save to PDF'}
```

## File: facebookresearch_mlgym/scripts/evaluation/process_results.py

Prompts

```
['run the get_ranks script with a trajectory directory path to compute model rankings and save CSV results', 'calculate model rankings from a scores dictionary sorted by maximize or minimize metric direction', 'compute a Plackett-Luce aggregate ranking from a dictionary of per-task model rankings', 'compute a Borda count aggregate ranking from a dictionary of per-task model rankings', 'calculate performance ratios for each model relative to the best score for a given task', 'plot a stacked bar chart of exit status counts per model and save to PDF', 'plot a bar chart of failed and incomplete runs for each model and save to PDF', 'plot a bar chart of failed and incomplete runs for each task and save to PDF', 'plot a bar chart of total action type counts across all tasks and models and save to PDF', 'plot a stacked bar chart showing action distribution at each step from 0 to 50 and save to PDF', 'run the script to process evaluation results for multiple models using trajectory directories and a priority metric', 'get the index of the best agent attempt based on a priority metric and maximize or minimize direction', 'get the average best and last attempt scores for a model across all parallel runs', 'get the baseline scores for a task from the first result that contains baseline data', 'print a formatted table of results by model showing min, max, average, and standard deviation for each metric']
```

Usage

```
{'run_process_results': 'run the script to process evaluation results for multiple models using trajectory directories and a priority metric', 'get_best_attempt': 'get the index of the best agent attempt based on a priority metric and maximize or minimize direction', 'get_scores': 'get the average best and last attempt scores for a model across all parallel runs', 'get_baseline_scores': 'get the baseline scores for a task from the first result that contains baseline data', 'print_results': 'print a formatted table of results by model showing min, max, average, and standard deviation for each metric'}
```

