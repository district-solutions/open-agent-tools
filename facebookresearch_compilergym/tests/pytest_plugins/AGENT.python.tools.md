# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/tests/pytest_plugins/common.py

Prompts

```
['check if the current environment is a CI environment by inspecting the CI environment variable', 'check if the current test is running under bazel by inspecting the TEST_WORKSPACE environment variable', 'check if docker is available by attempting to connect to the docker daemon', 'use the tmpwd pytest fixture to create a temporary working directory and change into it', 'use the temporary_environ pytest fixture to safely modify environment variables during a test', 'check if system GCC is available by running gcc --version and parsing output', 'get the system GCC binary path by running which gcc in the shell', 'check if GCC environment is supported via Docker or system GCC availability', 'list all available GCC binaries including Docker and system GCC options', 'use the gcc_bin pytest fixture to parametrize tests with available GCC binaries', 'create a pytest fixture that yields an MlirEnv instance via gym.make mlir-v0', 'create a function that reads a file line by line and yields stripped non-empty lines', 'test the pytest observation_space fixture that parametrizes over MLIR observation space names', 'test the pytest reward_space fixture that parametrizes over MLIR reward space names', 'test the pytest dataset fixture that returns a Dataset by name from the MLIR environment', 'run a random trajectory of actions on a CompilerEnv and return the resulting trajectory', 'test the apply_random_trajectory function by running random actions on a CompilerEnv instance', 'review the apply_random_trajectory function that samples random actions and steps through a CompilerEnv', 'refactor apply_random_trajectory to support a custom action sampling strategy instead of random', 'summarize the apply_random_trajectory function that evaluates random action sequences with optional timeout']
```

Usage

```
{'check_is_ci': 'check if the current environment is a CI environment by inspecting the CI environment variable', 'check_in_bazel': 'check if the current test is running under bazel by inspecting the TEST_WORKSPACE environment variable', 'check_docker_available': 'check if docker is available by attempting to connect to the docker daemon', 'use_tmpwd_fixture': 'use the tmpwd pytest fixture to create a temporary working directory and change into it', 'use_temporary_environ_fixture': 'use the temporary_environ pytest fixture to safely modify environment variables during a test'}
```

## File: facebookresearch_compilergym/tests/pytest_plugins/gcc.py

Prompts

```
['check if the current environment is a CI environment by inspecting the CI environment variable', 'check if the current test is running under bazel by inspecting the TEST_WORKSPACE environment variable', 'check if docker is available by attempting to connect to the docker daemon', 'use the tmpwd pytest fixture to create a temporary working directory and change into it', 'use the temporary_environ pytest fixture to safely modify environment variables during a test', 'check if system GCC is available by running gcc --version and parsing output', 'get the system GCC binary path by running which gcc in the shell', 'check if GCC environment is supported via Docker or system GCC availability', 'list all available GCC binaries including Docker and system GCC options', 'use the gcc_bin pytest fixture to parametrize tests with available GCC binaries', 'create a pytest fixture that yields an MlirEnv instance via gym.make mlir-v0', 'create a function that reads a file line by line and yields stripped non-empty lines', 'test the pytest observation_space fixture that parametrizes over MLIR observation space names', 'test the pytest reward_space fixture that parametrizes over MLIR reward space names', 'test the pytest dataset fixture that returns a Dataset by name from the MLIR environment', 'run a random trajectory of actions on a CompilerEnv and return the resulting trajectory', 'test the apply_random_trajectory function by running random actions on a CompilerEnv instance', 'review the apply_random_trajectory function that samples random actions and steps through a CompilerEnv', 'refactor apply_random_trajectory to support a custom action sampling strategy instead of random', 'summarize the apply_random_trajectory function that evaluates random action sequences with optional timeout']
```

Usage

```
{'check_system_gcc_availability': 'check if system GCC is available by running gcc --version and parsing output', 'get_system_gcc_path': 'get the system GCC binary path by running which gcc in the shell', 'check_gcc_environment_support': 'check if GCC environment is supported via Docker or system GCC availability', 'list_available_gcc_bins': 'list all available GCC binaries including Docker and system GCC options', 'use_gcc_bin_fixture': 'use the gcc_bin pytest fixture to parametrize tests with available GCC binaries'}
```

## File: facebookresearch_compilergym/tests/pytest_plugins/mlir.py

Prompts

```
['check if the current environment is a CI environment by inspecting the CI environment variable', 'check if the current test is running under bazel by inspecting the TEST_WORKSPACE environment variable', 'check if docker is available by attempting to connect to the docker daemon', 'use the tmpwd pytest fixture to create a temporary working directory and change into it', 'use the temporary_environ pytest fixture to safely modify environment variables during a test', 'check if system GCC is available by running gcc --version and parsing output', 'get the system GCC binary path by running which gcc in the shell', 'check if GCC environment is supported via Docker or system GCC availability', 'list all available GCC binaries including Docker and system GCC options', 'use the gcc_bin pytest fixture to parametrize tests with available GCC binaries', 'create a pytest fixture that yields an MlirEnv instance via gym.make mlir-v0', 'create a function that reads a file line by line and yields stripped non-empty lines', 'test the pytest observation_space fixture that parametrizes over MLIR observation space names', 'test the pytest reward_space fixture that parametrizes over MLIR reward space names', 'test the pytest dataset fixture that returns a Dataset by name from the MLIR environment', 'run a random trajectory of actions on a CompilerEnv and return the resulting trajectory', 'test the apply_random_trajectory function by running random actions on a CompilerEnv instance', 'review the apply_random_trajectory function that samples random actions and steps through a CompilerEnv', 'refactor apply_random_trajectory to support a custom action sampling strategy instead of random', 'summarize the apply_random_trajectory function that evaluates random action sequences with optional timeout']
```

Usage

```
{'create_mlir_env_fixture': 'create a pytest fixture that yields an MlirEnv instance via gym.make mlir-v0', 'read_list_file': 'create a function that reads a file line by line and yields stripped non-empty lines', 'test_observation_space_fixture': 'test the pytest observation_space fixture that parametrizes over MLIR observation space names', 'test_reward_space_fixture': 'test the pytest reward_space fixture that parametrizes over MLIR reward space names', 'test_dataset_fixture': 'test the pytest dataset fixture that returns a Dataset by name from the MLIR environment'}
```

## File: facebookresearch_compilergym/tests/pytest_plugins/random_util.py

Prompts

```
['check if the current environment is a CI environment by inspecting the CI environment variable', 'check if the current test is running under bazel by inspecting the TEST_WORKSPACE environment variable', 'check if docker is available by attempting to connect to the docker daemon', 'use the tmpwd pytest fixture to create a temporary working directory and change into it', 'use the temporary_environ pytest fixture to safely modify environment variables during a test', 'check if system GCC is available by running gcc --version and parsing output', 'get the system GCC binary path by running which gcc in the shell', 'check if GCC environment is supported via Docker or system GCC availability', 'list all available GCC binaries including Docker and system GCC options', 'use the gcc_bin pytest fixture to parametrize tests with available GCC binaries', 'create a pytest fixture that yields an MlirEnv instance via gym.make mlir-v0', 'create a function that reads a file line by line and yields stripped non-empty lines', 'test the pytest observation_space fixture that parametrizes over MLIR observation space names', 'test the pytest reward_space fixture that parametrizes over MLIR reward space names', 'test the pytest dataset fixture that returns a Dataset by name from the MLIR environment', 'run a random trajectory of actions on a CompilerEnv and return the resulting trajectory', 'test the apply_random_trajectory function by running random actions on a CompilerEnv instance', 'review the apply_random_trajectory function that samples random actions and steps through a CompilerEnv', 'refactor apply_random_trajectory to support a custom action sampling strategy instead of random', 'summarize the apply_random_trajectory function that evaluates random action sequences with optional timeout']
```

Usage

```
{'run_random_trajectory': 'run a random trajectory of actions on a CompilerEnv and return the resulting trajectory', 'test_apply_random_trajectory': 'test the apply_random_trajectory function by running random actions on a CompilerEnv instance', 'review_apply_random_trajectory': 'review the apply_random_trajectory function that samples random actions and steps through a CompilerEnv', 'refactor_apply_random_trajectory': 'refactor apply_random_trajectory to support a custom action sampling strategy instead of random', 'summarize_apply_random_trajectory': 'summarize the apply_random_trajectory function that evaluates random action sequences with optional timeout'}
```

