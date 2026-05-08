# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/examples/example_compiler_gym_service/demo_without_bazel.py

Prompts

```
['run the example compiler gym service demo without bazel using gym.make and random actions', 'create a RuntimeReward class that computes incremental reward from changes in the runtime observation value', 'create an ExampleDataset class with in-memory benchmarks using Benchmark.from_file_contents for foo and bar', 'register a custom compiler gym environment with gym using the register function with rewards and datasets', 'run a gym environment loop that resets, samples random actions, and steps 20 times with observation and reward tracking', 'test the demo_without_bazel smoke test that runs the main function from example_compiler_gym_service', 'test that the CompilerGym service binary rejects unrecognized command-line arguments with an error', 'test that the CompilerGym environment reports ir, features, and runtime observation spaces', 'test forking a CompilerGym environment to copy its benchmark and action history', 'test that the CompilerGym service respects a forced port value via the --port flag', 'test that the CompilerGym service writes pid.txt and port.txt to the specified working directory', 'create a RuntimeReward class that computes incremental reward from runtime observation changes', 'create an ExampleDataset class with benchmark URIs and file content benchmarks', 'run the pytest test suite programmatically with sharding support and custom arguments', 'test the example CompilerGym service binary for invalid arguments and error handling']
```

Usage

```
{'run_compiler_gym_demo': 'run the example compiler gym service demo without bazel using gym.make and random actions', 'create_runtime_reward': 'create a RuntimeReward class that computes incremental reward from changes in the runtime observation value', 'create_example_dataset': 'create an ExampleDataset class with in-memory benchmarks using Benchmark.from_file_contents for foo and bar', 'register_gym_environment': 'register a custom compiler gym environment with gym using the register function with rewards and datasets', 'run_gym_environment_loop': 'run a gym environment loop that resets, samples random actions, and steps 20 times with observation and reward tracking'}
```

## File: facebookresearch_compilergym/examples/example_compiler_gym_service/demo_without_bazel_test.py

Prompts

```
['run the example compiler gym service demo without bazel using gym.make and random actions', 'create a RuntimeReward class that computes incremental reward from changes in the runtime observation value', 'create an ExampleDataset class with in-memory benchmarks using Benchmark.from_file_contents for foo and bar', 'register a custom compiler gym environment with gym using the register function with rewards and datasets', 'run a gym environment loop that resets, samples random actions, and steps 20 times with observation and reward tracking', 'test the demo_without_bazel smoke test that runs the main function from example_compiler_gym_service', 'test that the CompilerGym service binary rejects unrecognized command-line arguments with an error', 'test that the CompilerGym environment reports ir, features, and runtime observation spaces', 'test forking a CompilerGym environment to copy its benchmark and action history', 'test that the CompilerGym service respects a forced port value via the --port flag', 'test that the CompilerGym service writes pid.txt and port.txt to the specified working directory', 'create a RuntimeReward class that computes incremental reward from runtime observation changes', 'create an ExampleDataset class with benchmark URIs and file content benchmarks', 'run the pytest test suite programmatically with sharding support and custom arguments', 'test the example CompilerGym service binary for invalid arguments and error handling']
```

Usage

```
{'test_demo_without_bazel': 'test the demo_without_bazel smoke test that runs the main function from example_compiler_gym_service'}
```

## File: facebookresearch_compilergym/examples/example_compiler_gym_service/env_tests.py

Prompts

```
['run the example compiler gym service demo without bazel using gym.make and random actions', 'create a RuntimeReward class that computes incremental reward from changes in the runtime observation value', 'create an ExampleDataset class with in-memory benchmarks using Benchmark.from_file_contents for foo and bar', 'register a custom compiler gym environment with gym using the register function with rewards and datasets', 'run a gym environment loop that resets, samples random actions, and steps 20 times with observation and reward tracking', 'test the demo_without_bazel smoke test that runs the main function from example_compiler_gym_service', 'test that the CompilerGym service binary rejects unrecognized command-line arguments with an error', 'test that the CompilerGym environment reports ir, features, and runtime observation spaces', 'test forking a CompilerGym environment to copy its benchmark and action history', 'test that the CompilerGym service respects a forced port value via the --port flag', 'test that the CompilerGym service writes pid.txt and port.txt to the specified working directory', 'create a RuntimeReward class that computes incremental reward from runtime observation changes', 'create an ExampleDataset class with benchmark URIs and file content benchmarks', 'run the pytest test suite programmatically with sharding support and custom arguments', 'test the example CompilerGym service binary for invalid arguments and error handling']
```

Usage

```
{'test_invalid_arguments': 'test that the CompilerGym service binary rejects unrecognized command-line arguments with an error', 'test_observation_spaces': 'test that the CompilerGym environment reports ir, features, and runtime observation spaces', 'test_fork': 'test forking a CompilerGym environment to copy its benchmark and action history', 'test_force_port': 'test that the CompilerGym service respects a forced port value via the --port flag', 'test_force_working_dir': 'test that the CompilerGym service writes pid.txt and port.txt to the specified working directory'}
```

## File: facebookresearch_compilergym/examples/example_compiler_gym_service/env_without_bazel_test.py

Prompts

```
['run the example compiler gym service demo without bazel using gym.make and random actions', 'create a RuntimeReward class that computes incremental reward from changes in the runtime observation value', 'create an ExampleDataset class with in-memory benchmarks using Benchmark.from_file_contents for foo and bar', 'register a custom compiler gym environment with gym using the register function with rewards and datasets', 'run a gym environment loop that resets, samples random actions, and steps 20 times with observation and reward tracking', 'test the demo_without_bazel smoke test that runs the main function from example_compiler_gym_service', 'test that the CompilerGym service binary rejects unrecognized command-line arguments with an error', 'test that the CompilerGym environment reports ir, features, and runtime observation spaces', 'test forking a CompilerGym environment to copy its benchmark and action history', 'test that the CompilerGym service respects a forced port value via the --port flag', 'test that the CompilerGym service writes pid.txt and port.txt to the specified working directory', 'create a RuntimeReward class that computes incremental reward from runtime observation changes', 'create an ExampleDataset class with benchmark URIs and file content benchmarks', 'run the pytest test suite programmatically with sharding support and custom arguments', 'test the example CompilerGym service binary for invalid arguments and error handling']
```

Usage

```
{'create_runtime_reward_class': 'create a RuntimeReward class that computes incremental reward from runtime observation changes', 'create_example_dataset_class': 'create an ExampleDataset class with benchmark URIs and file content benchmarks', 'register_gym_environment': 'register a CompilerGym environment with custom rewards and datasets using register()', 'run_pytest_main': 'run the pytest test suite programmatically with sharding support and custom arguments', 'test_compiler_gym_service': 'test the example CompilerGym service binary for invalid arguments and error handling'}
```

