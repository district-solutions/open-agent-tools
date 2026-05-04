# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/gmock_doctor.py

Prompts

```
['pipe compiler error messages to gmock_doctor.py via stdin to diagnose Google Mock usage problems', 'call Diagnose() with a compiler error message string to get human-readable diagnoses of Google Mock issues', 'use _NeedToReturnReferenceDiagnoser to detect when Return() should be replaced with ReturnRef() for reference return types', 'use _NeedToReturnSomethingDiagnoser to detect when a void-returning action is used where a value is expected', 'use _NeedToUseSymbolDiagnoser to detect when a Google Mock symbol is used without the testing namespace prefix']
```

Usage

```
{'run_gmock_doctor': 'pipe compiler error messages to gmock_doctor.py via stdin to diagnose Google Mock usage problems', 'diagnose_compiler_errors': 'call Diagnose() with a compiler error message string to get human-readable diagnoses of Google Mock issues', 'check_need_to_return_reference': 'use _NeedToReturnReferenceDiagnoser to detect when Return() should be replaced with ReturnRef() for reference return types', 'check_need_to_return_something': 'use _NeedToReturnSomethingDiagnoser to detect when a void-returning action is used where a value is expected', 'check_undeclared_gmock_symbol': 'use _NeedToUseSymbolDiagnoser to detect when a Google Mock symbol is used without the testing namespace prefix'}
```

