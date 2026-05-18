# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio_tests/tests/_loader.py

Prompts

```
['create a Loader instance and call loadTestsFromNames with a list of module names to build a test suite with coverage tracking', 'use the Loader walk_packages method to recursively discover and load tests from all modules in a package path', 'call visit_module on a Loader instance to add tests from a single module matching the _test regex pattern to the suite', 'use iterate_suite_cases to recursively yield all TestCase instances from a nested unittest TestSuite', 'review the Loader class which collects unittest tests from modules and packages while tracking code coverage', 'create a CaseResult namedtuple to store a single test case result with id, name, kind, and traceback', 'create an updated copy of a CaseResult by changing its kind, stdout, or stderr fields', 'build an AugmentedResult subclass of unittest.TestResult that tracks stdout and stderr per test case', 'summarize an AugmentedResult object into a human-readable string with test counts, tracebacks, and notes', 'build a Jenkins-compatible JUnit XML ElementTree from an AugmentedResult containing test case outcomes', 'run a unittest test suite with stdout stderr capture and JUnit XML report generation', 'create a CaptureFile context manager to redirect stdout or stderr to a temporary file', 'create an AugmentedCase namedtuple wrapping a TestCase with a unique UUID identifier', 'configure the Runner to skip specific tests by passing their ID patterns to skip_tests', 'use write_bypass on a CaptureFile to write directly to the original file descriptor', 'run sys_path_to_site_dir_hack to parse .pth files in the Bazel runtime environment', 'test sys_path_to_site_dir_hack to verify it adds valid sys.path items as site directories', 'review sys_path_to_site_dir_hack to understand the Bazel namespace package monkey patch', 'summarize sys_path_to_site_dir_hack which forces .pth file parsing for namespace packages in Bazel', 'refactor sys_path_to_site_dir_hack to improve how it filters existing sys.path entries']
```

Usage

```
{'load_tests_from_names': 'create a Loader instance and call loadTestsFromNames with a list of module names to build a test suite with coverage tracking', 'walk_packages': 'use the Loader walk_packages method to recursively discover and load tests from all modules in a package path', 'visit_module': 'call visit_module on a Loader instance to add tests from a single module matching the _test regex pattern to the suite', 'iterate_suite_cases': 'use iterate_suite_cases to recursively yield all TestCase instances from a nested unittest TestSuite', 'review_Loader_class': 'review the Loader class which collects unittest tests from modules and packages while tracking code coverage'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio_tests/tests/_result.py

Prompts

```
['create a Loader instance and call loadTestsFromNames with a list of module names to build a test suite with coverage tracking', 'use the Loader walk_packages method to recursively discover and load tests from all modules in a package path', 'call visit_module on a Loader instance to add tests from a single module matching the _test regex pattern to the suite', 'use iterate_suite_cases to recursively yield all TestCase instances from a nested unittest TestSuite', 'review the Loader class which collects unittest tests from modules and packages while tracking code coverage', 'create a CaseResult namedtuple to store a single test case result with id, name, kind, and traceback', 'create an updated copy of a CaseResult by changing its kind, stdout, or stderr fields', 'build an AugmentedResult subclass of unittest.TestResult that tracks stdout and stderr per test case', 'summarize an AugmentedResult object into a human-readable string with test counts, tracebacks, and notes', 'build a Jenkins-compatible JUnit XML ElementTree from an AugmentedResult containing test case outcomes', 'run a unittest test suite with stdout stderr capture and JUnit XML report generation', 'create a CaptureFile context manager to redirect stdout or stderr to a temporary file', 'create an AugmentedCase namedtuple wrapping a TestCase with a unique UUID identifier', 'configure the Runner to skip specific tests by passing their ID patterns to skip_tests', 'use write_bypass on a CaptureFile to write directly to the original file descriptor', 'run sys_path_to_site_dir_hack to parse .pth files in the Bazel runtime environment', 'test sys_path_to_site_dir_hack to verify it adds valid sys.path items as site directories', 'review sys_path_to_site_dir_hack to understand the Bazel namespace package monkey patch', 'summarize sys_path_to_site_dir_hack which forces .pth file parsing for namespace packages in Bazel', 'refactor sys_path_to_site_dir_hack to improve how it filters existing sys.path entries']
```

Usage

```
{'create_CaseResult': 'create a CaseResult namedtuple to store a single test case result with id, name, kind, and traceback', 'create_CaseResult_updated': 'create an updated copy of a CaseResult by changing its kind, stdout, or stderr fields', 'build_AugmentedResult': 'build an AugmentedResult subclass of unittest.TestResult that tracks stdout and stderr per test case', 'summarize_summary': 'summarize an AugmentedResult object into a human-readable string with test counts, tracebacks, and notes', 'build_jenkins_junit_xml': 'build a Jenkins-compatible JUnit XML ElementTree from an AugmentedResult containing test case outcomes'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio_tests/tests/_runner.py

Prompts

```
['create a Loader instance and call loadTestsFromNames with a list of module names to build a test suite with coverage tracking', 'use the Loader walk_packages method to recursively discover and load tests from all modules in a package path', 'call visit_module on a Loader instance to add tests from a single module matching the _test regex pattern to the suite', 'use iterate_suite_cases to recursively yield all TestCase instances from a nested unittest TestSuite', 'review the Loader class which collects unittest tests from modules and packages while tracking code coverage', 'create a CaseResult namedtuple to store a single test case result with id, name, kind, and traceback', 'create an updated copy of a CaseResult by changing its kind, stdout, or stderr fields', 'build an AugmentedResult subclass of unittest.TestResult that tracks stdout and stderr per test case', 'summarize an AugmentedResult object into a human-readable string with test counts, tracebacks, and notes', 'build a Jenkins-compatible JUnit XML ElementTree from an AugmentedResult containing test case outcomes', 'run a unittest test suite with stdout stderr capture and JUnit XML report generation', 'create a CaptureFile context manager to redirect stdout or stderr to a temporary file', 'create an AugmentedCase namedtuple wrapping a TestCase with a unique UUID identifier', 'configure the Runner to skip specific tests by passing their ID patterns to skip_tests', 'use write_bypass on a CaptureFile to write directly to the original file descriptor', 'run sys_path_to_site_dir_hack to parse .pth files in the Bazel runtime environment', 'test sys_path_to_site_dir_hack to verify it adds valid sys.path items as site directories', 'review sys_path_to_site_dir_hack to understand the Bazel namespace package monkey patch', 'summarize sys_path_to_site_dir_hack which forces .pth file parsing for namespace packages in Bazel', 'refactor sys_path_to_site_dir_hack to improve how it filters existing sys.path entries']
```

Usage

```
{'run_test_suite': 'run a unittest test suite with stdout stderr capture and JUnit XML report generation', 'capture_file_descriptor_output': 'create a CaptureFile context manager to redirect stdout or stderr to a temporary file', 'create_augmented_test_case': 'create an AugmentedCase namedtuple wrapping a TestCase with a unique UUID identifier', 'skip_tests_in_runner': 'configure the Runner to skip specific tests by passing their ID patterns to skip_tests', 'bypass_capture_write': 'use write_bypass on a CaptureFile to write directly to the original file descriptor'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio_tests/tests/bazel_namespace_package_hack.py

Prompts

```
['create a Loader instance and call loadTestsFromNames with a list of module names to build a test suite with coverage tracking', 'use the Loader walk_packages method to recursively discover and load tests from all modules in a package path', 'call visit_module on a Loader instance to add tests from a single module matching the _test regex pattern to the suite', 'use iterate_suite_cases to recursively yield all TestCase instances from a nested unittest TestSuite', 'review the Loader class which collects unittest tests from modules and packages while tracking code coverage', 'create a CaseResult namedtuple to store a single test case result with id, name, kind, and traceback', 'create an updated copy of a CaseResult by changing its kind, stdout, or stderr fields', 'build an AugmentedResult subclass of unittest.TestResult that tracks stdout and stderr per test case', 'summarize an AugmentedResult object into a human-readable string with test counts, tracebacks, and notes', 'build a Jenkins-compatible JUnit XML ElementTree from an AugmentedResult containing test case outcomes', 'run a unittest test suite with stdout stderr capture and JUnit XML report generation', 'create a CaptureFile context manager to redirect stdout or stderr to a temporary file', 'create an AugmentedCase namedtuple wrapping a TestCase with a unique UUID identifier', 'configure the Runner to skip specific tests by passing their ID patterns to skip_tests', 'use write_bypass on a CaptureFile to write directly to the original file descriptor', 'run sys_path_to_site_dir_hack to parse .pth files in the Bazel runtime environment', 'test sys_path_to_site_dir_hack to verify it adds valid sys.path items as site directories', 'review sys_path_to_site_dir_hack to understand the Bazel namespace package monkey patch', 'summarize sys_path_to_site_dir_hack which forces .pth file parsing for namespace packages in Bazel', 'refactor sys_path_to_site_dir_hack to improve how it filters existing sys.path entries']
```

Usage

```
{'run_sys_path_to_site_dir_hack': 'run sys_path_to_site_dir_hack to parse .pth files in the Bazel runtime environment', 'test_sys_path_to_site_dir_hack': 'test sys_path_to_site_dir_hack to verify it adds valid sys.path items as site directories', 'review_sys_path_to_site_dir_hack': 'review sys_path_to_site_dir_hack to understand the Bazel namespace package monkey patch', 'summarize_sys_path_to_site_dir_hack': 'summarize sys_path_to_site_dir_hack which forces .pth file parsing for namespace packages in Bazel', 'refactor_sys_path_to_site_dir_hack': 'refactor sys_path_to_site_dir_hack to improve how it filters existing sys.path entries'}
```

