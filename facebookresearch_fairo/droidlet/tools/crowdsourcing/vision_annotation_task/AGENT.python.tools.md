# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/tools/crowdsourcing/vision_annotation_task/examine_results.py

Prompts

```
['run the script to review and approve reject or pass crowdsourcing task results interactively', 'run format_for_printing_data to format Mephisto unit data with worker info and task outputs for display', 'review format_for_printing_data which extracts worker name duration status and question answers from task data', 'run the approval loop to approve reject or soft reject worker submissions with optional disqualification', 'run grant_qualification on a worker to soft block them from future tasks using a disqualification name', 'check the completion, launch, and assignment status of HITs for a given Mephisto task run', 'retrieve all completed units from a Mephisto task run by its run ID', 'plot histograms of browsers, OSes, and mobile usage for completed HITs in a task run', 'generate timing charts and pass rate statistics for all questions in a completed task run', 'create a bar chart histogram from a dictionary of key-value pairs with optional target line', 'run the pilot task script to launch a crowdsourcing vision annotation pilot task via mephisto', 'validate pilot task answers by checking that q1Answer through q4Answer all equal true', 'validate a submitted unit by extracting worker answers and granting block or allowlist qualifications', 'create a TestScriptConfig dataclass with hydra defaults for the static HTML blueprint and EC2 architect', 'setup a SharedStaticTaskState with a unit submission validator and block qualification to prevent repeat workers']
```

Usage

```
{'run_examine_results': 'run the script to review and approve reject or pass crowdsourcing task results interactively', 'run_format_for_printing_data': 'run format_for_printing_data to format Mephisto unit data with worker info and task outputs for display', 'review_format_for_printing_data': 'review format_for_printing_data which extracts worker name duration status and question answers from task data', 'run_approve_reject_soft_reject': 'run the approval loop to approve reject or soft reject worker submissions with optional disqualification', 'run_grant_qualification': 'run grant_qualification on a worker to soft block them from future tasks using a disqualification name'}
```

## File: facebookresearch_fairo/droidlet/tools/crowdsourcing/vision_annotation_task/pilot_stats.py

Prompts

```
['run the script to review and approve reject or pass crowdsourcing task results interactively', 'run format_for_printing_data to format Mephisto unit data with worker info and task outputs for display', 'review format_for_printing_data which extracts worker name duration status and question answers from task data', 'run the approval loop to approve reject or soft reject worker submissions with optional disqualification', 'run grant_qualification on a worker to soft block them from future tasks using a disqualification name', 'check the completion, launch, and assignment status of HITs for a given Mephisto task run', 'retrieve all completed units from a Mephisto task run by its run ID', 'plot histograms of browsers, OSes, and mobile usage for completed HITs in a task run', 'generate timing charts and pass rate statistics for all questions in a completed task run', 'create a bar chart histogram from a dictionary of key-value pairs with optional target line', 'run the pilot task script to launch a crowdsourcing vision annotation pilot task via mephisto', 'validate pilot task answers by checking that q1Answer through q4Answer all equal true', 'validate a submitted unit by extracting worker answers and granting block or allowlist qualifications', 'create a TestScriptConfig dataclass with hydra defaults for the static HTML blueprint and EC2 architect', 'setup a SharedStaticTaskState with a unit submission validator and block qualification to prevent repeat workers']
```

Usage

```
{'check_run_status': 'check the completion, launch, and assignment status of HITs for a given Mephisto task run', 'retrieve_units': 'retrieve all completed units from a Mephisto task run by its run ID', 'plot_OS_browser': 'plot histograms of browsers, OSes, and mobile usage for completed HITs in a task run', 'timing_charts': 'generate timing charts and pass rate statistics for all questions in a completed task run', 'plot_hist': 'create a bar chart histogram from a dictionary of key-value pairs with optional target line'}
```

## File: facebookresearch_fairo/droidlet/tools/crowdsourcing/vision_annotation_task/pilot_task_run.py

Prompts

```
['run the script to review and approve reject or pass crowdsourcing task results interactively', 'run format_for_printing_data to format Mephisto unit data with worker info and task outputs for display', 'review format_for_printing_data which extracts worker name duration status and question answers from task data', 'run the approval loop to approve reject or soft reject worker submissions with optional disqualification', 'run grant_qualification on a worker to soft block them from future tasks using a disqualification name', 'check the completion, launch, and assignment status of HITs for a given Mephisto task run', 'retrieve all completed units from a Mephisto task run by its run ID', 'plot histograms of browsers, OSes, and mobile usage for completed HITs in a task run', 'generate timing charts and pass rate statistics for all questions in a completed task run', 'create a bar chart histogram from a dictionary of key-value pairs with optional target line', 'run the pilot task script to launch a crowdsourcing vision annotation pilot task via mephisto', 'validate pilot task answers by checking that q1Answer through q4Answer all equal true', 'validate a submitted unit by extracting worker answers and granting block or allowlist qualifications', 'create a TestScriptConfig dataclass with hydra defaults for the static HTML blueprint and EC2 architect', 'setup a SharedStaticTaskState with a unit submission validator and block qualification to prevent repeat workers']
```

Usage

```
{'run_pilot_task': 'run the pilot task script to launch a crowdsourcing vision annotation pilot task via mephisto', 'validate_answers': 'validate pilot task answers by checking that q1Answer through q4Answer all equal true', 'validate_unit': 'validate a submitted unit by extracting worker answers and granting block or allowlist qualifications', 'create_test_script_config': 'create a TestScriptConfig dataclass with hydra defaults for the static HTML blueprint and EC2 architect', 'setup_shared_static_task_state': 'setup a SharedStaticTaskState with a unit submission validator and block qualification to prevent repeat workers'}
```

