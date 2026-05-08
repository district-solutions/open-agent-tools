# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/examples/loop_optimizations_service/env_tests.py

Prompts

```
['test the loops-opt-py-v0 environment action spaces for loop unroll and vectorize options', 'test the loops-opt-py-v0 environment observation spaces including IR Inst2vec Autophase and Programl', 'test the loops-opt-py-v0 environment reward spaces for runtime and size metrics', 'test forking a CompilerGym environment to preserve benchmark and action history', 'test listing available benchmark URIs for the loops-opt-v0 dataset', 'create a RuntimeReward class that computes incremental reward from changes in runtime observation values', 'create a SizeReward class that computes incremental reward from changes in compiled binary size observations', 'create a LoopsDataset class that registers C benchmark files and preprocesses them through the clang frontend', 'test the loops-opt-py-v2 CompilerGym environment action spaces, observation spaces, and reward spaces', 'run the pytest test suite with optional sharding support and custom pytest arguments', 'run the loop optimizations service example without bazel using compiler_gym.make with the loops-opt-py-v1 environment', 'create a RuntimeReward subclass of Reward that computes incremental reward based on changes in runtime observation values', 'create a SizeReward subclass of Reward that computes incremental reward based on changes in size observation values', 'create a LoopsDataset subclass of Dataset with benchmarks for add, offsets1, and conv2d C programs', 'preprocess a C source file through the clang compiler frontend using LoopsDataset.preprocess to include system library flags']
```

Usage

```
{'test_loop_optimization_env_action_space': 'test the loops-opt-py-v0 environment action spaces for loop unroll and vectorize options', 'test_loop_optimization_env_observation_spaces': 'test the loops-opt-py-v0 environment observation spaces including IR Inst2vec Autophase and Programl', 'test_loop_optimization_env_reward_spaces': 'test the loops-opt-py-v0 environment reward spaces for runtime and size metrics', 'test_loop_optimization_env_fork': 'test forking a CompilerGym environment to preserve benchmark and action history', 'test_loop_optimization_env_benchmarks': 'test listing available benchmark URIs for the loops-opt-v0 dataset'}
```

## File: facebookresearch_compilergym/examples/loop_optimizations_service/env_without_bazel_test.py

Prompts

```
['test the loops-opt-py-v0 environment action spaces for loop unroll and vectorize options', 'test the loops-opt-py-v0 environment observation spaces including IR Inst2vec Autophase and Programl', 'test the loops-opt-py-v0 environment reward spaces for runtime and size metrics', 'test forking a CompilerGym environment to preserve benchmark and action history', 'test listing available benchmark URIs for the loops-opt-v0 dataset', 'create a RuntimeReward class that computes incremental reward from changes in runtime observation values', 'create a SizeReward class that computes incremental reward from changes in compiled binary size observations', 'create a LoopsDataset class that registers C benchmark files and preprocesses them through the clang frontend', 'test the loops-opt-py-v2 CompilerGym environment action spaces, observation spaces, and reward spaces', 'run the pytest test suite with optional sharding support and custom pytest arguments', 'run the loop optimizations service example without bazel using compiler_gym.make with the loops-opt-py-v1 environment', 'create a RuntimeReward subclass of Reward that computes incremental reward based on changes in runtime observation values', 'create a SizeReward subclass of Reward that computes incremental reward based on changes in size observation values', 'create a LoopsDataset subclass of Dataset with benchmarks for add, offsets1, and conv2d C programs', 'preprocess a C source file through the clang compiler frontend using LoopsDataset.preprocess to include system library flags']
```

Usage

```
{'create_RuntimeReward': 'create a RuntimeReward class that computes incremental reward from changes in runtime observation values', 'create_SizeReward': 'create a SizeReward class that computes incremental reward from changes in compiled binary size observations', 'create_LoopsDataset': 'create a LoopsDataset class that registers C benchmark files and preprocesses them through the clang frontend', 'test_loops_opt_environment': 'test the loops-opt-py-v2 CompilerGym environment action spaces, observation spaces, and reward spaces', 'run_pytest_main': 'run the pytest test suite with optional sharding support and custom pytest arguments'}
```

## File: facebookresearch_compilergym/examples/loop_optimizations_service/example_without_bazel.py

Prompts

```
['test the loops-opt-py-v0 environment action spaces for loop unroll and vectorize options', 'test the loops-opt-py-v0 environment observation spaces including IR Inst2vec Autophase and Programl', 'test the loops-opt-py-v0 environment reward spaces for runtime and size metrics', 'test forking a CompilerGym environment to preserve benchmark and action history', 'test listing available benchmark URIs for the loops-opt-v0 dataset', 'create a RuntimeReward class that computes incremental reward from changes in runtime observation values', 'create a SizeReward class that computes incremental reward from changes in compiled binary size observations', 'create a LoopsDataset class that registers C benchmark files and preprocesses them through the clang frontend', 'test the loops-opt-py-v2 CompilerGym environment action spaces, observation spaces, and reward spaces', 'run the pytest test suite with optional sharding support and custom pytest arguments', 'run the loop optimizations service example without bazel using compiler_gym.make with the loops-opt-py-v1 environment', 'create a RuntimeReward subclass of Reward that computes incremental reward based on changes in runtime observation values', 'create a SizeReward subclass of Reward that computes incremental reward based on changes in size observation values', 'create a LoopsDataset subclass of Dataset with benchmarks for add, offsets1, and conv2d C programs', 'preprocess a C source file through the clang compiler frontend using LoopsDataset.preprocess to include system library flags']
```

Usage

```
{'run_loop_optimization_service': 'run the loop optimizations service example without bazel using compiler_gym.make with the loops-opt-py-v1 environment', 'create_runtime_reward': 'create a RuntimeReward subclass of Reward that computes incremental reward based on changes in runtime observation values', 'create_size_reward': 'create a SizeReward subclass of Reward that computes incremental reward based on changes in size observation values', 'create_loops_dataset': 'create a LoopsDataset subclass of Dataset with benchmarks for add, offsets1, and conv2d C programs', 'preprocess_c_source': 'preprocess a C source file through the clang compiler frontend using LoopsDataset.preprocess to include system library flags'}
```

