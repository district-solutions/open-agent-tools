# Agent Python Tools

- repo: facebookresearch/openlth
- repo_uri: https://github.com/facebookresearch/open_lth

## File: facebookresearch_openlth/lottery/desc.py

Prompts

```
['create a LotteryDesc instance from argparse arguments with model, dataset, training, and pruning hyperparameters', 'add lottery ticket training CLI arguments including rewinding and pretraining options to an argparse parser', 'compute the file system path for a lottery ticket experiment run given replicate and pruning level', 'convert a training step string like 160ep or 50000it into a Step object using dataset iteration info', 'get a formatted multi-line display string summarizing all hyperparameters for a lottery ticket experiment', 'run a lottery ticket hypothesis experiment with iterative pruning and training across multiple levels', 'create a LotteryRunner instance from parsed argparse command line arguments', 'pretrain a model using pretraining dataset and training hyperparameters before lottery experiments', 'prune a model at a given level and train the pruned model to completion']
```

Usage

```
{'create_lottery_desc_from_args': 'create a LotteryDesc instance from argparse arguments with model, dataset, training, and pruning hyperparameters', 'add_lottery_args_to_parser': 'add lottery ticket training CLI arguments including rewinding and pretraining options to an argparse parser', 'compute_run_path': 'compute the file system path for a lottery ticket experiment run given replicate and pruning level', 'convert_string_to_step': 'convert a training step string like 160ep or 50000it into a Step object using dataset iteration info', 'get_lottery_desc_display': 'get a formatted multi-line display string summarizing all hyperparameters for a lottery ticket experiment'}
```

## File: facebookresearch_openlth/lottery/runner.py

Prompts

```
['create a LotteryDesc instance from argparse arguments with model, dataset, training, and pruning hyperparameters', 'add lottery ticket training CLI arguments including rewinding and pretraining options to an argparse parser', 'compute the file system path for a lottery ticket experiment run given replicate and pruning level', 'convert a training step string like 160ep or 50000it into a Step object using dataset iteration info', 'get a formatted multi-line display string summarizing all hyperparameters for a lottery ticket experiment', 'run a lottery ticket hypothesis experiment with iterative pruning and training across multiple levels', 'create a LotteryRunner instance from parsed argparse command line arguments', 'pretrain a model using pretraining dataset and training hyperparameters before lottery experiments', 'prune a model at a given level and train the pruned model to completion']
```

Usage

```
{'run_lottery_experiment': 'run a lottery ticket hypothesis experiment with iterative pruning and training across multiple levels', 'create_lottery_runner_from_args': 'create a LotteryRunner instance from parsed argparse command line arguments', 'add_lottery_args_to_parser': 'add lottery ticket hyperparameters and job arguments to an argparse ArgumentParser', 'pretrain_model': 'pretrain a model using pretraining dataset and training hyperparameters before lottery experiments', 'prune_and_train_level': 'prune a model at a given level and train the pruned model to completion'}
```

