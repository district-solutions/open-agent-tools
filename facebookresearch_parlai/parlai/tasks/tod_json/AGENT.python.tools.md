# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/tod_json/agents.py

Prompts

```
['run tod_world_script with JsonTodParser agents to spot-check a TOD JSONL dialogue file', 'parse a JSONL file into TodStructuredEpisode objects using JsonTodParser setup_episodes method', 'filter TOD dialogue episodes by all_goals_hit metric using tod_metrics_datapath and filter_all_goals_hit flags', 'split TOD dialogue data into train valid test folds using split_to_folds and split_folds_seed options', 'process a single JSONL line into a TodStructuredEpisode with prefix-stripped text and API call dicts']
```

Usage

```
{'run_tod_world_script': 'run tod_world_script with JsonTodParser agents to spot-check a TOD JSONL dialogue file', 'parse_jsonl_dialogue': 'parse a JSONL file into TodStructuredEpisode objects using JsonTodParser setup_episodes method', 'filter_episodes_by_goals_hit': 'filter TOD dialogue episodes by all_goals_hit metric using tod_metrics_datapath and filter_all_goals_hit flags', 'split_dialogue_data_by_fold': 'split TOD dialogue data into train valid test folds using split_to_folds and split_folds_seed options', 'process_single_dialogue_line': 'process a single JSONL line into a TodStructuredEpisode with prefix-stripped text and API call dicts'}
```

