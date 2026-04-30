# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/entrypoints/cli/cli_types.py

Prompts

```
['create a CLI subcommand class that extends CLISubcommand with cmd, validate, and subparser_init methods', 'build a CLI subcommand cmd method that executes the command with argparse.Namespace arguments', 'test the CLISubcommand validate method with argparse.Namespace arguments', 'review the CLISubcommand subparser_init method that initializes argparse subparsers', 'summarize the CLISubcommand base class for CLI subcommand registration', 'run the generate command to generate video content from a prompt using DiffGenerator', 'add CLI arguments for the generate subcommand including config, perf-dump-path, and output-file-path options', 'create a GenerateSubcommand instance that registers the generate subcommand with argparse and validates arguments', 'dump performance metrics and memory snapshots to a JSON file after generation completes', 'apply output file path override to split a single output_file_path into output_path and output_file_name', 'run the sglang-diffusion CLI generate subcommand to produce multimodal content', 'run the sglang-diffusion CLI serve subcommand to start a model serving server', 'build a CLI subcommand by implementing the CLISubcommand interface', 'test the FlexibleArgumentParser argument parsing and subcommand dispatch logic', 'review the main entry point function that initializes and dispatches CLI subcommands', 'run the serve command to launch the sglang diffusion server with CLI arguments', 'build a serve subcommand that registers with argparse for launching the sglang diffusion server', 'test the serve subcommand validation to ensure config file paths exist before launching', 'create an argparse subparser for the serve command with --config and ServerArgs options', 'summarize the execute_serve_cmd function that initializes ServerArgs and dispatches the server launch', 'run launch_distributed to start a distributed GPU inference job with a specified number of GPUs', 'review the RaiseNotImplementedAction argparse action class that raises NotImplementedError for unimplemented options']
```

Usage

```
{'create_CLISubcommand': 'create a CLI subcommand class that extends CLISubcommand with cmd, validate, and subparser_init methods', 'build_CLISubcommand_cmd': 'build a CLI subcommand cmd method that executes the command with argparse.Namespace arguments', 'test_CLISubcommand_validate': 'test the CLISubcommand validate method with argparse.Namespace arguments', 'review_CLISubcommand_subparser_init': 'review the CLISubcommand subparser_init method that initializes argparse subparsers', 'summarize_CLISubcommand': 'summarize the CLISubcommand base class for CLI subcommand registration'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/entrypoints/cli/generate.py

Prompts

```
['create a CLI subcommand class that extends CLISubcommand with cmd, validate, and subparser_init methods', 'build a CLI subcommand cmd method that executes the command with argparse.Namespace arguments', 'test the CLISubcommand validate method with argparse.Namespace arguments', 'review the CLISubcommand subparser_init method that initializes argparse subparsers', 'summarize the CLISubcommand base class for CLI subcommand registration', 'run the generate command to generate video content from a prompt using DiffGenerator', 'add CLI arguments for the generate subcommand including config, perf-dump-path, and output-file-path options', 'create a GenerateSubcommand instance that registers the generate subcommand with argparse and validates arguments', 'dump performance metrics and memory snapshots to a JSON file after generation completes', 'apply output file path override to split a single output_file_path into output_path and output_file_name', 'run the sglang-diffusion CLI generate subcommand to produce multimodal content', 'run the sglang-diffusion CLI serve subcommand to start a model serving server', 'build a CLI subcommand by implementing the CLISubcommand interface', 'test the FlexibleArgumentParser argument parsing and subcommand dispatch logic', 'review the main entry point function that initializes and dispatches CLI subcommands', 'run the serve command to launch the sglang diffusion server with CLI arguments', 'build a serve subcommand that registers with argparse for launching the sglang diffusion server', 'test the serve subcommand validation to ensure config file paths exist before launching', 'create an argparse subparser for the serve command with --config and ServerArgs options', 'summarize the execute_serve_cmd function that initializes ServerArgs and dispatches the server launch', 'run launch_distributed to start a distributed GPU inference job with a specified number of GPUs', 'review the RaiseNotImplementedAction argparse action class that raises NotImplementedError for unimplemented options']
```

Usage

```
{'run_generate_cmd': 'run the generate command to generate video content from a prompt using DiffGenerator', 'add_multimodal_gen_generate_args': 'add CLI arguments for the generate subcommand including config, perf-dump-path, and output-file-path options', 'create_gsd_generate_subcommand': 'create a GenerateSubcommand instance that registers the generate subcommand with argparse and validates arguments', 'dump_performance_metrics': 'dump performance metrics and memory snapshots to a JSON file after generation completes', 'apply_output_file_path_override': 'apply output file path override to split a single output_file_path into output_path and output_file_name'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/entrypoints/cli/main.py

Prompts

```
['create a CLI subcommand class that extends CLISubcommand with cmd, validate, and subparser_init methods', 'build a CLI subcommand cmd method that executes the command with argparse.Namespace arguments', 'test the CLISubcommand validate method with argparse.Namespace arguments', 'review the CLISubcommand subparser_init method that initializes argparse subparsers', 'summarize the CLISubcommand base class for CLI subcommand registration', 'run the generate command to generate video content from a prompt using DiffGenerator', 'add CLI arguments for the generate subcommand including config, perf-dump-path, and output-file-path options', 'create a GenerateSubcommand instance that registers the generate subcommand with argparse and validates arguments', 'dump performance metrics and memory snapshots to a JSON file after generation completes', 'apply output file path override to split a single output_file_path into output_path and output_file_name', 'run the sglang-diffusion CLI generate subcommand to produce multimodal content', 'run the sglang-diffusion CLI serve subcommand to start a model serving server', 'build a CLI subcommand by implementing the CLISubcommand interface', 'test the FlexibleArgumentParser argument parsing and subcommand dispatch logic', 'review the main entry point function that initializes and dispatches CLI subcommands', 'run the serve command to launch the sglang diffusion server with CLI arguments', 'build a serve subcommand that registers with argparse for launching the sglang diffusion server', 'test the serve subcommand validation to ensure config file paths exist before launching', 'create an argparse subparser for the serve command with --config and ServerArgs options', 'summarize the execute_serve_cmd function that initializes ServerArgs and dispatches the server launch', 'run launch_distributed to start a distributed GPU inference job with a specified number of GPUs', 'review the RaiseNotImplementedAction argparse action class that raises NotImplementedError for unimplemented options']
```

Usage

```
{'run_cli_generate': 'run the sglang-diffusion CLI generate subcommand to produce multimodal content', 'run_cli_serve': 'run the sglang-diffusion CLI serve subcommand to start a model serving server', 'build_cli_subcommand': 'build a CLI subcommand by implementing the CLISubcommand interface', 'test_cli_parsing': 'test the FlexibleArgumentParser argument parsing and subcommand dispatch logic', 'review_cli_main': 'review the main entry point function that initializes and dispatches CLI subcommands'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/entrypoints/cli/serve.py

Prompts

```
['create a CLI subcommand class that extends CLISubcommand with cmd, validate, and subparser_init methods', 'build a CLI subcommand cmd method that executes the command with argparse.Namespace arguments', 'test the CLISubcommand validate method with argparse.Namespace arguments', 'review the CLISubcommand subparser_init method that initializes argparse subparsers', 'summarize the CLISubcommand base class for CLI subcommand registration', 'run the generate command to generate video content from a prompt using DiffGenerator', 'add CLI arguments for the generate subcommand including config, perf-dump-path, and output-file-path options', 'create a GenerateSubcommand instance that registers the generate subcommand with argparse and validates arguments', 'dump performance metrics and memory snapshots to a JSON file after generation completes', 'apply output file path override to split a single output_file_path into output_path and output_file_name', 'run the sglang-diffusion CLI generate subcommand to produce multimodal content', 'run the sglang-diffusion CLI serve subcommand to start a model serving server', 'build a CLI subcommand by implementing the CLISubcommand interface', 'test the FlexibleArgumentParser argument parsing and subcommand dispatch logic', 'review the main entry point function that initializes and dispatches CLI subcommands', 'run the serve command to launch the sglang diffusion server with CLI arguments', 'build a serve subcommand that registers with argparse for launching the sglang diffusion server', 'test the serve subcommand validation to ensure config file paths exist before launching', 'create an argparse subparser for the serve command with --config and ServerArgs options', 'summarize the execute_serve_cmd function that initializes ServerArgs and dispatches the server launch', 'run launch_distributed to start a distributed GPU inference job with a specified number of GPUs', 'review the RaiseNotImplementedAction argparse action class that raises NotImplementedError for unimplemented options']
```

Usage

```
{'run_serve_command': 'run the serve command to launch the sglang diffusion server with CLI arguments', 'build_serve_subcommand': 'build a serve subcommand that registers with argparse for launching the sglang diffusion server', 'test_validate_serve_args': 'test the serve subcommand validation to ensure config file paths exist before launching', 'create_serve_parser': 'create an argparse subparser for the serve command with --config and ServerArgs options', 'summarize_execute_serve_cmd': 'summarize the execute_serve_cmd function that initializes ServerArgs and dispatches the server launch'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/entrypoints/cli/utils.py

Prompts

```
['create a CLI subcommand class that extends CLISubcommand with cmd, validate, and subparser_init methods', 'build a CLI subcommand cmd method that executes the command with argparse.Namespace arguments', 'test the CLISubcommand validate method with argparse.Namespace arguments', 'review the CLISubcommand subparser_init method that initializes argparse subparsers', 'summarize the CLISubcommand base class for CLI subcommand registration', 'run the generate command to generate video content from a prompt using DiffGenerator', 'add CLI arguments for the generate subcommand including config, perf-dump-path, and output-file-path options', 'create a GenerateSubcommand instance that registers the generate subcommand with argparse and validates arguments', 'dump performance metrics and memory snapshots to a JSON file after generation completes', 'apply output file path override to split a single output_file_path into output_path and output_file_name', 'run the sglang-diffusion CLI generate subcommand to produce multimodal content', 'run the sglang-diffusion CLI serve subcommand to start a model serving server', 'build a CLI subcommand by implementing the CLISubcommand interface', 'test the FlexibleArgumentParser argument parsing and subcommand dispatch logic', 'review the main entry point function that initializes and dispatches CLI subcommands', 'run the serve command to launch the sglang diffusion server with CLI arguments', 'build a serve subcommand that registers with argparse for launching the sglang diffusion server', 'test the serve subcommand validation to ensure config file paths exist before launching', 'create an argparse subparser for the serve command with --config and ServerArgs options', 'summarize the execute_serve_cmd function that initializes ServerArgs and dispatches the server launch', 'run launch_distributed to start a distributed GPU inference job with a specified number of GPUs', 'review the RaiseNotImplementedAction argparse action class that raises NotImplementedError for unimplemented options']
```

Usage

```
{'run_launch_distributed': 'run launch_distributed to start a distributed GPU inference job with a specified number of GPUs', 'review_RaiseNotImplementedAction': 'review the RaiseNotImplementedAction argparse action class that raises NotImplementedError for unimplemented options'}
```

