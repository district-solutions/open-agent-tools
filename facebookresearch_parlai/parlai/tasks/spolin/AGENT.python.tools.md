# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/spolin/agents.py

Prompts

```
['run the SPOLIN dialogue teacher to load and serve yes-and dialogue data for training', 'create a DefaultTeacher instance that inherits SPOLIN dialogue data loading and serving behavior', 'test the SPOLINDialogueTeacher add_cmdline_args method to verify --use_acl_version and --include_nonyesands flags', 'review the SPOLINDialogueTeacher setup_data method to understand how yes-and pairs are loaded and yielded', 'refactor the SPOLINDialogueTeacher class to support additional dialogue dataset formats beyond yes-and pairs', 'build the SPOLin dataset by downloading train and validation JSON files to the data path', 'download the SPOLin train-acl, train, and validation JSON files from the GitHub repository', 'check if the SPOLin dataset has already been built at the given data path', 'remove outdated SPOLin dataset files when an older version exists at the data path', 'mark the SPOLin dataset as built after downloading all resource files']
```

Usage

```
{'run_SPOLINDialogueTeacher': 'run the SPOLIN dialogue teacher to load and serve yes-and dialogue data for training', 'create_DefaultTeacher': 'create a DefaultTeacher instance that inherits SPOLIN dialogue data loading and serving behavior', 'test_add_cmdline_args': 'test the SPOLINDialogueTeacher add_cmdline_args method to verify --use_acl_version and --include_nonyesands flags', 'review_setup_data': 'review the SPOLINDialogueTeacher setup_data method to understand how yes-and pairs are loaded and yielded', 'refactor_SPOLINDialogueTeacher': 'refactor the SPOLINDialogueTeacher class to support additional dialogue dataset formats beyond yes-and pairs'}
```

## File: facebookresearch_parlai/parlai/tasks/spolin/build.py

Prompts

```
['run the SPOLIN dialogue teacher to load and serve yes-and dialogue data for training', 'create a DefaultTeacher instance that inherits SPOLIN dialogue data loading and serving behavior', 'test the SPOLINDialogueTeacher add_cmdline_args method to verify --use_acl_version and --include_nonyesands flags', 'review the SPOLINDialogueTeacher setup_data method to understand how yes-and pairs are loaded and yielded', 'refactor the SPOLINDialogueTeacher class to support additional dialogue dataset formats beyond yes-and pairs', 'build the SPOLin dataset by downloading train and validation JSON files to the data path', 'download the SPOLin train-acl, train, and validation JSON files from the GitHub repository', 'check if the SPOLin dataset has already been built at the given data path', 'remove outdated SPOLin dataset files when an older version exists at the data path', 'mark the SPOLin dataset as built after downloading all resource files']
```

Usage

```
{'build_spolin_dataset': 'build the SPOLin dataset by downloading train and validation JSON files to the data path', 'download_spolin_resources': 'download the SPOLin train-acl, train, and validation JSON files from the GitHub repository', 'check_spolin_built_status': 'check if the SPOLin dataset has already been built at the given data path', 'remove_outdated_spolin_data': 'remove outdated SPOLin dataset files when an older version exists at the data path', 'mark_spolin_data_done': 'mark the SPOLin dataset as built after downloading all resource files'}
```

