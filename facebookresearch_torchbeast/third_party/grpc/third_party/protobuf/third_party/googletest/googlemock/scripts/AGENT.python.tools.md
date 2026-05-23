# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/gmock_doctor.py

Prompts

```
['pipe compiler error messages to gmock_doctor.py via stdin to diagnose Google Mock usage problems', 'call Diagnose(msg) with a compiler error string to get plain English diagnoses for Google Mock issues', 'use _NeedToReturnReferenceDiagnoser to detect when Return() should be replaced with ReturnRef() for reference returns', 'use _NeedToReturnSomethingDiagnoser to detect when a void action is used but a return value is required', 'use _NeedToUseSymbolDiagnoser to detect when a Google Mock symbol needs the testing:: namespace prefix']
```

Usage

```
{'run_gmock_doctor': 'pipe compiler error messages to gmock_doctor.py via stdin to diagnose Google Mock usage problems', 'diagnose_compiler_errors': 'call Diagnose(msg) with a compiler error string to get plain English diagnoses for Google Mock issues', 'check_need_to_return_reference': 'use _NeedToReturnReferenceDiagnoser to detect when Return() should be replaced with ReturnRef() for reference returns', 'check_need_to_return_something': 'use _NeedToReturnSomethingDiagnoser to detect when a void action is used but a return value is required', 'check_undeclared_gmock_symbol': 'use _NeedToUseSymbolDiagnoser to detect when a Google Mock symbol needs the testing:: namespace prefix'}
```

