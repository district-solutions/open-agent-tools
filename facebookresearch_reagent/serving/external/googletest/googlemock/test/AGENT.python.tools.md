# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/serving/external/googletest/googlemock/test/gmock_leak_test.py

Prompts

```
['test that leaked mock objects are caught by default in Google Mock', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks is disabled', 'test that leaked mocks are caught when gmock_catch_leaked_mocks is explicitly enabled', 'test that leaked mocks are caught when gmock_catch_leaked_mocks equals 1', 'test that multiple leaked mock objects are all caught by Google Mock', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from gmock output text', 'remove file location info from Google Test output and replace with normalized FILE:#: format', 'get the absolute path of the directory where the gmock test python files are located', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from an os.system result on Unix or Windows', 'run a subprocess and capture its output using the gmock Subprocess utility class', 'run the gmock unit test suite by calling the Main entry point function']
```

Usage

```
{'test_leaked_mock_by_default': 'test that leaked mock objects are caught by default in Google Mock', 'test_leaked_mock_disabled': 'test that leaked mocks are not caught when gmock_catch_leaked_mocks is disabled', 'test_leaked_mock_enabled': 'test that leaked mocks are caught when gmock_catch_leaked_mocks is explicitly enabled', 'test_leaked_mock_explicit_flag': 'test that leaked mocks are caught when gmock_catch_leaked_mocks equals 1', 'test_multiple_leaked_mocks': 'test that multiple leaked mock objects are all caught by Google Mock'}
```

## File: facebookresearch_reagent/serving/external/googletest/googlemock/test/gmock_output_test.py

Prompts

```
['test that leaked mock objects are caught by default in Google Mock', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks is disabled', 'test that leaked mocks are caught when gmock_catch_leaked_mocks is explicitly enabled', 'test that leaked mocks are caught when gmock_catch_leaked_mocks equals 1', 'test that multiple leaked mock objects are all caught by Google Mock', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from gmock output text', 'remove file location info from Google Test output and replace with normalized FILE:#: format', 'get the absolute path of the directory where the gmock test python files are located', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from an os.system result on Unix or Windows', 'run a subprocess and capture its output using the gmock Subprocess utility class', 'run the gmock unit test suite by calling the Main entry point function']
```

Usage

```
{'run_gmock_output_test': 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate_golden_file': 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize_test_output': 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract_leaky_tests': 'extract a list of test names that leak mock objects from gmock output text', 'remove_file_locations': 'remove file location info from Google Test output and replace with normalized FILE:#: format'}
```

## File: facebookresearch_reagent/serving/external/googletest/googlemock/test/gmock_test_utils.py

Prompts

```
['test that leaked mock objects are caught by default in Google Mock', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks is disabled', 'test that leaked mocks are caught when gmock_catch_leaked_mocks is explicitly enabled', 'test that leaked mocks are caught when gmock_catch_leaked_mocks equals 1', 'test that multiple leaked mock objects are all caught by Google Mock', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from gmock output text', 'remove file location info from Google Test output and replace with normalized FILE:#: format', 'get the absolute path of the directory where the gmock test python files are located', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from an os.system result on Unix or Windows', 'run a subprocess and capture its output using the gmock Subprocess utility class', 'run the gmock unit test suite by calling the Main entry point function']
```

Usage

```
{'get_source_dir': 'get the absolute path of the directory where the gmock test python files are located', 'get_test_executable_path': 'get the absolute path of a gmock test binary given its executable name', 'get_exit_status': 'extract the exit status code from an os.system result on Unix or Windows', 'run_subprocess': 'run a subprocess and capture its output using the gmock Subprocess utility class', 'run_main': 'run the gmock unit test suite by calling the Main entry point function'}
```

