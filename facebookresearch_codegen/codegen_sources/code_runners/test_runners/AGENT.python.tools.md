# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/code_runners/test_runners/unittest_runner.py

Prompts

```
['run unit tests for a function and test string, returning success status and failure count', 'create a UnitTestRunner subclass that implements _run_tests and _eval_proc_state for a new language', 'evaluate process stdout and stderr output to parse test success, total tests, and number of failures', 'handle MissingTest, InvalidTest, CompilationError, and Timeout exceptions when running tests and return error tuples', 'run EvoSuite-generated unit tests for Python or C++ functions by filling #TOFILL placeholders with generated code']
```

Usage

```
{'run_unit_tests': 'run unit tests for a function and test string, returning success status and failure count', 'create_unittest_runner': 'create a UnitTestRunner subclass that implements _run_tests and _eval_proc_state for a new language', 'evaluate_test_results': 'evaluate process stdout and stderr output to parse test success, total tests, and number of failures', 'handle_test_errors': 'handle MissingTest, InvalidTest, CompilationError, and Timeout exceptions when running tests and return error tuples', 'run_evosuite_tests': 'run EvoSuite-generated unit tests for Python or C++ functions by filling #TOFILL placeholders with generated code'}
```

