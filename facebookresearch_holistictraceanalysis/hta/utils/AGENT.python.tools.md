# Agent Python Tools

- repo: facebookresearch/holistictraceanalysis
- repo_uri: https://github.com/facebookresearch/holistictraceanalysis

## File: facebookresearch_holistictraceanalysis/hta/utils/checker.py

Prompts

```
['check if a given path is a valid readable directory and return an OperationOutcome', 'check if a given path is a valid directory that is also writable', 'validate a directory path exists and is readable before performing file operations', 'create an OperationOutcome dataclass instance with a success boolean and reason string', 'review the is_valid_directory function to understand its path validation logic and edge cases', 'get the absolute path to the test data directory with optional subdirectory components', 'get the test data directory path for a specific subdirectory like vision_transformer', 'create a parameterized unit test using the data_provider decorator with a dataset function', 'use the data_provider decorator with an inline lambda to provide test data tuples', 'review the data_provider decorator to understand how it unpacks dict and tuple test data', 'classify a GPU kernel name as communication, memory, computation, or other using get_kernel_type', 'merge overlapping kernel intervals in a pandas DataFrame to produce non-overlapping time ranges', 'shorten a long CUDA kernel or CPU operator name by stripping template and function arguments', 'estimate the optimal multiprocessing pool size based on object size and available system memory', 'extract a value from a nested dictionary using dot-notation keys like a.b.c with a default fallback', 'run the validate_trace CLI to validate a trace file at minimal, standard, or complete level', 'validate a trace file format against expected argument specs and return errors', 'get the list of AttributeSpec for a given validation level like minimal or complete', 'extract expected arguments as a pandas DataFrame from a list of AttributeSpec objects', 'check trace event arguments against expected types and collect skipped or type-violating keys']
```

Usage

```
{'check_directory_exists': 'check if a given path is a valid readable directory and return an OperationOutcome', 'check_directory_writable': 'check if a given path is a valid directory that is also writable', 'validate_path_before_use': 'validate a directory path exists and is readable before performing file operations', 'create_OperationOutcome': 'create an OperationOutcome dataclass instance with a success boolean and reason string', 'review_is_valid_directory': 'review the is_valid_directory function to understand its path validation logic and edge cases'}
```

## File: facebookresearch_holistictraceanalysis/hta/utils/test_utils.py

Prompts

```
['check if a given path is a valid readable directory and return an OperationOutcome', 'check if a given path is a valid directory that is also writable', 'validate a directory path exists and is readable before performing file operations', 'create an OperationOutcome dataclass instance with a success boolean and reason string', 'review the is_valid_directory function to understand its path validation logic and edge cases', 'get the absolute path to the test data directory with optional subdirectory components', 'get the test data directory path for a specific subdirectory like vision_transformer', 'create a parameterized unit test using the data_provider decorator with a dataset function', 'use the data_provider decorator with an inline lambda to provide test data tuples', 'review the data_provider decorator to understand how it unpacks dict and tuple test data', 'classify a GPU kernel name as communication, memory, computation, or other using get_kernel_type', 'merge overlapping kernel intervals in a pandas DataFrame to produce non-overlapping time ranges', 'shorten a long CUDA kernel or CPU operator name by stripping template and function arguments', 'estimate the optimal multiprocessing pool size based on object size and available system memory', 'extract a value from a nested dictionary using dot-notation keys like a.b.c with a default fallback', 'run the validate_trace CLI to validate a trace file at minimal, standard, or complete level', 'validate a trace file format against expected argument specs and return errors', 'get the list of AttributeSpec for a given validation level like minimal or complete', 'extract expected arguments as a pandas DataFrame from a list of AttributeSpec objects', 'check trace event arguments against expected types and collect skipped or type-violating keys']
```

Usage

```
{'get_test_data_dir': 'get the absolute path to the test data directory with optional subdirectory components', 'get_test_data_dir_subdir': 'get the test data directory path for a specific subdirectory like vision_transformer', 'data_provider_decorator': 'create a parameterized unit test using the data_provider decorator with a dataset function', 'data_provider_lambda': 'use the data_provider decorator with an inline lambda to provide test data tuples', 'review_data_provider': 'review the data_provider decorator to understand how it unpacks dict and tuple test data'}
```

## File: facebookresearch_holistictraceanalysis/hta/utils/utils.py

Prompts

```
['check if a given path is a valid readable directory and return an OperationOutcome', 'check if a given path is a valid directory that is also writable', 'validate a directory path exists and is readable before performing file operations', 'create an OperationOutcome dataclass instance with a success boolean and reason string', 'review the is_valid_directory function to understand its path validation logic and edge cases', 'get the absolute path to the test data directory with optional subdirectory components', 'get the test data directory path for a specific subdirectory like vision_transformer', 'create a parameterized unit test using the data_provider decorator with a dataset function', 'use the data_provider decorator with an inline lambda to provide test data tuples', 'review the data_provider decorator to understand how it unpacks dict and tuple test data', 'classify a GPU kernel name as communication, memory, computation, or other using get_kernel_type', 'merge overlapping kernel intervals in a pandas DataFrame to produce non-overlapping time ranges', 'shorten a long CUDA kernel or CPU operator name by stripping template and function arguments', 'estimate the optimal multiprocessing pool size based on object size and available system memory', 'extract a value from a nested dictionary using dot-notation keys like a.b.c with a default fallback', 'run the validate_trace CLI to validate a trace file at minimal, standard, or complete level', 'validate a trace file format against expected argument specs and return errors', 'get the list of AttributeSpec for a given validation level like minimal or complete', 'extract expected arguments as a pandas DataFrame from a list of AttributeSpec objects', 'check trace event arguments against expected types and collect skipped or type-violating keys']
```

Usage

```
{'classify_gpu_kernel_type': 'classify a GPU kernel name as communication, memory, computation, or other using get_kernel_type', 'merge_kernel_intervals': 'merge overlapping kernel intervals in a pandas DataFrame to produce non-overlapping time ranges', 'shorten_kernel_name': 'shorten a long CUDA kernel or CPU operator name by stripping template and function arguments', 'estimate_multiprocessing_pool_size': 'estimate the optimal multiprocessing pool size based on object size and available system memory', 'extract_nested_dict_value': 'extract a value from a nested dictionary using dot-notation keys like a.b.c with a default fallback'}
```

## File: facebookresearch_holistictraceanalysis/hta/utils/validate_trace.py

Prompts

```
['check if a given path is a valid readable directory and return an OperationOutcome', 'check if a given path is a valid directory that is also writable', 'validate a directory path exists and is readable before performing file operations', 'create an OperationOutcome dataclass instance with a success boolean and reason string', 'review the is_valid_directory function to understand its path validation logic and edge cases', 'get the absolute path to the test data directory with optional subdirectory components', 'get the test data directory path for a specific subdirectory like vision_transformer', 'create a parameterized unit test using the data_provider decorator with a dataset function', 'use the data_provider decorator with an inline lambda to provide test data tuples', 'review the data_provider decorator to understand how it unpacks dict and tuple test data', 'classify a GPU kernel name as communication, memory, computation, or other using get_kernel_type', 'merge overlapping kernel intervals in a pandas DataFrame to produce non-overlapping time ranges', 'shorten a long CUDA kernel or CPU operator name by stripping template and function arguments', 'estimate the optimal multiprocessing pool size based on object size and available system memory', 'extract a value from a nested dictionary using dot-notation keys like a.b.c with a default fallback', 'run the validate_trace CLI to validate a trace file at minimal, standard, or complete level', 'validate a trace file format against expected argument specs and return errors', 'get the list of AttributeSpec for a given validation level like minimal or complete', 'extract expected arguments as a pandas DataFrame from a list of AttributeSpec objects', 'check trace event arguments against expected types and collect skipped or type-violating keys']
```

Usage

```
{'run_validate_trace': 'run the validate_trace CLI to validate a trace file at minimal, standard, or complete level', 'validate_trace_format': 'validate a trace file format against expected argument specs and return errors', 'get_argument_spec': 'get the list of AttributeSpec for a given validation level like minimal or complete', 'get_expected_arguments': 'extract expected arguments as a pandas DataFrame from a list of AttributeSpec objects', 'check_args': 'check trace event arguments against expected types and collect skipped or type-violating keys'}
```

