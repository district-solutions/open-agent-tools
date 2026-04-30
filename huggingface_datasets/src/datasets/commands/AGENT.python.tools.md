# Agent Python Tools

- repo: huggingface/datasets
- repo_uri: https://github.com/huggingface/datasets

## File: huggingface_datasets/src/datasets/commands/datasets_cli.py

Prompts

```
['run the HuggingFace datasets CLI tool with a subcommand and optional arguments', 'run the environment subcommand to display the current datasets environment information', 'run the test subcommand to execute dataset tests from the CLI', 'run the delete-from-hub subcommand to delete a dataset from the HuggingFace Hub', 'parse unknown CLI arguments into a key-value dictionary by alternating pairs', 'register the delete_from_hub subcommand with an argparse parser for CLI usage', 'create a DeleteFromHubCommand instance with dataset_id, config_name, token, and revision', 'call _command_factory with argparse args to instantiate a DeleteFromHubCommand', 'delete a specific dataset config from the Hugging Face Hub using the delete_from_hub function', 'register the env subcommand with an ArgumentParser to print relevant system environment info', 'use format_dict to convert a dictionary into a newline-separated bullet-point list string', 'use info_command_factory to create an EnvironmentCommand instance for the datasets CLI', 'review the EnvironmentCommand class and its run method that collects library version info', 'test all dataset configurations by running TestCommand with the all_configs flag enabled', 'run the TestCommand with force_redownload to re-download the dataset from scratch', 'run the TestCommand with save_infos to generate a dataset card README.md file', 'run the TestCommand with clear_cache to remove cached files after each configuration test']
```

Usage

```
{'run_datasets_cli': 'run the HuggingFace datasets CLI tool with a subcommand and optional arguments', 'run_environment_command': 'run the environment subcommand to display the current datasets environment information', 'run_test_command': 'run the test subcommand to execute dataset tests from the CLI', 'run_delete_from_hub_command': 'run the delete-from-hub subcommand to delete a dataset from the HuggingFace Hub', 'parse_unknown_args': 'parse unknown CLI arguments into a key-value dictionary by alternating pairs'}
```

## File: huggingface_datasets/src/datasets/commands/delete_from_hub.py

Prompts

```
['run the HuggingFace datasets CLI tool with a subcommand and optional arguments', 'run the environment subcommand to display the current datasets environment information', 'run the test subcommand to execute dataset tests from the CLI', 'run the delete-from-hub subcommand to delete a dataset from the HuggingFace Hub', 'parse unknown CLI arguments into a key-value dictionary by alternating pairs', 'register the delete_from_hub subcommand with an argparse parser for CLI usage', 'create a DeleteFromHubCommand instance with dataset_id, config_name, token, and revision', 'call _command_factory with argparse args to instantiate a DeleteFromHubCommand', 'delete a specific dataset config from the Hugging Face Hub using the delete_from_hub function', 'register the env subcommand with an ArgumentParser to print relevant system environment info', 'use format_dict to convert a dictionary into a newline-separated bullet-point list string', 'use info_command_factory to create an EnvironmentCommand instance for the datasets CLI', 'review the EnvironmentCommand class and its run method that collects library version info', 'test all dataset configurations by running TestCommand with the all_configs flag enabled', 'run the TestCommand with force_redownload to re-download the dataset from scratch', 'run the TestCommand with save_infos to generate a dataset card README.md file', 'run the TestCommand with clear_cache to remove cached files after each configuration test']
```

Usage

```
{'run_delete_from_hub_command': 'run the DeleteFromHubCommand to delete a dataset config from the Hugging Face Hub', 'register_delete_from_hub_subcommand': 'register the delete_from_hub subcommand with an argparse parser for CLI usage', 'create_delete_from_hub_command': 'create a DeleteFromHubCommand instance with dataset_id, config_name, token, and revision', 'call_command_factory': 'call _command_factory with argparse args to instantiate a DeleteFromHubCommand', 'delete_dataset_config_from_hub': 'delete a specific dataset config from the Hugging Face Hub using the delete_from_hub function'}
```

## File: huggingface_datasets/src/datasets/commands/env.py

Prompts

```
['run the HuggingFace datasets CLI tool with a subcommand and optional arguments', 'run the environment subcommand to display the current datasets environment information', 'run the test subcommand to execute dataset tests from the CLI', 'run the delete-from-hub subcommand to delete a dataset from the HuggingFace Hub', 'parse unknown CLI arguments into a key-value dictionary by alternating pairs', 'register the delete_from_hub subcommand with an argparse parser for CLI usage', 'create a DeleteFromHubCommand instance with dataset_id, config_name, token, and revision', 'call _command_factory with argparse args to instantiate a DeleteFromHubCommand', 'delete a specific dataset config from the Hugging Face Hub using the delete_from_hub function', 'register the env subcommand with an ArgumentParser to print relevant system environment info', 'use format_dict to convert a dictionary into a newline-separated bullet-point list string', 'use info_command_factory to create an EnvironmentCommand instance for the datasets CLI', 'review the EnvironmentCommand class and its run method that collects library version info', 'test all dataset configurations by running TestCommand with the all_configs flag enabled', 'run the TestCommand with force_redownload to re-download the dataset from scratch', 'run the TestCommand with save_infos to generate a dataset card README.md file', 'run the TestCommand with clear_cache to remove cached files after each configuration test']
```

Usage

```
{'run_environment_command': 'run the EnvironmentCommand to print system environment info including datasets version and platform details', 'register_env_subcommand': 'register the env subcommand with an ArgumentParser to print relevant system environment info', 'format_dict_to_bullets': 'use format_dict to convert a dictionary into a newline-separated bullet-point list string', 'create_env_command_via_factory': 'use info_command_factory to create an EnvironmentCommand instance for the datasets CLI', 'review_environment_command_class': 'review the EnvironmentCommand class and its run method that collects library version info'}
```

## File: huggingface_datasets/src/datasets/commands/test.py

Prompts

```
['run the HuggingFace datasets CLI tool with a subcommand and optional arguments', 'run the environment subcommand to display the current datasets environment information', 'run the test subcommand to execute dataset tests from the CLI', 'run the delete-from-hub subcommand to delete a dataset from the HuggingFace Hub', 'parse unknown CLI arguments into a key-value dictionary by alternating pairs', 'register the delete_from_hub subcommand with an argparse parser for CLI usage', 'create a DeleteFromHubCommand instance with dataset_id, config_name, token, and revision', 'call _command_factory with argparse args to instantiate a DeleteFromHubCommand', 'delete a specific dataset config from the Hugging Face Hub using the delete_from_hub function', 'register the env subcommand with an ArgumentParser to print relevant system environment info', 'use format_dict to convert a dictionary into a newline-separated bullet-point list string', 'use info_command_factory to create an EnvironmentCommand instance for the datasets CLI', 'review the EnvironmentCommand class and its run method that collects library version info', 'test all dataset configurations by running TestCommand with the all_configs flag enabled', 'run the TestCommand with force_redownload to re-download the dataset from scratch', 'run the TestCommand with save_infos to generate a dataset card README.md file', 'run the TestCommand with clear_cache to remove cached files after each configuration test']
```

Usage

```
{'run_test_command': 'run the TestCommand to test dataset loading with a specified cache directory and data directory', 'test_all_configs': 'test all dataset configurations by running TestCommand with the all_configs flag enabled', 'test_with_force_redownload': 'run the TestCommand with force_redownload to re-download the dataset from scratch', 'test_with_save_infos': 'run the TestCommand with save_infos to generate a dataset card README.md file', 'test_with_clear_cache': 'run the TestCommand with clear_cache to remove cached files after each configuration test'}
```

