# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/examples/example_unrolling_service/env_tests.py

Prompts

```
['test the unrolling-py-v0 environment action spaces for loop unroll count options', 'test the unrolling environment observation spaces including ir features runtime and size', 'test the unrolling environment reward spaces for runtime and size metrics', 'test forking the unrolling environment to verify benchmark and action state are preserved', 'test listing available benchmark URIs for the unrolling-v0 dataset in the environment', 'run the pytest test suite for the unrolling CompilerGym service example environment', 'create a RuntimeReward class that computes incremental reward from runtime observation changes', 'create a SizeReward class that computes incremental reward from size observation changes', 'create an UnrollingDataset class that preprocesses C benchmarks through the clang compiler frontend', 'register the unrolling-py-v2 environment with custom rewards and datasets using compiler_gym registration', 'run the unrolling example service without bazel by executing example_without_bazel.py from the examples directory', 'create a RuntimeReward class that computes incremental reward based on changes in the runtime observation value', 'create a SizeReward class that computes incremental reward based on changes in the size observation value', 'create an UnrollingDataset class that registers C benchmarks and preprocesses them through the clang compiler frontend', 'register a custom CompilerGym environment using the register function with a client service, rewards, and datasets']
```

Usage

```
{'test_unrolling_env_action_space': 'test the unrolling-py-v0 environment action spaces for loop unroll count options', 'test_unrolling_env_observation_spaces': 'test the unrolling environment observation spaces including ir features runtime and size', 'test_unrolling_env_reward_spaces': 'test the unrolling environment reward spaces for runtime and size metrics', 'test_unrolling_env_fork': 'test forking the unrolling environment to verify benchmark and action state are preserved', 'test_unrolling_env_benchmarks': 'test listing available benchmark URIs for the unrolling-v0 dataset in the environment'}
```

## File: facebookresearch_compilergym/examples/example_unrolling_service/env_without_bazel_test.py

Prompts

```
['test the unrolling-py-v0 environment action spaces for loop unroll count options', 'test the unrolling environment observation spaces including ir features runtime and size', 'test the unrolling environment reward spaces for runtime and size metrics', 'test forking the unrolling environment to verify benchmark and action state are preserved', 'test listing available benchmark URIs for the unrolling-v0 dataset in the environment', 'run the pytest test suite for the unrolling CompilerGym service example environment', 'create a RuntimeReward class that computes incremental reward from runtime observation changes', 'create a SizeReward class that computes incremental reward from size observation changes', 'create an UnrollingDataset class that preprocesses C benchmarks through the clang compiler frontend', 'register the unrolling-py-v2 environment with custom rewards and datasets using compiler_gym registration', 'run the unrolling example service without bazel by executing example_without_bazel.py from the examples directory', 'create a RuntimeReward class that computes incremental reward based on changes in the runtime observation value', 'create a SizeReward class that computes incremental reward based on changes in the size observation value', 'create an UnrollingDataset class that registers C benchmarks and preprocesses them through the clang compiler frontend', 'register a custom CompilerGym environment using the register function with a client service, rewards, and datasets']
```

Usage

```
{'run_unrolling_service_tests': 'run the pytest test suite for the unrolling CompilerGym service example environment', 'create_runtime_reward_class': 'create a RuntimeReward class that computes incremental reward from runtime observation changes', 'create_size_reward_class': 'create a SizeReward class that computes incremental reward from size observation changes', 'create_unrolling_dataset_class': 'create an UnrollingDataset class that preprocesses C benchmarks through the clang compiler frontend', 'register_unrolling_environment': 'register the unrolling-py-v2 environment with custom rewards and datasets using compiler_gym registration'}
```

## File: facebookresearch_compilergym/examples/example_unrolling_service/example_without_bazel.py

Prompts

```
['test the unrolling-py-v0 environment action spaces for loop unroll count options', 'test the unrolling environment observation spaces including ir features runtime and size', 'test the unrolling environment reward spaces for runtime and size metrics', 'test forking the unrolling environment to verify benchmark and action state are preserved', 'test listing available benchmark URIs for the unrolling-v0 dataset in the environment', 'run the pytest test suite for the unrolling CompilerGym service example environment', 'create a RuntimeReward class that computes incremental reward from runtime observation changes', 'create a SizeReward class that computes incremental reward from size observation changes', 'create an UnrollingDataset class that preprocesses C benchmarks through the clang compiler frontend', 'register the unrolling-py-v2 environment with custom rewards and datasets using compiler_gym registration', 'run the unrolling example service without bazel by executing example_without_bazel.py from the examples directory', 'create a RuntimeReward class that computes incremental reward based on changes in the runtime observation value', 'create a SizeReward class that computes incremental reward based on changes in the size observation value', 'create an UnrollingDataset class that registers C benchmarks and preprocesses them through the clang compiler frontend', 'register a custom CompilerGym environment using the register function with a client service, rewards, and datasets']
```

Usage

```
{'run_unrolling_service_example': 'run the unrolling example service without bazel by executing example_without_bazel.py from the examples directory', 'create_runtime_reward': 'create a RuntimeReward class that computes incremental reward based on changes in the runtime observation value', 'create_size_reward': 'create a SizeReward class that computes incremental reward based on changes in the size observation value', 'create_unrolling_dataset': 'create an UnrollingDataset class that registers C benchmarks and preprocesses them through the clang compiler frontend', 'register_compiler_gym_environment': 'register a custom CompilerGym environment using the register function with a client service, rewards, and datasets'}
```

