# Agent Python Tools

- repo: facebookresearch/motif
- repo_uri: https://github.com/facebookresearch/motif

## File: facebookresearch_motif/rl_baseline/sample-factory/sample_factory/run_algorithm.py

Prompts

```
['run a reinforcement learning algorithm by passing a config object to run_algorithm', 'run RL training by calling main which parses CLI args and executes the algorithm', 'run an algorithm resuming from a checkpoint by passing a config with checkpoint path', 'parse command line arguments to create a config for running a reinforcement learning algorithm', 'get the algorithm class for a given algo name from the config to instantiate and run', 'run tensorboard on multiple directories using wildcard filters and auto-restart every 10 hours', 'run tensorboard in quiet mode by passing the --quiet flag to suppress stderr output', 'run tensorboard on a custom port by passing --port to the tb.py CLI script', 'test the tb_version function to parse and return the major and minor tensorboard version numbers', 'review the main function that launches tensorboard in a loop and restarts it periodically to prevent memory leaks']
```

Usage

```
{'run_algorithm': 'run a reinforcement learning algorithm by passing a config object to run_algorithm', 'run_rl_training': 'run RL training by calling main which parses CLI args and executes the algorithm', 'run_from_checkpoint': 'run an algorithm resuming from a checkpoint by passing a config with checkpoint path', 'parse_args': 'parse command line arguments to create a config for running a reinforcement learning algorithm', 'get_algo_class': 'get the algorithm class for a given algo name from the config to instantiate and run'}
```

## File: facebookresearch_motif/rl_baseline/sample-factory/sample_factory/tb.py

Prompts

```
['run a reinforcement learning algorithm by passing a config object to run_algorithm', 'run RL training by calling main which parses CLI args and executes the algorithm', 'run an algorithm resuming from a checkpoint by passing a config with checkpoint path', 'parse command line arguments to create a config for running a reinforcement learning algorithm', 'get the algorithm class for a given algo name from the config to instantiate and run', 'run tensorboard on multiple directories using wildcard filters and auto-restart every 10 hours', 'run tensorboard in quiet mode by passing the --quiet flag to suppress stderr output', 'run tensorboard on a custom port by passing --port to the tb.py CLI script', 'test the tb_version function to parse and return the major and minor tensorboard version numbers', 'review the main function that launches tensorboard in a loop and restarts it periodically to prevent memory leaks']
```

Usage

```
{'run_tensorboard_with_wildcard': 'run tensorboard on multiple directories using wildcard filters and auto-restart every 10 hours', 'run_tensorboard_quiet_mode': 'run tensorboard in quiet mode by passing the --quiet flag to suppress stderr output', 'run_tensorboard_custom_port': 'run tensorboard on a custom port by passing --port to the tb.py CLI script', 'test_tb_version': 'test the tb_version function to parse and return the major and minor tensorboard version numbers', 'review_main_tensorboard_loop': 'review the main function that launches tensorboard in a loop and restarts it periodically to prevent memory leaks'}
```

