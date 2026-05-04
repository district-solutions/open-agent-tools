# Agent Python Tools

- repo: facebookresearch/elf
- repo_uri: https://github.com/facebookresearch/elf

## File: facebookresearch_elf/elf/context_utils.py

Prompts

```
['create a ContextArgs instance that defines CLI arguments for RL training and MCTS options', 'run ContextArgs initialize method to populate a context object with num_games, T, and MCTS settings', 'review the ContextArgs _on_get_args hook that adjusts num_games and batchsize when eval mode is enabled', 'test the ContextArgs class to verify eval mode sets num_games and batchsize to 1', 'refactor the ContextArgs initialize method to customize MCTS options like threads, rollouts, and pick_method', 'create a MoreLabels instance that registers an additional_labels argument via ArgsProvider for batch label configuration', 'call add_labels on a MoreLabels instance to inject extra label keys into a batch description dict', 'build a MoreLabels object and pass a comma-separated additional_labels string to extend input keys in a descriptor', 'review the MoreLabels class and its add_labels method to understand how extra labels are merged into batch descriptors', 'summarize the MoreLabels class which provides an ArgsProvider hook to add custom labels to RL batch descriptions']
```

Usage

```
{'create_ContextArgs': 'create a ContextArgs instance that defines CLI arguments for RL training and MCTS options', 'run_ContextArgs_initialize': 'run ContextArgs initialize method to populate a context object with num_games, T, and MCTS settings', 'review_ContextArgs_on_get_args': 'review the ContextArgs _on_get_args hook that adjusts num_games and batchsize when eval mode is enabled', 'test_ContextArgs_eval_mode': 'test the ContextArgs class to verify eval mode sets num_games and batchsize to 1', 'refactor_ContextArgs_mcts_options': 'refactor the ContextArgs initialize method to customize MCTS options like threads, rollouts, and pick_method'}
```

## File: facebookresearch_elf/elf/more_labels.py

Prompts

```
['create a ContextArgs instance that defines CLI arguments for RL training and MCTS options', 'run ContextArgs initialize method to populate a context object with num_games, T, and MCTS settings', 'review the ContextArgs _on_get_args hook that adjusts num_games and batchsize when eval mode is enabled', 'test the ContextArgs class to verify eval mode sets num_games and batchsize to 1', 'refactor the ContextArgs initialize method to customize MCTS options like threads, rollouts, and pick_method', 'create a MoreLabels instance that registers an additional_labels argument via ArgsProvider for batch label configuration', 'call add_labels on a MoreLabels instance to inject extra label keys into a batch description dict', 'build a MoreLabels object and pass a comma-separated additional_labels string to extend input keys in a descriptor', 'review the MoreLabels class and its add_labels method to understand how extra labels are merged into batch descriptors', 'summarize the MoreLabels class which provides an ArgsProvider hook to add custom labels to RL batch descriptions']
```

Usage

```
{'init_MoreLabels': 'create a MoreLabels instance that registers an additional_labels argument via ArgsProvider for batch label configuration', 'add_labels_to_desc': 'call add_labels on a MoreLabels instance to inject extra label keys into a batch description dict', 'configure_additional_labels': 'build a MoreLabels object and pass a comma-separated additional_labels string to extend input keys in a descriptor', 'review_MoreLabels_class': 'review the MoreLabels class and its add_labels method to understand how extra labels are merged into batch descriptors', 'summarize_MoreLabels': 'summarize the MoreLabels class which provides an ArgsProvider hook to add custom labels to RL batch descriptions'}
```

