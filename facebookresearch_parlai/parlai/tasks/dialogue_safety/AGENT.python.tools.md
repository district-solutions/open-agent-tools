# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/dialogue_safety/agents.py

Prompts

```
['run the StandardTeacher to load and serve dialogue safety standard collection data', 'run the AdversarialTeacher to load and serve dialogue safety adversarial collection data', 'run the MultiturnTeacher to serve multi-turn adversarial dialogue safety conversations', 'run the WikiToxicCommentsTeacher to serve Wikipedia toxic comment classification data', 'review the _balance_data method to understand how OK and NOT OK labels are balanced', 'review the _BaseSafetyTeacher abstract class for single turn safety dialogue teaching in ParlAI', 'refactor the add_cmdline_args method to add new safety teacher CLI arguments like --round and --round-only', 'test the _setup_data method to verify it loads and shuffles safety data across rounds correctly', 'create a subclass of _BaseSafetyTeacher that implements the abstract _load_data_dump method for custom safety data', 'summarize the get method that returns a Message object for a given episode index from safety data', 'call build(datapath) to download single and multi turn dialogue safety datasets', 'download the single turn safety JSON dataset using the RESOURCES list', 'download the multi turn safety JSON dataset using the RESOURCES list', 'check if dialogue safety data is already built at version v1.0', 'remove older versions of the dialogue safety data directory before rebuilding']
```

Usage

```
{'run_standard_teacher': 'run the StandardTeacher to load and serve dialogue safety standard collection data', 'run_adversarial_teacher': 'run the AdversarialTeacher to load and serve dialogue safety adversarial collection data', 'run_multiturn_teacher': 'run the MultiturnTeacher to serve multi-turn adversarial dialogue safety conversations', 'run_wikitoxic_teacher': 'run the WikiToxicCommentsTeacher to serve Wikipedia toxic comment classification data', 'review_balance_data': 'review the _balance_data method to understand how OK and NOT OK labels are balanced'}
```

## File: facebookresearch_parlai/parlai/tasks/dialogue_safety/base_agent.py

Prompts

```
['run the StandardTeacher to load and serve dialogue safety standard collection data', 'run the AdversarialTeacher to load and serve dialogue safety adversarial collection data', 'run the MultiturnTeacher to serve multi-turn adversarial dialogue safety conversations', 'run the WikiToxicCommentsTeacher to serve Wikipedia toxic comment classification data', 'review the _balance_data method to understand how OK and NOT OK labels are balanced', 'review the _BaseSafetyTeacher abstract class for single turn safety dialogue teaching in ParlAI', 'refactor the add_cmdline_args method to add new safety teacher CLI arguments like --round and --round-only', 'test the _setup_data method to verify it loads and shuffles safety data across rounds correctly', 'create a subclass of _BaseSafetyTeacher that implements the abstract _load_data_dump method for custom safety data', 'summarize the get method that returns a Message object for a given episode index from safety data', 'call build(datapath) to download single and multi turn dialogue safety datasets', 'download the single turn safety JSON dataset using the RESOURCES list', 'download the multi turn safety JSON dataset using the RESOURCES list', 'check if dialogue safety data is already built at version v1.0', 'remove older versions of the dialogue safety data directory before rebuilding']
```

Usage

```
{'review_BaseSafetyTeacher': 'review the _BaseSafetyTeacher abstract class for single turn safety dialogue teaching in ParlAI', 'refactor_add_cmdline_args': 'refactor the add_cmdline_args method to add new safety teacher CLI arguments like --round and --round-only', 'test_setup_data': 'test the _setup_data method to verify it loads and shuffles safety data across rounds correctly', 'create_subclass_BaseSafetyTeacher': 'create a subclass of _BaseSafetyTeacher that implements the abstract _load_data_dump method for custom safety data', 'summarize_get_method': 'summarize the get method that returns a Message object for a given episode index from safety data'}
```

## File: facebookresearch_parlai/parlai/tasks/dialogue_safety/build.py

Prompts

```
['run the StandardTeacher to load and serve dialogue safety standard collection data', 'run the AdversarialTeacher to load and serve dialogue safety adversarial collection data', 'run the MultiturnTeacher to serve multi-turn adversarial dialogue safety conversations', 'run the WikiToxicCommentsTeacher to serve Wikipedia toxic comment classification data', 'review the _balance_data method to understand how OK and NOT OK labels are balanced', 'review the _BaseSafetyTeacher abstract class for single turn safety dialogue teaching in ParlAI', 'refactor the add_cmdline_args method to add new safety teacher CLI arguments like --round and --round-only', 'test the _setup_data method to verify it loads and shuffles safety data across rounds correctly', 'create a subclass of _BaseSafetyTeacher that implements the abstract _load_data_dump method for custom safety data', 'summarize the get method that returns a Message object for a given episode index from safety data', 'call build(datapath) to download single and multi turn dialogue safety datasets', 'download the single turn safety JSON dataset using the RESOURCES list', 'download the multi turn safety JSON dataset using the RESOURCES list', 'check if dialogue safety data is already built at version v1.0', 'remove older versions of the dialogue safety data directory before rebuilding']
```

Usage

```
{'build_dialogue_safety_data': 'call build(datapath) to download single and multi turn dialogue safety datasets', 'download_single_turn_safety': 'download the single turn safety JSON dataset using the RESOURCES list', 'download_multi_turn_safety': 'download the multi turn safety JSON dataset using the RESOURCES list', 'check_data_built': 'check if dialogue safety data is already built at version v1.0', 'remove_outdated_data': 'remove older versions of the dialogue safety data directory before rebuilding'}
```

