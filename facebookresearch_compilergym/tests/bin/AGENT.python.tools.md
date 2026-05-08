# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/tests/bin/manual_env_bin_test.py

Prompts

```
['test the CompilerGym manual_env shell by feeding input and validating output against regex patterns', 'test listing available compiler benchmarks in the CompilerGym manual environment shell', 'test listing available compiler optimization actions in the CompilerGym manual environment shell', 'test hill climbing optimization over compiler actions using the CompilerGym manual environment shell', 'test greedy optimization over compiler actions using the CompilerGym manual environment shell', 'test the print_service_capabilities function across all CompilerGym environments using pytest parametrization', 'run the smoke test that prints service capabilities for each registered CompilerGym environment', 'test creating a CompilerGym environment with gym.make and printing its service capabilities', 'test handling EnvironmentNotSupported exceptions when an environment is not available on the current platform', 'test initializing absl flags before running the service capabilities smoke test', 'test the validate main function with valid LLVM benchmark CSV input via stdin', 'test the validate main function with a CSV file path as input argument', 'test the validate main function exits with error when given empty stdin input', 'test the validate main function detects mismatched reward values in benchmark CSV results', 'test the validate main function rejects CSV input with wrong number of columns']
```

Usage

```
{'test_io_check': 'test the CompilerGym manual_env shell by feeding input and validating output against regex patterns', 'test_list_benchmarks': 'test listing available compiler benchmarks in the CompilerGym manual environment shell', 'test_list_actions': 'test listing available compiler optimization actions in the CompilerGym manual environment shell', 'test_hill_climb': 'test hill climbing optimization over compiler actions using the CompilerGym manual environment shell', 'test_greedy': 'test greedy optimization over compiler actions using the CompilerGym manual environment shell'}
```

## File: facebookresearch_compilergym/tests/bin/service_bin_test.py

Prompts

```
['test the CompilerGym manual_env shell by feeding input and validating output against regex patterns', 'test listing available compiler benchmarks in the CompilerGym manual environment shell', 'test listing available compiler optimization actions in the CompilerGym manual environment shell', 'test hill climbing optimization over compiler actions using the CompilerGym manual environment shell', 'test greedy optimization over compiler actions using the CompilerGym manual environment shell', 'test the print_service_capabilities function across all CompilerGym environments using pytest parametrization', 'run the smoke test that prints service capabilities for each registered CompilerGym environment', 'test creating a CompilerGym environment with gym.make and printing its service capabilities', 'test handling EnvironmentNotSupported exceptions when an environment is not available on the current platform', 'test initializing absl flags before running the service capabilities smoke test', 'test the validate main function with valid LLVM benchmark CSV input via stdin', 'test the validate main function with a CSV file path as input argument', 'test the validate main function exits with error when given empty stdin input', 'test the validate main function detects mismatched reward values in benchmark CSV results', 'test the validate main function rejects CSV input with wrong number of columns']
```

Usage

```
{'test_print_service_capabilities_smoke_test': 'test the print_service_capabilities function across all CompilerGym environments using pytest parametrization', 'run_service_capabilities_test': 'run the smoke test that prints service capabilities for each registered CompilerGym environment', 'test_gym_make_env': 'test creating a CompilerGym environment with gym.make and printing its service capabilities', 'test_environment_not_supported_handling': 'test handling EnvironmentNotSupported exceptions when an environment is not available on the current platform', 'test_absl_flags_initialization': 'test initializing absl flags before running the service capabilities smoke test'}
```

## File: facebookresearch_compilergym/tests/bin/validate_bin_test.py

Prompts

```
['test the CompilerGym manual_env shell by feeding input and validating output against regex patterns', 'test listing available compiler benchmarks in the CompilerGym manual environment shell', 'test listing available compiler optimization actions in the CompilerGym manual environment shell', 'test hill climbing optimization over compiler actions using the CompilerGym manual environment shell', 'test greedy optimization over compiler actions using the CompilerGym manual environment shell', 'test the print_service_capabilities function across all CompilerGym environments using pytest parametrization', 'run the smoke test that prints service capabilities for each registered CompilerGym environment', 'test creating a CompilerGym environment with gym.make and printing its service capabilities', 'test handling EnvironmentNotSupported exceptions when an environment is not available on the current platform', 'test initializing absl flags before running the service capabilities smoke test', 'test the validate main function with valid LLVM benchmark CSV input via stdin', 'test the validate main function with a CSV file path as input argument', 'test the validate main function exits with error when given empty stdin input', 'test the validate main function detects mismatched reward values in benchmark CSV results', 'test the validate main function rejects CSV input with wrong number of columns']
```

Usage

```
{'test_validate_main_with_valid_llvm_csv': 'test the validate main function with valid LLVM benchmark CSV input via stdin', 'test_validate_main_with_csv_file': 'test the validate main function with a CSV file path as input argument', 'test_validate_main_with_empty_input': 'test the validate main function exits with error when given empty stdin input', 'test_validate_main_with_invalid_reward': 'test the validate main function detects mismatched reward values in benchmark CSV results', 'test_validate_main_with_invalid_csv_format': 'test the validate main function rejects CSV input with wrong number of columns'}
```

