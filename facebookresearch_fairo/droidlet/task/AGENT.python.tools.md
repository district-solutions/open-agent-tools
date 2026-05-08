# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/task/condition_classes.py

Prompts

```
['create an AndCondition that checks multiple conditions and returns true only if all are true', 'create an OrCondition that checks multiple conditions and returns true if any one is true', "create a NotCondition that negates the result of another condition's check method", 'create a TaskStatusCondition to check if a task is finished, running, or paused', 'create a Comparator condition to compare two values using EQUAL, GREATER_THAN_EQUAL, or LESS_THAN_EQUAL', 'create a Task instance with an agent and optional task_data dictionary for memory registration', 'create a ControlBlock to manage a sequence of task generators with init and terminate conditions', 'bundle a list of tasks into a single task generator using maybe_bundle_task_list utility', 'wrap a Task into a callable generator using task_to_generator for deferred execution', 'create a BaseMovementTask subclass that changes agent location with a target location in task_data']
```

Usage

```
{'create_and_condition': 'create an AndCondition that checks multiple conditions and returns true only if all are true', 'create_or_condition': 'create an OrCondition that checks multiple conditions and returns true if any one is true', 'create_not_condition': "create a NotCondition that negates the result of another condition's check method", 'create_task_status_condition': 'create a TaskStatusCondition to check if a task is finished, running, or paused', 'create_comparator_condition': 'create a Comparator condition to compare two values using EQUAL, GREATER_THAN_EQUAL, or LESS_THAN_EQUAL'}
```

## File: facebookresearch_fairo/droidlet/task/task.py

Prompts

```
['create an AndCondition that checks multiple conditions and returns true only if all are true', 'create an OrCondition that checks multiple conditions and returns true if any one is true', "create a NotCondition that negates the result of another condition's check method", 'create a TaskStatusCondition to check if a task is finished, running, or paused', 'create a Comparator condition to compare two values using EQUAL, GREATER_THAN_EQUAL, or LESS_THAN_EQUAL', 'create a Task instance with an agent and optional task_data dictionary for memory registration', 'create a ControlBlock to manage a sequence of task generators with init and terminate conditions', 'bundle a list of tasks into a single task generator using maybe_bundle_task_list utility', 'wrap a Task into a callable generator using task_to_generator for deferred execution', 'create a BaseMovementTask subclass that changes agent location with a target location in task_data']
```

Usage

```
{'create_task': 'create a Task instance with an agent and optional task_data dictionary for memory registration', 'create_controlblock': 'create a ControlBlock to manage a sequence of task generators with init and terminate conditions', 'bundle_task_list': 'bundle a list of tasks into a single task generator using maybe_bundle_task_list utility', 'wrap_task_to_generator': 'wrap a Task into a callable generator using task_to_generator for deferred execution', 'create_movement_task': 'create a BaseMovementTask subclass that changes agent location with a target location in task_data'}
```

