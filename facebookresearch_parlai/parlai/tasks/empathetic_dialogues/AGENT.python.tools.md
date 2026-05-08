# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/empathetic_dialogues/agents.py

Prompts

```
['build a Parlai teacher that loads empathetic dialogues CSV data with emotion and situation metadata', 'create a function that parses CSV dialogue turns into Message objects with text, labels, and emotion fields', 'test the EmpatheticDialoguesTeacher setup_data method to verify CSV parsing and episode generation', 'refactor the _select_dialogues_to_add method to filter conversation sides based on experiencer_only flag', 'review the EmpatheticDialoguesTeacher add_cmdline_args method to understand the train_experiencer_only argument', 'run the build function to download and prepare the empathetic dialogues dataset for ParlAI', 'download the empathetic dialogues tar.gz file from parl.ai to the specified datapath directory', 'check if the empathetic dialogues dataset is already built at version 1.0 in the datapath', 'remove an older version of the empathetic dialogues dataset directory before rebuilding', 'mark the empathetic dialogues dataset build as complete with version string 1.0', 'review the SelfChatWorld class that overrides get_contexts to return None for empathetic dialogues self-chat', 'summarize the SelfChatWorld class which extends SelfChatBaseWorld with a no-context override for empathetic dialogues']
```

Usage

```
{'build_empathetic_teacher': 'build a Parlai teacher that loads empathetic dialogues CSV data with emotion and situation metadata', 'create_dialogue_parser': 'create a function that parses CSV dialogue turns into Message objects with text, labels, and emotion fields', 'test_setup_data': 'test the EmpatheticDialoguesTeacher setup_data method to verify CSV parsing and episode generation', 'refactor_select_dialogues': 'refactor the _select_dialogues_to_add method to filter conversation sides based on experiencer_only flag', 'review_add_cmdline_args': 'review the EmpatheticDialoguesTeacher add_cmdline_args method to understand the train_experiencer_only argument'}
```

## File: facebookresearch_parlai/parlai/tasks/empathetic_dialogues/build.py

Prompts

```
['build a Parlai teacher that loads empathetic dialogues CSV data with emotion and situation metadata', 'create a function that parses CSV dialogue turns into Message objects with text, labels, and emotion fields', 'test the EmpatheticDialoguesTeacher setup_data method to verify CSV parsing and episode generation', 'refactor the _select_dialogues_to_add method to filter conversation sides based on experiencer_only flag', 'review the EmpatheticDialoguesTeacher add_cmdline_args method to understand the train_experiencer_only argument', 'run the build function to download and prepare the empathetic dialogues dataset for ParlAI', 'download the empathetic dialogues tar.gz file from parl.ai to the specified datapath directory', 'check if the empathetic dialogues dataset is already built at version 1.0 in the datapath', 'remove an older version of the empathetic dialogues dataset directory before rebuilding', 'mark the empathetic dialogues dataset build as complete with version string 1.0', 'review the SelfChatWorld class that overrides get_contexts to return None for empathetic dialogues self-chat', 'summarize the SelfChatWorld class which extends SelfChatBaseWorld with a no-context override for empathetic dialogues']
```

Usage

```
{'build_empathetic_dialogues_dataset': 'run the build function to download and prepare the empathetic dialogues dataset for ParlAI', 'download_empathetic_dialogues_data': 'download the empathetic dialogues tar.gz file from parl.ai to the specified datapath directory', 'check_empathetic_dialogues_version': 'check if the empathetic dialogues dataset is already built at version 1.0 in the datapath', 'remove_outdated_empathetic_dialogues': 'remove an older version of the empathetic dialogues dataset directory before rebuilding', 'mark_empathetic_dialogues_done': 'mark the empathetic dialogues dataset build as complete with version string 1.0'}
```

## File: facebookresearch_parlai/parlai/tasks/empathetic_dialogues/worlds.py

Prompts

```
['build a Parlai teacher that loads empathetic dialogues CSV data with emotion and situation metadata', 'create a function that parses CSV dialogue turns into Message objects with text, labels, and emotion fields', 'test the EmpatheticDialoguesTeacher setup_data method to verify CSV parsing and episode generation', 'refactor the _select_dialogues_to_add method to filter conversation sides based on experiencer_only flag', 'review the EmpatheticDialoguesTeacher add_cmdline_args method to understand the train_experiencer_only argument', 'run the build function to download and prepare the empathetic dialogues dataset for ParlAI', 'download the empathetic dialogues tar.gz file from parl.ai to the specified datapath directory', 'check if the empathetic dialogues dataset is already built at version 1.0 in the datapath', 'remove an older version of the empathetic dialogues dataset directory before rebuilding', 'mark the empathetic dialogues dataset build as complete with version string 1.0', 'review the SelfChatWorld class that overrides get_contexts to return None for empathetic dialogues self-chat', 'summarize the SelfChatWorld class which extends SelfChatBaseWorld with a no-context override for empathetic dialogues']
```

Usage

```
{'review_SelfChatWorld': 'review the SelfChatWorld class that overrides get_contexts to return None for empathetic dialogues self-chat', 'summarize_SelfChatWorld': 'summarize the SelfChatWorld class which extends SelfChatBaseWorld with a no-context override for empathetic dialogues'}
```

