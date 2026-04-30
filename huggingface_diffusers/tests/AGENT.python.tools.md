# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/conftest.py

Prompts

```
['configure pytest to register custom markers like lora, quantization, and slow for test categorization', 'add custom pytest command-line options by delegating to the shared testing utilities parser', 'generate test summary reports at the end of pytest runs using the make-reports option', 'insert the diffusers source path into sys.path so tests can import from the local checkout', 'configure warnings to ignore FutureWarning during test execution to avoid noisy output', 'assert two PyTorch tensors are close within given absolute and relative tolerances', 'decorate a flaky test function to retry up to five times on failure', 'run a test function in a subprocess to avoid GPU memory leaks', 'use the CaptureLogger context manager to capture and inspect logging output from a logger', 'create device-aware test expectations that match against cuda, rocm, or xpu properties']
```

Usage

```
{'configure_pytest_markers': 'configure pytest to register custom markers like lora, quantization, and slow for test categorization', 'add_pytest_options': 'add custom pytest command-line options by delegating to the shared testing utilities parser', 'generate_terminal_reports': 'generate test summary reports at the end of pytest runs using the make-reports option', 'setup_sys_path_for_tests': 'insert the diffusers source path into sys.path so tests can import from the local checkout', 'suppress_future_warnings': 'configure warnings to ignore FutureWarning during test execution to avoid noisy output'}
```

## File: huggingface_diffusers/tests/testing_utils.py

Prompts

```
['configure pytest to register custom markers like lora, quantization, and slow for test categorization', 'add custom pytest command-line options by delegating to the shared testing utilities parser', 'generate test summary reports at the end of pytest runs using the make-reports option', 'insert the diffusers source path into sys.path so tests can import from the local checkout', 'configure warnings to ignore FutureWarning during test execution to avoid noisy output', 'assert two PyTorch tensors are close within given absolute and relative tolerances', 'decorate a flaky test function to retry up to five times on failure', 'run a test function in a subprocess to avoid GPU memory leaks', 'use the CaptureLogger context manager to capture and inspect logging output from a logger', 'create device-aware test expectations that match against cuda, rocm, or xpu properties']
```

Usage

```
{'test_assert_tensors_close': 'assert two PyTorch tensors are close within given absolute and relative tolerances', 'test_is_flaky_decorator': 'decorate a flaky test function to retry up to five times on failure', 'run_test_in_subprocess': 'run a test function in a subprocess to avoid GPU memory leaks', 'review_CaptureLogger_class': 'use the CaptureLogger context manager to capture and inspect logging output from a logger', 'test_Expectations_class': 'create device-aware test expectations that match against cuda, rocm, or xpu properties'}
```

