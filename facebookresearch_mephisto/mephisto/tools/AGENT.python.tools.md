# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/tools/data_browser.py

Prompts

```
['get a list of all task names from the Mephisto database using DataBrowser', 'retrieve all completed units for a given task name using DataBrowser', 'extract all data from a unit including status, worker info, and timestamps', 'find all workers who have a specific qualification using DataBrowser', 'extract a specific metadata property from all units of a named task', 'run an interactive examine or review flow to inspect and approve task results', 'run an interactive worker-by-worker review to accept reject or pass completed task units', 'print task results to stdout for a given task name with optional start and end range', 'prompt the user for a task name and optional block and approve qualification names', 'get a mapping of worker ids to their units grouped by accepted rejected and soft rejected status']
```

Usage

```
{'get_task_name_list': 'get a list of all task names from the Mephisto database using DataBrowser', 'get_units_for_task_name': 'retrieve all completed units for a given task name using DataBrowser', 'get_data_from_unit': 'extract all data from a unit including status, worker info, and timestamps', 'get_workers_with_qualification': 'find all workers who have a specific qualification using DataBrowser', 'get_metadata_property_from_task_name': 'extract a specific metadata property from all units of a named task'}
```

## File: facebookresearch_mephisto/mephisto/tools/examine_utils.py

Prompts

```
['get a list of all task names from the Mephisto database using DataBrowser', 'retrieve all completed units for a given task name using DataBrowser', 'extract all data from a unit including status, worker info, and timestamps', 'find all workers who have a specific qualification using DataBrowser', 'extract a specific metadata property from all units of a named task', 'run an interactive examine or review flow to inspect and approve task results', 'run an interactive worker-by-worker review to accept reject or pass completed task units', 'print task results to stdout for a given task name with optional start and end range', 'prompt the user for a task name and optional block and approve qualification names', 'get a mapping of worker ids to their units grouped by accepted rejected and soft rejected status']
```

Usage

```
{'run_examine_or_review': 'run an interactive examine or review flow to inspect and approve task results', 'run_examine_by_worker': 'run an interactive worker-by-worker review to accept reject or pass completed task units', 'print_results': 'print task results to stdout for a given task name with optional start and end range', 'prompt_for_options': 'prompt the user for a task name and optional block and approve qualification names', 'get_worker_stats': 'get a mapping of worker ids to their units grouped by accepted rejected and soft rejected status'}
```

