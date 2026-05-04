# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/manipulation/run_tests.py

Prompts

```
['run all manipulation test files in a directory by passing the directory path as an argument', 'find all test files ending in test.py within a given directory tree excluding build and venv paths', 'convert a file path like dir/file.py into a Python module name like dm_robotics.manipulation.dir.file', 'run a single test module by name using subprocess and return whether it passed', 'review the manual test runner that isolates each test in a separate process to avoid global state issues']
```

Usage

```
{'run_manipulation_tests': 'run all manipulation test files in a directory by passing the directory path as an argument', 'find_test_files': 'find all test files ending in test.py within a given directory tree excluding build and venv paths', 'convert_path_to_module': 'convert a file path like dir/file.py into a Python module name like dm_robotics.manipulation.dir.file', 'run_single_test_module': 'run a single test module by name using subprocess and return whether it passed', 'review_test_runner': 'review the manual test runner that isolates each test in a separate process to avoid global state issues'}
```

