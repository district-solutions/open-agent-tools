# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/compiler_gym/bin/manual_env.py

Prompts

```
['run the CompilerGym interactive shell with python -m compiler_gym.bin.manual_env --env=<env>', 'run hill climbing search in the CompilerGym shell to accept only positive reward actions', 'run greedy search in the CompilerGym shell to select the highest reward action each step', 'run a compiler action like tailcallelim or loop-unroll on the current benchmark in the shell', 'run simplify_stack in the CompilerGym shell to remove no-effect or negative reward actions', 'run the random_eval CLI tool to evaluate random search logs from an output directory', 'evaluate random search progress logs and print a summary table with benchmark rewards and statistics', 'parse a random search progress CSV line using RandomSearchProgressLogEntry.from_csv to extract reward and episode data', 'compute the geometric mean of initial and max rewards across benchmarks using the geometric_mean utility', 'format benchmark evaluation results into a tabulated table with headers for instructions, rewards, attempts, and actions', 'run a CompilerGym service on a specified port using --run_on_port and --env flags', 'query the capabilities of a CompilerGym environment including datasets, observation spaces, and action spaces', 'summarize an iterable of Dataset objects into a reStructuredText table with benchmark counts and descriptions', 'print tabular summaries of a CompilerEnv datasets, observation spaces, reward spaces, and action spaces', 'list the available CompilerGym environments using the --ls_env flag', 'run the validate script to replay compiler environment states from CSV input and verify rewards match', 'pipe benchmark CSV data into the validate script via stdin to check environment state rewards', 'run the validate script with geometric mean or arithmetic mean reward aggregation for summary statistics', 'run the validate script and write validation results to a JSON log file for later review', 'run the validate script in summary-only mode to print only aggregate statistics without individual results']
```

Usage

```
{'run_manual_env_shell': 'run the CompilerGym interactive shell with python -m compiler_gym.bin.manual_env --env=<env>', 'run_hill_climb_search': 'run hill climbing search in the CompilerGym shell to accept only positive reward actions', 'run_greedy_search': 'run greedy search in the CompilerGym shell to select the highest reward action each step', 'run_apply_compiler_action': 'run a compiler action like tailcallelim or loop-unroll on the current benchmark in the shell', 'run_simplify_action_stack': 'run simplify_stack in the CompilerGym shell to remove no-effect or negative reward actions'}
```

## File: facebookresearch_compilergym/compiler_gym/bin/random_eval.py

Prompts

```
['run the CompilerGym interactive shell with python -m compiler_gym.bin.manual_env --env=<env>', 'run hill climbing search in the CompilerGym shell to accept only positive reward actions', 'run greedy search in the CompilerGym shell to select the highest reward action each step', 'run a compiler action like tailcallelim or loop-unroll on the current benchmark in the shell', 'run simplify_stack in the CompilerGym shell to remove no-effect or negative reward actions', 'run the random_eval CLI tool to evaluate random search logs from an output directory', 'evaluate random search progress logs and print a summary table with benchmark rewards and statistics', 'parse a random search progress CSV line using RandomSearchProgressLogEntry.from_csv to extract reward and episode data', 'compute the geometric mean of initial and max rewards across benchmarks using the geometric_mean utility', 'format benchmark evaluation results into a tabulated table with headers for instructions, rewards, attempts, and actions', 'run a CompilerGym service on a specified port using --run_on_port and --env flags', 'query the capabilities of a CompilerGym environment including datasets, observation spaces, and action spaces', 'summarize an iterable of Dataset objects into a reStructuredText table with benchmark counts and descriptions', 'print tabular summaries of a CompilerEnv datasets, observation spaces, reward spaces, and action spaces', 'list the available CompilerGym environments using the --ls_env flag', 'run the validate script to replay compiler environment states from CSV input and verify rewards match', 'pipe benchmark CSV data into the validate script via stdin to check environment state rewards', 'run the validate script with geometric mean or arithmetic mean reward aggregation for summary statistics', 'run the validate script and write validation results to a JSON log file for later review', 'run the validate script in summary-only mode to print only aggregate statistics without individual results']
```

Usage

```
{'run_random_eval_cli': 'run the random_eval CLI tool to evaluate random search logs from an output directory', 'eval_logs_function': 'evaluate random search progress logs and print a summary table with benchmark rewards and statistics', 'parse_random_search_progress_csv': 'parse a random search progress CSV line using RandomSearchProgressLogEntry.from_csv to extract reward and episode data', 'compute_geometric_mean_rewards': 'compute the geometric mean of initial and max rewards across benchmarks using the geometric_mean utility', 'tabulate_benchmark_results': 'format benchmark evaluation results into a tabulated table with headers for instructions, rewards, attempts, and actions'}
```

## File: facebookresearch_compilergym/compiler_gym/bin/service.py

Prompts

```
['run the CompilerGym interactive shell with python -m compiler_gym.bin.manual_env --env=<env>', 'run hill climbing search in the CompilerGym shell to accept only positive reward actions', 'run greedy search in the CompilerGym shell to select the highest reward action each step', 'run a compiler action like tailcallelim or loop-unroll on the current benchmark in the shell', 'run simplify_stack in the CompilerGym shell to remove no-effect or negative reward actions', 'run the random_eval CLI tool to evaluate random search logs from an output directory', 'evaluate random search progress logs and print a summary table with benchmark rewards and statistics', 'parse a random search progress CSV line using RandomSearchProgressLogEntry.from_csv to extract reward and episode data', 'compute the geometric mean of initial and max rewards across benchmarks using the geometric_mean utility', 'format benchmark evaluation results into a tabulated table with headers for instructions, rewards, attempts, and actions', 'run a CompilerGym service on a specified port using --run_on_port and --env flags', 'query the capabilities of a CompilerGym environment including datasets, observation spaces, and action spaces', 'summarize an iterable of Dataset objects into a reStructuredText table with benchmark counts and descriptions', 'print tabular summaries of a CompilerEnv datasets, observation spaces, reward spaces, and action spaces', 'list the available CompilerGym environments using the --ls_env flag', 'run the validate script to replay compiler environment states from CSV input and verify rewards match', 'pipe benchmark CSV data into the validate script via stdin to check environment state rewards', 'run the validate script with geometric mean or arithmetic mean reward aggregation for summary statistics', 'run the validate script and write validation results to a JSON log file for later review', 'run the validate script in summary-only mode to print only aggregate statistics without individual results']
```

Usage

```
{'run_service_on_port': 'run a CompilerGym service on a specified port using --run_on_port and --env flags', 'query_service_capabilities': 'query the capabilities of a CompilerGym environment including datasets, observation spaces, and action spaces', 'summarize_datasets': 'summarize an iterable of Dataset objects into a reStructuredText table with benchmark counts and descriptions', 'print_service_capabilities': 'print tabular summaries of a CompilerEnv datasets, observation spaces, reward spaces, and action spaces', 'list_available_environments': 'list the available CompilerGym environments using the --ls_env flag'}
```

## File: facebookresearch_compilergym/compiler_gym/bin/validate.py

Prompts

```
['run the CompilerGym interactive shell with python -m compiler_gym.bin.manual_env --env=<env>', 'run hill climbing search in the CompilerGym shell to accept only positive reward actions', 'run greedy search in the CompilerGym shell to select the highest reward action each step', 'run a compiler action like tailcallelim or loop-unroll on the current benchmark in the shell', 'run simplify_stack in the CompilerGym shell to remove no-effect or negative reward actions', 'run the random_eval CLI tool to evaluate random search logs from an output directory', 'evaluate random search progress logs and print a summary table with benchmark rewards and statistics', 'parse a random search progress CSV line using RandomSearchProgressLogEntry.from_csv to extract reward and episode data', 'compute the geometric mean of initial and max rewards across benchmarks using the geometric_mean utility', 'format benchmark evaluation results into a tabulated table with headers for instructions, rewards, attempts, and actions', 'run a CompilerGym service on a specified port using --run_on_port and --env flags', 'query the capabilities of a CompilerGym environment including datasets, observation spaces, and action spaces', 'summarize an iterable of Dataset objects into a reStructuredText table with benchmark counts and descriptions', 'print tabular summaries of a CompilerEnv datasets, observation spaces, reward spaces, and action spaces', 'list the available CompilerGym environments using the --ls_env flag', 'run the validate script to replay compiler environment states from CSV input and verify rewards match', 'pipe benchmark CSV data into the validate script via stdin to check environment state rewards', 'run the validate script with geometric mean or arithmetic mean reward aggregation for summary statistics', 'run the validate script and write validation results to a JSON log file for later review', 'run the validate script in summary-only mode to print only aggregate statistics without individual results']
```

Usage

```
{'run_validate_compiler_env_states': 'run the validate script to replay compiler environment states from CSV input and verify rewards match', 'run_validate_from_stdin': 'pipe benchmark CSV data into the validate script via stdin to check environment state rewards', 'run_validate_with_reward_aggregation': 'run the validate script with geometric mean or arithmetic mean reward aggregation for summary statistics', 'run_validate_with_json_log': 'run the validate script and write validation results to a JSON log file for later review', 'run_validate_summary_only': 'run the validate script in summary-only mode to print only aggregate statistics without individual results'}
```

