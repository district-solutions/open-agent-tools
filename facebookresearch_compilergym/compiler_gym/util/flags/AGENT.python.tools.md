# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/compiler_gym/util/flags/benchmark_from_flags.py

Prompts

```
['run benchmark_from_flags to get the benchmark name or Benchmark message from commandline flags', 'review the benchmark_from_flags function that parses absl flags to return a benchmark URI or Benchmark object', 'test benchmark_from_flags with a file:/// URI to verify it returns a Benchmark from file path', 'test benchmark_from_flags with no benchmark flag set to verify it returns None', 'refactor benchmark_from_flags to support additional URI schemes beyond file:/// and benchmark://', 'create a CompilerEnv from command-line flags using env_from_flags with an optional benchmark argument', 'create ConnectionOpts from absl flags using connection_settings_from_flags for service timeout and retry configuration', 'create a managed environment session using env_session_from_flags as a context manager with automatic cleanup', 'list all registered CompilerGym environments by passing the --ls_env flag to env_from_flags', 'configure a CompilerEnv observation space and reward space via --observation and --reward flags']
```

Usage

```
{'run_benchmark_from_flags': 'run benchmark_from_flags to get the benchmark name or Benchmark message from commandline flags', 'review_benchmark_from_flags': 'review the benchmark_from_flags function that parses absl flags to return a benchmark URI or Benchmark object', 'test_benchmark_from_flags': 'test benchmark_from_flags with a file:/// URI to verify it returns a Benchmark from file path', 'test_benchmark_from_flags_no_flag': 'test benchmark_from_flags with no benchmark flag set to verify it returns None', 'refactor_benchmark_from_flags': 'refactor benchmark_from_flags to support additional URI schemes beyond file:/// and benchmark://'}
```

## File: facebookresearch_compilergym/compiler_gym/util/flags/env_from_flags.py

Prompts

```
['run benchmark_from_flags to get the benchmark name or Benchmark message from commandline flags', 'review the benchmark_from_flags function that parses absl flags to return a benchmark URI or Benchmark object', 'test benchmark_from_flags with a file:/// URI to verify it returns a Benchmark from file path', 'test benchmark_from_flags with no benchmark flag set to verify it returns None', 'refactor benchmark_from_flags to support additional URI schemes beyond file:/// and benchmark://', 'create a CompilerEnv from command-line flags using env_from_flags with an optional benchmark argument', 'create ConnectionOpts from absl flags using connection_settings_from_flags for service timeout and retry configuration', 'create a managed environment session using env_session_from_flags as a context manager with automatic cleanup', 'list all registered CompilerGym environments by passing the --ls_env flag to env_from_flags', 'configure a CompilerEnv observation space and reward space via --observation and --reward flags']
```

Usage

```
{'create_compiler_env_from_flags': 'create a CompilerEnv from command-line flags using env_from_flags with an optional benchmark argument', 'create_connection_opts_from_flags': 'create ConnectionOpts from absl flags using connection_settings_from_flags for service timeout and retry configuration', 'create_env_session_context_manager': 'create a managed environment session using env_session_from_flags as a context manager with automatic cleanup', 'list_available_compiler_gym_envs': 'list all registered CompilerGym environments by passing the --ls_env flag to env_from_flags', 'configure_env_observation_and_reward': 'configure a CompilerEnv observation space and reward space via --observation and --reward flags'}
```

