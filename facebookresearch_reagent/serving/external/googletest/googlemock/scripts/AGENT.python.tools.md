# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/serving/external/googletest/googlemock/scripts/gmock_doctor.py

Prompts

```
['pipe compiler error messages to gmock_doctor.py on stdin to diagnose Google Mock usage problems', 'call Diagnose with a compiler error message string to get plain English diagnoses for Google Mock issues', 'review the 13 diagnoser functions like _NeedToReturnReferenceDiagnoser that pattern match GCC and Clang error output', 'review the _GenericDiagnoser function that yields diagnosis tuples by matching regex patterns against compiler messages', 'review the _COMMON_GMOCK_SYMBOLS list containing matchers, actions, cardinalities, and misc Google Mock symbols']
```

Usage

```
{'run_gmock_doctor': 'pipe compiler error messages to gmock_doctor.py on stdin to diagnose Google Mock usage problems', 'diagnose_compiler_errors': 'call Diagnose with a compiler error message string to get plain English diagnoses for Google Mock issues', 'review_diagnoser_functions': 'review the 13 diagnoser functions like _NeedToReturnReferenceDiagnoser that pattern match GCC and Clang error output', 'review_generic_diagnoser': 'review the _GenericDiagnoser function that yields diagnosis tuples by matching regex patterns against compiler messages', 'review_common_gmock_symbols': 'review the _COMMON_GMOCK_SYMBOLS list containing matchers, actions, cardinalities, and misc Google Mock symbols'}
```

