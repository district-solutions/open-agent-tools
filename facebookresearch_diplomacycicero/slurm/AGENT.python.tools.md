# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/slurm/tasks.py

Prompts

```
['run a list of Task objects locally with results written to a specified output directory', 'create a Task dataclass with a target file name, handler function, and keyword arguments', 'get lists of completed and pending task files from a results directory by checking scheduled markers', 'run a single task handler that writes output atomically to a target file path', 'run a list of tasks locally, skipping any whose target files already exist']
```

Usage

```
{'run_locally_or_on_slurm': 'run a list of Task objects locally with results written to a specified output directory', 'create_Task_dataclass': 'create a Task dataclass with a target file name, handler function, and keyword arguments', 'get_done_and_undone_files': 'get lists of completed and pending task files from a results directory by checking scheduled markers', 'run_task_with_atomic_write': 'run a single task handler that writes output atomically to a target file path', 'run_tasks_locally': 'run a list of tasks locally, skipping any whose target files already exist'}
```

