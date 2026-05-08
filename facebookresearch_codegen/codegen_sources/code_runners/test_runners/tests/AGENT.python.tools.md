# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/code_runners/test_runners/tests/test_cpp_test_runner.py

Prompts

```
['run CppEvosuiteTestRunner to compile and execute a C++ function against a GoogleTest test suite', 'test a correct C++ sigmoid function and verify all tests pass with zero failures', 'test a C++ function with a missing semicolon and verify it returns a compilation error', 'test a C++ function that sleeps longer than the timeout and verify it returns a timeout result', 'test that CppEvosuiteTestRunner sandbox prevents generated C++ code from writing files to disk', 'run Python unit tests against a generated function using PythonEvosuiteTestRunner and get pass or failure results', 'test a Python function with a custom timeout using PythonEvosuiteTestRunner to detect hanging code', 'test that PythonEvosuiteTestRunner sandbox prevents generated code from writing files to disk', 'tokenize Python source code using LangProcessor for python to normalize whitespace and structure', 'evaluate Python test output to extract success status, number of tests run, and number of failures']
```

Usage

```
{'run_cpp_tests_with_runner': 'run CppEvosuiteTestRunner to compile and execute a C++ function against a GoogleTest test suite', 'test_cpp_function_success': 'test a correct C++ sigmoid function and verify all tests pass with zero failures', 'test_cpp_compilation_error': 'test a C++ function with a missing semicolon and verify it returns a compilation error', 'test_cpp_timeout': 'test a C++ function that sleeps longer than the timeout and verify it returns a timeout result', 'test_cpp_sandbox_firejail': 'test that CppEvosuiteTestRunner sandbox prevents generated C++ code from writing files to disk'}
```

## File: facebookresearch_codegen/codegen_sources/code_runners/test_runners/tests/test_python_test_runner.py

Prompts

```
['run CppEvosuiteTestRunner to compile and execute a C++ function against a GoogleTest test suite', 'test a correct C++ sigmoid function and verify all tests pass with zero failures', 'test a C++ function with a missing semicolon and verify it returns a compilation error', 'test a C++ function that sleeps longer than the timeout and verify it returns a timeout result', 'test that CppEvosuiteTestRunner sandbox prevents generated C++ code from writing files to disk', 'run Python unit tests against a generated function using PythonEvosuiteTestRunner and get pass or failure results', 'test a Python function with a custom timeout using PythonEvosuiteTestRunner to detect hanging code', 'test that PythonEvosuiteTestRunner sandbox prevents generated code from writing files to disk', 'tokenize Python source code using LangProcessor for python to normalize whitespace and structure', 'evaluate Python test output to extract success status, number of tests run, and number of failures']
```

Usage

```
{'run_python_unit_tests': 'run Python unit tests against a generated function using PythonEvosuiteTestRunner and get pass or failure results', 'test_python_function_with_timeout': 'test a Python function with a custom timeout using PythonEvosuiteTestRunner to detect hanging code', 'test_python_sandbox_firejail': 'test that PythonEvosuiteTestRunner sandbox prevents generated code from writing files to disk', 'tokenize_python_code': 'tokenize Python source code using LangProcessor for python to normalize whitespace and structure', 'eval_python_test_results': 'evaluate Python test output to extract success status, number of tests run, and number of failures'}
```

