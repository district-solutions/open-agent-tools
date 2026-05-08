# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/code_runners/test_runners/evosuite_test_runners/python_evosuite_test_runner.py

Prompts

```
['run Python unit tests by filling a #TOFILL placeholder in test code with a function and executing it', 'create a PythonEvosuiteTestRunner instance with a custom tmp_folder, timeout, and number of subfolders', 'evaluate Python test runner stdout and stderr to parse success, failure, or error counts', 'initialize the Python test runner environment by prepending the Python executable path to PATH', 'run a test file where a function replaces the #TOFILL marker and return output, error, and exit code']
```

Usage

```
{'run_python_evosuite_tests': 'run Python unit tests by filling a #TOFILL placeholder in test code with a function and executing it', 'create_test_runner_instance': 'create a PythonEvosuiteTestRunner instance with a custom tmp_folder, timeout, and number of subfolders', 'evaluate_test_output': 'evaluate Python test runner stdout and stderr to parse success, failure, or error counts', 'initialize_test_environment': 'initialize the Python test runner environment by prepending the Python executable path to PATH', 'run_filled_test_file': 'run a test file where a function replaces the #TOFILL marker and return output, error, and exit code'}
```

