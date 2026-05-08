# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/dialogue_qe/agents.py

Prompts

```
['build the DialogueQE dataset by calling the build function to download and prepare train and test JSON files', 'create a DefaultTeacher instance with an opt dict to load DialogueQE dialogue data for training or evaluation', 'transform a single utterance dict into a formatted string with userId, userType, and text fields', 'setup and iterate over dialogue threads from a JSON file, yielding dialog text and quality evaluation labels', 'get the file path for train or test JSON data based on the datatype in the opt configuration', 'run the build function to download and prepare the DialogueQE dataset into the datapath directory', 'download the DialogueQE dataset tar.gz file from the deepmipt turing-data GitHub repository', 'rename the downloaded data_train and data_test JSON files to train.json and test.json', 'check if the DialogueQE dataset has already been built using build_data.built with the version string', 'remove the existing DialogueQE data directory using build_data.remove_dir before rebuilding']
```

Usage

```
{'build_dialogue_qe_dataset': 'build the DialogueQE dataset by calling the build function to download and prepare train and test JSON files', 'create_default_teacher': 'create a DefaultTeacher instance with an opt dict to load DialogueQE dialogue data for training or evaluation', 'transform_utterance': 'transform a single utterance dict into a formatted string with userId, userType, and text fields', 'setup_dialogue_data': 'setup and iterate over dialogue threads from a JSON file, yielding dialog text and quality evaluation labels', 'get_data_path': 'get the file path for train or test JSON data based on the datatype in the opt configuration'}
```

## File: facebookresearch_parlai/parlai/tasks/dialogue_qe/build.py

Prompts

```
['build the DialogueQE dataset by calling the build function to download and prepare train and test JSON files', 'create a DefaultTeacher instance with an opt dict to load DialogueQE dialogue data for training or evaluation', 'transform a single utterance dict into a formatted string with userId, userType, and text fields', 'setup and iterate over dialogue threads from a JSON file, yielding dialog text and quality evaluation labels', 'get the file path for train or test JSON data based on the datatype in the opt configuration', 'run the build function to download and prepare the DialogueQE dataset into the datapath directory', 'download the DialogueQE dataset tar.gz file from the deepmipt turing-data GitHub repository', 'rename the downloaded data_train and data_test JSON files to train.json and test.json', 'check if the DialogueQE dataset has already been built using build_data.built with the version string', 'remove the existing DialogueQE data directory using build_data.remove_dir before rebuilding']
```

Usage

```
{'build_dialogue_qe_data': 'run the build function to download and prepare the DialogueQE dataset into the datapath directory', 'download_dialogue_qe_resources': 'download the DialogueQE dataset tar.gz file from the deepmipt turing-data GitHub repository', 'rename_dialogue_qe_files': 'rename the downloaded data_train and data_test JSON files to train.json and test.json', 'check_dialogue_qe_built': 'check if the DialogueQE dataset has already been built using build_data.built with the version string', 'remove_dialogue_qe_data': 'remove the existing DialogueQE data directory using build_data.remove_dir before rebuilding'}
```

