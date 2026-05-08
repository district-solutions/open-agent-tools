# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/d2go/distributed.py

Prompts

```
['launch a D2Go distributed training job across multiple processes and machines with automatic CPU fallback', 'create a D2GoSharedContext dataclass to pass shared state to all distributed workers before launch', 'get the local rank of the current process in a distributed D2Go training setup', 'get the number of processes running per machine in a D2Go distributed environment', 'run a D2Go distributed worker function that sets up process groups and executes the main function', 'run initialize_all to set up the D2Go environment and populate all registries', 'run initialize_all with boostrap_registries true to also bootstrap registries with caching enabled', 'review the initialize_all function to understand the idempotent initialization guard pattern', 'summarize the _setup_env function that registers torchvision ops and sets up Detectron2 environment', 'review the _populate_registries function that imports optimizer, dataset_mappers, and fbnet_v2 modules', 'build a list of CLI argument strings from config path, output dir, and runner name parameters', 'create a CfgNode config object from a config file path with optional command-line overwrites', 'build an argparse parser for Detectron2Go training binaries with distributed and output dir options', 'run post-launch setup including logger init, config dump, runner initialization, and deterministic training config', 'create a picklable wrapper decorator that enables post-mortem debugging on failure for the main function']
```

Usage

```
{'launch_distributed_training': 'launch a D2Go distributed training job across multiple processes and machines with automatic CPU fallback', 'create_shared_context': 'create a D2GoSharedContext dataclass to pass shared state to all distributed workers before launch', 'get_local_rank': 'get the local rank of the current process in a distributed D2Go training setup', 'get_num_processes_per_machine': 'get the number of processes running per machine in a D2Go distributed environment', 'run_distributed_worker': 'run a D2Go distributed worker function that sets up process groups and executes the main function'}
```

## File: facebookresearch_d2go/d2go/initializer.py

Prompts

```
['launch a D2Go distributed training job across multiple processes and machines with automatic CPU fallback', 'create a D2GoSharedContext dataclass to pass shared state to all distributed workers before launch', 'get the local rank of the current process in a distributed D2Go training setup', 'get the number of processes running per machine in a D2Go distributed environment', 'run a D2Go distributed worker function that sets up process groups and executes the main function', 'run initialize_all to set up the D2Go environment and populate all registries', 'run initialize_all with boostrap_registries true to also bootstrap registries with caching enabled', 'review the initialize_all function to understand the idempotent initialization guard pattern', 'summarize the _setup_env function that registers torchvision ops and sets up Detectron2 environment', 'review the _populate_registries function that imports optimizer, dataset_mappers, and fbnet_v2 modules', 'build a list of CLI argument strings from config path, output dir, and runner name parameters', 'create a CfgNode config object from a config file path with optional command-line overwrites', 'build an argparse parser for Detectron2Go training binaries with distributed and output dir options', 'run post-launch setup including logger init, config dump, runner initialization, and deterministic training config', 'create a picklable wrapper decorator that enables post-mortem debugging on failure for the main function']
```

Usage

```
{'run_initialize_all': 'run initialize_all to set up the D2Go environment and populate all registries', 'run_initialize_all_with_bootstrap': 'run initialize_all with boostrap_registries true to also bootstrap registries with caching enabled', 'review_initialize_all': 'review the initialize_all function to understand the idempotent initialization guard pattern', 'summarize_setup_env': 'summarize the _setup_env function that registers torchvision ops and sets up Detectron2 environment', 'review_populate_registries': 'review the _populate_registries function that imports optimizer, dataset_mappers, and fbnet_v2 modules'}
```

## File: facebookresearch_d2go/d2go/setup.py

Prompts

```
['launch a D2Go distributed training job across multiple processes and machines with automatic CPU fallback', 'create a D2GoSharedContext dataclass to pass shared state to all distributed workers before launch', 'get the local rank of the current process in a distributed D2Go training setup', 'get the number of processes running per machine in a D2Go distributed environment', 'run a D2Go distributed worker function that sets up process groups and executes the main function', 'run initialize_all to set up the D2Go environment and populate all registries', 'run initialize_all with boostrap_registries true to also bootstrap registries with caching enabled', 'review the initialize_all function to understand the idempotent initialization guard pattern', 'summarize the _setup_env function that registers torchvision ops and sets up Detectron2 environment', 'review the _populate_registries function that imports optimizer, dataset_mappers, and fbnet_v2 modules', 'build a list of CLI argument strings from config path, output dir, and runner name parameters', 'create a CfgNode config object from a config file path with optional command-line overwrites', 'build an argparse parser for Detectron2Go training binaries with distributed and output dir options', 'run post-launch setup including logger init, config dump, runner initialization, and deterministic training config', 'create a picklable wrapper decorator that enables post-mortem debugging on failure for the main function']
```

Usage

```
{'build_basic_cli_args': 'build a list of CLI argument strings from config path, output dir, and runner name parameters', 'create_cfg_from_cli': 'create a CfgNode config object from a config file path with optional command-line overwrites', 'setup_basic_argument_parser': 'build an argparse parser for Detectron2Go training binaries with distributed and output dir options', 'setup_after_launch': 'run post-launch setup including logger init, config dump, runner initialization, and deterministic training config', 'post_mortem_if_fail_for_main': 'create a picklable wrapper decorator that enables post-mortem debugging on failure for the main function'}
```

