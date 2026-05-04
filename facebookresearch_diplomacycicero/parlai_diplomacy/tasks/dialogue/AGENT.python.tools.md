# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/parlai_diplomacy/tasks/dialogue/base_agent.py

Prompts

```
['build a ParlAI dialogue teacher that streams Diplomacy game messages and predicts the next message', 'create command-line arguments for the dialogue teacher including message filtering and pseudo order generation options', 'test the custom evaluation method that calculates per-year loss and perplexity metrics by player rating', 'review the build_example method that adds pseudo order prefixes and justification generation to training examples', 'refactor the _load_pseudo_orders method to load and return pseudo orders from a JSON file by game ID', 'create a BasePseudoorderDialogueChunkTeacher subclass to load predicted pseudo orders as dialogue training data', 'register the message_history_pseudoorder_dialogue_chunk teacher for message history with pseudo order input', 'register the message_history_shortstate_pseudoorder_dialogue_chunk teacher for message with state input', 'register the message_history_lastorder_pseudoorder_dialogue_chunk teacher for last phase order with pseudo order input', 'review the requires_pseudo_orders method that always returns True for pseudo order dialogue teachers']
```

Usage

```
{'build_BaseDialogueChunkTeacher': 'build a ParlAI dialogue teacher that streams Diplomacy game messages and predicts the next message', 'create_add_cmdline_args': 'create command-line arguments for the dialogue teacher including message filtering and pseudo order generation options', 'test_custom_evaluation': 'test the custom evaluation method that calculates per-year loss and perplexity metrics by player rating', 'review_build_example': 'review the build_example method that adds pseudo order prefixes and justification generation to training examples', 'refactor_load_pseudo_orders': 'refactor the _load_pseudo_orders method to load and return pseudo orders from a JSON file by game ID'}
```

## File: facebookresearch_diplomacycicero/parlai_diplomacy/tasks/dialogue/pseudo_order_agents.py

Prompts

```
['build a ParlAI dialogue teacher that streams Diplomacy game messages and predicts the next message', 'create command-line arguments for the dialogue teacher including message filtering and pseudo order generation options', 'test the custom evaluation method that calculates per-year loss and perplexity metrics by player rating', 'review the build_example method that adds pseudo order prefixes and justification generation to training examples', 'refactor the _load_pseudo_orders method to load and return pseudo orders from a JSON file by game ID', 'create a BasePseudoorderDialogueChunkTeacher subclass to load predicted pseudo orders as dialogue training data', 'register the message_history_pseudoorder_dialogue_chunk teacher for message history with pseudo order input', 'register the message_history_shortstate_pseudoorder_dialogue_chunk teacher for message with state input', 'register the message_history_lastorder_pseudoorder_dialogue_chunk teacher for last phase order with pseudo order input', 'review the requires_pseudo_orders method that always returns True for pseudo order dialogue teachers']
```

Usage

```
{'create_pseudoorder_dialogue_teacher': 'create a BasePseudoorderDialogueChunkTeacher subclass to load predicted pseudo orders as dialogue training data', 'register_message_history_pseudoorder_teacher': 'register the message_history_pseudoorder_dialogue_chunk teacher for message history with pseudo order input', 'register_shortstate_pseudoorder_teacher': 'register the message_history_shortstate_pseudoorder_dialogue_chunk teacher for message with state input', 'register_lastorder_pseudoorder_teacher': 'register the message_history_lastorder_pseudoorder_dialogue_chunk teacher for last phase order with pseudo order input', 'review_requires_pseudo_orders_method': 'review the requires_pseudo_orders method that always returns True for pseudo order dialogue teachers'}
```

