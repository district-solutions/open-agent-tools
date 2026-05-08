# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/taskmaster/agents.py

Prompts

```
['run the Taskmaster1Parser to load and parse Taskmaster-1 self-dialogs and woz-dialogs JSON data into TOD structured episodes', 'run the SystemTeacher to train a dialogue system agent on Taskmaster-1 assistant utterances using the TOD format', 'run the UserSimulatorTeacher to train a user simulator agent on Taskmaster-1 user utterances using the TOD format', 'run the SelfDialogueTeacher to train a dialogue model on written two-person dialogues with both user and assistant passes', 'run the WozDialogueTeacher to train a dialogue model on spoken two-person dialogues with optional corrupt example exclusion', 'run the build function to download and set up the Taskmaster-1 dataset into the data directory', 'download the self-dialogs.json and woz-dialogs.json files from the Taskmaster GitHub repository', 'check if the Taskmaster-1 dataset has already been built at version 1.02', 'remove an older version of the Taskmaster-1 dataset directory before rebuilding', 'mark the Taskmaster-1 dataset directory as built with the current version string', 'smoothen a conversation by aggregating contiguous responses from the same speaker into alternating USER and ASSISTANT turns', 'generate a cheatsheet for a dialogue episode showing first and last USER and ASSISTANT reply indexes and example counts', 'join two utterances from the same speaker into a single utterance with newline-separated text and an incremented counter', 'update the index field of each utterance in a conversation list to sequential zero-based integers', 'get the file path to a Taskmaster 1 data file after ensuring the dataset is built']
```

Usage

```
{'run_Taskmaster1Parser': 'run the Taskmaster1Parser to load and parse Taskmaster-1 self-dialogs and woz-dialogs JSON data into TOD structured episodes', 'run_SystemTeacher': 'run the SystemTeacher to train a dialogue system agent on Taskmaster-1 assistant utterances using the TOD format', 'run_UserSimulatorTeacher': 'run the UserSimulatorTeacher to train a user simulator agent on Taskmaster-1 user utterances using the TOD format', 'run_SelfDialogueTeacher': 'run the SelfDialogueTeacher to train a dialogue model on written two-person dialogues with both user and assistant passes', 'run_WozDialogueTeacher': 'run the WozDialogueTeacher to train a dialogue model on spoken two-person dialogues with optional corrupt example exclusion'}
```

## File: facebookresearch_parlai/parlai/tasks/taskmaster/build.py

Prompts

```
['run the Taskmaster1Parser to load and parse Taskmaster-1 self-dialogs and woz-dialogs JSON data into TOD structured episodes', 'run the SystemTeacher to train a dialogue system agent on Taskmaster-1 assistant utterances using the TOD format', 'run the UserSimulatorTeacher to train a user simulator agent on Taskmaster-1 user utterances using the TOD format', 'run the SelfDialogueTeacher to train a dialogue model on written two-person dialogues with both user and assistant passes', 'run the WozDialogueTeacher to train a dialogue model on spoken two-person dialogues with optional corrupt example exclusion', 'run the build function to download and set up the Taskmaster-1 dataset into the data directory', 'download the self-dialogs.json and woz-dialogs.json files from the Taskmaster GitHub repository', 'check if the Taskmaster-1 dataset has already been built at version 1.02', 'remove an older version of the Taskmaster-1 dataset directory before rebuilding', 'mark the Taskmaster-1 dataset directory as built with the current version string', 'smoothen a conversation by aggregating contiguous responses from the same speaker into alternating USER and ASSISTANT turns', 'generate a cheatsheet for a dialogue episode showing first and last USER and ASSISTANT reply indexes and example counts', 'join two utterances from the same speaker into a single utterance with newline-separated text and an incremented counter', 'update the index field of each utterance in a conversation list to sequential zero-based integers', 'get the file path to a Taskmaster 1 data file after ensuring the dataset is built']
```

Usage

```
{'build_taskmaster_dataset': 'run the build function to download and set up the Taskmaster-1 dataset into the data directory', 'download_taskmaster_dialogs': 'download the self-dialogs.json and woz-dialogs.json files from the Taskmaster GitHub repository', 'check_taskmaster_version': 'check if the Taskmaster-1 dataset has already been built at version 1.02', 'remove_outdated_taskmaster_data': 'remove an older version of the Taskmaster-1 dataset directory before rebuilding', 'mark_taskmaster_built': 'mark the Taskmaster-1 dataset directory as built with the current version string'}
```

## File: facebookresearch_parlai/parlai/tasks/taskmaster/tm_utils.py

Prompts

```
['run the Taskmaster1Parser to load and parse Taskmaster-1 self-dialogs and woz-dialogs JSON data into TOD structured episodes', 'run the SystemTeacher to train a dialogue system agent on Taskmaster-1 assistant utterances using the TOD format', 'run the UserSimulatorTeacher to train a user simulator agent on Taskmaster-1 user utterances using the TOD format', 'run the SelfDialogueTeacher to train a dialogue model on written two-person dialogues with both user and assistant passes', 'run the WozDialogueTeacher to train a dialogue model on spoken two-person dialogues with optional corrupt example exclusion', 'run the build function to download and set up the Taskmaster-1 dataset into the data directory', 'download the self-dialogs.json and woz-dialogs.json files from the Taskmaster GitHub repository', 'check if the Taskmaster-1 dataset has already been built at version 1.02', 'remove an older version of the Taskmaster-1 dataset directory before rebuilding', 'mark the Taskmaster-1 dataset directory as built with the current version string', 'smoothen a conversation by aggregating contiguous responses from the same speaker into alternating USER and ASSISTANT turns', 'generate a cheatsheet for a dialogue episode showing first and last USER and ASSISTANT reply indexes and example counts', 'join two utterances from the same speaker into a single utterance with newline-separated text and an incremented counter', 'update the index field of each utterance in a conversation list to sequential zero-based integers', 'get the file path to a Taskmaster 1 data file after ensuring the dataset is built']
```

Usage

```
{'smoothen_convo': 'smoothen a conversation by aggregating contiguous responses from the same speaker into alternating USER and ASSISTANT turns', 'gen_ep_cheatsheet': 'generate a cheatsheet for a dialogue episode showing first and last USER and ASSISTANT reply indexes and example counts', 'join_speech': 'join two utterances from the same speaker into a single utterance with newline-separated text and an incremented counter', 'update_indexes': 'update the index field of each utterance in a conversation list to sequential zero-based integers', 'path_datafile': 'get the file path to a Taskmaster 1 data file after ensuring the dataset is built'}
```

