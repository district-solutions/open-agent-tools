# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/metalwoz/agents.py

Prompts

```
['build the metalwoz dataset by calling the build function with opt to download and prepare dialogue data', 'load metalwoz dialogue data from JSONL files and merge with tasks table using load_data method', 'setup the SystemTeacher to yield bot dialogue turns with prompts and labels for training a dialogue system', 'setup the UserSimulatorTeacher to yield user dialogue turns with role-prefixed prompts for training a user simulator', 'filter metalwoz dialogue data to a subset of domains using the metalwoz_domains command line argument', 'download the MetaLWOZ train and test zip files from Microsoft servers using RESOURCES', 'create the train and test dialogues directory structure for the MetaLWOZ dataset', 'extract the dstc8_metalwoz_heldout zip file into the test dialogues directory', 'check if the MetaLWOZ dataset is already built at version 1.0 before downloading']
```

Usage

```
{'build_metalwoz_dataset': 'build the metalwoz dataset by calling the build function with opt to download and prepare dialogue data', 'load_metalwoz_data': 'load metalwoz dialogue data from JSONL files and merge with tasks table using load_data method', 'setup_system_teacher': 'setup the SystemTeacher to yield bot dialogue turns with prompts and labels for training a dialogue system', 'setup_user_simulator': 'setup the UserSimulatorTeacher to yield user dialogue turns with role-prefixed prompts for training a user simulator', 'filter_metalwoz_domains': 'filter metalwoz dialogue data to a subset of domains using the metalwoz_domains command line argument'}
```

## File: facebookresearch_parlai/parlai/tasks/metalwoz/build.py

Prompts

```
['build the metalwoz dataset by calling the build function with opt to download and prepare dialogue data', 'load metalwoz dialogue data from JSONL files and merge with tasks table using load_data method', 'setup the SystemTeacher to yield bot dialogue turns with prompts and labels for training a dialogue system', 'setup the UserSimulatorTeacher to yield user dialogue turns with role-prefixed prompts for training a user simulator', 'filter metalwoz dialogue data to a subset of domains using the metalwoz_domains command line argument', 'download the MetaLWOZ train and test zip files from Microsoft servers using RESOURCES', 'create the train and test dialogues directory structure for the MetaLWOZ dataset', 'extract the dstc8_metalwoz_heldout zip file into the test dialogues directory', 'check if the MetaLWOZ dataset is already built at version 1.0 before downloading']
```

Usage

```
{'build_metalwoz_dataset': 'run the build function to download and extract the MetaLWOZ train and test datasets', 'download_metalwoz_resources': 'download the MetaLWOZ train and test zip files from Microsoft servers using RESOURCES', 'create_metalwoz_directory_structure': 'create the train and test dialogues directory structure for the MetaLWOZ dataset', 'extract_metalwoz_test_data': 'extract the dstc8_metalwoz_heldout zip file into the test dialogues directory', 'check_metalwoz_build_version': 'check if the MetaLWOZ dataset is already built at version 1.0 before downloading'}
```

