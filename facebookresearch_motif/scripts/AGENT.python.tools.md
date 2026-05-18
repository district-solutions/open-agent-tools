# Agent Python Tools

- repo: facebookresearch/motif
- repo_uri: https://github.com/facebookresearch/motif

## File: facebookresearch_motif/scripts/main.py

Prompts

```
['run the RL algorithm with parsed arguments and optional W&B tracking via main entry point', 'parse command line arguments including custom env episode length and LLM reward coefficient', 'add custom CLI arguments like episode length and LLM reward to an argparse parser', 'initialize Weights and Biases tracking for the nethack_project when WANDB_API_KEY is set', 'import and register NetHack Learning Environment tasks, encoders, and environments for RL training', 'train a reward model using binary cross entropy on trajectory preference pairs from a dataset', 'validate the reward model on a validation set and log accuracy and loss metrics', 'save the reward model checkpoint, optimizer state, and training metrics to disk', 'extract and sort all training messages from the dataset loader for RMS calculation', 'calculate the running mean and standard deviation of rewards across the training dataset', 'run the RL agent evaluation script to visualize trained policy behavior in the environment', 'run the enjoy function to evaluate a trained actor-critic model with optional reward model', 'run parse_all_args to parse command line arguments for RL agent visualization with sleep and render options', 'run add_extra_params to add sleep and render CLI arguments to the argument parser', 'run the main entry point to parse args and execute RL agent evaluation with rendering']
```

Usage

```
{'run_rl_algorithm': 'run the RL algorithm with parsed arguments and optional W&B tracking via main entry point', 'parse_all_args': 'parse command line arguments including custom env episode length and LLM reward coefficient', 'add_extra_params': 'add custom CLI arguments like episode length and LLM reward to an argparse parser', 'init_wandb_tracking': 'initialize Weights and Biases tracking for the nethack_project when WANDB_API_KEY is set', 'register_nle_components': 'import and register NetHack Learning Environment tasks, encoders, and environments for RL training'}
```

## File: facebookresearch_motif/scripts/train_reward.py

Prompts

```
['run the RL algorithm with parsed arguments and optional W&B tracking via main entry point', 'parse command line arguments including custom env episode length and LLM reward coefficient', 'add custom CLI arguments like episode length and LLM reward to an argparse parser', 'initialize Weights and Biases tracking for the nethack_project when WANDB_API_KEY is set', 'import and register NetHack Learning Environment tasks, encoders, and environments for RL training', 'train a reward model using binary cross entropy on trajectory preference pairs from a dataset', 'validate the reward model on a validation set and log accuracy and loss metrics', 'save the reward model checkpoint, optimizer state, and training metrics to disk', 'extract and sort all training messages from the dataset loader for RMS calculation', 'calculate the running mean and standard deviation of rewards across the training dataset', 'run the RL agent evaluation script to visualize trained policy behavior in the environment', 'run the enjoy function to evaluate a trained actor-critic model with optional reward model', 'run parse_all_args to parse command line arguments for RL agent visualization with sleep and render options', 'run add_extra_params to add sleep and render CLI arguments to the argument parser', 'run the main entry point to parse args and execute RL agent evaluation with rendering']
```

Usage

```
{'train_reward_model': 'train a reward model using binary cross entropy on trajectory preference pairs from a dataset', 'validate_reward_model': 'validate the reward model on a validation set and log accuracy and loss metrics', 'save_checkpoint': 'save the reward model checkpoint, optimizer state, and training metrics to disk', 'get_all_messages': 'extract and sort all training messages from the dataset loader for RMS calculation', 'get_rms': 'calculate the running mean and standard deviation of rewards across the training dataset'}
```

## File: facebookresearch_motif/scripts/visualize.py

Prompts

```
['run the RL algorithm with parsed arguments and optional W&B tracking via main entry point', 'parse command line arguments including custom env episode length and LLM reward coefficient', 'add custom CLI arguments like episode length and LLM reward to an argparse parser', 'initialize Weights and Biases tracking for the nethack_project when WANDB_API_KEY is set', 'import and register NetHack Learning Environment tasks, encoders, and environments for RL training', 'train a reward model using binary cross entropy on trajectory preference pairs from a dataset', 'validate the reward model on a validation set and log accuracy and loss metrics', 'save the reward model checkpoint, optimizer state, and training metrics to disk', 'extract and sort all training messages from the dataset loader for RMS calculation', 'calculate the running mean and standard deviation of rewards across the training dataset', 'run the RL agent evaluation script to visualize trained policy behavior in the environment', 'run the enjoy function to evaluate a trained actor-critic model with optional reward model', 'run parse_all_args to parse command line arguments for RL agent visualization with sleep and render options', 'run add_extra_params to add sleep and render CLI arguments to the argument parser', 'run the main entry point to parse args and execute RL agent evaluation with rendering']
```

Usage

```
{'run_visualize_rl_agent': 'run the RL agent evaluation script to visualize trained policy behavior in the environment', 'run_enjoy_function': 'run the enjoy function to evaluate a trained actor-critic model with optional reward model', 'run_parse_all_args': 'run parse_all_args to parse command line arguments for RL agent visualization with sleep and render options', 'run_add_extra_params': 'run add_extra_params to add sleep and render CLI arguments to the argument parser', 'run_main_entry': 'run the main entry point to parse args and execute RL agent evaluation with rendering'}
```

