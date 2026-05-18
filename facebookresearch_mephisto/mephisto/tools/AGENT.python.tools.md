# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/tools/data_browser.py

Prompts

```
['get a list of all task names from the Mephisto database using DataBrowser', 'retrieve all completed units for a given task name using DataBrowser', 'extract all data from a unit including status, worker info, and timestamps', 'find all workers who have a specific qualification using DataBrowser', 'extract a specific metadata property from all units of a named task', 'run an interactive examine or review flow to inspect and approve task results', 'run an interactive worker-by-worker review to accept reject or pass completed task units', 'print task results to stdout for a given task name with optional start and end range', 'prompt the user for a task name and optional block and approve qualification names', 'get a mapping of worker ids to their units grouped by accepted rejected and soft rejected status', 'create a decorator for a Mephisto task script using task_script with a TaskConfig dataclass', 'load a MephistoDB and validate a Hydra DictConfig against the database contents', 'get an Operator instance and validated config from a Hydra DictConfig', 'build a custom webapp bundle by running npm install and webpack in the source directory', 'print a formatted list of task names using rich markdown output']
```

Usage

```
{'get_task_name_list': 'get a list of all task names from the Mephisto database using DataBrowser', 'get_units_for_task_name': 'retrieve all completed units for a given task name using DataBrowser', 'get_data_from_unit': 'extract all data from a unit including status, worker info, and timestamps', 'get_workers_with_qualification': 'find all workers who have a specific qualification using DataBrowser', 'get_metadata_property_from_task_name': 'extract a specific metadata property from all units of a named task'}
```

## File: facebookresearch_mephisto/mephisto/tools/examine_utils.py

Prompts

```
['get a list of all task names from the Mephisto database using DataBrowser', 'retrieve all completed units for a given task name using DataBrowser', 'extract all data from a unit including status, worker info, and timestamps', 'find all workers who have a specific qualification using DataBrowser', 'extract a specific metadata property from all units of a named task', 'run an interactive examine or review flow to inspect and approve task results', 'run an interactive worker-by-worker review to accept reject or pass completed task units', 'print task results to stdout for a given task name with optional start and end range', 'prompt the user for a task name and optional block and approve qualification names', 'get a mapping of worker ids to their units grouped by accepted rejected and soft rejected status', 'create a decorator for a Mephisto task script using task_script with a TaskConfig dataclass', 'load a MephistoDB and validate a Hydra DictConfig against the database contents', 'get an Operator instance and validated config from a Hydra DictConfig', 'build a custom webapp bundle by running npm install and webpack in the source directory', 'print a formatted list of task names using rich markdown output']
```

Usage

```
{'run_examine_or_review': 'run an interactive examine or review flow to inspect and approve task results', 'run_examine_by_worker': 'run an interactive worker-by-worker review to accept reject or pass completed task units', 'print_results': 'print task results to stdout for a given task name with optional start and end range', 'prompt_for_options': 'prompt the user for a task name and optional block and approve qualification names', 'get_worker_stats': 'get a mapping of worker ids to their units grouped by accepted rejected and soft rejected status'}
```

## File: facebookresearch_mephisto/mephisto/tools/scripts.py

Prompts

```
['get a list of all task names from the Mephisto database using DataBrowser', 'retrieve all completed units for a given task name using DataBrowser', 'extract all data from a unit including status, worker info, and timestamps', 'find all workers who have a specific qualification using DataBrowser', 'extract a specific metadata property from all units of a named task', 'run an interactive examine or review flow to inspect and approve task results', 'run an interactive worker-by-worker review to accept reject or pass completed task units', 'print task results to stdout for a given task name with optional start and end range', 'prompt the user for a task name and optional block and approve qualification names', 'get a mapping of worker ids to their units grouped by accepted rejected and soft rejected status', 'create a decorator for a Mephisto task script using task_script with a TaskConfig dataclass', 'load a MephistoDB and validate a Hydra DictConfig against the database contents', 'get an Operator instance and validated config from a Hydra DictConfig', 'build a custom webapp bundle by running npm install and webpack in the source directory', 'print a formatted list of task names using rich markdown output']
```

Usage

```
{'build_task_script_decorator': 'create a decorator for a Mephisto task script using task_script with a TaskConfig dataclass', 'load_db_and_process_config': 'load a MephistoDB and validate a Hydra DictConfig against the database contents', 'process_config_and_get_operator': 'get an Operator instance and validated config from a Hydra DictConfig', 'build_custom_bundle': 'build a custom webapp bundle by running npm install and webpack in the source directory', 'print_out_task_names': 'print a formatted list of task names using rich markdown output'}
```

