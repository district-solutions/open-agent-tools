# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/examples/simple_static_task/examine_results.py

Prompts

```
['run the examine results script to review Mephisto task data from the local database', 'format Mephisto task result data including worker info, inputs, outputs, and attached files for display', 'review Mephisto task results by running the examine utility with a custom formatting function', 'summarize the format_for_printing_data function that extracts worker name, duration, character inputs, ratings, and files', 'refactor the format_for_printing_data function to support additional output fields or different display formats', 'run a mephisto static task with onboarding validation that checks worker answers before assignment', 'create a dataclass config extending build_default_task_config with a custom correct_answer field', 'validate onboarding data by comparing the worker answer output against the expected correct answer', 'launch a shared static task with onboarding data and a validation function using SharedStaticTaskState', 'wait for all task runs to complete then shutdown the operator with periodic logging']
```

Usage

```
{'run_examine_results': 'run the examine results script to review Mephisto task data from the local database', 'format_for_printing_data': 'format Mephisto task result data including worker info, inputs, outputs, and attached files for display', 'review_task_results': 'review Mephisto task results by running the examine utility with a custom formatting function', 'summarize_format_for_printing_data': 'summarize the format_for_printing_data function that extracts worker name, duration, character inputs, ratings, and files', 'refactor_format_for_printing_data': 'refactor the format_for_printing_data function to support additional output fields or different display formats'}
```

## File: facebookresearch_mephisto/examples/simple_static_task/run_task_with_onboarding__local__inhouse.py

Prompts

```
['run the examine results script to review Mephisto task data from the local database', 'format Mephisto task result data including worker info, inputs, outputs, and attached files for display', 'review Mephisto task results by running the examine utility with a custom formatting function', 'summarize the format_for_printing_data function that extracts worker name, duration, character inputs, ratings, and files', 'refactor the format_for_printing_data function to support additional output fields or different display formats', 'run a mephisto static task with onboarding validation that checks worker answers before assignment', 'create a dataclass config extending build_default_task_config with a custom correct_answer field', 'validate onboarding data by comparing the worker answer output against the expected correct answer', 'launch a shared static task with onboarding data and a validation function using SharedStaticTaskState', 'wait for all task runs to complete then shutdown the operator with periodic logging']
```

Usage

```
{'run_task_with_onboarding_validation': 'run a mephisto static task with onboarding validation that checks worker answers before assignment', 'create_onboarding_config_dataclass': 'create a dataclass config extending build_default_task_config with a custom correct_answer field', 'validate_onboarding_data': 'validate onboarding data by comparing the worker answer output against the expected correct answer', 'launch_shared_static_task': 'launch a shared static task with onboarding data and a validation function using SharedStaticTaskState', 'wait_for_runs_then_shutdown': 'wait for all task runs to complete then shutdown the operator with periodic logging'}
```

