# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/environ.py

Prompts

```
['test the temp_set_env context manager to temporarily override environment variables', 'test the envs.SGLANG_TEST_RETRACT.override context manager to temporarily override an env var value', 'test the Envs descriptor get, set, clear, and is_set methods for reading and writing environment variables', 'test the EnvBool, EnvInt, EnvFloat, EnvStr, and EnvTuple descriptor types for parsing environment values', 'test the global envs singleton instance that provides typed access to all SGLANG environment variables', 'create ServerArgs instance from command line arguments for sglang serve', 'run prepare_server_args to parse CLI argv list into a ServerArgs dataclass', 'build PortArgs dataclass with IPC names and NCCL port for SGLang inter-process communication', 'test ServerArgs.check_server_args validates parallel size and LoRA constraints', 'summarize auto_choose_speculative_params returns (num_steps, topk, num_draft_tokens) for a model architecture', 'build a ConfigArgumentMerger instance with an argparse parser to merge YAML config files with CLI arguments', 'create a merged argument list by merging YAML config values with command-line arguments for precedence', 'test extracting the config file path from a list of command-line arguments', 'refactor parsing a YAML configuration file into a dictionary with validation for empty or invalid files', 'review converting a configuration dictionary into a CLI argument list respecting store_true actions']
```

Usage

```
{'test_temp_set_env': 'test the temp_set_env context manager to temporarily override environment variables', 'test_env_override': 'test the envs.SGLANG_TEST_RETRACT.override context manager to temporarily override an env var value', 'test_env_get_set_clear': 'test the Envs descriptor get, set, clear, and is_set methods for reading and writing environment variables', 'test_env_type_parsing': 'test the EnvBool, EnvInt, EnvFloat, EnvStr, and EnvTuple descriptor types for parsing environment values', 'test_envs_instance': 'test the global envs singleton instance that provides typed access to all SGLANG environment variables'}
```

## File: sgl-project_sglang/python/sglang/srt/server_args.py

Prompts

```
['test the temp_set_env context manager to temporarily override environment variables', 'test the envs.SGLANG_TEST_RETRACT.override context manager to temporarily override an env var value', 'test the Envs descriptor get, set, clear, and is_set methods for reading and writing environment variables', 'test the EnvBool, EnvInt, EnvFloat, EnvStr, and EnvTuple descriptor types for parsing environment values', 'test the global envs singleton instance that provides typed access to all SGLANG environment variables', 'create ServerArgs instance from command line arguments for sglang serve', 'run prepare_server_args to parse CLI argv list into a ServerArgs dataclass', 'build PortArgs dataclass with IPC names and NCCL port for SGLang inter-process communication', 'test ServerArgs.check_server_args validates parallel size and LoRA constraints', 'summarize auto_choose_speculative_params returns (num_steps, topk, num_draft_tokens) for a model architecture', 'build a ConfigArgumentMerger instance with an argparse parser to merge YAML config files with CLI arguments', 'create a merged argument list by merging YAML config values with command-line arguments for precedence', 'test extracting the config file path from a list of command-line arguments', 'refactor parsing a YAML configuration file into a dictionary with validation for empty or invalid files', 'review converting a configuration dictionary into a CLI argument list respecting store_true actions']
```

Usage

```
{'create_server_args_from_cli': 'create ServerArgs instance from command line arguments for sglang serve', 'run_prepare_server_args': 'run prepare_server_args to parse CLI argv list into a ServerArgs dataclass', 'build_port_args': 'build PortArgs dataclass with IPC names and NCCL port for SGLang inter-process communication', 'test_server_args_validation': 'test ServerArgs.check_server_args validates parallel size and LoRA constraints', 'summarize_auto_choose_speculative_params': 'summarize auto_choose_speculative_params returns (num_steps, topk, num_draft_tokens) for a model architecture'}
```

## File: sgl-project_sglang/python/sglang/srt/server_args_config_parser.py

Prompts

```
['test the temp_set_env context manager to temporarily override environment variables', 'test the envs.SGLANG_TEST_RETRACT.override context manager to temporarily override an env var value', 'test the Envs descriptor get, set, clear, and is_set methods for reading and writing environment variables', 'test the EnvBool, EnvInt, EnvFloat, EnvStr, and EnvTuple descriptor types for parsing environment values', 'test the global envs singleton instance that provides typed access to all SGLANG environment variables', 'create ServerArgs instance from command line arguments for sglang serve', 'run prepare_server_args to parse CLI argv list into a ServerArgs dataclass', 'build PortArgs dataclass with IPC names and NCCL port for SGLang inter-process communication', 'test ServerArgs.check_server_args validates parallel size and LoRA constraints', 'summarize auto_choose_speculative_params returns (num_steps, topk, num_draft_tokens) for a model architecture', 'build a ConfigArgumentMerger instance with an argparse parser to merge YAML config files with CLI arguments', 'create a merged argument list by merging YAML config values with command-line arguments for precedence', 'test extracting the config file path from a list of command-line arguments', 'refactor parsing a YAML configuration file into a dictionary with validation for empty or invalid files', 'review converting a configuration dictionary into a CLI argument list respecting store_true actions']
```

Usage

```
{'build_config_argument_merger': 'build a ConfigArgumentMerger instance with an argparse parser to merge YAML config files with CLI arguments', 'create_merge_config_with_args': 'create a merged argument list by merging YAML config values with command-line arguments for precedence', 'test_extract_config_file_path': 'test extracting the config file path from a list of command-line arguments', 'refactor_parse_yaml_config': 'refactor parsing a YAML configuration file into a dictionary with validation for empty or invalid files', 'review_convert_config_to_args': 'review converting a configuration dictionary into a CLI argument list respecting store_true actions'}
```

