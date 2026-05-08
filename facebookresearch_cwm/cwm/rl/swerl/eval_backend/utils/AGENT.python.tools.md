# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/rl/swerl/eval_backend/utils/grading.py

Prompts

```
['parse pytest log output and extract test case status map from the short summary lines', 'retrieve evaluation results and patch application status from a task instance log file', 'generate a report comparing evaluation results against gold results with fail-to-pass and pass-to-pass metrics', 'determine if a fix is fully resolved, partially resolved, or not resolved based on test metrics', 'generate a full evaluation report from a test spec, prediction, and log path with resolution status', 'parse a pytest test log string and return a dict mapping test case names to their pass or fail status', 'parse a pytest test log with bracketed options and return a dict mapping test names including options to their status', 'parse a Django test runner log string and return a dict mapping test names to passed, failed, skipped, or error status', 'parse a later version pytest log with ANSI escape codes and return a dict mapping test names to their status', 'parse a Sympy test log and return a dict mapping test file locations and test names to their pass, fail, or error status', 'parse a pytest log string and return a dictionary mapping test case names to their status', 'check if a specific test case passed by looking it up in the parsed test status map', 'check if a specific test case failed or errored by looking it up in the parsed test status map', 'review the parse_log function to understand how it extracts test case names and statuses from pytest output', 'summarize the TestStatus enum and its FAILED, PASSED, SKIPPED, and ERROR values']
```

Usage

```
{'parse_pytest_logs': 'parse pytest log output and extract test case status map from the short summary lines', 'get_logs_eval': 'retrieve evaluation results and patch application status from a task instance log file', 'get_eval_tests_report': 'generate a report comparing evaluation results against gold results with fail-to-pass and pass-to-pass metrics', 'get_resolution_status': 'determine if a fix is fully resolved, partially resolved, or not resolved based on test metrics', 'get_eval_report': 'generate a full evaluation report from a test spec, prediction, and log path with resolution status'}
```

## File: facebookresearch_cwm/cwm/rl/swerl/eval_backend/utils/log_parsers.py

Prompts

```
['parse pytest log output and extract test case status map from the short summary lines', 'retrieve evaluation results and patch application status from a task instance log file', 'generate a report comparing evaluation results against gold results with fail-to-pass and pass-to-pass metrics', 'determine if a fix is fully resolved, partially resolved, or not resolved based on test metrics', 'generate a full evaluation report from a test spec, prediction, and log path with resolution status', 'parse a pytest test log string and return a dict mapping test case names to their pass or fail status', 'parse a pytest test log with bracketed options and return a dict mapping test names including options to their status', 'parse a Django test runner log string and return a dict mapping test names to passed, failed, skipped, or error status', 'parse a later version pytest log with ANSI escape codes and return a dict mapping test names to their status', 'parse a Sympy test log and return a dict mapping test file locations and test names to their pass, fail, or error status', 'parse a pytest log string and return a dictionary mapping test case names to their status', 'check if a specific test case passed by looking it up in the parsed test status map', 'check if a specific test case failed or errored by looking it up in the parsed test status map', 'review the parse_log function to understand how it extracts test case names and statuses from pytest output', 'summarize the TestStatus enum and its FAILED, PASSED, SKIPPED, and ERROR values']
```

Usage

```
{'parse_log_pytest': 'parse a pytest test log string and return a dict mapping test case names to their pass or fail status', 'parse_log_pytest_options': 'parse a pytest test log with bracketed options and return a dict mapping test names including options to their status', 'parse_log_django': 'parse a Django test runner log string and return a dict mapping test names to passed, failed, skipped, or error status', 'parse_log_pytest_v2': 'parse a later version pytest log with ANSI escape codes and return a dict mapping test names to their status', 'parse_log_sympy': 'parse a Sympy test log and return a dict mapping test file locations and test names to their pass, fail, or error status'}
```

## File: facebookresearch_cwm/cwm/rl/swerl/eval_backend/utils/pytest_parser.py

Prompts

```
['parse pytest log output and extract test case status map from the short summary lines', 'retrieve evaluation results and patch application status from a task instance log file', 'generate a report comparing evaluation results against gold results with fail-to-pass and pass-to-pass metrics', 'determine if a fix is fully resolved, partially resolved, or not resolved based on test metrics', 'generate a full evaluation report from a test spec, prediction, and log path with resolution status', 'parse a pytest test log string and return a dict mapping test case names to their pass or fail status', 'parse a pytest test log with bracketed options and return a dict mapping test names including options to their status', 'parse a Django test runner log string and return a dict mapping test names to passed, failed, skipped, or error status', 'parse a later version pytest log with ANSI escape codes and return a dict mapping test names to their status', 'parse a Sympy test log and return a dict mapping test file locations and test names to their pass, fail, or error status', 'parse a pytest log string and return a dictionary mapping test case names to their status', 'check if a specific test case passed by looking it up in the parsed test status map', 'check if a specific test case failed or errored by looking it up in the parsed test status map', 'review the parse_log function to understand how it extracts test case names and statuses from pytest output', 'summarize the TestStatus enum and its FAILED, PASSED, SKIPPED, and ERROR values']
```

Usage

```
{'parse_log': 'parse a pytest log string and return a dictionary mapping test case names to their status', 'test_passed': 'check if a specific test case passed by looking it up in the parsed test status map', 'test_failed': 'check if a specific test case failed or errored by looking it up in the parsed test status map', 'review_parse_log': 'review the parse_log function to understand how it extracts test case names and statuses from pytest output', 'summarize_TestStatus': 'summarize the TestStatus enum and its FAILED, PASSED, SKIPPED, and ERROR values'}
```

