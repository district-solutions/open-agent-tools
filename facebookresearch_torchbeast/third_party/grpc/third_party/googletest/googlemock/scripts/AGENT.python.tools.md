# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/googletest/googlemock/scripts/gmock_doctor.py

Prompts

```
['pipe compiler error messages to gmock_doctor.py on stdin to get plain English diagnoses of Google Mock usage problems', 'call Diagnose(msg) with a compiler error message string to get a list of possible Google Mock disease diagnoses', 'call _GenericDiagnoser with a short name, long name, list of regex-diagnosis pairs, and error message to pattern-match and yield diagnoses', 'call _NeedToReturnReferenceDiagnoser(msg) to detect when Return() is used instead of ReturnRef() for reference-returning functions', 'call _NeedToReturnSomethingDiagnoser(msg) to detect when a void-returning action is used but a non-void return type is expected']
```

Usage

```
{'diagnose_gmock_compiler_errors': 'pipe compiler error messages to gmock_doctor.py on stdin to get plain English diagnoses of Google Mock usage problems', 'run_diagnose_function': 'call Diagnose(msg) with a compiler error message string to get a list of possible Google Mock disease diagnoses', 'use_generic_diagnoser': 'call _GenericDiagnoser with a short name, long name, list of regex-diagnosis pairs, and error message to pattern-match and yield diagnoses', 'check_need_return_reference': 'call _NeedToReturnReferenceDiagnoser(msg) to detect when Return() is used instead of ReturnRef() for reference-returning functions', 'check_need_return_something': 'call _NeedToReturnSomethingDiagnoser(msg) to detect when a void-returning action is used but a non-void return type is expected'}
```

