# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/projects/functions/next_task.py

Prompts

```
['get the next unlabeled task for a user from a project with configurable sampling strategies', 'get a queryset of tasks not yet solved by a user excluding completed and postponed drafts', 'get the next task from non-data-manager queues including assigned, ground truth, and breadth-first strategies', 'select the next task from a queryset using sequence, uncertainty, or uniform random sampling', 'recover skipped tasks for a user and return them in preserved order for relabeling', 'add a task to the label stream history for a user and project', 'fill the annotation id in stream history for a completed annotation', 'get the label stream history for a user and project filtering deleted tasks', "create a function that appends a task id to a user's label stream history", 'test the get_label_stream_history function with a user and project', 'test get_unique_ids_list to convert lists, sets, or querysets of task objects into a list of unique IDs', 'build a queryset of Task objects from an iterable of Task instances or integer IDs', 'run recalculate_created_annotations_and_labels_from_scratch to reset and rebuild project summary cache from scratch', 'refactor get_unique_ids_list to support additional input types beyond lists, sets, and querysets', 'review make_queryset_from_iterable for edge cases with empty iterables and unknown object types']
```

Usage

```
{'get_next_task': 'get the next unlabeled task for a user from a project with configurable sampling strategies', 'get_not_solved_tasks_qs': 'get a queryset of tasks not yet solved by a user excluding completed and postponed drafts', 'get_next_task_without_dm_queue': 'get the next task from non-data-manager queues including assigned, ground truth, and breadth-first strategies', 'get_task_from_qs_with_sampling': 'select the next task from a queryset using sequence, uncertainty, or uniform random sampling', 'skipped_queue': 'recover skipped tasks for a user and return them in preserved order for relabeling'}
```

## File: HumanSignal_label-studio/label_studio/projects/functions/stream_history.py

Prompts

```
['get the next unlabeled task for a user from a project with configurable sampling strategies', 'get a queryset of tasks not yet solved by a user excluding completed and postponed drafts', 'get the next task from non-data-manager queues including assigned, ground truth, and breadth-first strategies', 'select the next task from a queryset using sequence, uncertainty, or uniform random sampling', 'recover skipped tasks for a user and return them in preserved order for relabeling', 'add a task to the label stream history for a user and project', 'fill the annotation id in stream history for a completed annotation', 'get the label stream history for a user and project filtering deleted tasks', "create a function that appends a task id to a user's label stream history", 'test the get_label_stream_history function with a user and project', 'test get_unique_ids_list to convert lists, sets, or querysets of task objects into a list of unique IDs', 'build a queryset of Task objects from an iterable of Task instances or integer IDs', 'run recalculate_created_annotations_and_labels_from_scratch to reset and rebuild project summary cache from scratch', 'refactor get_unique_ids_list to support additional input types beyond lists, sets, and querysets', 'review make_queryset_from_iterable for edge cases with empty iterables and unknown object types']
```

Usage

```
{'add_stream_history': 'add a task to the label stream history for a user and project', 'fill_history_annotation': 'fill the annotation id in stream history for a completed annotation', 'get_label_stream_history': 'get the label stream history for a user and project filtering deleted tasks', 'create_function_add_stream_history': "create a function that appends a task id to a user's label stream history", 'test_get_label_stream_history': 'test the get_label_stream_history function with a user and project'}
```

## File: HumanSignal_label-studio/label_studio/projects/functions/utils.py

Prompts

```
['get the next unlabeled task for a user from a project with configurable sampling strategies', 'get a queryset of tasks not yet solved by a user excluding completed and postponed drafts', 'get the next task from non-data-manager queues including assigned, ground truth, and breadth-first strategies', 'select the next task from a queryset using sequence, uncertainty, or uniform random sampling', 'recover skipped tasks for a user and return them in preserved order for relabeling', 'add a task to the label stream history for a user and project', 'fill the annotation id in stream history for a completed annotation', 'get the label stream history for a user and project filtering deleted tasks', "create a function that appends a task id to a user's label stream history", 'test the get_label_stream_history function with a user and project', 'test get_unique_ids_list to convert lists, sets, or querysets of task objects into a list of unique IDs', 'build a queryset of Task objects from an iterable of Task instances or integer IDs', 'run recalculate_created_annotations_and_labels_from_scratch to reset and rebuild project summary cache from scratch', 'refactor get_unique_ids_list to support additional input types beyond lists, sets, and querysets', 'review make_queryset_from_iterable for edge cases with empty iterables and unknown object types']
```

Usage

```
{'test_get_unique_ids_list': 'test get_unique_ids_list to convert lists, sets, or querysets of task objects into a list of unique IDs', 'build_make_queryset_from_iterable': 'build a queryset of Task objects from an iterable of Task instances or integer IDs', 'run_recalculate_created_annotations_and_labels_from_scratch': 'run recalculate_created_annotations_and_labels_from_scratch to reset and rebuild project summary cache from scratch', 'refactor_get_unique_ids_list': 'refactor get_unique_ids_list to support additional input types beyond lists, sets, and querysets', 'review_make_queryset_from_iterable': 'review make_queryset_from_iterable for edge cases with empty iterables and unknown object types'}
```

