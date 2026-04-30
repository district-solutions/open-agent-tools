# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/test/ci/ci_register.py

Prompts

```
['collect and parse CI test registrations from a list of Python test files', 'auto partition CI test files across distributed workers using greedy load balancing', 'parse a single Python file and extract CI registry entries using AST analysis', 'register a CPU CI test with estimated time, suite name, nightly flag, and optional disabled reason', 'register a CUDA CI test with estimated time, suite name, nightly flag, and optional disabled reason', 'build a bench_serving stress test command for sglang with random prompts and output file', 'run a stress test command with a timeout and raise on failure', 'run a complete stress test for a model with server launch, execution, and cleanup', 'write the accumulated stress test report to GitHub summary in CI', 'get the accumulated markdown stress test report as a string', 'test the is_retriable_failure function to determine if a test failure output is retriable based on pattern matching', 'run a list of TestFile objects or CIRegistry entries with configurable timeout, retry, and continue-on-error behavior', 'run a callable function with a specified timeout, raising TimeoutError if it exceeds the limit', 'test the write_github_step_summary function to append content to the GitHub Step Summary file when available', 'test the run_unittest_files function with enable_retry=True to automatically retry accuracy or performance assertion failures']
```

Usage

```
{'collect_tests_parse_ci_registrations': 'collect and parse CI test registrations from a list of Python test files', 'auto_partition_tests_across_workers': 'auto partition CI test files across distributed workers using greedy load balancing', 'ut_parse_one_file_extract_registry': 'parse a single Python file and extract CI registry entries using AST analysis', 'register_cpu_ci_mark_test_for_cpu': 'register a CPU CI test with estimated time, suite name, nightly flag, and optional disabled reason', 'register_cuda_ci_mark_test_for_gpu': 'register a CUDA CI test with estimated time, suite name, nightly flag, and optional disabled reason'}
```

## File: sgl-project_sglang/python/sglang/test/ci/ci_stress_utils.py

Prompts

```
['collect and parse CI test registrations from a list of Python test files', 'auto partition CI test files across distributed workers using greedy load balancing', 'parse a single Python file and extract CI registry entries using AST analysis', 'register a CPU CI test with estimated time, suite name, nightly flag, and optional disabled reason', 'register a CUDA CI test with estimated time, suite name, nightly flag, and optional disabled reason', 'build a bench_serving stress test command for sglang with random prompts and output file', 'run a stress test command with a timeout and raise on failure', 'run a complete stress test for a model with server launch, execution, and cleanup', 'write the accumulated stress test report to GitHub summary in CI', 'get the accumulated markdown stress test report as a string', 'test the is_retriable_failure function to determine if a test failure output is retriable based on pattern matching', 'run a list of TestFile objects or CIRegistry entries with configurable timeout, retry, and continue-on-error behavior', 'run a callable function with a specified timeout, raising TimeoutError if it exceeds the limit', 'test the write_github_step_summary function to append content to the GitHub Step Summary file when available', 'test the run_unittest_files function with enable_retry=True to automatically retry accuracy or performance assertion failures']
```

Usage

```
{'build_stress_test_command': 'build a bench_serving stress test command for sglang with random prompts and output file', 'run_stress_test_command': 'run a stress test command with a timeout and raise on failure', 'run_stress_test_for_model': 'run a complete stress test for a model with server launch, execution, and cleanup', 'write_final_report': 'write the accumulated stress test report to GitHub summary in CI', 'get_full_report': 'get the accumulated markdown stress test report as a string'}
```

## File: sgl-project_sglang/python/sglang/test/ci/ci_utils.py

Prompts

```
['collect and parse CI test registrations from a list of Python test files', 'auto partition CI test files across distributed workers using greedy load balancing', 'parse a single Python file and extract CI registry entries using AST analysis', 'register a CPU CI test with estimated time, suite name, nightly flag, and optional disabled reason', 'register a CUDA CI test with estimated time, suite name, nightly flag, and optional disabled reason', 'build a bench_serving stress test command for sglang with random prompts and output file', 'run a stress test command with a timeout and raise on failure', 'run a complete stress test for a model with server launch, execution, and cleanup', 'write the accumulated stress test report to GitHub summary in CI', 'get the accumulated markdown stress test report as a string', 'test the is_retriable_failure function to determine if a test failure output is retriable based on pattern matching', 'run a list of TestFile objects or CIRegistry entries with configurable timeout, retry, and continue-on-error behavior', 'run a callable function with a specified timeout, raising TimeoutError if it exceeds the limit', 'test the write_github_step_summary function to append content to the GitHub Step Summary file when available', 'test the run_unittest_files function with enable_retry=True to automatically retry accuracy or performance assertion failures']
```

Usage

```
{'test_is_retriable_failure': 'test the is_retriable_failure function to determine if a test failure output is retriable based on pattern matching', 'run_unittest_files': 'run a list of TestFile objects or CIRegistry entries with configurable timeout, retry, and continue-on-error behavior', 'run_with_timeout': 'run a callable function with a specified timeout, raising TimeoutError if it exceeds the limit', 'test_write_github_step_summary': 'test the write_github_step_summary function to append content to the GitHub Step Summary file when available', 'test_run_unittest_files_retry': 'test the run_unittest_files function with enable_retry=True to automatically retry accuracy or performance assertion failures'}
```

