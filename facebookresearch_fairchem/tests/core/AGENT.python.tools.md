# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/core/conftest.py

Prompts

```
['create an Approx wrapper for a numpy array with custom relative and absolute tolerance values', 'review the ApproxExtension class that overrides syrupy snapshot serialization and matching for numpy arrays', 'test the _try_parse_approx function to parse serialized Approx string representations back into Approx objects', 'build a pytest snapshot fixture using the ApproxExtension for approximate numpy array comparison in tests', 'create a parametrized dummy binary dataset fixture that generates ASE DB or CIF files for testing', 'test the fairchem CLI main function with a Hydra config YAML file', 'test the fairchem CLI main function with multi-rank CPU scheduler configuration', 'test the fairchem CLI main function throws ValueError on invalid runner input arguments', 'test the get_hydra_config_from_yaml function loads and validates a Hydra config from a YAML file', 'test the MockRunner save_state and load_state methods for checkpoint creation and state restoration', 'test the download_file_group function by mocking urlretrieve to validate path existence checks', 'run the download_large_files script with a file group argument like ALL or odac', 'test the urlretrieve mock side effect that raises ValueError when target directory is missing', 'run download_file_group with ALL to download all file groups from the S3 root', 'review the test_download_large_files test that patches urlretrieve and validates fairchem directory structure', 'run launch_main with sys_args list to invoke the fairchem CLI with custom arguments in a test context', 'test the fairchem CLI by calling launch_main with a list of command-line arguments', 'refactor launch_main to add custom cleanup or setup logic before and after calling the fairchem main entry point', 'review launch_main to understand how it cleans up GP utils, distutils, and Hydra state between test runs', 'summarize how launch_main resets sys.argv and invokes the fairchem CLI main function for testing']
```

Usage

```
{'create_Approx': 'create an Approx wrapper for a numpy array with custom relative and absolute tolerance values', 'review_ApproxExtension': 'review the ApproxExtension class that overrides syrupy snapshot serialization and matching for numpy arrays', 'test_try_parse_approx': 'test the _try_parse_approx function to parse serialized Approx string representations back into Approx objects', 'build_snapshot_fixture': 'build a pytest snapshot fixture using the ApproxExtension for approximate numpy array comparison in tests', 'create_dummy_binary_dataset': 'create a parametrized dummy binary dataset fixture that generates ASE DB or CIF files for testing'}
```

## File: facebookresearch_fairchem/tests/core/test_cli.py

Prompts

```
['create an Approx wrapper for a numpy array with custom relative and absolute tolerance values', 'review the ApproxExtension class that overrides syrupy snapshot serialization and matching for numpy arrays', 'test the _try_parse_approx function to parse serialized Approx string representations back into Approx objects', 'build a pytest snapshot fixture using the ApproxExtension for approximate numpy array comparison in tests', 'create a parametrized dummy binary dataset fixture that generates ASE DB or CIF files for testing', 'test the fairchem CLI main function with a Hydra config YAML file', 'test the fairchem CLI main function with multi-rank CPU scheduler configuration', 'test the fairchem CLI main function throws ValueError on invalid runner input arguments', 'test the get_hydra_config_from_yaml function loads and validates a Hydra config from a YAML file', 'test the MockRunner save_state and load_state methods for checkpoint creation and state restoration', 'test the download_file_group function by mocking urlretrieve to validate path existence checks', 'run the download_large_files script with a file group argument like ALL or odac', 'test the urlretrieve mock side effect that raises ValueError when target directory is missing', 'run download_file_group with ALL to download all file groups from the S3 root', 'review the test_download_large_files test that patches urlretrieve and validates fairchem directory structure', 'run launch_main with sys_args list to invoke the fairchem CLI with custom arguments in a test context', 'test the fairchem CLI by calling launch_main with a list of command-line arguments', 'refactor launch_main to add custom cleanup or setup logic before and after calling the fairchem main entry point', 'review launch_main to understand how it cleans up GP utils, distutils, and Hydra state between test runs', 'summarize how launch_main resets sys.argv and invokes the fairchem CLI main function for testing']
```

Usage

```
{'test_cli_main': 'test the fairchem CLI main function with a Hydra config YAML file', 'test_cli_multi_rank': 'test the fairchem CLI main function with multi-rank CPU scheduler configuration', 'test_cli_error_handling': 'test the fairchem CLI main function throws ValueError on invalid runner input arguments', 'test_get_hydra_config_from_yaml': 'test the get_hydra_config_from_yaml function loads and validates a Hydra config from a YAML file', 'test_mockrunner_save_load_state': 'test the MockRunner save_state and load_state methods for checkpoint creation and state restoration'}
```

## File: facebookresearch_fairchem/tests/core/test_download_large_files.py

Prompts

```
['create an Approx wrapper for a numpy array with custom relative and absolute tolerance values', 'review the ApproxExtension class that overrides syrupy snapshot serialization and matching for numpy arrays', 'test the _try_parse_approx function to parse serialized Approx string representations back into Approx objects', 'build a pytest snapshot fixture using the ApproxExtension for approximate numpy array comparison in tests', 'create a parametrized dummy binary dataset fixture that generates ASE DB or CIF files for testing', 'test the fairchem CLI main function with a Hydra config YAML file', 'test the fairchem CLI main function with multi-rank CPU scheduler configuration', 'test the fairchem CLI main function throws ValueError on invalid runner input arguments', 'test the get_hydra_config_from_yaml function loads and validates a Hydra config from a YAML file', 'test the MockRunner save_state and load_state methods for checkpoint creation and state restoration', 'test the download_file_group function by mocking urlretrieve to validate path existence checks', 'run the download_large_files script with a file group argument like ALL or odac', 'test the urlretrieve mock side effect that raises ValueError when target directory is missing', 'run download_file_group with ALL to download all file groups from the S3 root', 'review the test_download_large_files test that patches urlretrieve and validates fairchem directory structure', 'run launch_main with sys_args list to invoke the fairchem CLI with custom arguments in a test context', 'test the fairchem CLI by calling launch_main with a list of command-line arguments', 'refactor launch_main to add custom cleanup or setup logic before and after calling the fairchem main entry point', 'review launch_main to understand how it cleans up GP utils, distutils, and Hydra state between test runs', 'summarize how launch_main resets sys.argv and invokes the fairchem CLI main function for testing']
```

Usage

```
{'test_download_file_group': 'test the download_file_group function by mocking urlretrieve to validate path existence checks', 'run_download_large_files_cli': 'run the download_large_files script with a file group argument like ALL or odac', 'test_urlretrieve_mock_side_effect': 'test the urlretrieve mock side effect that raises ValueError when target directory is missing', 'run_download_file_group_all': 'run download_file_group with ALL to download all file groups from the S3 root', 'review_download_large_files_test': 'review the test_download_large_files test that patches urlretrieve and validates fairchem directory structure'}
```

## File: facebookresearch_fairchem/tests/core/testing_utils.py

Prompts

```
['create an Approx wrapper for a numpy array with custom relative and absolute tolerance values', 'review the ApproxExtension class that overrides syrupy snapshot serialization and matching for numpy arrays', 'test the _try_parse_approx function to parse serialized Approx string representations back into Approx objects', 'build a pytest snapshot fixture using the ApproxExtension for approximate numpy array comparison in tests', 'create a parametrized dummy binary dataset fixture that generates ASE DB or CIF files for testing', 'test the fairchem CLI main function with a Hydra config YAML file', 'test the fairchem CLI main function with multi-rank CPU scheduler configuration', 'test the fairchem CLI main function throws ValueError on invalid runner input arguments', 'test the get_hydra_config_from_yaml function loads and validates a Hydra config from a YAML file', 'test the MockRunner save_state and load_state methods for checkpoint creation and state restoration', 'test the download_file_group function by mocking urlretrieve to validate path existence checks', 'run the download_large_files script with a file group argument like ALL or odac', 'test the urlretrieve mock side effect that raises ValueError when target directory is missing', 'run download_file_group with ALL to download all file groups from the S3 root', 'review the test_download_large_files test that patches urlretrieve and validates fairchem directory structure', 'run launch_main with sys_args list to invoke the fairchem CLI with custom arguments in a test context', 'test the fairchem CLI by calling launch_main with a list of command-line arguments', 'refactor launch_main to add custom cleanup or setup logic before and after calling the fairchem main entry point', 'review launch_main to understand how it cleans up GP utils, distutils, and Hydra state between test runs', 'summarize how launch_main resets sys.argv and invokes the fairchem CLI main function for testing']
```

Usage

```
{'run_launch_main': 'run launch_main with sys_args list to invoke the fairchem CLI with custom arguments in a test context', 'test_launch_main': 'test the fairchem CLI by calling launch_main with a list of command-line arguments', 'refactor_launch_main': 'refactor launch_main to add custom cleanup or setup logic before and after calling the fairchem main entry point', 'review_launch_main': 'review launch_main to understand how it cleans up GP utils, distutils, and Hydra state between test runs', 'summarize_launch_main': 'summarize how launch_main resets sys.argv and invokes the fairchem CLI main function for testing'}
```

