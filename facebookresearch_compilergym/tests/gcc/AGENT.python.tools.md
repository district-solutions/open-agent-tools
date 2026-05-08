# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/tests/gcc/gcc_bin_test.py

Prompts

```
['test that gym.make raises ServiceError when gcc_bin points to a nonexistent file', 'test that gym.make raises ServiceError when gcc_bin is set to the shell false command', 'test that gym.make with gcc_bin gcc creates an env where compiler_version contains gcc', 'test that gym.make raises ServiceError when gcc_bin is gcc but no system gcc is installed', 'run all GCC binary validation tests using pytest against the CompilerGym gcc-v0 environment', 'test that gym.make gcc-v0 raises ServiceError when given an invalid Docker image name', 'test that gcc-v0 environment reports compiler version 11.2.0 when using Docker image gcc:11.2.0', 'test gcc-v0 environment with Docker image gcc:10.3.0 using full, partial, and major version tags', 'test gcc-v0 environment with Docker image gcc:9.4.0 using full, partial, and major version tags', 'test gcc-v0 environment with Docker image gcc:8.5.0 using full, partial, and major version tags', 'test the gcc-v0 environment default action space names and count', 'test the gcc-v0 environment observation spaces including asm obj rtl and source', 'test the gcc-v0 environment reward spaces for asm_size and obj_size', 'test forking a gcc-v0 environment to create an independent copy with shared actions', 'test compiling with different optimization flags like O0 O3 and finline in gcc-v0']
```

Usage

```
{'test_missing_gcc_bin': 'test that gym.make raises ServiceError when gcc_bin points to a nonexistent file', 'test_invalid_gcc_bin': 'test that gym.make raises ServiceError when gcc_bin is set to the shell false command', 'test_system_gcc': 'test that gym.make with gcc_bin gcc creates an env where compiler_version contains gcc', 'test_missing_system_gcc': 'test that gym.make raises ServiceError when gcc_bin is gcc but no system gcc is installed', 'run_gcc_bin_tests': 'run all GCC binary validation tests using pytest against the CompilerGym gcc-v0 environment'}
```

## File: facebookresearch_compilergym/tests/gcc/gcc_docker_test.py

Prompts

```
['test that gym.make raises ServiceError when gcc_bin points to a nonexistent file', 'test that gym.make raises ServiceError when gcc_bin is set to the shell false command', 'test that gym.make with gcc_bin gcc creates an env where compiler_version contains gcc', 'test that gym.make raises ServiceError when gcc_bin is gcc but no system gcc is installed', 'run all GCC binary validation tests using pytest against the CompilerGym gcc-v0 environment', 'test that gym.make gcc-v0 raises ServiceError when given an invalid Docker image name', 'test that gcc-v0 environment reports compiler version 11.2.0 when using Docker image gcc:11.2.0', 'test gcc-v0 environment with Docker image gcc:10.3.0 using full, partial, and major version tags', 'test gcc-v0 environment with Docker image gcc:9.4.0 using full, partial, and major version tags', 'test gcc-v0 environment with Docker image gcc:8.5.0 using full, partial, and major version tags', 'test the gcc-v0 environment default action space names and count', 'test the gcc-v0 environment observation spaces including asm obj rtl and source', 'test the gcc-v0 environment reward spaces for asm_size and obj_size', 'test forking a gcc-v0 environment to create an independent copy with shared actions', 'test compiling with different optimization flags like O0 O3 and finline in gcc-v0']
```

Usage

```
{'test_invalid_docker_image': 'test that gym.make gcc-v0 raises ServiceError when given an invalid Docker image name', 'test_version_11': 'test that gcc-v0 environment reports compiler version 11.2.0 when using Docker image gcc:11.2.0', 'test_version_10': 'test gcc-v0 environment with Docker image gcc:10.3.0 using full, partial, and major version tags', 'test_version_9': 'test gcc-v0 environment with Docker image gcc:9.4.0 using full, partial, and major version tags', 'test_version_8': 'test gcc-v0 environment with Docker image gcc:8.5.0 using full, partial, and major version tags'}
```

## File: facebookresearch_compilergym/tests/gcc/gcc_env_test.py

Prompts

```
['test that gym.make raises ServiceError when gcc_bin points to a nonexistent file', 'test that gym.make raises ServiceError when gcc_bin is set to the shell false command', 'test that gym.make with gcc_bin gcc creates an env where compiler_version contains gcc', 'test that gym.make raises ServiceError when gcc_bin is gcc but no system gcc is installed', 'run all GCC binary validation tests using pytest against the CompilerGym gcc-v0 environment', 'test that gym.make gcc-v0 raises ServiceError when given an invalid Docker image name', 'test that gcc-v0 environment reports compiler version 11.2.0 when using Docker image gcc:11.2.0', 'test gcc-v0 environment with Docker image gcc:10.3.0 using full, partial, and major version tags', 'test gcc-v0 environment with Docker image gcc:9.4.0 using full, partial, and major version tags', 'test gcc-v0 environment with Docker image gcc:8.5.0 using full, partial, and major version tags', 'test the gcc-v0 environment default action space names and count', 'test the gcc-v0 environment observation spaces including asm obj rtl and source', 'test the gcc-v0 environment reward spaces for asm_size and obj_size', 'test forking a gcc-v0 environment to create an independent copy with shared actions', 'test compiling with different optimization flags like O0 O3 and finline in gcc-v0']
```

Usage

```
{'test_gcc_env_action_spaces': 'test the gcc-v0 environment default action space names and count', 'test_gcc_env_observation_spaces': 'test the gcc-v0 environment observation spaces including asm obj rtl and source', 'test_gcc_env_reward_spaces': 'test the gcc-v0 environment reward spaces for asm_size and obj_size', 'test_gcc_env_fork': 'test forking a gcc-v0 environment to create an independent copy with shared actions', 'test_gcc_env_compile': 'test compiling with different optimization flags like O0 O3 and finline in gcc-v0'}
```

