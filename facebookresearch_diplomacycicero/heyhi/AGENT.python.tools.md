# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/heyhi/checkpoint_repo.py

Prompts

```
['create a copy of all repo code into a new tmp directory via checkpoint_repo.sh', 'get an existing checkpoint path from ckpt.link or create a new one for the output directory', 'add a --checkpoint CLI argument to an argparse parser for archiving code before slurm runs', 'handle the checkpoint CLI argument to create or skip checkpointing based on the provided value', 'check if a given path is a nontrivial checkpoint different from the project root directory', 'load a protobuf config from a .prototxt file and apply key=value scalar overrides', 'load a MetaCfg root config from a prototxt file with optional scalar overrides applied', 'save a protobuf config message to a .prototxt file using text format serialization', 'apply scalar key=value overrides to a frozen config and return a new frozen config', 'convert a protobuf config message to a Python dictionary with optional default values included', 'run the HeyHi main entrypoint to parse CLI args and launch an experiment with a config file', 'run an experiment locally or remotely by computing the task in the specified mode with config overrides', 'create an experiment directory path for a given project name using the HH_EXP_DIR environment variable', 'create the default experiment directory path for the diplomacy project using the hardcoded PROJECT_NAME constant', 'review the HeyHi entrypoint function that handles config loading, experiment status detection, and local or remote launch', 'setup logging with console and file handlers at configurable levels with custom labels', 'handle experiment directory status with modes like gentle_start, restart, start_continue, or dryrun', 'run a task function with a config file and optional overrides via local or slurm launcher', 'manage experiment directories by saving job IDs, checking status, and killing or pruning jobs', 'generate a unique experiment ID from a config path, overrides, and adhoc flag']
```

Usage

```
{'create_checkpoint_copy': 'create a copy of all repo code into a new tmp directory via checkpoint_repo.sh', 'get_or_create_checkpoint_for_out_dir': 'get an existing checkpoint path from ckpt.link or create a new one for the output directory', 'add_parser_checkpoint_arg': 'add a --checkpoint CLI argument to an argparse parser for archiving code before slurm runs', 'handle_parser_checkpoint_arg': 'handle the checkpoint CLI argument to create or skip checkpointing based on the provided value', 'check_nontrivial_checkpoint': 'check if a given path is a nontrivial checkpoint different from the project root directory'}
```

## File: facebookresearch_diplomacycicero/heyhi/conf.py

Prompts

```
['create a copy of all repo code into a new tmp directory via checkpoint_repo.sh', 'get an existing checkpoint path from ckpt.link or create a new one for the output directory', 'add a --checkpoint CLI argument to an argparse parser for archiving code before slurm runs', 'handle the checkpoint CLI argument to create or skip checkpointing based on the provided value', 'check if a given path is a nontrivial checkpoint different from the project root directory', 'load a protobuf config from a .prototxt file and apply key=value scalar overrides', 'load a MetaCfg root config from a prototxt file with optional scalar overrides applied', 'save a protobuf config message to a .prototxt file using text format serialization', 'apply scalar key=value overrides to a frozen config and return a new frozen config', 'convert a protobuf config message to a Python dictionary with optional default values included', 'run the HeyHi main entrypoint to parse CLI args and launch an experiment with a config file', 'run an experiment locally or remotely by computing the task in the specified mode with config overrides', 'create an experiment directory path for a given project name using the HH_EXP_DIR environment variable', 'create the default experiment directory path for the diplomacy project using the hardcoded PROJECT_NAME constant', 'review the HeyHi entrypoint function that handles config loading, experiment status detection, and local or remote launch', 'setup logging with console and file handlers at configurable levels with custom labels', 'handle experiment directory status with modes like gentle_start, restart, start_continue, or dryrun', 'run a task function with a config file and optional overrides via local or slurm launcher', 'manage experiment directories by saving job IDs, checking status, and killing or pruning jobs', 'generate a unique experiment ID from a config path, overrides, and adhoc flag']
```

Usage

```
{'load_config_with_overrides': 'load a protobuf config from a .prototxt file and apply key=value scalar overrides', 'load_root_config_meta_cfg': 'load a MetaCfg root config from a prototxt file with optional scalar overrides applied', 'save_config_to_prototxt': 'save a protobuf config message to a .prototxt file using text format serialization', 'conf_with_overrides_frozen': 'apply scalar key=value overrides to a frozen config and return a new frozen config', 'conf_to_dict_json': 'convert a protobuf config message to a Python dictionary with optional default values included'}
```

## File: facebookresearch_diplomacycicero/heyhi/run.py

Prompts

```
['create a copy of all repo code into a new tmp directory via checkpoint_repo.sh', 'get an existing checkpoint path from ckpt.link or create a new one for the output directory', 'add a --checkpoint CLI argument to an argparse parser for archiving code before slurm runs', 'handle the checkpoint CLI argument to create or skip checkpointing based on the provided value', 'check if a given path is a nontrivial checkpoint different from the project root directory', 'load a protobuf config from a .prototxt file and apply key=value scalar overrides', 'load a MetaCfg root config from a prototxt file with optional scalar overrides applied', 'save a protobuf config message to a .prototxt file using text format serialization', 'apply scalar key=value overrides to a frozen config and return a new frozen config', 'convert a protobuf config message to a Python dictionary with optional default values included', 'run the HeyHi main entrypoint to parse CLI args and launch an experiment with a config file', 'run an experiment locally or remotely by computing the task in the specified mode with config overrides', 'create an experiment directory path for a given project name using the HH_EXP_DIR environment variable', 'create the default experiment directory path for the diplomacy project using the hardcoded PROJECT_NAME constant', 'review the HeyHi entrypoint function that handles config loading, experiment status detection, and local or remote launch', 'setup logging with console and file handlers at configurable levels with custom labels', 'handle experiment directory status with modes like gentle_start, restart, start_continue, or dryrun', 'run a task function with a config file and optional overrides via local or slurm launcher', 'manage experiment directories by saving job IDs, checking status, and killing or pruning jobs', 'generate a unique experiment ID from a config path, overrides, and adhoc flag']
```

Usage

```
{'run_parse_args_and_maybe_launch': 'run the HeyHi main entrypoint to parse CLI args and launch an experiment with a config file', 'run_maybe_launch': 'run an experiment locally or remotely by computing the task in the specified mode with config overrides', 'create_get_exp_dir': 'create an experiment directory path for a given project name using the HH_EXP_DIR environment variable', 'create_get_default_exp_dir': 'create the default experiment directory path for the diplomacy project using the hardcoded PROJECT_NAME constant', 'review_parse_args_and_maybe_launch': 'review the HeyHi entrypoint function that handles config loading, experiment status detection, and local or remote launch'}
```

## File: facebookresearch_diplomacycicero/heyhi/util.py

Prompts

```
['create a copy of all repo code into a new tmp directory via checkpoint_repo.sh', 'get an existing checkpoint path from ckpt.link or create a new one for the output directory', 'add a --checkpoint CLI argument to an argparse parser for archiving code before slurm runs', 'handle the checkpoint CLI argument to create or skip checkpointing based on the provided value', 'check if a given path is a nontrivial checkpoint different from the project root directory', 'load a protobuf config from a .prototxt file and apply key=value scalar overrides', 'load a MetaCfg root config from a prototxt file with optional scalar overrides applied', 'save a protobuf config message to a .prototxt file using text format serialization', 'apply scalar key=value overrides to a frozen config and return a new frozen config', 'convert a protobuf config message to a Python dictionary with optional default values included', 'run the HeyHi main entrypoint to parse CLI args and launch an experiment with a config file', 'run an experiment locally or remotely by computing the task in the specified mode with config overrides', 'create an experiment directory path for a given project name using the HH_EXP_DIR environment variable', 'create the default experiment directory path for the diplomacy project using the hardcoded PROJECT_NAME constant', 'review the HeyHi entrypoint function that handles config loading, experiment status detection, and local or remote launch', 'setup logging with console and file handlers at configurable levels with custom labels', 'handle experiment directory status with modes like gentle_start, restart, start_continue, or dryrun', 'run a task function with a config file and optional overrides via local or slurm launcher', 'manage experiment directories by saving job IDs, checking status, and killing or pruning jobs', 'generate a unique experiment ID from a config path, overrides, and adhoc flag']
```

Usage

```
{'setup_logging': 'setup logging with console and file handlers at configurable levels with custom labels', 'handle_experiment_status': 'handle experiment directory status with modes like gentle_start, restart, start_continue, or dryrun', 'run_with_config': 'run a task function with a config file and optional overrides via local or slurm launcher', 'manage_experiment_dir': 'manage experiment directories by saving job IDs, checking status, and killing or pruning jobs', 'generate_experiment_id': 'generate a unique experiment ID from a config path, overrides, and adhoc flag'}
```

