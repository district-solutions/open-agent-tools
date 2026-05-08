# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/airdialogue/agents.py

Prompts

```
['build a Parlai teacher that loads and serves AirDialogue flight booking dialogue data for training', 'create an AirDialogueTeacher instance to load train, validation, or test dialogue episodes from JSON files', 'test the AirDialogueTeacher get method to retrieve a specific dialogue turn with its label', 'review the AirDialogueTeacher num_examples method to count total dialogue turns across all episodes', 'summarize the save_messages_from_path method that parses JSONL dialogue files into message lists', 'build the AirDialogue dataset by downloading and extracting data to the specified datapath', 'run the build function to download and set up the AirDialogue dataset for ParlAI', 'download the AirDialogue dataset tar.gz file from Google Storage using the RESOURCES list', 'check if the AirDialogue dataset is already built at version 1.0 before downloading', 'remove an outdated AirDialogue dataset directory before rebuilding with the latest version']
```

Usage

```
{'build_airdialogue_teacher': 'build a Parlai teacher that loads and serves AirDialogue flight booking dialogue data for training', 'create_airdialogue_data_loader': 'create an AirDialogueTeacher instance to load train, validation, or test dialogue episodes from JSON files', 'test_get_dialogue_turn': 'test the AirDialogueTeacher get method to retrieve a specific dialogue turn with its label', 'review_num_examples': 'review the AirDialogueTeacher num_examples method to count total dialogue turns across all episodes', 'summarize_save_messages_from_path': 'summarize the save_messages_from_path method that parses JSONL dialogue files into message lists'}
```

## File: facebookresearch_parlai/parlai/tasks/airdialogue/build.py

Prompts

```
['build a Parlai teacher that loads and serves AirDialogue flight booking dialogue data for training', 'create an AirDialogueTeacher instance to load train, validation, or test dialogue episodes from JSON files', 'test the AirDialogueTeacher get method to retrieve a specific dialogue turn with its label', 'review the AirDialogueTeacher num_examples method to count total dialogue turns across all episodes', 'summarize the save_messages_from_path method that parses JSONL dialogue files into message lists', 'build the AirDialogue dataset by downloading and extracting data to the specified datapath', 'run the build function to download and set up the AirDialogue dataset for ParlAI', 'download the AirDialogue dataset tar.gz file from Google Storage using the RESOURCES list', 'check if the AirDialogue dataset is already built at version 1.0 before downloading', 'remove an outdated AirDialogue dataset directory before rebuilding with the latest version']
```

Usage

```
{'build_airdialogue_data': 'build the AirDialogue dataset by downloading and extracting data to the specified datapath', 'run_build_function': 'run the build function to download and set up the AirDialogue dataset for ParlAI', 'download_airdialogue_resources': 'download the AirDialogue dataset tar.gz file from Google Storage using the RESOURCES list', 'check_airdialogue_version': 'check if the AirDialogue dataset is already built at version 1.0 before downloading', 'remove_old_airdialogue_data': 'remove an outdated AirDialogue dataset directory before rebuilding with the latest version'}
```

