# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/run.py

Prompts

```
['run an MLGym agent against a task environment using the main entry point', 'parse command line arguments into a ScriptArguments config object with default values', 'configure a ScriptArguments dataclass with environment, agent, and GPU settings for a run', 'run a single agent instance against an MLGym environment and log the trajectory', 'launch multiple agents asynchronously with GPU distribution across available devices', 'run a replay of a trajectory file using a config template and task ID', 'run process_single_traj to extract assistant actions from a trajectory and replay them via run.py', 'run get_args to parse CLI arguments for trajectory path, config file, task ID, and suffix', 'review process_single_traj to understand how it extracts assistant actions from JSON or YAML trajectory files', 'test the main function by passing a trajectory path, config file, and task ID to replay actions']
```

Usage

```
{'run_mlgym_agent': 'run an MLGym agent against a task environment using the main entry point', 'parse_mlgym_args': 'parse command line arguments into a ScriptArguments config object with default values', 'configure_script_arguments': 'configure a ScriptArguments dataclass with environment, agent, and GPU settings for a run', 'run_single_agent': 'run a single agent instance against an MLGym environment and log the trajectory', 'launch_parallel_agents': 'launch multiple agents asynchronously with GPU distribution across available devices'}
```

## File: facebookresearch_mlgym/run_replay.py

Prompts

```
['run an MLGym agent against a task environment using the main entry point', 'parse command line arguments into a ScriptArguments config object with default values', 'configure a ScriptArguments dataclass with environment, agent, and GPU settings for a run', 'run a single agent instance against an MLGym environment and log the trajectory', 'launch multiple agents asynchronously with GPU distribution across available devices', 'run a replay of a trajectory file using a config template and task ID', 'run process_single_traj to extract assistant actions from a trajectory and replay them via run.py', 'run get_args to parse CLI arguments for trajectory path, config file, task ID, and suffix', 'review process_single_traj to understand how it extracts assistant actions from JSON or YAML trajectory files', 'test the main function by passing a trajectory path, config file, and task ID to replay actions']
```

Usage

```
{'run_replay_trajectory': 'run a replay of a trajectory file using a config template and task ID', 'run_process_single_traj': 'run process_single_traj to extract assistant actions from a trajectory and replay them via run.py', 'run_get_args': 'run get_args to parse CLI arguments for trajectory path, config file, task ID, and suffix', 'review_process_single_traj': 'review process_single_traj to understand how it extracts assistant actions from JSON or YAML trajectory files', 'test_main': 'test the main function by passing a trajectory path, config file, and task ID to replay actions'}
```

