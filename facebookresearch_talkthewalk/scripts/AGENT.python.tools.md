# Agent Python Tools

- repo: facebookresearch/talkthewalk
- repo_uri: https://github.com/facebookresearch/talkthewalk

## File: facebookresearch_talkthewalk/scripts/compute_upperbound.py

Prompts

```
['run the compute upperbound script with --data-dir, --orientation-aware, --max-T, and --condition-on-action flags', 'run prediction_upperbound to compute accuracy upperbound for a sequence of landmarks given neighborhood and boundaries', 'run process to calculate upperbound accuracy across all configs for a given number of steps and action space', 'init paths agnostic to create 4x4 grid paths with location and landmark sequences for step-agnostic navigation', 'init paths aware to create 4x4x4 grid paths with orientation for step-aware navigation with turn actions', 'run the evaluate script to test tourist-guide navigation models on train, valid, and test datasets', 'run the evaluate script with continuous communication channel between tourist and guide models', 'run the evaluate script with discrete communication channel between tourist and guide models', 'run the evaluate script with natural language communication and a specified decoding strategy', 'run the evaluate script on GPU with cuda enabled for faster model inference', 'run the script to generate train, valid, and test splits for the TalkTheWalk dataset', 'run get_configurations to generate neighborhood boundary configurations split into train, valid, and test sets', 'review the get_configurations function that creates 4x4 grid boundary configs for each neighborhood', 'summarize the script that splits TalkTheWalk dialogues into train, valid, and test JSON files', 'refactor get_configurations to accept boundaries as a parameter instead of relying on the imported module']
```

Usage

```
{'run_compute_upperbound_cli': 'run the compute upperbound script with --data-dir, --orientation-aware, --max-T, and --condition-on-action flags', 'run_prediction_upperbound': 'run prediction_upperbound to compute accuracy upperbound for a sequence of landmarks given neighborhood and boundaries', 'run_process_upperbound': 'run process to calculate upperbound accuracy across all configs for a given number of steps and action space', 'init_paths_agnostic': 'init paths agnostic to create 4x4 grid paths with location and landmark sequences for step-agnostic navigation', 'init_paths_aware': 'init paths aware to create 4x4x4 grid paths with orientation for step-aware navigation with turn actions'}
```

## File: facebookresearch_talkthewalk/scripts/evaluate_location.py

Prompts

```
['run the compute upperbound script with --data-dir, --orientation-aware, --max-T, and --condition-on-action flags', 'run prediction_upperbound to compute accuracy upperbound for a sequence of landmarks given neighborhood and boundaries', 'run process to calculate upperbound accuracy across all configs for a given number of steps and action space', 'init paths agnostic to create 4x4 grid paths with location and landmark sequences for step-agnostic navigation', 'init paths aware to create 4x4x4 grid paths with orientation for step-aware navigation with turn actions', 'run the evaluate script to test tourist-guide navigation models on train, valid, and test datasets', 'run the evaluate script with continuous communication channel between tourist and guide models', 'run the evaluate script with discrete communication channel between tourist and guide models', 'run the evaluate script with natural language communication and a specified decoding strategy', 'run the evaluate script on GPU with cuda enabled for faster model inference', 'run the script to generate train, valid, and test splits for the TalkTheWalk dataset', 'run get_configurations to generate neighborhood boundary configurations split into train, valid, and test sets', 'review the get_configurations function that creates 4x4 grid boundary configs for each neighborhood', 'summarize the script that splits TalkTheWalk dialogues into train, valid, and test JSON files', 'refactor get_configurations to accept boundaries as a parameter instead of relying on the imported module']
```

Usage

```
{'run_evaluate_location': 'run the evaluate script to test tourist-guide navigation models on train, valid, and test datasets', 'run_evaluate_continuous': 'run the evaluate script with continuous communication channel between tourist and guide models', 'run_evaluate_discrete': 'run the evaluate script with discrete communication channel between tourist and guide models', 'run_evaluate_natural': 'run the evaluate script with natural language communication and a specified decoding strategy', 'run_evaluate_gpu': 'run the evaluate script on GPU with cuda enabled for faster model inference'}
```

## File: facebookresearch_talkthewalk/scripts/split_dataset.py

Prompts

```
['run the compute upperbound script with --data-dir, --orientation-aware, --max-T, and --condition-on-action flags', 'run prediction_upperbound to compute accuracy upperbound for a sequence of landmarks given neighborhood and boundaries', 'run process to calculate upperbound accuracy across all configs for a given number of steps and action space', 'init paths agnostic to create 4x4 grid paths with location and landmark sequences for step-agnostic navigation', 'init paths aware to create 4x4x4 grid paths with orientation for step-aware navigation with turn actions', 'run the evaluate script to test tourist-guide navigation models on train, valid, and test datasets', 'run the evaluate script with continuous communication channel between tourist and guide models', 'run the evaluate script with discrete communication channel between tourist and guide models', 'run the evaluate script with natural language communication and a specified decoding strategy', 'run the evaluate script on GPU with cuda enabled for faster model inference', 'run the script to generate train, valid, and test splits for the TalkTheWalk dataset', 'run get_configurations to generate neighborhood boundary configurations split into train, valid, and test sets', 'review the get_configurations function that creates 4x4 grid boundary configs for each neighborhood', 'summarize the script that splits TalkTheWalk dialogues into train, valid, and test JSON files', 'refactor get_configurations to accept boundaries as a parameter instead of relying on the imported module']
```

Usage

```
{'run_split_dataset': 'run the script to generate train, valid, and test splits for the TalkTheWalk dataset', 'run_get_configurations': 'run get_configurations to generate neighborhood boundary configurations split into train, valid, and test sets', 'review_get_configurations': 'review the get_configurations function that creates 4x4 grid boundary configs for each neighborhood', 'summarize_split_dataset': 'summarize the script that splits TalkTheWalk dialogues into train, valid, and test JSON files', 'refactor_get_configurations': 'refactor get_configurations to accept boundaries as a parameter instead of relying on the imported module'}
```

