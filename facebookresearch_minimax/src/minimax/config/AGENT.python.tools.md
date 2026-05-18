# Agent Python Tools

- repo: facebookresearch/minimax
- repo_uri: https://github.com/facebookresearch/minimax

## File: facebookresearch_minimax/src/minimax/config/make_cmd.py

Prompts

```
['generate training shell commands from a parameter dict with configurable trial count and seed offsets', 'generate all parameter combinations from a hyperparameter grid dictionary merged with default values', 'generate a unique experiment ID string from training parameters including environment, runner, and model info', 'read wandb base URL and API key from a local config/wandb.json file', 'run the CLI to generate training or eval commands from a JSON config grid file with optional W&B integration', 'get the experiment runner info string from a config object using the train_runner handler', 'get the environment info string from a config object based on the env_name and train_runner', 'get the model architecture info string for a given role from a config object', 'get the algorithm info string for a given role using the agent_rl_algo handler', 'extract the base role name by removing _tch or _st suffixes from a role string']
```

Usage

```
{'generate_train_cmds': 'generate training shell commands from a parameter dict with configurable trial count and seed offsets', 'generate_all_params_for_grid': 'generate all parameter combinations from a hyperparameter grid dictionary merged with default values', 'xpid_from_params': 'generate a unique experiment ID string from training parameters including environment, runner, and model info', 'get_wandb_config': 'read wandb base URL and API key from a local config/wandb.json file', 'run_make_cmd_cli': 'run the CLI to generate training or eval commands from a JSON config grid file with optional W&B integration'}
```

## File: facebookresearch_minimax/src/minimax/config/xpid_maker.py

Prompts

```
['generate training shell commands from a parameter dict with configurable trial count and seed offsets', 'generate all parameter combinations from a hyperparameter grid dictionary merged with default values', 'generate a unique experiment ID string from training parameters including environment, runner, and model info', 'read wandb base URL and API key from a local config/wandb.json file', 'run the CLI to generate training or eval commands from a JSON config grid file with optional W&B integration', 'get the experiment runner info string from a config object using the train_runner handler', 'get the environment info string from a config object based on the env_name and train_runner', 'get the model architecture info string for a given role from a config object', 'get the algorithm info string for a given role using the agent_rl_algo handler', 'extract the base role name by removing _tch or _st suffixes from a role string']
```

Usage

```
{'get_runner_info': 'get the experiment runner info string from a config object using the train_runner handler', 'get_env_info': 'get the environment info string from a config object based on the env_name and train_runner', 'get_model_info': 'get the model architecture info string for a given role from a config object', 'get_algo_info': 'get the algorithm info string for a given role using the agent_rl_algo handler', 'get_base_role': 'extract the base role name by removing _tch or _st suffixes from a role string'}
```

