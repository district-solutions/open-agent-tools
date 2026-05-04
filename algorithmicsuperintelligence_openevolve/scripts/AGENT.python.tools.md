# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/scripts/manual.py

Prompts

```
['create a flask blueprint for the manual mode UI with task listing and answer submission endpoints', 'resolve the run root path from a checkpoint directory path that may include nested checkpoint folders', 'list all pending tasks from the manual tasks queue directory that do not have answers yet', 'read a specific task by its ID from the manual tasks queue directory and return the task data', 'write an answer for a task to the queue directory using atomic file operations with temporary files', 'run a flask server to visualize OpenEvolve evolution data from a checkpoint directory', 'export a static HTML visualization of evolution data to a specified output directory', 'find the most recent checkpoint folder in a given base directory by modification time', 'load evolution nodes and edges from a checkpoint folder including metadata and program files', 'sanitize program metrics by replacing infinite or NaN values with null for JSON serialization']
```

Usage

```
{'create_manual_blueprint': 'create a flask blueprint for the manual mode UI with task listing and answer submission endpoints', 'resolve_run_root': 'resolve the run root path from a checkpoint directory path that may include nested checkpoint folders', 'list_tasks': 'list all pending tasks from the manual tasks queue directory that do not have answers yet', 'read_task': 'read a specific task by its ID from the manual tasks queue directory and return the task data', 'write_answer': 'write an answer for a task to the queue directory using atomic file operations with temporary files'}
```

## File: algorithmicsuperintelligence_openevolve/scripts/visualizer.py

Prompts

```
['create a flask blueprint for the manual mode UI with task listing and answer submission endpoints', 'resolve the run root path from a checkpoint directory path that may include nested checkpoint folders', 'list all pending tasks from the manual tasks queue directory that do not have answers yet', 'read a specific task by its ID from the manual tasks queue directory and return the task data', 'write an answer for a task to the queue directory using atomic file operations with temporary files', 'run a flask server to visualize OpenEvolve evolution data from a checkpoint directory', 'export a static HTML visualization of evolution data to a specified output directory', 'find the most recent checkpoint folder in a given base directory by modification time', 'load evolution nodes and edges from a checkpoint folder including metadata and program files', 'sanitize program metrics by replacing infinite or NaN values with null for JSON serialization']
```

Usage

```
{'run_visualizer_server': 'run a flask server to visualize OpenEvolve evolution data from a checkpoint directory', 'export_static_html': 'export a static HTML visualization of evolution data to a specified output directory', 'find_latest_checkpoint': 'find the most recent checkpoint folder in a given base directory by modification time', 'load_evolution_data': 'load evolution nodes and edges from a checkpoint folder including metadata and program files', 'sanitize_program_for_visualization': 'sanitize program metrics by replacing infinite or NaN values with null for JSON serialization'}
```

