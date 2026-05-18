# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/mvfst/build/fbcode_builder_config.py

Prompts

```
['build mvfst using fbcode_builder with cmake and ctest for running tests', 'configure cmake defines to disable shared libs and enable tests for mvfst', 'run mvfst tests using ctest with parallelism and output on failure', 'add gmock, fmt, folly, and fizz as build dependencies for mvfst', 'setup the fbcode_builder spec function to define build steps and dependencies for mvfst']
```

Usage

```
{'build_mvfst_with_cmake': 'build mvfst using fbcode_builder with cmake and ctest for running tests', 'configure_cmake_defines': 'configure cmake defines to disable shared libs and enable tests for mvfst', 'run_mvfst_tests': 'run mvfst tests using ctest with parallelism and output on failure', 'add_build_dependencies': 'add gmock, fmt, folly, and fizz as build dependencies for mvfst', 'setup_fbcode_builder_spec': 'setup the fbcode_builder spec function to define build steps and dependencies for mvfst'}
```

