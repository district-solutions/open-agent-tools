# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/_loader.py

Prompts

```
['run the Loader class to load tests from a list of module names with coverage tracking', 'run the Loader walk_packages method to discover and load tests from package paths', 'run the Loader visit_module method to add tests from a module matching the _test suffix pattern', 'run the iterate_suite_cases generator to recursively yield all TestCase instances from a TestSuite', 'review the Loader class for custom unittest test discovery with coverage integration and module pattern matching', 'create a CaseResult namedtuple to store a single test case result with id, name, kind, and traceback', 'build an updated CaseResult by calling the updated method to change the kind or add a traceback', 'test the AugmentedResult class to track stdout and stderr output for each unittest test case', 'summarize an AugmentedResult object into a human-readable string with test counts, tracebacks, and unexpected successes', 'run jenkins_junit_xml to generate a Jenkins-compatible JUnit XML ElementTree from an AugmentedResult object', 'run a unittest test suite using the Runner class with optional dedicated threads', 'capture stdout or stderr output by using CaptureFile as a context manager', 'retrieve captured output bytes from a CaptureFile instance after redirection', 'create an AugmentedCase wrapping a TestCase with a guaranteed unique UUID identifier', 'skip specific tests in the Runner by calling skip_tests with a list of test IDs', 'run sys_path_to_site_dir_hack to parse .pth files in the Bazel runtime environment', 'review sys_path_to_site_dir_hack to understand how it patches Bazel namespace package resolution', 'summarize sys_path_to_site_dir_hack which adds sys.path items as site directories for .pth parsing', 'test sys_path_to_site_dir_hack to verify it only runs when GRPC_BAZEL_RUNTIME env var is set', 'refactor sys_path_to_site_dir_hack to use list comprehension instead of a manual loop']
```

Usage

```
{'run_loader_loadTestsFromNames': 'run the Loader class to load tests from a list of module names with coverage tracking', 'run_loader_walk_packages': 'run the Loader walk_packages method to discover and load tests from package paths', 'run_loader_visit_module': 'run the Loader visit_module method to add tests from a module matching the _test suffix pattern', 'run_iterate_suite_cases': 'run the iterate_suite_cases generator to recursively yield all TestCase instances from a TestSuite', 'review_Loader_class': 'review the Loader class for custom unittest test discovery with coverage integration and module pattern matching'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/_result.py

Prompts

```
['run the Loader class to load tests from a list of module names with coverage tracking', 'run the Loader walk_packages method to discover and load tests from package paths', 'run the Loader visit_module method to add tests from a module matching the _test suffix pattern', 'run the iterate_suite_cases generator to recursively yield all TestCase instances from a TestSuite', 'review the Loader class for custom unittest test discovery with coverage integration and module pattern matching', 'create a CaseResult namedtuple to store a single test case result with id, name, kind, and traceback', 'build an updated CaseResult by calling the updated method to change the kind or add a traceback', 'test the AugmentedResult class to track stdout and stderr output for each unittest test case', 'summarize an AugmentedResult object into a human-readable string with test counts, tracebacks, and unexpected successes', 'run jenkins_junit_xml to generate a Jenkins-compatible JUnit XML ElementTree from an AugmentedResult object', 'run a unittest test suite using the Runner class with optional dedicated threads', 'capture stdout or stderr output by using CaptureFile as a context manager', 'retrieve captured output bytes from a CaptureFile instance after redirection', 'create an AugmentedCase wrapping a TestCase with a guaranteed unique UUID identifier', 'skip specific tests in the Runner by calling skip_tests with a list of test IDs', 'run sys_path_to_site_dir_hack to parse .pth files in the Bazel runtime environment', 'review sys_path_to_site_dir_hack to understand how it patches Bazel namespace package resolution', 'summarize sys_path_to_site_dir_hack which adds sys.path items as site directories for .pth parsing', 'test sys_path_to_site_dir_hack to verify it only runs when GRPC_BAZEL_RUNTIME env var is set', 'refactor sys_path_to_site_dir_hack to use list comprehension instead of a manual loop']
```

Usage

```
{'create_CaseResult': 'create a CaseResult namedtuple to store a single test case result with id, name, kind, and traceback', 'build_CaseResult_updated': 'build an updated CaseResult by calling the updated method to change the kind or add a traceback', 'test_AugmentedResult': 'test the AugmentedResult class to track stdout and stderr output for each unittest test case', 'summarize_summary': 'summarize an AugmentedResult object into a human-readable string with test counts, tracebacks, and unexpected successes', 'run_jenkins_junit_xml': 'run jenkins_junit_xml to generate a Jenkins-compatible JUnit XML ElementTree from an AugmentedResult object'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/_runner.py

Prompts

```
['run the Loader class to load tests from a list of module names with coverage tracking', 'run the Loader walk_packages method to discover and load tests from package paths', 'run the Loader visit_module method to add tests from a module matching the _test suffix pattern', 'run the iterate_suite_cases generator to recursively yield all TestCase instances from a TestSuite', 'review the Loader class for custom unittest test discovery with coverage integration and module pattern matching', 'create a CaseResult namedtuple to store a single test case result with id, name, kind, and traceback', 'build an updated CaseResult by calling the updated method to change the kind or add a traceback', 'test the AugmentedResult class to track stdout and stderr output for each unittest test case', 'summarize an AugmentedResult object into a human-readable string with test counts, tracebacks, and unexpected successes', 'run jenkins_junit_xml to generate a Jenkins-compatible JUnit XML ElementTree from an AugmentedResult object', 'run a unittest test suite using the Runner class with optional dedicated threads', 'capture stdout or stderr output by using CaptureFile as a context manager', 'retrieve captured output bytes from a CaptureFile instance after redirection', 'create an AugmentedCase wrapping a TestCase with a guaranteed unique UUID identifier', 'skip specific tests in the Runner by calling skip_tests with a list of test IDs', 'run sys_path_to_site_dir_hack to parse .pth files in the Bazel runtime environment', 'review sys_path_to_site_dir_hack to understand how it patches Bazel namespace package resolution', 'summarize sys_path_to_site_dir_hack which adds sys.path items as site directories for .pth parsing', 'test sys_path_to_site_dir_hack to verify it only runs when GRPC_BAZEL_RUNTIME env var is set', 'refactor sys_path_to_site_dir_hack to use list comprehension instead of a manual loop']
```

Usage

```
{'run_test_suite_with_runner': 'run a unittest test suite using the Runner class with optional dedicated threads', 'capture_stdout_stderr_with_capturefile': 'capture stdout or stderr output by using CaptureFile as a context manager', 'retrieve_captured_output_bytes': 'retrieve captured output bytes from a CaptureFile instance after redirection', 'create_augmented_case_with_uuid': 'create an AugmentedCase wrapping a TestCase with a guaranteed unique UUID identifier', 'skip_tests_in_runner': 'skip specific tests in the Runner by calling skip_tests with a list of test IDs'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/bazel_namespace_package_hack.py

Prompts

```
['run the Loader class to load tests from a list of module names with coverage tracking', 'run the Loader walk_packages method to discover and load tests from package paths', 'run the Loader visit_module method to add tests from a module matching the _test suffix pattern', 'run the iterate_suite_cases generator to recursively yield all TestCase instances from a TestSuite', 'review the Loader class for custom unittest test discovery with coverage integration and module pattern matching', 'create a CaseResult namedtuple to store a single test case result with id, name, kind, and traceback', 'build an updated CaseResult by calling the updated method to change the kind or add a traceback', 'test the AugmentedResult class to track stdout and stderr output for each unittest test case', 'summarize an AugmentedResult object into a human-readable string with test counts, tracebacks, and unexpected successes', 'run jenkins_junit_xml to generate a Jenkins-compatible JUnit XML ElementTree from an AugmentedResult object', 'run a unittest test suite using the Runner class with optional dedicated threads', 'capture stdout or stderr output by using CaptureFile as a context manager', 'retrieve captured output bytes from a CaptureFile instance after redirection', 'create an AugmentedCase wrapping a TestCase with a guaranteed unique UUID identifier', 'skip specific tests in the Runner by calling skip_tests with a list of test IDs', 'run sys_path_to_site_dir_hack to parse .pth files in the Bazel runtime environment', 'review sys_path_to_site_dir_hack to understand how it patches Bazel namespace package resolution', 'summarize sys_path_to_site_dir_hack which adds sys.path items as site directories for .pth parsing', 'test sys_path_to_site_dir_hack to verify it only runs when GRPC_BAZEL_RUNTIME env var is set', 'refactor sys_path_to_site_dir_hack to use list comprehension instead of a manual loop']
```

Usage

```
{'run_sys_path_to_site_dir_hack': 'run sys_path_to_site_dir_hack to parse .pth files in the Bazel runtime environment', 'review_sys_path_to_site_dir_hack': 'review sys_path_to_site_dir_hack to understand how it patches Bazel namespace package resolution', 'summarize_sys_path_to_site_dir_hack': 'summarize sys_path_to_site_dir_hack which adds sys.path items as site directories for .pth parsing', 'test_sys_path_to_site_dir_hack': 'test sys_path_to_site_dir_hack to verify it only runs when GRPC_BAZEL_RUNTIME env var is set', 'refactor_sys_path_to_site_dir_hack': 'refactor sys_path_to_site_dir_hack to use list comprehension instead of a manual loop'}
```

