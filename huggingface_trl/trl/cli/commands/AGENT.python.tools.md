# Agent Python Tools

- repo: huggingface/trl
- repo_uri: https://github.com/huggingface/trl.git

## File: huggingface_trl/trl/cli/commands/base.py

Prompts

```
['create a Command subclass with register and run methods for a TRL CLI subcommand', 'build a CommandContext with argv list to pass to CLI command run methods', 'run a Command subclass by calling register to add a subparser and run with args and context', 'test the CommandContext.argv_after method to extract tokens after a subcommand token', 'review the Command base class for abstract register and run methods in TRL CLI', 'run the CLI env command to print TRL environment information', "create an EnvCommand instance that registers an 'env' CLI subparser", 'review the EnvCommand class and its run method that prints environment info', 'test the EnvCommand.run method with a Namespace and CommandContext', 'summarize the print_env function from trl.scripts.env that prints environment details', 'run the TRL CLI skills command to manage agent skills', 'register the skills CLI subcommand with an argparse subparser', 'create a SkillsCommand instance that manages TRL agent skills via CLI', 'run a registered skills subcommand function from argparse args', 'print help text for the TRL CLI skills command', 'run the TrainingCommand CLI to launch a training script with accelerate', 'create a TrainingCommand instance for a named training subcommand like dpo', 'register a TrainingCommand with argparse subparsers', 'build training script arguments by parsing CLI args and accelerate config', 'subtract an ordered subsequence from a list of strings', 'run the vLLM serve CLI command to serve a TRL model with vLLM', 'create a VllmServeCommand instance and register it with argparse subparsers', 'build an argparse parser for vLLM serve script arguments using TrlParser', 'test the WeightSyncWorkerExtension for synchronizing model weights between client and server workers', 'review the vllm_serve main function that starts the uvicorn server with weight sync endpoints']
```

Usage

```
{'create_command_subclass': 'create a Command subclass with register and run methods for a TRL CLI subcommand', 'build_command_context': 'build a CommandContext with argv list to pass to CLI command run methods', 'run_command_execute': 'run a Command subclass by calling register to add a subparser and run with args and context', 'test_command_context_argv_after': 'test the CommandContext.argv_after method to extract tokens after a subcommand token', 'review_command_base_class': 'review the Command base class for abstract register and run methods in TRL CLI'}
```

## File: huggingface_trl/trl/cli/commands/env.py

Prompts

```
['create a Command subclass with register and run methods for a TRL CLI subcommand', 'build a CommandContext with argv list to pass to CLI command run methods', 'run a Command subclass by calling register to add a subparser and run with args and context', 'test the CommandContext.argv_after method to extract tokens after a subcommand token', 'review the Command base class for abstract register and run methods in TRL CLI', 'run the CLI env command to print TRL environment information', "create an EnvCommand instance that registers an 'env' CLI subparser", 'review the EnvCommand class and its run method that prints environment info', 'test the EnvCommand.run method with a Namespace and CommandContext', 'summarize the print_env function from trl.scripts.env that prints environment details', 'run the TRL CLI skills command to manage agent skills', 'register the skills CLI subcommand with an argparse subparser', 'create a SkillsCommand instance that manages TRL agent skills via CLI', 'run a registered skills subcommand function from argparse args', 'print help text for the TRL CLI skills command', 'run the TrainingCommand CLI to launch a training script with accelerate', 'create a TrainingCommand instance for a named training subcommand like dpo', 'register a TrainingCommand with argparse subparsers', 'build training script arguments by parsing CLI args and accelerate config', 'subtract an ordered subsequence from a list of strings', 'run the vLLM serve CLI command to serve a TRL model with vLLM', 'create a VllmServeCommand instance and register it with argparse subparsers', 'build an argparse parser for vLLM serve script arguments using TrlParser', 'test the WeightSyncWorkerExtension for synchronizing model weights between client and server workers', 'review the vllm_serve main function that starts the uvicorn server with weight sync endpoints']
```

Usage

```
{'run_env_command': 'run the CLI env command to print TRL environment information', 'create_env_command': "create an EnvCommand instance that registers an 'env' CLI subparser", 'review_env_command': 'review the EnvCommand class and its run method that prints environment info', 'test_env_command': 'test the EnvCommand.run method with a Namespace and CommandContext', 'summarize_print_env': 'summarize the print_env function from trl.scripts.env that prints environment details'}
```

## File: huggingface_trl/trl/cli/commands/skills.py

Prompts

```
['create a Command subclass with register and run methods for a TRL CLI subcommand', 'build a CommandContext with argv list to pass to CLI command run methods', 'run a Command subclass by calling register to add a subparser and run with args and context', 'test the CommandContext.argv_after method to extract tokens after a subcommand token', 'review the Command base class for abstract register and run methods in TRL CLI', 'run the CLI env command to print TRL environment information', "create an EnvCommand instance that registers an 'env' CLI subparser", 'review the EnvCommand class and its run method that prints environment info', 'test the EnvCommand.run method with a Namespace and CommandContext', 'summarize the print_env function from trl.scripts.env that prints environment details', 'run the TRL CLI skills command to manage agent skills', 'register the skills CLI subcommand with an argparse subparser', 'create a SkillsCommand instance that manages TRL agent skills via CLI', 'run a registered skills subcommand function from argparse args', 'print help text for the TRL CLI skills command', 'run the TrainingCommand CLI to launch a training script with accelerate', 'create a TrainingCommand instance for a named training subcommand like dpo', 'register a TrainingCommand with argparse subparsers', 'build training script arguments by parsing CLI args and accelerate config', 'subtract an ordered subsequence from a list of strings', 'run the vLLM serve CLI command to serve a TRL model with vLLM', 'create a VllmServeCommand instance and register it with argparse subparsers', 'build an argparse parser for vLLM serve script arguments using TrlParser', 'test the WeightSyncWorkerExtension for synchronizing model weights between client and server workers', 'review the vllm_serve main function that starts the uvicorn server with weight sync endpoints']
```

Usage

```
{'run_skills_cli': 'run the TRL CLI skills command to manage agent skills', 'register_skills_subcommands': 'register the skills CLI subcommand with an argparse subparser', 'create_skills_command': 'create a SkillsCommand instance that manages TRL agent skills via CLI', 'run_skills_subcommand': 'run a registered skills subcommand function from argparse args', 'print_skills_help': 'print help text for the TRL CLI skills command'}
```

## File: huggingface_trl/trl/cli/commands/training.py

Prompts

```
['create a Command subclass with register and run methods for a TRL CLI subcommand', 'build a CommandContext with argv list to pass to CLI command run methods', 'run a Command subclass by calling register to add a subparser and run with args and context', 'test the CommandContext.argv_after method to extract tokens after a subcommand token', 'review the Command base class for abstract register and run methods in TRL CLI', 'run the CLI env command to print TRL environment information', "create an EnvCommand instance that registers an 'env' CLI subparser", 'review the EnvCommand class and its run method that prints environment info', 'test the EnvCommand.run method with a Namespace and CommandContext', 'summarize the print_env function from trl.scripts.env that prints environment details', 'run the TRL CLI skills command to manage agent skills', 'register the skills CLI subcommand with an argparse subparser', 'create a SkillsCommand instance that manages TRL agent skills via CLI', 'run a registered skills subcommand function from argparse args', 'print help text for the TRL CLI skills command', 'run the TrainingCommand CLI to launch a training script with accelerate', 'create a TrainingCommand instance for a named training subcommand like dpo', 'register a TrainingCommand with argparse subparsers', 'build training script arguments by parsing CLI args and accelerate config', 'subtract an ordered subsequence from a list of strings', 'run the vLLM serve CLI command to serve a TRL model with vLLM', 'create a VllmServeCommand instance and register it with argparse subparsers', 'build an argparse parser for vLLM serve script arguments using TrlParser', 'test the WeightSyncWorkerExtension for synchronizing model weights between client and server workers', 'review the vllm_serve main function that starts the uvicorn server with weight sync endpoints']
```

Usage

```
{'run_training_command': 'run the TrainingCommand CLI to launch a training script with accelerate', 'create_training_command': 'create a TrainingCommand instance for a named training subcommand like dpo', 'register_training_command': 'register a TrainingCommand with argparse subparsers', 'build_training_args': 'build training script arguments by parsing CLI args and accelerate config', 'subtract_subsequence': 'subtract an ordered subsequence from a list of strings'}
```

## File: huggingface_trl/trl/cli/commands/vllm_serve.py

Prompts

```
['create a Command subclass with register and run methods for a TRL CLI subcommand', 'build a CommandContext with argv list to pass to CLI command run methods', 'run a Command subclass by calling register to add a subparser and run with args and context', 'test the CommandContext.argv_after method to extract tokens after a subcommand token', 'review the Command base class for abstract register and run methods in TRL CLI', 'run the CLI env command to print TRL environment information', "create an EnvCommand instance that registers an 'env' CLI subparser", 'review the EnvCommand class and its run method that prints environment info', 'test the EnvCommand.run method with a Namespace and CommandContext', 'summarize the print_env function from trl.scripts.env that prints environment details', 'run the TRL CLI skills command to manage agent skills', 'register the skills CLI subcommand with an argparse subparser', 'create a SkillsCommand instance that manages TRL agent skills via CLI', 'run a registered skills subcommand function from argparse args', 'print help text for the TRL CLI skills command', 'run the TrainingCommand CLI to launch a training script with accelerate', 'create a TrainingCommand instance for a named training subcommand like dpo', 'register a TrainingCommand with argparse subparsers', 'build training script arguments by parsing CLI args and accelerate config', 'subtract an ordered subsequence from a list of strings', 'run the vLLM serve CLI command to serve a TRL model with vLLM', 'create a VllmServeCommand instance and register it with argparse subparsers', 'build an argparse parser for vLLM serve script arguments using TrlParser', 'test the WeightSyncWorkerExtension for synchronizing model weights between client and server workers', 'review the vllm_serve main function that starts the uvicorn server with weight sync endpoints']
```

Usage

```
{'run_vllm_serve_cli': 'run the vLLM serve CLI command to serve a TRL model with vLLM', 'create_vllm_serve_command': 'create a VllmServeCommand instance and register it with argparse subparsers', 'build_vllm_serve_parser': 'build an argparse parser for vLLM serve script arguments using TrlParser', 'test_weight_sync_extension': 'test the WeightSyncWorkerExtension for synchronizing model weights between client and server workers', 'review_vllm_serve_main': 'review the vllm_serve main function that starts the uvicorn server with weight sync endpoints'}
```

