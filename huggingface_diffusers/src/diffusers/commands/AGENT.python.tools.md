# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/commands/custom_blocks.py

Prompts

```
['run the custom_blocks CLI command to save a custom diffusers block module to the current directory', 'register the custom_blocks subcommand with argparse to accept block module name and class name arguments', 'parse a Python file with AST to find all classes inheriting from ModularPipelineBlocks', 'select a specific custom block class from a list of candidate classes by name', 'create an automap dictionary mapping a parent class to its child module and class name', 'run the EnvironmentCommand to collect and display system environment information for diffusers', 'register the env subcommand parser for the diffusers CLI argument parser', 'collect environment info including PyTorch, Flax, Jax, and accelerator versions into a dictionary', 'format a dictionary into a readable string with key-value pairs separated by newlines', 'detect GPU accelerator info using nvidia-smi on Linux or system_profiler on macOS', 'run the diffusers CLI fp16_safetensors command to convert a checkpoint repo to FP16 and safetensors format', 'create an FP16SafetensorsCommand instance with a checkpoint repo ID, fp16 flag, and safetensors flag', 'register the fp16_safetensors subcommand with argparse to accept ckpt_id, fp16, and use_safetensors arguments', 'convert a HuggingFace model checkpoint to FP16 precision and upload via a pull request', 'convert a HuggingFace model checkpoint to safetensors format and upload via a pull request']
```

Usage

```
{'run_custom_blocks_command': 'run the custom_blocks CLI command to save a custom diffusers block module to the current directory', 'register_custom_blocks_subcommand': 'register the custom_blocks subcommand with argparse to accept block module name and class name arguments', 'get_class_names_from_file': 'parse a Python file with AST to find all classes inheriting from ModularPipelineBlocks', 'choose_block_by_name': 'select a specific custom block class from a list of candidate classes by name', 'create_automap_for_block': 'create an automap dictionary mapping a parent class to its child module and class name'}
```

## File: huggingface_diffusers/src/diffusers/commands/env.py

Prompts

```
['run the custom_blocks CLI command to save a custom diffusers block module to the current directory', 'register the custom_blocks subcommand with argparse to accept block module name and class name arguments', 'parse a Python file with AST to find all classes inheriting from ModularPipelineBlocks', 'select a specific custom block class from a list of candidate classes by name', 'create an automap dictionary mapping a parent class to its child module and class name', 'run the EnvironmentCommand to collect and display system environment information for diffusers', 'register the env subcommand parser for the diffusers CLI argument parser', 'collect environment info including PyTorch, Flax, Jax, and accelerator versions into a dictionary', 'format a dictionary into a readable string with key-value pairs separated by newlines', 'detect GPU accelerator info using nvidia-smi on Linux or system_profiler on macOS', 'run the diffusers CLI fp16_safetensors command to convert a checkpoint repo to FP16 and safetensors format', 'create an FP16SafetensorsCommand instance with a checkpoint repo ID, fp16 flag, and safetensors flag', 'register the fp16_safetensors subcommand with argparse to accept ckpt_id, fp16, and use_safetensors arguments', 'convert a HuggingFace model checkpoint to FP16 precision and upload via a pull request', 'convert a HuggingFace model checkpoint to safetensors format and upload via a pull request']
```

Usage

```
{'run_environment_command': 'run the EnvironmentCommand to collect and display system environment information for diffusers', 'register_env_subcommand': 'register the env subcommand parser for the diffusers CLI argument parser', 'collect_environment_info': 'collect environment info including PyTorch, Flax, Jax, and accelerator versions into a dictionary', 'format_dict_to_string': 'format a dictionary into a readable string with key-value pairs separated by newlines', 'detect_gpu_accelerator': 'detect GPU accelerator info using nvidia-smi on Linux or system_profiler on macOS'}
```

## File: huggingface_diffusers/src/diffusers/commands/fp16_safetensors.py

Prompts

```
['run the custom_blocks CLI command to save a custom diffusers block module to the current directory', 'register the custom_blocks subcommand with argparse to accept block module name and class name arguments', 'parse a Python file with AST to find all classes inheriting from ModularPipelineBlocks', 'select a specific custom block class from a list of candidate classes by name', 'create an automap dictionary mapping a parent class to its child module and class name', 'run the EnvironmentCommand to collect and display system environment information for diffusers', 'register the env subcommand parser for the diffusers CLI argument parser', 'collect environment info including PyTorch, Flax, Jax, and accelerator versions into a dictionary', 'format a dictionary into a readable string with key-value pairs separated by newlines', 'detect GPU accelerator info using nvidia-smi on Linux or system_profiler on macOS', 'run the diffusers CLI fp16_safetensors command to convert a checkpoint repo to FP16 and safetensors format', 'create an FP16SafetensorsCommand instance with a checkpoint repo ID, fp16 flag, and safetensors flag', 'register the fp16_safetensors subcommand with argparse to accept ckpt_id, fp16, and use_safetensors arguments', 'convert a HuggingFace model checkpoint to FP16 precision and upload via a pull request', 'convert a HuggingFace model checkpoint to safetensors format and upload via a pull request']
```

Usage

```
{'run_fp16_safetensors_conversion': 'run the diffusers CLI fp16_safetensors command to convert a checkpoint repo to FP16 and safetensors format', 'create_fp16_safetensors_command': 'create an FP16SafetensorsCommand instance with a checkpoint repo ID, fp16 flag, and safetensors flag', 'register_fp16_safetensors_subcommand': 'register the fp16_safetensors subcommand with argparse to accept ckpt_id, fp16, and use_safetensors arguments', 'convert_checkpoint_to_fp16': 'convert a HuggingFace model checkpoint to FP16 precision and upload via a pull request', 'convert_checkpoint_to_safetensors': 'convert a HuggingFace model checkpoint to safetensors format and upload via a pull request'}
```

