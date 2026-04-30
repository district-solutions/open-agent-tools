# Agent Python Tools

- repo: huggingface/trl
- repo_uri: https://github.com/huggingface/trl.git

## File: huggingface_trl/trl/cli/accelerate_config.py

Prompts

```
['resolve the --accelerate_config CLI argument into an accelerate --config_file path', 'test the resolve_accelerate_config_argument function with a filesystem path argument', 'test the resolve_accelerate_config_argument function with a bundled trl config name', 'test the resolve_accelerate_config_argument function raises ValueError for invalid config', 'test the resolve_accelerate_config_argument function returns args unchanged when no flag is present', 'run the launch_training_script function to launch a TRL training script through accelerate launch', 'test the launch_training_script function with script_name, launch_args, and training_script_args', 'refactor the launch_training_script function to support custom launch_command_fn and launch_parser_fn', 'review the launch_training_script function that resolves training scripts from trl.scripts package', 'summarize the launch_training_script function that parses accelerate launch arguments and executes training']
```

Usage

```
{'resolve_accelerate_config_argument': 'resolve the --accelerate_config CLI argument into an accelerate --config_file path', 'test_resolve_accelerate_config_argument': 'test the resolve_accelerate_config_argument function with a filesystem path argument', 'test_resolve_accelerate_config_bundled': 'test the resolve_accelerate_config_argument function with a bundled trl config name', 'test_resolve_accelerate_config_missing': 'test the resolve_accelerate_config_argument function raises ValueError for invalid config', 'test_resolve_accelerate_config_no_flag': 'test the resolve_accelerate_config_argument function returns args unchanged when no flag is present'}
```

## File: huggingface_trl/trl/cli/accelerate_launcher.py

Prompts

```
['resolve the --accelerate_config CLI argument into an accelerate --config_file path', 'test the resolve_accelerate_config_argument function with a filesystem path argument', 'test the resolve_accelerate_config_argument function with a bundled trl config name', 'test the resolve_accelerate_config_argument function raises ValueError for invalid config', 'test the resolve_accelerate_config_argument function returns args unchanged when no flag is present', 'run the launch_training_script function to launch a TRL training script through accelerate launch', 'test the launch_training_script function with script_name, launch_args, and training_script_args', 'refactor the launch_training_script function to support custom launch_command_fn and launch_parser_fn', 'review the launch_training_script function that resolves training scripts from trl.scripts package', 'summarize the launch_training_script function that parses accelerate launch arguments and executes training']
```

Usage

```
{'run_launch_training_script': 'run the launch_training_script function to launch a TRL training script through accelerate launch', 'test_launch_training_script': 'test the launch_training_script function with script_name, launch_args, and training_script_args', 'refactor_launch_training_script': 'refactor the launch_training_script function to support custom launch_command_fn and launch_parser_fn', 'review_launch_training_script': 'review the launch_training_script function that resolves training scripts from trl.scripts package', 'summarize_launch_training_script': 'summarize the launch_training_script function that parses accelerate launch arguments and executes training'}
```

