# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/google_sgd/agents.py

Prompts

```
['parse Google SGD dataset dialogues into TodStructuredEpisode format for task-oriented dialogue training', 'evaluate a model on Joint Goal Accuracy using the GoogleSGDDSTTeacher custom evaluation method', 'fuzzy match predicted slot values against ground truth using token sort ratio from fuzzywuzzy', 'extract API call parameters and service results from system turns in Google SGD dialogues', 'load Google SGD schema and dialogue data with optional filtering by dialogue IDs', 'build the Google SGD dataset by downloading train, dev, and test splits from the DSTC8 repository', 'run the build function to download schema and dialogue JSON files for all data splits', 'check the number of dialogue files available for a given train, dev, or test split', 'download numbered dialogue JSON files and schema files for each data split into the output directory', 'review the build function versioning logic that checks for existing data and removes outdated versions']
```

Usage

```
{'parse_google_sgd_dialogues': 'parse Google SGD dataset dialogues into TodStructuredEpisode format for task-oriented dialogue training', 'evaluate_dialogue_state_tracking': 'evaluate a model on Joint Goal Accuracy using the GoogleSGDDSTTeacher custom evaluation method', 'fuzzy_match_slot_values': 'fuzzy match predicted slot values against ground truth using token sort ratio from fuzzywuzzy', 'extract_api_calls_from_dialogue': 'extract API call parameters and service results from system turns in Google SGD dialogues', 'load_sgd_data_with_filtering': 'load Google SGD schema and dialogue data with optional filtering by dialogue IDs'}
```

## File: facebookresearch_parlai/parlai/tasks/google_sgd/build.py

Prompts

```
['parse Google SGD dataset dialogues into TodStructuredEpisode format for task-oriented dialogue training', 'evaluate a model on Joint Goal Accuracy using the GoogleSGDDSTTeacher custom evaluation method', 'fuzzy match predicted slot values against ground truth using token sort ratio from fuzzywuzzy', 'extract API call parameters and service results from system turns in Google SGD dialogues', 'load Google SGD schema and dialogue data with optional filtering by dialogue IDs', 'build the Google SGD dataset by downloading train, dev, and test splits from the DSTC8 repository', 'run the build function to download schema and dialogue JSON files for all data splits', 'check the number of dialogue files available for a given train, dev, or test split', 'download numbered dialogue JSON files and schema files for each data split into the output directory', 'review the build function versioning logic that checks for existing data and removes outdated versions']
```

Usage

```
{'build_google_sgd_dataset': 'build the Google SGD dataset by downloading train, dev, and test splits from the DSTC8 repository', 'run_build_function': 'run the build function to download schema and dialogue JSON files for all data splits', 'check_fold_size': 'check the number of dialogue files available for a given train, dev, or test split', 'download_dialogue_files': 'download numbered dialogue JSON files and schema files for each data split into the output directory', 'review_build_versioning': 'review the build function versioning logic that checks for existing data and removes outdated versions'}
```

